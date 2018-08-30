# AirStreamer 使用说明

## 本地有下载好的字幕srt格式的，投视频可以带字幕吗? 

   目前电视和电视盒子的协议不支持带字幕，所以只能视频上面带字幕才可以,下面提供一些方法可以将视频和字幕合成为一个带字幕的视频.<br>

   安装转换插件 brew install mkvtoolnix<br>
   打开系统终端 <br>
   mkvmerge -o 合成的文件路径.mkv 源视频文件路径.mkv 源视频字幕路径.srt<br>
   
   例如:<br>
   mkvmerge -o '/Users/**/Movies/output.mkv' '/Users/**/Movies/inputput.mp4' '/Users/**/Movies/inputput.srt'<br>


## 为什么投屏了之后,电脑休眠了之后视频断开了呢?
   因为电脑休眠后网络连接断开导致,解决: 系统->能源与节能->设置自动休眠长些时间

## YouTube为什么投屏不了呢?
   需要电脑和电视都可以访问youtobe才能解析并投屏

