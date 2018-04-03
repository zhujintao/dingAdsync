目前只做了单向同步。
钉钉管理后台新增员工账号都会同步到AD域，删除账号在AD域会自动停用该账号。
组织架构会以组的行式同步到AD域。
使用方法：
   ./dingAdsync 
   默认会读取当前目录下的 dingAdsync.conf 配置文件，其它目录加-c 参数。
   
   
配置文件格式：
[dingding]

corpId="xxxx"
corpSecret="xxxx"
noteappid="123456"

[domain]

domain="DRIXMT.LOCAL"
server="srv01-w12r2"
mainou="K-Think"
account="administrator@drixmt.local"
password="j@1985v.com"
ldapssl=true

  