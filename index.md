# OPENCV 安裝指南

### 前言

這個方法是我在網路上找的，大多參考[這個網站](https://medium.com/@sourabhjigjinni/install-opencv-4-0-0-for-c-windows-7-10-code-blocks-tdm-gcc-64-dff65addf162)，然後把它改的詳細一點而已。

### 工具

有打包好ㄌ，來我的[Google Drive下載](https://drive.google.com/file/d/1aLryH8sqTeMiGuKjUB-BDm1s3Jm3RAgc/view?usp=sharing)，裡面東西都是從官網來的。  

或者是你會怕，想自己去官網下載：
- [CMake](https://cmake.org/download/) 選x86-64.msi
- [TDM-GCC](https://jmeubank.github.io/tdm-gcc/) 選左邊的MinGW-w64
- [OpenCV](https://opencv.org/releases/) 選任一個版本的Sources下載。創建一個新資料夾opencv，裡面創兩個空資料夾build、source，然後把剛剛下載的檔案解壓縮後丟入source

### 1. 安裝CMake

執行我給的 cmake-3.20.3-windows-x86_64.msi
