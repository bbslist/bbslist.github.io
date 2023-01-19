---
title: 中文 BBS 系統譜系圖 Chinese-language BBS Genealogy
description: Supplement of <https://hackmd.io/@holishing/r1pdt-59b>
tags: telnet, ssh, BBS, 電子布告欄, TANet BBSes, 華文 BBSes, BBS 分支圖, BBS 系統沿革
---

## BBS 系統譜系圖
### BBS Software Genealogy Chart

此段落編輯鏈結：\
Link for editing this paragraph:\
<https://hackmd.io/@IID/ch-lang-bbs-genealogy>

* 目前收錄的 BBS 系統節點數 Number of currently recorded BBS software nodes (2022-11-17): 143
    * 試探性節點（仍需進一步考證） Tentative nodes (need further investigation): 8

### 譜系圖凡例
**Conventions of the Genealogy Chart**

* 節點格式 Layout format of nodes:
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
  * 事件僅為舉例，會有不完整之處。\
    The listed events are not necessary comprehensive.
    * <code><sup>\[ref]</sup></code>: 可直接參考的資料來源 A link to the reference
    * <code><sup>\[?]</sup></code>: 需補充資料來源 References are needed
  * 受參考系統可能僅表示其功能受參考，不一定代表其原始碼受參考。\
    *Referenced software* only means that its functionalities are referenced but does not necessary mean that its source code is referenced.
    * <code>&dagger;</code>: 暫無法考證的受參考系統 A referenced software which is no longer available for investigation.
  * 可找到原始碼者，於系統名稱與版本處附上存取鏈結。\
    Access URLs are attached to the software name and version if the source code is available.
  * 軟體名與版本後的 <code><sup>\[?]</sup></code> 表示該節點為試探性，具體位置仍需進一步考證。\
    Tentative nodes have <code><sup>\[?]</sup></code> after the software name and version. Their precise genealogy position still needs further investigation.
  * 開發年代主要參考了版權宣告之日期以及程式修改紀錄。以取時間區間之聯集為原則。\
    The development period is inferred from the copyright declaration and the modification history of the source code. The union of both period is taken if no further evidences are available.
    * `n.d.`: 年代暫無法考證 No date available
  * 歷史代表站臺以有官方性質且為非個人站臺者優先。\
    If multiple sites are regarded as official, the most authoritative non-personal one is taken as the official site.
    * 最近祖節點相同的同一系統不同版本的歷史代表站臺相同時，只在其中最早版本上標出歷史代表站臺。\
      For multiple versions of the same software with the same most recent ancestor node, the official site is only listed on the earliest node.
    * `N.A.`: 代表站臺暫無法考證 The official site is not available to investigate.
* 分支以每橫行最多一節點的（無環）樹狀圖表示。\
  Branch relation is represented by a(n) (acyclic) tree graph where every node occupies its own row.
  * 同系列的不同版本與其間的事件，若無分支，則併為一緊密縱列，順序由上而下；若有分支，則所有直接子分支縮進在同一縱列。\
    For multiple versions of a software series and the events in-between, their nodes are connected and have the same indentation level if there are no branches, otherwise the immediate children nodes simply have the same indentation level.
    * 緊密縱列內，事件內具有括起的版本或時間的話，則明確表示事件發生在上方版本之中。\
      For connected nodes with the same indentation level, an event with parenthesized version or date appended denotes that the event happened during the immediately preceding version node.
  * 分支由上而下的排列順序：較早分支→較晚分支。\
    Vertical layout order of branches: The one branched off earlier → the one branched off later.
  * 分支早晚順序待考證或過於接近者，暫時以其在既有譜系圖中的位置為主，以隨意指定的順序為輔。\
    If the dates of branching off still need investigation or is too near with each other for some nodes, their order in previous genealogy charts is taken if they even appeared, otherwise an arbitrary order is assigned.
  * 由原開發團隊開發或採用的直接子分支，以分支圖上的雙橫線表示。\
    Immediate children branches developed or adopted by the original development team are denoted with doubly-lined horizontal relation line.
  * 有多個候選根節點時，以初分支時成分最大的或在譜系上最早出現的節點為實際根節點，其它候選節點則列於受參考系統。\
    If there are multiple reasonable candidates for the root node, the one having the most significant influence when the software branched off or being listed earliest on the genealogy chart is taken as the root node and the other candidates are listed as referenced software.
