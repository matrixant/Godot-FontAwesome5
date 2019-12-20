## FontAwesome5 icon plugin for godot 3.x

简介：这个插件可以让你在你的游戏中使用 [FontAwesome 5](https://fontawesome.com/) 的图标。 

使用：将 addons 文件夹复制到你的工程根目录，添加节点时搜索 FontAwesome 即可(继承自 Label)

新增属性：  
- `icon_size`: 图标尺寸  
- `icon_type`: 图标种类，有三种类型可选 `solid`/`regular`/`brands`，每种类型下图标都不同，详见[这里](https://fontawesome.com/cheatsheet/free/solid)  
- `icon_name`: 图标名称，如 `flag` 将对应 <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="flag" class="svg-inline--fa fa-flag fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="16" height="16"><path fill="currentColor" d="M349.565 98.783C295.978 98.783 251.721 64 184.348 64c-24.955 0-47.309 4.384-68.045 12.013a55.947 55.947 0 0 0 3.586-23.562C118.117 24.015 94.806 1.206 66.338.048 34.345-1.254 8 24.296 8 56c0 19.026 9.497 35.825 24 45.945V488c0 13.255 10.745 24 24 24h16c13.255 0 24-10.745 24-24v-94.4c28.311-12.064 63.582-22.122 114.435-22.122 53.588 0 97.844 34.783 165.217 34.783 48.169 0 86.667-16.294 122.505-40.858C506.84 359.452 512 349.571 512 339.045v-243.1c0-23.393-24.269-38.87-45.485-29.016-34.338 15.948-76.454 31.854-116.95 31.854z"></path></svg> ，更多图标名称请查看[这里](https://fontawesome.com/cheatsheet/free/solid)  

> 这里的字体版本是 `FontAwesome 5.12.0`  

>  如果你需要更新字体文件，你要先从[这里](https://github.com/FortAwesome/Font-Awesome/tree/master/webfonts)更新 **`addons/FontAwesome`** 里的三个 .ttf 字体文件，还有从[这里](https://github.com/FortAwesome/Font-Awesome/tree/master/js)更新 **`utils`** 里的三个 .js 文件。然后运行 **`utils`** 里的 Lua 脚本以生成新的 Cheatsheet.gd 文件。  


Intro: This is a plugin that let you use FontAwesome 5 icons in your game.

How to use: Copy the `addons` folder to your godot project directory, and then add the `FontAwesome` node to your scene.

Properties:  
- `icon_size`: icon's size.  
- `icon_type`: icon type，There are three different icon set `solid`/`regular`/`brands`，for more details look [this site](https://fontawesome.com/cheatsheet/free/solid)  
- `icon_name`: icon name，for instance `flag` correspond to <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="flag" class="svg-inline--fa fa-flag fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" width="16" height="16"><path fill="currentColor" d="M349.565 98.783C295.978 98.783 251.721 64 184.348 64c-24.955 0-47.309 4.384-68.045 12.013a55.947 55.947 0 0 0 3.586-23.562C118.117 24.015 94.806 1.206 66.338.048 34.345-1.254 8 24.296 8 56c0 19.026 9.497 35.825 24 45.945V488c0 13.255 10.745 24 24 24h16c13.255 0 24-10.745 24-24v-94.4c28.311-12.064 63.582-22.122 114.435-22.122 53.588 0 97.844 34.783 165.217 34.783 48.169 0 86.667-16.294 122.505-40.858C506.84 359.452 512 349.571 512 339.045v-243.1c0-23.393-24.269-38.87-45.485-29.016-34.338 15.948-76.454 31.854-116.95 31.854z"></path></svg> ，go [here](https://fontawesome.com/cheatsheet/free/solid) to find more icon names.

> The font's version in this repo is `5.12.0`  

>  You need to update the [*.ttf](https://github.com/FortAwesome/Font-Awesome/tree/master/webfonts) file in **`addons/FontAwesome`** and [*.js](https://github.com/FortAwesome/Font-Awesome/tree/master/js) file in **`utils`** when you want update FontAwesome's fonts.Then run the lua script in **`utils`** to generate a new Cheatsheet.gd file.  
