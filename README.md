# Live2D demo

Live2D 看板娘插件 (https://www.fghrsh.net/post/123.html) 的前端 HTML 源码
无需模型 API 版

在 fghrsh 的 [Live2D demo](https://github.com/fghrsh/live2d_demo) 的基础上修改而成，具体使用方法请参考原版，以下仅交代不同之处

和原版相比，此版本无需再搭建后端 API (在前端实现模型和材质的更换，一言 API 仍需后端支持)。
可以直接白嫖 jsdelivr（
为了写代码的方便，我把模型和材质的id都从0开始了

若需添加新模型，请克隆原后端 API，按照原 API 的方式添加好模型后，将`gene_config_file.py`移动至API的`model`文件夹下并运行。修改`waifu-tips.js`中的`live2d_settings['staticAPIFile']`为生成的`static-api-file.json`目录，并更新`live2d_settings['staticPath']`为`model`文件夹路径，即可正常使用。

## 版权声明

> ( ˃ ˄ ˂̥̥ ) 都看到这了，点个 Star 吧 ~

[Flat UI Free][1]  
[live2d_src / ©journey-ad / GPL v2.0][2]  
[waifu-tips.js / ©journey-ad / CC BY-NC-SA 4.0][3]  
[Live2D demo / ©fghrsh / GPL v2.0][4]  
  
Open sourced under the GPL v2.0 license.


  [1]: https://designmodo.com/flat-free/ "Flat UI Free"
  [2]: https://github.com/journey-ad/live2d_src "基于 #fea64e4 的修改版"
  [3]: https://imjad.cn/ "猫与向日葵"
  [4]: https://github.com/fghrsh/live2d_demo "Live2D demo"
