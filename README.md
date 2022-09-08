# 已知現存中文 BBS 站台

###### tags: `telnet` `ssh` `BBS` `電子布告欄` `站台` `TANet BBSes` `華文 BBSes` `BBS 分支圖` `BBS 系統沿革` `Known Existing Chinese Language BBSes`

## 本文版本
* stable version: [on GitHub](https://github.com/bbslist/bbslist.github.io)
* co-writing version: [on HackMD](https://hackmd.io/r1pdt-59b)

共筆版本 (co-writing version) 可自由編輯；穩定版本 (stable version) 則是共筆版本在被修改且經過不定的一段時間後，若經確認沒太大問題的話，才會 push 上去更新。

若覺得 GitHub 版本太久沒更新可去[提 issue](https://github.com/bbslist/bbslist.github.io/issues)。

而整體資訊是否及時，或查驗流程是否順暢，則取決於能協助確認資訊、改善方法的大大們有多少了。

## 可連線數量

* 目前統計有 **52**/126 個 (2022-07-24)
* 詳細情況請見下文表格中的 `可連` 欄位
* 為便於判斷，以測試時從外網可使用任一直接網路連線途徑連入為判斷原則。可能適逢站臺暫時離線維護，如有不便，尚祈見諒。
* 列表以文字終端機介面為基礎並提供 telnet、ssh 等網路連線途徑的站台為主，若只有 Web 論壇形式的站台暫不列入。
* 本文列出的從未被過去的站臺列表收錄的私人小型站臺，以站長知情且同意補充者為主。

## 近期修正與補充欄位

* BBS 站台程式版本，可搭配參考 BBS 站台程式開發分支圖。
    * PttBBS/Ptt current 版號可搭配 [此連結](https://github.com/ptt/pttbbs/blob/master/UPDATING) 了解其重大差異
* 加密連線支援資訊，以 :lock: 標示，可搭配參考表格式的加密連線站台列表。
    * 已將 PttChrome 網頁版程式版本資訊加入支援 Websocket 連線的站台列表。
* **`twbbs.org`** 網域已經終止服務，故現不附上相關網域資訊
* 補充 Web 版網址。以站台資料與 telnet、ssh 等介面的資料同步者為主。
* 已將站臺依衍生關係→校名（若有，取全名去稱謂）讀音→站名讀音排序。讀音方面忽略聲調，中國大陸站臺與海外站臺依漢語拼音 Unicode 順序，其它站臺依注音 Unicode 順序。

還請其他熱心人士協助編輯補充 `^_^`

## 大學相關站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 銘傳大學 築夢別境 | [telnet://bbs.mcu.edu.tw](telnet://bbs.mcu.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2022-02-06: 域名解析失敗 |
| :x: | 逢甲紡織 七月七日晴 | [telnet://77bbs.com](telnet://77bbs.com) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2022-02-07: 重新導向至環球科技大學網頁 |
| :x: | 淡江資管 渡船頭之戀 | [telnet://bbs.im.tku.edu.tw](telnet://bbs.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-06-24 測試: down |
| :x: | 淡江蛋捲 新系統測試站 | [telnet://loyal.ee.tku.edu.tw](telnet://loyal.ee.tku.edu.tw) | [天火系統](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) | 2019-10-30 測試: 連線失敗 <br> 2022-02-14: ping 有回應 |
| :x: | 淡江資管 星星之戀 | [telnet://starlove.im.tku.edu.tw](telnet://starlove.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)| |
| :x: | 東海大學 資訊傳奇 | [telnet://bbs.csie.thu.edu.tw](telnet://bbs.csie.thu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-07: 域名解析失敗 |
| :x: | 東海數學 陽光草坪 | [telnet://122.117.69.100](telnet://122.117.69.100) | [PttBBS](https://github.com/ptt/pttbbs) <br/> (不明舊版本) | 2022-02-14: `Destination host unreachable.` |
| :white_check_mark: | 東華大學 東方小城 | [telnet://bbs.ndhu.edu.tw](telnet://bbs.ndhu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [easttownbbs](https://github.com/guessi/easttownbbs) | 網頁版: <http://bbs.ndhu.edu.tw> :unlock: <br> 2021-01-10: 已正常 <br> 2021-08-18: 未加密網頁版 up |
| :white_check_mark: | 東吳機研站 | [telnet://scumotor.com.tw](telnet://scumotor.com.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://scumotor.com.tw:8080> :unlock: <br> 2021-05-26: 已正常 |
| :x: | 臺北大學 北極星 | [telnet://bbs.ntpu.edu.tw](telnet://bbs.ntpu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-12-01: down |
| :white_check_mark: | 臺北市立大學 七號出口 |   [telnet://bbs.utaipei.edu.tw](telnet://bbs.utaipei.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本: <= 2008-10-12) | 2022-07-24: up |
| :x: | 台北醫學大學 杏林綠意 | [telnet://bbs.tmu.edu.tw](telnet://bbs.tmu.edu.tw) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 另外有很多班板在未來最舊小站 |
| :x: | 台中教育大學 柳岸咖啡館 | [telnet://bbs.ntcu.edu.tw](telnet://bbs.ntcu.edu.tw) | 未納入版本管理的 Maple-itoc fork | 硬碟毀損，域名屬於學校，目前無復站希望，詳見 [#4](https://github.com/bbslist/bbslist.github.io/issues/4) |
| :x: | 台大 不良牛 | [telnet://bbs.badcow.com.tw](telnet://bbs.badcow.com.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) <br> [SOB-fromzero](https://github.com/bbsmirror/BBSmirror/blob/master/SOB/sob_rfc2047.tar.gz) | 因仍有 DNS 反查, 部份BBS瀏覽軟體不支援 <br> 2021-08-11: 連線失敗 |
| :white_check_mark: | 台大批踢踢 | ~~telnet://ptt.cc <br> [ip](telnet://140.112.172.11) / [ip<sub>1</sub>](telnet://140.112.172.1) / [ip<sub>2</sub>](telnet://140.112.172.2) / [ip<sub>3</sub>](telnet://140.112.172.3) / [ip<sub>4</sub>](telnet://140.112.172.4) / [ip<sub>5</sub>](telnet://140.112.172.5)~~ <br> `ssh bbs@ptt.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt.cc> (wss) [:lock:](#Websocket-連線) | [PttBBS git r5011+](https://github.com/ptt/pttbbs) | 網頁版: <https://www.ptt.cc/bbs> <br> guest無法登入 <br> 2022-04-15 停用 Telnet 連線 |
| :white_check_mark: | 批踢踢兔 | ~~telnet://ptt2.cc~~ <br> `ssh bbs@ptt2.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt2.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt2.cc> (wss) [:lock:](#Websocket-連線) | [PttBBS git r5011+](https://github.com/ptt/pttbbs) | guest無法登入 <br> 2022-04-15 停用 Telnet 連線 |
| :x: | 批踢踢參 | [telnet://ptt3.cc](telnet://ptt3.cc) <br> `ssh bbs@ptt3.cc` [:lock:](#SSH-連線) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r4423 | 2019-10-30 測試: 連線失敗 |
| :white_check_mark: | 台大資管 鳴蟬小站 (墮落天堂) | [telnet://bbs.im.ntu.edu.tw](telnet://bbs.im.ntu.edu.tw) <br> [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) [:lock:](#Websocket-連線) :x: <br> <https://tolo.ntu.im> (wss) [:unlock:](#Websocket-連線) :x: | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-08-11: PttChrome 誤連到批踢踢 <br> 2021-12-01: WSS 連線失敗；加密憑證網域設定錯誤 |
| :x: | 台大物理 冷月流蘇 | [telnet://bbs.phys.ntu.edu.tw](telnet://bbs.phys.ntu.edu.tw) <br> [telnet://bbs.phys.tw](telnet://bbs.phys.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | |
| :white_check_mark: | 台大未來最舊 | [telnet://ofo.tw](telnet://ofo.tw) <br> `ssh bbs@ofo.tw` [:lock:](#SSH-連線) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) <br> Oldest future Object | 不開放guest <br> 2021-04-28 測試: Up |
| :x: | 高雄大學 原野星辰 | [telnet://bbs.nuk.edu.tw](telnet://bbs.nuk.edu.tw) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 海洋大學 | [telnet://bbs.ntou.edu.tw](telnet://bbs.ntou.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 海洋電機 忘晴海 | [telnet://bbs.ee.ntou.edu.tw](telnet://bbs.ee.ntou.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本) | 2022-02-14: 域名解析失敗 |
| :x: | 暨大電機 漂浮電子 | [telnet://bbs.ee.ncnu.edu.tw](telnet://bbs.ee.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 暨大土木 土木小站 | [telnet://bbs.ce.ncnu.edu.tw](telnet://bbs.ce.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法使用guest，以及看板列表毀損 |
| :x: | 暨南大學 水沙連 | [telnet://bbs.ncnu.edu.tw](telnet://bbs.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-07-24: 連線逾時 |
| :x: | 交通大學 機械工廠 |  [telnet://bbs.me.nctu.edu.tw](telnet://bbs.me.nctu.edu.tw) | [Maple3.10-itoc](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2020-12-17 測試: 連線失敗 <br> 2022-02-14: 域名解析失敗 |
| :white_check_mark: | ~~交大~~淒美燈塔 | [telnet://bbs.pharos.rocks](telnet://bbs.pharos.rocks) <br> [wss://bbs.pharos.rocks](wss://bbs.pharos.rocks) [:lock:](#Websocket-連線) <br> <https://bbs.pharos.rocks> (wss) [:lock:](#Websocket-連線) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2019-10-31 測試: Websocket up |
| :x: | 交通大學 次世代 | [telnet://bs2.to](telnet://bs2.to) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [已關站](https://www.ptt.cc/bbs/NCTU_TALK/M.1461738017.A.8BA.html) |
| :white_check_mark: | 次世代．佚 | [telnet://bs2.io](telnet://bs2.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [另外發起](https://www.ptt.cc/bbs/NCTU_TALK/M.1469423697.A.2AE.html)之相關延續站台 |
| :white_check_mark: | 靜宜大學 水世界 | [telnet://bbs.cs.pu.edu.tw:3001](telnet://bbs.cs.pu.edu.tw:3001) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> [3.02 Rev. 20001103](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-3.02-20001103-SNAP.tgz) | 2016因校計中資安政策封鎖Port 23，請改用Port 3001 or 3456連線 <br> 2021-08-12: Up |
| :white_check_mark: | 清華大學 楓橋驛站 | [telnet://bbs.cs.nthu.edu.tw](telnet://bbs.cs.nthu.edu.tw) / [:443](telnet://bbs.cs.nthu.edu.tw:443) <br> [telnet://imaple.tw](telnet://imaple.tw) :x: / [:443](telnet://imaple.tw:443) :x: <br> [telnet://140.114.87.5](telnet://140.114.87.5) / [:443](telnet://140.114.87.5:443) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS 3.20 (3.10-ATOM)](https://github.com/maplebridge/bbs) r402 | (2007年, 系統從自己開發的系統, 轉換成 itoc 大 fork 出來的版本 繼續維護) <br> 2022-07-02: imaple.tw 連線失敗
| :x: | 清華資工 呼拉貝爾 | [telnet://114.32.9.125](telnet://114.32.9.125) | [WindTop BBS](http://windtop.yzu.edu.tw/) | |
| :x: | 彰師生命 擎天崗 | [telnet://bbs.bio.ncue.edu.tw](telnet://bbs.bio.ncue.edu.tw) <br> [telnet://bbs2.ncue.edu.tw](telnet://bbs2.ncue.edu.tw) <br> [telnet://micro.bio.ncue.edu.tw](telnet://micro.bio.ncue.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://micro.bio.ncue.edu.tw:8080> :unlock: <br> 2021-07-10: guest 不可登入 (無此帳號) <br> 2022-02-14: down；網頁版拒絕連線 |
| :x: | 真理大學 雲淡風清 | [telnet://bbs.au.edu.tw](telnet://bbs.au.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 真理大學 脆笛酥的家 | [telnet://bbs.jal.tw](telnet://bbs.jal.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: guest 不可登入 (無此帳號) |
| :x: | 政大資科 貓空行館 | [telnet://bbs.cs.nccu.edu.tw](telnet://bbs.cs.nccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) |
| :x: | 中正大學 寂寞芳心小站 | [telnet://bbs.ccu.edu.tw](telnet://bbs.ccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2018/8/3測試：down <br> 2022-02-14: 域名解析失敗 |
| :x: | 中正心理 心海奇航 賽卡羅旗號 | [telnet://140.123.185.40](telnet://140.123.185.40) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | ~~中正~~築夢園 | ~~telnet://140.123.29.12~~ <br> ~~telnet://cd.cna.ccu.edu.tw~~ <br> [telnet://207.148.108.123](telnet://207.148.108.123) <br> [telnet://ccudream.csie.io](telnet://ccudream.csie.io) <br> [telnet://cd.csie.io](telnet://cd.csie.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 已由Maple 3 轉至 Maple3.10-itoc 版本 <br> 2021-02-18 測試: 新域名 up <br> 預計 2021/12/30 關站 <br> 2021-12-30 取消關站 |
| :x: | 中正大學 闇黑國度 | [telnet://bbs.cna.ccu.edu.tw](telnet://bbs.cna.ccu.edu.tw) <br> [wss://term.cna.ccu.edu.tw:9800](wss://term.cna.ccu.edu.tw:9800) (TLS 1.0/1.1) [:unlock:](#Websocket-連線) <br> <https://term.cna.ccu.edu.tw> (wss) (TLS 1.0/1.1) [:unlock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-01-31: 預計 2022/3/1 關站 <br> 2022-07-02: 域名 down |
| :x: | 中正通訊 1394 | ~~telnet://bbs.comm.ccu.edu.tw~~ <br> `ssh bbs@bbs.comm.ccu.edu.tw` [:lock:](#SSH-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<https://bbs.comm.ccu.edu.tw> <br> 2021-08-18: Telnet 連線停用 <br> 2022-07-02: SSH 連線逾時 <br> 且網頁版拒絕連線 |
| :x: | 中山大學 美麗島 | [telnet://140.117.11.2](telnet://140.117.11.2) <br> [telnet://[2001:288:8001:11::2]](telnet://[2001:288:8001:11::2]) <br> [telnet://bbs.nsysu.edu.tw](telnet://bbs.nsysu.edu.tw) | [Formosa BBS CE](https://github.com/PichuChen/formosa) | (1992-12 資訊月開站) <br> 2021-07-10: IPv4 無法連線 |
| :x: | 中山大學 西子灣 | [telnet://140.117.11.6](telnet://140.117.11.6) <br> [telnet://[2001:288:8001:11::6]](telnet://[2001:288:8001:11::6]) <br> [telnet://bbs3.nsysu.edu.tw](telnet://bbs3.nsysu.edu.tw) | [Formosa BBS CE](https://github.com/PichuChen/formosa) | 網頁版: <https://[2001:288:8001:11::6]> <br> 2021-07-10: IPv4 無法連線 <br> 2021-07-10: 僅網頁版可連 <br> 2021-12-01: 網頁版 down |
| :x: | 中央大學 二進位 | [telnet://140.115.50.50](telnet://140.115.50.50) <br> [telnet://binary.csie.ncu.edu.tw](telnet://binary.csie.ncu.edu.tw) <br> [telnet://bbs.ncu.cc](telnet://bbs.ncu.cc) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-07-10: Down <br> 2022-02-14: .cc 域名解析失敗 |
| :x: | 中央數學 織夢天堂 | [telnet://bbs.math.ncu.edu.tw](telnet://bbs.math.ncu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 中央 神通廣大 | [telnet://bbs.ce.ncu.edu.tw](telnet://bbs.ce.ncu.edu.tw) | | |
| :white_check_mark: | 中原資工 神祕之旅 | [telnet://bbs.ice.cycu.edu.tw](telnet://bbs.ice.cycu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<https://bbs.ice.cycu.edu.tw> |
| :x: | 長庚大學 巧克力傳奇 | [telnet://bbs.cgu.edu.tw](telnet://bbs.cgu.edu.tw) | | 2022-02-14: 域名解析失敗 |
| :x: | 長庚醫學 醫甸園 | [telnet://bbs.med.cgu.edu.tw](telnet://bbs.med.cgu.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本) | |
| :white_check_mark: | 成功大學 夢之大地 | ~~telnet://140.116.250.3~~ **(IP已更改)** <br> ~~telnet://140.116.249.140~~  / [:3456](telnet://140.116.249.140:3456) **(現在IP)** <br> ~~telnet://[2001:288:7001:249::140]~~ / [:3456](telnet://[2001:288:7001:249::140]:3456)  <br> ~~telnet://ccns.cc~~ / [:3456](telnet://ccns.cc:3456) <br> `ssh bbs@ccns.cc` / `-p 22222` [:lock:](#SSH-連線) <br> [wss://ws.ccns.ncku.edu.tw/bbs](wss://ws.ccns.ncku.edu.tw/bbs) [:lock:](#Websocket-連線) <br> <https://term.ccns.cc> (wss) [:lock:](#Websocket-連線) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> 3.10 Rev. 20081002 <br> [DreamBBS git r1785+](https://github.com/ccns/dreambbs) | 2022-07-02: 校外 port 23 連線失敗 <br> 2022-07-02 棄用 Telnet 連線 <br> 2022-09-05: 校外 port 22 連線失敗 <br> ssh 連線請改用 port 22222 |
| :white_check_mark: | 成大電機 風之谷 | [telnet://bbs.ee.ncku.edu.tw](telnet://bbs.ee.ncku.edu.tw) :x: / [:3456](telnet://bbs.ee.ncku.edu.tw:3456) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [windyvalleybbs](https://github.com/bbsmirror/windyvalleybbs) r55.1 | guest過多無法登入；不開放線上註冊 <br> 2022-07-02: port 23 連線失敗 |
| :x: | 成大醫學 迴風谷 | [telnet://bbs.med.ncku.edu.tw](telnet://bbs.med.ncku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-07-02: port 23 連線失敗 |
| :x: | 師大資訊 白色情迷 | [telnet://bbs.csie.ntnu.edu.tw](telnet://bbs.csie.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-14: ping 有回應 |
| :white_check_mark: | 師大數學 獨數一閣 | [telnet://bbs.math.ntnu.edu.tw:8000](telnet://bbs.math.ntnu.edu.tw:8000) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5284 | 2022-06-21: 校外 port 改 8000 |
| :white_check_mark: | 師大 人民公社 | [telnet://cvic.org](telnet://cvic.org) <br> [telnet://cvic.be](telnet://cvic.be) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2019-10-31 測試: Up <br> 2021-07-10 guest 從主選單進入 `(C)onfig` 後直接按右鍵會進入空白選單 |
| :x: | 師大歷史 原史空間 | [telnet://bbs.his.ntnu.edu.tw](telnet://bbs.his.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: Down |
| :white_check_mark: | 慈濟大學 蔚藍海岸  | [telnet://perlbbs.tw](telnet://perlbbs.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | |
| :x: | 陽明 神農坡 | [telnet://bbs.ym.edu.tw](telnet://bbs.ym.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | PCman主要作者畢業學校 |
| :x: | 元智大學 風之塔 | [telnet://bbs.yzu.edu.tw](telnet://bbs.yzu.edu.tw) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | 2020-06-24 測試: down |
| :white_check_mark: | 元智資工 火車站 | [telnet://bbs.cse.yzu.edu.tw](telnet://bbs.cse.yzu.edu.tw) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> TrainBBS Ver.1220 | 2022-07-04: 進入 `(I)nfo` 會斷線 |
| :x: | 雲林科技大學 藍天使 | [telnet://bbs.yuntech.edu.tw](telnet://bbs.yuntech.edu.tw) | | 2017/1/5測試：down <br> 2022-02-14: 域名解析失敗 |

## 高中相關站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :white_check_mark: | 北一女中 弗基斯特 | [telnet://fgisc.org](telnet://fgisc.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台南一中 動力核心 | [telnet://cpu.tfcis.org](telnet://cpu.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-03-05: up |
| :x: | 台南一中資訊社 索尼小站 | [telnet://bbs.tfcis.org](telnet://bbs.tfcis.org) <br> [telnet://sony.tfcis.org](telnet://sony.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [SonyBBS](https://github.com/lantw44/sonybbs) | 不開放 guest <br> 2022-02-14: down |
| :white_check_mark: | 台南一中 與南共舞 | [telnet://bbs.tnfsh.tn.edu.tw](telnet://bbs.tnfsh.tn.edu.tw) <br> [telnet://wolf.tfcis.org](telnet://wolf.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 台中二中 迷幻國度 | [telnet://csc241.tcssh.tc.edu.tw](telnet://csc241.tcssh.tc.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-14: 域名解析失敗 |
| :x: | 台中一中 龍夢紀元 | [telnet://bbs.tcfsh.tc.edu.tw](telnet://bbs.tcfsh.tc.edu.tw) <br> [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs) [:lock:](#Websocket-連線) <br> [telnet://eod.tw](telnet://eod.tw) <br> [ws://eod.tw/bbs](ws://eod.tw/bbs) <br> [wss://eod.tw/bbs](wss://eod.tw/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 可以相容於 PTT 的 Websocket 模式連線 <br> 程式碼為極光鯨藍之穩定版本分支 <br> 2020-12-27 test: Down <br> 2022-02-14: .edu.tw 域名解析失敗；其它域名 ping 有回應 |
| :x: | 台中一中電研社 極光鯨藍 | [telnet://tcirc.org](telnet://tcirc.org/) <br> `ssh bbs@tcirc.org` [:lock:](#SSH-連線) <br> [wss://tcirc.org/bbs](wss://tcirc.org/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 可以相容於 PTT 的 Websocket 模式連線 <br> 2021-08-18: `DNS resolution error` |
| :x: | 建中之夏 烏魯木齊 | [telnet://bbs.ck.tp.edu.tw](telnet://bbs.ck.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-08-18: 域名解析失敗 |
| :white_check_mark: | 中壢高中 壢網狂瀾 | [telnet://clhs.csie.org](telnet://clhs.csie.org) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) [3.02 Rev. 20001220](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-3.02-20001220-SNAP.tgz) <br> CLHSBBS Ver.20030520 | 2022-07-02: up |
| :x: | 中山女中 楓資羽翼 | [telnet://203.68.236.13](telnet://203.68.236.13) <br> [telnet://csisc.csghs.tp.edu.tw](telnet://csisc.csghs.tp.edu.tw) | [WindTop](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) → [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://bbs.csghs.tp.edu.tw> :unlock: <br> 2019-12-31 測試: Down <br> 2021-08-18: 域名解析失敗 |
| :x: | 成功高中 沈澱日記 | `ssh bbsu@bbs.ckcsc.net -p 25` [:lock:](#SSH-連線) <br> <https://bbs.ckcsc.net> (ttyd) :lock: | [PttBBS git r4927+](https://github.com/ptt/pttbbs) | 提供網頁終端介面(ttyd)登入 <br> 2021-08-12: 連線逾時 <br> 2022-03-05: 域名解析失敗 |
| :x: | 永春高中 永春哈哈 | [telnet://haha.ycsh.tp.edu.tw](telnet://haha.ycsh.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法進去看板閱讀，僅能瀏覽公佈欄/精華區 <br> 2022-02-14: 域名解析失敗 |


## 不在學術網路的站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 八八八 | [telnet://bbs.wim888.tw](telnet://bbs.wim888.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版：<http://bbs.wim888.tw> :unlock: <br> 2022-07-24: 連線逾時 |
| :white_check_mark: | 巴哈姆特BBS | [telnet://bbs.gamer.com.tw](telnet://bbs.gamer.com.tw) <br> [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) [:lock:](#Websocket-連線) :x: <br> <https://term.gamer.com.tw> (wss) [:lock:](#Websocket-連線) <br> [telnet://bahamut.org](telnet://bahamut.org) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 網頁版: <https://www.gamer.com.tw> <br> guest 無法登入, 需先從 Web 註冊 <br> 2022-07-02: 直接連 WebSocket 失敗，須從 PttChrome 網頁版連線 |
| :white_check_mark: | 貓坑 CatPit | [telnet://bbs.cis92.net](telnet://bbs.cis92.net) | [MapleBBS 3.10](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) CCH Patch | |
| :x: | 反地球聯邦組織 | [telnet://122.116.74.57](telnet://122.116.74.57) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 風與塵埃的對話 | [telnet://wdbbs.tw](telnet://wdbbs.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-01-11: Down |
| :white_check_mark: | △．Kirika | [telnet://andcycle.idv.tw](telnet://andcycle.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 動漫遊戲廣播站 | [telnet://bbs.animeyo.com](telnet://bbs.animeyo.com) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台灣天主教BBS站 厄瑪奴耳 | [telnet://bbs-jesus.name](telnet://bbs-jesus.name) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 內灣新小月台 | [telnet://bbs.emu486.net](telnet://bbs.emu486.net) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS-itoc-emu486](https://github.com/irvin/MapleBBS-itoc-emu486) | 2022-07-02: up |
| :white_check_mark: | 南友小站 |[telnet://tainan.jal.tw](telnet://tainan.jal.tw) <br> [telnet://192.192.120.31](telnet://192.192.120.31) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 看板列表排版溢出，但仍可正常進入看板 <br> 2022-03-05: up |
| :white_check_mark: | 華年小集 | [telnet://literature.twbbs.io](telnet://literature.twbbs.io) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5563 | |
| :white_check_mark: | 花魁藝色館 | [telnet://libido.cx](telnet://libido.cx) <br> [telnet://74.52.17.106](telnet://74.52.17.106) :x: <br> [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) [:lock:](#Websocket-連線) <br> <https://libido.malusu.com> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2018/10 下旬起停用 libido.cx 域名連線 <br> 2021-08-18: 原域名 up <br> 不開放 guest 登入 <br> 2022-03-05: Telnet up |
| :x: | 伙計小站 | [telnet://patw.idv.tw](telnet://patw.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [PartnerBBS](https://github.com/patw0929/MapleBBS-itoc) | 2020/04/19:down |
| :white_check_mark: | 西雅圖 | [telnet://www.seattle.tw](telnet://www.seattle.tw) [telnet://seattle.tw](telnet://seattle.tw) [telnet://122.117.16.81](telnet://122.117.16.81) | [MapleBBS-3.10-20121021-PACK.itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020/02/22: 已復站 |
| :x: | 幸運草之戀 | [telnet://segaa.net](telnet://segaa.net) | [WindTopBBS-3.02-20021129-SNAP](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | 2022-07-02: 連線失敗 |
| :white_check_mark: | 書齋軒 | [telnet://bbs.windcity.net](telnet://bbs.windcity.net) | [Open Ptt](https://github.com/bbsmirror/BBSmirror/tree/master/Ptt/openptt) | 提供個人及團體板 |
| :white_check_mark: | 亞特蘭提斯 | [telnet://125.227.52.214](telnet://125.227.52.214) <br> [telnet://bbs.bsd.com.tw](telnet://bbs.bsd.com.tw) | [Atlantis](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis) | 註冊通過者, 可自己開個板, 免等審核 <br> 2022-07-24: up
| :white_check_mark: | 武陵人的桃花源 | [telnet://139.180.205.27:2323](telnet://139.180.205.27:2323) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | |
| :x: | 543 音樂站 | [telnet://music543.com](telnet://music543.com) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r3359 | 網頁版（資料不完全與 telnet 介面同步）：<http://music543.com> :unlock: <br> 2022-07-02: 連線逾時 |
| :x: | YKLM大學 | [telnet://yklm.schl.tw](telnet://yklm.schl.tw) :x: <br> [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) [:lock:](#Websocket-連線) :x: <br> <https://yklm.schl.tw> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-08-10: Up <br> 2022-02-14: Telnet down <br> 2022-07-02: WebSocket down |
| :white_check_mark: | 網際新世界 | [telnet://209.141.35.127](telnet://209.141.35.127) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-01-11: Up <br> 2021-07-10: guest 無法登入（無此帳號） |
| :x: | 月下夜想 | [telnet://220.130.248.130](telnet://220.130.248.130) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-14: ping 有回應 |


## 中國大陸站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :white_check_mark: | 北京大學 | [telnet://bbs.pku.edu.cn](telnet://bbs.pku.edu.cn) :x: <br> `ssh <user>@bbs.pku.edu.cn` [:lock:](#SSH-連線) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | 網頁版：<https://bbs.pku.edu.cn> <br> 2021-08-18 測試：SSH up |
| :white_check_mark: | 未名空間 | [telnet://mitbbs.com](telnet://mitbbs.com) :x: <br> `ssh <user>@mitbbs.com` (SSH-1) [:unlock:](#SSH-連線) :x: | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d) <br> MITBBS | 網頁版：<https://mitbbs.com> <br> 相關衍生之商業BBS站台 <br> 2021-08-18: 僅網頁版可連 |
| :white_check_mark: | 北京大學 大話西遊 | [telnet://dhxy.info](telnet://dhxy.info) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1106 (beta2) | 網頁版：<https://dhxy.info> :unlock: <br> 2021-08-21: guest 不可登入 (無此 ID) <br> 加密連線憑證過期 |
| :white_check_mark: | 北京大學 桃花潭 | [telnet://thtpku.3322.org](telnet://thtpku.3322.org) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版：<https://thtpku.3322.org> <br> 無法申請新帳號 <br> guest 不可登入 (無此帳號) <br> 2022-02-14: Telnet up |
| :x: | 北京大學 一塌糊塗 海外紀念站 | [telnet://bbs.ytht.net](telnet://bbs.ytht.net) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 北京郵電大學 北郵人論壇 | [telnet://bbs.byr.cn](telnet://bbs.byr.cn) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版：<br><https://bbs.byr.cn> |
| :x: | 東南大學 虎踞龍盤 | [telnet://bbs.seu.edu.cn](telnet://bbs.seu.edu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2022-02-14: 域名解析失敗 |
| :white_check_mark: | 復旦大學 日月光華 | [telnet://bbs.fudan.edu.cn](telnet://bbs.fudan.edu.cn) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [fbbs](https://github.com/fbbs/fbbs) | 網頁版：<https://bbs.fudan.edu.cn> <br> 2022-07-02: up |
| :white_check_mark: | ~~復旦大學~~ 燕曦BBS | [telnet://yanxi.org](telnet://yanxi.org) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | |
| :x: | 廣西師範大學 煙雨漓江 | [telnet://bbs.gxnu.cn](telnet://bbs.gxnu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2022-02-14: 域名解析失敗 |
| :x: | 哈爾濱工業大學 紫丁香站 | [telnet://bbs.hit.edu.cn](telnet://bbs.hit.edu.cn) | | 無法連線,可能是限制校外ip連入或關站 <br> 2022-02-14: 域名解析失敗 |
| :white_check_mark: | 紫丁香社區 | [telnet://lilacbbs.com](telnet://lilacbbs.com) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/)  <br> [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d) <br> [LilacBBS](https://github.com/marvelliu/lilacsrc) | 網頁版：<http://lilacbbs.com> :unlock: <br> 相關衍生之商業BBS站台 |
| :x: | 華中理工 白雲黃鶴 | [telnet://bbs.whnet.edu.cn](telnet://bbs.whnet.edu.cn) <br> [telnet://byhh.hust.edu.cn](telnet://byhh.hust.edu.cn) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | 網頁版：<http://byhh.hust.edu.cn> :unlock: <br> 2020-12-18 測試: Down <br> 2022-07-02: 網頁版限校內連入 |
| :x: | 蘭州大學 西北望BBS站 | [telnet://106.225.138.11:2223](telnet://106.225.138.11:2223) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 2022-07-24: 連線逾時 |
| :x: | 南京大學 小百合 | [telnet://bbs.nju.edu.cn](telnet://bbs.nju.edu.cn) (教育網) <br> [telnet://lilybbs.net](telnet://lilybbs.net) (公眾網) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | |
| :x: | 清華大學 | [telnet://smth.org](telnet://smth.org) | | (1995-08-08 開站) <br> [無法連線](https://www.ptt.cc/bbs/SMTH/M.1415081920.A.2B0.html) |
| :white_check_mark: | 水木社區 | [telnet://newsmth.org](telnet://newsmth.org) <br> `ssh <user>@newsmth.org` [:lock:](#SSH-連線) <br> [telnet://bbs.newsmth.net](telnet://bbs.newsmth.net) <br> `ssh <user>@bbs.newsmth.net` [:lock:](#SSH-連線) <br> [telnet://bbs.mysmth.net](telnet://bbs.mysmth.net) <br> `ssh <user>@bbs.mysmth.net` [:lock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版：<br> <https://www.newsmth.net> <br> <https://www.mysmth.net> <br> 相關衍生之商業BBS站台 |
| :white_check_mark: | 清華大學 大話西遊 (紫霞BBS) | [telnet://wforum.zixia.net](telnet://wforum.zixia.net) <br> `ssh <user>@wforum.zixia.net` (SSH-1) [:unlock:](#SSH-連線) <br> [telnet://bbs.zixia.net](telnet://bbs.zixia.net) <br> `ssh <user>@bbs.zixia.net` (SSH-1) [:unlock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) <br> [zixia BBS v21.2.1](https://github.com/zixia/bbs) |
| :x: | 清華大學 KissU | [telnet://bbs.thu.cn](telnet://bbs.thu.cn) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版：<https://bbs.thu.cn> <br> 2021-08-18: 僅網頁版可連 <br> 2022-07-02: 網頁版 502 |
| :white_check_mark: | 清華大學 聽濤站 | [telnet://bbs.tingtao.net](telnet://bbs.tingtao.net) <br> `ssh <user>@bbs.tingtao.net` (SSH-1) [:unlock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [SMTH BBS 1.0](https://github.com/zhouqt/kbs) | 網頁版：<https://bbs.tingtao.net> <br> 2022-03-05: up |
| :x: | 上海交大 飲水思源 | [telnet://bbs.sjtu.edu.cn](telnet://bbs.sjtu.edu.cn) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1106 (beta2) <br> [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs) | 網頁版：<https://bbs.sjtu.edu.cn> :unlock: :x: (TLS 1.0/1.1) <br> 不開放校外連線 <br> 2021-12-01: 加密連線憑證過期 |
| :white_check_mark: | 南洋客棧 | [telnet://bbs.nykz.net](telnet://bbs.nykz.net) <br> [telnet://back.nykz.net:2323](telnet://back.nykz.net:2323) :x: | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1219 <br> [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs) <br> [nykz BBS](https://github.com/scaret/nykz) | 相關衍生站臺 <br> 2021-10-12: guest 不可登入 (無此 ID) <br> 2022-02-14: back. 域名解析失敗 |
| :x: | 四川大學 藍色星空站 | [telnet://bbs.lsxk.org](telnet://bbs.lsxk.org) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 已經關閉telnet，只提供校內ssh加密訪問 |
| :white_check_mark: | 西安交大 兵馬俑 | [telnet://bbs.xjtu.edu.cn](telnet://bbs.xjtu.edu.cn) :x: | [FireBird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [YTHT BBS](https://github.com/lytsing/ytht) <br> [bmybbs](https://github.com/bmybbs/bmybbs) | 網頁版：<br> https://bbs.xjtu.edu.cn/ <br> 2021-12-18: Telnet 與 SSH 連線限校內連入 https://bbs.xjtu.edu.cn/BMY/con?B=sysop&F=M.1617802725.A |
| :white_check_mark: | ~~浙江大學~~ 明月水軒 | [telnet://bbs.twomice.net](telnet://bbs.twomice.net) | [MapleBBS 3.10](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) <br> MoonBBS v0.0.2 | |
| :x: | 中國科大 瀚海星雲 | [telnet://ustcbbs.ustc.edu.cn](telnet://ustcbbs.ustc.edu.cn) <br> [telnet://bbs.ustc.edu.cn](telnet://bbs.ustc.edu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版：<https://bbs.ustc.edu.cn> <br> 2021-04-05: guest 不可登入 (無此 ID) <br> 2022-02-14: ustcbbs 域名解析失敗 <br> 2022-07-02: 連線逾時 |
| :x: | 中科院 (智慧電腦中心) 曙光站 | [telnet://bbs.ncic.ac.cn](telnet://bbs.ncic.ac.cn) | | (1994 春開站) <br> 2022-02-14: 域名解析失敗 |
| :x: | 中國礦業大學 放鶴亭 | [telnet://bbs.cumt.edu.cn](telnet://bbs.cumt.edu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |

* 北京大學 一塌糊涂 20040913被關 telnet://ytht.net
* 清華大學 水木清華 20050316封校 telnet://smth.org
* 南京大學 小百合 20050322分站 telnet://bbs.nju.edu.cn

## 其他海外華文 BBS 站台

| 可連 | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :x: | 美國 San Diego Home | [telnet://bbs.huaxiaspace.net](telnet://bbs.huaxiaspace.net) <br> [telnet://sd-bbs.net](telnet://sd-bbs.net) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2022-02-14: huaxiaspace.net domain suspended <br> 2022-07-02: 連線失敗 |
| :x: | 美國 天天壇 | [telnet://tttan.com](telnet://tttan.com) | [FireBird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [YTHT BBS](https://github.com/lytsing/ytht) | |

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
| 夢之大地 | `ssh bbs@ccns.ncku.edu.tw` `-p 22222` <br> `ssh bbsu@ccns.ncku.edu.tw` `-p 22222` <br> `ssh bbs@ccns.cc` `-p 22222` <br> `ssh bbsu@ccns.cc` `-p 22222` | *未*支援 UTF-8 <br> 校外需用 `-p 22222` 連 port 22222 | 
| 成功高中 沈澱日記 | `ssh bbsu@bbs.ckcsc.net -p 25` | |
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
    * Firefox 57 版開始無法使用，[作者表示還在修改中](https://www.ptt.cc/bbs/Browsers/M.1546565629.A.8F5.html)，完成時間未定。

其他用戶端瀏覽器相關資訊也可至 [批踢踢實業坊 AppsForBBS 板](https://www.ptt.cc/bbs/AppsForBBS/index.html) 查詢。

## BBS 系統譜系圖

- 目前 (2022-07-24) 收錄的 BBS 系統節點數：142
    - 試探性節點（需進一步考證）：8

### 譜系圖凡例

* 節點格式:
  ```
  (! 顯著開發事件; + 受參考系統)
  系統名稱與版本  開發年代  開發團隊隸屬機構  歷史代表站臺 (＊: 還在使用本系列系統)
      (備註)
  ```
  ```
  (! significant dev. events; + referenced softwares)
  Software name & ver.  Dev. period in years  Organization of dev. team  Official site (＊: still uses the software)
      (remarks)
  ```
  - 事件僅為舉例，會有不完整之處。
    - <code><sup>\[ref]</sup></code>: 可直接參考的資料來源
    - <code><sup>\[?]</sup></code>: 需補充資料來源
  - 受參考系統可能僅表示其功能受參考，不一定代表其原始碼受參考。
    - <code>&dagger;</code>: 暫無法考證的受參考系統
  - 可找到原始碼者，於系統名稱與版本處附上存取鏈結。
  - 軟體名與版本後的 <sup>\[?]</sup> 表示該節點為試探性，具體位置仍需進一步考證。 
  - 開發年代主要參考了版權宣告之日期以及程式修改紀錄。以取時間區間之聯集為原則。
    - `n.d.`: 年代暫無法考證
  - 歷史代表站臺以有官方性質且為非個人站臺者優先。
    - 最近祖節點相同的同一系統不同版本的歷史代表站臺相同時，只在其中最早版本上標出歷史代表站臺。
    - `N.A.`: 代表站臺暫無法考證
* 分支以每橫行最多一節點的（無環）樹狀圖表示。
  - 同系列的不同版本與其間的事件，若無分支，則併為一緊密縱列，順序由上而下；若有分支，則所有直接子分支縮進在同一縱列。
    - 緊密縱列內，事件內具有括起的版本或時間的話，則明確表示事件發生在上方版本之中。
  - 分支由上而下的排列順序：較早分支→較晚分支。
  - 分支早晚順序待考證或過於接近者，暫時以其在既有譜系圖中的位置為主，以隨意指定的順序為輔。
  - 由原開發團隊開發或採用的直接子分支，以分支圖上的雙橫線表示。
  - 有多個候選根節點時，以初分支時成分最大的或在譜系上最早出現的節點為實際根節點，其它候選節點則列於受參考系統。
* 圖中列出的系統，其**未受參考的葉節點**應符合以下所有條件：
  - 可確定其軟體名稱與譜系位置。
    - 需有伺服器主程式原始碼或參考文獻。
    - 僅知站名而不知軟體名者：
      - 有原始碼者，依英文簡寫站名作為軟體名列入。
      - 無原始碼者，不列入。
  - 具有終端機文字介面且具有閱讀與發表文章之功能。
    - 不可考察代表站臺，而僅能考察其伺服器主程式原始碼者，須已實作上述功能。
  - 針對中文使用者設計。
  - ※ 有多個子分支的節點與已受參考的葉節點不受上述條件限制。

### 譜系圖

<big><pre>
\* Pirate BBS 1.6  1990  Mississippi State University  The Mars Hotel
&nbsp; │   (SunOS-only)
&nbsp; ╞══ [Pirate BBS 1.9](https://github.com/bbsmirror/BBSmirror/blob/master/PirateBBS/pbbs-1.9.tar.Z)  1992
&nbsp; │  (! support Linux (1992-09))
&nbsp; └──(! support ESIX, user signature files, user plan, user query, post replies)
&nbsp;     Eagles BBS 1.1  1992  The University of Southern Mississippi  The Eagle's Nest＊
&nbsp;     │   ("Enhanced Pirates")
&nbsp;     ├── [NSYSU BBS](https://github.com/bbsmirror/BBSmirror/blob/master/FormosaBBS/old/bbs-2.2.1.tar.gz) 1.0&ndash;3.0.0  1992&ndash;1996  中山計中  美麗之島
&nbsp;     │  (! support Linux (2.2.1))
&nbsp;     │   ╞══(! no-TTY Telnet daemon (1996-10-03)<sup>\[[ref](https://github.com/PichuChen/formosa/blob/b08f10a59eb475129d761aca2554b0ab1999b5e8/src/main.c#L4)]</sup>, support C/S, renamed by dev. team)
&nbsp;     │   │   [Formosa BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FormosaBBS) [1.0.0-beta](https://github.com/bbsmirror/BBSmirror/blob/master/FormosaBBS/old/Formosa-1.0.0-beta.tar.gz)&ndash;[1.4.1](https://github.com/pigfoot/formosa/tree/c5efe3d3cb82e9c03cefeb6cd760bb9dfba8023e) ([archived](https://github.com/bbsmirror/BBSmirror/tree/master/FormosaBBS/old))  1996&ndash;2009  中山計中  美麗之島＊
&nbsp;     │   │  (! support FreeBSD (1.1.0), WEB BBS (1.1.0), i18n (1.1.1)))
&nbsp;     │   │  (+ PttBBS (pfterm, pmore, visio (= vtuikit)))
&nbsp;     │   │   [Formosa BBS CE](https://github.com/PichuChen/formosa)  2009&ndash;2012
&nbsp;     │   │  (! support IPv6)
&nbsp;     │   ├──(+ Pivot BBS 5.8<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/Y2ZUiYz_Bzs)]</sup>, Phoenix BBS)
&nbsp;     │   │   FCU CC BBS  n.d.  逢甲計中  蒼穹資訊網
&nbsp;     │   └──(+ Pivot BBS 5.8)
&nbsp;     │       Rose BBS  n.d.  (政大中文  玫瑰天空？)
&nbsp;     ╘══(! guest account)
&nbsp;        (+ Chatsubo BBS&dagger; (2nd beta site), Auggie BBS&dagger; (BBSNet & 4m), NSYSU BBS (non-ANSI porting))
&nbsp;         Eagles BBS 2.0  1992&ndash;1993
&nbsp;        (! support Linux (1993-10))
&nbsp;         ├──(! refactored; + Phoenix BBS)<sup>\[[ref](https://github.com/bbsmirror/bbshistory/blob/master/19950402T131858@install)]</sup>
&nbsp;         │  (+ Secret BBS)
&nbsp;         │   [Pivot BBS](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot) [5.08](https://github.com/bbsmirror/BBSmirror/tree/master/PivotBBS/source/pivot/v5.08) ([5.8](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot/v5.08/pivot-5.8.tar.gz)&ndash;[5.8+1](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot/v5.08/pivot-5.8p1.tar.gz))  1993&ndash;1996  中興計中  天樞資訊
&nbsp;         │   [Pivot BBS 5.9b4](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot/pivot5.9.tar.gz)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/Aef3-hrIjsk/m/HzcgSI9qU28J)]</sup>  1995
&nbsp;         │   ╞══(! [renamed by dev. team](https://github.com/bbsmirror/bbshistory/blob/master/19950817T163852@install) 1995-08-17)
&nbsp;         │   │   [Feeling BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Feeling-nsysu)  1995&ndash;1996  中正計中  寂寞芳心
&nbsp;         │   │   [Feeling-nsysu (Feeling BBS 1.0 TS)](https://github.com/bbsmirror/BBSmirror/blob/master/Feeling-nsysu/Feeling-1.0b1.tar.gz)  1997  中山鹿苑佛教 BBS 專站
&nbsp;         │   └── NCHU CC BBS 5.9  n.d.  中興計中
&nbsp;         ├──(! C/S-based)<sup>\[[ref](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/doc/bbs-inst.doc.gz)]</sup>
&nbsp;         │   NCTU CIS BBS  n.d.  交大資科
&nbsp;         ├──(! chroot-free, navigation keys, zh_tw UI)
&nbsp;         │  (! email posting, News, board gem, (0)Announce, Internet mail gateway)
&nbsp;         │   Phoenix BBS 3.0  1993, 1994  交大資工  鳳凰城資訊站
&nbsp;         │   │   ("Enhanced EaglesBBS 2.0")
&nbsp;         │   ╞══(! arrow-only browsing, ANSI-previewing editor, editor clipboard, run-time customizable menus)
&nbsp;         │   │   [Phoenix BBS 4.0](https://github.com/bbsmirror/BBSmirror/tree/master/PhoenixBBS)  1994&ndash;1995
&nbsp;         │   │   ├── [Napoleon BBS](https://github.com/bbsmirror/BBSmirror/tree/master/NapoleonBBS)  1994&ndash;1997  交大工管
&nbsp;         │   │   └── [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk) 2.00  1995  中正資工  四百年來第一站
&nbsp;         │   │       ╞══(+ FireBird BBS 2.4M)
&nbsp;         │   │       │   [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk) 2.50&ndash;[2.52](https://github.com/bbsmirror/BBSmirror/blob/master/FirebirdBBS_cuhk/FirebirdBBS2.51.tar.gz)  1996&ndash;1997
&nbsp;         │   │       ├──(+ MapleBBS 2.36, MapleBBS 3.0x, FireBird BBS 2.5x/2.xxM, SOB BBS, Palm BBS, Formosa BBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/F2bdEacZ9eM/m/dS8Zm7y-ldgJ)]</sup>
&nbsp;         │   │       │   EggRoll BBS  1996&ndash;2002  淡江大學  蛋捲廣場
&nbsp;         │   │       ╞══(! Big5 <-> GB2312)
&nbsp;         │   │       │   Hibiscus Realm BBS (FireBird M) 2.4M&ndash;[2.66M](https://github.com/bbsmirror/BBSmirror/blob/master/cuhk_ifcss/FirebirdBBS2.66M.Big5.tgz)  1997, 1998
&nbsp;         │   │       │       中央大學  大紅花的國度
&nbsp;         │   │       │  (! EaglesBBS dropped from `Version.info`)
&nbsp;         │   │       │  (+ FireBird BBS 2.50 (2.5M), IFI BBS (2.56M), FireBird BBS 2.52 (2.57M))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/U7jcX0hknh0)]</sup>
&nbsp;         │   │       │   ├── NativeBBS<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/t_X2olbFQi0/m/jonlHobQJ8cJ)]</sup>  1997  交大資科  夢幻國度
&nbsp;         │   │       │   ├──(+ SOB BBS)<sup>\[[ref](https://www.ptt.cc/man/SetupBBS/DAAD/M.924605418.A.html)]</sup>
&nbsp;         │   │       │   │   [MagicBBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/MagicBBS) 0.90  1997&ndash;1999  魔法王國
&nbsp;         │   │       │   │  (! Magic Web BBS (Web UI) (1998))
&nbsp;         │   │       │   │   ╞══ MagicBBS 1.x  1999&ndash;2000
&nbsp;         │   │       │   │   └── [PolyUBBS](https://github.com/bbsmirror/BBSmirror/tree/master/PolyU)  1999&ndash;2001  香港理工大學  紅磚學術資訊網
&nbsp;         │   │       │   │      (! bbs2www (Web UI) integrated (1999-11-21))
&nbsp;         │   │       │   ├── FireBird BBS 2.x-KCN  1998  清华大学  酒井 BBS
&nbsp;         │   │       │   │  (+ MapleBBS 3.00 1996 (mbbsd))
&nbsp;         │   │       │   │   [FireBird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/FireBird3.0Kbeta6.tar.gz)  1999
&nbsp;         │   │       │   │   ├──(! support Windows NT (via cygwin))
&nbsp;         │   │       │   │   │   [FireBird BBS NT](https://github.com/bbsmirror/BBSmirror/blob/master/FireBird/NT/fbnt_b3.zip)  2000&ndash;2001  N.A.
&nbsp;         │   │       │   │   └──(+ FireBird 2000, NJUWWWBBS 0.9, SMTH BBS)
&nbsp;         │   │       │   │       [YTHT BBS](https://github.com/lytsing/ytht)  1999&ndash;2004  北大物理  一塌糊涂
&nbsp;         │   │       │   │       ├── [bmybbs](https://github.com/bmybbs/bmybbs)  2003&ndash;2021  西安交通大学  兵马俑
&nbsp;         │   │       │   │       └──(! support Discuz! Web UI)
&nbsp;         │   │       │   │           [yilubbs](https://code.google.com/archive/p/ythtbbs/)  n.d.  一路 BBS
&nbsp;         │   │       │   ╘══(+ SEEDNet BBS, MapleBBS 3.00 1996 (mbbsd))
&nbsp;         │   │       │       [FireBird BBS 3.0](https://github.com/bbsmirror/BBSmirror/blob/master/FireBird/ftp.firebird.org.tw/3.0-RELEASE.tar.gz)  1999  N.A.
&nbsp;         │   │       │       ├── [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/FB2000deardragon.tar.gz)  1999, 2000  华南农业大学  快意灌水站
&nbsp;         │   │       │       │   ├── PKUBBS  1999&ndash;n.d.  北京大学  北大未名
&nbsp;         │   │       │       │   ├──(! new Web UI ([NJUWWWBBS](https://code.google.com/archive/p/lily-bbs/source/default/source)))
&nbsp;         │   │       │       │   │   Lily BBS  2000&ndash;2005  南京大学  小百合
&nbsp;         │   │       │       │   │   └── fdubbs  2002&ndash;2008  复旦大学  日月光华＊
&nbsp;         │   │       │       │   │       [fbbs](https://github.com/fbbs/fbbs)  2008&ndash;n.d.
&nbsp;         │   │       │       │   ├── [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs)  n.d.  上海交通大学  饮水思源＊
&nbsp;         │   │       │       │   │   ╘══ [nykzbbs](https://github.com/scaret/nykz)  n.d.  南洋客棧＊
&nbsp;         │   │       │       │   ├──(+ NJUWWWBBS 0.9)
&nbsp;         │   │       │       │   │   [inankai bbs](https://github.com/madoldman/inankai_bbs)  2010&ndash;2011  南开人社区
&nbsp;         │   │       │       │   └── [argo bbs](https://github.com/argomaintainer/bbssrc)  n.d.  中山大学  逸仙时空
&nbsp;         │   │       │       └── Freecity BBS  2002&ndash;n.d.  浙江大学  飘渺水云间
&nbsp;         │   │       ├── IFI BBS<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/_ZiCSCBdrME/m/0_m3vtsYfjYJ)]</sup>  1997  交大資科  插花島
&nbsp;         │   │       └──(! Big5 -> GB2312; + NJUWWWBBS 0.9)
&nbsp;         │   │           [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d)  2001&ndash;2005  清华大学  水木清华
&nbsp;         │   │           ├──(+ KBS)
&nbsp;         │   │           │   [zixia BBS](https://github.com/zixia/bbs)  2001&ndash;2021  清华大学  大话西游 紫霞BBS＊
&nbsp;         │   │           ╞══ [SMTH BBS 2.0](https://github.com/zhouqt/kbs/tree/70c3ec0b8564a65b9a72887d10fb829f8d560d30)  2005
&nbsp;         │   │           │  (! [renamed by dev. team](https://github.com/zhouqt/kbs/commit/4738b257ea407825320d56c9e25f74241a8958c2) 2005-07-18)
&nbsp;         │   │           │   [KBS](https://github.com/zhouqt/kbs)  2005&ndash;n.d.  水木社区＊
&nbsp;         │   │           ├── MITBBS  2005&ndash;n.d.  未名空间＊
&nbsp;         │   │           ├── [TongJi BBS](https://github.com/moqi88/tongjibbs)  2007  同济大学  同舟共济
&nbsp;         │   │           └── [LilacBBS](https://github.com/marvelliu/lilacsrc)  2011&ndash;n.d.  紫丁香社区＊
&nbsp;         │   └──(! support ANSI color, current article highlighting, thread-reading hotkeys, jump-to by number)
&nbsp;         │       SecretLover BBS (SecretBBS) 3.1  1994  大同資工  秘密情人
&nbsp;         │       ╞══(! active main menu banner, user list friend display, searching related posts, C/S chatroom)
&nbsp;         │       │   [Secret BBS 4.0B](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/S4.0B.tgz)  1994
&nbsp;         │       │  (+ Phoenix BBS 4.0, MapleBBS 2.36)<sup>\[[ref](https://github.com/bbsmirror/bbshistory/blob/master/A0OOM2IB@SysSuggest)]</sup>
&nbsp;         │       │   [Secret BBS 4.1B](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/S4.1B.tgz)  1995
&nbsp;         │       └──(! 4-space K&R -> 2-space Allman, copyright header removed)
&nbsp;         │          (+ Secret BBS 4.0B, Phoenix BBS 4.0, Pivot BBS 5.08, Palmarama BBS)
&nbsp;         │           [MapleBridge BBS (MapleBBS) 2.05 Beta](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/mapleBBS-2.0.5.tar.gz)  1994&ndash;1995  清大資科  楓橋驛站＊
&nbsp;         │          (! server sources put under maple/, thread-reading hotkeys \< & \>)
&nbsp;         │          (+ EaglesBBS 3.0, Phoenix BBS 4.0, Pivot BBS 5.9, NSYSU BBS, PowerBBS)<sup>\[[ref](https://github.com/bbsmirror/bbshistory/blob/master/A0OOHK9L@SysSuggest)]</sup>
&nbsp;         │           [MapleBBS 2.36](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/MapleBBS-2.36b.tar.gz)  1994&ndash;1995
&nbsp;         │           ╞══ [MapleBBS-current](https://github.com/bbsmirror/BBSmirror/blob/master/MapleBBS_cuhk/MapleBBS-current.tgz)  1996
&nbsp;         │           │   (! Tag list, gopher gem, n-selection vote, home/u/userid, BRD_NOZAP etc., RC_NONE etc.)
&nbsp;         │           │   MapleBBS [2.39a](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/MapleBBS-2.39a.tgz)&ndash;[2.39b](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/MapleBBS-2.39b.tgz)  1995&ndash;1996
&nbsp;         │           │   ├── [koalabear BBS](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_koalabear/SecretLover.tar.gz)  1995&ndash;1997  大同資工  秘密情人
&nbsp;         │           │   ╘══(! refactored (by opus), patched (by Thor, chuan, et al.))
&nbsp;         │           │      (+ SOB BBS)
&nbsp;         │           │      (! mbbsd (TTY-free) (1996-10-12); + Formosa BBS)
&nbsp;         │           │      (! (X)yz menu removed, GPL license file removed)
&nbsp;         │           │       MapleBBS [3.00b](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/Old/Alpha/MapleBBS-3.00b.tgz)&ndash;[3.00a](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/Old/Alpha/MapleBBS-3.00a.tgz)  1995&ndash;1998
&nbsp;         │           │      (! less refactored, ported (by lkchu), patched (by lkchu et al.))
&nbsp;         │           │      (! header files put under include/)
&nbsp;         │           │       DragonII BBS (MapleBBS [3.01](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/Old/Beta/MapleBBS-3.01.tgz)&ndash;[3.02](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/MapleBBS-3.02-RELEASE.tgz))  1998&ndash;1999
&nbsp;         │           │       │   交通大學  新冷馨居
&nbsp;         │           │       ├── Maple3 FreeBSD Ports<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/PShStVZ4w8s/m/vmKsw7OvIpEJ)]</sup> [3.01-fbsd](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/Old/Alpha/maple-301-fbsd.tgz)&ndash;[3.02-FreeBSD](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/Old/MapleBBS-3.02_FreeBSD-2.2.6.tgz)
&nbsp;         │           │       │       1998  台大電機  N.A.
&nbsp;         │           │       ├── [Maple 3 for OS2](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/branch/OS2/maple3.zip)  1998  淡江電機  N.A.
&nbsp;         │           │       ╞══(! shared libs (maple/))
&nbsp;         │           │       │   MapleBBS 3.05<sup>\[?]</sup>  n.d.
&nbsp;         │           │       │   ╞══(! shared libs put under maple/bso/)
&nbsp;         │           │       │   │   [MapleBBS 3.10](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/MapleBBS-3.10-20000606-SNAP.tgz)  1998&ndash;2000
&nbsp;         │           │       │   │   ╞══(! shared libs put under so/, (X)yz menu)
&nbsp;         │           │       │   │   │  (+ WindTopBBS, WD BBS (bhttpd; Web UI), PttBBS, FireBird BBS)<sup>\[[ref](https://github.com/xeonchen/maplebbs-itoc/blob/master/bbs/src/maple/CHANGE)]</sup>
&nbsp;         │           │       │   │   │  (+ MoonBBS)
&nbsp;         │           │       │   │   │   [MapleBBS 3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)  2000&ndash;2012  臺南一中  與南共舞*
&nbsp;         │           │       │   │   │   ├──(+ AT-BBS (project folder naming))
&nbsp;         │           │       │   │   │   │   [YA-AT-BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Athena/YA)  2002  松山高中  亞世界
&nbsp;         │           │       │   │   │   │   ╘══ [AT2-BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Athena/AT2)  2002&ndash;2003  建中資訊社  亞世界
&nbsp;         │           │       │   │   │   ╞══ [MapleBBS 3.20](https://github.com/maplebridge/bbs) (3.10-ATOM)  2007&ndash;2011  清大資科  楓橋驛站＊
&nbsp;         │           │       │   │   │   ├── [Auroral BBS](https://github.com/MapleCirc/Auroral)  2007&ndash;2014  台中一中  極光鯨藍＊
&nbsp;         │           │       │   │   │   ├── [MapleBBS-itoc-emu486](https://github.com/irvin/MapleBBS-itoc-emu486)  2008&ndash;2012  內灣新小月台＊
&nbsp;         │           │       │   │   │   ├──(+ PttBBS (pfterm, pmore))
&nbsp;         │           │       │   │   │   │   [XDBBS](https://github.com/hrs113355/Maple-XDBBS)  2008&ndash;n.d.  叉滴小站
&nbsp;         │           │       │   │   │   │   └── [windyvalleybbs](https://github.com/bbsmirror/windyvalleybbs)  2010&ndash;2019  成大電機  風之谷＊
&nbsp;         │           │       │   │   │   ├── [easttownbbs](https://github.com/guessi/easttownbbs)  2011&ndash;2021  東華大學  東方小城＊
&nbsp;         │           │       │   │   │   ├── [SonyBBS](https://github.com/lantw44/sonybbs)  2012&ndash;2019  台南一中  索尼小站＊
&nbsp;         │           │       │   │   │   └── [PartnerBBS](https://github.com/patw0929/MapleBBS-itoc)  n.d.  伙計小站
&nbsp;         │           │       │   │   ├──(! Big5 <-> GB2312; + FireBird BBS 3.0, MapleBBS 3.10-itoc)
&nbsp;         │           │       │   │   │   ├── MoonBBS  n.d.  浙江大学  明月水轩
&nbsp;         │           │       │   │   │   └──(+ yzuWEBBBS, NJUWWWBBS)
&nbsp;         │           │       │   │   │       [MapleBBS 3.10-WEB-hightman](https://github.com/bbsmirror/BBSmirror/blob/master/NotOpen/china_bbs/hightman/MapleBBS-3.10-WEB-20011031.tar.gz) ([Big5](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple3/branch/MapleBBS-3.10-WEB-20011103-BG5.tar.gz))  2001&ndash;n.d.  浙江大学  笑书亭
&nbsp;         │           │       │   │   ├──(! integrate SNOW (Web UI for MapleBBS 3.10))
&nbsp;         │           │       │   │   │   MapleBBS-3.10-snow<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/zLKz0M5JsKw/m/23ermCJbydAJ)]</sup>  2000  N.A.
&nbsp;         │           │       │   │   └──(! support Win32, Telnet screen resizing, board explanation window, support i18n)
&nbsp;         │           │       │   │       [My Elixir BBS (Melix BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/melix)  2001  N.A.
&nbsp;         │           │       │   └── [Train BBS Ver.19991230](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/TrainBBS-19991230.tgz)  1998&ndash;1999  元智資工  新火車站＊
&nbsp;         │           │       │      (+ WindTop BBS 2.X, MapleBBS 3.10)
&nbsp;         │           │       │       ╞══ Train BBS  n.d.
&nbsp;         │           │       │       ╘══ [WindTop BBS 3.02](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop)  1998&ndash;2004  元智大學  風之塔＊
&nbsp;         │           │       │          (! yzuWEBBBS (Web UI) (Ver.20010410); + MapleBBS 3.10-itoc)
&nbsp;         │           │       │           ╞══ WindTop BBS 3.10  2004&ndash;2009
&nbsp;         │           │       │           └── DreamLand BBS (DreamBBS) 3.02  2004&ndash;2009
&nbsp;         │           │       │                   成功大學  夢之大地＊
&nbsp;         │           │       │              (+ WindTop BBS 3.10, MapleBBS 3.10-itoc, windyvalleybbs (pmore))
&nbsp;         │           │       │               [DreamBBS 3.10 (DreamBBS 2010)](https://github.com/ccns/dreambbs2010)  2010&ndash;2017
&nbsp;         │           │       │              (! support IPv6, x86_64-compat, C++\-compat, 2- -> 4-space)
&nbsp;         │           │       │              (+ PttBBS (pfterm, BBS-Lua, wsproxy, bbs-sshd), windyvalleybbs (BBS-Ruby))
&nbsp;         │           │       │               [DreamBBS (git)](https://github.com/ccns/dreambbs)  2017&ndash;2022
&nbsp;         │           │       ├── [M3-WindTop (Tsaoyc ver.)](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/M3_WindsTop_Version_Buggy_Revision.tgz)  1998  元智大學  風之塔
&nbsp;         │           │       └── [Fall BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/branch/Fall)  n.d.  台灣科大  秋亭夜話
&nbsp;         │           ├──(+ MapleBBS 2.39)
&nbsp;         │           │   [Rouge BBS Ver.971011](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple2/branch/Rouge)  1995&ndash;1997  交通大學  冷馨居
&nbsp;         │           │  (+ MapleBBS 3.00 (mbbsd -> main, visio))
&nbsp;         │           │   [Rouge BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple2/branch/Rouge)  1998
&nbsp;         │           ├──(+ MapleBBS 2.39&ndash;3.00 1996 (gem .DIR))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/es_EPEQTvy4/m/SOhQyEtm5iwJ)]</sup>
&nbsp;         │           │   SunOfBeach BBS (SOB BBS) 0.22  1996  臺灣大學  陽光沙灘
&nbsp;         │           │   ╞══(! Copyleft ($))
&nbsp;         │           │   │   SOB on FreeBSD<sup>\[?]</sup>  n.d.
&nbsp;         │           │   │   ╞══(+ MapleBBS 3.00 1996 (mbbsd, visio))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bDlffmTSjT8/m/1iRg6wQzLMoJ)]</sup>
&nbsp;         │           │   │   │   ╞══ SOB mbbsd SunOS Plug&Play<sup>\[?]</sup>  1996  N.A.
&nbsp;         │           │   │   │   ╞══(! maple/buggy.c)
&nbsp;         │           │   │   │   │   SOB-fromzero (SOB 3.0)  n.d.  臺大電機  從零開始
&nbsp;         │           │   │   │   │   SOB domi  n.d.  糟了！誤上賊船
&nbsp;         │           │   │   │   │   └──(+ MapleBBS-itoc, ATS BBS)<sup>\[[ref](https://www.ptt.cc/bbs/SetupBBS/M.1058724092.A.html)]</sup>
&nbsp;         │           │   │   │   │       [SOB-PACK](https://github.com/bbsmirror/BBSmirror/blob/master/SOB/sob_rfc2047.tar.gz)  2003  N.A.
&nbsp;         │           │   │   │   ├── [Atlantis BBS (ATS BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bEHu_OfxYjw)]</sup>  1996&ndash;n.d.  亞特蘭提斯＊
&nbsp;         │           │   │   │   │   (+ MapleBBS 3.0x (DAO lib.), 3.10 (shared libs))
&nbsp;         │           │   │   │   │   (! emulated sub-sites (1.20))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bEHu_OfxYjw)]</sup>
&nbsp;         │           │   │   │   │   (+ WD BBS 2.9, PttBBS (games) (1.31))
&nbsp;         │           │   │   │   ├── NaiveAge BBS<sup>\[[ref](http://www.ncu.edu.tw/~w3meng/train90s/900820_ArGuo-BBS/NaiveAge-BBS_Install.doc)]</sup>  n.d.  中央機械  純真年代
&nbsp;         │           │   │   │   ├──(+ SOB-Leeym (bhttpf -> TKU-PRO BBSD))
&nbsp;         │           │   │   │   │   PeRsOnal BBS (PRO BBS)<sup>\[[ref](https://www.ptt.cc/man/SetupBBS/D389/M.913695634.A.html)]</sup>  1997&ndash;1998  淡江大學  蛋捲個人站
&nbsp;         │           │   │   │   └── [Purple Garden BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/fpgsrc.tgz) (FPG BBS)  1998&ndash;1999  臺灣法律  小魚的紫色花園
&nbsp;         │           │   │   └── [Ptt BBS 0.001](https://www.ptt.cc/man/SetupBBS/DC13/index.html)  1996&ndash;2000  臺灣大學  批踢踢實業坊＊
&nbsp;         │           │   │      (! 2-space Allman -> 4-space K\&R (partially); + SOB on FreeBSD (mbbsd))
&nbsp;         │           │   │       ╞══ Ptt BBS (for Linux) [0.9.2](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttsrc-0.9.2.tar.gz)&ndash;[1.0.0](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.0.tar.gz) ([archived](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt))  2000
&nbsp;         │           │   │       │   ├── [saloon BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/branch/saloon/saloonsrc.tgz)  2001  政治大學  煮酒論英雄
&nbsp;         │           │   │       │   ╞══ [Open Ptt](https://github.com/bbsmirror/openptt) (Ptt BBS [1.0.1](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.1.tar.gz)&ndash;[1.0.2](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.2.tar.gz))  2001
&nbsp;         │           │   │       │   ╘══(! x86_64-compat)
&nbsp;         │           │   │       │       [Ptt BBS Current](https://github.com/ptt/pttbbs)  2003&ndash;2014<sup>\[?]</sup>
&nbsp;         │           │   │       │       ├── [pttbbs-henry](https://github.com/alextwl/pttbbs-henry)  2006&ndash;2015  暨大資工  霞蔚山城
&nbsp;         │           │   │       │       ╘══ [Ptt BBS Current (git-only)](https://github.com/ptt/pttbbs)  2014&ndash;2022
&nbsp;         │           │   │       │           └── [BRsBBS](https://github.com/BunnyBBS/BRsBBS)  2018&ndash;2022  BunnyBBS
&nbsp;         │           │   │       └── PttFreeBSD<sup>\[?]</sup>  1998  風與塵埃的對話
&nbsp;         │           │   │          (+ MapleBBS 3.0x (DAO lib., HDR struct.), 3.10 (shared libs))
&nbsp;         │           │   │           Wind & Dust BBS (WD BBS) 1.34  1999  風與塵埃的對話＊
&nbsp;         │           │   │           ╞══(+ MapleBBS 2.39)
&nbsp;         │           │   │           │   [WD BBS 2.3](https://github.com/bbsmirror/BBSmirror/tree/master/WD/tarball)  1999
&nbsp;         │           │   │           │   ├── [WD-BBS 2.3-SSSH (PR BBS)](https://github.com/bbsmirror/BBSmirror/blob/master/WD/branches/PR_001206_SNAP.tgz)  2000  松山高中  松江水綠
&nbsp;         │           │   │           │   │   ╘══ Athenaeum BBS<sup>\[?]</sup>  1999<sup>\[?]</sup>&ndash;n.d.  建中資訊社  雅典娜
&nbsp;         │           │   │           │   │       ╞══ [Athena BBS (AT-BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/Athena/AT) v1.1.1  1999<sup>\[?]</sup>&ndash;2002
&nbsp;         │           │   │           │   │       │   │   建中資訊社  雅典娜
&nbsp;         │           │   │           │   │       │   ╞══ [AT-BBS-Pure](https://github.com/bbsmirror/BBSmirror/blob/master/Athena/AT/AT-BBS-Pure-0.1.1.tgz)  2002  建中資訊社  N.A.
&nbsp;         │           │   │           │   │       │   ╘══ AT-BBS  2002
&nbsp;         │           │   │           │   │       │      (! rename project folders (1.5.1))
&nbsp;         │           │   │           │   │       │      (+ MapleBBS 3.0x ("WD-visio") (1.5.1))
&nbsp;         │           │   │           │   │       ╞══ WD BBS 2.9<sup>\[?]</sup>  2000&ndash;2010<sup>\[?]</sup>
&nbsp;         │           │   │           │   │       │   ╞══(! renamed by original dev. team)
&nbsp;         │           │   │           │   │       │   │  (+ WD BBS, exbbs, MapleBBS 3.10-itoc, AT-BBS)<sup>\[[ref](https://github.com/hialan/hialanBBS/blob/master/src/doc/CHANGES)]</sup>
&nbsp;         │           │   │           │   │       │   │  (+ myth BBS&dagger;, PttBBS)<sup>\[[ref](https://www.ptt.cc/bbs/SetupBBS/M.1105470062.A.html)]</sup>
&nbsp;         │           │   │           │   │       │   │   [WD_hialan BBS (AT3-BBS) (AT-BBS v2)](https://github.com/hialan/hialanBBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/TPeEm84denQ)]</sup> ([archived](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/hialan))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/iFMcpSVSOZM)]</sup>  2002&ndash;2017
&nbsp;         │           │   │           │   │       │   │       建中資訊社  威尼斯咖啡館
&nbsp;         │           │   │           │   │       │   └── [CCUMATH-BBS](https://github.com/jcppkkk/MapleBBS-3.00)  n.d.&ndash;2013  中正大學  無數不學
&nbsp;         │           │   │           │   │       ╘══(! refactored (C++), support Windows NT)
&nbsp;         │           │   │           │   │           [EdenBBS v0.5](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/Eden)  2001  建中資訊社  兩光的兩光小站
&nbsp;         │           │   │           │   ├── [exbbs](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/exbbs)  2001  宜蘭技院  紅樓頂尖 BBS
&nbsp;         │           │   │           │   ╘══ [Pure WD BBS (WD-P BBS)](https://github.com/bbsmirror/BBSmirror/blob/master/WD/tarball/wd_pure_snap_linux.tgz)  2002  風與塵埃的對話-空無一物版
&nbsp;         │           │   │           └──(+ PttBBS, FPG BBS)<sup>\[[ref](https://www.ptt.cc/man/SetupBBS/DAAD/M.939173101.A.html)]</sup>
&nbsp;         │           │   │              (+ MapleBBS 3.0x ("WD-visio" &mdash; io+term+screen-stuff) (20000619))
&nbsp;         │           │   │               [StarRiver BBS (Star BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/StarVersion)  2000&ndash;2002  輔仁大學  星河夜話
&nbsp;         │           │   ├──(! bhttpd (Web UI))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/iRD0Cor13YM/m/dKh4qol8LkcJ)]</sup>
&nbsp;         │           │   │   SOB-Leeym  n.d.  成大土木  大地雕塑家
&nbsp;         │           │   ├── Forest BBS<sup>\[?]</sup>  n.d.  中原資管  森林站<sup>\[?]</sup>
&nbsp;         │           │   ├──(+ FireBird BBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bp0ZpSPflHM)]</sup>
&nbsp;         │           │   │   ForestV BBS  n.d.  政治大學  月光森林
&nbsp;         │           │   ├── Oldest future Object BBS (OfO)  1997&ndash;n.d.  臺灣大學  未來最舊小棧
&nbsp;         │           │   └── Wind's Top BBS (WindTop BBS) (wind BBS) [2.2](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/Wind/wind1101.tgz)&ndash;[2.4](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-19991229-V2.4.tgz)  1998&ndash;1999
&nbsp;         │           │           元智大學  風之塔＊
&nbsp;         │           ├── [EE CS BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/eecs.tgz)  1996  清華大學  資電整合
&nbsp;         │           ├── [Bobule BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple2/branch/rpg)<sup>\[?]</sup>  1996  交通大學  包包的 CPU
&nbsp;         │           │   ╘══ [RPG BBS](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple2/branch/rpg)  1996&ndash;1997  交通大學  創世紀
&nbsp;         │           └──(! Big5 <-> GB2312; + FireBird BBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/GD6MeEiGBXI/m/VG4rz3UC6igJ)]</sup>
&nbsp;         │               [blast BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/blast.tgz)  1997  沙灘驛站
&nbsp;         ├── NCU BBS  n.d.  中央大學  龍貓資訊天地
&nbsp;         ╘══(! refactored, run-time customizable menus, chroot-free)
&nbsp;             Eagles BBS [3.0](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/ebbs-3.0.tgz)  1994, 1995
&nbsp;             ╞══ Eagles BBS [3.1](https://wq5l.net/ebbs/) ([archived](https://github.com/bbsmirror/BBSmirror/blob/master/EaglesBBS/ebbs-3.1.1.tar.gz))  1995&ndash;2020
&nbsp;             └──(+ Phoenix BBS 4.0)
&nbsp;                 [Palmarama BBS (Palm BBS) 2.01](https://github.com/bbsmirror/BBSmirror/blob/master/cuhk_ifcss/palmbbs-2.01.tar.gz)  1995  臺大計中  椰林風情
\*(! C/S-based)
&nbsp; [Power BBS](https://github.com/bbsmirror/BBSmirror/tree/master/PowerBBS)  1994&ndash;1997  中華資工  方城資訊站
\*(+ IFI BBS)<sup>\[?]</sup>
&nbsp; [ColaBBS](https://github.com/bbsmirror/BBSmirror/tree/master/ColaBBS)  1997&ndash;2000  交大資科  插花島
&nbsp;(! re-licensed with GPL<sup>\[?]</sup>)
&nbsp; [OpenColaBBS](https://github.com/bbsmirror/ColaBBS)  2007
\*(+ EggRoll BBS, SOB BBS, PttBBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/FcDhGB-vwsA/m/Wkli0xOovBwJ)]</sup>
&nbsp; [天火 BBS](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) ([archived](https://github.com/bbsmirror/BBSmirror/tree/master/rexchen))  2002  淡江電機  蛋捲廣場＊
\*(+ FireBird BBS)
&nbsp; [NetBBS](https://sourceforge.net/projects/netbbs/)  2004  同济网 Tongji Net<sup>\[?]</sup>
</pre></big>

### 譜系圖近期更動

- 初步增加事件節點。「請支援考察。」
    - 尚待確定適當的詳細程度。
    - 暫時未將事件節點的參考鏈結放入參考資料。
- 將連續未分支同系節點併為一縱列。
- 顯著調整部份譜系的呈現。
    - WindTop BBS 3 系列，根節點從 WindTop BBS 2.x 改至新節點 MapleBBS 3.05。
    - Pivot/Feeling BBS 系列，改名前最後共同祖節點從 5.8 改至 5.9b4。
    - WD BBS 系列，補充中間節點，並將 2.9 版分支之根節點改至新節點 Athenaeum BBS。
- 試探性地加入新分支節點。需進一步驗證。
    - Train BBS，設為 Train BBS 後繼版本與 WindTop BBS 3 系列之祖節點。內部參考關係待釐清。
        - 與 M3-WindTop 間無直接分支關係。
    - PttFreeBSD，設為 WD BBS 系列之祖節點。有無其它分支仍待考察。
    - SOB on FreeBSD，暫設為較後期的 SOB BBS 的祖節點。是否獨立存在仍待驗證。或可改以 SOB BBS 之某日期版本表示。
    - Athenaeum BBS，暫設為建中資訊社之 WD BBS 衍生系統的祖節點。子節點仍待驗證。或可改以 Athena BBS 之某具體前期版本表示。
        - AT2-BBS 非其子分支。
    - MapleBBS 3.05，設為 WindTop BBS 3 系列與 MapleBBS 3.10 之最後共同祖節點，視為 MapleBBS 3.10 之早期版本。見於早期 WindTop BBS 3 原始碼 `include/config.h`。
- 將機構名與站名改放到開發年代後。
- 初步建立是否列入某軟體的準則。

### 譜系圖研究方法
* 以現有譜系圖為藍本，先統整一致之處。
* 先行考察不一致的部份的站臺與軟體並修正譜系圖。
* 參考軟體原始碼的版本資訊（注意有時可能有編輯錯誤，需交叉參考相關軟體）：
    - 常位於 `install.files/`, `config/`, `bbshome/`, `example/`, `sample/bbs/`, 或 `etc/`
    - 常名為 `Version.info`, `Version`, 或 `info`
* 整理同一系列之祖先軟體和／或其衍生軟體之具特異性的共同特徵，驗證現有譜系圖。
* 未有版本資訊的軟體，依其軟體特徵與修改時間，佐以過去文獻，判斷其譜系位置。
* 不一致時，參考資料來源的優先順序：原始碼 > 代表站臺之軟體功能 > 主要開發團隊與他人引用，開發時期 > 開發團隊回憶與他人引用 > 開發團隊，他人轉述 > 他人，開發時期 > 他人回憶
* 代表站臺的確定，以文獻資料為主，以原始碼中的預設設定檔為輔。

### 譜系圖參考資料
* 過去的 TANet BBS 發展譜系圖及相關說明
    - Tseng, K.-F. [kftseng]. *[轉貼] 電子布告欄簡介*. 中山大學 West BBS-西子灣站. http://bbs3.nsysu.edu.tw/txtVersion/treasure/ee90-2/M.889205710.A/M.889268386.A.html
    - geniuswei. (2007, May 8). *Re: [請益] 關於BBS的定義*. 批踢踢實業坊. https://www.ptt.cc/bbs/ask/M.1178594446.A.727.html
* Maple 系列發展譜系圖與考據
    - [Ho, L.-S. \[holishing\]](https://github.com/holishing). (2018, January 6). *[分享] 目前各版本 BBS server 安裝資訊*. 批踢踢實業坊. https://www.ptt.cc/bbs/AppsForBBS/M.1515230521.A.104.html
    - Dopin. (2002, July 18). *Maple Family (by Dopin) Ver. 5*. 亞特蘭提斯站 ([telnet://125.227.52.214](telnet://125.227.52.214)). ATSVersion 板 置底
    * MapleBBS 3.0x 考據
        - Wu, Q.-H. \[woju] (1997, December 6). *NTHU-CS Maple 3.0 BBS ports 計畫展開！*. Google Groups. Retrieved July 7, 2022, from https://groups.google.com/g/tw.bbs.admin.installbbs/c/YvEuaTaCuhU/m/wYJkGqja460J
        - Domi, Lin, Wu, Q.-H. \[woju] (1997, December 7). *Re: NTHU-CS Maple 3.0 BBS ports 計畫展開！*. Google Groups. Retrieved July 7, 2022, from https://groups.google.com/g/tw.bbs.admin.installbbs/c/PShStVZ4w8s/m/vmKsw7OvIpEJ
        - Wu, Q.-H. \[woju] (1998, January 14). *Re: 想請 vanilla 幫忙做 ports*. 水雲間資訊交流站--WebBBS介面. Retrieved July 7, 2022, from <https://web.archive.org/web/20050905233651/http://bbs.unix-like.org:80/show.php?brdname=FB_maple&filename=/M.1009379801.A&filename_p=&filename_n=>
    * AT BBS 系列考據
        - LinuxBoy  (2003, July 6). *[公告]AT-News newsgroup*. Google Groups. Retrieved July 11, 2022, from https://groups.google.com/g/tw.bbs.admin.installbbs/c/9h1D0ZSv_SU/m/nmDl0rHMebMJ
* FireBird 系列發展沿革與譜系圖
    - Huang, L.-T. (2017, Sep). BBS 之前世今生. *YTHT BBS 开发指南*. https://lytsing.gitbooks.io/ytht-bbs/content/bbs-history.html
    * luckwithme, [mo7](https://github.com/moqi88), & kxn (2007). *Re: 有没有各个bbs版本的关系图*. In SpiritRain (Ed.), BBSView 版 (精华区). 水木社区. https://www.mysmth.net/bbsanc.php?p=1156-1-2
    * Li, X.-R. (1999, December 6). 蛋 捲廣 場 秘 史-- 第 419 期 專題報導. *淡江時報 Tamkang Times*. https://tkutimes.tku.edu.tw/dtl.aspx?no=7364
* Eagles BBS 的相關資料
    * 官方站臺見下
    * 經 Eagles BBS 原作者之一 Ray Rocker 認可的官方網站
        - https://enbbs.org/
        - https://enbbs.org/history.php 含有以下網路文章的鏈結
    * 介紹到了 Pirate BBS，並提到了 Eagles BBS 與 Pivot BBS 的文章
        * Scott, J. (2008, November 4). *When the BBS Broke Free*. ASCII by Jason Scott. http://ascii.textfiles.com/archives/1474
    * 由 Eagles BBS 原作者之一 Ray Rocker 撰寫的介紹了 Eagles BBS 的起源的文章
        - Rocker, R. (1994, August 1). *Eagles BBS*. Linux Journal. https://www.linuxjournal.com/article/2789
    * Eagles BBS 2.00 的簡介說明文件（提到了 NSYSU BBS）
        - Rocker, R. (1993, May 1). *README.first*. https://github.com/bbsmirror/bbshistory/blob/48f8b22c4234296bebc86a749f946fc091ab41c1/EaglesBBS-2.00-README.first
        - [Secret BBS 4.0](https://github.com/bbsmirror/BBSmirror/blob/master/SecretBBS/SecretLover_4.0b/S4.0B.tgz) (`S4.0B/doc/README.first.obsoleted`)
        - [Pivot BBS 5.04-pl14](https://github.com/bbsmirror/BBSmirror/blob/master/PivotBBS/source/pivot/v5.04/pivot.5_04.pl14.tar.gz) (`pivot/INFO/README.first`)
* Formosa BBS 1.1.1 的安裝說明（提到了 Formosa BBS 的發展簡史）
    - Liang, M.-J. \[lmj\] & Huang, L.-D. \[lasehu\]. (1998, May 22). *中山 Formosa BBS Server 系統安裝手冊  for v1.1.1*
      https://github.com/bbsmirror/BBSmirror/blob/master/FormosaBBS/old/FormosaBBS-1.1.1.tar.gz (`./FormosaBBS-1.1.1/INSTALL`)
* PCMAN 瀏覽器內建的站臺列表
  https://github.com/bbslist/bbslist.github.io/blob/master/pcman-windows/BBSList
* 過去的文件與文字紀錄（更多參考資料見此）
    * 批踢踢實業坊 SetupBBS 板精華區：
      https://www.ptt.cc/man/SetupBBS/index.html
    * 楓橋驛站 SysSuggest 板及其精華區：
      [telnet://bbs.cs.nthu.edu.tw](telnet://bbs.cs.nthu.edu.tw)
    * 部份封存版：
      https://github.com/bbsmirror/bbshistory
    * tw.bbs.admin.installbbs 新聞群組（需使用搜尋功能）：
      https://groups.google.com/g/tw.bbs.admin.installbbs
    * 水雲間資訊交流站--WebBBS介面（以關鍵字 `FB_maple` 過濾）：
      <https://web.archive.org/web/*/http://bbs.unix-like.org/show.php*>
    * [php.twbbs.org](#) (豬頭紀公園) 的 plan 看板精華區備份
      https://github.com/bbsmirror/BBSmirror/tree/master/php_gem
* 現存站臺上的版權宣告及相關公告
* 程式原始碼中的相關文件（見譜系圖中各鏈結）

| 可連 <br> (不納入統計) | 站名 | 位址 | BBS 版本 | 備註 |
| - | - | - | - | - |
| :white_check_mark: | Eagle's Nest | `ssh bbs@bbs.wq5l.net` :lock: <br> `ssh bbs@nest.wq5l.net` :lock: | [Eagles BBS 3.1.4-rc2](https://wq5l.net/ebbs/) | (1992-04-14 開站) |
