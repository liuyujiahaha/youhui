# youhui
youhui download address

IOS使用企业证书，发布inhouse版本：<br>
1.首先需要一个可以访问的plist文件，此plist文件必须放在有CA证书的网站上面；<br>
2.然后需要在网页上添加以下代码：<br>
		/<a href='itms-services://?action=download-manifest&url=https://git.oschina.net/liuyujiahaha/youhuiDownload/raw/master/youhui_release.plist'>点击安装渝优汇【正式环境地址】/</a/> 
需要在代码中添加可以直接打开这plist文件的地址，需要把https://git.oschina.net/liuyujiahaha/youhuiDownload/blob/master/youhui.plist中的blob改成raw；<br>
3.在plist文件中填写正确的下载地址；
