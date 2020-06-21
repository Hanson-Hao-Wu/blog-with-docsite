# Readme



> document: [docsite](https://docsite.js.org/zh-cn/index.html)



## Change Default Langauge

> site_config/site.js

```
defaultLanguage: 'zh-cn',
```



## Add Blog



1. add markdown file in `blog/zh-cn/markdown.md`
2. site_config/blog.js add:

```json
{
	title: 'First Markdown',
	author: 'Hao',
	dateStr: 'June 21st，2020',
	desc: 'First Markdown',
	link: '/zh-cn/blog/markdown.html',
},
```



## Add Doc



1. add markdown file in `docs/zh-cn/markdown.md`
2. site_config/docs.js add:

```
{
	title: 'Markdown',
	link: '/zh-cn/docs/markdown.html',
},
```



## publish in the Github



`settings` > `GitHub Pages` > `Source` > master

> Your site is ready to be published at https://hanson-hao-wu.github.io/blog-with-docsite/.



## Ref.

[如何打造一款静态开源站点搭建工具](https://juejin.im/post/5b95dbeee51d450e51624539)