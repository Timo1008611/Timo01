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
  - name: 3.9免费节点
    type: trojan
    server: 166.88.130.226
    port: 443
    password: adb13850-7e70-492e-85b2-01184801d587
    sni: ca05.oportal.cc
    skip-cert-verify: true
    tls: false
  - name: 3.9免费节点_1
    type: trojan
    server: 8443.golden-cards.me
    port: 443
    password: q2GRUM1-odJBWq_KV6xv2fuNvu8ed-
    skip-cert-verify: true
    tls: false
  - name: 3.9免费节点_2
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.9免费节点_3
    type: vmess
    server: v30.hdacd.com
    port: 30830
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.9免费节点_4
    type: vmess
    server: 103.181.164.237
    port: 34114
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.9免费节点_5
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.9免费节点_6
    type: trojan
    server: 58.152.25.253
    port: 443
    password: BxceQaOe
    sni: t.me/ripaojiedian
    skip-cert-verify: true
    tls: false
  - name: 3.9免费节点_7
    type: ss
    server: slur.izenny.com
    port: 40063
    cipher: chacha20-ietf-poly1305
    password: d3a07498-7bcf-48b0-a6ed-8dbda2451c7d
  - name: 3.9免费节点_8
    type: ss
    server: iepl.huli168.com
    port: 19822
    cipher: aes-256-gcm
    password: g4JtpkuxkwRH4jhj
  - name: 3.9免费节点_9
    type: vmess
    server: v8.hdacd.com
    port: 30808
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 2
    cipher: auto
    tls: false
    skip-cert-verify: false
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
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
      - 3.9免费节点
      - 3.9免费节点_1
      - 3.9免费节点_2
      - 3.9免费节点_3
      - 3.9免费节点_4
      - 3.9免费节点_5
      - 3.9免费节点_6
      - 3.9免费节点_7
      - 3.9免费节点_8
      - 3.9免费节点_9
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
