# 使用nginx作为基础镜像
FROM nginx

# 将本地的html文件复制到nginx的默认静态文件目录
COPY event_graph/travel_event_graph.html /usr/share/nginx/html

# 将vis.css和vis.js文件复制到nginx的默认静态文件目录
COPY event_graph/VIS/dist/vis.css /usr/share/nginx/html/VIS/dist/
COPY event_graph/VIS/dist/vis.js /usr/share/nginx/html/VIS/dist/

# 暴露80端口
EXPOSE 80