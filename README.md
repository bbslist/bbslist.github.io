# 已知現存中文 BBS 站台

###### tags: `telnet` `BBS` `電子布告欄` `站台`

## 本文版本
* stable version: [on GitHub](https://github.com/bbslist/bbslist.github.io)
* co-writing version: [on HackMD](https://hackmd.io/r1pdt-59b)

共筆版本 (co-writing version) 可自由編輯，穩定版本 (stable version) 則是共筆版本修改後經過一段時間，確認沒太大問題後才會 push 上去。

若覺得 GitHub 版本太久沒更新可去[提 issue](https://github.com/bbslist/bbslist.github.io/issues)。

整體資訊是否過時與過於老舊，以及有沒有更好的查驗方法，則取決於能協助確認資訊、改善方法的大大們有多少了。

## 可連線數量

* 目前統計有 **51** 個
* 詳細情況請見下文表格中的 `可連` 欄位

## 近期修正與補充欄位

* BBS 站台程式版本 (追溯至最近公開源始碼版本)
* 加密連線支援資訊 *(Web 版網址待補)*
* 列表以文字終端機介面為基礎並提供 telnet、ssh 等網路連線途徑的站台為主，若只有 Web 論壇形式的站台暫不列入。
* **`twbbs.org`** 網域已經終止服務，故暫不附上相關網域資訊
* Current Ptt 版號可搭配 [此連結](https://github.com/ptt/pttbbs/blob/master/UPDATING) 了解其重大差異
* BBS 站台程式開發分支圖
* 暫未列入較近期的私人小型站臺，此類站臺以站長知情且同意補充為主。
* 將加密連線資訊列入連線位址，使用 :lock: 標明，以便一目瞭然。

還請其他熱心人士協助編輯補充 `^_^`

## 大學相關站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 銘傳大學 築夢別境 | [telnet://bbs.mcu.edu.tw](telnet://bbs.mcu.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | |
| :x: | 逢甲紡織 七月七日晴 | [telnet://77bbs.com](telnet://77bbs.com) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | |
| :white_check_mark: | 東華大學 東方小城 | [telnet://bbs.ndhu.edu.tw](telnet://bbs.ndhu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 目前 telnet 連線的看板列表錯誤，會導致斷線 <br> 2021-01-10: 已正常 <br> web 連線正常 |
| :white_check_mark: | 東吳機研站 | [telnet://scumotor.com.tw](telnet://scumotor.com.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-05-26: 已正常 |
| :x: | 東海大學 資訊傳奇 | [telnet://bbs.csie.thu.edu.tw](telnet://bbs.csie.thu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 東海數學 陽光草坪 | [telnet://122.117.69.100](telnet://122.117.69.100) | [Current Ptt](https://github.com/ptt/pttbbs) <br/> (不明舊版本) | |
| :x: | 淡江資管 渡船頭之戀 | [telnet://bbs.im.tku.edu.tw](telnet://bbs.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-06-24 測試: down |
| :x: | 淡江蛋捲 新系統測試站 | [telnet://loyal.ee.tku.edu.tw](telnet://loyal.ee.tku.edu.tw) | [天火系統](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) | 2019-10-30 測試: 連線失敗 |
| :x: | 淡江資管 星星之戀 | [telnet://starlove.im.tku.edu.tw](telnet://starlove.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)| |
| :white_check_mark: | 台大批踢踢 | [telnet://ptt.cc](telnet://ptt.cc) <br> [ip](telnet://140.112.172.11) / [ip~1~](telnet://140.112.172.1) / [ip~2~](telnet://140.112.172.2) / [ip~3~](telnet://140.112.172.3) / [ip~4~](telnet://140.112.172.4) / [ip~5~](telnet://140.112.172.5) <br> `ssh bbs@ptt.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt.cc> (wss) [:lock:](#Websocket-連線) | [Current Ptt](https://github.com/ptt/pttbbs) | guest無法登入 |
| :white_check_mark: | 批踢踢兔 | [telnet://ptt2.cc](telnet://ptt2.cc) <br> `ssh bbs@ptt2.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt2.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt2.cc> (wss) [:lock:](#Websocket-連線) | [Current Ptt](https://github.com/ptt/pttbbs) | guest無法登入 |
| :x: | 批踢踢參 | [telnet://ptt3.cc](telnet://ptt3.cc) <br> `ssh bbs@ptt3.cc` [:lock:](#SSH-連線) | [CurrentPtt](https://github.com/ptt/pttbbs) <br> trunk r4423 | 2019-10-30 測試: 連線失敗 |
| :white_check_mark: | 台大未來最舊 | [telnet://ofo.tw](telnet://ofo.tw) <br> `ssh bbs@ofo.tw` [:lock:](#SSH-連線) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 不開放guest <br> 2021-04-28 測試: Up |
| :white_check_mark: | 台大 不良牛 | [telnet://bbs.badcow.com.tw](telnet://bbs.badcow.com.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 因仍有 DNS 反查, 部份BBS瀏覽軟體不支援 |
| :x: | 台大物理 冷月流蘇 | [telnet://bbs.phys.ntu.edu.tw](telnet://bbs.phys.ntu.edu.tw) <br> [telnet://bbs.phys.tw](telnet://bbs.phys.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | |
| :white_check_mark: | 台大資管 鳴蟬小站 墮落天堂 | [telnet://bbs.im.ntu.edu.tw](telnet://bbs.im.ntu.edu.tw) <br> [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) [:lock:](#Websocket-連線) <br> <https://tolo.ntu.im> (wss) [:lock:](#Websocket-連線) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2020-12-18 測試: WebSocket up |
| :x: | 台北醫學大學 杏林綠意 | [telnet://bbs.tmu.edu.tw](telnet://bbs.tmu.edu.tw) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 另外有很多班板在未來最舊小站 |
| :white_check_mark: | 臺北大學 北極星 | [telnet://bbs.ntpu.edu.tw](telnet://bbs.ntpu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 臺北市立大學 七號出口 |   [telnet://bbs.utaipei.edu.tw](telnet://bbs.utaipei.edu.tw) | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 台中教育大學 柳岸咖啡館 | [telnet://bbs.ntcu.edu.tw](telnet://bbs.ntcu.edu.tw) | 未納入版本管理的 Maple-itoc fork | 硬碟毀損，域名屬於學校，目前無復站希望，詳見 [#4](https://github.com/bbslist/bbslist.github.io/issues/4) |
| :x: | 高雄大學 原野星辰 | [telnet://bbs.nuk.edu.tw](telnet://bbs.nuk.edu.tw) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 海洋大學 | [telnet://bbs.ntou.edu.tw](telnet://bbs.ntou.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 海洋電機 忘晴海 | [telnet://bbs.ee.ntou.edu.tw](telnet://bbs.ee.ntou.edu.tw) | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 交通大學 次世代 | [telnet://bs2.to](telnet://bs2.to) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [已關站](https://www.ptt.cc/bbs/NCTU_TALK/M.1461738017.A.8BA.html) |
| :white_check_mark: | 次世代．佚 | [telnet://bs2.io](telnet://bs2.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [另外發起](https://www.ptt.cc/bbs/NCTU_TALK/M.1469423697.A.2AE.html)之相關延續站台 |
| :white_check_mark: | 淒美燈塔 | [telnet://bbs.pharos.rocks](telnet://bbs.pharos.rocks) <br> [wss://bbs.pharos.rocks](wss://bbs.pharos.rocks) [:lock:](#Websocket-連線) <br> <https://bbs.pharos.rocks> (wss) [:lock:](#Websocket-連線) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2019-10-31 測試: Websocket up |
| :x: | 交通大學 機械工廠 |  [telnet://bbs.me.nctu.edu.tw](telnet://bbs.me.nctu.edu.tw) | [Maple3.10-itoc](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2020-12-17 測試: 連線失敗 |
| :x: | 暨大電機 漂浮電子 | [telnet://bbs.ee.ncnu.edu.tw](telnet://bbs.ee.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 暨大土木 土木小站 | [telnet://bbs.ce.ncnu.edu.tw](telnet://bbs.ce.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法使用guest，以及看板列表毀損 |
| :white_check_mark: | 靜宜水世界 | [telnet://bbs.cs.pu.edu.tw:3001](telnet://bbs.cs.pu.edu.tw:3001) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> 3.02 Rev. 20001103 | 2016因校計中資安政策封鎖Port 23，請改用Port 3001 or 3456連線
| :white_check_mark: | 暨南大學 水沙連 | [telnet://bbs.ncnu.edu.tw](telnet://bbs.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 清華大學 楓橋驛站 | [telnet://bbs.cs.nthu.edu.tw](telnet://bbs.cs.nthu.edu.tw) <br> [telnet://bbs.cs.nthu.edu.tw:443](telnet://bbs.cs.nthu.edu.tw:443) <br> [telnet://imaple.tw](telnet://imaple.tw) <br> [telnet://imaple.tw:443](telnet://imaple.tw:443) <br> [telnet://140.114.87.5](telnet://140.114.87.5) <br> [telnet://140.114.87.5:443](telnet://140.114.87.5:443) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | (2007年, 系統從自己開發的系統, 轉換成 itoc 大 fork 出來的版本 繼續維護)
| :x: | 清華資工 呼拉貝爾 | [telnet://114.32.9.125](telnet://114.32.9.125) | [WindTop BBS](http://windtop.yzu.edu.tw/) | |
| :white_check_mark: | 中央大學 二進位 | [telnet://140.115.50.50](telnet://140.115.50.50) <br> [telnet://binary.csie.ncu.edu.tw](telnet://binary.csie.ncu.edu.tw) <br> [telnet://bbs.ncu.cc](telnet://bbs.ncu.cc) :x: | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2020-12-17 測試: Up; 嘗試進入分類看板時會斷線; [telnet://bbs.ncu.cc](telnet://bbs.ncu.cc) 連線失敗 |
| :x: | 中央數學 織夢天堂 | [telnet://bbs.math.ncu.edu.tw](telnet://bbs.math.ncu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 中山大學 美麗島 | [telnet://140.117.11.2](telnet://140.117.11.2) <br> [telnet://[2001:288:8001:11::2]](telnet://[2001:288:8001:11::2]) <br> [telnet://bbs.nsysu.edu.tw](telnet://bbs.nsysu.edu.tw) | [Formosa BBS](https://github.com/pigfoot/formosa) | |
| :white_check_mark: | 中山大學 西子灣 | [telnet://140.117.11.6](telnet://140.117.11.6) <br> [telnet://[2001:288:8001:11::6]](telnet://[2001:288:8001:11::6]) <br> [telnet://bbs3.nsysu.edu.tw](telnet://bbs3.nsysu.edu.tw) | [Formosa BBS](https://github.com/pigfoot/formosa) | |
| :white_check_mark: | 中正築夢園 | ~~telnet://140.123.29.12~~ <br> ~~telnet://cd.cna.ccu.edu.tw~~ <br> [telnet://207.148.108.123](telnet://207.148.108.123) <br> [telnet://ccudream.csie.io](telnet://ccudream.csie.io) <br> [telnet://cd.csie.io](telnet://cd.csie.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 已由Maple 3 轉至 Maple3.10-itoc 版本 <br> 2021-02-18 測試: 新域名 up |
| :x: | 中正大學 寂寞芳心小站 | [telnet://bbs.ccu.edu.tw](telnet://bbs.ccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/)  | 2018/8/3測試：down |
| :x: | 中正大學 闇黑國度 | [telnet://bbs.cna.ccu.edu.tw](telnet://bbs.cna.ccu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-12-17 測試: Down |
| :x: | 中正通訊 1394 | [telnet://bbs.comm.ccu.edu.tw](telnet://bbs.comm.ccu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-12-17 測試: Down |
| :x: | 中正心理 心海奇航 賽卡羅旗號 | [telnet://140.123.185.40](telnet://140.123.185.40) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 政大資科 貓空行館 | [telnet://bbs.cs.nccu.edu.tw](telnet://bbs.cs.nccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) |
| :white_check_mark: | 彰師生命 擎天崗 | [telnet://bbs.bio.ncue.edu.tw](telnet://bbs.bio.ncue.edu.tw) <br> [telnet://bbs2.ncue.edu.tw](telnet://bbs2.ncue.edu.tw) <br> [telnet://micro.bio.ncue.edu.tw](telnet://micro.bio.ncue.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-01-10: guest 不可登入 (無此帳號) |
| :x: | 真理大學 雲淡風清 | [telnet://bbs.au.edu.tw](telnet://bbs.au.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 真理大學 脆笛酥的家 | [telnet://bbs.jal.tw](telnet://bbs.jal.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 成功大學 夢之大地 | ~~telnet://140.116.250.3~~ **(IP已更改)** <br> [telnet://140.116.249.140](telnet://140.116.249.140/) <br> [telnet://[2001:288:7001:249::140]](telnet://[2001:288:7001:249::140]) **(現在IP)**  <br> [telnet://ccns.cc](telnet://ccns.cc) <br> <https://term.ccns.cc> (wss) [:lock:](#Websocket-連線) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> 3.10 Rev. 20081002 <br> [DreamLand BBS](https://github.com/ccns/dreamlandbbs) <br> [DreamBBS](https://github.com/ccns/dreambbs) | |
| :white_check_mark: | 成大醫學 迴風谷 | [telnet://bbs.med.ncku.edu.tw](telnet://bbs.med.ncku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 成大電機 風之谷 | [telnet://bbs.ee.ncku.edu.tw](telnet://bbs.ee.ncku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | guest無法登入，停止線上註冊 |
| :x: | 長庚大學 巧克力傳奇 | [telnet://bbs.cgu.edu.tw](telnet://bbs.cgu.edu.tw) |
| :x: | 長庚醫學 醫甸園 | [telnet://bbs.med.cgu.edu.tw](telnet://bbs.med.cgu.edu.tw) | [Current Ptt](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 師大資訊 白色情迷 | [telnet://bbs.csie.ntnu.edu.tw](telnet://bbs.csie.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 師大數學 獨數一閣 | [telnet://bbs.math.ntnu.edu.tw](telnet://bbs.math.ntnu.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5284 |
| :white_check_mark: | 師大 人民公社 | [telnet://cvic.org](telnet://cvic.org) <br> [telnet://cvic.be](telnet://cvic.be) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2019-10-31 測試: Up |
| :white_check_mark: | 師大歷史 原史空間 | [telnet://bbs.his.ntnu.edu.tw](telnet://bbs.his.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-04-05: Up |
| :white_check_mark: | 慈濟大學 蔚藍海岸  | [telnet://perlbbs.tw](telnet://perlbbs.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | |
| :x: | 陽明 神農坡 | [telnet://bbs.ym.edu.tw](telnet://bbs.ym.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | PCman主要作者畢業學校 |
| :x: | 元智大學 風之塔 | [telnet://bbs.yzu.edu.tw](telnet://bbs.yzu.edu.tw) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | 2020-06-24 測試: down |
| :x: | 雲林科技大學 藍天使 | [telnet://bbs.yuntech.edu.tw](telnet://bbs.yuntech.edu.tw) | | 2017/1/5測試：down |
| :x: | 中央 神通廣大 | [telnet://bbs.ce.ncu.edu.tw](telnet://bbs.ce.ncu.edu.tw) | | |
| :white_check_mark: | 中原資工 神祕之旅 | [telnet://bbs.ice.cycu.edu.tw](telnet://bbs.ice.cycu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |

## 高中相關站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 建中之夏 烏魯木齊 | [telnet://bbs.ck.tp.edu.tw](telnet://bbs.ck.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 北一女中 弗基斯特 | [telnet://fgisc.org](telnet://fgisc.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 中山女中 楓資羽翼 | [telnet://203.68.236.13](telnet://203.68.236.13) <br> [telnet://csisc.csghs.tp.edu.tw](telnet://csisc.csghs.tp.edu.tw) | [WindTop](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) → [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2019-12-31 測試: Down <br> (有網頁版：<http://bbs.csghs.tp.edu.tw/>) |
| :white_check_mark: | 成功高中 沈澱日記 | `ssh -p 25 bbsu@bbs.ckcsc.net` [:lock:](#SSH-連線) <br> <https://bbs.ckcsc.net> (ttyd) :lock: | [Current Ptt](https://github.com/ptt/pttbbs) | 提供網頁終端介面(ttyd)登入: <https://bbs.ckcsc.net> <br> 2021-04-05: Up |
| :x: | 永春高中 永春哈哈 | [telnet://haha.ycsh.tp.edu.tw](telnet://haha.ycsh.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法進去看板閱讀，僅能瀏覽公佈欄/精華區 |
| :x: | 中壢高中 壢網狂瀾 | [telnet://clhs.csie.org](telnet://clhs.csie.org) | [WindTop BBS](http://windtop.yzu.edu.tw/) | |
| :x: | 台中一中 龍夢紀元 | [telnet://bbs.tcfsh.tc.edu.tw](telnet://bbs.tcfsh.tc.edu.tw) <br> [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs) [:lock:](#Websocket-連線) <br> [telnet://eod.tw](telnet://eod.tw) <br> [ws://eod.tw/bbs](ws://eod.tw/bbs) <br> [wss://eod.tw/bbs](wss://eod.tw/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 可以相容於 PTT 的 Websocket 模式連線 <br> 程式碼為極光鯨藍之穩定版本分支 <br> 2020-12-27 test: Down
| :x: | 台中一中電研社 極光鯨藍 | [telnet://tcirc.org](telnet://tcirc.org/) <br> `ssh bbs@tcirc.org` [:lock:](#SSH-連線) <br> [wss://tcirc.org/bbs](wss://tcirc.org/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 可以相容於 PTT 的 Websocket 模式連線
| :x: | 台中二中 迷幻國度 | [telnet://csc241.tcssh.tc.edu.tw](telnet://csc241.tcssh.tc.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)
| :white_check_mark: | 台南一中 與南共舞 | [telnet://bbs.tnfsh.tn.edu.tw](telnet://bbs.tnfsh.tn.edu.tw) <br> [telnet://wolf.tfcis.org](telnet://wolf.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台南一中資訊社  索尼小站 | [telnet://sony.tfcis.org](telnet://sony.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [SonyBBS](https://github.com/lantw44/sonybbs) | 不開放 guest |
| :white_check_mark: | 台南一中 動力核心 | [telnet://cpu.tfcis.org](telnet://cpu.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-11-17 test: Up |


## 不在學術網路的站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 風與塵埃的對話 | [telnet://wdbbs.tw](telnet://wdbbs.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-01-11: Down |
| :white_check_mark: | 巴哈姆特BBS | [telnet://bbs.gamer.com.tw](telnet://bbs.gamer.com.tw) <br> [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) [:lock:](#Websocket-連線) <br> <https://term.gamer.com.tw> (wss) [:lock:](#Websocket-連線) <br> [telnet://bahamut.org](telnet://bahamut.org) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | guest 無法登入, 需先從 Web 註冊 |
| :white_check_mark: | 花魁異色館 | ~~telnet://libido.cx~~ <br> [telnet://74.52.17.106](telnet://74.52.17.106) :x: <br> [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) [:lock:](#Websocket-連線) :x: <br> <https://libido.malusu.com> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2018/10 下旬起停用 libido.cx 域名連線 <br> 不開放 guest 登入 <br> 2021-01-11: Up |
| :white_check_mark: | 亞特蘭提斯 | [telnet://125.227.52.214](telnet://125.227.52.214) | [Atlantis](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis) | 註冊通過者, 可自己開個板, 免等審核
| :x: | 月下夜想 | [telnet://220.130.248.130](telnet://220.130.248.130) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 反地球聯邦組織 | [telnet://122.116.74.57](telnet://122.116.74.57) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 台灣天主教BBS站 厄瑪奴耳 | [telnet://1.34.185.155](telnet://1.34.185.155) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 動漫遊戲廣播站 | [telnet://bbs.animeyo.com](telnet://bbs.animeyo.com) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 南友小站 |[telnet://tainan.jal.tw](telnet://tainan.jal.tw) <br> [telnet://192.192.120.31](telnet://192.192.120.31) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-04-05: Down; pink 無回應 |
| :white_check_mark: | 書齋軒 | [telnet://bbs.windcity.net](telnet://bbs.windcity.net) | [Open Ptt](https://github.com/bbsmirror/BBSmirror/tree/master/Ptt/openptt) | 提供個人及團體板 |
| :white_check_mark: | 華年小集 | [telnet://literature.twbbs.io](telnet://literature.twbbs.io) | [Current Ptt](https://github.com/ptt/pttbbs) <br> trunk r5563 | |
| :white_check_mark: | 網際新世界 | [telnet://209.141.35.127](telnet://209.141.35.127) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-01-11: Up |
| :x: | 543 音樂站 | [telnet://music543.com](telnet://music543.com) | [Current Ptt](https://github.com/ptt/pttbbs)  <br> trunk r3359 | 2021-04-05: Down; 但 ping 有回應 |
| :white_check_mark: | 幸運草之戀 | [telnet://segaa.net](telnet://segaa.net) | [WindTopBBS-3.02-20021129-SNAP](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | |
| :white_check_mark: | 內灣新小月台 | [telnet://bbs.emu486.net](telnet://bbs.emu486.net) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS-itoc-emu486](https://github.com/irvin/MapleBBS-itoc-emu486) | 
| :white_check_mark: | 西雅圖 | [telnet://www.seattle.ro](telnet://www.seattle.ro) [telnet://seattle.ro](telnet://seattle.ro) [telnet://122.117.16.81](telnet://122.117.16.81) | [MapleBBS-3.10-20121021-PACK.itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020/02/22: 已復站 | 
| :x: | 伙計小站 | [telnet://patw.idv.tw](telnet://patw.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020/04/19:down | 
| :white_check_mark: | 八八八 | [telnet://bbs.wim888.tw](telnet://bbs.wim888.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 
| :white_check_mark: | △．Kirika | [telnet://andcycle.idv.tw](telnet://andcycle.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 
| :white_check_mark: | YKLM大學 | [telnet://yklm.schl.tw](telnet://yklm.schl.tw) <br> [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) [:lock:](#Websocket-連線) <br> <https://yklm.schl.tw> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | | 

## 中國大陸站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 中科院 曙光站(智慧電腦中心) | [telnet://bbs.ncic.ac.cn](telnet://bbs.ncic.ac.cn) | | |
| :x: | 北京大學 | [telnet://bbs.pku.edu.cn](telnet://bbs.pku.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) <br> [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman) | 2020-05-31 測試：網頁版 up <br> 網頁版：<br>https://bbs.pku.edu.cn |
| :x: | 未名空間 | [telnet://mitbbs.com](telnet://mitbbs.com) <br> `ssh <user>@mitbbs.com` (SSH-1) [:unlock:](#SSH-連線) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 相關衍生之商業BBS站台 <br> 2021-04-05: Down; 但 ping 有回應 |
| :x: | 北京大學 一塌糊塗 海外紀念站 | [telnet://bbs.ytht.net](telnet://bbs.ytht.net) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 北京大學 桃花潭 | [telnet://thtpku.3322.org](telnet://thtpku.3322.org) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 無法申請新帳號 <br> guest 不可登入 (無此帳號) <br> 2021-04-05: Down; ping 無回應 |
| :x: | 清華大學 | [telnet://smth.org](telnet://smth.org) | | [無法連線](https://www.ptt.cc/bbs/SMTH/M.1415081920.A.2B0.html) |
| :x: | 清華大學 KissU | [telnet://bbs.thu.cn](telnet://bbs.thu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 水木社區 | [telnet://newsmth.org](telnet://newsmth.org) <br> `ssh <user>@newsmth.org` [:lock:](#SSH-連線) <br> [telnet://bbs.newsmth.net](telnet://bbs.newsmth.net) <br> `ssh <user>@bbs.newsmth.net` [:lock:](#SSH-連線) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 相關衍生之商業BBS站台 <br> 網頁版：<br>https://www.newsmth.net |
| :x: | 南京大學 小百合 | [telnet://bbs.nju.edu.cn](telnet://bbs.nju.edu.cn) <br> [telnet://lilybbs.net](telnet://lilybbs.net) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 教育網 <br> 公眾網 |
| :x: | 哈爾濱工業大學 紫丁香站 | [telnet://bbs.hit.edu.cn](telnet://bbs.hit.edu.cn) | | 無法連線,可能是限制校外ip連入或關站 |
| :white_check_mark: | 紫丁香社區 | [telnet://lilacbbs.com](telnet://lilacbbs.com) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 相關衍生之商業BBS站台 |
| :x: | 上海交通大學 | [telnet://bbs.sjtu.edu.cn](telnet://bbs.sjtu.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 廣西師範大學 煙雨漓江 | [telnet://bbs.gxnu.cn](telnet://bbs.gxnu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 四川大學 藍色星空站 | [telnet://bbs.lsxk.org](telnet://bbs.lsxk.org) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 已經關閉telnet，只提供校內ssh加密訪問 |
| :x: | 復旦大學 日月光華_公網 | [telnet://bbs.fudan.sh.cn](telnet://bbs.fudan.sh.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) <br> [fbbs](https://github.com/fbbs/fbbs) | |
| :x: | 中國科大 瀚海星雲_公網 | [telnet://ustcbbs.ustc.edu.cn](telnet://ustcbbs.ustc.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 華中理工 白云黃鶴 | [telnet://bbs.whnet.edu.cn](telnet://bbs.whnet.edu.cn) <br> [telnet://byhh.hust.edu.cn](telnet://byhh.hust.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) <br> [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman) | 2020-12-18 測試: Down <br> 網頁版：<br>http://byhh.hust.edu.cn |
| :x: | 上海交大 飲水思源 | [telnet://bbs.sjtu.edu.cn](telnet://bbs.sjtu.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 東南大學 虎踞龍盤 | [telnet://bbs.seu.edu.cn](telnet://bbs.seu.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 中國礦業大學 放鶴亭 | [telnet://bbs.cumt.edu.cn](telnet://bbs.cumt.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 北京郵電大學 北郵人論壇 | [telnet://bbs.byr.cn](telnet://bbs.byr.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版：<br><https://bbs.byr.cn> |
| :white_check_mark: | 中國科大 瀚海星雲 | [telnet://bbs.ustc.edu.cn](telnet://bbs.ustc.edu.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2021-04-05: guest 不可登入 (無此 ID) <br> 網頁版：<https://bbs.ustc.edu.cn> |
| :white_check_mark: | 明月水軒 | [telnet://bbs.twomice.net](telnet://bbs.twomice.net) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |

註：
* 北京大學 一塌糊涂 20040913被關 telnet://ytht.net
* 清華大學 水木清華 20050316封校 telnet://smth.org
* 南京大學 小百合 20050322分站 telnet://bbs.nju.edu.cn

## 其他海外華文 BBS 站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 美國 天天壇 | [telnet://tttan.com](telnet://tttan.com) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 美國 San Diego Home | [telnet://bbs.huaxiaspace.net](telnet://bbs.huaxiaspace.net) <br> [telnet://sd-bbs.net](telnet://sd-bbs.net) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2019-12-31 測試: Up |

## 加密連線站台資料列表

### SSH 連線

* 批踢踢實業坊
  * `ssh bbs@ptt.cc`
  * `ssh bbsu@ptt.cc` (預設支援 UTF-8)

* 批踢踢兔
  * `ssh bbs@ptt2.cc`
  * `ssh bbsu@ptt2.cc` (預設支援 UTF-8)

* 批踢踢參
  * `ssh bbs@ptt3.cc` (密碼: `bbs`)

* 台大未來最舊小棧
  * `ssh bbs@ofo.tw`

* 台中一中電研社 極光鯨藍
  * `ssh bbs@tcirc.org`

* 成功高中 沈澱日記
  * `ssh -p 25 bbsu@bbs.ckcsc.net`

* 未名空間
  * `ssh <user>@mitbbs.com` (與 telnet BBS 帳密同步)
  * 目前只支援 SSH-1 -> *不安全*

* 水木社區
  * `ssh <user>@newsmth.org` (與 telnet BBS 帳密同步)
  * `ssh <user>@bbs.newsmth.net` (與 telnet BBS 帳密同步)
  * 支援 SSH-2

### Websocket 連線

* 批踢踢實業坊
  * [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) (從改版過的 PttChrome 免安裝體驗: <https://term.ptt.cc> )

* 批踢踢兔
  * [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) (從改版過的 PttChrome 免安裝體驗: <https://term.ptt2.cc> )

* 台中一中 龍夢紀元
  * [wss://eod.tw/bbs](wss://eod.tw/bbs)
  * [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs)

* 台中一中電研社 極光鯨藍
  * [wss://tcirc.org/bbs](wss://tcirc.org/bbs)

* 台大資管 鳴蟬小站 墮落天堂
  * [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) (從改版過的 PttChrome 免安裝體驗: <https://tolo.ntu.im> )

* 巴哈姆特 BBS
  * [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) (從改版過的 PttChrome 免安裝體驗: <https://term.gamer.com.tw> )

* 淒美燈塔
  * [wss://bbs.pharos.rocks](wss://wsbbs.pharos.rocks) (從改版過的 PttChrome 免安裝體驗: <https://bbs.pharos.rocks> )

* 夢之大地
  * [wss://ws.ccns.ncku.edu.tw/bbs](wss://ws.ccns.ncku.edu.tw/bbs) (從改版過的 PttChrome 免安裝體驗: <https://term.ccns.ncku.edu.tw> )
  * [wss://ws.ccns.cc/bbs](wss://ws.ccns.ncku.edu.tw/bbs) (從改版過的 PttChrome 免安裝體驗: <https://term.ccns.cc> )

* 花魁異色館
  * [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) (從改版過的 PttChrome 免安裝體驗: <https://libido.malusu.com> )

+ YKLM大學
  * [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) (從改版過的 PttChrome 免安裝體驗: <https://yklm.schl.tw> )

## BBS 瀏覽器列表

### Telnet 連線

* PCMan : http://pcman.ptt.cc
* KKman : http://www.kkbox.com/kkman/
* (Mac使用者) Welly (clyang版) : https://github.com/clyang/welly

### SSH 連線

* PieTTY: https://sites.google.com/view/pietty-project
* (Mac使用者) Welly (clyang版) : https://github.com/clyang/welly

### Websocket 連線

* PCMan : https://github.com/pcman-bbs/pcman-windows/releases
* (Mac使用者) Welly (clyang版) : https://github.com/clyang/welly

### 瀏覽器附加元件版本

* [PttChrome](https://chrome.google.com/webstore/detail/pttchrome/hhnlfapopmaimdlldbknjdgekpgffmbo)
* [BBSFox](https://addons.mozilla.org/zh-TW/firefox/addon/bbsfox/)
    * Firefox 57 版後無法使用，[作者表示還在修改中](https://www.ptt.cc/bbs/Browsers/M.1546565629.A.8F5.html)，完成時間未定。

其他用戶端瀏覽器相關資訊也可至 [批踢踢實業坊 AppsForBBS 板](https://www.ptt.cc/bbs/AppsForBBS/index.html) 查詢。

## BBS 系統譜系圖

* 格式: `系統名稱與版本  開發團隊隸屬機構  歷史代表站臺(＊: 還在使用本系列系統)  開發年代`
  - `N.A.`: 代表站臺暫無法考證
  - `n.d.`: 年代暫無法考證

* 同一系統不同版本的歷史代表站臺相同時，只在其中最早版本上標出歷史代表站臺。
* 開發年代主要參考了版權宣告之日期，以及程式修改紀錄。

```
* Pirate BBS 1.6  Mississippi State University  The Mars Hotel  1990
  ├── Pirate BBS 1.9  1992
  └── Eagles BBS 1.1  The University of Southern Mississippi  The Eagle's Nest  1992
      ├── Eagles BBS 2.0  1992-1993
      │   ├── Eagles BBS 3.0  1994, 1995
      │   │   ├── Eagles BBS 3.1  1995-1997
      │   │   └── Palm BBS  臺大計中  椰林風情  1995
      │   ├── Pivot BBS 5.8  中興計中  天樞資訊  1993-1996
      │   │   ├── Feeling BBS  中正計中  寂寞芳心  1995-1996
      │   │   └── NCHU Pivot BBS 5.9  1996
      │   ├── NCTU CIS BBS  交大資科  n.d.
      │   ├── Phoenix BBS 3.0  交大資工  鳳凰城資訊站  1993, 1994
      │   │   ├── Phoenix BBS 4.0  1995
      │   │   │   ├── FireBird BBS 2.0  中正資工  四百年來第一站  1995
      │   │   │   │   ├── Hibiscus Realm BBS 2.xM (FireBird BBS 2.xM)
      │   │   │   │   │   │  中央大學  大紅花的國度  1997, 1998
      │   │   │   │   │   ├── FireBird BBS 3.0  N.A.  1999
      │   │   │   │   │   │   └── FireBird BBS 2000  N.A.  1999, 2000
      │   │   │   │   │   │       ├── PKUBBS  北京大学  北大未名  1999-
      │   │   │   │   │   │       └── Lily BBS  南京大学  小百合  2000-2005
      │   │   │   │   │   │           └── fdubbs  复旦大学  日月光华  2002-2008
      │   │   │   │   │   │               └── fbbs  2008-
      │   │   │   │   │   ├── FireBird BBS 2.x-KCN  N.A.  1998
      │   │   │   │   │   │   └── FireBird BBS 3.0-KCN  N.A.  1999
      │   │   │   │   │   │       └── YTHT BBS  一塌糊涂  1999-2004
      │   │   │   │   │   └── MagicBBS 0.90  魔法王國  1997-1999
      │   │   │   │   │       └── MagicBBS 1.x  1999-2000
      │   │   │   │   │           └── PolyUBBS  香港理工大學  紅磚學術資訊網  1999-2001
      │   │   │   │   └── SMTH BBS 1.2  清华大学  水木清华  2001-2005
      │   │   │   │       ├── SMTH BBS 2.0  2005
      │   │   │   │       │   └── KBS  水木社區＊  2005-
      │   │   │   │       └── MITBBS  未名空间＊  2005-
      │   │   │   └── Napoleon BBS  交大工管  1995-1997
      │   │   └── Secret BBS 4.0  大同資工  秘密情人  1994
      │   │       ├── Secret BBS 4.1B  1995
      │   │       └── Maple BBS 2.36  清大資科  楓橋驛站＊  1994-1995
      │   │           ├── Maple 3.0x (M3)  1995-1998
      │   │           │   ├── DragonII BBS  交通大學  新冷馨居  1998-1999
      │   │           │   │   └── Maple 3.10  1998-2000
      │   │           │   │       └── Maple 3.10-itoc  臺南一中  與南共舞*  2000-
      │   │           │   │           └── AT2-BBS  亞世界  2002-2003
      │   │           │   └── Melix BBS  N.A.  2001
      │   │           ├─── Rouge BBS  交通大學  冷馨居  1995-1997
      │   │           ├── Maple SOB 0.22  臺灣大學  陽光沙灘  1996
      │   │           │   ├── SOB domi  (糟了！誤上賊船  sobdomi.twbbs.org？)  n.d.
      │   │           │   ├── Forest BBS  (中原資管  森林站？)  n.d.
      │   │           │   ├── Atlantis BBS  亞特蘭提斯＊  1996-
      │   │           │   ├── NaiveAge BBS  中央機械  純真年代  n.d.
      │   │           │   ├── Ptt BBS 0.001  臺灣大學  批踢踢實業坊＊  1996-
      │   │           │   │   ├── Open Ptt  2000-2001
      │   │           │   │   ├── Ptt Current  2003-
      │   │           │   │   └── WD BBS 1.34  風與塵埃的對話＊  1999
      │   │           │   │       ├── WD BBS 2.3 1999
      │   │           │   │       │   ├── WD BBS  2000-2010
      │   │           │   │       │   ├── Athena BBS (AT-BBS)  雅典娜  1999-2002
      │   │           │   │       │   └── WD_hialan BBS (AT3-BBS)  威尼斯咖啡館  2002-2003
      │   │           │   │       └── StarRiver BBS  輔仁大學  星河夜話/銀河鐵道之戀  2000-2002
      │   │           │   └── WindTop BBS 2.x  元智大學  風之塔＊  1998-1999
      │   │           │       └── WindTop BBS 3.0x  2000-2004
      │   │           │           ├── WindTop BBS 3.10  2004-2009
      │   │           │           └── DreamLand BBS 3.02  成功大學  夢之大地＊  2004-2009
      │   │           │               └── DreamLand BBS 3.10 (DreamBBS 2010)  2010-2017
      │   │           │                   └── DreamLand BBS  2017-
      │   │           ├── RPG BBS  交通大學  創世紀  1996-1997
      │   │           └── Purple Garden BBS  臺灣法律  小魚的紫色花園  1999
      │   └── NCU BBS  中央大學  N.A.  n.d.
      └── NSYSU BBS  中山計中  美麗之島  1994, 1996, 1997, 1998
          ├── Formosa BBS  中山計中  美麗之島＊  1997-2012
          ├── FCU CC BBS  逢甲計中  蒼穹資訊網  n.d.
          └── Rose BBS  (玫瑰天空？)  n.d.
* Power BBS  中華資工  方城資訊站  1994-1997
* ColaBBS  交大資科  插花島  1997-2000
* 天火 BBS  淡江電機  蛋捲廣場＊  2002
```

### 譜系圖參考資料
* 本圖基礎
   - FireBird BBS. (2014, November 22). Retrieved from 维基百科, 自由的百科全书: https://zh.wikipedia.org/w/index.php?title=FireBird_BBS&oldid=33383364
* TANet BBS 發展譜系圖及相關說明
   - Su, Y. (1995, December). [轉貼] 電子布告欄簡介. Retrieved from 中山大學 West BBS-西子灣站: http://bbs3.nsysu.edu.tw/txtVersion/treasure/ee90-2/M.889205710.A/M.889268386.A.html
   - geniuswei. (2007, May 8). Re: [請益] 關於BBS的定義. Retrived from 批踢踢實業坊: https://www.ptt.cc/bbs/ask/M.1178594446.A.727.html
* Maple 系列發展譜系圖
   - holishing. (2018, January 6). [分享] 目前各版本 BBS server 安裝資訊. Retrieved from 批踢踢實業坊: https://www.ptt.cc/bbs/AppsForBBS/M.1515230521.A.104.html
      - Dopin. (2002, July 18). Maple Family (by Dopin) Ver. 5. 亞特蘭提斯站 ([telnet://125.227.52.214](telnet://125.227.52.214)) ATSVersion 板 置底
* FireBird 系列發展沿革
   - Huang, L. (n.d.) BBS 之前世今生. Retrieved from YTHT BBS 开发指南: https://lytsing.gitbooks.io/ytht-bbs/content/bbs-history.html
* PCMAN 瀏覽器內建的站臺列表
* 介紹到了 Pirate BBS 的文章
   - Scott, J. (2008, November 3). When the BBS Broke Free. ASCII by Jason Scott. Retrieved from: http://ascii.textfiles.com/archives/1474
* 介紹 Eagles BBS 起源的文章
   - Rocker, R. (1994, August 1). Eagles BBS. ***Linux Journal***. Retrieved from https://www.linuxjournal.com/article/2789
* 現存站臺上的版權宣告及相關公告
* 程式原始碼中的相關文件
