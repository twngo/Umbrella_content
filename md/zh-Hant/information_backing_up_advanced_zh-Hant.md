為何備份？
=========

備份是複製與整理電腦上的資料，當意外發生時可以將其重新回復到原先的狀態。例如多年的工作資料可能因為遭小偷、被沒收或壞掉而消失，因此保有最新的備份且能好好地復原重建就很重要。

建立有效的備份政策有時可能並不容易：
- 原始資料和備份資料需要放在不同的物理空間
- 保持備份資料的隱密
- 資料共享者之間的協調，因為其可能會使用自己的儲存設備。

除了備份與檔案復原的技巧，本課程也特別介紹二個工具，Cobian Backup 與 Recuva。

識別與組織資訊
=============

執行備份政策的第一步是要先知道目前你所有的個人與工作資訊放在什麼地方，這可能包括：
- 郵件伺服器上或自己電腦中所儲存的電子郵件
- 可能放在家裏或辦公室的文件、聯絡簿、電腦上的聊天記錄
- 儲在 USB 記憶卡, 隨身硬碟或 CDs 上的資訊
- 手機上的連絡人以及重要的簡訊資料
- 你的網站上包含的重要資訊或是工作收集品
- 別忘了一些非數位的資訊，例如紙本筆記、日記、信件等等。

再來，你需要整理出哪一些檔案是主要原件，哪一些要複製檔。主要原件是指最新版本的檔案也是你要備份的資料。

你應該整理出一張表格來列出上面你所辨識的資訊類別，並註記：
- 這些資訊是否為主原件還是複製檔
- 檔案是否存在這個設備上
- 這些設備通常放置的地方

這個表單可以幫助你看清哪一些資訊 (主原件) 只存放在一個位置以及它的重要性
![image](backing1.png)

你的備份策略
===========

要備份上述的資料類型，你會需要一套綜合的軟體和程序。基本上你得確認每一類資料至少有存放在兩個不同的地點。

