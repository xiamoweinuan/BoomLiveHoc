# BoomLiveHoc
#浏览器打开itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/BoomLiveHub/BoomLive/master/BoomLive_overseasTest.plist
浏览器打开itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/xiamoweinuan/BoomLiveHoc/main/BoomLive_overseasTest.plist
国内访问可能打不开可以吧plist放在自己服务端上

# bug
ios16 里面的bundle-identifier必须和项目对应:

<key>bundle-identifier</key>
                <string>exact bundle-identifier value</string>
iOS16 对这个bundle-identifier 验证可能更严格了。
