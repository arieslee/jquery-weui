# jQuery WeUI - 打造微信公众号开发的瑞士军刀

<p align="center">
  <a href="http://jqweui.com/">
    <img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/logo.png" width="250" />
  </a>
</p>

[![npm version](https://img.shields.io/npm/v/jquery-weui.svg)](https://www.npmjs.com/package/jquery-weui)

jQuery WeUI 是专为微信公众账号开发而设计的一个简洁而强大的UI库，包含全部WeUI官方的CSS组件，并且额外提供了大量的拓展组件，丰富的组件库可以极大减少前端开发时间。

更多文档请参阅官网： [https://jquery-weui.xiaomizhou.net/](https://jquery-weui.xiaomizhou.net/)

微信扫描二维码立刻体验：

![code](https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/code.png)

# 为什么选择 jQuery WeUI

- 简单易用，无上手难度
- 丰富强大的组件库，并且还在不断完善中
- 轻量，无限制，可以结合任何主流JS框架使用，比如 `Vue, Angular, React` 等
- 高性能的 CSS3 动画，低端手机上依然可以较流畅运行
- 详尽完善的官方文档
- 稳定的API，不间断的更新迭代

# 搭配框架

`jQuery WeUI` 的定位正如 `jQuery` 的定位：做一把锋利的小刀，而不是做一个笨重的大炮。

`jQuery WeUI` 只是提供一些常用的UI控件，如果不是很复杂的项目，基本只用 `jQuery WeUI` 即可满足需求。如果项目比较复杂，或者希望实现单页应用，推荐使用 [Vue](https://github.com/vuejs/vue/) 或者 [Angular](https://angular.io/)

# 下载

推荐通过npm来安装 `npm install jquery-weui`

或者你可以 clone 这个仓库，自行编译，关于如何进行编译请参见下面的gulp章节。

所有编译后的代码都在 `dist` 目录下，为了减少垃圾文件，master默认忽略了这个目录，你可以自行编译或者切换到 `build` 分支就可以看到这个目录。

# gulp

使用 `gulp` 进行代码编译，如果你没有用过或者不想自行编译，可以切换到 `build` 分支即可。

关于如何使用 gulp 请参考 [http://gulpjs.com/](http://gulpjs.com/)

可用的 gulp 命令如下：

- `gulp` 进入开发模式，同时打开 `watch` 和 `server`任务
- `gulp build` 编译压缩代码

# 分支说明

- `master` 主分支，正式发布的代码才会进入master分支
- `build` 包含全部编译后代码的分支，和 `master` 分支同步，但是会包含 `dist` 目录
- `dev` 开发分支
- `gh-pages` 文档主分支
- `gh-pages-dev` 文档的开发分支

# 联系和讨论

QQ 群：546452237(一群), 55572340(二群), 478537720(三群)
加群暗号是在官网执行以下代码的值：

```js
location.host.split('.')[0]
```

群里更适合聊天，如果是发现bug或者有功能上的建议，推荐通过 `issue` 来讨论。

# 捐助

jQuery WeUI 是 MIT 协议的免费开源项目，不会收取任何费用。作者维护这个项目需要耗费不少精力，如果jQuery WeUI 帮到了你，你可以捐款让这个项目变得更好。当然，无论是否捐款，都感谢您对本项目的支持。

**捐款是纯粹自愿的捐助行为，我将非常感谢您的捐助，但您本人并不会因为您的捐款而获得比其他不捐款用户更多的权利，望理解。**

<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/zfb.jpg" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/wx.jpg" />

# LICENSE

[MIT](https://opensource.org/licenses/MIT)，尽情享受开源代码。

# Thanks

- [WeUI](http://weui.github.io/weui/#/)
- [Framework7](http://framework7.io/)
- [MSUI](http://m.sui.taobao.org/)
- [Jekyll](http://jekyllrb.com/)
- [gulp](http://gulpjs.com/)

# 组件展示

<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/grid.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/buttons.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/cell.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/form.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/dialog.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/select.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/calendar.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/address.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/actions.png" width="320" />
<img src="https://raw.githubusercontent.com/arieslee/jquery-weui/master/screenshot/photos.png" width="320" />
