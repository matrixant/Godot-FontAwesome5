## FontAwesome5 icon plugin for godot 3.x

---  

插件参考了 [GodotExplorer/FontAwesome](https://github.com/GodotExplorer/FontAwesome)

---  
简介：这个插件可以让你在你的游戏中使用 [FontAwesome 5](https://fontawesome.com/) 的图标。 

使用：将 addons 文件夹复制到你的工程根目录，添加节点时搜索 FontAwesome 即可(继承自 Label)

新增属性：  
- `icon_size`: 图标尺寸  
- `icon_type`: 图标种类，有三种类型可选 `solid`/`regular`/`brands`，每种类型下图标都不同，详见[这里](https://fontawesome.com/cheatsheet/free/solid)  
- `icon_name`: 图标名称，如 `flag` 将对应![flag](flag.png)，更多图标名称请查看[这里](https://fontawesome.com/cheatsheet/free/solid)  

> 这里的字体版本是 `FontAwesome 5.12.0`  

>  如果你需要更新字体文件，你要先从[这里](https://github.com/FortAwesome/Font-Awesome/tree/master/webfonts)更新 **`addons/FontAwesome5`** 里的三个 .ttf 字体文件，还有从[这里](https://github.com/FortAwesome/Font-Awesome/tree/master/js)更新 **`utils`** 里的三个 .js 文件。然后运行 **`utils`** 里的 Lua 脚本以生成新的 Cheatsheet.gd 文件, 并用它覆盖 **`addons/FontAwesome5`** 里的同名文件。  

---

Intro: This is a plugin that let you use FontAwesome 5 icons in your game.

How to use: Copy the `addons` folder to your godot project directory, and then add the `FontAwesome` node to your scene.

Properties:  
- `icon_size`: icon's size.  
- `icon_type`: icon type，There are three different icon set `solid`/`regular`/`brands`，for more details look [this site](https://fontawesome.com/cheatsheet/free/solid)  
- `icon_name`: icon name，for instance `flag` correspond to ![flag](flag.png)，go [here](https://fontawesome.com/cheatsheet/free/solid) to find more icon names.

> The font's version in this repo is `5.12.0`  

>  You need to update the [*.ttf](https://github.com/FortAwesome/Font-Awesome/tree/master/webfonts) file in **`addons/FontAwesome5`** and [*.js](https://github.com/FortAwesome/Font-Awesome/tree/master/js) file in **`utils`** when you want update FontAwesome's fonts.Then run the lua script in **`utils`** to generate a new Cheatsheet.gd file and copy it to **`addons/FontAwesome5`** folder.  

---
