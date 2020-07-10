# notes
cordova 开发App的gradle配置：
1:在运行cordova run android前,需要下载gradle版本并配置环境变量（path中加入grable/bin的路径）
2:环境变量完成后执行cordova run android提示Downloading https://services.gradle.org/distributions/gradle-4.10.3-all.zip或其他版本,
这里会卡很久,解决方法是将下载的gradle.zip压缩包拷贝到C:\Users\Administrator\.gradle\wrapper\dists\gradle-4.10.3-all\81msde2dx9p4vji0mjgtvxkcb
打包进程就会继续，后面会下载一些其他的依赖包，可能会失败几次，重新执行cordova run android直到成功为止


