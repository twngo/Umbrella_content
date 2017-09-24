什麼是 PGP ？
====

如果你遭到來自政府或是執法機關的威脅，或是你有一些原因要確保電子郵件服務的提供商不能把你的電郵通訊內容提供給第三方，你或許要考慮在電子信箱中使用末端之間加密。末端加密是一種讓資料傳輸時不受打擾的保護方式。
![image](email3)

PGP 正是一種標準的末端間電子郵件加密方式。PGP 代表 Pretty Good Privacy。它的確是良好的隱私工具，如果正確使用，它可以保護你訊息，文件甚致是檔案被國家資源雄厚的監控項目所截取知悉 

## 公鑰加密

PGP 建構在公鑰加密的概念上，這個加密系統使用二支鑰匙 - 一支是任何人皆可取得的公鑰，另一支是唯有訊息收件者才有私鑰。例如張三要傳送一則私密的訊息給李四，張三利用李四的公鑰來加密這則訊息，然後李四在收到這則加密訊息後用自己的秘鑰來進行解密

- 因此公鑰加密是讓你安全傳送訊息給已知其公鑰的收件人
- 如果別人有你的公鑰資料，他們可以利用它傳送給你唯有你可解密讀取的私密訊息
- 如果有人知道你的公鑰，你也可以簽署自己的訊息，這樣對方就知道訊息的來源
- 如果你知道某人的公鑰，你可以解密他們簽署的訊息，因此知道這的確是來自對方的訊息

你應把私鑰存在一個安全的地方，並使用一組長串的密碼加以保護(如果某人取得你的私鑰複本，他們可以偽裝成你，然後以你的名義簽署傳送不實訊息)你可以把公鑰提供給要連絡通訊的對像，或是那些想知道某些加密訊息是否真來自你所傳送的收件人。

### 使用PGP
不幸的是，PGP　被一般人認為難以理解或使用。現在好消息是，有越來越多的應用程式可以把複雜的 PGP 應用包裝起來，讓使用更容易操作，例如在加密與證實電子郵件上，主要就是 PGP 的應用</p><p>如何在電子郵件中使用 PGP，請見下方進一步詳細的說明
- [How to: Use PGP for Mac OS X](umbrella://lesson/pgp-for-mac-os-x)
- [How to: Use PGP for Windows](umbrella://lesson/pgp-for-windows)
- [How to: Use PGP for Linux](umbrella://lesson/pgp-for-linux)

保存你的 PGP 秘鑰在手機上可能有風險，但它的好處是可以在移動設備上傳送與儲存加密電郵。學習如何在智慧型手機上安裝使用電子郵件加密工具[K9 and APG Guide](umbrella://lesson/k9-&-apg)

PGP 不能作什麼？詮釋資料
====

PGP 作的是確保訊息內容的加密不受竄改.但這不是你唯一要擔心的隱私問題。PGP 無法保護你的詮釋資料，它們是內容之外的其它資料，包括電郵主旨，何時與何人通訊。這些資料可以大量地曝露你的身份即便你的通訊內容仍然保持私密。

如果你和某一位著名的異議者進行了 PGP 加密通訊，你也許將只因和他們通訊而惹上麻煩，即便不用解密這些通訊內容。事實上在許多國家，有人僅因為拒絕解密其加密的訊息而被抓坐牢。

保護你的詮釋資料將需要其它工具，例如 TOR 瀏覧器以及末端間的加密。你可以在[網際網路課程](umbrella://lesson/the-internet)中學到相關方法。 

### 分享你的 GPG 公鑰

PGP 工具指南將詳細解釋如何創建你的 PGP 公鑰以及如何分享使用它 一般而言，僅記住如果你正在一個危險的環境而要使用假名，這個公鑰就取假名並且使用另一個電子信箱。

掩飾你正在與某一個人通訊更為困難，一個方法是雙方都透過TOR使用匿名的電子郵件，這樣作，PGP　仍然很有用，可以讓你們雙方的電子郵件內容保持隱密，提供對方不會收被遭到篡改的訊息。

滑動右側到課程檢查表

到初學者課程求得進一步如何改善基本電子郵件安全以及處理電郵遭駭的處理資訊

[初級者課程](umbrella://lesson/the-internet)

### 相關的課程工具

-   [Internet lesson](umbrella://lesson/the-internet)
-   [PGP for Mac OSX tool](umbrella://lesson/pgp-for-mac-os-x)
-   [PGP for Windows tool](umbrella://lesson/pgp-for-windows)
-   [PGP for Linux tool](umbrella://lesson/pgp-for-linux)
-   [K9 & APG tool](umbrella://lesson/k9-&-apg)

### 進階閱讀材料
-   [EFF - Public key cryptography and PGP](https://ssd.eff.org/en/module/introduction-public-key-cryptography-and-pgp)

	

