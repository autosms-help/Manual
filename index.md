# 教程

### 目录

* [Sim卡激活](#Sim卡激活)
* [检查手机设置](#检查手机设置)
* [手机数据网络基本排错方法](#手机数据网络基本排错方法)
* [换卡改串号](#换卡改串号)
* [软件下载](#软件下载)
* [Autocall相关](#Autocall相关)
* [Autocall教程](#Autocall教程)
* [刷机教程](#刷机教程)
    - [下載地址](#下載地址)
    - [准备工作](#准备工作)
    - [製作流程](#製作流程)

#### Sim卡激活
Lycamobile Sim卡激活
- 方法1: 使用在线激活工具: [http://ninemagicwords.pythonanywhere.com/activate](http://ninemagicwords.pythonanywhere.com/activate)
- 方法2: 将未激活的卡插入手机，然后拨打622，根据语音提示激活。

#### 检查手机设置
- 检查「手机号」: `设置`->`SIM卡` 查看屏幕顶部，应该显示正常的手机号码。如果这里显示的是100000****的话，说明Sim还没有激活。
- 检查「首选SIM卡」: `设置`->`SIM卡` 查看屏幕中部「首选SIM卡」，其中`移动数据网络` `通话` `短信`应该选择为当前SIM卡。
- 检查「APN设置」: `设置`->`更多`->`移动网络`->`接入点名称（APN）` 这里应该选“lycamobile”。如果没有找到“lycamobile”，可以手动添加APN。具体设置可以参考[https://www.lycamobile.us/en/help/mobile-web-settings/](https://www.lycamobile.us/en/help/mobile-web-settings/)
- 检查「数据流量」是否开启: `设置`->`流量使用情况` 查看屏幕顶部，`移动数据网络` 应该是开启的状态。

#### 手机数据网络基本排错方法
- 一般手机开机后，需要等一段时间，手机顶部信号状态会显示为E/3G/4G 这些都是正常的。
- 如果信号栏显示正常，但是软件无法登陆，可以开启飞行模式，然后再关闭飞行模式，让手机从新搜索网络。
- 另一种测试方法，是使用手机浏览器，访问某个网站，如google.com看是否可以连接。
- 如果还是不能工作，可以使用该手机，给另一个手机打电话，看是否跟余额或卡激活有关。
- 换一张确认好用的Sim卡，如果可以正常工作，即可判断是sim卡的问题。
- 在信号不好，未满格的情况下，需要一些耐心，因为这种情况，需要更多的时间等待手机网络。

#### 换卡改串号
每次更换Sim卡时，建议手机修改IMEI串号，这样可以最大限度降低手机被封锁的几率，方法如下：
1. 关机，取出SIM卡，再开机。
2. 在无Sim卡的状态下，点击`改串换卡`。（是个白色的开关标识）程序会自动更换IMEI串号，并关机。
3. 插入新Sim卡，开机即可。
4. 验证新串号，可以在电话拨打界面，拨`*#06#`。手机上会显示当前更换后的串号。
5. 目前BLU手机还不支持改串号功能。K3 Note支持。

#### 软件下载
- Autocall: [https://drive.google.com/drive/folders/1EgSW3tRF1tdY7TzsHkWRSwsi-04UimGn?usp=sharing](https://drive.google.com/drive/folders/1EgSW3tRF1tdY7TzsHkWRSwsi-04UimGn?usp=sharing)
- AutoSMS V25: [https://drive.google.com/file/d/1PPumqra87UrX_nG4VINPNWHTTbNjjAxv/view?usp=sharing](https://drive.google.com/file/d/1PPumqra87UrX_nG4VINPNWHTTbNjjAxv/view?usp=sharing)
- MTK自改串工具: [https://drive.google.com/file/d/1jL8c9m7qN8NNKQgsnZNmFZH7P1n4SEal/view?usp=sharing](https://drive.google.com/file/d/1jL8c9m7qN8NNKQgsnZNmFZH7P1n4SEal/view?usp=sharing)
- MTK自改串工具（来源）:[https://tiandixing.org/viewtopic.php?f=20&t=184501&start=0](https://tiandixing.org/viewtopic.php?f=20&t=184501&start=0)
- sim卡处理软件: [https://drive.google.com/drive/folders/1hOilD8zFq9HRAndwjqTabkU8mSFRnHvL?usp=sharing](https://drive.google.com/drive/folders/1hOilD8zFq9HRAndwjqTabkU8mSFRnHvL?usp=sharing)

#### Autocall相关
- Autocall 需要配套使用 CallActive。一般刷机后都可以正常使用。如果没有，请下载。[https://drive.google.com/drive/folders/1EgSW3tRF1tdY7TzsHkWRSwsi-04UimGn?usp=sharing]
- 如果出现“辅助包未安装...”的字样，请下载AutoCall.zip，解压之后使用RE管理器放到/sdcard/下。
#### Autocall教程
- 1. 打开 Autocall
- 2. 左下角 点击 `开始`
- 3. 选择 `自动运行`, 在`State`这一栏会开始计数。



## 刷机教程

##### 下載地址
- 3.0版刷机镜像: https://drive.google.com/drive/folders/1gPUPv5EGfgvF5x1nkALIhXIo3JK0WpDp?usp=sharing
- 刷机工具+驱动: https://drive.google.com/drive/folders/17LwbEJ4uI0Nsvag85p20XPw5yubogOYP?usp=sharing

##### 准备工作
- 1. 驅動安裝:方法見相應文件夾裡的說明文件
- 2. 工具軟件文件名為 `Flash Tools.zip`。下載完成後，解壓至桌面，桌面上會出現一個名為 `Flash Tools` 的文件夾，裡面有四個文件夾。
- 3. 鏡像文件:下載完成後， 將文件解壓縮至桌面。(步驟 3 和 4:如果把文件解壓至其它地方，一定要保證文件路徑上沒有中文)
- 4. 雙擊打開 `Flash Tools/SP_Flash_Tool_1` 文件夾裡的 `flash_tool.exe` 文件，將 Scatter-loading File 的文件改為指向對應鏡像文件夾裡的 `scatter file.txt` 文件(點擊`choose`按鈕選擇)。其它設置都不需要改動。保持該軟件打開。

##### 製作流程

- 1. 手機充好電，保證電池有超過 70%的電量。關閉手機電源。(如果手機裡原來有 Sim 卡，請先把手機設置為飛行模式，然後再關機)
- 2. 在 SPFlashTool 的界面，點擊 `Download` 按鈕(綠色下指箭頭)。 此時軟件界面處於等待狀態。
- 3. 將手機通過 USB 數據線連接到電腦的 USB 接口。如果驅動安裝正確，手機會被識別，然後自動開始執行操作，會有進度條顯示操作進度。整個製作過程需要將近 20 分鐘。完成之後，會彈出來一個綠色打勾的對話框。(注:盡量使用台式機，並且使用機箱後面的 USB 接口來製作真相手機，其電源質量比較穩定，效果比較好;如果沒有台式機，筆記本電腦也可以，但如果可行的話，盡量使用筆記本電腦上用於充電的那個 USB 接口，這個接口上面除了一般的 USB 標識外，還有一個閃電形的標識)
- 4. 關掉彈出來的綠色打勾對話框。斷開手機與電腦的連接。再次點擊 `Download` 按鈕，連接另一個已經關閉電源的手機繼續製作下一個。
- **Note** 如果要製作的真相手機數量比較多時，為了提高效率，可以利用 台式機機箱後面的多個 USB 接口同步進行真相手機製作，工具文件 夾裡的其他幾個文件夾 SP_Flash_Tool_2、3、4 就是做這個用的。 機箱後面有幾個 USB 接口，就可以打開幾個文件夾裡的 flash_tool.exe 同步製作。注意:每次點擊 flash tool 界面上的 Download 按鈕之後，一定要先連上一台手機，然後才能點擊下一個 界面的 Download，再連另一台手機。不可以同時在幾個界面上都點 擊 Dowaload，然後才開始連第一台手機。這樣會報錯。
而且切記，不要使用普通的筆記本電腦或者台式機機箱前面的 USB 接口同步製作真相手機，這樣容易出現異常。
在製作真相手機的過程中，請保持心態純淨，正念加持。
