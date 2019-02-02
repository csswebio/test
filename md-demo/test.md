# Markdown Syntax

## 一、文字
|        | 語法 | 效果      |
|:-------|:----|:---------|
| 1.斜體  | _   | _斜體_    |
| 2.粗體  | __  | __粗體__  |
| 3.刪除線 | ~~ | ~~刪除線~~ |
| 4.螢光筆 | == | ==螢光筆== |
| 5.底線  | ++  | ++底線++  |
| 6.上標  | \<sup> | 文<sup>上標<sup>  |
| 7.下標  | \<sub> | 文<sub>下標<sub>  |
    
## 二、排版
|        | 語法   | 效果      |
|:-------|:------|:---------|
| 1.標提  | # ##  | #h1 ##h2 |
| 2.分隔線 | ===  | =========|
| 3.列清單 | - + * | - fst + snd|
| 4.引用名 | > [name=] | =Martin | 
| 5.引用時 | > [time=] | =Jun 28, 2019 | 
| 6.註記   | [^note]   | [^note]: 敘述 |
| 7.表格  | \|:-----:\| | \| 欄位 \| 內容 \| | 

## 三、網頁              
|        | 語法    | 效果   |
|:-------|:-------|:-------|
| 1.嵌入  | \`\`\` | ```xml ``` |
| 2.連結  | \[site]( http:// ) |[yahoo](http://yahoo.com "yahoo")|
| 3.圖片  | !\[title]( http:// =200x200 ) | ![cat](http://web.io/cat.jpg "cat") |
| 4.標籤  | tags: \`html5\` | tags: `html5`
| 5.外錨 | \[yweb]: http://yahoo.com | [yahoo][yweb] |
| 6.外部  | Youtube \{%youtube 1G4isv_Fylg %} | Youtube {%youtube 1G4isv_Fylg %}

## 四、圖表
|        | 語法 | 效果 |
|:-------|:----|:---------|
| 1.循序圖 | sequence | ```sequence ``` |
| 2.流程圖 | flow     | ```flow ``` |
| 3.樹節點 | graphviz | ```graphviz ``` |
| 4.甘特圖 | mermaid  | ```mermaid ``` |
| 5.目錄   | \<details>\<summary> | <details><summary> 目錄標題 |
