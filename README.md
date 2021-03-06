
|                         博客部署狀態                         |
| :----------------------------------------------------------: |
| ![部署狀態](https://api.travis-ci.com/LiuPhoenix/LiuPhoenix.github.io.svg?branch=master&status=started) |



### **注意事項:**

* 請保持這個 repo 公開, 不然自動部署將無法工作
* 請不要刪除 issue, 他們將是博客的評論
* 請不要改動 Personal Settings 裡的任何一項

### **原理:**

* 博客用 Hexo 部署到 Gitpages 上面.
* 你可以訪問你的 [TravisCi](https://travis-ci.com) , 用 Github 登陸, 它幫助你自動構建你的博客
* 生成的文件放在 `gh-pages` 這個分支裡面, 你可以看到

### **如何寫博客:**

1. 訪問git倉庫中的 [source/_posts](https://github.com/LiuPhoenix/LiuPhoenix.github.io/tree/master/source/_posts)
2. 點擊右上角的 Add File -> Create a new file

![Screen Shot 2021-03-22 at 10.02.19 PM.png](https://i.loli.net/2021/03/22/J7vR5DFwAylGade.png)

3. 如上圖所示, 輸入文件名, 格式為 `標題.md`
4. 將下列模板填入大片空白中 ( 按照需求修改)

```
---
title: 此處寫入標題
description: 你對博文的描述
date: 2099-12-31 23:59:59
categories:
 - 你的分類
 - 你的分類(如果有第二個)
---

# H1
## H2
### H3

normal text
**bold text**
*italicized text*
> blockquote
`code`
[title](https://www.example.com)
![alt text](image.jpg)
~~The world is flat.~~

1. First item
2. Second item
3. Third item

- First item
- Second item
- Third item

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


Here's a sentence with a footnote. [^1]
[^1]: This is the footnote.
```

5. 你隨時都可以通過 Preview 按鈕來預覽自己寫好的博文.
6. 點擊最下方的 Commit Changes 綠色按鈕發布博文

![image.png](https://i.loli.net/2021/03/22/F9gsCcykSNKBxVA.png)

7. 將電腦放置一段時間讓其自然生成, 刷新頁面後若途中黃色點變為綠色, 或者本教程開頭的圖標顯示為 Passing, 則成功.



如果網頁沒有顯示, 記得刷新瀏覽器;  
如果小圓點變為紅色, 檢查你的博文格式有沒有出問題;  
當然你也可以隨時聯繫我.

### **Howto...**

* 評論:

![Screen Shot 2021-03-22 at 10.27.19 PM.png](https://i.loli.net/2021/03/22/EkBR3K2oN9eg1bu.png)

如圖所示, 每篇博文初始化一下評論然後用 Git 登陸即可.

* 插入圖片

將你的圖片上傳到圖床:

[sm.ms](https://sm.ms)

會自動生成可供插入的 Markdown.

### **高階玩法**

這我幫不了你, 下面是你用得到的資源

* [Hexo 官網](https://hexo.io)
* [Keep 主題官網](https://keep-docs.xpoet.cn)
* [Github 傻瓜指南](https://www.runoob.com/w3cnote/git-guide.html)
