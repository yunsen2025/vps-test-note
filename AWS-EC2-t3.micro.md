**云服务商**: AWS  
**实例类型**: t3.micro  
**CPU**: Intel(R) Xeon(R) Platinum 8259CL CPU @ 2.50GHz  
**配置**: 2C1G  
**IP**: ASN16509  
**其他**: AWS 免费套餐  

---
[https://paste.spiritlhl.net/#/show/h0s6e.txt](https://paste.spiritlhl.net/#/show/h0s6e.txt)
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2025.08.15
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址 [推荐]：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Intel(R) Xeon(R) Platinum 8259CL CPU @ 2.50GHz
 CPU 核心数        : 2
 CPU 频率          : 2499.996 MHz
 CPU 缓存          : L1: 32.00 KB / L2: 1.00 MB / L3: 35.75 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 180.44 MiB / 939.75 MiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 995.70 MiB / 24965.07 MiB
 启动盘路径        : /dev/nvme0n1p1
 系统在线时间      : 0 days, 0 hour 28 min
 负载              : 0.16, 0.04, 0.01
 系统              : Debian GNU/Linux 13 (trixie) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 6.12.41+deb13-cloud-amd64
 TCP加速方式       : cubic
 虚拟化架构        : Amazon Virtualization
 NAT类型           : Port Restricted Cone
 IPV4 ASN          : AS16509 Amazon.com, Inc.
 IPV4 位置         : Hong Kong / Hong Kong / HK
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		991 Scores
 2 线程测试(多核)得分: 		1707 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		20471.20 MB/s
 单线程写测试:		16969.11 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		4.5 MB/s (1093 IOPS, 23.42s)		6.7 MB/s (1644 IOPS, 15.57s)
 1GB-1M Block		149 MB/s (142 IOPS, 7.02s)		141 MB/s (134 IOPS, 7.45s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 6.19 MB/s     (1.5k) | 66.03 MB/s    (1.0k)
Write      | 6.18 MB/s     (1.5k) | 66.39 MB/s    (1.0k)
Total      | 12.37 MB/s    (3.0k) | 132.43 MB/s   (2.0k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 63.33 MB/s     (123) | 62.72 MB/s      (61)
Write      | 66.58 MB/s     (130) | 67.18 MB/s      (65)
Total      | 129.92 MB/s    (253) | 129.91 MB/s    (126)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：中国香港
[IPV6]
您的网络可能没有正常配置IPv6，或者没有IPv6网络接入
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG07S42)
Youtube识别地域: 中国香港(HK)
[IPV6]
Youtube在您的出口IP所在的国家不提供服务
---------------DisneyPlus---------------
[IPV4]
当前IPv4出口所在地区即将开通DisneyPlus
[IPV6]
DisneyPlus在您的出口IP所在的国家不提供服务
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Yes (Region: HK)
 Disney+:				No (IP Banned By Disney+ 1)
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: HK)
 Amazon Prime Video:			Yes (Region: HK)
 TVBAnywhere+:				No
 Spotify Registration:			No
 OneTrust Region:			HK [Unknown]
 iQyi Oversea Region:			HK
 Bing Region:				HK
 Apple Region:				HK
 YouTube CDN:				Hong Kong
 Netflix Preferred CDN:			Mumbai (Bombay)
 ChatGPT:				No (Only Available with Mobile APP)
 Google Gemini:				No
 Claude:				No
 Wikipedia Editability:			No
 Google Play Store:			Hong Kong 
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			HKD
 ---Forum---
 Reddit:				No
 ---Game---
 SD Gundam G Generation Eternal:	No
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
--------------------TikTok解锁--感谢lmc999的源脚本----------------------
 Tiktok Region:		Failed
-------------IP质量检测--基于oneclickvirt/securityCheck使用-------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  [0] | scamalytics数据库 [1] | virustotal数据库   [2] | abuseipdb数据库   [3] | ip2location数据库    [4]
ip-api数据库  [5] | ipwhois数据库     [6] | ipregistry数据库   [7] | ipdata数据库      [8] | db-ip数据库          [9]
ipapiis数据库 [A] | ipapicom数据库    [B] | bigdatacloud数据库 [C] | dkly数据库        [D] | ipqualityscore数据库 [E]
IPV4:
安全得分:
声誉(越高越好): 0 [2] 
信任得分(越高越好): 0 [8] 
VPN得分(越低越好): 100 [8] 
代理得分(越低越好): 100 [8] 
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 100 [8] 
欺诈得分(越低越好): 12 [1] 65 [E]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0001 (Very Low) [A]
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [9] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: hosting - moderate probability [C] DataCenter/WebHosting/Transit [3] business [8] hosting [0 7 9 A]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7] 
是否数据中心: No [8 C] Yes [0 1 5 6 A]
是否移动设备: No [5 A C] Yes [E]
是否代理: Yes [E] No [0 1 4 5 6 7 8 9 A C]
是否VPN: Yes [A E] No [0 1 6 7 C]
是否Tor: No [0 1 3 6 7 8 A C E] 
是否Tor出口: No [1 7] 
是否网络爬虫: No [9 A E] 
是否匿名: No [1 6 7 8] 
是否攻击者: No [7 8] 
是否滥用者: No [7 8 A C E] 
是否威胁: No [7 8 C] 
是否中继: No [0 7 8 C] 
是否Bogon: No [7 8 A C] 
是否机器人: No [E] 
DNS-黑名单: 315(Total_Check) 0(Clean) 4(Blacklisted) 19(Other) 
Google搜索可行性：NO
-------------邮件端口检测--基于oneclickvirt/portchecker开源-------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✔     ✔     ✔     ✔     ✔     ✔    
QQ        ✘     ✔     ✔     ✘     ✔     ✘    
163       ✘     ✔     ✔     ✘     ✔     ✘    
Sohu      ✘     ✔     ✔     ✘     ✔     ✘    
Yandex    ✘     ✔     ✔     ✘     ✔     ✘    
Gmail     ✘     ✔     ✘     ✘     ✘     ✘    
Outlook   ✘     ✘     ✔     ✘     ✔     ✘    
Office365 ✘     ✘     ✔     ✘     ✔     ✘    
Yahoo     ✘     ✔     ✘     ✘     ✘     ✘    
MailCOM   ✘     ✔     ✔     ✘     ✔     ✘    
MailRU    ✘     ✔     ✘     ✘     ✔     ✘    
AOL       ✘     ✔     ✘     ✘     ✘     ✘    
GMX       ✘     ✔     ✔     ✘     ✔     ✘    
Sina      ✘     ✔     ✔     ✘     ✔     ✘    
Apple     ✘     ✔     ✘     ✘     ✘     ✘    
FastMail  ✘     ✔     ✘     ✘     ✘     ✘    
ProtonMail✘     ✘     ✘     ✘     ✘     ✘    
MXRoute   ✘     ✘     ✔     ✘     ✔     ✘    
Namecrane ✘     ✔     ✔     ✘     ✔     ✘    
XYAMail   ✘     ✘     ✘     ✘     ✘     ✘    
ZohoMail  ✘     ✔     ✘     ✘     ✘     ✘    
Inbox_eu  ✘     ✔     ✔     ✘     ✘     ✘    
Free_fr   ✘     ✔     ✔     ✘     ✔     ✘    
-------------上游及三网回程--基于oneclickvirt/backtrace开源-------------
国家: HK 城市: Hong Kong 服务商: AS16509 Amazon.com, Inc.
      AS174             AS1299            AS2914            AS3356            AS3491      
      Cogent           Arelion             NTT              Lumen              PCCW       
   Tier1 Global      Tier1 Global      Tier1 Global      Tier1 Global      Tier1 Global   
      AS5511            AS6453      
      Orange             Tata       
   Tier1 Global      Tier1 Global   
