# 用于虚拟终端的中英文杂交字体 #

杂交中英文字体可以解决中文字体在虚拟终端中显示过大的问题。

## 使用方法 ##

需要先安装 fontforge, 然后执行:
	
	resize.pe (中文字体) (em大小)
	hybird.pe (英文等宽字体) (中文字体) (新字体前缀名字)
	cp $FONTNAME ~/.local/share/fonts/  # $FONTNAME是新字体文件名
	fc-cache -f

或者直接使用我的 wqy-microhei-terminal-mono.ttf, 该字体由 Meslo LG S Regular for Powerline.otf 和 文泉驿微米黑组合而来。
