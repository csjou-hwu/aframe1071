# aframe1071
## 簡介
1. asp.net core sdk 2.1.4 (https://dotnet.microsoft.com/download) and/or Visual Studio 2017 
2. Windows 7 x64
## Wk1 教學環境測試 (電腦/手機)
### 1-1 dotnet 測試
cmd
dotnet --version

### 1-2 自動產生網站程式(localhost)
dotnet new web -o wk0101
cd wk0101
dotnet run
chrome http://localhost:5000

### 1-3 電腦網址(ipconfig)


### 1-4 修改固定網址(localhost ⇒ 192.168.131.70)
Program.cs
.UseUrls(“http://192.168.131.70:5000/”)


### 1-5 手機連線

### 1-6 測試手機 (aframe.io)

## Visual Studio 2017 工作環境
### 2-2-1 VS2017 ASP.NETCore WebApplication(空白)

### 2-2-1 固定IP
Program.cs
.UseUrls("http://192.168.131.70:5000")

### 2-2-3 靜態網頁
Startup.cs

### 2-2-4 HTML
### 2-2-5 aframe.io






 