* 圖中列出的系統，其**未受參考的葉節點**應符合以下所有條件：\
  For a listed software, a **non-referenced leaf node** of it should fulfill the following preconditions:
  * 可確定其軟體名稱與譜系位置。\
    Its software name and genealogy position can be determined.
    * 需有伺服器主程式原始碼或參考文獻。\
      Either the source code of the main program of the server or a reference is needed.
    * 僅知站名而不知軟體名者：\
      When only its site name but not the software name is known:
      * 有原始碼者，依英文簡寫站名作為軟體名列入。\
        If the source code is available, it is listed here with the English acronym of the site name taken as the software name.
      * 無原始碼者，不列入。\
        If no source codes are available, it is not listed here.
  * 具有終端機文字介面且具有閱讀與發表文章之功能。\
    It provides a text-terminal&ndash;based interface and has the functionalities of browsing and posting articles.
    * 不可考察代表站臺，而僅能考察其伺服器主程式原始碼者，須已實作上述功能。\
      For official sites no longer online but having the source code available, the above functionalities needed to be implemented in the code.
  * 針對中文使用者設計。\
    Designed for Chinese-language users.
  * ※ 有多個子分支的節點與已受參考的葉節點不受上述條件限制。\
    ※ Nodes with multiple descendant branches and referenced leaf nodes are excepted from the above preconditions.

