# RcloneX
支持世纪互联的魔改Rclone整合集

## API

一般来说需要自己的世纪互联API

如果是同济校友等无API的，请使用公共API或者该教程：

世纪互联空全局订阅获取Azure+自建独享API+Rclone挂载+Sharelist挂载

【 https://blog.000714.xyz/202008/2321.html 】

## 使用正确的RcloneX版本

VerA经过测试，不能挂载同济SP（表现为挂载和挂OD一致），但OD可以

VerB经过测试，SP和OD均可挂载

VerC未测试

注意：添加新配置需要把世纪互联版本填true

注意：Win版不影响Linux挂载

## 获取SiteID

目前推荐去这两个地方获取

网站A：https://od.xkx.me/sp.php

网站B：https://blog.jialezi.net/?post=157

请根据中文提示填写，Site ID长这样：

universitytongji.sharepoint.cn,53adcc59-5e28-47b6-b9d0-04e62338cc1d,7e475269-0c00-408e-abb2-b437bf67e410

到rclone末尾问你siteid时候直接复制即可
