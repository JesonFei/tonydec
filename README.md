# tonydec
lihancong/tonyenc 的解密工具


### python在3.6版本及以下的时候需要微调一下程序可用

26行，取消下划线 data[i] = data[i]^key[p]^0b1111_1111

34行，改为传统模式 print('Processing file: {}...'.format(input_path), end='')

参考连接2022UUCTF-web
https://blog.csdn.net/bossDDYY/article/details/127671924