- **電子文件：**使用如 Cobian Backup 的工具來備份電腦上所有的文件，這個我們會在底下做更完整的介紹。把備份檔案存在一個行動設備上以便把它帶回家或是送到其它安全的地方，如外接硬碟、CD/DVDs、USB、記憶卡都是選項，由於這類的資料往往涉及敏感，所以電子文件的備份最好進行加密。你可以在[保護檔案](umbrella://lesson/protecting-files)課程以及 [TrueCrypt 工具指南](umbrella://lesson/truecrypt)中找到如何操作
- **程式資料庫：**如果你使中用日曆軟體或是電子通訊錄，將要找出其軟體存放資料的目錄。一旦你刪除這些應用軟體的資料庫，你才可以把它們備份成某種電子文件。
- **Email：**最好用電子郵軟體如雷鳥設定讀取電郵而不是透過網頁瀏覽器。[Thunderbird工具指南](umbrella://lesson/thunderbird)有介紹。大多數的網頁電子郵件服務都有提供如何使用電子郵件軟體的滙入設定指示，如果因安全考慮，選擇要把信件移到電腦上好讓伺服器不在存有這些資訊，請確認包括前述的電子文件備份。
- **手機資料：**備份手機上的號碼和簡訊，可以用合適的軟體連接電腦與手機來進行,這些軟體通常可以在手機製造商的網站上下載.你可能需要有特別的傳輸線來進行備份連接。
- **紙本文件：**可能的話，你應該把掃描所有重要的文件然後把它們和上述的其它電子文件設備上一起進行備份。

儲存設備
========

在備份資料之前，必須先決定要使用何種儲存設備

- **USB 記憶卡或是外接式硬碟：**它們不貴容量大且容易多次覆寫。USB 隨身碟的使用壽命大約是十年，比外接式硬碟要久一點
- **CDs光碟片：**  CDs 大約能存 700 Megabytes (MB)的資料。你還需要一個燒錄器和空白光碟片，如果要刪除光碟與更新裏面的內容，就必須使用可重覆讀寫燒錄器和可覆寫光碟。所有主要的作業系統，包括Windows XP，都有內建的光碟燒錄軟體以刻製光碟片，這些光碟片大約能保存 5~10 年然後就會開始劣化。
- **DVDs：**DVDs 大約能儲存 4.7 Gigabytes (GB) 資料。就如同 CDs，DVD 或 DVD-RW 燒錄器稍貴一點，其保存時限也和 CD 差不多，最後資料終將消失。
- **Remote server：**一個良好維持的網路備份伺服器可能會無限制的容量,但其速度和穩定性以及網路連線品質將決定其是否為理想的選擇 .記住要在自家辦公室運行備份伺服器會遠比把資料複制到網路上要快許多,但違背了要把重要資料存成二份複本以放在不同的地方。現在有許多免費的網路儲存服務，但你要小心考慮把資料放到網路上的風險且最好在上傳之前先進行加密，尤其是那些你並不認識的伺服器管理商。
![image](deleting2.png)
		

備份軟體
========

Cobian Backup 是一個使用者友善的工具軟體可以設定為定期自動執行備分，包括只備份距上次備份後有所變動更新的檔案，它能壓縮備份包讓其不佔空間。可以在 [Cobian Backup](umbrella://lesson/cobian-backup) 工具指南中學習如何安裝使用

使用備份工具時，有幾件事可以協助你讓備份工作更順利：
- 整理好電腦上的檔案，試著把要備份的資料夾和電子文件放到同一個位置，像是「我的文件」目錄下。
- 如果應用程式把資料存在其程式资料庫中，你得先找出這些資料庫的位置，如果它不是在一般的位置，查查看是否這個程式可以讓你選擇把資料庫移到其它位置。如果可以，就把它們一併放在要備份文件的同一資料夾下。
- 定期排程來執行備份
- 讓辦公室所有同仁都建立一套定期、可靠、安全的備份措施和程序，協助同仁了解此議題的重要性。
- 先測試著從備份檔案中重建回復資料，記住重要的是最後的重建恢復目標才是比備份過程更令人真正關心的！

一旦你備份好了資料或是建立了一套程序，你需要去知道一處安全儲存的位置。記住它得和原始資料存放在不同的位置！(如果辦公室的備份檔案存在記憶卡上，那麼這支記憶卡就不要放在辦公室裏)

意外地檔案刪除

當刪除電腦的檔案時，它通常只是從檢視中消失但其內容仍然實際存在。即便你也清空了資源回收筒，你所刪除的檔案其資訊仍然可在硬碟中找到。請見「檔案刪除」課程了解詳情。如果你意外地刪除了重要的檔案或資料夾，原本安全上的弱點可能反而成為優勢。有一些軟體程式可以重建最近被刪除的檔案，包括一個叫作 [Recuva -檔案回復](umbrella://lesson/recuva)的工具，你可在本書工具指南中找到其介紹。

在電腦上刪除檔案以及重建的動作最好少做。當要在很長一段時間後才重建檔案，其成功的機會就越小。這也意謂著你在刪完檔案後，最好使用隨身版的 Recuva 而不是安裝版。(或是最好在任何事之前先安裝好它！)

本章看來似乎有許多工作要做和學習的工具，好讓備份策略落實。但一旦當你的系統到位第一次的設定並不困難，而且備份工作可能是資料安全中最要緊的事，當走一遍後你可以確定它是值得花力氣且能安心休息。

滑動右側到課程檢查表

### 相關課程與工具<

- [保護檔案課程](umbrella://lesson/protecting-files)
- [刪除課程](umbrella://lesson/safely-deleting)
- [TrueCrypt 工具指南](umbrella://lesson/truecrpyt)
- [Thunderbird　雷鳥工具指南](umbrella://lesson/thunderbird)
- [Cobian　備份工具指南](umbrella://lesson/cobian-backup)
- [Recuva 檔案復原工具指南](umbrella://lesson/recuva)

### 進一步閱讀<
- [Security in a Box - Chapter 6, Backing up](https://securityinabox.org/chapter-6)
