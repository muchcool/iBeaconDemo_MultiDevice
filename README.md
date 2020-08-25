# iBeaconDemo_MultiDevice

利用iBeacon做的多设备间测距离的demo

1目前功能:

首页作为发送,有个发送开关,(一个区域内,发送端UUID可以填任何设备的uuid,随便填个,只要是个uuid, 收发端都填同一个就能收发,这个uuid只作为收发匹配识别用,和实际发送端设备uuid不同也没关系);
第二页作为接受,有接受开关,log框显示与发送端的距离

2附加

建了个tableView的list,显示多个设备的name,右侧实时显示当前距离
beacons.count

多个设备收发已经实现.设备名和major一一对应后设定,作为设备识别

