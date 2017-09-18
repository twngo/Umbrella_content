如何對付線上審查
============

許多政府、公司、學校與公共網路使用區都透過一些軟體來阻止使用者連上某一些網站或網路服務。這樣稱之為網路過濾或是封鎖，也被視為網路審查的一種。內容過濾來自不同的形式，有時整個網站都被封鎖有的只是包含某些關鍵字的內容被過濾。某個國家或許會封鎖了整個臉書網站，有些則是封鎖臉書上部份的社群小組或是含有某些字眼的網頁內容。

![](internetb1.png)

不管其內容是如何被過濾封鎖，你只有透過一些對付工具才能取得資訊。對付因應的工具往往透過分散你的網路或透過其它電腦的繞行交通，以躲避執行審查的機器。

現有許多對付網路審查的工具，有些提供多出來的安全層帶供你使用。這樣的工具最適合受到威脅的用戶，如果你不確定你受到威脅的模式是哪些，你可以透過[管理資訊](umbrella://lesson/managing-information)課程來了解。受到高度威脅的使用者需要完整的線上匿名方式，可以參考本課程進階部份的介紹

HTTPS
======
HTTPS 是 HTTP 通訊協議的安全版本。有時候審查者只會封鎖網站的一般非安全網址，這讓我們可以造訪它以 HTTPS 為開頭的安全網址。尤其在遇到關鍵字過濾或只封鎖部份網頁時，這招格外有效。 HTTPS 阻止審查者讀取你的瀏網交通資訊，所以他們無法知道你送出了什麼關鍵字的查詢或是造訪某些特定的網頁 (然而審查者仍然可以看到你造訪過的網址資訊)。

![](internetb2.png)

如果你懷疑有這類簡單的封鎖，試試在網址列打入 https:// 取代 http://

試試電子前鋒基金會 EFF　的 [HTTPS Everywhere](ttps://www.eff.org/https-everywhere\) 這是一個瀏覧器外掛可以自動地把網址轉向有支援 HTTPS 的網站。

網站差異
=======
另一個躲避線上審查的基本方法是試圖找另一個替代的網域名或網址。以推特為例，你可以造訪它的行動網址 http://m.twitter.com 來取代 http://twitter.com。審查者封鎖網站或網頁往往依照被禁止的黑名單資料，所以不在名單上的網址或許可以躲過一劫，因為他們並不知道某一個特定網站有其它不同的網域名稱，尤其是因為遭封鎖而註冊了其它的網域名。

網頁代理
========

網頁代理（例如 [https://proxy.org](https://proxy.org/)）是最簡單對付審的方式之一。它是由網站讓用戶可以近用其它遭到封鎖的網址。使用網頁代理，你只需在其網頁上的輸入框打上被過濾的網址，代理器就會在網頁上呈現出你要求的內容。
![](internetb3.png)

網頁代理器是一個快速近用封鎖網站的好方法，但是它也有一些缺點：
- 它住往無法提供安全保密，如果你的網路行為受到監控的威脅，這就不是一個好的選項
- 有時這個工具也無法提供你要求的正確網頁內容，許多網頁代理無法承載複雜的網站，像是有影音內容的網站
- 如其名稱所示網頁代理由能提供網站服務，你無法利用它來使用即時通訊或是電子郵件程式
- 最後，網頁代理本身也給使用者帶來一些風險，因為代理器會全程記錄你的瀏網行為

有一些代理服務使用了加密功能可以提供多一層的安全防護以及躲避過濾。雖然它的連線有加密但是服務提供者仍然保有你的網路資料，這意謂著它並不是匿名。不管如何，這總是稍比一般性的網頁代理更為安全。最簡單形式的加密網頁代理是透過使\"https\"開頭的網址，它的網站會使用加密通訊

虛擬私人網路
===========

虛擬私人網路 (VPN)會在你的電腦與其它電腦之間進行加密與傳送。這個電腦可以是商用或是非營利, 或是由你的公司或是一個信賴者所架設的 VPN 服務。代理伺服器只有網頁交通功能，但是 VPN 可以加密和保護通訊內容。主要的差異就在 VPN 伺服器可以加密資料，而代理器則不能。VPN 也可以讓你方使使用更多網路資源 ，例如透過它讀取網頁、電子郵件、即時通訊、網路電話等種種服務。 
![](internetb4.png)

Psiphon3
----------
Psiphon3 是一個安全公共的躲避工具，它結合了 VPN、SSH 和 HTTP 代理技術，提供不受審查地近用網路內容。其有 Windows 與 Android 版本可供免費下載。可在 [Psiphon3 工具指南](umbrella://lesson/psiphon)學習如何使用。

Psiphon 3 是一個以　VPN　為基礎的工具，它能夠代理你所有的網路交流，不只限於網頁瀏覧。但要注意的是， Psiphon3 不能讓個別用戶的 IP 位置與任何訪問過的網路產生關聯，Psiphon 是為了進行審查躲避而不是匿名。

其它 VPN 服務的資訊以及了解找出適合你的工具，請到[此處](http://torrentfreak.com/which-vpn-services-take-your-anonymity-seriously-2014-edition-140315)。不要使用你不信任的 VPN。

VPN 透過本機上的加密保護你的使用記錄，但是 VPN 提供者仍然可以保留你訪問過的網站活動記錄甚致將其提供給第三方以直接窺探你的瀏覧歷史.依照你受威脅模式的程度，政府很可能監聽或是取得你的 VPN 記錄，這將是很大的風險。這些人則只看重使用 VPN 的短期好處。需要全程匿名的使用者，應該用 Tor，相關的介紹可在本課程進階部份找到。

從智慧手機上躲避審查
==================
使用智慧手機上網往往比用電腦更加危險。你可以利用下列方法來降低手機的風險

使用手機 VPN 可讓你自由地近用網路資源且加密你的活動，我們推薦 Psiphon 3。如前所述，它可以運行在 Androids 以及Windows系統下。

高危險的使用者需要確保網路上全程的匿名，可參考本課程進階訊部份的介紹。

代理
----

在手機上使用代理器可讓你造訪遭到封鎖的網站。你可以下載手機版本的火狐瀏覧器來使用代理 [Firefox mobile](http://f-droid.org/repository/browse/?fdid=org.mozilla.firefox)</a> 以及 [Proxy Mobile](https://guardianproject.info/apps/proxymob-firefox-add-on/) 它是一個火狐的外掛程式，可輕易地協助對付審查。然而這種方式如果代理與你的電腦之間沒進行加密，仍然或揭露出你送出的請求內容，這個工具可以用在 Androids 與 iPhones。

私人虛擬網路 (VPN)
------------------
手機使用 VPN 可讓你不受限地讀取網路內容也會加密你的活動。我們建議使用 [Psiphon3](umbrella://lesson/psiphon)，它同樣可安裝在 Android。

面臨高度威脅的用戶需要確保網路全程匿名的狀態，其應該參考本課程的進階部份。

滑動右側到課程檢查表

到進階課程了解如何碓保你維持線上匿名狀態。

[進階課程](umbrella://lesson/the-internet/1){.button
.yellow}

### 相關課程與工具

- [管理資訊](umbrella://lesson/managing-information)
- [Psiphon3 tool guid](umbrella://lesson/psiphon)
- [行動代理工具指南](umbrella://lesson/proxy-mobile)

### 進階閱讀
- [EFF - How to circumvent online censorship](https://ssd.eff.org/en/module/how-circumvent-online-censorship)
- [FlossBypassing censorship](https://en.flossmanuals.net/bypassing-censorship/)
- [OpenNet - Outlining internet restrictions](https://opennet.net)
	