北京电信v4 219.141.140.10           电信163    [普通线路] 
北京联通v4 202.106.195.68           联通4837   [普通线路] 
北京移动v4 221.179.155.161          移动CMI    [普通线路] 
上海电信v4 202.96.209.133           电信163    [普通线路] 
上海联通v4 210.22.97.1              联通4837   [普通线路] 
上海移动v4 211.136.112.200          移动CMI    [普通线路] 
广州电信v4 58.60.188.222            电信163    [普通线路] 
广州联通v4 210.21.196.6             联通4837   [普通线路] 
广州移动v4 120.196.165.24           移动CMI    [普通线路] 
成都电信v4 61.139.2.69              电信163    [普通线路] 
成都联通v4 119.6.6.6                联通4837   [普通线路] 
成都移动v4 211.137.96.205           移动CMI    [普通线路] 
准确线路自行查看详细路由，本测试结果仅作参考
同一目标地址多个线路时，检测可能已越过汇聚层，除第一个线路外，后续信息可能无效
-----------------------回程路由--基于nexttrace开源----------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自nexttrace，请知悉!
广州电信 58.60.188.222
49.91 ms 	* RFC1112
49.89 ms 	* RFC1112
49.50 ms 	AS16509 [AMAZO-4] 美国 弗吉尼亚州 阿什本 amazon.com
49.55 ms 	AS16509 [AMAZO-4] 美国 弗吉尼亚州 阿什本 amazon.com
* ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
87.24 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
93.54 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
4.50 ms 	* RFC1112
0.40 ms 	* RFC1112
0.83 ms 	* RFC1112
34.40 ms 	* RFC1112
31.75 ms 	* 新加坡
191.54 ms 	* 新加坡
86.22 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
101.85 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
93.01 ms 	AS17623 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.61 ms 	* 中国 香港
0.80 ms 	* RFC1112
1.39 ms 	* RFC1112
20.19 ms 	* 中国 香港
2.18 ms 	* 美国 伊利诺伊州 芝加哥
2.22 ms 	AS58453 [CMI-INT] 中国 香港 cmi.chinamobile.com 移动
7.00 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
8.40 ms 	AS9808 [CMNET] 中国 广东 广州 X-I chinamobileltd.com 移动
32.36 ms 	AS9808 [CMNET] 中国 广东 广州 I-C chinamobileltd.com 移动
35.22 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
41.22 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
38.74 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
36.32 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟
Speedtest.net	 3938.78Mbps	 4016.79Mbps	 737.15ms	
中国香港	 709.23Mbps	 463.54Mbps	 2.90ms	
新加坡		 377.38Mbps	 329.62Mbps	 35.91ms	
联通上海5G	 165.40Mbps	 302.07Mbps	 88.72ms	
电信Suzhou5G	 165.33Mbps	 126.23Mbps	 98.32ms	
电信浙江	 0.80Mbps	 46.59Mbps	 207.02ms	
移动Suzhou	 13.75Mbps	 0.46Mbps	 32.83ms	
------------------------------------------------------------------------
 总共花费      : 8 分 48 秒
 时间          : Thu Aug 28 06:31:06 UTC 2025
------------------------------------------------------------------------

```
