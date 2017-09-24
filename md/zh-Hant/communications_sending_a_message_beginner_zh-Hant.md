一般 SMS 文字簡訊
===============

SMS 簡訊並沒有良好加密所以你不應只依賴它們來傳送敏感的資訊。送出的 SMS 簡訊可能會被攔截以及被你的電信服務供應商所保留，或是被第三方以不昂貴的設備取得。這些簡訊夾帶著送出者與接收者的電話號碼和訊息本身的內容。更重要的是，SMS　簡訊能被輕易地被第三方竄改。

如果你真的要用 SMS 簡訊，不妨考慮和你的通訊對像之間建立一套密語系統。它可讓你的通訊更為安全也能夠提供一個確認你通訊對像身份識別的方式，密語系統要安全與定期更新。

儲存在手機上的簡訊容易被任何一佪拿到你手機的人讀取內容，所以不妨考慮直接把收到與送出的訊息都刪除掉。

**手機傳送與接收到的一般 SMS 文字簡訊都不夠安全。**

手機安全傳送簡訊
=============

SMSSecure
---------

SMSSecure　是一個免費開源的工具，讓安卓手機可以安全地傳送與接收 SMS 簡訊。它有簡訊加密與未加密模式，所以你可以把它當成主要的簡訊程式。它只消幾秒鐘就可以完成設定，將自動滙入你的聯絡人以及手機上存有的　SMS　簡訊。當傳送或接收　SMS　簡訊時，並不需要網路連線。若要交換加密的簡訊，它必須通訊雙方都安裝了此軟體，因此如果你固定與某人通訊，不妨建議他們也安裝 SMSSecure。SMSSecure 也可以在本機上對所有簡訊進行加密，所以如果不幸手機遺失或被偷，上面的簡訊仍然被好好保護著。

許多之前使用　TextSecure 的用戶現在已改用 SMSSecure　來傳送安全簡訊。

SMSSecure 可從 google play 商店下戴，只要點擊幾個步驟就可完成安裝

從手機上傳送安全簡訊
================

Signal
------

[Signal](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)　是一個免費開源的好用傳送簡訊工具，其可用於點對點之間的簡訊加密傳送以及安全的語音通話。此軟體可於 Androids 和 iPhones　手機上使用，其替代之前的安卓手機應用 TextSecure。( TextSecure 用戶或舊版 Signal　用戶應已收到更新通知或是可以自行到　Playstore/Appstore 安裝更新。)

Signal 現在整合了安全的語音電話軟體 Redphone，所以你不管是用 Android 還是 iPhone，現在可以同時用 Signal 來與對方通話以及傳簡訊。

Signal 利用你的電話號碼以及通訊錄，故無需要額外的登入、用戶名稱、密碼或 PINs 等資訊要管理。以電話號碼作身份識別 (如同一組帳號) 讓使用者容易上手，但這也讓你的通話流量分析與被追踪變得更為容易。Signal 使用一個集中的伺服器，以便於有力地管理掌控一些資料。他們無法知道你的通話內容或是看到你的簡訊，其它第三人也無法取得。

Telegram
----------
Telegram的注意事項：雖然Telegram 在某些模式下也使用點對點加密，但他們的加密能力以及收集用戶資料；數量(如包括完整的通訊錄)卻是讓人擔心。使用者也要記住，在進行\n「安全聊天」\"Secret Chat\"之前，要先開啟加密功能。鍳於在安全通訊方式的考量，我們並不推薦使用 Telegram 來作為安全通訊的工具。

ChatSecure
-----------
[ChatSecure](https://chatsecure.org/) 是 iPhones 和 Androids 以及其它手機系統的跨平台安全簡訊聊天應用程式。 ChatSecure 不只能加密手機間的簡訊傳送，它的跨平台運作以及提供比Signal 更多的功能。ChatSecure 簡單而強固的聊天加密能力提供了通訊者之間的雙重認證(以確信通訊對像是你要找的人)以及每次聊天的獨立安全，所以即更某一次的聊天內容不幸遭到破壞，但不至影響過去或未來聊天通誦的安全。

如何設定使用請見 [ChatSecure 工具指南](umbrella://lesson/chatsecure)

WhatsApp
==========
WhatsApp 最受歡迎的行動通訊工具,它提供跨手機作業平台的免費簡訊傳送與群組聊天服務。過去 WhatsApp 被認為還不夠安全因此不推薦給需要高度安全通訊的使用者，但現在 WhatsApp 已改善其加密強度。

自 2014 年 11 月後， WhatsApp 整合入科技公司 (Open Whisper Systems)的隱私保護安全碼到它的產品上。這表示現在它的訊息受到高度安全認可而且 WhatsApp 也不再輕易地檢視或被迫把這些訊息資訊提供給政府當局。

但我們仍要知道：

- 目前只有安卓手機的使用者才適用加密( Apple iOS、 Windows Phone、 Blackberry and Nokia 的用戶享受同等保障還得稍等一段時間。)
- 只有雙邊個別通訊的簡訊才有進行加密 (例如：群組聊天尚無加密保護)
- 任何被接收的照片也不會被加密
- WhatsApp 公司或其其它人雖然無法檢視你的訊息內容，但他們仍然可知道你的通訊對像(例如利用透過詮釋資料)。有時候這仍然會有不良的安全後果。

基於上述原因我們推薦使用 [Signal](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)來進行安全的簡訊傳送和打電話。

從電腦上安全傳送簡訊
=================

Pidgin
-------
我們建議你在電腦上改採安全、免費、開源的工具 Pidgin 來取代 Skype、Google Talk 或 MSN Messenger。

Pidgin是一款聊天軟體可讓你同步登入多項聊天服務. 這表示你可以利用它同時與MSN、Google Talk 與 Yahoo 等通訊軟體的網友聊天。Pidgin　可運行在　Windows、Linux 以及 UNIX 等作業系統下。

Pidgin 也支援上述相關聊天軟體的各種功能，例如檔案傳送、離線訊息、表情符號與以打字通知等。

Adium
-------
是另一款運行於 Macs 電腦用來替代 Pidgin 的好選擇 [Adium](http://adium.im/)

滑動右側到課程檢查表

### 相關課程與工具
- [TextSecure 工具指南](umbrella://lesson/textsecure)
- [ChatSecure 工具指南](umbrella://lesson/chatsecure)
- [Pidgin 工具指南](umbrella://lesson/pidgin)
- [Adium 工具指南](umbrella://lesson/adium)

### 進階閱讀

- [EFF 電子前鋒基金會 - Communicating with　others](https://ssd.eff.org/en/module/communicating-others)
- [Security in a Box安全工具箱 - Secure communication　guide](https://securityinabox.org/en/guide/secure-communication)
	
