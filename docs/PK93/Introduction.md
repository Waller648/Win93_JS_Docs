# Introduction

This is how you make a package :D!


``
le._apps.test = {name:"Test", icon:"/c/sys/skins/w93/cdrom.png", exec:function(){var l=$window({baseHeight:"auto", height:"auto", html:"Hello World",maximizable:false,minimizable:false,closable:false,btnOk:"Close"});l.el.title.style.background = "#000000";l.el.title.innerHTML = "<b>Window</b>"}}