### 譜系圖
**Genealogy Chart**

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
&nbsp;         │           │      (+ SOB BBS (gem .DIR))
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
&nbsp;         │           ├──(+ MapleBBS 2.39&ndash;3.00 1996)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/es_EPEQTvy4/m/SOhQyEtm5iwJ)]</sup>
&nbsp;         │           │   SunOfBeach BBS (SOB BBS) 0.22  1996  臺灣大學  陽光沙灘
&nbsp;         │           │   ├──(! bhttpd (Web UI))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/iRD0Cor13YM/m/dKh4qol8LkcJ)]</sup>
&nbsp;         │           │   │   SOB-Leeym  n.d.  成大土木  大地雕塑家
&nbsp;         │           │   ├── Forest BBS<sup>\[?]</sup>  n.d.  中原資管  森林站<sup>\[?]</sup>
&nbsp;         │           │   ├──(+ FireBird BBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bp0ZpSPflHM)]</sup>
&nbsp;         │           │   │   ForestV BBS  n.d.  政治大學  月光森林
&nbsp;         │           │   ├── [FHLBBS](https://ftp.fhl.net/FHL/BBS/)  1996&ndash;2004  信望愛BBS站
&nbsp;         │           │   ╘══(+ gem .DIR (1996-09-10))<sup>\[[ref](https://www.ptt.cc/man/SetupBBS/DC13/DEEE/M.908117798.A.html)]</sup>
&nbsp;         │           │      (! Copyleft ($) (<= 1996-10-08))
&nbsp;         │           │       SOB on FreeBSD<sup>\[?]</sup>  n.d.
&nbsp;         │           │       ╞══(+ MapleBBS 3.00 1996 (mbbsd, visio) (1996-11-16))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bDlffmTSjT8/m/1iRg6wQzLMoJ)]</sup>
&nbsp;         │           │       │   ╞══ SOB mbbsd SunOS Plug&Play<sup>\[?]</sup>  1996  N.A.
&nbsp;         │           │       │   ╞══(! maple/buggy.c)
&nbsp;         │           │       │   │   SOB-fromzero (SOB 3.0)  n.d.  臺大電機  從零開始
&nbsp;         │           │       │   │   SOB domi  n.d.  糟了！誤上賊船
&nbsp;         │           │       │   │   └──(+ MapleBBS-itoc, ATS BBS)<sup>\[[ref](https://www.ptt.cc/bbs/SetupBBS/M.1058724092.A.html)]</sup>
&nbsp;         │           │       │   │       [SOB-PACK](https://github.com/bbsmirror/BBSmirror/blob/master/SOB/sob_rfc2047.tar.gz)  2003  N.A.
&nbsp;         │           │       │   ├── [Atlantis BBS (ATS BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/Atlantis)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bEHu_OfxYjw)]</sup>  1996&ndash;n.d.  亞特蘭提斯＊
&nbsp;         │           │       │   │   (+ MapleBBS 3.0x (DAO lib.), 3.10 (shared libs))
&nbsp;         │           │       │   │   (! emulated sub-sites (1.20))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/bEHu_OfxYjw)]</sup>
&nbsp;         │           │       │   │   (+ WD BBS 2.9, PttBBS (games) (1.31))
&nbsp;         │           │       │   ├── NaiveAge BBS<sup>\[[ref](http://www.ncu.edu.tw/~w3meng/train90s/900820_ArGuo-BBS/NaiveAge-BBS_Install.doc)]</sup>  n.d.  中央機械  純真年代
&nbsp;         │           │       │   ├──(+ SOB-Leeym (bhttpf -> TKU-PRO BBSD))
&nbsp;         │           │       │   │   PeRsOnal BBS (PRO BBS)<sup>\[[ref](https://www.ptt.cc/man/SetupBBS/D389/M.913695634.A.html)]</sup>  1997&ndash;1998  淡江大學  蛋捲個人站
&nbsp;         │           │       │   └──(+ MapleBBS 3.0x (DAO lib.), 3.10 (shared libs))
&nbsp;         │           │       │       [Purple Garden BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/fpgsrc.tgz) (FPG BBS)  1998&ndash;1999  臺灣法律  小魚的紫色花園
&nbsp;         │           │       ├── [sob-ptt BBS 0.00](https://www.ptt.cc/man/SetupBBS/DC13/index.html)  1996  臺灣大學  批踢踢實業坊＊
&nbsp;         │           │       │   Ptt BBS 0.001  1996&ndash;2000  臺灣大學  批踢踢實業坊＊
&nbsp;         │           │       │  (! 2-space Allman -> 4-space K\&R (partially); + SOB on FreeBSD (mbbsd))
&nbsp;         │           │       │   ╞══ Ptt BBS (for Linux) [0.9.2](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttsrc-0.9.2.tar.gz)&ndash;[1.0.0](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.0.tar.gz) ([archived](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt))  2000
&nbsp;         │           │       │   │   ├── [saloon BBS](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/branch/saloon/saloonsrc.tgz)  2001  政治大學  煮酒論英雄
&nbsp;         │           │       │   │   ╞══ [Open Ptt](https://github.com/bbsmirror/openptt) (Ptt BBS [1.0.1](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.1.tar.gz)&ndash;[1.0.2](https://github.com/bbsmirror/BBSmirror/blob/master/Ptt/openptt/pttbbs-1.0.2.tar.gz))  2001
&nbsp;         │           │       │   │   ╘══(! x86_64-compat)
&nbsp;         │           │       │   │       [Ptt BBS Current](https://github.com/ptt/pttbbs)  2003&ndash;2014<sup>\[?]</sup>
&nbsp;         │           │       │   │       ├── [pttbbs-henry](https://github.com/alextwl/pttbbs-henry)  2006&ndash;2015  暨大資工  霞蔚山城
&nbsp;         │           │       │   │       ╘══ [Ptt BBS Current (git-only)](https://github.com/ptt/pttbbs)  2014&ndash;2022
&nbsp;         │           │       │   │           └── [BRsBBS](https://github.com/BunnyBBS/BRsBBS)  2018&ndash;2022  BunnyBBS
&nbsp;         │           │       │   └── PttFreeBSD<sup>\[?]</sup>  1998  風與塵埃的對話
&nbsp;         │           │       │      (+ MapleBBS 3.0x (DAO lib., HDR struct.), 3.10 (shared libs))
&nbsp;         │           │       │       Wind & Dust BBS (WD BBS) 1.34  1999  風與塵埃的對話＊
&nbsp;         │           │       │       ╞══(+ MapleBBS 2.39)
&nbsp;         │           │       │       │   [WD BBS 2.3](https://github.com/bbsmirror/BBSmirror/tree/master/WD/tarball)  1999
&nbsp;         │           │       │       │   ├── [WD-BBS 2.3-SSSH (PR BBS)](https://github.com/bbsmirror/BBSmirror/blob/master/WD/branches/PR_001206_SNAP.tgz)  2000  松山高中  松江水綠
&nbsp;         │           │       │       │   │   ╘══ Athenaeum BBS<sup>\[?]</sup>  1999<sup>\[?]</sup>&ndash;n.d.  建中資訊社  雅典娜
&nbsp;         │           │       │       │   │       ╞══ [Athena BBS (AT-BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/Athena/AT) v1.1.1  1999<sup>\[?]</sup>&ndash;2002
&nbsp;         │           │       │       │   │       │   │   建中資訊社  雅典娜
&nbsp;         │           │       │       │   │       │   ╞══ [AT-BBS-Pure](https://github.com/bbsmirror/BBSmirror/blob/master/Athena/AT/AT-BBS-Pure-0.1.1.tgz)  2002  建中資訊社  N.A.
&nbsp;         │           │       │       │   │       │   ╘══ AT-BBS  2002
&nbsp;         │           │       │       │   │       │      (! rename project folders (1.5.1))
&nbsp;         │           │       │       │   │       │      (+ MapleBBS 3.0x ("WD-visio") (1.5.1))
&nbsp;         │           │       │       │   │       ╞══ WD BBS 2.9<sup>\[?]</sup>  2000&ndash;2010<sup>\[?]</sup>
&nbsp;         │           │       │       │   │       │   ╞══(! renamed by original dev. team)
&nbsp;         │           │       │       │   │       │   │  (+ WD BBS, exbbs, MapleBBS 3.10-itoc, AT-BBS)<sup>\[[ref](https://github.com/hialan/hialanBBS/blob/master/src/doc/CHANGES)]</sup>
&nbsp;         │           │       │       │   │       │   │  (+ myth BBS&dagger;, PttBBS)<sup>\[[ref](https://www.ptt.cc/bbs/SetupBBS/M.1105470062.A.html)]</sup>
&nbsp;         │           │       │       │   │       │   │   [WD_hialan BBS (AT3-BBS) (AT-BBS v2)](https://github.com/hialan/hialanBBS)<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/TPeEm84denQ)]</sup> ([archived](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/hialan))<sup>\[[ref](https://groups.google.com/g/tw.bbs.admin.installbbs/c/iFMcpSVSOZM)]</sup>  2002&ndash;2017
&nbsp;         │           │       │       │   │       │   │       建中資訊社  威尼斯咖啡館
&nbsp;         │           │       │       │   │       │   └── [CCUMATH-BBS](https://github.com/jcppkkk/MapleBBS-3.00)  n.d.&ndash;2013  中正大學  無數不學
&nbsp;         │           │       │       │   │       ╘══(! refactored (C++), support Windows NT)
&nbsp;         │           │       │       │   │           [EdenBBS v0.5](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/Eden)  2001  建中資訊社  兩光的兩光小站
&nbsp;         │           │       │       │   ├── [exbbs](https://github.com/bbsmirror/BBSmirror/tree/master/WD/branches/exbbs)  2001  宜蘭技院  紅樓頂尖 BBS
&nbsp;         │           │       │       │   ╘══ [Pure WD BBS (WD-P BBS)](https://github.com/bbsmirror/BBSmirror/blob/master/WD/tarball/wd_pure_snap_linux.tgz)  2002  風與塵埃的對話-空無一物版
&nbsp;         │           │       │       └──(+ PttBBS, FPG BBS)<sup>\[[ref](https://www.ptt.cc/man/SetupBBS/DAAD/M.939173101.A.html)]</sup>
&nbsp;         │           │       │          (+ MapleBBS 3.0x ("WD-visio" &mdash; io+term+screen-stuff) (20000619))
&nbsp;         │           │       │           [StarRiver BBS (Star BBS)](https://github.com/bbsmirror/BBSmirror/tree/master/StarVersion)  2000&ndash;2002  輔仁大學  星河夜話
&nbsp;         │           │       ├── Oldest future Object BBS (OfO)  1997&ndash;n.d.  臺灣大學  未來最舊小棧
&nbsp;         │           │       └── Wind's Top BBS (WindTop BBS) (wind BBS) [2.2](https://github.com/bbsmirror/BBSmirror/blob/master/Maple/Maple2/branch/Wind/wind1101.tgz)&ndash;[2.4](https://github.com/bbsmirror/BBSmirror/blob/master/WindTop/old/WindTopBBS-19991229-V2.4.tgz)  1998&ndash;1999
&nbsp;         │           │               元智大學  風之塔＊
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
**Recent Changes to the Genealogy Chart**

* 初步增加事件節點。「請支援考察。」
    * 尚待確定適當的詳細程度。
    * 暫時未將事件節點的參考鏈結整理進參考資料。
* 將連續未分支同系節點併為一縱列。
* 顯著調整部份譜系的呈現。
    * WindTop BBS 3 系列，根節點從 WindTop BBS 2.x 改至新節點 MapleBBS 3.05。
    * Pivot/Feeling BBS 系列，改名前最後共同祖節點從 5.8 改至 5.9b4。
    * WD BBS 系列，補充中間節點，並將 2.9 版分支之根節點改至新節點 Athenaeum BBS。
    * 前移較早期或時代待考證的 SOB BBS 系列的位置；OfO BBS 與 WindTop BBS 2 改置於較後期的 SOB BBS 系列。
- 試探性地加入新分支節點。需進一步驗證。
    * Train BBS，設為 Train BBS 後繼版本與 WindTop BBS 3 系列之祖節點。內部參考關係待釐清。
        * 與 M3-WindTop 間無直接分支關係。
    * PttFreeBSD，設為 WD BBS 系列之祖節點。有無其它分支仍待考察。
    * SOB on FreeBSD，暫設為較後期的 SOB BBS 的祖節點。是否僅為某版本別稱仍待驗證。或可改以 SOB BBS 之某日期版本表示。
        * 暫以是否實作 .DIR 精華區為定位依據。
    * Athenaeum BBS，暫設為建中資訊社之 WD BBS 衍生系統的祖節點。子節點仍待驗證。或可改以 Athena BBS 之某具體前期版本表示。
        * AT2-BBS 非其子分支。
    * MapleBBS 3.05，設為 WindTop BBS 3 系列與 MapleBBS 3.10 之最後共同祖節點，視為 MapleBBS 3.10 之早期版本。見於早期 WindTop BBS 3 原始碼 `include/config.h`。
* 將機構名與站名改放到開發年代後。
* 初步建立是否列入某軟體的準則。

### 譜系圖研究方法
**Research Methodology of the Genealogy Chart**

* 以現有譜系圖為藍本，並進行交叉驗證。
* 參考軟體原始碼的版本資訊（注意有時可能有編輯錯誤，需交叉參考相關軟體）：
    * 常位於 `install.files/`, `config/`, `bbshome/`, `example/`, `sample/bbs/`, 或 `etc/`
    * 常名為 `Version.info`, `Version`, 或 `info`
* 整理同一系列之祖先軟體和／或其衍生軟體之具特異性的共同特徵，驗證現有譜系圖。
* 未有版本資訊的軟體，依其軟體特徵與修改時間，佐以過去文獻，判斷其譜系位置。
* 不一致時，參考資料來源的優先順序：原始碼 > 代表站臺之軟體功能 > 主要開發團隊與他人引用，開發時期 > 開發團隊回憶與他人引用 > 開發團隊，他人轉述 > 他人，開發時期 > 他人回憶
* 代表站臺的確定，以文獻資料為主，以原始碼中的預設設定檔為輔。

### 譜系圖參考資料
**References of the Genealogy Chart**

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

### 相關非中文 BBS 站臺
**Relevant non&ndash;Chinese-language BBS sites**

* 此處可連線狀態不納入統計\
  The connectable status below is excluded from the number of connectable sites.

<div class="bbslist excluded">

| 可連&nbsp;&nbsp; <br> Con. | 站名 <br> Site Name | 位址 <br> Address | BBS 版本 <br> BBS Software Version | 備註 <br> Notes |
| - | - | - | - | - |
| :white_check_mark: | Eagle's Nest | `ssh bbs@bbs.wq5l.net` :lock: <br> `ssh bbs@nest.wq5l.net` :lock: | [Eagles BBS 3.1.4-rc2](https://wq5l.net/ebbs/) | (1992-04-14 開站 Est. 1992-04-14) |

</div>