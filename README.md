# 说明

这是一个利用rem来实现自适应的demo,

只需要修改js部分的

    docEle.style.fontSize = 20 * (width / 1024) + 'px';

和less部分的：


	.function{
	    .rem(@px){
	        return:@px*1024/@designWidth/20rem; /
	    }


这里需要安装less和less-plugin-functions，并且在开发工具中设置好即可


	npm i less -g
	npm i less-plugin-functions -g


![](http://i.imgur.com/a2PelUQ.png)