# virtualbox
[環境]
```
node1 : RAC ノード1
  IP:192.168.56.101 (public)
     192.168.100.101 (interconnect1)
     192.168.200.101 (interconnect2)
node2 : RAC ノード2
  IP:192.168.56.102 (public)
     192.168.100.102 (interconnect1)
     192.168.200.102 (interconnect2)
utility : DNS,NFS等
  IP:192.168.56.254
```
[手順]
```
1. 仮想マシン作成
create_VM

2. OSインストール (Oracle Linux 7.6)
install_OEL7.6

3. GI,DBインストール (19c)
install_19cRAC_on_OEL7.6.txt
```
