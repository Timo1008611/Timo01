mixed-port: 7890
allow-lan: true
mode: rule
log-level: info
ipv6: false
external-controller: 0.0.0.0:9090
dns:
  enable: true
  listen: 0.0.0.0:53
  ipv6: false
  default-nameserver:
    - 223.5.5.5
    - 114.114.114.114
  nameserver:
    - 223.5.5.5
    - 114.114.114.114
    - 119.29.29.29
    - 180.76.76.76
  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter:
    - "*.lan"
    - "*.localdomain"
    - "*.example"
    - "*.invalid"
    - "*.localhost"
    - "*.test"
    - "*.local"
    - "*.home.arpa"
    - router.asus.com
    - localhost.sec.qq.com
    - localhost.ptlogin2.qq.com
    - +.msftconnecttest.com
tun:
  enable: true
  stack: system
  auto-route: true
  auto-detect-interface: true
  dns-hijack:
    - 114.114.114.114
    - 180.76.76.76
    - 119.29.29.29
    - 223.5.5.5
    - 8.8.8.8
    - 8.8.4.4
    - 1.1.1.1
    - 1.0.0.1
proxies:
  - name: 3.11免费节点
    type: vless
    server: 211.238.83.146
    port: 39135
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_1
    type: vless
    server: 211.198.173.100
    port: 10082
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_2
    type: vless
    server: 112.133.148.226
    port: 17170
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_3
    type: vless
    server: 211.238.83.146
    port: 23792
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_4
    type: vless
    server: 119.195.168.105
    port: 20031
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_5
    type: vless
    server: 68.64.179.243
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_6
    type: vless
    server: 211.184.116.84
    port: 50000
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_7
    type: vless
    server: 210.105.224.42
    port: 10840
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_8
    type: vless
    server: 34.143.159.175
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_9
    type: vless
    server: 83.229.121.78
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_10
    type: vless
    server: 119.195.168.105
    port: 16738
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_11
    type: vless
    server: 198.62.62.235
    port: 443
    uuid: 5a4abb78-ecd7-4d68-ab2a-c11a3842f261
    network: ws
    servername: bank.alaska-tigr.info
    tls: true
    ws-opts:
      path: /love
      headers:
        Host: bank.alaska-tigr.info
  - name: 3.11免费节点_12
    type: vless
    server: 202.84.53.85
    port: 30816
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_13
    type: vless
    server: 198.62.62.248
    port: 443
    uuid: 5a4abb78-ecd7-4d68-ab2a-c11a3842f261
    network: ws
    servername: tar.alabama-tigr.info
    tls: true
    ws-opts:
      path: /love
      headers:
        Host: tar.alabama-tigr.info
  - name: 3.11免费节点_14
    type: vless
    server: mx2.tehrantolidi.ir
    port: 80
    uuid: dfe13f5a-9ce4-44fc-be96-1067bbf9202d
    network: ws
    tls: false
    ws-opts:
      path: /site
      headers:
        Host: cdn123.global.ssl.fastly.net
  - name: 3.11免费节点_15
    type: vless
    server: 194.87.10.77
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_16
    type: vless
    server: 211.48.77.114
    port: 22410
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_17
    type: vless
    server: 43.165.180.71
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_18
    type: vless
    server: 218.150.33.69
    port: 30052
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_19
    type: vless
    server: 119.195.168.105
    port: 11786
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_20
    type: vless
    server: 188.114.98.112
    port: 80
    uuid: 0991a0c4-0ee5-4213-af89-7ad589f853f3
    network: ws
    tls: false
    ws-opts:
      path: /ELiV2-RAY----ELiV2-RAY----ELiV2-RAY----ELiV2-RAY----ELiV2-RAY----ELiV2-RAY?ed=2560
      headers:
        Host: elenaaaaaaaaaa.cloudns.pro.
  - name: 3.11免费节点_21
    type: vless
    server: 59.29.89.197
    port: 18765
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_22
    type: vless
    server: 218.150.33.69
    port: 15050
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_23
    type: vless
    server: 59.29.89.197
    port: 20114
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_24
    type: vless
    server: 68.64.179.250
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_25
    type: vless
    server: 220.71.102.124
    port: 16691
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_26
    type: vless
    server: 43.160.248.66
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_27
    type: vless
    server: 220.122.42.198
    port: 19071
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_28
    type: vless
    server: 77.93.91.159
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_29
    type: vless
    server: 119.192.158.53
    port: 16628
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_30
    type: vless
    server: 220.78.129.86
    port: 11937
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_31
    type: vless
    server: 59.16.228.103
    port: 18469
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_32
    type: vless
    server: 59.30.5.169
    port: 30020
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_33
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_34
    type: vless
    server: 221.146.116.77
    port: 15284
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_35
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_36
    type: vless
    server: 121.139.183.69
    port: 30020
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_37
    type: vless
    server: 220.85.201.216
    port: 10448
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_38
    type: vless
    server: 218.154.216.119
    port: 12332
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_39
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_40
    type: vless
    server: 175.212.45.195
    port: 12053
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_41
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_42
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_43
    type: vless
    server: 198.62.62.124
    port: 443
    uuid: 5a4abb78-ecd7-4d68-ab2a-c11a3842f261
    network: ws
    servername: war.connecticut-haloo.info
    tls: true
    ws-opts:
      path: /love
      headers:
        Host: war.connecticut-haloo.info
  - name: 3.11免费节点_44
    type: vless
    server: 59.3.3.161
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_45
    type: vless
    server: 119.195.168.105
    port: 10973
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_46
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_47
    type: vless
    server: 151.242.74.249
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_48
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_49
    type: vless
    server: 83.229.123.173
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_50
    type: vless
    server: 119.195.168.105
    port: 12417
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_51
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_52
    type: vless
    server: 61.102.250.123
    port: 15347
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_53
    type: vless
    server: 211.238.83.146
    port: 26373
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_54
    type: vless
    server: 211.238.83.146
    port: 32641
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_55
    type: vless
    server: 68.64.179.96
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_56
    type: vless
    server: 211.243.73.135
    port: 30023
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_57
    type: vless
    server: 211.48.77.114
    port: 11265
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_58
    type: vless
    server: 119.195.168.105
    port: 12345
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_59
    type: vless
    server: 220.88.3.5
    port: 11099
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_60
    type: vless
    server: 111.65.134.21
    port: 36210
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_61
    type: vless
    server: 119.203.217.216
    port: 12415
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_62
    type: vless
    server: 211.238.83.146
    port: 14096
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_63
    type: vless
    server: 192.0.54.136
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_64
    type: vless
    server: 192.0.63.88
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_65
    type: vless
    server: 121.166.253.13
    port: 30038
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_66
    type: vless
    server: 192.0.63.91
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_67
    type: vless
    server: 192.0.63.242
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_68
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_69
    type: vmess
    server: 103.181.164.237
    port: 34114
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_70
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_71
    type: vmess
    server: pub.ap20260228.com
    port: 64018
    uuid: a739e782-1682-38a5-9153-aad09d779ae9
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_72
    type: trojan
    server: 58.152.25.253
    port: 443
    password: BxceQaOe
    skip-cert-verify: true
    tls: true
  - name: 3.11免费节点_73
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.11免费节点_74
    type: vless
    server: 43.160.248.66
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_75
    type: vless
    server: 77.93.91.159
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_76
    type: vless
    server: 45.93.30.168
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_77
    type: vless
    server: 220.92.158.117
    port: 15916
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_78
    type: vless
    server: 121.143.196.49
    port: 32773
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.fgfw.indevs.in
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.fgfw.indevs.in
  - name: 3.11免费节点_79
    type: vless
    server: 59.3.3.161
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_80
    type: vless
    server: 211.48.77.114
    port: 22410
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_81
    type: vless
    server: 220.80.220.45
    port: 10046
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_82
    type: vless
    server: 112.184.55.64
    port: 32789
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_83
    type: vless
    server: 218.150.33.69
    port: 15050
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_84
    type: vless
    server: 119.203.217.216
    port: 12415
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_85
    type: vless
    server: 211.198.173.100
    port: 10082
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_86
    type: vless
    server: 220.88.3.5
    port: 12283
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_87
    type: vless
    server: 34.143.159.175
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_88
    type: vless
    server: 43.165.180.71
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_89
    type: vless
    server: 119.195.168.105
    port: 10973
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_90
    type: vless
    server: 211.184.116.84
    port: 50000
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_91
    type: vless
    server: 183.97.71.221
    port: 12125
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_92
    type: vless
    server: 121.166.253.13
    port: 30038
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳+@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_93
    type: vless
    server: 119.195.168.105
    port: 11097
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.11免费节点_94
    type: vmess
    server: 141.11.21.219
    port: 50521
    uuid: 7b4c6795-3be5-4a4e-b234-07a46f580c45
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    servername: a.sezar.top
  - name: 3.11免费节点_95
    type: vless
    server: 89.208.113.120
    port: 8082
    uuid: 00000000-0000-4000-8000-000000000000
    network: ws
    servername: sub.mot.ip-ddns.com
    tls: true
    ws-opts:
      path: /
      headers:
        Host: sub.mot.ip-ddns.com
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
  - name: 🎯 全球直连
    type: select
    proxies:
      - DIRECT
      - 🚀 节点选择
      - ♻️ 自动选择
  - name: 🛑 全球拦截
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🍃 应用净化
    type: select
    proxies:
      - REJECT
      - DIRECT
  - name: 🐟 漏网之鱼
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - ♻️ 自动选择
      - 3.11免费节点
      - 3.11免费节点_1
      - 3.11免费节点_2
      - 3.11免费节点_3
      - 3.11免费节点_4
      - 3.11免费节点_5
      - 3.11免费节点_6
      - 3.11免费节点_7
      - 3.11免费节点_8
      - 3.11免费节点_9
      - 3.11免费节点_10
      - 3.11免费节点_11
      - 3.11免费节点_12
      - 3.11免费节点_13
      - 3.11免费节点_14
      - 3.11免费节点_15
      - 3.11免费节点_16
      - 3.11免费节点_17
      - 3.11免费节点_18
      - 3.11免费节点_19
      - 3.11免费节点_20
      - 3.11免费节点_21
      - 3.11免费节点_22
      - 3.11免费节点_23
      - 3.11免费节点_24
      - 3.11免费节点_25
      - 3.11免费节点_26
      - 3.11免费节点_27
      - 3.11免费节点_28
      - 3.11免费节点_29
      - 3.11免费节点_30
      - 3.11免费节点_31
      - 3.11免费节点_32
      - 3.11免费节点_33
      - 3.11免费节点_34
      - 3.11免费节点_35
      - 3.11免费节点_36
      - 3.11免费节点_37
      - 3.11免费节点_38
      - 3.11免费节点_39
      - 3.11免费节点_40
      - 3.11免费节点_41
      - 3.11免费节点_42
      - 3.11免费节点_43
      - 3.11免费节点_44
      - 3.11免费节点_45
      - 3.11免费节点_46
      - 3.11免费节点_47
      - 3.11免费节点_48
      - 3.11免费节点_49
      - 3.11免费节点_50
      - 3.11免费节点_51
      - 3.11免费节点_52
      - 3.11免费节点_53
      - 3.11免费节点_54
      - 3.11免费节点_55
      - 3.11免费节点_56
      - 3.11免费节点_57
      - 3.11免费节点_58
      - 3.11免费节点_59
      - 3.11免费节点_60
      - 3.11免费节点_61
      - 3.11免费节点_62
      - 3.11免费节点_63
      - 3.11免费节点_64
      - 3.11免费节点_65
      - 3.11免费节点_66
      - 3.11免费节点_67
      - 3.11免费节点_68
      - 3.11免费节点_69
      - 3.11免费节点_70
      - 3.11免费节点_71
      - 3.11免费节点_72
      - 3.11免费节点_73
      - 3.11免费节点_74
      - 3.11免费节点_75
      - 3.11免费节点_76
      - 3.11免费节点_77
      - 3.11免费节点_78
      - 3.11免费节点_79
      - 3.11免费节点_80
      - 3.11免费节点_81
      - 3.11免费节点_82
      - 3.11免费节点_83
      - 3.11免费节点_84
      - 3.11免费节点_85
      - 3.11免费节点_86
      - 3.11免费节点_87
      - 3.11免费节点_88
      - 3.11免费节点_89
      - 3.11免费节点_90
      - 3.11免费节点_91
      - 3.11免费节点_92
      - 3.11免费节点_93
      - 3.11免费节点_94
      - 3.11免费节点_95
