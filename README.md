s3upload
========

透過指令將網頁到佈署 S3

# Features

* 上傳本地檔案到 S3
* 上傳本地資料夾到 S3
* Minimize and gzip any JavaScript, CSS and HTML using [HTML Compressor](http://code.google.com/p/htmlcompressor/) and [YUI Compressor](http://yui.github.io/yuicompressor/)
* Set correct content type and content-encoding headers
* Sets HTTP cache headers far into the future

# Dependencies

* [AWS CLI](http://docs.aws.amazon.com/cli/latest/index.html)
* Java

# 設定

1. git clone https://github.com/jinweilin/s3upload.git
2. export PATH=$PATH:/path/to/s3upload

# 使用方式

1. s3upload-file _filename bucket/folder
2. s3upload-folder _folder bucket/folder
3. Defaults to ap-northeast-1 region.