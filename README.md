# 已知現存中文 BBS 站台

###### tags: `telnet` `BBS` `電子布告欄` `站台`

## 相關連結
* stable version: [on GitHub](https://github.com/bbslist/bbslist.github.io)
* Co-writing version: [on HackMD](https://hackmd.io/r1pdt-59b)

共筆版本(Co-writing version)可自由編輯，穩定版本(stable version)則是一段時間後，確認沒太大問題的修改才會 push 上去，若覺得 GitHub 版本太久沒更新可去[提 issue](https://github.com/bbslist/bbslist.github.io/issues)，整體資訊是否過時與過於老舊，以及之後有沒有更好的方法，則取決於能協助確認資訊、改善方法的大大們有多少了。

## 數量
* 目前統計約 **57** 個

## 近期修正與補充欄位

* BBS 站台程式版本 (追溯至最近開源版本)
* 支援加密連線資訊 *(Web 版網址待補)*
* 列表以 telnet 連線為基礎的站台為主，若只有 Web 論壇形式的站台暫不列入。
* **`twbbs.org`** 網域已經終止服務，故暫不附上相關網域資訊
* Current Ptt 版號可搭配 [此連結](https://github.com/ptt/pttbbs/blob/master/UPDATING) 了解其重大差異

還請其他熱心人士協助編輯補充 `^_^`

## 大學相關站台

| 可連線？ | 站名 | 位址 | 加密 | BBS 版本 | 備註 |
| - | - | - | - | - | - |
|  :x: | 銘傳大學 築夢別境 | <telnet://bbs.mcu.edu.tw> | | [Maple3](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/) | |
| :x: | 逢甲紡織 七月七日晴 | <telnet://77bbs.com> | | [Wind & Dust](http://ftp.isu.edu.tw/pub/Unix/BBS/WD/) | |
|  :white_check_mark: | 東華大學 東方小城 | <telnet://bbs.ndhu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 目前 telnet 連線的看板列表錯誤，會導致斷線；web 連線正常|
|  :white_check_mark: | 東吳機研站 | <telnet://scumotor.com.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
|  :x: | 東海大學 資訊傳奇 | <telnet://bbs.csie.thu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
|  :x: | 東海數學 陽光草坪 | <telnet://122.117.69.100> | | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
|  :x: | 淡江資管 渡船頭之戀 | <telnet://bbs.im.tku.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
|  :x: | 淡江蛋捲 新系統測試站 | <telnet://loyal.ee.tku.edu.tw> | | [天火系統](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) | 2019-10-30 測試: 連線失敗 |
|  :x: | 淡江資管 星星之戀 | <telnet://starlove.im.tku.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)| |
|  :white_check_mark: | 台大批踢踢   |   <telnet://ptt.cc> <br>  [ip](telnet://140.112.172.11) / [ip~1~](telnet://140.112.172.1) / [ip~2~](telnet://140.112.172.2) / [ip~3~](telnet://140.112.172.3) /  [ip~4~](telnet://140.112.172.4) / [ip~5~](telnet://140.112.172.5)  | [:white_check_mark:](#加密連線站台資料列表) | [Current Ptt](https://github.com/ptt/pttbbs) | guest無法登入 | 
|  :white_check_mark: | 批踢踢兔  | <telnet://ptt2.cc> | [:white_check_mark:](#加密連線站台資料列表) | [Current Ptt](https://github.com/ptt/pttbbs) | guest無法登入 |
|  :x: | 批踢踢參 | <telnet://ptt3.cc> | [:x:](#加密連線站台資料列表) | [CurrentPtt](https://github.com/ptt/pttbbs) <br> trunk r4423 | 2019-10-30 測試: 連線失敗 |
|  :white_check_mark: | 台大未來最舊 | <telnet://ofo.tw> | [:white_check_mark:](#加密連線站台資料列表) | [Sun of Beach](http://ftp.isu.edu.tw/Unix/BBS/SOB/) | 不開放guest |
|  :white_check_mark: | 台大 不良牛 | <telnet://bbs.badcow.com.tw> | | [Sun of Beach](http://ftp.isu.edu.tw/Unix/BBS/SOB/) | 因仍有 DNS 反查, 部份BBS瀏覽器不支援 |
|  :x: | 台大物理 冷月流蘇 | <telnet://bbs.phys.ntu.edu.tw> <br> <telnet://bbs.phys.tw> |  | [Wind & Dust](http://ftp.isu.edu.tw/pub/Unix/BBS/WD/) | |
|  :white_check_mark: | 台大資管 鳴蟬小站 墮落天堂 | <telnet://bbs.im.ntu.edu.tw> | [:x:](#加密連線站台資料列表) | [Sun of Beach](http://ftp.isu.edu.tw/Unix/BBS/SOB/) | 2019-10-30 測試: <wss://tolo.ntu.im/bbs> 連線失敗|
|  :x: | 台北醫學大學 杏林綠意 | <telnet://bbs.tmu.edu.tw> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 另外有很多班板在未來最舊小站 |
|  :white_check_mark: | 臺北大學 北極星 |   <telnet://bbs.ntpu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
|  :white_check_mark: | 臺北市立大學 七號出口 |   <telnet://bbs.utaipei.edu.tw> | | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 台中教育大學 柳岸咖啡館 | <telnet://bbs.ntcu.edu.tw> | | 未納入版本管理的 Maple-itoc fork | 硬碟毀損，域名屬於學校，目前無復站希望，詳見 [#4](https://github.com/bbslist/bbslist.github.io/issues/4) |
| :x: | 高雄大學 原野星辰 | <telnet://bbs.nuk.edu.tw> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 海洋大學 | <telnet://bbs.ntou.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 海洋電機 忘晴海 | <telnet://bbs.ee.ntou.edu.tw> | | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 交通大學 次世代 | <telnet://bs2.to> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [已關站](https://www.ptt.cc/bbs/NCTU_TALK/M.1461738017.A.8BA.html) |
| :white_check_mark: | 次世代．佚 | <telnet://bs2.io> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [另外發起](https://www.ptt.cc/bbs/NCTU_TALK/M.1469423697.A.2AE.html)之相關延續站台 |
| :white_check_mark:  | 淒美燈塔  |  <telnet://bbs.pharos.rocks> | [:white_check_mark:](#加密連線站台資料列表) | [Maple3](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/) | 2019-10-31 測試: Websocket up |
| :white_check_mark:  | 交通大學 機械工廠  |  <telnet://bbs.me.nctu.edu.tw> | | [Maple3.10-itoc](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/) | |
| :x:  | 暨大電機 漂浮電子 | <telnet://bbs.ee.ncnu.edu.tw>| | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark:  | 暨大土木 土木小站 | <telnet://bbs.ce.ncnu.edu.tw>| | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) |無法使用guest，以及看板列表毀損 |
| :x: | 靜宜水世界  | <telnet://bbs.cs.pu.edu.tw> | | | 2017/1/5測試：down
| :white_check_mark: | 暨南大學 水沙連 | <telnet://bbs.ncnu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 清華大學 楓橋驛站 | **因防火牆設定問題，請先使用 port 443**：<br>**<telnet://bbs.cs.nthu.edu.tw:443>**<br>**<telnet://140.114.87.5:443>**<br>**<telnet://imaple.tw:443>**<br>~~<telnet://bbs.cs.nthu.edu.tw>~~ <br> ~~<telnet://imaple.tw>~~ <br> ~~<telnet://140.114.87.5>~~ | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | (2007年, 系統從自己開發的系統, 轉換成 itoc 大 fork 出來的版本 繼續維護)
| :x: | 清華資工 呼拉貝爾 | <telnet://114.32.9.125> | | [WindTop BBS](http://windtop.yzu.edu.tw/) |  |
| :white_check_mark: | 中央大學 二進位 | <telnet://140.115.50.50> <br> <telnet://binary.csie.ncu.edu.tw> <br> <telnet://bbs.ncu.cc> | | [Wind & Dust](http://ftp.isu.edu.tw/pub/Unix/BBS/WD/) | 2019-10-30 測試: Up (<telnet://bbs.ncu.cc> 連線失敗) |
| :white_check_mark: | 中央數學 織夢天堂 | <telnet://bbs.math.ncu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 中山大學 美麗島 | <telnet://140.117.11.2> <br> <telnet://bbs.nsysu.edu.tw> | | [Formosa BBS](https://github.com/pigfoot/formosa) | |
| :white_check_mark: | 中山大學 西子灣 | <telnet://140.117.11.6> <br> <telnet://bbs3.nsysu.edu.tw> | | [Formosa BBS](https://github.com/pigfoot/formosa) | |
| :white_check_mark: | 中正築夢園 | <telnet://140.123.29.12> <telnet://cd.cna.ccu.edu.tw>| | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) |已由Maple 3 轉至 Maple3.10-itoc 版本 |
| :x: | 中正大學 寂寞芳心小站 | <telnet://bbs.ccu.edu.tw> | | [Maple3.02](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/)  |2018/8/3測試：down |
| :white_check_mark: | 中正大學 闇黑國度 | <telnet://bbs.cna.ccu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 中正通訊 1394 | <telnet://bbs.comm.ccu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 中正心理 心海奇航 賽卡羅旗號 | <telnet://140.123.185.40> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 政大資科 貓空行館 | <telnet://bbs.cs.nccu.edu.tw> | | [Maple3.02](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/) |
| :white_check_mark: | 彰師生命 擎天崗 | <telnet://bbs.bio.ncue.edu.tw> <br> <telnet://bbs2.ncue.edu.tw> <br> <telnet://micro.bio.ncue.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 真理大學 雲淡風清 | <telnet://bbs.au.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 真理大學 脆笛酥的家 | <telnet://bbs.jal.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 成功大學 夢之大地 |  ~~telnet://140.116.250.3~~ **(IP已更改)** <br> [telnet://140.116.249.140](telnet://140.116.249.140/) **(現在IP)** <br> [telnet://bbs.ccns.ncku.edu.tw](telnet://bbs.ccns.ncku.edu.tw/) <br> <telnet://ccns.cc> **(新網域)** | | [WindTop BBS](http://windtop.yzu.edu.tw/) <br> [Dreamlandbbs](https://github.com/ccns/dreamlandbbs) | |
| :white_check_mark: | 成大醫學 迴風谷 | <telnet://bbs.med.ncku.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 成大電機 風之谷 | <telnet://bbs.ee.ncku.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | guest無法登入，停止線上註冊| |
| :x: | 長庚大學 巧克力傳奇 | <telnet://bbs.cgu.edu.tw> |
| :x: | 長庚醫學 醫甸園 | <telnet://bbs.med.cgu.edu.tw> | | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 師大資訊 白色情迷 | <telnet://bbs.csie.ntnu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 師大數學 獨數一閣 | <telnet://bbs.math.ntnu.edu.tw> | | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5284 |
| :white_check_mark: | 師大 人民公社 | <telnet://cvic.org> <br> <telnet://cvic.be> | | [Sun of Beach](http://ftp.isu.edu.tw/Unix/BBS/SOB/) | 2019-10-31 測試: Up |
| :x: | 師大歷史 原史空間 | <telnet://bbs.his.ntnu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 慈濟大學 蔚藍海岸  | <telnet://perlbbs.tw> | | [Sun of Beach](http://ftp.isu.edu.tw/Unix/BBS/SOB/) | |
| :x: | 陽明 神農坡 | <telnet://bbs.ym.edu.tw> | | [Maple3](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/) | PCman主要作者畢業學校 |
| :white_check_mark: | 元智大學 風之塔 | <telnet://bbs.yzu.edu.tw> | | [WindTop BBS](http://windtop.yzu.edu.tw/) | 2019-10-30 測試: Up |
| :x: | 雲林科技大學 藍天使 | <telnet://bbs.yuntech.edu.tw> | | | 2017/1/5測試：down |
| :x: | 中央 神通廣大 | <telnet://bbs.ce.ncu.edu.tw> | | | |
| :white_check_mark: | 中原資工 神祕之旅 | <telnet://bbs.ice.cycu.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |

## 高中相關站台

| 可連線？ | 站名 | 位址 | 加密 | BBS 版本 | 備註 |
| - | - | - | - | - | - |
| :white_check_mark: | 建中之夏 烏魯木齊 | <telnet://bbs.ck.tp.edu.tw>| | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 北一女中 弗基斯特 | <telnet://fgisc.org>  | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 中山女中 楓資羽翼 | <telnet://203.68.236.13> <br> <telnet://csisc.csghs.tp.edu.tw> | | [WindTop](http://windtop.yzu.edu.tw/) → [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2019-10-30 測試: Telnet 連線無回應；可連網頁版 <br> (有網頁版：<http://bbs.csghs.tp.edu.tw/>) |
| :x: | 成功高中 沉澱日記 | <telnet://203.71.24.161> <br> <telnet://bbs.ckcsc.info> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 永春高中 永春哈哈 | <telnet://haha.ycsh.tp.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法進去看板閱讀， 僅能瀏覽公佈欄/精華區 |
| :x: | 中壢高中 壢網狂瀾 | <telnet://clhs.csie.org> | |[WindTop BBS](http://windtop.yzu.edu.tw/) |  |
| :white_check_mark: | 台中一中 龍夢紀元 | <telnet://bbs.tcfsh.tc.edu.tw> <br> <telnet://eod.tw> <br> <wss://eod.tw/bbs> |[:x:](#加密連線站台資料列表)| [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 可以相容於 PTT 的 Websocket 模式連線 <br> 程式碼為極光鯨藍之穩定版本分支
| :x: | 台中一中電研社 極光鯨藍 | [telnet://tcirc.org](telnet://tcirc.org/) <br> <wss://tcirc.org/bbs> | [:x:](#加密連線站台資料列表) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 可以相容於 PTT 的 Websocket 模式連線 <br> GitHub: https://github.com/MapleCirc/Auroral
| :x: | 台中二中 迷幻國度 | <telnet://csc241.tcssh.tc.edu.tw> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)
| :white_check_mark: | 台南一中 與南共舞 | <telnet://bbs.tnfsh.tn.edu.tw> <br> <telnet://wolf.tfcis.org> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台南一中資訊社  索尼小站 | <telnet://sony.tfcis.org> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台南一中 動力核心 | <telnet://cpu.tfcis.org> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) ||


## 不在學術網路的站台

| 可連線？ | 站名 | 位址 | 加密 | BBS 版本 | 備註 |
| - | - | - | - | - | - |
| :white_check_mark: | 風與塵埃的對話 | <telnet://wdbbs.tw> | | [Wind & Dust](http://ftp.isu.edu.tw/pub/Unix/BBS/WD/) |  |
| :white_check_mark: | 巴哈姆特BBS | <telnet://bbs.gamer.com.tw> <br> <telnet://bahamut.org> | [:white_check_mark:](#加密連線站台資料列表) | [Maple3.02](http://ftp.isu.edu.tw/Unix/BBS/Maple/Maple3/) | guest無法登入, 需先從 Web 註冊 |
| :white_check_mark: | 花魁異色館 |~~telnet://libido.cx~~ <telnet://74.52.17.106> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | guest無法登入，2018/10下旬起僅用IP連線 |
| :white_check_mark: | 亞特蘭提斯 | <telnet://125.227.52.214> | | Atlantis | 註冊通過者, 可自己開個板, 免等審核
| :x: | 月下夜想 | <telnet://220.130.248.130> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 反地球聯邦組織 | <telnet://122.116.74.57> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 台灣天主教BBS站 厄瑪奴耳 | <telnet://1.34.185.155> | | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 動漫遊戲廣播站 | <telnet://bbs.animeyo.com> |  | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 南友小站 |<telnet://tainan.jal.tw><br><telnet://192.192.120.31> |  | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 書齋軒 | <telnet://bbs.windcity.net> | | [Open Ptt](http://ftp.isu.edu.tw/unix/BBS/Ptt/openptt) | 提供個人及團體板 |
| :white_check_mark: | 華年小集 | <telnet://literature.twbbs.io> | | [Current Ptt](https://github.com/ptt/pttbbs)  <br> trunk r5563 | |
| :white_check_mark: | 網際新世界 | <telnet://209.141.35.127> | | [Sun of Beach](http://ftp.isu.edu.tw/Unix/BBS/SOB/) | |
| :white_check_mark: | 543 音樂站 | <telnet://music543.com> | | [Current Ptt](https://github.com/ptt/pttbbs)  <br> trunk r3359 | 2019-10-31 測試: Up (似乎有同 IP 不能同時連線的限制) |
| :white_check_mark: | 幸運草之戀 | <telnet://segaa.net>| | [WindTopBBS](http://windtop.yzu.edu.tw) | |
| :white_check_mark: | 內灣新小月台 | <telnet://bbs.emu486.net> | |[Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 
| :white_check_mark: | 西雅圖 | <telnet://www.seattle.ro> <telnet://seattle.ro> <telnet://59.126.126.89> | |[MapleBBS-3.10-20121021-PACK.itoc](https://github.com/xeonchen/maplebbs-itoc) | | 
| :white_check_mark: | 伙計小站 | <telnet://patw.idv.tw> | |[Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 
| :white_check_mark: | 八八八 | <telnet://bbs.wim888.tw>| |[Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 
| :white_check_mark: | △．Kirika | <telnet://andcycle.idv.tw> | |[Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 

## 中國大陸站台

| 可連線？ | 站名 | 位址 | 加密 | BBS 版本 | 備註 |
| - | - | - | - | - | - |
| :x: | 中科院 曙光站(智慧電腦中心) | <telnet://bbs.ncic.ac.cn> |
| :x: | 北京大學 | <telnet://bbs.pku.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 網頁版：<br>https://bbs.pku.edu.cn  |
| :white_check_mark: | 未名空間 | <telnet://mitbbs.com> | [:white_check_mark:](#加密連線站台資料列表) | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 相關衍生之商業BBS站台 |
| :x: | 北京大學 一塌糊塗 海外紀念站 | <telnet://bbs.ytht.net> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 北京大學 桃花潭 | <telnet://thtpku.3322.org> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 無法申請新帳號 + guest 瀏覽 |
| :x: | 清華大學  | <telnet://smth.org> | | | [無法連線](https://www.ptt.cc/bbs/SMTH/M.1415081920.A.2B0.html) |
| :x: | 清華大學 KissU | <telnet://bbs.thu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :white_check_mark: | 水木社區 |    <telnet://newsmth.org>     | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 相關衍生之商業BBS站台 |
| :x: | 南京大學 小百合 |     <telnet://bbs.nju.edu.cn> <br> <telnet://lilybbs.net> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 教育網 <br> 公眾網 |
| :x: | 哈爾濱工業大學 紫丁香站 |   <telnet://bbs.hit.edu.cn> | | | 無法連線,可能是限制校外ip連入或關站 |
| :white_check_mark: | 紫丁香社區 | <telnet://lilacbbs.com>      | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 相關衍生之商業BBS站台 |
| :x: | 上海交通大學 | <telnet://bbs.sjtu.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 廣西師範大學 煙雨漓江 | <telnet://bbs.gxnu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 四川大學 藍色星空站 | <telnet://virus.lsxk.org> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 復旦大學 日月光華_公網 | <telnet://bbs.fudan.sh.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 中國科大 瀚海星雲_公網 | <telnet://ustcbbs.ustc.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 華中理工 白云黃鶴 | <telnet://bbs.whnet.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 上海交大 飲水思源 | <telnet://bbs.sjtu.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 東南大學 虎踞龍盤 | <telnet://bbs.seu.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :x: | 中國礦業大學 放鶴亭 | <telnet://bbs.cumt.edu.cn> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |

註：
* 北京大學 一塌糊涂 20040913被關 telnet://ytht.net
* 清華大學 水木清華 20050316封校 telnet://smth.org
* 南京大學 小百合 20050322分站 telnet://bbs.nju.edu.cn

## 其他海外華文 BBS 站台

| 可連線？ | 站名 | 位址 | 加密 | BBS 版本 | 備註 |
| - | - | - | - | - | - |
| :x: | 美國 天天壇 | <telnet://tttan.com> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | |
| :white_check_mark: | 美國 San Diego Home | <telnet://bbs.huaxiaspace.net> <br> <telnet://sd-bbs.net> | | [Firebird BBS](http://ftp.isu.edu.tw/pub/Unix/BBS/FireBird/) | 2019-10-30 測試: Up (<telnet://bbs.huaxiaspace.net> 連線無回應) |

## 加密連線站台資料列表

### SSH 連線

* 批踢踢實業坊：
  * ssh bbs@ptt.cc
  * ssh bbsu@ptt.cc (預設支援 UTF-8)

* 批踢踢兔
  * ssh bbs@ptt2.cc
  * ssh bbsu@ptt2.cc (預設支援 UTF-8)

* 批踢踢參
  * ssh bbs@ptt3.cc (密碼: bbs)

* 台大未來最舊小棧
  * ssh bbs@ofo.tw

* 台中一中電研社 極光鯨藍
  * ssh bbs@tcirc.org

* 未名空間
  * ssh mitbbs.com (與 telnet BBS 帳密同步)
  * 目前只支援 SSH-1

### Websocket 連線

* 批踢踢實業坊：
  * <wss://ws.ptt.cc/bbs> (從改版過的 PttChrome 免安裝體驗: <https://term.ptt.cc> )

* 台中一中 龍夢紀元
  * <wss://eod.tw/bbs> (從改版過的 PttChrome [免安裝體驗](https://term.ptt.cc/?site=wsstelnet://eod.tw/bbs) )
  * <wss://bbs.tcfsh.tc.edu.tw/bbs>

* 台中一中電研社 極光鯨藍
  * <wss://tcirc.org/bbs> (從改版過的 PttChrome [免安裝體驗](https://term.ptt.cc/?site=wsstelnet://tcirc.org/bbs) ) 

* 台大資管 鳴蟬小站 墮落天堂
  * <wss://tolo.ntu.im/bbs> (從改版過的 PttChrome 免安裝體驗: <https://tolo.ntu.im> )

* 巴哈姆特 BBS
  * <wss://term.gamer.com.tw/bbs> (從改版過的 PttChrome 免安裝體驗: <https://term.gamer.com.tw> )

* 淒美燈塔
  * <wss://wsbbs.pharos.rocks> (從改版過的 PttChrome 免安裝體驗: <https://bbs.pharos.rocks> )

## BBS 瀏覽器列表

### Telnet 連線

* PCMan : http://pcman.ptt.cc
* KKman : http://www.kkbox.com/kkman/
* Mac用戶:
  * Welly(clyang版) : https://github.com/clyang/welly

### SSH 連線

* PieTTY: https://sites.google.com/view/pietty-project
* Mac用戶:
  * Welly(clyang版) : https://github.com/clyang/welly

### Websocket 連線

* PCMan : https://github.com/pcman-bbs/pcman-windows/releases
* Mac用戶:
  * Welly(clyang版) : https://github.com/clyang/welly

### 瀏覽器附加元件版本

* [PttChrome](https://chrome.google.com/webstore/detail/pttchrome/hhnlfapopmaimdlldbknjdgekpgffmbo)
* [BBSFox](https://addons.mozilla.org/zh-TW/firefox/addon/bbsfox/)
    * Firefox 57 版後無法使用，[作者表示還在修改中](https://www.ptt.cc/bbs/Browsers/M.1546565629.A.8F5.html)，完成時間未定。

其他用戶端瀏覽器相關資訊也可至 [批踢踢實業坊 AppsForBBS 板](https://www.ptt.cc/bbs/AppsForBBS/index.html) 查詢。
