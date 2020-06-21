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

