# 已知現存中文 BBS 站台
### Known Existing Chinese Language BBSes

###### tags: `telnet` `ssh` `BBS` `電子布告欄` `TANet BBSes` `華文 BBSes` `BBS 分支圖` `BBS 系統沿革`

## 本文版本
### Versions of this Article

* 穩定版本 stable version: [on GitHub](https://github.com/bbslist/bbslist.github.io)
* 共筆版本 co-writing version: [on HackMD](https://hackmd.io/r1pdt-59b)

共筆版本可自由編輯；穩定版本則是共筆版本在被修改且經過不定的一段時間後，若經確認沒太大問題的話，才會 push 上去更新。\
The co-writing version can be edited freely; the stable version is updated when a certain amount of time has been passed since the last edit of the co-writing version and no significant issues are found.

若覺得穩定版本太久沒更新可去 GitHub 提 issue：\
You can issue an update request at GitHub if you feel that the stable version has not been updated for a while:\
<https://github.com/bbslist/bbslist.github.io/issues>

若您願意協助確認資訊使其及時，或改善查驗流程使其順暢，請不吝編輯或留言以改進此文。\
If you are willing to help to keep the information up-to-date or make the checking process smoother, please do not hesitate to edit or leave comments to improve this article.

## 可連線數量
### Number of Connectable Sites

目前統計有 **52**/126 個 (2023-04-09)；[查看自動加總器](#bbstotal)\
There are **52**/126 known connectable sites (2023-01-16); [see the auto-sum-counter](#bbstotal)

詳情請見下文表格中的 `可連` 欄位：:white_check_mark: 可成功連線／:x: 連線失敗／:x:<sup>:warning:</sup> 連線失敗但 ping 有回應／:x:<sup>:question:</sup> 網域無法解析或已被它站註冊\
For details, see the `Con.` field of the tables below: :white_check_mark: Connectable / :x: Not connectable / :x:<sup>:warning:</sup> Not connectable but responsive to ping / :x:<sup>:question:</sup> The URL domain cannot be resolved or is registered by others.

以測試時從外網可使用任一直接網路連線途徑（含網頁版）連入為判斷原則。可能適逢站臺暫時離線維護，如有不便，尚祈見諒。\
*Connectable* is judged by whether there are available methods (including using the website) to access the site from the Internet during the checking process. It is possible that the checking process is performed during temporary offline maintenance of the site. We apologize for any inconvenience this may cause.

列表以文字終端機介面為基礎並提供 telnet、ssh 等網路連線途徑的站台為主；只有 Web 論壇形式的站台暫不列入。\
Only sites providing text-terminal&ndash;based interface and connection methods such as Telnet & SSH are listed. Sites providing only web forum interface are not listed.

本文列出的從未被過去的站臺列表收錄的私人小型站臺，以站長知情且同意補充者為主。\
As for personal sites never listed in previous BBS site lists, they can be listed here as long as the SYSOP(s) have acknowledged and agreed.

## 大學相關站台
### University Sites and Derivation Sites

<div class="bbslist">

| 可連&nbsp;&nbsp; <br> Con. | 站名 <br> Site Name | 位址 <br> Address | BBS 版本 <br> BBS Server Version | 備註 <br> Notes |
| - | - | - | - | - |
| :x:<sup>:question:</sup> | 銘傳 築夢別境 <br> *Zhu Meng Bie Jing*, MCU | [telnet://bbs.mcu.edu.tw](telnet://bbs.mcu.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2022-02-06: 域名解析失敗 Domain resolution failed |
| :x:<sup>:question:</sup> | 逢甲紡織 七月七日晴 <br> *77 BBS*, FCM, FCU | [telnet://77bbs.com](telnet://77bbs.com) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2022-02-07: 重新導向至環球科技大學網頁 Redirected to a webpage of TransWorld University |
| :x: | 淡江資管 渡船頭之戀 <br> *Ferry Pier Love*<sup>\[?]</sup>, IM, TKU | [telnet://bbs.im.tku.edu.tw](telnet://bbs.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020-06-24 測試: down |
| :x:<sup>:warning:</sup> | 淡江 蛋捲新系統測試站 <br> *New Loyal*<sup>\[?]</sup>, EE, TKU | [telnet://loyal.ee.tku.edu.tw](telnet://loyal.ee.tku.edu.tw) | [天火系統](http://tube.ee.tku.edu.tw/~rexchen/bbs/index.html) | 2019-10-30: 連線失敗 Connection failed <br> 2022-02-14: ping 有回應 Responsive to ping |
| :x: | 淡江資管 星星之戀 <br> *Star Love*, IM, TKU | [telnet://starlove.im.tku.edu.tw](telnet://starlove.im.tku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc)| |
| :x:<sup>:question:</sup> | 東海 資訊傳奇 <br> *Legend of IT*, CSIE, THU | [telnet://bbs.csie.thu.edu.tw](telnet://bbs.csie.thu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-07: 域名解析失敗 Domain resolution failed |
| :x: | 東海數學 陽光草坪 <br> *Sun of Lawn*<sup>\[?]</sup>, Math, THU | [telnet://122.117.69.100](telnet://122.117.69.100) | [PttBBS](https://github.com/ptt/pttbbs) <br/> (不明舊版本 unknown early ver.) | 2022-02-14: `Destination host unreachable.` |
| :white_check_mark: | 東華 東方小城 <br> *East Town*, NDHU | [telnet://bbs.ndhu.edu.tw](telnet://bbs.ndhu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [easttownbbs](https://github.com/guessi/easttownbbs) | 網頁版 Web UI: <http://bbs.ndhu.edu.tw> :unlock: <br> 2021-01-10: 已正常 Resumed <br> 2021-08-18: 未加密網頁版 up Non-encrypted website: up |
| :x: | 東吳機研站 <br> *SCU Motor*, SCU | [telnet://scumotor.com.tw](telnet://scumotor.com.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<http://scumotor.com.tw:8080> :unlock: <br> 2023-03-18: Down |
| :x: | 台北大學 北極星II <br> *Polaris II*, NTPU | [telnet://bbs.ntpu.edu.tw](telnet://bbs.ntpu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-12-01: down |
| :x: | 台北市立大學 七號出口 <br> *Seventh Exit*<sup>\[?]</sup>, UT | [telnet://bbs.utaipei.edu.tw](telnet://bbs.utaipei.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本 unknown early ver.: ≤ 2008-10-12) | 2022-11-14: 連線失敗 Connection failed |
| :x: | 台北醫學大學 杏林綠意 <br> *Greenish Forest of Apricot*<sup>\[?]</sup>, TMU | [telnet://bbs.tmu.edu.tw](telnet://bbs.tmu.edu.tw) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 另外有很多班板在未來最舊小站 Many school-class&ndash;themed board are created at the *Oldest future Object* site instead |
| :x: | 台中教育大學 柳岸咖啡館 <br> *Willow Bank Cafe*<sup>\[?]</sup>, NTCU | [telnet://bbs.ntcu.edu.tw](telnet://bbs.ntcu.edu.tw) | Maple-itoc <br> (未納入版本管理的分支) <br> (A fork out of version control) | 硬碟毀損，域名屬於學校，目前無復站希望，詳見 [#4](https://github.com/bbslist/bbslist.github.io/issues/4) <br> No hopes in resume due to hard disk failure and the domain owned by the school. See [#4](https://github.com/bbslist/bbslist.github.io/issues/4) |
| :x: | 台大 不良牛 <br> *Bad Cow*, NTU | [telnet://bbs.badcow.com.tw](telnet://bbs.badcow.com.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) <br> [SOB-fromzero](https://github.com/bbsmirror/BBSmirror/blob/master/SOB/sob_rfc2047.tar.gz) | 因仍有 DNS 反查, 部份BBS瀏覽軟體不支援 <br> Incompatible with some BBS browsers due to reverse DNS <br> 2021-08-11: 連線失敗 Connection failed |
| :white_check_mark: | ~~台大~~ 批踢踢實業坊 <br> *Ptt*, ~~NTU~~ | ~~telnet://ptt.cc <br> [ip](telnet://140.112.172.11) / [ip<sub>1</sub>](telnet://140.112.172.1) / [ip<sub>2</sub>](telnet://140.112.172.2) / [ip<sub>3</sub>](telnet://140.112.172.3) / [ip<sub>4</sub>](telnet://140.112.172.4) / [ip<sub>5</sub>](telnet://140.112.172.5)~~ <br> `ssh bbs@ptt.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt.cc> (wss) [:lock:](#Websocket-連線) | [PttBBS git r5032+](https://github.com/ptt/pttbbs) | 網頁版 Web UI: <https://www.ptt.cc/bbs> <br> guest無法登入 guest cannot log in <br> 2022-04-15 停用 Telnet 連線 Telnet connection is no longer provided |
| :white_check_mark: | 批踢踢兔 <br> *Ptt 2* | ~~telnet://ptt2.cc~~ <br> `ssh bbs@ptt2.cc` [:lock:](#SSH-連線) <br> `ssh bbsu@ptt2.cc` (UTF-8) [:lock:](#SSH-連線) <br> [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) [:lock:](#Websocket-連線) <br> <https://term.ptt2.cc> (wss) [:lock:](#Websocket-連線) | [PttBBS git r5032+](https://github.com/ptt/pttbbs) | guest無法登入 guest cannot log in <br> 2022-04-15 停用 Telnet 連線 Telnet connection is no longer provided |
| :x: | 批踢踢參 <br> *Ptt 3* | [telnet://ptt3.cc](telnet://ptt3.cc) <br> `ssh bbs@ptt3.cc` [:lock:](#SSH-連線) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r4423 | 2019-10-30: 連線失敗 Connection failed |
| :white_check_mark: | 台大大氣 卡莎米亞 <br> *Casamia*, As, NTU | [telnet://bbs.as.ntu.edu.tw](telnet://bbs.as.ntu.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本 unknown early ver. ≤ 2013-12-09) | |
| :x: | 台大資管 鳴蟬小站 (墮落天堂) <br> *Cicadae* (*Tolo Heaven*<sup>\[?]</sup>), IM, NTU | [telnet://bbs.im.ntu.edu.tw](telnet://bbs.im.ntu.edu.tw) <br> [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) [:lock:](#Websocket-連線) :x: <br> <https://tolo.ntu.im> (wss) [:unlock:](#Websocket-連線) :x: | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-08-11: PttChrome 網頁版誤連到批踢踢 The PttChrome webpage erroneously connects to Ptt <br> 2021-12-01: WSS 連線失敗；加密憑證網域設定錯誤 <br> WSS connection failed due to misconfiguration of domain of encryption certification <br> 2023-04-09: 連線逾時 Connection timed out |
| :x: | 台大物理 冷月流蘇 <br> *Leng Yue Liu Su*<sup>\[?]</sup>, Phys, NTU | [telnet://bbs.phys.ntu.edu.tw](telnet://bbs.phys.ntu.edu.tw) <br> [telnet://bbs.phys.tw](telnet://bbs.phys.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | |
| :white_check_mark: | 台大 未來最舊小棧 <br> *Oldest future Object*, NTU | [telnet://ofo.tw](telnet://ofo.tw) <br> `ssh bbs@ofo.tw` [:lock:](#SSH-連線) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) <br> Oldest future Object | 不開放guest <br> Not open to guest <br> 2021-04-28: Up |
| :x: | 高雄 原野星辰 <br> *Wilderness & Stars*<sup>\[?]</sup>, NUK | [telnet://bbs.nuk.edu.tw](telnet://bbs.nuk.edu.tw) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :x: | 海洋大學 <br> *NTOU BBS* | [telnet://bbs.ntou.edu.tw](telnet://bbs.ntou.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x:<sup>:question:</sup> | 海洋電機 忘晴海 <br> *Dismissed Calm Ocean*<sup>\[?]</sup>, EE, NTOU | [telnet://bbs.ee.ntou.edu.tw](telnet://bbs.ee.ntou.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本 unknown early ver.) | 2022-02-14: 域名解析失敗 Domain resolution failed |
| :x: | 暨大電機 漂浮電子 <br> *Floating Digital*<sup>\[?]</sup>, EE, NCNU | [telnet://bbs.ee.ncnu.edu.tw](telnet://bbs.ee.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 暨大土木 土木小站 <br> *Civil Engineering BBS*<sup>\[?]</sup>, CE, NCNU | [telnet://bbs.ce.ncnu.edu.tw](telnet://bbs.ce.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法使用guest，以及看板列表毀損 <br> guest is unavailable; board list is corrupted |
| :x: | 暨南 水沙連站 <br> *Shuishalian*<sup>\[?]</sup>, NCNU | [telnet://bbs.ncnu.edu.tw](telnet://bbs.ncnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-07-24: 連線逾時 Connection timed out |
| :white_check_mark: | 嘉義 應物轉資巴 <br> *Applied Physics Zhuan Zi 8*<sup>\[?]</sup>, AP, NCYU | [telnet://aptg8.sytes.net](telnet://aptg8.sytes.net) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> 20080508-PACK | 2022-11-17: 進入看板列表會斷線，需改用 <kbd>Ctrl</kbd>-<kbd>S</kbd> 瀏覽看板 <br> Disconnects when enter the board list. <kbd>Ctrl</kbd>-<kbd>S</kbd> is needed for browsing boards |
| :x:<sup>:question:</sup> | 交通 機械工廠 <br> *Factory BBS*, ME, NCTU |  [telnet://bbs.me.nctu.edu.tw](telnet://bbs.me.nctu.edu.tw) | [Maple3.10-itoc](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2020-12-17: 連線失敗 Connection failed <br> 2022-02-14: 域名解析失敗 Domain resolution failed |
| :white_check_mark: | ~~交大~~ 淒美燈塔 <br> *The Pharos BBS*, ~~NCTU~~ | [telnet://bbs.pharos.rocks](telnet://bbs.pharos.rocks) <br> [wss://bbs.pharos.rocks](wss://bbs.pharos.rocks) [:lock:](#Websocket-連線) <br> <https://bbs.pharos.rocks> (wss) [:lock:](#Websocket-連線) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2019-10-31: Websocket up |
| :x:<sup>:question:</sup> | 交通 次世代ＢＳ２ <br> *BS2*, NCTU | [telnet://bs2.to](telnet://bs2.to) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [已關站 closed](https://www.ptt.cc/bbs/NCTU_TALK/M.1461738017.A.8BA.html) |
| :white_check_mark: | 次世代ＢＳ２．佚 <br> *BS2 Lost*<sup>\[?]</sup> | [telnet://bs2.io](telnet://bs2.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | [另外發起](https://www.ptt.cc/bbs/NCTU_TALK/M.1469423697.A.2AE.html)之相關延續站台 <br> [An independent derivation site](https://www.ptt.cc/bbs/NCTU_TALK/M.1469423697.A.2AE.html) |
| :white_check_mark: | 靜宜 水世界 <br> *Water World BBS*, PU | [telnet://bbs.cs.pu.edu.tw:3001](telnet://bbs.cs.pu.edu.tw:3001) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> [3.02 Rev. 20001103](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-3.02-20001103-SNAP.tgz) | 2016因校計中資安政策封鎖Port 23，請改用Port 3001 or 3456連線 <br> Port 23 has been blocked due to the secure policy from the computer center of the school; please connect using port 3001/3456 instead <br> 2021-08-12: Up |
| :white_check_mark: | 清華 楓橋驛站 <br> *Maple Bridge*, NTHU | [telnet://bbs.cs.nthu.edu.tw](telnet://bbs.cs.nthu.edu.tw) / [:443](telnet://bbs.cs.nthu.edu.tw:443) <br> [telnet://imaple.tw](telnet://imaple.tw) :x: / [:443](telnet://imaple.tw:443) :x: <br> [telnet://140.114.87.5](telnet://140.114.87.5) / [:443](telnet://140.114.87.5:443) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS 3.20 (3.10-ATOM)](https://github.com/maplebridge/bbs) r402 | (2007年, 系統從自己開發的系統, 轉換成 itoc 大 fork 出來的版本 繼續維護) <br> In 2007, the software switched from the independently developed one to the itoc version and is independently maintained since then. <br> 2022-07-02: imaple.tw 連線失敗 Connection to imaple.tw failed
| :x: | 清華資工 呼拉貝爾 <br> *Hulabear*, CS, NTHU | [telnet://114.32.9.125](telnet://114.32.9.125) | [WindTop BBS](http://windtop.yzu.edu.tw/) | |
| :white_check_mark: | 彰師生命 吟風‧眺月‧擎天崗 <br> *Qingtiangang*<sup>\[?]</sup>, Bio, NCUE | [telnet://bbs.bio.ncue.edu.tw](telnet://bbs.bio.ncue.edu.tw) <br> [telnet://bbs2.ncue.edu.tw](telnet://bbs2.ncue.edu.tw) <br> [telnet://micro.bio.ncue.edu.tw](telnet://micro.bio.ncue.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<http://micro.bio.ncue.edu.tw:8080> :unlock: <br> 2021-07-10: guest 不可登入 (無此帳號) <br> guest cannot log in (unrecognized user ID) <br> 2023-01-16: up |
| :x: | 真理 雲淡風清 <br> *Yun Dan Feng Qing*, AU | [telnet://bbs.au.edu.tw](telnet://bbs.au.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 真理 脆笛酥的家 <br> *Jal's Home*<sup>\[?]</sup>, AU | [telnet://bbs.jal.tw](telnet://bbs.jal.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: guest 不可登入 (無此帳號) <br> guest cannot log in (unrecognized user ID) |
| :white_check_mark: | 政大資科 貓空行館 <br> *Maokong Hotel*<sup>\[?]</sup>, CS, NCCU | [telnet://bbs.cs.nccu.edu.tw](telnet://bbs.cs.nccu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2023-04-09: Up |
| :x:<sup>:question:</sup> | 中正 寂寞芳心小站 <br> *Feeling BBS*, CCU | [telnet://bbs.ccu.edu.tw](telnet://bbs.ccu.edu.tw) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 2018/8/3：down <br> 2022-02-14: 域名解析失敗 Domain resolution failed |
| :x: | 中正心理 心海奇航-賽卡羅旗號 <br> *Pirates of the Consciousness: Boat of Psychology*<sup>\[?]</sup>, Psy, CCU | [telnet://140.123.185.40](telnet://140.123.185.40) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | ~~中正~~築夢園 <br> *CCU Dream*, ~~CCU~~ | ~~telnet://140.123.29.12~~ <br> ~~telnet://cd.cna.ccu.edu.tw~~ :x:<sup>:question:</sup> <br> [telnet://207.148.108.123](telnet://207.148.108.123) <br> [telnet://ccudream.csie.io](telnet://ccudream.csie.io) <br> [telnet://cd.csie.io](telnet://cd.csie.io) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 已由Maple 3 轉至 Maple3.10-itoc 版本 <br> The software switched from Maple 3 to Maple3.10-itoc <br> 2021-02-18 測試: 新域名 up <br> ~~預計 2021/12/30 關站 Expected to be closed on 2021-12-30~~ <br> 2021-12-30 取消關站 Cancel the closing announcement |
| :x:<sup>:question:</sup> | 中正 闇黑國度 <br> *Dark Empire*<sup>\[?]</sup>, CCU | [telnet://bbs.cna.ccu.edu.tw](telnet://bbs.cna.ccu.edu.tw) <br> [wss://term.cna.ccu.edu.tw:9800](wss://term.cna.ccu.edu.tw:9800) (TLS 1.0/1.1) [:unlock:](#Websocket-連線) <br> <https://term.cna.ccu.edu.tw> (wss) (TLS 1.0/1.1) [:unlock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-01-31: 預計 2022/3/1 關站 Expect to be closed on 2022-03-01 <br> 2022-07-02: 域名 down Domain down |
| :white_check_mark: | 中正通訊 1394 <br> *1394*, Comm, CCU | ~~telnet://bbs.comm.ccu.edu.tw~~ <br> `ssh bbs@bbs.comm.ccu.edu.tw` [:lock:](#SSH-連線) :x: | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<https://bbs.comm.ccu.edu.tw> <br> 2021-08-18: Telnet 連線停用 <br> Telnet connection is no longer provided <br> 2022-07-02: SSH 連線逾時 Connection using SSH timed out <br> 2022-11-18: 網頁版 up Website up |
| :x: | 中山 美麗島 <br> *Formosa BBS*, NSYSU | [telnet://140.117.11.2](telnet://140.117.11.2) <br> [telnet://[2001:288:8001:11::2]](telnet://[2001:288:8001:11::2]) <br> [telnet://bbs.nsysu.edu.tw](telnet://bbs.nsysu.edu.tw) | [Formosa BBS CE](https://github.com/PichuChen/formosa) | (1992-12 資訊月開站 Est. 1992-12 IT Month) <br> 2021-07-10: IPv4 無法連線 Cannot connect using IPv4 |
| :x: | 中山 西子灣 <br> *Sizihwan*<sup>\[?]</sup>, NSYSU | [telnet://140.117.11.6](telnet://140.117.11.6) <br> [telnet://[2001:288:8001:11::6]](telnet://[2001:288:8001:11::6]) <br> [telnet://bbs3.nsysu.edu.tw](telnet://bbs3.nsysu.edu.tw) | [Formosa BBS CE](https://github.com/PichuChen/formosa) | 網頁版 Web UI: <https://[2001:288:8001:11::6]> <br> 2021-07-10: IPv4 無法連線 Cannot connect using IPv4 <br> 2021-07-10: 僅網頁版可連 Only accessible using website <br> 2021-12-01: 網頁版 down Website down |
| :x: | 中央 二進位 <br> *Binary*, NCU | [telnet://140.115.50.50](telnet://140.115.50.50) <br> [telnet://binary.csie.ncu.edu.tw](telnet://binary.csie.ncu.edu.tw) <br> [telnet://bbs.ncu.cc](telnet://bbs.ncu.cc) :x:<sup>:question:</sup> | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-07-10: Down <br> 2022-02-14: .cc 域名解析失敗 Resolution failed for the .cc domain |
| :x: | 中央數學 織夢天堂 <br> *Heaven of Dream Weaver*<sup>\[?]</sup>, Math, NCU | [telnet://bbs.math.ncu.edu.tw](telnet://bbs.math.ncu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<http://bbs.math.ncu.edu.tw> :unlock: <br> 2023-04-09: 網頁版 down Web down |
| :x: | 中央 神通廣大 <br> *Supernatural Communication*<sup>\[?]</sup>, CE, NCU | [telnet://bbs.ce.ncu.edu.tw](telnet://bbs.ce.ncu.edu.tw) | | |
| :white_check_mark: | 中原資工 神祕之旅 <br> *Mystery Tour*<sup>\[?]</sup>, ICE, CYCU | [telnet://bbs.ice.cycu.edu.tw](telnet://bbs.ice.cycu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<https://bbs.ice.cycu.edu.tw> |
| :x:<sup>:question:</sup> | 長庚 巧克力傳奇 <br> *Legend of Chocolate*<sup>\[?]</sup>, CGU | [telnet://bbs.cgu.edu.tw](telnet://bbs.cgu.edu.tw) | | 2022-02-14: 域名解析失敗 Domain resolution failed |
| :x: | 長庚醫學 醫甸園 <br> *Garden of M-Eden*<sup>\[?]</sup>, Med, CGU | [telnet://bbs.med.cgu.edu.tw](telnet://bbs.med.cgu.edu.tw) | [PttBBS](https://github.com/ptt/pttbbs) <br> (不明舊版本 unknown early ver.) | |
| :white_check_mark: | 成功 夢之大地 <br> *Dream Land BBS*, NCKU | ~~telnet://140.116.250.3~~ :x:<sup>:question:</sup> **(IP已更改 IP has changed)** <br> ~~telnet://140.116.249.140~~  / [:3456](telnet://140.116.249.140:3456) **(現在IP Current IP)** <br> ~~telnet://[2001:288:7001:249::140]~~ / [:3456](telnet://[2001:288:7001:249::140]:3456)  <br> ~~telnet://ccns.cc~~ / [:3456](telnet://ccns.cc:3456) <br> `ssh bbs@ccns.cc` / `-p 22222` [:lock:](#SSH-連線) <br> [wss://ws.ccns.ncku.edu.tw/bbs](wss://ws.ccns.ncku.edu.tw/bbs) [:lock:](#Websocket-連線) <br> <https://term.ccns.cc> (wss) [:lock:](#Websocket-連線) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> 3.10 Rev. 20081002 <br> [DreamBBS git r1785+](https://github.com/ccns/dreambbs) | 2022-07-02: 校外 port 23 連線失敗 Connection to port 23 failed outside the school <br> 2022-07-02 棄用 Telnet 連線 Telnet connection has been deprecated <br> port 3456 僅作後備使用 <br> Port 3456 is now only for reserved uses <br> 2022-09-05: 校外 port 22 連線失敗 Connection to port 22 failed outside the school <br> ssh 連線請改用 port 22222 <br> Please use port 22222 for SSH connection instead |
| :x: | 成大電機 風之谷 <br> *Windy Valley*, EE, NCKU | [telnet://bbs.ee.ncku.edu.tw](telnet://bbs.ee.ncku.edu.tw) / [:3456](telnet://bbs.ee.ncku.edu.tw:3456) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [windyvalleybbs](https://github.com/bbsmirror/windyvalleybbs) r55.1 | guest過多無法登入；不開放線上註冊 <br> guest is unavailable due to too many guests online; online registration is closed <br> 2022-07-02: port 23 連線失敗 Connection to port 23 failed <br> 2023-04-09: 連線逾時 Connection timed out |
| :x: | 成大醫學 迴風谷 <br> *Whirlwind Valley*<sup>\[?]</sup>, Med, NCKU | [telnet://bbs.med.ncku.edu.tw](telnet://bbs.med.ncku.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-07-02: port 23 連線失敗 Connection to port 23 failed |
| :x:<sup>:warning:</sup> | 師大資訊 白色情迷 <br> *Blanc*<sup>\[?]</sup>, CSIE, NTNU | [telnet://bbs.csie.ntnu.edu.tw](telnet://bbs.csie.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-14: ping 有回應 Responsive to ping |
| :white_check_mark: | 師大數學 獨數一閣 <br> *Math Home*, Math, NTNU | [telnet://bbs.math.ntnu.edu.tw:8000](telnet://bbs.math.ntnu.edu.tw:8000) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5284 | 2022-06-21: 校外 port 改 8000 <br> The port for connecting outside the school changed to 8000 |
| :white_check_mark: | 師大 人民公社 <br> *Civil Commune*<sup>\[?]</sup>, NTNU | [telnet://cvic.org](telnet://cvic.org) <br> [telnet://cvic.be](telnet://cvic.be) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2019-10-31: Up <br> 2021-07-10 guest 從主選單進入 `(C)onfig` 後直接按右鍵會進入空白選單 <br> The guest enters an empty menu if entering `(C)onfig` from the main menu and then pressing <kbd>→</kbd> |
| :x: | 師大歷史 原史空間 <br> *Protohistory Space*<sup>\[?]</sup>, His, NTNU | [telnet://bbs.his.ntnu.edu.tw](telnet://bbs.his.ntnu.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-07-10: Down |
| :white_check_mark: | 慈濟 蔚藍海岸 <br> *Perl BBS*, TCU | [telnet://perlbbs.tw](telnet://perlbbs.tw) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | |
| :x: | 陽明 神農坡 <br> *Shennong Hillside*<sup>\[?]</sup>, NYMU | [telnet://bbs.ym.edu.tw](telnet://bbs.ym.edu.tw) | [Maple3](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | PCMan主要作者畢業學校 <br> The university where the main author of PCMan graduate |
| :x: | 元智 風之塔 <br> *Wind's Top*, YZU | [telnet://bbs.yzu.edu.tw](telnet://bbs.yzu.edu.tw) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | 2020-06-24: down |
| :x: | 元智資工 火車站 <br> *Train BBS*, CSE, YZU | [telnet://bbs.cse.yzu.edu.tw](telnet://bbs.cse.yzu.edu.tw) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) <br> TrainBBS Ver.1220 | 2022-07-04: 進入 `(I)nfo` 會斷線 <br> Disconnects when entering `(I)nfo` <br> 2022-11-14: 連線失敗 Connection failed |
| :x:<sup>:question:</sup> | 雲林科大 藍天使 <br> *Blue Angel*<sup>\[?]</sup>, NYUST | [telnet://bbs.yuntech.edu.tw](telnet://bbs.yuntech.edu.tw) | | 2017/1/5：down <br> 2022-02-14: 域名解析失敗 Domain resolution failed |

</div>    

## 高中相關站台
### Senior High School Sites and Derivation Sites

<div class="bbslist">

| 可連&nbsp;&nbsp; <br> Con. | 站名 <br> Site Name | 位址 <br> Address | BBS 版本 <br> BBS Server Version | 備註 <br> Notes |
| - | - | - | - | - |
| :white_check_mark: | 北一女中 弗基斯特 <br> *Fu GI Si Te*<sup>\[?]</sup>, FGISC, TFGHS | [telnet://fgisc.org](telnet://fgisc.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 台南一中 動力核心 <br> *Processor*, TNFSH | [telnet://cpu.tfcis.org](telnet://cpu.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-03-05: up |
| :x: | 台南一中資訊社 索尼小站 <br> *Sony BBS*, TFCIS, TNFSH | [telnet://bbs.tfcis.org](telnet://bbs.tfcis.org) <br> [telnet://sony.tfcis.org](telnet://sony.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [SonyBBS](https://github.com/lantw44/sonybbs) | 不開放 guest <br> Not open to guest <br> 2022-02-14: down |
| :white_check_mark: | 台南一中 與南共舞 <br> *Wolf BBS*, TNFSH | [telnet://bbs.tnfsh.tn.edu.tw](telnet://bbs.tnfsh.tn.edu.tw) <br> [telnet://wolf.tfcis.org](telnet://wolf.tfcis.org) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x:<sup>:question:</sup> | 台中二中 迷幻國度 <br> *Charming Shadow Country*, TCSSH | [telnet://csc241.tcssh.tc.edu.tw](telnet://csc241.tcssh.tc.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-14: 域名解析失敗 Domain resolution failed |
| :x:<sup>:warning:</sup> | 台中一中 龍夢紀元 <br> *Era of Dragon*, TCFSH | [telnet://bbs.tcfsh.tc.edu.tw](telnet://bbs.tcfsh.tc.edu.tw) :x:<sup>:question:</sup> <br> [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs) [:lock:](#Websocket-連線) :x:<sup>:question:</sup> <br> [telnet://eod.tw](telnet://eod.tw) <br> [ws://eod.tw/bbs](ws://eod.tw/bbs) <br> [wss://eod.tw/bbs](wss://eod.tw/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 程式碼為極光鯨藍之穩定版本分支 <br> The code branched off from the stable version of Auroral BBS <br> 2020-12-27: Down <br> 2022-02-14: .edu.tw 域名解析失敗；其它域名 ping 有回應 <br> Resolution failure for the .edu.tw domain; responsive to ping via the other domains |
| :x:<sup>:question:</sup> | 台中一中電研社 極光鯨藍 <br> *Auroral BBS*, TCIRC, TCFSH | [telnet://tcirc.org](telnet://tcirc.org/) <br> `ssh bbs@tcirc.org` [:lock:](#SSH-連線) <br> [wss://tcirc.org/bbs](wss://tcirc.org/bbs) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [Auroral BBS](https://github.com/MapleCirc/Auroral) | 2021-08-18: `DNS resolution error` |
| :x:<sup>:question:</sup> | 建中之夏 烏魯木齊 <br> *CKHS's Summer&mdash;Ürümchi*<sup>\[?]</sup>, CKHS | [telnet://bbs.ck.tp.edu.tw](telnet://bbs.ck.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-08-18: 域名解析失敗 Domain resolution failed |
| :x: | 中壢高中 壢網狂瀾 <br> *LI WANG Kuang Lan*, CLHS | [telnet://clhs.csie.org](telnet://clhs.csie.org) | [WindTop BBS](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) [3.02 Rev. 20001220](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-3.02-20001220-SNAP.tgz) <br> CLHSBBS Ver.20030520 | 2023-01-17: 連線失敗 Connection failed |
| :x:<sup>:question:</sup> | 中山女中 楓資羽翼 <br> *Feng Zi Yu Yi*, CSGHS | [telnet://203.68.236.13](telnet://203.68.236.13) <br> [telnet://csisc.csghs.tp.edu.tw](telnet://csisc.csghs.tp.edu.tw) | [WindTop](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) → [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<http://bbs.csghs.tp.edu.tw> :unlock: <br> 2019-12-31: Down <br> 2021-08-18: 域名解析失敗 Domain resolution failed |
| :x:<sup>:question:</sup> | 成功高中 沈澱日記 <br> *Chen Dian Ri Ji*, CKSH | `ssh bbsu@bbs.ckcsc.net -p 25` [:lock:](#SSH-連線) <br> <https://bbs.ckcsc.net> (ttyd) :lock: | [PttBBS git r4927+](https://github.com/ptt/pttbbs) | 提供網頁終端介面(ttyd)登入 <br> Provides a web terminal interface (ttyd) <br> 2021-08-12: 連線逾時 Connection timed out <br> 2022-03-05: 域名解析失敗 Domain resolution failed |
| :x:<sup>:question:</sup> | 永春高中 永春哈哈 <br> *Yong Chun Ha Ha*, YCSH | [telnet://haha.ycsh.tp.edu.tw](telnet://haha.ycsh.tp.edu.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 無法進去看板閱讀，僅能瀏覽公佈欄/精華區 <br> Cannot browse any boards; can only browse within the announcement/gem area <br> 2022-02-14: 域名解析失敗 Domain resolution failed |

</div>

## 不在學術網路的站台
### Sites outside of the Academic Network in Taiwan

<div class="bbslist">
    
| 可連&nbsp;&nbsp; <br> Con. | 站名 <br> Site Name | 位址 <br> Address | BBS 版本 <br> BBS Server Version | 備註 <br> Notes |
| - | - | - | - | - |
| :white_check_mark: | 八八八 <br> *888* | [telnet://bbs.wim888.tw](telnet://bbs.wim888.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 網頁版 Web UI：<http://bbs.wim888.tw> :unlock: <br> 2022-11-15: up |
| :white_check_mark: | 巴哈姆特BBS <br> *Bahamut BBS* | [telnet://bbs.gamer.com.tw](telnet://bbs.gamer.com.tw) <br> [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) [:lock:](#Websocket-連線) :x: <br> <https://term.gamer.com.tw> (wss) [:lock:](#Websocket-連線) <br> [telnet://bahamut.org](telnet://bahamut.org) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | 網頁版 Web UI: <https://www.gamer.com.tw> <br> guest 無法登入, 需先從 Web 註冊 <br> Not open to guest; requires registering from the website in advance <br> 2022-07-02: 直接連 WebSocket 失敗，須從 PttChrome 網頁版連線 <br> Directly connection to WebSocket failed; use the PttChrome webpage is needed |
| :white_check_mark: | 貓坑 CatPit <br> *CatPit* | [telnet://bbs.cis92.net](telnet://bbs.cis92.net) | [MapleBBS 3.10](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) CCH Patch | |
| :x: | 反地球聯邦組織 <br> *A.E.U.G.*<sup>\[?]</sup> | [telnet://122.116.74.57](telnet://122.116.74.57) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x: | 風與塵埃的對話 <br> *Wind & Dust BBS* | [telnet://wdbbs.tw](telnet://wdbbs.tw) | [Wind & Dust](https://github.com/bbsmirror/BBSmirror/tree/master/WD/) | 2021-01-11: Down |
| :white_check_mark: | △．Kirika <br> *Kirika* | [telnet://andcycle.idv.tw](telnet://andcycle.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :white_check_mark: | 動漫遊戲廣播站 <br> *Animeyo* | [telnet://bbs.animeyo.com](telnet://bbs.animeyo.com) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | |
| :x:<sup>:warning:</sup> | 台灣天主教BBS站 厄瑪奴耳 <br> *Emmanuel*, CCNET | [telnet://bbs-jesus.name](telnet://bbs-jesus.name) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2023-04-09: Service unavailable |
| :white_check_mark: | 內灣新小月台 <br> *EMU486* | [telnet://bbs.emu486.net](telnet://bbs.emu486.net) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [MapleBBS-itoc-emu486](https://github.com/irvin/MapleBBS-itoc-emu486) | 2022-07-02: up |
| :white_check_mark: | 南友小站 <br> *Tainan BBS* |[telnet://tainan.jal.tw](telnet://tainan.jal.tw) <br> [telnet://192.192.120.31](telnet://192.192.120.31) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 看板列表排版溢出，但仍可正常進入看板 <br> The display of board list overflows but behaves as expected <br> 2022-03-05: up |
| :white_check_mark: | 華年小集 <br> *Literature BBS* | [telnet://literature.twbbs.io](telnet://literature.twbbs.io) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r5563 | |
| :white_check_mark: | 花魁藝色館 <br> *Libido BBS* | [telnet://libido.cx](telnet://libido.cx) <br> [telnet://74.52.17.106](telnet://74.52.17.106) :x: <br> [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) [:lock:](#Websocket-連線) <br> <https://libido.malusu.com> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | ~~2018/10 下旬起停用 libido.cx 域名連線 The libido.cx domain is expected to be terminated in late 2018-10~~ <br> <br> 2021-08-18: 原域名 up The previous domain is up <br> 不開放 guest 登入 <br> Not open to guest <br> 2022-03-05: Telnet up |
| :x: | 伙計小站 <br> *Partner BBS* | [telnet://patw.idv.tw](telnet://patw.idv.tw) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) <br> [PartnerBBS](https://github.com/patw0929/MapleBBS-itoc) | 2020/04/19:down |
| :white_check_mark: | 西雅圖 <br> *Seattle* | [telnet://www.seattle.tw](telnet://www.seattle.tw) [telnet://seattle.tw](telnet://seattle.tw) [telnet://122.117.16.81](telnet://122.117.16.81) | [MapleBBS-3.10-20121021-PACK.itoc](https://github.com/xeonchen/maplebbs-itoc) | 2020/02/22: 已復站 The site is resumed |
| :white_check_mark: | 幸運草之戀 <br> *Segaa BBS* | [telnet://segaa.net](telnet://segaa.net) | [WindTopBBS-3.02-20021129-SNAP](https://github.com/bbsmirror/BBSmirror/tree/master/WindTop) | 2022-11-15: up |
| :white_check_mark: | 書齋軒 <br> *Wind City* | [telnet://bbs.windcity.net](telnet://bbs.windcity.net) | [Open Ptt](https://github.com/bbsmirror/BBSmirror/tree/master/Ptt/openptt) | 提供個人及團體板 <br> Provides personal and group boards |
| :x: | 亞特蘭提斯 <br> *Atlantis* | [telnet://125.227.52.214](telnet://125.227.52.214) <br> [telnet://bbs.bsd.com.tw](telnet://bbs.bsd.com.tw) | [Atlantis](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis) | 註冊通過者, 可自己開個板, 免等審核 <br> Registered users can create their personal board without manual approval <br> 2023-01-16: 連線失敗 Connection failed
| :white_check_mark: | 武陵人的桃花源 <br> *Wulinger's BBS* | [telnet://139.180.205.27:2323](telnet://139.180.205.27:2323) | [Maple3.02](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) | |
| :x: | 543 音樂站 <br> *543 Music BBS* | [telnet://music543.com](telnet://music543.com) | [PttBBS](https://github.com/ptt/pttbbs) <br> trunk r3359 | 網頁版 Web UI（資料不完全與 telnet 介面同步 Data not completely in sync with the telnet interface）：<http://music543.com> :unlock: <br> 2022-07-02: 連線逾時 Connection timed out |
| :x:<sup>:question:</sup> | YKLM大學 <br> *YKLM School* | [telnet://yklm.schl.tw](telnet://yklm.schl.tw) :x: <br> [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) [:lock:](#Websocket-連線) :x: <br> <https://yklm.schl.tw> (wss) [:lock:](#Websocket-連線) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2021-08-10: Up <br> 2022-02-14: Telnet down <br> 2022-07-02: WebSocket down <br> 2023-04-09: 域名解析失敗 Domain resolution failed |
| :white_check_mark: | 網際新世界 <br> *NETO WORLD* | [telnet://209.141.35.127](telnet://209.141.35.127) | [Sun of Beach](https://github.com/bbsmirror/BBSmirror/tree/master/SOB/) | 2021-01-11: Up <br> 2021-07-10: guest 無法登入（無此帳號） <br> guest cannot log in (unrecognized user ID) |
| :x:<sup>:warning:</sup> | 月下夜想 <br> *Luna BBS* | [telnet://220.130.248.130](telnet://220.130.248.130) | [Maple3.10-itoc](https://github.com/xeonchen/maplebbs-itoc) | 2022-02-14: ping 有回應 Responsive to ping |
| :x:<sup>:warning:</sup> | 永恆地域‧拉帕之結 <br> *Lapa BBS* | [telnet://lapa.tw](telnet://lapa.tw) | (不明; MapleBBS?) | 2022-11-17: guest 無法登入；登入即斷線 <br> guest cannot log in; disconnects as soon as log in <br> 2023-04-09: Down |

</div>

## 中國大陸站台
### Sites in Mainland China and Derivation Sites

<div class="bbslist">

| 可連&nbsp;&nbsp; <br> Con. | 站名 <br> Site Name | 位址 <br> Address | BBS 版本 <br> BBS Server Version | 備註 <br> Notes |
| - | - | - | - | - |
| :white_check_mark: | 北京大學 <br> *PKU BBS* | ~~telnet://bbs.pku.edu.cn~~ <br> `ssh <user>@bbs.pku.edu.cn` [:lock:](#SSH-連線) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | 網頁版 Web UI：<https://bbs.pku.edu.cn> <br> 2021-08-18：SSH up <br> 2023-01-16: 已棄用 Telnet 連線 The Telnet connection has been deprecated |
| :x: | 未名空間 <br> *MIT BBS* | [telnet://mitbbs.com](telnet://mitbbs.com) <br> `ssh <user>@mitbbs.com` (SSH-1) [:unlock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d) <br> MITBBS | 網頁版 Web UI：<https://mitbbs.com> <br> 相關衍生之商業BBS站台 Commercial derivation site <br> [已關站 Closed](https://newmitbbs.com/viewtopic.php?t=2795) |
| :white_check_mark: | 北京大學 大話西遊 <br> *Da Hua Xi You*, PKU | [telnet://dhxy.info](telnet://dhxy.info) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1106 (beta2) | 網頁版 Web UI：<http://dhxy.info> :unlock: <br> 2021-08-21: guest 不可登入 (無此 ID) <br> guest cannot log in (unrecognized ID) <br> 加密連線憑證過期 Encryption certification outdated |
| :white_check_mark: | 北京大學 桃花潭 <br> *Tao Hua Tan*, PKU | [telnet://thtpku.3322.org](telnet://thtpku.3322.org) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版 Web UI：<https://thtpku.3322.org> <br> 無法申請新帳號 <br> Registration is unavailable <br> guest 不可登入 (無此帳號) <br> guest cannot log in (unrecognized user ID) <br> 2022-02-14: Telnet up |
| :x: | 一塌糊塗 海外紀念站 <br> *Yi Ta Hu Tu Oversea Memorial Site*<sup>\[?]</sup> | [telnet://bbs.ytht.net](telnet://bbs.ytht.net) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
| :white_check_mark: | 北京郵電大學 北郵人論壇 <br> *Bei You Ren Forum*<sup>\[?]</sup>, BUPT | [telnet://bbs.byr.cn](telnet://bbs.byr.cn) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版：<br><https://bbs.byr.cn> |
| :x:<sup>:question:</sup> | 東南大學 虎踞龍盤 <br> *Hu Ju Long Pan*, SEU | [telnet://bbs.seu.edu.cn](telnet://bbs.seu.edu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2022-02-14: 域名解析失敗 Domain resolution failed |
| :white_check_mark: | 復旦大學 日月光華 <br> *Ri Yue Guang Hua*, FDU | [telnet://bbs.fudan.edu.cn](telnet://bbs.fudan.edu.cn) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [fbbs](https://github.com/fbbs/fbbs) | 網頁版：<https://bbs.fudan.edu.cn> <br> 2023-04-09: Up |
| :white_check_mark: | ~~復旦大學~~ 燕曦BBS <br> *Yan Xi BBS*, ~~FDU~~ | [telnet://yanxi.org](telnet://yanxi.org) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | |
| :x:<sup>:question:</sup> | 廣西師範大學 煙雨漓江 <br> *Yan Yu Li Jiang*, GXNU | [telnet://bbs.gxnu.cn](telnet://bbs.gxnu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 2022-02-14: 域名解析失敗 Domain resolution failed |
| :x:<sup>:question:</sup> | 哈爾濱工業大學 紫丁香站 <br> *Lilac BBS*, HIT | [telnet://bbs.hit.edu.cn](telnet://bbs.hit.edu.cn) | | 無法連線,可能是限制校外ip連入或關站 <br> Connect failed, possibly due to limitation of IP outside of the school or being closed <br> 2022-02-14: 域名解析失敗 Domain resolution failed |
| :white_check_mark: | 紫丁香社區 <br> *Lilac Community*<sup>\[?]</sup> | [telnet://lilacbbs.com](telnet://lilacbbs.com) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/)  <br> [SMTH BBS 1.2](https://github.com/zhouqt/kbs/tree/ba2d9aa2c53f47d27763380e6d16b24c567ddb1d) <br> [LilacBBS](https://github.com/marvelliu/lilacsrc) | 網頁版 Web UI：<http://lilacbbs.com> :unlock: <br> 相關衍生之商業BBS站台 Commercial derivation site |
| :x: | 華中理工 白雲黃鶴 <br> *Bai Yun Huang He*, HUST | [telnet://bbs.whnet.edu.cn](telnet://bbs.whnet.edu.cn) <br> [telnet://byhh.hust.edu.cn](telnet://byhh.hust.edu.cn) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | 網頁版 Web UI：<http://byhh.hust.edu.cn> :unlock: <br> 2020-12-18: Down <br> 2022-07-02: 網頁版限校內連入 The website is only accessible from the school |
| :x: | 蘭州大學 西北望BBS站 <br> *Xi Bei Wang BBS*, LZU | [telnet://106.225.138.11:2223](telnet://106.225.138.11:2223) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 2022-07-24: 連線逾時 Connection timed out |
| :x: | 南京大學 小百合 <br> *Lily BBS*, NJU | [telnet://bbs.nju.edu.cn](telnet://bbs.nju.edu.cn) (教育網 Academic network) <br> [telnet://lilybbs.net](telnet://lilybbs.net) (公眾網 Public network) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) | |
| :x: | 清華大學 <br> *THU BBS*<sup>\[?]</sup> | [telnet://smth.org](telnet://smth.org) | | (1995-08-08 開站 Est. 1995-08-08) <br> [無法連線 Connection failed](https://www.ptt.cc/bbs/SMTH/M.1415081920.A.2B0.html) |
| :white_check_mark: | 水木社區 <br> *Shuimu Community*<sup>\[?]</sup> | [telnet://newsmth.org](telnet://newsmth.org) <br> `ssh <user>@newsmth.org` [:lock:](#SSH-連線) <br> [telnet://bbs.newsmth.net](telnet://bbs.newsmth.net) <br> `ssh <user>@bbs.newsmth.net` [:lock:](#SSH-連線) <br> [telnet://bbs.mysmth.net](telnet://bbs.mysmth.net) <br> `ssh <user>@bbs.mysmth.net` [:lock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版 Web UI：<br> <https://www.newsmth.net> <br> <https://www.mysmth.net> <br> 相關衍生之商業BBS站台 Commercial derivation site |
| :white_check_mark: | 清華大學 大話西遊 (紫霞BBS) <br> *Zixia BBS*, THU | [telnet://wforum.zixia.net](telnet://wforum.zixia.net) <br> `ssh <user>@wforum.zixia.net` (SSH-1) [:unlock:](#SSH-連線) <br> [telnet://bbs.zixia.net](telnet://bbs.zixia.net) <br> `ssh <user>@bbs.zixia.net` (SSH-1) [:unlock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) <br> [zixia BBS v21.2.1](https://github.com/zixia/bbs) |
| :white_check_mark: | 清華大學 KissU <br> *THU KissU*<sup>\[?]</sup> | [telnet://bbs.thu.cn](telnet://bbs.thu.cn) :x: | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版 Web UI：<https://bbs.thu.cn> <br> 2021-08-18: 僅網頁版可連 <br> Only accessible using website <br> 2023-04-09: 網頁版 up Website up |
| :white_check_mark: | 清華大學 聽濤站 <br> *Ting-Tao Zhan*, THU | [telnet://bbs.tingtao.net](telnet://bbs.tingtao.net) <br> `ssh <user>@bbs.tingtao.net` (SSH-1) [:unlock:](#SSH-連線) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FirebirdBBS_cuhk/) <br> [SMTH BBS 1.0](https://github.com/zhouqt/kbs) | 網頁版 Web UI：<https://bbs.tingtao.net> <br> 2022-03-05: up |
| :x: | 上海交大 飲水思源 <br> *Yin Shui Si Yuan*, SJTU | [telnet://bbs.sjtu.edu.cn](telnet://bbs.sjtu.edu.cn) | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1106 (beta2) <br> [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs) | 網頁版 Web UI：<https://bbs.sjtu.edu.cn> :unlock: :x: (TLS 1.0/1.1) <br> 不開放校外連線 Not open to connections outside the school <br> 2021-12-01: 加密連線憑證過期 Encryption certification outdated |
| :white_check_mark: | 南洋客棧 <br> *Nan Yang Ke Zan* | [telnet://bbs.nykz.net](telnet://bbs.nykz.net) <br> [telnet://back.nykz.net:2323](telnet://back.nykz.net:2323) :x:<sup>:question:</sup> | [FireBird BBS 2000](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) v1219 <br> [sjtubbs](https://github.com/scaret/nykz/tree/master/sjtubbs) <br> [nykz BBS](https://github.com/scaret/nykz) | 相關衍生站臺 Derivation site <br> 2021-10-12: guest 不可登入 (無此 ID) <br> guest cannot log in (unrecognized user ID) <br> 2022-02-14: back. 域名解析失敗 <br> Resolution failed for the back. domain |
| :x: | 四川大學 藍色星空站 <br> *Lan Se Xing Kong*, SCU | [telnet://bbs.lsxk.org](telnet://bbs.lsxk.org) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 已經關閉telnet，只提供校內ssh加密訪問 <br> The Telnet connection is no longer provided. Only accessible using SSH within the school. |
| :x: | 西安交大 兵馬俑 <br> *Bing Ma Yong*, XJTU | [telnet://bbs.xjtu.edu.cn](telnet://bbs.xjtu.edu.cn) :x: | [FireBird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [YTHT BBS](https://github.com/lytsing/ytht) <br> [bmybbs](https://github.com/bmybbs/bmybbs) | 網頁版 Web UI：<br> <https://bbs.xjtu.edu.cn/> <br> 2021-12-18: Telnet 與 SSH 連線限校內連入 <br> Telnet & SSH connection are accessible only within the school <https://bbs.xjtu.edu.cn/BMY/con?B=sysop&F=M.1617802725.A> |
| :white_check_mark: | ~~浙江大學~~ 明月水軒 <br> *Moon BBS*, ~~ZJU~~ | [telnet://bbs.twomice.net](telnet://bbs.twomice.net) | [MapleBBS 3.10](https://github.com/bbsmirror/BBSmirror/tree/master/Maple/Maple3/) <br> MoonBBS v0.0.2 | 2023-04-09: Up |
| :x: | 中國科大 瀚海星雲 <br> *Xiang Hai Xing Yun*, USTC | [telnet://ustcbbs.ustc.edu.cn](telnet://ustcbbs.ustc.edu.cn) :x:<sup>:question:</sup> <br> [telnet://bbs.ustc.edu.cn](telnet://bbs.ustc.edu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | 網頁版 Web UI：<https://bbs.ustc.edu.cn> <br> 2021-04-05: guest 不可登入 (無此 ID) <br> guest cannot log in (unrecognized user ID) <br> 2022-02-14: ustcbbs 域名解析失敗 <br> resolution failed for the ustcbbs domain <br> 2022-07-02: 連線逾時 Connection timed out |
| :x:<sup>:question:</sup> | 中科院 (智慧電腦中心) 曙光站 <br> *Shu-Guang Zhan*, CAS | [telnet://bbs.ncic.ac.cn](telnet://bbs.ncic.ac.cn) | | (1994 春開站 Est. Spring 1994) <br> 2022-02-14: 域名解析失敗 Domain resolution failed |
| :x: | 中國礦業大學 放鶴亭 <br> *Fang He Ting*, CUMT | [telnet://bbs.cumt.edu.cn](telnet://bbs.cumt.edu.cn) | [FireBird BBS 2.65M](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) | |
    
</div>

* 北京大學 一塌糊涂 *Yi Ta Hu Tu*, PKU: telnet://ytht.net\
  2004-09-13 被關 Closed
* 清華大學 水木清華 *Shuimu Tsinghua*, THU: telnet://smth.org\
  2005-03-16 封校 Access limited to within the school
* 南京大學 小百合 *Lily BBS*, NJU: telnet://bbs.nju.edu.cn\
  2005-03-22 分站 Subsidiary site

## 其他海外華文 BBS 站台
### Other Oversea Chinese-Language Sites

<div class="bbslist">
    
| 可連&nbsp;&nbsp; <br> Con. | 站名 <br> Site Name | 位址 <br> Address | BBS 版本 <br> BBS Server Version | 備註 <br> Notes |
| - | - | - | - | - |
| :x: | 美國 聖迭戈小站 *San Diego Home*, America | [telnet://bbs.huaxiaspace.net](telnet://bbs.huaxiaspace.net) <br> [telnet://sd-bbs.net](telnet://sd-bbs.net) | [FireBird BBS](https://github.com/bbsmirror/BBSmirror/tree/master/FireBird/) <br> [KBS BBS 2.0](https://github.com/zhouqt/kbs) | 網頁版 Web UI：<http://sd-bbs.net/> :unlock: <br> 2023-04-09: 連線逾時 Connection timed out |
| :x: | 美國 天天壇 *Tian-Tian Tan*, America | [telnet://tttan.com](telnet://tttan.com) | [FireBird BBS 3.0-KCN](https://github.com/bbsmirror/BBSmirror/tree/master/NotOpen/china_bbs/hightman/) <br> [YTHT BBS](https://github.com/lytsing/ytht) | |

</div>

### <div id="bbstotal"></div>

## 加密連線站台資料列表
### Sites with Encrypted Connection

### SSH 連線
**SSH Connection**

- 連線方式有 `<user>` 的站台，ssh 帳密與 telnet BBS 帳密同步，請將 `<user>` 代入 telnet 帳號 ID。\
  For sites with `<user>` in their connection method, the SSH user ID/password is in sync with their in-BBS interface. Please substitute `<user>` with the user ID of your BBS account.
- 有 (SSH-1) 標示的站台，只支援 SSH-1 → *不安全*\
  Sites with (SSH-1) in their connection method only support SSH-1 and are **not secure**.

| 站名 <br> Site Name | 連線方式 <br> Connection Method | 備註 <br> Notes |
| - | - | - |
| 批踢踢實業坊 <br> *Ptt* | `ssh bbs@ptt.cc` <br> `ssh bbsu@ptt.cc` (預設使用 UTF-8) | |
| 批踢踢兔 <br> *Ptt 2* | `ssh bbs@ptt2.cc` <br> `ssh bbsu@ptt2.cc` (預設使用 UTF-8) | |
| 批踢踢參 <br> *Ptt 3* | `ssh bbs@ptt3.cc` | 密碼: `bbs` |
| 台大 未來最舊小棧 <br> *Oldest future Object*, NTU | `ssh bbs@ofo.tw` | |
| 中正通訊 1394 <br> *1394*, Comm, CCU | `ssh bbs@bbs.comm.ccu.edu.tw` | 密碼: `bbs` |
| 夢之大地 <br> *Dream Land BBS*, NCKU | `ssh bbs@ccns.ncku.edu.tw` `-p 22222` <br> `ssh bbsu@ccns.ncku.edu.tw` `-p 22222` <br> `ssh bbs@ccns.cc` `-p 22222` <br> `ssh bbsu@ccns.cc` `-p 22222` | *未*支援 UTF-8 <br> 校外需用 `-p 22222` 連 port 22222 | 
| 台中一中電研社 極光鯨藍 <br> *Auroral BBS*, TCIRC, TCFSH | `ssh bbs@tcirc.org` | |
| 成功高中 沈澱日記 <br> *Chen Dian Ri Ji*, CKSH | `ssh bbsu@bbs.ckcsc.net -p 25` | |
| 北京大學 <br> *PKU BBS* | `ssh <user>@bbs.pku.edu.cn` | guest 可登入，密碼為空
| 未名空間 <br> *MIT BBS* | `ssh <user>@mitbbs.com` (SSH-1) :unlock: | |
| 水木社區 <br> *Shuimu Community*<sup>[?]</sup> | `ssh <user>@newsmth.org`  <br> `ssh <user>@bbs.newsmth.net` <br> `ssh <user>@bbs.mysmth.net` | |
| 清華大學 大話西遊 <br> *Zixia BBS*, THU | `ssh <user>@wforum.zixia.net` (SSH-1) :unlock: <br> `ssh <user>@bbs.zixia.net` (SSH-1) :unlock: | guest 可登入 |
| 清華大學 聽濤站 <br> *Ting-Tao Zhan*, THU | `ssh <user>@bbs.tingtao.net` (SSH-1) :unlock: |

### WebSocket 連線
**WebSocket Connection**

* 可從改版過的 PttChrome (網頁版) 免安裝體驗\
  Can be browsed by the upgraded PttChrome (webpage version) without installing any dedicated clients.
* 僅列出使用 WebSocket Secure 的站臺\
  Only sites supporting WebSocket Secure connection are listed.

| 站名 <br> Site Name | 位址 <br> Address | PttChrome 網頁版 <br> PttChrome webpage | PttChrome 網頁版版本 <br> Version of PttChrome webpage |
| - | - | - | - |
| 批踢踢實業坊 <br> *Ptt* | [wss://ws.ptt.cc/bbs](wss://ws.ptt.cc/bbs) | <https://term.ptt.cc> | <https://github.com/robertabcd/PttChrome> |
| 批踢踢兔 <br> *Ptt 2* | [wss://ws.ptt2.cc/bbs](wss://ws.ptt2.cc/bbs) | <https://term.ptt2.cc> | <https://github.com/robertabcd/PttChrome> |
| 台大資管 鳴蟬小站 墮落天堂 <br> *Cicadae* (*Tolo Heaven*<sup>[?]</sup>), IM, NTU | [wss://tolo.ntu.im/bbs](wss://tolo.ntu.im/bbs) | <https://tolo.ntu.im> | <https://github.com/robertabcd/PttChrome> |
| 淒美燈塔 <br> *The Pharos BBS* | [wss://bbs.pharos.rocks](wss://wsbbs.pharos.rocks) | <https://bbs.pharos.rocks> | <https://github.com/robertabcd/PttChrome> |
| 夢之大地 <br> *Dream Land BBS*, NCKU | [wss://ws.ccns.ncku.edu.tw/bbs](wss://ws.ccns.ncku.edu.tw/bbs) (支援 IPv6) <br> [wss://ws.ccns.cc/bbs](wss://ws.ccns.cc/bbs) | <https://term.ccns.ncku.edu.tw> <br> <https://term.ccns.cc> | <https://github.com/ccns/PttChrome> |
| 台中一中 龍夢紀元 <br> *Era of Dragon*, TCFSH | [wss://eod.tw/bbs](wss://eod.tw/bbs) <br> [wss://bbs.tcfsh.tc.edu.tw/bbs](wss://bbs.tcfsh.tc.edu.tw/bbs) | |
| 台中一中電研社 極光鯨藍 <br> *Auroral BBS*, TCIRC, TCFSH | [wss://tcirc.org/bbs](wss://tcirc.org/bbs) | | |
| 巴哈姆特 BBS <br> *Bahamut BBS* | [wss://term.gamer.com.tw/bbs](wss://term.gamer.com.tw/bbs) | <https://term.gamer.com.tw> | <https://github.com/robertabcd/PttChrome> |
| 花魁異色館 <br> *Libido BBS* | [wss://libido.malusu.com:8899/bbs](wss://libido.malusu.com:8899/bbs) | <https://libido.malusu.com> | <https://github.com/robertabcd/PttChrome> |
| YKLM大學 <br> *YKLM School* | [wss://yklm.schl.tw/bbs](wss:///yklm.schl.tw/bbs) | <https://yklm.schl.tw> | <https://github.com/yklmbbs/PttChrome> |

## BBS 瀏覽器列表
### BBS Browser List

### Telnet 連線
**Telnet Connection**

* PCMan: http://pcman.ptt.cc
* KKman: http://www.kkbox.com/kkman/
* (macOS) Welly (clyang ver.): https://github.com/clyang/welly

### SSH 連線
**SSH Connection**

* PieTTY: https://sites.google.com/view/pietty-project
* (macOS) Welly (clyang ver.): https://github.com/clyang/welly

### WebSocket 連線
**WebSocket Connection**

* PCMan: https://github.com/pcman-bbs/pcman-windows/releases
* (macOS) Welly (clyang ver.): https://github.com/clyang/welly

### 瀏覽器附加元件版本
**Web Browser Plugins**

* [PttChrome](https://chrome.google.com/webstore/detail/pttchrome/hhnlfapopmaimdlldbknjdgekpgffmbo)
* [BBSFox](https://addons.mozilla.org/zh-TW/firefox/addon/bbsfox/)
    * Firefox 57 版開始無法使用，作者表示還在修改中，完成時間未定：\
      Not compatible with Firefox 57+. The author has announced that the relevant changes are still in progress without a definite finish date.\
      <https://www.ptt.cc/bbs/Browsers/M.1546565629.A.8F5.html>

其他用戶端瀏覽器相關資訊也可至批踢踢實業坊 AppsForBBS 板查詢：\
For more information of BBS browsers, see the board AppsForBBS on Ptt.
<https://www.ptt.cc/bbs/AppsForBBS/index.html>

## 近期修正與補充欄位
### Recent Changes and New Fields

* BBS 站台程式版本，可搭配參考 [BBS 系統譜系圖](#BBS-系統譜系圖)。\
  Server software version of BBS sites. See [BBS Software Genealogy Chart](#BBS-系統譜系圖) for their derivation relation.
    * PttBBS/Ptt current 版號可搭配 [PttBBS 專案的 `UPDATING` 說明文件](https://github.com/ptt/pttbbs/blob/master/UPDATING) 了解其重大差異\
      As for the version number of PttBBS/Ptt current, [the `UPDATING` file from the PttBBS project](https://github.com/ptt/pttbbs/blob/master/UPDATING) can be referred for the major changes.
* 加密連線支援資訊，以 :lock: 標示，可搭配參考[加密連線站台資料列表](#加密連線站台資料列表)。\
  Encrypted connection information, denoted with :lock:. See [Sites with Encrypted Connection](#加密連線站台資料列表) for details.
    * 已將 PttChrome 網頁版程式版本資訊加入 [WebSocket 連線](#WebSocket-連線)站台列表。\
      The version information of PttChrome (webpage version) has been added to the [WebSocket Connection](#WebSocket-連線) List.
* **`twbbs.org`** 網域已經終止服務，故現不附上相關網域資訊\
  The domain-hosting service of **`twbbs.org`** has been terminated. The relevant domain information is not listed here.
* 補充 Web 版網址。以站台資料與 telnet、ssh 等介面的資料同步者為主。\
  The URL to the website version has been added. For these URL to be listed here, the site data should be in sync with the data accessible using the Telnet/SSH/... interface.
* 已將站臺依衍生關係→校名（若有，取全名去稱謂）讀音→站名讀音排序。讀音方面忽略聲調，中國大陸站臺與海外站臺依漢語拼音 Unicode 順序，其它站臺依注音 Unicode 順序。\
  The sites are re-sorted according to their derivation relation → school name (if any, use the full name and ignore the suffix) pronunciation → site name pronunciation. For sorting by pronunciation, the tone is ignored, the Unicode order of the Hanyu Pinyin transliteration is used for Mainland China sites and oversea sites, and the Unicode order of the Zhuyin transliteration is used for the other sites.
* 新增可連數自動加總器。\
  auto-sum-counters for connectable sites have been added.
* 中–英雙語化。\
  The English translation has been added.
    * 英文站名標有 <code><sup>\[?]</sup></code> 者爲非官方非音譯翻譯。\
      English site names with <code><sup>\[?]</sup></code> are unofficial non-transliteration translations.

還請其他熱心人士協助編輯補充 `^_^`\
You can help to improve this article.

## 其它站臺列表資源
### Other References for BBS Site List

* Telnet BBS Guide 所收錄的中文 BBS 站臺\
  The Chinese-language BBS listed in Telnet BBS Guide
    * 包含但不限於 Including but not limited to: <https://www.telnetbbsguide.com/?s=Chinese+Language+BBS>
* 成功大學 CCNS 所提供的站臺 ping 狀態列表\
  The ping status list provided by CCNS from Cheng-Kung University
    * 站點 1 Site 1: <https://smokeping-tanet-tnn-1.ccns.io/smokeping/?target=BBS>
    * 站點 2 Site 2: <https://smokeping-tanet-tnn-2ndsac.ccns.io/smokeping/?target=BBS>

<div class="hide-next-in-jekyll" style="display: none;">
{% raw %}
</div>

{%hackmd @DreamBBS/ch-lang-bbs-genealogy %}

<div style="display: none;">
{% endraw %}
</div>

<details style="display: none;"><summary>Markdown Embedding 筆記嵌入</summary>

<!-- see <https://github.com/jekyll/jekyll-help/issues/51#issuecomment-76543341> -->
{% capture content %}{% include_relative ch-lang-bbs-genealogy.md %}{% endcapture %}
{% assign lines = content | split: "
" %}

{% if lines[0] contains "---" %}
  {% for l in lines %}
    {% if l contains "---" and forloop.first == false %}
      {% assign content = lines | slice: forloop.index, forloop.length | join: "
" %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endif %}
</details>

<div class="hide-next-in-hackmd" style="display: none;"></div>

{{ content }}
  
<div id="end-of-article"></div>

<link rel="stylesheet" href="./ch-lang-bbs-list.css" />

{% raw %}

{%hackmd @DreamBBS/ch-lang-bbs-list-css %}

{% endraw %}
