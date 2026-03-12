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
  - name: 3.13.1免费节点
    type: vless
    server: 141.11.21.219
    port: 53458
    uuid: de73ea62-68e4-45e2-8cc3-87c6d4b23aa0
    servername: a.sezar.top
    tls: true
  - name: 3.13.1免费节点_1
    type: vmess
    server: v24.hdacd.com
    port: 30824
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 2
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.1免费节点_2
    type: vmess
    server: 103.181.164.237
    port: 52283
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.1免费节点_3
    type: vless
    server: 141.11.21.219
    port: 17191
    uuid: 54635a5b-8638-452a-c9b2-805b157025a8
    servername: a.sezar.top
    tls: true
  - name: 3.13.1免费节点_4
    type: vless
    server: 104.18.32.47
    port: 2052
    uuid: 5e62ddcf-78c9-4b15-803a-436c8c839ddc
    network: ws
    tls: false
    ws-opts:
      path: /
      headers:
        Host: oBEDiENt-noiseqJf5ja18yF.wIndLer.CO.UK.
  - name: 3.13.1免费节点_5
    type: vmess
    server: 216.167.101.148
    port: 58976
    uuid: 841dc449-5bde-4a3f-81ba-d068f965cfd7
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.1免费节点_6
    type: vmess
    server: v8.hdacd.com
    port: 30808
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 2
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.1免费节点_7
    type: vmess
    server: 141.11.21.219
    port: 50521
    uuid: 7b4c6795-3be5-4a4e-b234-07a46f580c45
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    servername: a.sezar.top
  - name: 3.13.1免费节点_8
    type: vmess
    server: 103.181.164.145
    port: 54022
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
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
      - 3.13.1免费节点
      - 3.13.1免费节点_1
      - 3.13.1免费节点_2
      - 3.13.1免费节点_3
      - 3.13.1免费节点_4
      - 3.13.1免费节点_5
      - 3.13.1免费节点_6
      - 3.13.1免费节点_7
      - 3.13.1免费节点_8
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
