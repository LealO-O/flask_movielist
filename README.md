# flask_movielist
《flask入门教程》项目
.flaskenv 用来存储 Flask 命令行系统相关的公开环境变量；而 .env 则用来存储敏感数据\n
我们把包含变量和运算逻辑的 HTML 或其他格式的文本叫做模板，执行这些变量替换和逻辑计算工作的过程被称为渲染，这个工作由我们这一章要学习使用的模板渲染引擎——Jinja2 来完成。
{{ ... }} 用来标记变量。\n
{% ... %} 用来标记语句，比如 if 语句，for 语句等。
{# ... #} 用来写注释。
index.html ---chapter3
Jinja2 提供了一些过滤器，语法形式如下：
{{ 变量|过滤器 }}
左侧是变量，右侧是过滤器名。比如，上面的模板里使用 length 过滤器来获取 movies 的长度，类似 Python 里的 len() 函数。
可以借助前端框架来完善页面样式，比如 Bootstrap、Semantic-UI、Foundation 等。它们提供了大量的 CSS 定义和动态效果，使用起来非常简单。
扩展 Bootstrap-Flask 可以简化在 Flask 项目里使用 Bootstrap 的步骤。
