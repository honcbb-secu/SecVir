# SecVir

SecVir 軟體程式是由[Honc](https://blog.honcbb.me/) 安全研究人員開發」，這款程式是提供任何人可以掃描網站是否為惡意的(可提前預防)，且SecVir 核心是採用了知名反病毒引擎[VirusTotal](https://zh.wikipedia.org/zh-tw/VirusTotal) 平台的技術(API)來掃描查詢並結合諸多防毒軟體廠商病毒引擎來分析最後結果。

![image](https://i.imgur.com/P1hyaFy.jpg)

[![Release](https://img.shields.io/badge/%E7%89%88%E6%9C%AC-V1.1-green)](https://github.com/honcbb-secu/SecVir/releases)

[![Release](https://img.shields.io/badge/%E9%BB%9E%E6%88%91-%E4%B8%8B%E8%BC%89-brightgreen)](https://github.com/honcbb-secu/SecVir/releases/download/V1.1/SecVir.zip)


## Demo

[![ScreenShot](https://i.imgur.com/cdRs9g2.jpg)](https://www.youtube.com/watch?v=6oAhz3h8frE&feature=youtu.be)



## 更新

SecVir 會不定時更新，日後也會替該程式加上更多功能(敬啟期待！)


## 注意

SecVir 雖然可拿來掃描網站是否為惡意病毒，但這些資料都只能供當作參考(建議)，畢竟現代越來越多攻擊者的手法不斷的在變化(因此可能繞過這些防毒引擎)，但至少可以讓更多用戶防範(免除風險)。

## 支援

**Windows 系統**

## 分析

SecVir 掃描則使用**VirusTotal API**  來查詢而返回響應分析的結果，在傳輸過程當中所有**客戶端**資料都是直接傳至**VirusTotal** 因此非常安全！分析總結果絕對**100%** 準確。


## 安全

作者也為了保護軟體安全因而採用**軟體加密保護技術**，所以有些防毒軟體產品會判**SecVir**為是惡意木馬部分，但同樣可保證是**SecVir** 絕沒有植入**病毒木馬**及**竊取用戶電腦資訊** 任何情況，如果還是**無法放心(請勿使用)**

## 如何使用？

把想要掃描網址輸入至程式界面當中『**輸入要掃描的網址的下面輸入框**』再**點選掃描** 後等待結果通知即可。


## 常見問題

* 為什麼開啟程式出現**請先確定是否有連線！** ? 

    → 『因為程式加入了相關版本驗證通知必須與伺服器作連線確認，因此前提開啟程式下必須先開啟網路執行才行』
    
* 為什麼開啟程式出現**程式已有更新！請至作者專案重新下載新版本程式。** ? 

    → 『程式已經有新增功能或修補其他相關錯誤Bug 而衍生出新版本，這時只需至專案重新下載新版本即可』
    
* 為什麼開啟程式出現**元件'MSInet.ocx'或它的依存檔案並未正確地註冊:某檔案遺漏或不正確** ? 

    → 『這個錯誤是因為SecVir 程式本身引用了網路驗證MSInet.ocx 組件，必須要有這個檔案才能正確與伺服器驗證並且回傳相關通知訊息，電腦處於兩種情況：
    
    一. 電腦路徑C:\Windows\SysWOW64\* 沒有這個MSInet.ocx檔案，所以須至網路尋找並放置正確路徑即可>[可點我下載](https://www.ocxme.com/files/msinet_ocx)
    
    二. 電腦雖有這個檔案，但沒有給它正確註冊，可參考[這篇文章](https://dotblogs.com.tw/usice0314/2010/04/07/14442) 修改一下註冊即可』
    
 * 為什麼開啟程式出現**元件'Mswinsck.ocx'或它的依存檔案並未正確地註冊:某檔案遺漏或不正確** ? 
 
  → 『這個錯誤是因為SecVir 同樣也使用了該系統元件來與傳輸網路通訊，參考如上解決方法↑』
  
* 掃描結果是可信的嗎？ ? 
 
  → 『SecVir 是使用Google 旗下反病毒權威線上產品 VirusTotal 之服務，因此所有報告結果都是與VirusTotal 準確可信。 』
  
* 一定要連線才能開啟程式(掃描) ? 
 
  → 『是的，程式掃描所有資訊都需送往VirusTotal 系統搜尋，然而必須連網才能。 』
  
 
 ## 聯絡

若有任何問題請聯繫我：honcbb@gmail.com
  
  
  
