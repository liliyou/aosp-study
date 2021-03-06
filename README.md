# aosp-study

本項目為 [Android 讀書會](https://www.facebook.com/groups/523386591081376/)中，由大家自發性發起學習 AOSP 的教材。

AOSP 為 **Android Open Source Project** 的縮寫，白話來說就是 Android 的原始碼，這份教材會以探討AOSP的設計架構為主軸。

由於大部份人都是使用 Mac 和 Linux 進行開發，因此本教材基於 Mac OS X 和 Ubuntu 14.04 LTS 編寫。如果您用的是其他 Linux 系統則建議參考教材進行調整。

***或可直接參考[AOSP官方網站](https://source.android.com/index.html)***

## 實驗環境

我們提供**已經成功建置供 Google Nexus 5 手機開發用的虛擬機映像檔（VMware Workstation Pro 12.1.1 + Ubuntu 14.04.4 LTS + AOSP 6.0.1_r60 + Nexus 5 Binaries + Nexus 5 Images Built）**，無法順利下載 AOSP 程式碼建置的朋友可以考慮使用虛擬機開始唷！  
[點此下載 (Google Drive)](https://drive.google.com/a/vhost.com.tw/folderview?id=0B_-EbjrACEtWNmJRY1ExY1VQQjA&usp=sharing)  
[點此下載 (OneDrive)](https://1drv.ms/f/s!ApqiyucM1a6alBO6WK5I5EG8-RTm)

## TODO

以下這些章節待完成，如果各位願意一起共筆的話不妨寫上吧！別忘了在 Contributors 上加上你的大名和聯絡方式喔！

* [CH6: AOSP 架構總覽](/ch6_aosp_overview)

## 目錄

### 基本設定篇

1. [環境設定](/ch1_setup)
2. [下載 AOSP 程式碼](/ch2_download)
3. [編繹 AOSP 原始碼](/ch3_build)
4. [燒錄客製的 AOSP Image](/ch4_flash)
5. [使用 adb 工具開發 AOSP](/ch5_adb)
6. [AOSP 架構總覽](/ch6_aosp_overview)
7. [設定 Android Studio](/ch7_android_studio_setup)

### Android 基礎知識篇

8. [Android 的核心 Library](/ch8_android_core_libraries)
9. [Android 的 `Makefile` -- `Android.mk`](/ch9_android_makefile)
10. [Android 開機流程概觀](/ch10_android_bootup_progress)
11. Android 的第一行程式碼 -- `init` 及 `init.rc`
12. Android framework 啟動

### Android 核心知識篇

13. [Android 的 IPC 框架：Binder](/ch13_android_ipc_binder)
* Android 與 Linux Kernel 的關係
* HAL
* Zygote
* System Server

### 附錄

* [repo工具](/appendix/repo/)
* [終端機工具及指令](/appendix/cli-tools)

## Contributors (協作者們)

* [Charlie Tsai](https://github.com/chatea) - cha122977@gmail.com
* [Cheng-Yi, Yu](https://github.com/erinus) - erinus.startup@gmail.com
* [Richard Chang](https://github.com/chiel99)
* [Lex Chien](https://github.com/LexChien)
* [weihung](https://github.com/weihung)
* [liliyou](https://github.com/liliyou)

## License (版權聲明)

[![Created Commons License](https://i.creativecommons.org/l/by-sa/3.0/88x31.png)](http://creativecommons.org/licenses/by-sa/3.0/)
<br>
本項目採用 [CC-BY-SA授權](http://creativecommons.org/licenses/by-sa/3.0/).
<br>
This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).
