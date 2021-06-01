# OPENCV 安裝指南

## 1. 前言

這個方法是我在網路上找的，大多參考[這個網站](https://medium.com/@sourabhjigjinni/install-opencv-4-0-0-for-c-windows-7-10-code-blocks-tdm-gcc-64-dff65addf162)，然後把它改的詳細一點而已。

## 2. 需要的工具

要用到 **CodeBlock**，應該不會有人沒ㄅ

其他要用的，可來我的[Google Drive下載](https://drive.google.com/file/d/1aLryH8sqTeMiGuKjUB-BDm1s3Jm3RAgc/view?usp=sharing)，裡面東西都是從官網來的。  

或者是你會怕，也可自己去官網下載：
- [CMake](https://cmake.org/download/) 選x86-64.msi
- [TDM-GCC](https://jmeubank.github.io/tdm-gcc/) 選左邊的MinGW-w64
- [OpenCV](https://opencv.org/releases/) 選任一個版本的Sources下載。創建一個新資料夾opencv，裡面創兩個空資料夾build、source，然後把剛剛下載的檔案解壓縮後丟入source

## 3. 安裝CMake

執行我給的 **cmake-3.20.3-windows-x86_64.msi**

選 **Add to system path for all user**

![](img/cmake02.png)

把安裝路徑改成 **C:\CMake**

![](img/cmake03.png)

再 **Install** 就 OK 啦！

## 4. 安裝TDM-GCC
執行 **tdm64-gcc-10.3.0-2.exe**  並 **create**

![](img/tdm01.png)

選 **MinGW-w64**

![](img/tdm02.png)

後面就都不改，照預設的安裝！

## 5. OPENCV
把我那個 **opencv** 資料夾直接拖到 C 槽底下

## 6. Binaries
執行 **C:\CMake\bin\cmake-gui.exe**

- **source** 的地方打 **C:/opencv/source**  
**binary** 的地方打 **C:/opencv/build**  

- **Grouped** 跟 **Advanced** 不用勾選  

- 按 **Configure** 再選擇 **CodeBlocks - MinGW**  
再 **Use default**

- 按下 **finish** ，等他跑完

![](img/bin01.png)

