//主流程
https://docs.polygon.technology/docs/integrate/full-node-binaries

//snapshot 流程
https://forum.matic.network/t/snapshot-instructions-for-heimdall-and-bor/2278


//最新snapshot
https://snapshots.matic.today/

1.先根据流程操作
2.启动3个服务
heimdalld start --home 
heimdalld rest-server
bor
3.下载snapshot
4.关闭服务
5.解压snapshot
6.重启

注意:
 heimdalld 200G snapshot后同步需要2小时
 bor 600G snapshot 后同步需要6消失
 bor invalid merkle root 报错是因为heimdalld还没有同步完,等待
 都用master分支就可以

 bor
 Version: 0.2.12-stable
 heimdalld
 Version: 0.2.4-6-ga6eda18c


