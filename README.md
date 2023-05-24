[中文](https://github.com/nuistZPZ/siyuan-template-RememberEnglish/blob/master/README_zh_CN.md)

# Reverse linking to remember words skillfully

Share a set of templates used when memorizing words, used to record the inspiration associated with memorizing words, you need to download the pendant Note Backlink and Query first.

 [langzhou/note-backlinks： 思源笔记挂件：类似 Roam Research，在文档页面内展示反向链接 (github.com)](https://github.com/langzhou/note-backlinks) 

 [Zuoqiu-Yingyi/widget-query： 一个将思源笔记数据库查询结果以表格样式渲染的挂件 |以表格样式呈现思源笔记数据库查询结果的小组件。 (github.com)](https://github.com/Zuoqiu-Yingyi/widget-query) 



## Usage Scenarios

Using backlinks allows us to remember words anywhere without the clutter of not finding them in relation to each other.

Jot down a word on the fly and use the shortcut [[]] or UI to create a new page with that word as the title.

![img1.png (1387×342) (gitee.io)](https://nuistzpz.gitee.io/static/siyuan/template/RememberEnglish/img1.png) 





## Example

Each word is written on a separate page that is used to record all information about that word.

![img1.png (1387×342) (gitee.io)](https://nuistzpz.gitee.io/static/siyuan/template/RememberEnglish/1684721435700.png)

Using the two-way links, you can jump to the related words page and also see which words are related to it.

Take template for example, I have sentences elsewhere that reference template without me having to manually add this sentence to the example sentence in template, and I can find example sentences in template that I have used before.

![img1.png (1387×342) (gitee.io)](https://nuistzpz.gitee.io/static/siyuan/template/RememberEnglish/1684721176339-1684724617183.png)

Use SQL to query recorded words to form your own unique word book. Provide templates to find all words, created in the last N days, updated in the last N days, alphabetical search, etc.

### SQL parameters explanation

#### General parameters

- **hpath means the location where the file is stored**

```
hpath like "/%"  在/后面添加文件夹名称
```

- **type means the type of the block**

```
type = "d" 中的d代表文档块
```

- **content means the content of the block**

```

```

#### Query all words

The limit 1000 is used because, by default, Siyuan only returns 64. If your word bank exceeds 1000, please replace it with a larger number. Same as below

![img1.png (1387×342) (gitee.io)](https://nuistzpz.gitee.io/static/siyuan/template/RememberEnglish/1684851769970.png)



#### Query by word initials

Replace the a in content like "a%" with the letter you are looking for

![img1.png (1387×342) (gitee.io)](https://nuistzpz.gitee.io/static/siyuan/template/RememberEnglish/1684851616465.png)

#### Words created in the last N days

Replace -1 of -1 day with the date you want, such as the last three days, please use -3 day

![img1.png (1387×342) (gitee.io)](https://nuistzpz.gitee.io/static/siyuan/template/RememberEnglish/1684851901101.png)



## Acknowledgements

Thanks to the author of the two pendants and to the author of Siyuan.