# my-picture-online
🎉Power Design By 打酱油🎉

**最新更新**
🎉图片现已支持 -多分辨率- 下载（Safari暂不支持，请自行保存）
🎉图片已支持标签显示

## 项目简介
> 该项目是基于`React Hook` + `semantic ui react`实现，提供在线壁纸服务的前端浏览服务。

**在线地址：** [点击预览](192.168.0.223)

## 配置说明
- 头部导航栏配置：

`src/config/nav,js`
```js
/*
  Tip:
    导航栏会根据URL自动确定当前页面对应激活菜单项。
    配置默认根路由跳转的URL，即可设置默认激活子菜单。
    例如：
      '/' => '/test' 根路由跳转
      {
        key: 'Main',
        title: '主页',
        href: '/test'
      }
      会自动激活 主页 菜单项
      
  导航栏配置说明：
    titleIcon 标题图片
    titleText 标题文字
    textColor 菜单项默认文字颜色（不含标题文字）
    activeColor 菜单项默认激活颜色（现支持：red orange yellow olive green teal blue violet purple pink brown grey black）
    leftMenu 左侧菜单组
    rightMenu 右侧菜单组
    （菜单顺序与菜单项配置先后顺序一致）
    
    普通子菜单项：
      {
        key: 'Main',
        title: '主页',
        href: '/test/1'
      }
    外部链接跳转：
      {
        key: 'GitHub',
        title: 'GitHub',
        href: 'www.github.com',
        externalLink: true // 设置为true表示为外部链接，否则为站内地址
      }
    多级子菜单（subitems中追加即可）：
      {
        key: 'Main2',
        title: '分类',
        subitems: [
          {
            key: 'AA',
            title: 'AA',
            href: '/AA'
          },
          {
            key: 'BB',
            title: 'BB',
            href: '/BB'
          }
        ]
      }
*/
```