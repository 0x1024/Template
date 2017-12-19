# Template
good form of struct for manage project

.gitignore：确保忽略不属于项目的文件。这是一种常见的失策。

CODE_OF_CONDUCT.md：在项目中放入一些有关您期望贡献者表现出的行为的信息，这是一个不错的主意。

CONTRIBUTING.MD：有关您将如何接受贡献的明确说明会对招聘很有帮助。

LICENSE：拥有一个许可（比如 MIT或 BSD）会很有帮助。在某些情况下，如果您没有许可，一个潜在的贡献者可能无法参与项目。

Makefile：makefile 是一种运行测试、部署和设置环境的优秀工具。

README.md：良好的 README.md 会回答基本问题，比如用户如何构建项目和项目有何用途。此外，README.md 可能提供“徽章”来显示项目的质量，比如一次已通过的构建。

命令行工具：在我的示例中，有一个 dml 命令行工具。拥有一个 cli 接口，这对探索您的库和创建实例来执行测试都很有帮助。

包含 __init__.py 的库目录：在项目的根目录位置，应该创建一个包含 __init__.py 的库目录来表明它是可导入的。在本例中，该库名为 devml。

ext 目录：此目录是放置 config.json 或 config.yml 文件之类内容的好地方。将非代码内容放在一个可以集中引用的地方会更好。可能还需要一个 data 子目录来创建一些本地删减样本（用于探索）。

notebooks 目录：一个包含 Jupyter Notebook 的特定目录，有助于轻松地集中开发与 notebook 相关的代码。此外，它还使得设置 notebook 的自动化测试变得更容易。

requirements.txt：一个包含项目所需的包列表的文件。

setup.py：一个设置 Python 包的部署方式的配置文件。也可以使用该文件将 Python 包部署到 Python Package Index。

tests 目录：一个放置测试数据的目录。
