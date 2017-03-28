channel.py:python脚本
channel_list.txt:渠道列表
signed.apk:已签名的原apk文件，不包含渠道信息
zipalign_batch.bat:zipalign.exe对apk文件优化处理（必须的操作）

执行命令：python channel.py signed.apk