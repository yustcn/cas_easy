CAS Overlay Template
============================

 本项目存在意义：
 ---------------------
   为了简化CAS服务端部署。
      
   当然，如果你想完整的部署，本人也总结了部署流程。
   见：http://wiki.sai.corp/pages/viewpage.action?pageId=11338103
   学习该文档能更好的帮助你理解CAS搭建流程。
      
 本项目使用方式：
 -----------------
  直接使用：
   1.git clone
   2.执行 sudo ./build.sh
   3.将war部署到tomcat即可。
   
  项目更新：
   1.下载Overlay版服务端：https://github.com/apereo/cas-overlay-template
   2.下载的项目和此项目唯一的区别是没有src目录。
   3.将本项目的src 复制到 你的项目中。
   4.执行 sudo ./build.sh
   5.将war部署到tomcat即可。
     
     
    注意：该项目 编译(./build.sh)，部署(启动tomcat) 需要root 权限。
     
     
