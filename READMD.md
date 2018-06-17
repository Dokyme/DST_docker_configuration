# 饥荒专用服务器Docker配置

## 文件说明

1. overworld.env 外部世界
2. underworld.env 洞穴
3. docker-compose.yml docker-compose配置文件，包括外部和洞穴的配置。
4. start.sh 启动文件
5. modoverrides.lua mod配置文件

## 使用步骤

1. 得到server_token
2. 确定洞穴有几个，在compose中添加相应的docker
3. 修改外部世界和洞穴的env，包括NAME
4. 替换modoverrides.lua
5. start.sh
