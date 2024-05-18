# SAROO-BGSOUND
SAROO 20240515开始支持菜单背景音乐，格式为PCM S16LE 2CH 16BIT 44.1K

此BGSOUND2.0工具安装至SAROO目录下，将任何音乐文件拖到相应的BAT文件上面即可

（工具借助FFMPEG软件，使用前将FFMPEG.EXE拷贝到BGSOUND目录）


注意：

使用前确保目录正确，不缺文件：

下载BGSOUND.RAR解压缩至SAROO目录

下载FFMPEG.EXE
（https://ffmpeg.org/download.html#build-windows）
（https://github.com/BtbN/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-win64-gpl.zip）


萨鲁/BGSOUND/

		WAVPATCH 补丁文件，不要删除	

		多首歌曲multi-songs.bat 将多个音乐文件合并成一个背景音乐，逐个拖动音乐文件到此BAT文件上面，拖动的最后一个为播放时的第一首
  
		单首歌曲single-song.bat 将一个音乐文件转换成一首背景音乐
  
		游戏镜像GAME_BIN_PCM_to_single_song.bat一般多BIN游戏镜像内第二个BIN文件（个别游戏第三需要或第四）为音频文件，转换成一首背景音乐;
                                                      玩家之间互相交流的bgsound.pcm文件可以用这个文件进行试听
  
		说明readme.txt 此文档
  
		ffmpeg.exe 需要自行下载，将bin目录里的ffmpeg.exe拷贝到BGSOUND目录
  ![bgsound](https://github.com/tzmwx/SAROO-BGSOUND/assets/129564095/f9d22451-024f-4ef6-bbc5-64668c8f0d2b)

  

将任何音乐文件拖到对应的BAT文件上面即可完成转换，注意对应的文件名称即对应的功能


tzmwx 2024/05/18