rule-providers:
  LocalAreaNetwork:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/LocalAreaNetwork.list
    path: ./rules/LocalAreaNetwork.yaml
  BanAD:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/BanAD.list
    path: ./rules/BanAD.yaml
  BanProgramAD:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/BanProgramAD.list
    path: ./rules/BanProgramAD.yaml
  GoogleCN:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/GoogleCN.list
    path: ./rules/GoogleCN.yaml
  SteamCN:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Ruleset/SteamCN.list
    path: ./rules/SteamCN.yaml
  Microsoft:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Microsoft.list
    path: ./rules/Microsoft.yaml
  Apple:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Apple.list
    path: ./rules/Apple.yaml
  ProxyMedia:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ProxyMedia.list
    path: ./rules/ProxyMedia.yaml
  Telegram:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/Telegram.list
    path: ./rules/Telegram.yaml
  ProxyLite:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ProxyLite.list
    path: ./rules/ProxyLite.yaml
  ChinaDomain:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ChinaDomain.list
    path: ./rules/ChinaDomain.yaml
  ChinaCompanyIp:
    type: http
    behavior: classical
    url: https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/refs/heads/master/Clash/ChinaCompanyIp.list
    path: ./rules/ChinaCompanyIp.yaml
rules:
  - RULE-SET,LocalAreaNetwork,🎯 全球直连
  - RULE-SET,BanAD,🛑 全球拦截
  - RULE-SET,BanProgramAD,🍃 应用净化
  - RULE-SET,GoogleCN,🎯 全球直连
  - RULE-SET,SteamCN,🎯 全球直连
  - RULE-SET,Microsoft,Ⓜ️ 微软服务
  - RULE-SET,Apple,🍎 苹果服务
  - RULE-SET,ProxyMedia,🌍 国外媒体
  - RULE-SET,Telegram,📲 电报信息
  - RULE-SET,ProxyLite,🚀 节点选择
  - RULE-SET,ChinaDomain,🎯 全球直连
  - RULE-SET,ChinaCompanyIp,🎯 全球直连
  - GEOIP,CN,🎯 全球直连
  - MATCH,🐟 漏网之鱼
