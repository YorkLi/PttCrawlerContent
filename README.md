# PttCrawlerContent (PTT文章爬蟲)

PTT文章爬蟲 for Windows and Linux
* [Demo Video](https://www.youtube.com/watch?v=Caqxj8uci9M&feature=youtu.be) - Windows

## 特色
* 抓取PTT 文章

## 輸出格式
* 文字檔

## 執行方法
```
python PttCrawler.py  [版名]   [抓取頁數]   [搜尋關鍵字](可省略)
```
 
## 執行範例
抓取PTT Gossiping版 2頁 文章內容
```
python PttCrawler.py  Gossiping  2 
```

抓取PTT Gossiping版 1頁 文章內容 且內容含有「台灣」兩字
```
python PttCrawler.py  Gossiping  2 台灣
```

## 執行畫面
![alt tag](http://i.imgur.com/r4dkGtC.jpg)
![alt tag](http://i.imgur.com/pgNjE6n.jpg)
![alt tag](http://i.imgur.com/rS5eIi7.jpg)

## Environment
Python3.5.2 (相容於Python 2.7.3)
  
## License
MIT license
