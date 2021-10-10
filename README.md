## thrift demo
### version 1.0 确保了能跑
### version 2.0 完善了客户端
### version 3.0 实现了调用远程的接口（save_data，需要提供远程服务器密码的md5值的前8位）
### version 3.1 添加匹配规则，A，B玩家分查不大于50才可匹配
### version 4.0 从TSimpleServer换成TThreadedServer 提高了match_server服务端的并发能力
### version 5.0 添加匹配规则，随时间推移，玩家可接受的分差值会变大，从而更容易匹配到人
