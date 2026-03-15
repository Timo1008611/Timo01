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
  - name: 3.15免费节点
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_1
    type: vless
    server: 220.88.3.5
    port: 12283
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_2
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
  - name: 3.15免费节点_3
    type: vless
    server: 192.0.63.76
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_4
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
  - name: 3.15免费节点_5
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
  - name: 3.15免费节点_6
    type: vless
    server: 192.0.63.115
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_7
    type: vmess
    server: 103.181.164.145
    port: 54022
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_8
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
  - name: 3.15免费节点_9
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_10
    type: vless
    server: 83.229.123.173
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_11
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_12
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
  - name: 3.15免费节点_13
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_14
    type: vless
    server: 45.145.42.170
    port: 8005
    uuid: 00000000-0000-4000-8000-000000000000
    network: ws
    servername: sub.mot.ip-ddns.com
    tls: true
    ws-opts:
      path: /
      headers:
        Host: sub.mot.ip-ddns.com
  - name: 3.15免费节点_15
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_16
    type: ss
    server: auto.poland.ray-vpn.ru
    port: 4495
    cipher: chacha20-ietf-poly1305
    password: 2Z9ba3GwDL-rn6DSQ0N-awHNhcuxaHP3
  - name: 3.15免费节点_17
    type: trojan
    server: 58.152.25.253
    port: 443
    password: BxceQaOe
    skip-cert-verify: true
    tls: false
  - name: 3.15免费节点_18
    type: trojan
    server: nl-4.tr202507.com
    port: 443
    password: uThbm8eGmXZ7GKqnWy
    skip-cert-verify: true
    tls: false
  - name: 3.15免费节点_19
    type: trojan
    server: nl-4.tr202512.com
    port: 443
    password: M08tvzYWtUEJNtbpHp
    skip-cert-verify: true
    tls: false
  - name: 3.15免费节点_20
    type: vless
    server: 192.200.160.20
    port: 443
    uuid: dc08d353-44f5-45b6-b273-703ff5e955dc
    network: ws
    servername: 639073677243308853.camry-perma.info
    tls: true
    ws-opts:
      path: /jxyughws?ed=2560
      headers:
        Host: 639073677243308853.camry-perma.info
  - name: 3.15免费节点_21
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_22
    type: vmess
    server: cn02.365cloud5878.com
    port: 6044
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_23
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_24
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_25
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_26
    type: vmess
    server: cn02.365cloud5878.com
    port: 6007
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_27
    type: vmess
    server: cn02.365cloud5878.com
    port: 6036
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_28
    type: vmess
    server: cn02.365cloud5878.com
    port: 6018
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_29
    type: vmess
    server: cn02.365cloud5878.com
    port: 6027
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_30
    type: vmess
    server: cn02.365cloud5878.com
    port: 6035
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_31
    type: vmess
    server: cn02.365cloud5878.com
    port: 6009
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_32
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_33
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_34
    type: vmess
    server: cn02.365cloud5878.com
    port: 6038
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_35
    type: vmess
    server: cn02.365cloud5878.com
    port: 6029
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_36
    type: vmess
    server: cn02.365cloud5878.com
    port: 6023
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_37
    type: vmess
    server: cn02.365cloud5878.com
    port: 6032
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_38
    type: vmess
    server: cn02.365cloud5878.com
    port: 6046
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_39
    type: vmess
    server: cn02.365cloud5878.com
    port: 6024
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_40
    type: vmess
    server: cn02.365cloud5878.com
    port: 6031
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_41
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_42
    type: vmess
    server: cn02.365cloud5878.com
    port: 6010
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_43
    type: vmess
    server: cn02.365cloud5878.com
    port: 6034
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_44
    type: vmess
    server: cn02.365cloud5878.com
    port: 6041
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_45
    type: vmess
    server: cn02.365cloud5878.com
    port: 6005
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_46
    type: vmess
    server: cn02.365cloud5878.com
    port: 6052
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_47
    type: vmess
    server: cn02.365cloud5878.com
    port: 6014
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_48
    type: vmess
    server: cn02.365cloud5878.com
    port: 6049
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_49
    type: vmess
    server: cn02.365cloud5878.com
    port: 6026
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_50
    type: vmess
    server: cn02.365cloud5878.com
    port: 6045
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_51
    type: vmess
    server: cn02.365cloud5878.com
    port: 6021
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_52
    type: vmess
    server: cn02.365cloud5878.com
    port: 6039
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_53
    type: vmess
    server: cn02.365cloud5878.com
    port: 6028
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_54
    type: vmess
    server: cn02.365cloud5878.com
    port: 6020
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_55
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_56
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_57
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_58
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_59
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_60
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_61
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_62
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_63
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_64
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_65
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_66
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_67
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_68
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_69
    type: vmess
    server: cn02.365cloud5878.com
    port: 6001
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_70
    type: vmess
    server: cn02.365cloud5878.com
    port: 6004
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_71
    type: vmess
    server: cn02.365cloud5878.com
    port: 6017
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_72
    type: vmess
    server: cn02.365cloud5878.com
    port: 6043
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_73
    type: vmess
    server: cn02.365cloud5878.com
    port: 6042
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_74
    type: vmess
    server: cn02.365cloud5878.com
    port: 6016
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_75
    type: vmess
    server: cn02.365cloud5878.com
    port: 6012
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_76
    type: vmess
    server: cn02.365cloud5878.com
    port: 6047
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_77
    type: vmess
    server: cn02.365cloud5878.com
    port: 6022
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_78
    type: vmess
    server: cn02.365cloud5878.com
    port: 6002
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_79
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_80
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_81
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_82
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_83
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_84
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_85
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_86
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_87
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_88
    type: vless
    server: 172.64.229.85
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_89
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
  - name: 3.15免费节点_90
    type: vless
    server: 43.165.191.25
    port: 19457
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_91
    type: vless
    server: 104.19.58.74
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_92
    type: vless
    server: 121.131.86.236
    port: 13214
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.kozow.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.kozow.com
  - name: 3.15免费节点_93
    type: vless
    server: 118.37.73.36
    port: 12321
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_94
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
  - name: 3.15免费节点_95
    type: vless
    server: 59.3.3.161
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_96
    type: vless
    server: 106.244.201.248
    port: 50001
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_97
    type: vless
    server: 38.47.113.227
    port: 38318
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_98
    type: vless
    server: 112.219.110.147
    port: 12100
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_99
    type: vless
    server: 43.160.248.66
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_100
    type: vless
    server: 218.157.158.21
    port: 11965
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_101
    type: vless
    server: 104.17.28.89
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_102
    type: vless
    server: 192.0.63.49
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_103
    type: vless
    server: 192.0.63.216
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_104
    type: vless
    server: 192.0.54.130
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_105
    type: vless
    server: 192.0.54.131
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.kozow.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.kozow.com
  - name: 3.15免费节点_106
    type: vless
    server: 192.0.63.194
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_107
    type: vless
    server: 211.252.46.215
    port: 10255
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_108
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
  - name: 3.15免费节点_109
    type: vless
    server: 193.9.49.65
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_110
    type: vless
    server: 192.0.63.76
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_111
    type: vless
    server: 192.0.63.115
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_112
    type: vless
    server: 192.0.54.130
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_113
    type: vless
    server: 192.0.63.134
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.kozow.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.kozow.com
  - name: 3.15免费节点_114
    type: vless
    server: 192.0.54.29
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_115
    type: vless
    server: 192.0.63.216
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_116
    type: vless
    server: 192.0.54.250
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_117
    type: vless
    server: 192.0.63.58
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_118
    type: vless
    server: 192.0.63.230
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.kozow.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.kozow.com
  - name: 3.15免费节点_119
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
  - name: 3.15免费节点_120
    type: vless
    server: 192.0.63.60
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_121
    type: vless
    server: 188.130.207.30
    port: 2053
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_122
    type: vless
    server: 43.165.191.25
    port: 20524
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_123
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
  - name: 3.15免费节点_124
    type: vless
    server: 43.165.191.25
    port: 20524
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳@WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_125
    type: vless
    server: 162.159.7.2
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_126
    type: vless
    server: 204.197.163.166
    port: 8500
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_127
    type: vless
    server: 104.18.41.43
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_128
    type: vless
    server: 162.159.24.111
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_129
    type: vless
    server: 104.19.85.38
    port: 443
    uuid: 9e4f36da-8f61-44f8-a9a7-0fd3a8d81234
    network: ws
    servername: r.icy.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: r.icy.de5.net
  - name: 3.15免费节点_130
    type: vless
    server: 143.20.213.120
    port: 8443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_131
    type: vless
    server: 143.20.213.69
    port: 8443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_132
    type: vless
    server: 178.253.22.252
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_133
    type: vless
    server: 143.20.213.22
    port: 8443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_134
    type: vless
    server: 185.133.173.205
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.kozow.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.kozow.com
  - name: 3.15免费节点_135
    type: vless
    server: 143.20.213.88
    port: 8443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_136
    type: vless
    server: 194.87.245.253
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.kozow.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.kozow.com
  - name: 3.15免费节点_137
    type: vmess
    server: cg1d05.waimaojd.com
    port: 443
    uuid: 6abe3ac8-e1f8-4b24-bb67-191bc23b5fab
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    servername: cg1d05.waimaojd.com
    network: ws
    ws-opts:
      path: /api/v1/graphql
      headers:
        Host: cg1d05.waimaojd.com
  - name: 3.15免费节点_138
    type: vmess
    server: cn02.365cloud5878.com
    port: 6015
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_139
    type: vless
    server: 194.58.68.6
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_140
    type: vmess
    server: cn02.365cloud5878.com
    port: 6051
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_141
    type: vless
    server: 68.64.179.96
    port: 443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_142
    type: vless
    server: 43.165.180.71
    port: 8443
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_143
    type: vless
    server: 199.241.138.38
    port: 25631
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.15免费节点_144
    type: vless
    server: 31.133.0.105
    port: 2053
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.loc.cc
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.loc.cc
  - name: 3.15免费节点_145
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_146
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_147
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_148
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_149
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_150
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_151
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_152
    type: vmess
    server: cn02.365cloud5878.com
    port: 6003
    uuid: 9f1ecfca-13a9-488d-ac84-aaeb73a8d574
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_153
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_154
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_155
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_156
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_157
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_158
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_159
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_160
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_161
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_162
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_163
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_164
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_165
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_166
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_167
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_168
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_169
    type: vless
    server: 192.0.63.49
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.15免费节点_170
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.15免费节点_171
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
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
      - 3.15免费节点
      - 3.15免费节点_1
      - 3.15免费节点_2
      - 3.15免费节点_3
      - 3.15免费节点_4
      - 3.15免费节点_5
      - 3.15免费节点_6
      - 3.15免费节点_7
      - 3.15免费节点_8
      - 3.15免费节点_9
      - 3.15免费节点_10
      - 3.15免费节点_11
      - 3.15免费节点_12
      - 3.15免费节点_13
      - 3.15免费节点_14
      - 3.15免费节点_15
      - 3.15免费节点_16
      - 3.15免费节点_17
      - 3.15免费节点_18
      - 3.15免费节点_19
      - 3.15免费节点_20
      - 3.15免费节点_21
      - 3.15免费节点_22
      - 3.15免费节点_23
      - 3.15免费节点_24
      - 3.15免费节点_25
      - 3.15免费节点_26
      - 3.15免费节点_27
      - 3.15免费节点_28
      - 3.15免费节点_29
      - 3.15免费节点_30
      - 3.15免费节点_31
      - 3.15免费节点_32
      - 3.15免费节点_33
      - 3.15免费节点_34
      - 3.15免费节点_35
      - 3.15免费节点_36
      - 3.15免费节点_37
      - 3.15免费节点_38
      - 3.15免费节点_39
      - 3.15免费节点_40
      - 3.15免费节点_41
      - 3.15免费节点_42
      - 3.15免费节点_43
      - 3.15免费节点_44
      - 3.15免费节点_45
      - 3.15免费节点_46
      - 3.15免费节点_47
      - 3.15免费节点_48
      - 3.15免费节点_49
      - 3.15免费节点_50
      - 3.15免费节点_51
      - 3.15免费节点_52
      - 3.15免费节点_53
      - 3.15免费节点_54
      - 3.15免费节点_55
      - 3.15免费节点_56
      - 3.15免费节点_57
      - 3.15免费节点_58
      - 3.15免费节点_59
      - 3.15免费节点_60
      - 3.15免费节点_61
      - 3.15免费节点_62
      - 3.15免费节点_63
      - 3.15免费节点_64
      - 3.15免费节点_65
      - 3.15免费节点_66
      - 3.15免费节点_67
      - 3.15免费节点_68
      - 3.15免费节点_69
      - 3.15免费节点_70
      - 3.15免费节点_71
      - 3.15免费节点_72
      - 3.15免费节点_73
      - 3.15免费节点_74
      - 3.15免费节点_75
      - 3.15免费节点_76
      - 3.15免费节点_77
      - 3.15免费节点_78
      - 3.15免费节点_79
      - 3.15免费节点_80
      - 3.15免费节点_81
      - 3.15免费节点_82
      - 3.15免费节点_83
      - 3.15免费节点_84
      - 3.15免费节点_85
      - 3.15免费节点_86
      - 3.15免费节点_87
      - 3.15免费节点_88
      - 3.15免费节点_89
      - 3.15免费节点_90
      - 3.15免费节点_91
      - 3.15免费节点_92
      - 3.15免费节点_93
      - 3.15免费节点_94
      - 3.15免费节点_95
      - 3.15免费节点_96
      - 3.15免费节点_97
      - 3.15免费节点_98
      - 3.15免费节点_99
      - 3.15免费节点_100
      - 3.15免费节点_101
      - 3.15免费节点_102
      - 3.15免费节点_103
      - 3.15免费节点_104
      - 3.15免费节点_105
      - 3.15免费节点_106
      - 3.15免费节点_107
      - 3.15免费节点_108
      - 3.15免费节点_109
      - 3.15免费节点_110
      - 3.15免费节点_111
      - 3.15免费节点_112
      - 3.15免费节点_113
      - 3.15免费节点_114
      - 3.15免费节点_115
      - 3.15免费节点_116
      - 3.15免费节点_117
      - 3.15免费节点_118
      - 3.15免费节点_119
      - 3.15免费节点_120
      - 3.15免费节点_121
      - 3.15免费节点_122
      - 3.15免费节点_123
      - 3.15免费节点_124
      - 3.15免费节点_125
      - 3.15免费节点_126
      - 3.15免费节点_127
      - 3.15免费节点_128
      - 3.15免费节点_129
      - 3.15免费节点_130
      - 3.15免费节点_131
      - 3.15免费节点_132
      - 3.15免费节点_133
      - 3.15免费节点_134
      - 3.15免费节点_135
      - 3.15免费节点_136
      - 3.15免费节点_137
      - 3.15免费节点_138
      - 3.15免费节点_139
      - 3.15免费节点_140
      - 3.15免费节点_141
      - 3.15免费节点_142
      - 3.15免费节点_143
      - 3.15免费节点_144
      - 3.15免费节点_145
      - 3.15免费节点_146
      - 3.15免费节点_147
      - 3.15免费节点_148
      - 3.15免费节点_149
      - 3.15免费节点_150
      - 3.15免费节点_151
      - 3.15免费节点_152
      - 3.15免费节点_153
      - 3.15免费节点_154
      - 3.15免费节点_155
      - 3.15免费节点_156
      - 3.15免费节点_157
      - 3.15免费节点_158
      - 3.15免费节点_159
      - 3.15免费节点_160
      - 3.15免费节点_161
      - 3.15免费节点_162
      - 3.15免费节点_163
      - 3.15免费节点_164
      - 3.15免费节点_165
      - 3.15免费节点_166
      - 3.15免费节点_167
      - 3.15免费节点_168
      - 3.15免费节点_169
      - 3.15免费节点_170
      - 3.15免费节点_171
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
