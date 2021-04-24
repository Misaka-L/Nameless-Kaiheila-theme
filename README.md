# Nameless 无名氏开黑啦第三方主题
> English version here -> https://github.com/Misaka-L/Nameless-Kaiheila-theme/README_EN.md

> ## *该为第三方产物，可能会因客户端更新等导致无法使用!*
 
## 如何安装
### 1. 下载主题
1. 打开 [Github Releases](https://github.com/Misaka-L/Nameless-Kaiheila-theme/releases)，找到最后发布的版本。
2. 点击下方的 `nameless_kaiheila_theme_v*.zip` 下载文件
### 2. 安装主题
1. 解压缩下载下来的 `nameless_kaiheila.theme_v*.zip`。
2. 打开目录 `%appdata%\..\Local\KaiHeiLa\resources\app\webapp\build`，并放入解压缩的所有文件。
3. 使用任意文本编辑器打开 `index.htm`，并查找 `rel="stylesheet"`。
4. 在 `>` 后面添加 `<link href="/app/Nameless.css" rel="stylesheet">`。
5. 重新启动开黑啦客户端。
6. 搞定

## 自定义
### 自定义背景图片
1. 打开目录  `%appdata%\..\Local\KaiHeiLa\resources\app\webapp\build`，并使用文本编辑器打开 `Nameless.css`。
> 使用本地图片记得把图片文件放入 `%appdata%\..\Local\KaiHeiLa\resources\app\webapp\build` 并将 `background-url` 的值修改为 `url("app/图片文件名称")`
2. 找到 `background-url` 变量并将其值修改为 `url("图片地址")`
##### 例子:
```css
/* -- 无名氏 Nameless kaiheila theme By Misaka-L -- */
/* Github: https://github.com/Misaka-L/Nameless-Kaiheila-theme */

/* -- 主题相关 -- */
*{
    --background-url: url("https://bing.ioliu.cn/v1/rand");
}
```

## 版权信息
    背景图片来自 Pixiv: https://www.pixiv.net/artworks/89358421
    插画: 星空をキャンバスに変えて 作者: ドトノ
    插画版权归原作者所有，主题作者对于使用该插画造成的侵权行为不负任何责任

    Background Image from Pixiv: https://www.pixiv.net/artworks/89358421
    Illustration: 星空をキャンバスに変えて Creator: ドトノ
    The copyright of the illustration belongs to the original author. The theme author is not responsible for any infringement caused by the use of the illustration.


## 预览
![服务器界面](https://i.bmp.ovh/imgs/2021/04/d80b41e24b365751.png)
![推荐服务器界面](https://i.bmp.ovh/imgs/2021/04/4214fdde1877cece.png)
![用户设置界面](https://i.bmp.ovh/imgs/2021/04/c68c0adad1bd0acb.png)
![服务器设置界面](https://i.bmp.ovh/imgs/2021/04/d9f8021c724b074a.png)