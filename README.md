# 已知現存中文 BBS 站台

###### tags: `telnet` `BBS` `電子布告欄` `站台`

## 本文版本
* stable version: [on GitHub](https://github.com/bbslist/bbslist.github.io)
* co-writing version: [on HackMD](https://hackmd.io/r1pdt-59b)

共筆版本 (co-writing version) 可自由編輯，穩定版本 (stable version) 則是共筆版本修改後經過一段時間，確認沒太大問題後才會 push 上去。

若覺得 GitHub 版本太久沒更新可去[提 issue](https://github.com/bbslist/bbslist.github.io/issues)。

整體資訊是否過時與過於老舊，以及有沒有更好的查驗方法，則取決於能協助確認資訊、改善方法的大大們有多少了。

## 可連線數量

* 目前統計有 **59** 個 (2021-12-18)
* 詳細情況請見下文表格中的 `可連` 欄位
* 為便於判斷，以從外網可使用任一直接網路連線途徑連入為判斷原則

## 近期修正與補充欄位

* BBS 站台程式版本 (以追溯至最近公開源始碼版本為主)
* 加密連線支援資訊
* 列表以文字終端機介面為基礎並提供 telnet、ssh 等網路連線途徑的站台為主，若只有 Web 論壇形式的站台暫不列入。
* **`twbbs.org`** 網域已經終止服務，故暫不附上相關網域資訊
* PttBBS/Ptt current 版號可搭配 [此連結](https://github.com/ptt/pttbbs/blob/master/UPDATING) 了解其重大差異
* BBS 站台程式開發分支圖
* 暫未列入較近期的私人小型站臺，此類站臺以站長知情且同意補充為主。
* 將加密連線資訊列入連線位址，使用 :lock: 標明，以便一目瞭然。
* 將加密連線站台列表整理成表格。
* 將 PttChrome 網頁版程式版本資訊加入支援 Websocket 連線的站台列表。
* 補充 Web 版網址。以站台資料與 telnet、ssh 等介面的資料同步者為主。
* 在 BBS 系統譜系圖的各節點補充原始碼鏈結

還請其他熱心人士協助編輯補充 `^_^`

## 大學相關站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 銘傳大學 築夢別境 | [telnet://bbs.mcu.edu.tw](telnet://bbs.mcu.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | |
| :x: | 逢甲紡織 七月七日晴 | [telnet://77bbs.com](telnet://77bbs.com) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | |
| :white_check_mark: | 東華大學 東方小城 | [telnet://bbs.ndhu.edu.tw](telnet://bbs.ndhu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [easttownbbs](https://github.com/guessi/easttownbbs) | 網頁版: <http://bbs.ndhu.edu.tw> :unlock: <br> 2021-01-10: 已正常 <br> 2021-08-18: 未加密網頁版 up |
| :white_check_mark: | 東吳機研站 | [telnet://scumotor.com.tw](telnet://scumotor.com.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://scumotor.com.tw:8080> :unlock: <br> 2021-05-26: 已正常 |
| :x: | 東海大學 資訊傳奇 | [telnet://bbs.csie.thu.edu.tw](telnet://bbs.csie.thu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 東海數學 陽光草坪 | [telnet://122.117.69.100](telnet://122.117.69.100) | [PttBBS](https://github.com/ptt/pttbbs) <br/> (不明舊版本) | |
| :x: | 淡江資管 渡船頭之戀 | [telnet://bbs.im.tku.edu.tw](telnet://bbs.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-06-24 測試: down |
| :x: | 淡江蛋捲 新系統測試站 | [telnet://loyal.ee.tku.edu.tw](telnet://loyal.ee.tku.edu.tw) | [天火系統](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) | 2019-10-30 測試: 連線失敗 |
| :x: | 淡江資管 星星之戀 | [telnet://starlove.im.tku.edu.tw](telnet://starlove.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)| |
| :white_check_mark: | 台大批踢踢 | [telnet://ptt.cc](telnet://ptt.cc) <br> [ip](telnet://140.112.172.11) / [ip~1~](telnet://140.112.172.1) / [ip~2~](telnet://140.112.172.2) / [ip~3~](telnet://140.112.172.3) / [ip~4~](telnet://140.112.172.4) / [ip~5~](telnet://140.112.172.5) <br> `ssh bbs@ptt.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt.cc> (wss) [:lock:](#Websocket-連線) | [PttBBS git r5011+](https://github.com/ptt/pttbbs) | 網頁版: <https://www.ptt.cc/bbs> <br> guest無法登入 |
| :white_check_mark: | 批踢踢兔 | [telnet://ptt2.cc](telnet://ptt2.cc) <br> `ssh bbs@ptt2.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt2.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt2.cc> (wss) [:lock:](#Websocket-連線) | [PttBBS git r5011+](https://github.com/ptt/pttbbs) | guest無法登入 |
| :x: | 批踢踢參 | [telnet://ptt3.cc](telnet://ptt3.cc) <br> `ssh bbs@ptt3.cc` [:lock:](#SSH-連線) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r4423 | 2019-10-30 測試: 連線失敗 |
| :white_check_mark: | 台大未來最舊 | [telnet://ofo.tw](telnet://ofo.tw) <br> `ssh bbs@ofo.tw` [:lock:](#SSH-連線) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 不開放guest <br> 2021-04-28 測試: Up |
| :x: | 台大 不良牛 | [telnet://bbs.badcow.com.tw](telnet://bbs.badcow.com.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) <br> [SOB-fromzero](https://github.com/bbsmirror/BBSmirror/blob/master/SOB/sob_rfc2047.tar.gz) | 因仍有 DNS 反查, 部份BBS瀏覽軟體不支援 <br> 2021-08-11: 連線失敗， |
| :x: | 台大物理 冷月流蘇 | [telnet://bbs.phys.ntu.edu.tw](telnet://bbs.phys.ntu.edu.tw) <br> [telnet://bbs.phys.tw](telnet://bbs.phys.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | |
| :white_check_mark: | 台大資管 鳴蟬小站 墮落天堂 | [telnet://bbs.im.ntu.edu.tw](telnet://bbs.im.ntu.edu.tw) <br> [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) [:lock:](#Websocket-連線) :x: <br> <https://tolo.ntu.im> (wss) [:unlock:](#Websocket-連線) :x: | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-08-11: PttChrome 誤連到批踢踢 <br> 2021-12-01: WSS 連線失敗；加密憑證網域設定錯誤 |
| :x: | 台北醫學大學 杏林綠意 | [telnet://bbs.tmu.edu.tw](telnet://bbs.tmu.edu.tw) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 另外有很多班板在未來最舊小站 |
| :x: | 臺北大學 北極星 | [telnet://bbs.ntpu.edu.tw](telnet://bbs.ntpu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-12-01: down |
| :x: | 臺北市立大學 七號出口 |   [telnet://bbs.utaipei.edu.tw](telnet://bbs.utaipei.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本) | 2021-07-10: Down |
| :x: | 台中教育大學 柳岸咖啡館 | [telnet://bbs.ntcu.edu.tw](telnet://bbs.ntcu.edu.tw) | 未納入版本管理的 Maple-itoc fork | 硬碟毀損，域名屬於學校，目前無復站希望，詳見 [#4](https://github.com/bbslist/bbslist.github.io/issues/4) |
| :x: | 高雄大學 原野星辰 | [telnet://bbs.nuk.edu.tw](telnet://bbs.nuk.edu.tw) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 海洋大學 | [telnet://bbs.ntou.edu.tw](telnet://bbs.ntou.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 海洋電機 忘晴海 | [telnet://bbs.ee.ntou.edu.tw](telnet://bbs.ee.ntou.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 交通大學 次世代 | [telnet://bs2.to](telnet://bs2.to) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [已關站](https://www.ptt.cc/bbs/NCTU_TALK/M.1461738017.A.8BA.html) |
| :white_check_mark: | 次世代．佚 | [telnet://bs2.io](telnet://bs2.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [另外發起](https://www.ptt.cc/bbs/NCTU_TALK/M.1469423697.A.2AE.html)之相關延續站台 |
| :white_check_mark: | 淒美燈塔 | [telnet://bbs.pharos.rocks](telnet://bbs.pharos.rocks) <br> [wss://bbs.pharos.rocks](wss://bbs.pharos.rocks) [:lock:](#Websocket-連線) <br> <https://bbs.pharos.rocks> (wss) [:lock:](#Websocket-連線) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2019-10-31 測試: Websocket up |
| :x: | 交通大學 機械工廠 |  [telnet://bbs.me.nctu.edu.tw](telnet://bbs.me.nctu.edu.tw) | [Maple3.10-itoc](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2020-12-17 測試: 連線失敗 |
| :x: | 暨大電機 漂浮電子 | [telnet://bbs.ee.ncnu.edu.tw](telnet://bbs.ee.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 暨大土木 土木小站 | [telnet://bbs.ce.ncnu.edu.tw](telnet://bbs.ce.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法使用guest，以及看板列表毀損 |
| :white_check_mark: | 靜宜水世界 | [telnet://bbs.cs.pu.edu.tw:3001](telnet://bbs.cs.pu.edu.tw:3001) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> 3.02 Rev. 20001103 | 2016因校計中資安政策封鎖Port 23，請改用Port 3001 or 3456連線 <br> 2021-08-12: Up
| :white_check_mark: | 暨南大學 水沙連 | [telnet://bbs.ncnu.edu.tw](telnet://bbs.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 清華大學 楓橋驛站 | [telnet://bbs.cs.nthu.edu.tw](telnet://bbs.cs.nthu.edu.tw) <br> [telnet://bbs.cs.nthu.edu.tw:443](telnet://bbs.cs.nthu.edu.tw:443) <br> [telnet://imaple.tw](telnet://imaple.tw) <br> [telnet://imaple.tw:443](telnet://imaple.tw:443) <br> [telnet://140.114.87.5](telnet://140.114.87.5) <br> [telnet://140.114.87.5:443](telnet://140.114.87.5:443) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS 3.20 (3.10-ATOM)](https://github.com/maplebridge/bbs) r402 | (2007年, 系統從自己開發的系統, 轉換成 itoc 大 fork 出來的版本 繼續維護)
| :x: | 清華資工 呼拉貝爾 | [telnet://114.32.9.125](telnet://114.32.9.125) | [WindTop BBS](http://windtop.yzu.edu.tw/) | |
| :x: | 中央大學 二進位 | [telnet://140.115.50.50](telnet://140.115.50.50) <br> [telnet://binary.csie.ncu.edu.tw](telnet://binary.csie.ncu.edu.tw) <br> [telnet://bbs.ncu.cc](telnet://bbs.ncu.cc) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-07-10: Down |
| :x: | 中央數學 織夢天堂 | [telnet://bbs.math.ncu.edu.tw](telnet://bbs.math.ncu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 中山大學 美麗島 | [telnet://140.117.11.2](telnet://140.117.11.2) <br> [telnet://[2001:288:8001:11::2]](telnet://[2001:288:8001:11::2]) <br> [telnet://bbs.nsysu.edu.tw](telnet://bbs.nsysu.edu.tw) | [Formosa BBS CE](https://github.com/PichuChen/formosa) | 2021-07-10: IPv4 無法連線 |
| :x: | 中山大學 西子灣 | [telnet://140.117.11.6](telnet://140.117.11.6) <br> [telnet://[2001:288:8001:11::6]](telnet://[2001:288:8001:11::6]) <br> [telnet://bbs3.nsysu.edu.tw](telnet://bbs3.nsysu.edu.tw) | [Formosa BBS CE](https://github.com/PichuChen/formosa) | 網頁版: <https://[2001:288:8001:11::6]> <br> 2021-07-10: IPv4 無法連線 <br> 2021-07-10: 僅網頁版可連 <br> 2021-12-01: 網頁版 down |
| :white_check_mark: | 中正築夢園 | ~~telnet://140.123.29.12~~ <br> ~~telnet://cd.cna.ccu.edu.tw~~ <br> [telnet://207.148.108.123](telnet://207.148.108.123) <br> [telnet://ccudream.csie.io](telnet://ccudream.csie.io) <br> [telnet://cd.csie.io](telnet://cd.csie.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 已由Maple 3 轉至 Maple3.10-itoc 版本 <br> 2021-02-18 測試: 新域名 up <br> 預計 2021/12/30 關站 |
| :x: | 中正大學 寂寞芳心小站 | [telnet://bbs.ccu.edu.tw](telnet://bbs.ccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/)  | 2018/8/3測試：down |
| :white_check_mark: | 中正大學 闇黑國度 | [telnet://bbs.cna.ccu.edu.tw](telnet://bbs.cna.ccu.edu.tw) :x: <br> [wss://term.cna.ccu.edu.tw:9800](wss://term.cna.ccu.edu.tw:9800) (TLS 1.0/1.1) [:unlock:](#Websocket-連線) <br> <https://term.cna.ccu.edu.tw> (wss) (TLS 1.0/1.1) [:unlock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-12-17 測試: Down <br> 2021-08-18: WebSocket & PttChrome up |
| :white_check_mark: | 中正通訊 1394 | [telnet://bbs.comm.ccu.edu.tw](telnet://bbs.comm.ccu.edu.tw) :x: <br> `ssh bbs@bbs.comm.ccu.edu.tw` [:lock:](#SSH-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<https://bbs.comm.ccu.edu.tw> <br> 2021-08-18: Telnet 連線停用 <br> 2021-12-01: 加密連線 up |
| :x: | 中正心理 心海奇航 賽卡羅旗號 | [telnet://140.123.185.40](telnet://140.123.185.40) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 政大資科 貓空行館 | [telnet://bbs.cs.nccu.edu.tw](telnet://bbs.cs.nccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) |
| :white_check_mark: | 彰師生命 擎天崗 | [telnet://bbs.bio.ncue.edu.tw](telnet://bbs.bio.ncue.edu.tw) <br> [telnet://bbs2.ncue.edu.tw](telnet://bbs2.ncue.edu.tw) <br> [telnet://micro.bio.ncue.edu.tw](telnet://micro.bio.ncue.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://micro.bio.ncue.edu.tw:8080> :unlock: <br> 2021-07-10: guest 不可登入 (無此帳號) |
| :x: | 真理大學 雲淡風清 | [telnet://bbs.au.edu.tw](telnet://bbs.au.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 真理大學 脆笛酥的家 | [telnet://bbs.jal.tw](telnet://bbs.jal.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: guest 不可登入 (無此帳號) |
| :white_check_mark: | 成功大學 夢之大地 | ~~telnet://140.116.250.3~~ **(IP已更改)** <br> [telnet://140.116.249.140](telnet://140.116.249.140/) <br> [telnet://[2001:288:7001:249::140]](telnet://[2001:288:7001:249::140]) **(現在IP)**  <br> [telnet://ccns.cc](telnet://ccns.cc) <br> `ssh bbs@ccns.cc` :lock: <br> [wss://ws.ccns.ncku.edu.tw/bbs](wss://ws.ccns.ncku.edu.tw/bbs) [:lock:](#Websocket-連線) <br> <https://term.ccns.cc> (wss) [:lock:](#Websocket-連線) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> 3.10 Rev. 20081002 <br> [DreamBBS git r1785+](https://github.com/ccns/dreambbs) | |
| :white_check_mark: | 成大醫學 迴風谷 | [telnet://bbs.med.ncku.edu.tw](telnet://bbs.med.ncku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [windyvalleybbs](https://github.com/bbsmirror/windyvalleybbs) | 2021-12-01: up |
| :white_check_mark: | 成大電機 風之谷 | [telnet://bbs.ee.ncku.edu.tw](telnet://bbs.ee.ncku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | guest過多無法登入；不開放線上註冊 |
| :x: | 長庚大學 巧克力傳奇 | [telnet://bbs.cgu.edu.tw](telnet://bbs.cgu.edu.tw) |
| :x: | 長庚醫學 醫甸園 | [telnet://bbs.med.cgu.edu.tw](telnet://bbs.med.cgu.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :x: | 師大資訊 白色情迷 | [telnet://bbs.csie.ntnu.edu.tw](telnet://bbs.csie.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 師大數學 獨數一閣 | [telnet://bbs.math.ntnu.edu.tw](telnet://bbs.math.ntnu.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5284 |
| :white_check_mark: | 師大 人民公社 | [telnet://cvic.org](telnet://cvic.org) <br> [telnet://cvic.be](telnet://cvic.be) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2019-10-31 測試: Up <br> 2021-07-10 guest 從主選單進入 `(C)onfig` 後直接按右鍵會進入空白選單 |
| :x: | 師大歷史 原史空間 | [telnet://bbs.his.ntnu.edu.tw](telnet://bbs.his.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: Down |
| :white_check_mark: | 慈濟大學 蔚藍海岸  | [telnet://perlbbs.tw](telnet://perlbbs.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | |
| :x: | 陽明 神農坡 | [telnet://bbs.ym.edu.tw](telnet://bbs.ym.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | PCman主要作者畢業學校 |
| :x: | 元智大學 風之塔 | [telnet://bbs.yzu.edu.tw](telnet://bbs.yzu.edu.tw) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | 2020-06-24 測試: down |
| :x: | 雲林科技大學 藍天使 | [telnet://bbs.yuntech.edu.tw](telnet://bbs.yuntech.edu.tw) | | 2017/1/5測試：down |
| :x: | 中央 神通廣大 | [telnet://bbs.ce.ncu.edu.tw](telnet://bbs.ce.ncu.edu.tw) | | |
| :white_check_mark: | 中原資工 神祕之旅 | [telnet://bbs.ice.cycu.edu.tw](telnet://bbs.ice.cycu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<https://bbs.ice.cycu.edu.tw> |

## 高中相關站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 建中之夏 烏魯木齊 | [telnet://bbs.ck.tp.edu.tw](telnet://bbs.ck.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-08-18: 域名無效 |
| :white_check_mark: | 北一女中 弗基斯特 | [telnet://fgisc.org](telnet://fgisc.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 中山女中 楓資羽翼 | [telnet://203.68.236.13](telnet://203.68.236.13) <br> [telnet://csisc.csghs.tp.edu.tw](telnet://csisc.csghs.tp.edu.tw) | [WindTop](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) → [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://bbs.csghs.tp.edu.tw> :unlock: <br> 2019-12-31 測試: Down <br> 2021-08-18: 域名無效 |
| :x: | 成功高中 沈澱日記 | `ssh -p 25 bbsu@bbs.ckcsc.net` [:lock:](#SSH-連線) <br> <https://bbs.ckcsc.net> (ttyd) :lock: | [PttBBS git r4927+](https://github.com/ptt/pttbbs) | 提供網頁終端介面(ttyd)登入 <br> 2021-08-12: 連線逾時 |
| :x: | 永春高中 永春哈哈 | [telnet://haha.ycsh.tp.edu.tw](telnet://haha.ycsh.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法進去看板閱讀，僅能瀏覽公佈欄/精華區 |
| :x: | 中壢高中 壢網狂瀾 | [telnet://clhs.csie.org](telnet://clhs.csie.org) | [WindTop BBS](http://windtop.yzu.edu.tw/) | |
| :x: | 台中一中 龍夢紀元 | [telnet://bbs.tcfsh.tc.edu.tw](telnet://bbs.tcfsh.tc.edu.tw) <br> [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs) [:lock:](#Websocket-連線) <br> [telnet://eod.tw](telnet://eod.tw) <br> [ws://eod.tw/bbs](ws://eod.tw/bbs) <br> [wss://eod.tw/bbs](wss://eod.tw/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 可以相容於 PTT 的 Websocket 模式連線 <br> 程式碼為極光鯨藍之穩定版本分支 <br> 2020-12-27 test: Down <br> 2021-08-18: 域名無效
| :x: | 台中一中電研社 極光鯨藍 | [telnet://tcirc.org](telnet://tcirc.org/) <br> `ssh bbs@tcirc.org` [:lock:](#SSH-連線) <br> [wss://tcirc.org/bbs](wss://tcirc.org/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 可以相容於 PTT 的 Websocket 模式連線 <br> 2021-08-18: `DNS resolution error`
| :x: | 台中二中 迷幻國度 | [telnet://csc241.tcssh.tc.edu.tw](telnet://csc241.tcssh.tc.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: `No route to host` |
| :white_check_mark: | 台南一中 與南共舞 | [telnet://bbs.tnfsh.tn.edu.tw](telnet://bbs.tnfsh.tn.edu.tw) <br> [telnet://wolf.tfcis.org](telnet://wolf.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台南一中資訊社  索尼小站 | [telnet://bbs.tfcis.org](telnet://bbs.tfcis.org) <br> [telnet://sony.tfcis.org](telnet://sony.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [SonyBBS](https://github.com/lantw44/sonybbs) | 不開放 guest <br> 2021-07-12: Up |
| :white_check_mark: | 台南一中 動力核心 | [telnet://cpu.tfcis.org](telnet://cpu.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-12: Up |


## 不在學術網路的站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 風與塵埃的對話 | [telnet://wdbbs.tw](telnet://wdbbs.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-01-11: Down |
| :white_check_mark: | 巴哈姆特BBS | [telnet://bbs.gamer.com.tw](telnet://bbs.gamer.com.tw) <br> [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) [:lock:](#Websocket-連線) <br> <https://term.gamer.com.tw> (wss) [:lock:](#Websocket-連線) <br> [telnet://bahamut.org](telnet://bahamut.org) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 網頁版: <https://www.gamer.com.tw> <br> guest 無法登入, 需先從 Web 註冊 |
| :white_check_mark: | 花魁藝色館 | [telnet://libido.cx](telnet://libido.cx) <br> [telnet://74.52.17.106](telnet://74.52.17.106) :x: <br> [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) [:lock:](#Websocket-連線) <br> <https://libido.malusu.com> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2018/10 下旬起停用 libido.cx 域名連線 <br> 2021-08-18: 原域名 up <br> 不開放 guest 登入 |
| :white_check_mark: | 亞特蘭提斯 | [telnet://125.227.52.214](telnet://125.227.52.214) <br> [telnet://bbs.bsd.com.tw](telnet://bbs.bsd.com.tw) | [Atlantis](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis) | 註冊通過者, 可自己開個板, 免等審核
| :x: | 月下夜想 | [telnet://220.130.248.130](telnet://220.130.248.130) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 反地球聯邦組織 | [telnet://122.116.74.57](telnet://122.116.74.57) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台灣天主教BBS站 厄瑪奴耳 | [telnet://bbs-jesus.name](telnet://bbs-jesus.name) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 動漫遊戲廣播站 | [telnet://bbs.animeyo.com](telnet://bbs.animeyo.com) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 南友小站 |[telnet://tainan.jal.tw](telnet://tainan.jal.tw) <br> [telnet://192.192.120.31](telnet://192.192.120.31) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: Up <br> 看板列表顯示不正常，但仍可正常進入看板 |
| :white_check_mark: | 書齋軒 | [telnet://bbs.windcity.net](telnet://bbs.windcity.net) | [Open Ptt](https://github.com/bbsmirror/BBSmirror/tree/master/Ptt/openptt) | 提供個人及團體板 |
| :white_check_mark: | 華年小集 | [telnet://literature.twbbs.io](telnet://literature.twbbs.io) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5563 | |
| :white_check_mark: | 網際新世界 | [telnet://209.141.35.127](telnet://209.141.35.127) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-01-11: Up <br> 2021-07-10: guest 無法登入（無此帳號） |
| :white_check_mark: | 543 音樂站 | [telnet://music543.com](telnet://music543.com) | [PttBBS](https://github.com/ptt/pttbbs)  <br> trunk r3359 | 網頁版（資料不完全與 telnet 介面同步）：<http://music543.com> :unlock: :x: <br> 2021-07-10: Up <br> 2021-12-01: 網頁版 down |
| :white_check_mark: | 幸運草之戀 | [telnet://segaa.net](telnet://segaa.net) | [WindTopBBS-3.02-20021129-SNAP](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | |
| :white_check_mark: | 內灣新小月台 | [telnet://bbs.emu486.net](telnet://bbs.emu486.net) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS-itoc-emu486](https://github.com/irvin/MapleBBS-itoc-emu486) | 
| :white_check_mark: | 西雅圖 | [telnet://www.seattle.tw](telnet://www.seattle.tw) [telnet://seattle.tw](telnet://seattle.tw) [telnet://122.117.16.81](telnet://122.117.16.81) | [MapleBBS-3.10-20121021-PACK.itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020/02/22: 已復站 | 
| :x: | 伙計小站 | [telnet://patw.idv.tw](telnet://patw.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [PartnerBBS](https://github.com/patw0929/MapleBBS-itoc) | 2020/04/19:down | 
| :white_check_mark: | 八八八 | [telnet://bbs.wim888.tw](telnet://bbs.wim888.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://bbs.wim888.tw> :unlock: | 
| :white_check_mark: | △．Kirika | [telnet://andcycle.idv.tw](telnet://andcycle.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | YKLM大學 | [telnet://yklm.schl.tw](telnet://yklm.schl.tw) <br> [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) [:lock:](#Websocket-連線) <br> <https://yklm.schl.tw> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-08-10: Up | 

## 中國大陸站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 中科院 曙光站(智慧電腦中心) | [telnet://bbs.ncic.ac.cn](telnet://bbs.ncic.ac.cn) | | |
| :white_check_mark: | 北京大學 | [telnet://bbs.pku.edu.cn](telnet://bbs.pku.edu.cn) :x: <br> `ssh <user>@bbs.pku.edu.cn` [:lock:](#SSH-連線) | [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | 網頁版：<https://bbs.pku.edu.cn> <br> 2021-08-18 測試：SSH up |
| :white_check_mark: | 未名空間 | [telnet://mitbbs.com](telnet://mitbbs.com) :x: <br> `ssh <user>@mitbbs.com` (SSH-1) [:unlock:](#SSH-連線) :x: | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d) <br> MITBBS | 網頁版：<https://mitbbs.com> <br> 相關衍生之商業BBS站台 <br> 2021-08-18: 僅網頁版可連 |
| :x: | 北京大學 一塌糊塗 海外紀念站 | [telnet://bbs.ytht.net](telnet://bbs.ytht.net) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 北京大學 桃花潭 | [telnet://thtpku.3322.org](telnet://thtpku.3322.org) :x: | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版：<https://thtpku.3322.org> <br> 無法申請新帳號 <br> guest 不可登入 (無此帳號) <br> 2021-12-01: telnet down |
| :x: | 清華大學 | [telnet://smth.org](telnet://smth.org) | | [無法連線](https://www.ptt.cc/bbs/SMTH/M.1415081920.A.2B0.html) |
| :white_check_mark: | 清華大學 KissU | [telnet://bbs.thu.cn](telnet://bbs.thu.cn) :x: | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) |網頁版：<https://bbs.thu.cn> <br> 2021-08-18: 僅網頁版可連 |
| :white_check_mark: | 水木社區 | [telnet://newsmth.org](telnet://newsmth.org) <br> `ssh <user>@newsmth.org` [:lock:](#SSH-連線) <br> [telnet://bbs.newsmth.net](telnet://bbs.newsmth.net) <br> `ssh <user>@bbs.newsmth.net` [:lock:](#SSH-連線) <br> [telnet://bbs.mysmth.net](telnet://bbs.mysmth.net) <br> `ssh <user>@bbs.mysmth.net` [:lock:](#SSH-連線) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版：<br> <https://www.newsmth.net> <br> <https://www.mysmth.net> <br> 相關衍生之商業BBS站台 |
| :x: | 南京大學 小百合 | [telnet://bbs.nju.edu.cn](telnet://bbs.nju.edu.cn) (教育網) <br> [telnet://lilybbs.net](telnet://lilybbs.net) (公眾網) | [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | |
| :x: | 哈爾濱工業大學 紫丁香站 | [telnet://bbs.hit.edu.cn](telnet://bbs.hit.edu.cn) | | 無法連線,可能是限制校外ip連入或關站 |
| :white_check_mark: | 紫丁香社區 | [telnet://lilacbbs.com](telnet://lilacbbs.com) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/)  <br> [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d) <br> [LilacBBS](https://github.com/marvelliu/lilacsrc) | 網頁版：<http://lilacbbs.com> :unlock: <br> 相關衍生之商業BBS站台 |
| :x: | 上海交大 飲水思源 | [telnet://bbs.sjtu.edu.cn](telnet://bbs.sjtu.edu.cn) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) <br> [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1106 <br> [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs) | 網頁版：<https://bbs.sjtu.edu.cn> :unlock: :x: (TLS 1.0/1.1) <br> 不開放校外連線 <br> 2021-12-01: 加密連線憑證過期 |
| :x: | 廣西師範大學 煙雨漓江 | [telnet://bbs.gxnu.cn](telnet://bbs.gxnu.cn) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 四川大學 藍色星空站 | [telnet://bbs.lsxk.org](telnet://bbs.lsxk.org) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 已經關閉telnet，只提供校內ssh加密訪問 |
| :white_check_mark: | 復旦大學 日月光華 | [telnet://bbs.fudan.edu.cn](telnet://bbs.fudan.edu.cn) | [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [fbbs](https://github.com/fbbs/fbbs) | 網頁版：<https://bbs.fudan.edu.cn> |
| :white_check_mark: | 中國科大 瀚海星雲 | [telnet://ustcbbs.ustc.edu.cn](telnet://ustcbbs.ustc.edu.cn) :x: <br> [telnet://bbs.ustc.edu.cn](telnet://bbs.ustc.edu.cn) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版：<https://bbs.ustc.edu.cn> <br> 2021-04-05: guest 不可登入 (無此 ID) |
| :x: | 華中理工 白云黃鶴 | [telnet://bbs.whnet.edu.cn](telnet://bbs.whnet.edu.cn) <br> [telnet://byhh.hust.edu.cn](telnet://byhh.hust.edu.cn) | [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | 網頁版：<http://byhh.hust.edu.cn> :unlock: <br> 2020-12-18 測試: Down |
| :x: | 東南大學 虎踞龍盤 | [telnet://bbs.seu.edu.cn](telnet://bbs.seu.edu.cn) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 中國礦業大學 放鶴亭 | [telnet://bbs.cumt.edu.cn](telnet://bbs.cumt.edu.cn) | [Firebird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 北京郵電大學 北郵人論壇 | [telnet://bbs.byr.cn](telnet://bbs.byr.cn) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版：<br><https://bbs.byr.cn> |
| :white_check_mark: | 明月水軒 | [telnet://bbs.twomice.net](telnet://bbs.twomice.net) | [Maple3.10-WEB-hightman](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/MapleBBS-3.10-WEB-20011031.tar.gz) | |
| :white_check_mark: | 清華大學 聽濤站 | [telnet://bbs.tingtao.net](telnet://bbs.tingtao.net) <br> `ssh <user>@bbs.tingtao.net` (SSH-1) [:unlock:](#SSH-連線) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [SMTH BBS 1.0](https://github.com/zhouqt/kbs) | 網頁版：<https://bbs.tingtao.net>
| :white_check_mark: | 北京大學 大話西遊 | [telnet://dhxy.info](telnet://dhxy.info) | [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1106 | 網頁版：<https://dhxy.info> :unlock: <br> 2021-08-21: guest 不可登入 (無此 ID) <br> 加密連線憑證過期
| :white_check_mark: | 清華大學 大話西遊 紫霞BBS | [telnet://wforum.zixia.net](telnet://wforum.zixia.net) <br> `ssh <user>@wforum.zixia.net` (SSH-1) [:unlock:](#SSH-連線) <br> [telnet://bbs.zixia.net](telnet://bbs.zixia.net) <br> `ssh <user>@bbs.zixia.net` (SSH-1) [:unlock:](#SSH-連線) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) <br> [zixia BBS v21.2.1](https://github.com/zixia/bbs) |
| :white_check_mark: | 南洋客棧 | [telnet://bbs.nykz.net](telnet://bbs.nykz.net) <br> [telnet://back.nykz.net:2323](telnet://back.nykz.net:2323) :x: | [Firebird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1219 <br> [nykz BBS](https://github.com/scaret/nykz) | 2021-10-12: guest 不可登入 (無此 ID)
:white_check_mark: | 西安交大 兵馬俑 | [telnet://bbs.xjtu.edu.cn](telnet://bbs.xjtu.edu.cn) :x: | [Firebird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [YTHT BBS](https://github.com/lytsing/ytht) <br> [bmybbs](https://github.com/bmybbs/bmybbs) | 網頁版：<br> https://bbs.xjtu.edu.cn/ <br> 2021-12-18: Telnet 與 SSH 連線限校內連入 https://bbs.xjtu.edu.cn/BMY/con?B=sysop&F=M.1617802725.A
:white_check_mark: | 燕曦BBS | [telnet://yanxi.org](telnet://yanxi.org) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) |
* 北京大學 一塌糊涂 20040913被關 telnet://ytht.net
* 清華大學 水木清華 20050316封校 telnet://smth.org
* 南京大學 小百合 20050322分站 telnet://bbs.nju.edu.cn

## 其他海外華文 BBS 站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 美國 天天壇 | [telnet://tttan.com](telnet://tttan.com) | [Firebird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [YTHT BBS](https://github.com/lytsing/ytht) | |
| :white_check_mark: | 美國 San Diego Home | [telnet://bbs.huaxiaspace.net](telnet://bbs.huaxiaspace.net) :x: <br> [telnet://sd-bbs.net](telnet://sd-bbs.net) | [Firebird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2021-12-01: up |

## 加密連線站台資料列表

### SSH 連線

- 連線方式有 `<user>` 的站台，ssh 帳密與 telnet BBS 帳密同步，請將 `<user>` 代入 telnet 帳號 ID。
- 有 (SSH-1) 標示的站台，只支援 SSH-1 → *不安全*

| 站名 | 連線方式 | 備註 |
| - | - | - |
| 批踢踢實業坊 | `ssh bbs@ptt.cc` <br> `ssh bbsu@ptt.cc` (預設使用 UTF-8) | |
| 批踢踢兔 | `ssh bbs@ptt2.cc` <br> `ssh bbsu@ptt2.cc` (預設使用 UTF-8) | |
| 批踢踢參 | `ssh bbs@ptt3.cc` | 密碼: `bbs` |
| 台大未來最舊小棧 | `ssh bbs@ofo.tw` | |
| 中正通訊 1394 | `ssh bbs@bbs.comm.ccu.edu.tw` | 密碼: `bbs` |
| 夢之大地 | `ssh bbs@ccns.ncku.edu.tw` <br> `ssh bbsu@ccns.ncku.edu.tw` <br> `ssh bbs@ccns.cc` <br> `ssh bbsu@ccns.cc` | *未*支援 UTF-8 | 
| 成功高中 沈澱日記 | `ssh -p 25 bbsu@bbs.ckcsc.net` | |
| 台中一中電研社 極光鯨藍 | `ssh bbs@tcirc.org` | |
| 北京大學 | `ssh <user>@bbs.pku.edu.cn` | guest 可登入，密碼為空
| 未名空間 | `ssh <user>@mitbbs.com` (SSH-1) :unlock: | |
| 水木社區 | `ssh <user>@newsmth.org`  <br> `ssh <user>@bbs.newsmth.net` <br> `ssh <user>@bbs.mysmth.net` | |
| 清華大學 聽濤站 | `ssh <user>@bbs.tingtao.net` (SSH-1) :unlock: |
| 清華大學 大話西遊 | `ssh <user>@wforum.zixia.net` (SSH-1) :unlock: <br> `ssh <user>@bbs.zixia.net` (SSH-1) :unlock: | guest 可登入 |

### Websocket 連線

* 可從改版過的 PttChrome (網頁版) 免安裝體驗

| 站名 | 位址 | PttChrome 網頁版 | PttChrome 網頁版版本 |
| - | - | - | - |
| 批踢踢實業坊 | [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) | <https://term.ptt.cc> | <https://github.com/robertabcd/PttChrome> |
| 批踢踢兔 | [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) | <https://term.ptt2.cc> | <https://github.com/robertabcd/PttChrome> |
| 台大資管 鳴蟬小站 墮落天堂 | [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) | <https://tolo.ntu.im> | <https://github.com/robertabcd/PttChrome> |
| 淒美燈塔 | [wss://bbs.pharos.rocks](wss://wsbbs.pharos.rocks) | <https://bbs.pharos.rocks> | <https://github.com/robertabcd/PttChrome> |
| 中正大學 闇黑國度 | [wss://term.cna.ccu.edu.tw:9800](wss://term.cna.ccu.edu.tw:9800) :unlock: | <https://term.cna.ccu.edu.tw> :unlock: | <https://github.com/robertabcd/PttChrome>
| 夢之大地 | [wss://ws.ccns.ncku.edu.tw/bbs](wss://ws.ccns.ncku.edu.tw/bbs) (支援 IPv6) <br> [wss://ws.ccns.cc/bbs](wss://ws.ccns.cc/bbs) | <https://term.ccns.ncku.edu.tw> <br> <https://term.ccns.cc> | <https://github.com/ccns/PttChrome> |
| 台中一中 龍夢紀元 | [wss://eod.tw/bbs](wss://eod.tw/bbs) <br> [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs) | |
| 台中一中電研社 極光鯨藍 | [wss://tcirc.org/bbs](wss://tcirc.org/bbs) | | |
| 巴哈姆特 BBS | [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) | <https://term.gamer.com.tw> | <https://github.com/robertabcd/PttChrome> |
| 花魁異色館 | [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) | <https://libido.malusu.com> | <https://github.com/robertabcd/PttChrome> |
| YKLM大學 | [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) | <https://yklm.schl.tw> | <https://github.com/yklmbbs/PttChrome> |

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


<big><pre>* Pirate BBS 1.6  Mississippi State University  The Mars Hotel  1990
&nbsp; ├── [Pirate BBS 1.9](https://github.com/bbsmirror/BBSmirror/blob/master/PirateBBS/pbbs-1.9.tar.Z)  1992
&nbsp; └── Eagles BBS 1.1  The University of Southern Mississippi  The Eagle's Nest＊  1992
&nbsp;     ├── Eagles BBS 2.0  1992&ndash;1993
&nbsp;     │   ├── Eagles BBS [3.0](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/ebbs-3.0.tgz)  1994, 1995
&nbsp;     │   │   ├── Eagles BBS [3.1](https://wq5l.net/ebbs/) ([archived](https://github.com/bbsmirror/BBSmirror/blob/master/EaglesBBS/ebbs-3.1.1.tar.gz))  1995&ndash;2020
&nbsp;     │   │   └── [Palm BBS](https://github.com/bbsmirror/BBSmirror/blob/master/cuhk_ifcss/palmbbs-2.01.tar.gz)  臺大計中  椰林風情  1995
&nbsp;     │   ├── [Pivot BBS](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot) [5.8](https://github.com/bbsmirror/BBSmirror/tree/master/PivotBBS/source/pivot/v5.08) 中興計中  天樞資訊  1993&ndash;1996
&nbsp;     │   │   ├── [NCHU Pivot BBS 5.9](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot/pivot5.9.tar.gz)  1996
&nbsp;     │   │   └── [Feeling BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Feeling-nsysu)  中正計中  寂寞芳心  1995&ndash;1996
&nbsp;     │   ├── NCTU CIS BBS  交大資科  n.d.
&nbsp;     │   ├── Phoenix BBS 3.0  交大資工  鳳凰城資訊站  1993, 1994
&nbsp;     │   │   ├── [Phoenix BBS 4.0](https://github.com/bbsmirror/BBSmirror/tree/master/PhoenixBBS)  1995
&nbsp;     │   │   │   ├── [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk) 2.00  中正資工  四百年來第一站  1995
&nbsp;     │   │   │   │   ├── Hibiscus Realm BBS (FireBird BBS 2.5M&ndash;[2.66M](https://github.com/bbsmirror/BBSmirror/blob/master/cuhk_ifcss/FirebirdBBS2.66M.Big5.tgz))
&nbsp;     │   │   │   │   │   │  中央大學  大紅花的國度  1997, 1998
&nbsp;     │   │   │   │   │   ├── [FireBird BBS 3.0](https://github.com/bbsmirror/BBSmirror/blob/master/FireBird/ftp.firebird.org.tw/3.0-RELEASE.tar.gz)  N.A.  1999
&nbsp;     │   │   │   │   │   │   ├── [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/FB2000deardragon.tar.gz)  华南农业大学  快意灌水站  1999, 2000
&nbsp;     │   │   │   │   │   │   │   ├── PKUBBS  北京大学  北大未名  1999&ndash;
&nbsp;     │   │   │   │   │   │   │   ├── Lily BBS ([NJUWWWBBS](https://code.google.com/archive/p/lily-bbs/source/default/source))  南京大学  小百合  2000&ndash;2005
&nbsp;     │   │   │   │   │   │   │   │   └── fdubbs  复旦大学  日月光华＊  2002&ndash;2008
&nbsp;     │   │   │   │   │   │   │   │       └── [fbbs](https://github.com/fbbs/fbbs)  2008&ndash;
&nbsp;     │   │   │   │   │   │   │   ├── [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs)  上海交通大学  饮水思源＊  n.d.
&nbsp;     │   │   │   │   │   │   │   │   └── [nykzbbs](https://github.com/scaret/nykz)  南洋客棧＊  n.d.
&nbsp;     │   │   │   │   │   │   │   ├── [inankai bbs](https://github.com/madoldman/inankai_bbs)  南开人社区  2010&ndash;2011
&nbsp;     │   │   │   │   │   │   │   └── [argo bbs](https://github.com/argomaintainer/bbssrc)  中山大学  逸仙时空  n.d.
&nbsp;     │   │   │   │   │   │   └── Freecity BBS  浙江大学  飘渺水云间  2002&ndash;n.d.
&nbsp;     │   │   │   │   │   ├── FireBird BBS 2.x-KCN  清华大学  虚无空间  1998
&nbsp;     │   │   │   │   │   │   └── [FireBird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/FireBird3.0Kbeta6.tar.gz)  N.A.  1999
&nbsp;     │   │   │   │   │   │       ├── [FireBird BBS NT](https://github.com/bbsmirror/BBSmirror/blob/master/FireBird/NT/fbnt_b3.zip)  N.A.  2000&ndash;2001
&nbsp;     │   │   │   │   │   │       └── [YTHT BBS](https://github.com/lytsing/ytht)  北大物理 一塌糊涂  1999&ndash;2004
&nbsp;     │   │   │   │   │   │           └── [bmybbs](https://github.com/bmybbs/bmybbs)  西安交通大学  兵马俑  2003&ndash;
&nbsp;     │   │   │   │   │   └── [MagicBBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/MagicBBS) 0.90  魔法王國  1997&ndash;1999
&nbsp;     │   │   │   │   │       └── MagicBBS 1.x  1999&ndash;2000
&nbsp;     │   │   │   │   │           └── [PolyUBBS](https://github.com/bbsmirror/BBSmirror/tree/master/PolyU)  香港理工大學  紅磚學術資訊網  1999&ndash;2001
&nbsp;     │   │   │   │   ├── EggRoll BBS  淡江大學  蛋捲廣場  1996&ndash;2002
&nbsp;     │   │   │   │   └── [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d)  清华大学  水木清华  2001&ndash;2005
&nbsp;     │   │   │   │       ├── [SMTH BBS 2.0](https://github.com/zhouqt/kbs/tree/70c3ec0b8564a65b9a72887d10fb829f8d560d30)  2005
&nbsp;     │   │   │   │       │   └── [KBS](https://github.com/zhouqt/kbs)  水木社区＊  2005&ndash;
&nbsp;     │   │   │   │       ├── [zixia BBS](https://github.com/zixia/bbs)  清华大学  大话西游 紫霞BBS＊  2001&ndash;
&nbsp;     │   │   │   │       ├── MITBBS  未名空间＊  2005&ndash;
&nbsp;     │   │   │   │       ├── [TongJi BBS](https://github.com/moqi88/tongjibbs)  同济大学  同舟共济  2007
&nbsp;     │   │   │   │       └── [LilacBBS](https://github.com/marvelliu/lilacsrc)  紫丁香社区＊  2011&ndash;
&nbsp;     │   │   │   └── [Napoleon BBS](https://github.com/bbsmirror/BBSmirror/tree/master/NapoleonBBS)  交大工管  1995&ndash;1997
&nbsp;     │   │   └── Secret BBS 3.1  大同資工  秘密情人  1994
&nbsp;     │   │       ├── [Secret BBS 4.0](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/S4.0B.tgz)  1994
&nbsp;     │   │       │   └── [Secret BBS 4.1B](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/S4.1B.tgz)  1995
&nbsp;     │   │       └── [MapleBBS 2.36](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/MapleBBS-2.36b.tar.gz)  清大資科  楓橋驛站＊  1994&ndash;1995
&nbsp;     │   │           ├── MapleBBS [3.00b&ndash;3.01-fbsd](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/Old/Alpha)  1995&ndash;1998
&nbsp;     │   │           │   └── DragonII BBS (MapleBBS [3.01](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/Old/Beta/MapleBBS-3.01.tgz)&ndash;[3.02](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/MapleBBS-3.02-RELEASE.tgz))  交通大學  新冷馨居  1998&ndash;1999
&nbsp;     │   │           │       ├── [MapleBBS 3.10](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/MapleBBS-3.10-20000606-SNAP.tgz)  1998&ndash;2000
&nbsp;     │   │           │       │   └── [MapleBBS 3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)  臺南一中  與南共舞*  2000&ndash;2012
&nbsp;     │   │           │       │       ├── [MapleBBS 3.20](https://github.com/maplebridge/bbs) (3.10-ATOM)  清大資科  楓橋驛站＊  2007&ndash;2011
&nbsp;     │   │           │       │       ├── [MapleBBS 3.10-WEB-hightman](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/MapleBBS-3.10-WEB-20011031.tar.gz)  浙江大学  笑书亭  2001&ndash;
&nbsp;     │   │           │       │       ├── [AT2-BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Athena/AT2)  亞世界  2002&ndash;2003
&nbsp;     │   │           │       │       ├── [Auroral BBS](https://github.com/MapleCirc/Auroral)  台中一中 極光鯨藍＊  2007&ndash;2014
&nbsp;     │   │           │       │       ├── [MapleBBS-itoc-emu486](https://github.com/irvin/MapleBBS-itoc-emu486)  內灣新小月台＊  2008&ndash;2012
&nbsp;     │   │           │       │       ├── [XDBBS](https://github.com/hrs113355/Maple-XDBBS)  叉滴小站  2008&ndash;n.d.
&nbsp;     │   │           │       │       │   └── [windyvalleybbs](https://github.com/bbsmirror/windyvalleybbs)  成大電機 風之谷  2010&ndash;2019
&nbsp;     │   │           │       │       ├── [easttownbbs](https://github.com/guessi/easttownbbs)  東華大學 東方小城＊  2011&ndash;
&nbsp;     │   │           │       │       ├── [SonyBBS](https://github.com/lantw44/sonybbs)  台南一中 索尼小站＊  2012&ndash;2019
&nbsp;     │   │           │       │       └── [PartnerBBS](https://github.com/patw0929/MapleBBS-itoc)  伙計小站  n.d.
&nbsp;     │   │           │       └── [Melix BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/melix)  N.A.  2001
&nbsp;     │   │           ├── [Rouge BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple2/branch/Rouge)  交通大學  冷馨居  1995&ndash;1997
&nbsp;     │   │           ├── [SOB BBS](https://github.com/bbsmirror/BBSmirror/tree/master/SOB) 0.22  臺灣大學  陽光沙灘  1996
&nbsp;     │   │           │   ├── SOB-fromzero (SOB 3.0)  臺大電機  從零開始  n.d.
&nbsp;     │   │           │   │   └── [SOB domi](https://github.com/bbsmirror/BBSmirror/blob/master/SOB/sob_rfc2047.tar.gz)  糟了！誤上賊船  n.d.
&nbsp;     │   │           │   ├── Forest BBS  (中原資管  森林站？)  n.d.
&nbsp;     │   │           │   ├── [Atlantis BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis)  亞特蘭提斯＊  1996&ndash;
&nbsp;     │   │           │   ├── NaiveAge BBS  中央機械  純真年代  n.d.
&nbsp;     │   │           │   ├── Ptt BBS 0.001  臺灣大學  批踢踢實業坊＊  1996&ndash;2000
&nbsp;     │   │           │   │   ├── Ptt BBS [1.0.0](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.0.tar.gz) ([archived](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt))  1996&ndash;2000
&nbsp;     │   │           │   │   │   ├── [Open Ptt](https://github.com/bbsmirror/openptt) (Ptt BBS [1.0.1](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.1.tar.gz)&ndash;[1.0.2](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.2.tar.gz))  2001
&nbsp;     │   │           │   │   │   ├── [Ptt BBS Current](https://github.com/ptt/pttbbs)  2003&ndash;
&nbsp;     │   │           │   │   │   │   ├── [pttbbs-henry](https://github.com/alextwl/pttbbs-henry)  暨大資工 霞蔚山城  2006&ndash;2015
&nbsp;     │   │           │   │   │   │   └── [BRsBBS](https://github.com/BunnyBBS/BRsBBS)  BunnyBBS  2018&ndash;
&nbsp;     │   │           │   │   │   └─── [saloon BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/branch/saloon/saloonsrc.tgz)  煮酒論英雄  2001
&nbsp;     │   │           │   │   └── WD BBS 1.34  風與塵埃的對話＊  1999
&nbsp;     │   │           │   │       ├── [WD BBS 2.3](https://github.com/bbsmirror/BBSmirror/blob/master/WD/branches/exbbs/tgz/wd_991119_snap_for_linux.tgz) 1999
&nbsp;     │   │           │   │       │   ├── WD BBS  2000&ndash;2010
&nbsp;     │   │           │   │       │   │   └── [CCUMATH-BBS](https://github.com/jcppkkk/MapleBBS-3.00)  中正大學 無數不學  n.d.&ndash;2013
&nbsp;     │   │           │   │       │   ├── [Athena BBS (AT-BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/Athena/AT)  雅典娜  1999&ndash;2002
&nbsp;     │   │           │   │       │   └── [WD_hialan BBS (AT3-BBS)](https://github.com/hialan/hialanBBS) ([archived](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/hialan))  威尼斯咖啡館  2002&ndash;2017
&nbsp;     │   │           │   │       └── [StarRiver BBS](https://github.com/bbsmirror/BBSmirror/tree/master/StarVersion)  輔仁大學  星河夜話/銀河鐵道之戀  2000&ndash;2002
&nbsp;     │   │           │   └── WindTop BBS [2.2](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/Wind/wind1101.tgz)&ndash;[2.4](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-19991229-V2.4.tgz)  元智大學  風之塔＊  1998-1999
&nbsp;     │   │           │       └── [WindTop BBS 3.0x](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop)  2000&ndash;2004
&nbsp;     │   │           │           ├── WindTop BBS 3.10  2004&ndash;2009
&nbsp;     │   │           │           └── DreamLand BBS 3.02  成功大學  夢之大地＊  2004&ndash;2009
&nbsp;     │   │           │               └── [DreamLand BBS 3.10 (DreamBBS 2010)](https://github.com/ccns/dreambbs2010)  2010&ndash;2017
&nbsp;     │   │           │                   └── [DreamLand BBS](https://github.com/ccns/dreambbs)  2017&ndash;
&nbsp;     │   │           ├── [RPG BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple2/branch/rpg)  交通大學  創世紀  1996&ndash;1997
&nbsp;     │   │           └── [Purple Garden BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/fpgsrc.tgz)  臺灣法律  小魚的紫色花園  1999
&nbsp;     │   └── NCU BBS  中央大學  N.A.  n.d.
&nbsp;     └── [NSYSU BBS](https://github.com/bbsmirror/BBSmirror/blob/master/FormosaBBS/old/bbs-2.2.1.tar.gz)  中山計中  美麗之島  1994, 1996, 1997, 1998
&nbsp;         ├── [Formosa BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FormosaBBS) [1.4.1](https://github.com/pigfoot/formosa/tree/c5efe3d3cb82e9c03cefeb6cd760bb9dfba8023e)  中山計中  美麗之島＊  1997&ndash;2009
&nbsp;         │   └── [Formosa BBS CE](https://github.com/PichuChen/formosa)  2009&ndash;2012
&nbsp;         ├── FCU CC BBS  逢甲計中  蒼穹資訊網  n.d.
&nbsp;         └── Rose BBS  (玫瑰天空？)  n.d.
* [Power BBS](https://github.com/bbsmirror/BBSmirror/tree/master/PowerBBS)  中華資工  方城資訊站  1994&ndash;1997
* [ColaBBS](https://github.com/bbsmirror/BBSmirror/tree/master/ColaBBS)  交大資科  插花島  1997&ndash;2000
* [天火 BBS](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) ([archived](https://github.com/bbsmirror/BBSmirror/tree/master/rexchen))  淡江電機  蛋捲廣場＊  2002
</pre></big>

### 譜系圖參考資料
* 過去的 TANet BBS 發展譜系圖及相關說明
   - Su, Y. (1995, December). *[轉貼] 電子布告欄簡介*. 中山大學 West BBS-西子灣站. http://bbs3.nsysu.edu.tw/txtVersion/treasure/ee90-2/M.889205710.A/M.889268386.A.html
   - geniuswei. (2007, May 8). *Re: [請益] 關於BBS的定義*. 批踢踢實業坊. https://www.ptt.cc/bbs/ask/M.1178594446.A.727.html
* Maple 系列發展譜系圖
   - [Ho, L.-S. \[holishing\]](https://github.com/holishing). (2018, January 6). *[分享] 目前各版本 BBS server 安裝資訊*. 批踢踢實業坊. https://www.ptt.cc/bbs/AppsForBBS/M.1515230521.A.104.html
   - Dopin. (2002, July 18). *Maple Family (by Dopin) Ver. 5*. 亞特蘭提斯站 ([telnet://125.227.52.214](telnet://125.227.52.214)). ATSVersion 板 置底
* FireBird 系列發展沿革與譜系圖
   - Huang, L.-T. (2017, Sep). BBS 之前世今生. *YTHT BBS 开发指南*. https://lytsing.gitbooks.io/ytht-bbs/content/bbs-history.html
    * luckwithme, [mo7](https://github.com/moqi88), & kxn (2007). *Re: 有没有各个bbs版本的关系图*. In SpiritRain (Ed.), BBSView 版 (精华区). 水木社区. https://www.mysmth.net/bbsanc.php?p=1156-1-2
    * Li, X.-R. (1999, December 6). 蛋 捲廣 場 秘 史-- 第 419 期 專題報導. *淡江時報 Tamkang Times*. https://tkutimes.tku.edu.tw/dtl.aspx?no=7364
* Eagles BBS 的相關資料
    * 官方站臺：`ssh -l bbs bbs.wq5l.net`
    * 經 Eagles BBS 原作者之一 Ray Rocker 認可的官方網站
        - https://enbbs.org/
        - 含以下網路文章的鏈結
    * 介紹到了 Pirate BBS，並提到了 Eagles BBS 與 Pivot BBS 的文章
        * Scott, J. (2008, November 4). *When the BBS Broke Free*. ASCII by Jason Scott. http://ascii.textfiles.com/archives/1474
    * 由 Eagles BBS 原作者之一 Ray Rocker 撰寫的介紹了 Eagles BBS 的起源的文章
        - Rocker, R. (1994, August 1). *Eagles BBS*. Linux Journal. https://www.linuxjournal.com/article/2789
    * Eagles BBS 2.00 的簡介說明文件（提到了 NSYSU BBS）
        - Rocker, R. (1993, May 1). *README.first*. https://github.com/bbsmirror/bbshistory/blob/48f8b22c4234296bebc86a749f946fc091ab41c1/EaglesBBS-2.00-README.first
        - [Secret BBS 4.0](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/S4.0B.tgz)  (`S4.0B/doc/README.first.obsoleted`)
        - [Pivot BBS 5.04-pl14](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot/v5.04/pivot.5_04.pl14.tar.gz) (`pivot/INFO/README.first`)
* PCMAN 瀏覽器內建的站臺列表 https://github.com/bbslist/bbslist.github.io/blob/master/pcman-windows/BBSList
* 過去的文件與文字紀錄：https://github.com/bbsmirror/bbshistory
* 現存站臺上的版權宣告及相關公告
* 程式原始碼中的相關文件（見譜系圖中各鏈結）
