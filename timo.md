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
  - name: 3.12免费节点
    type: vmess
    server: 103.181.164.145
    port: 54022
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_1
    type: vmess
    server: 103.181.164.237
    port: 52283
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_2
    type: vmess
    server: 120.232.240.91
    port: 50016
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_3
    type: vmess
    server: 120.232.240.91
    port: 50018
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_4
    type: vmess
    server: 120.232.240.91
    port: 50003
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_5
    type: vmess
    server: 120.232.240.91
    port: 50009
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_6
    type: vmess
    server: 120.232.240.91
    port: 50017
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_7
    type: vmess
    server: 120.232.240.91
    port: 50020
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_8
    type: vmess
    server: 120.232.240.91
    port: 50023
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_9
    type: vmess
    server: 120.232.240.91
    port: 50026
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_10
    type: vmess
    server: 120.232.240.91
    port: 50013
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_11
    type: vmess
    server: 120.232.240.91
    port: 50019
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_12
    type: vmess
    server: 141.11.21.219
    port: 50521
    uuid: 7b4c6795-3be5-4a4e-b234-07a46f580c45
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    servername: a.sezar.top
  - name: 3.12免费节点_13
    type: vmess
    server: pub.ap20260228.com
    port: 64097
    uuid: a739e782-1682-38a5-9153-aad09d779ae9
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_14
    type: vmess
    server: pub.ap20260228.com
    port: 64018
    uuid: a739e782-1682-38a5-9153-aad09d779ae9
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_15
    type: vmess
    server: pub.ap20260228.com
    port: 64003
    uuid: a739e782-1682-38a5-9153-aad09d779ae9
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_16
    type: vmess
    server: pub.ap20260228.com
    port: 64021
    uuid: a739e782-1682-38a5-9153-aad09d779ae9
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_17
    type: vmess
    server: 38.55.193.199
    port: 443
    uuid: 462d9694-62b5-4781-a287-61a422b920e8
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    servername: mn1ray.jagoanvip.xyz
    network: ws
    ws-opts:
      path: /vvip
      headers:
        Host: mn1ray.jagoanvip.xyz
  - name: 3.12免费节点_18
    type: vmess
    server: pub.ap20260228.com
    port: 64014
    uuid: a739e782-1682-38a5-9153-aad09d779ae9
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_19
    type: vmess
    server: 120.232.240.91
    port: 50001
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_20
    type: vmess
    server: 120.232.240.91
    port: 50011
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_21
    type: vmess
    server: 120.232.240.91
    port: 50028
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_22
    type: vmess
    server: 120.232.240.91
    port: 50005
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_23
    type: vmess
    server: 120.232.240.91
    port: 50024
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_24
    type: vmess
    server: 120.232.240.91
    port: 50012
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_25
    type: vmess
    server: 120.232.240.91
    port: 50002
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_26
    type: vmess
    server: 120.232.240.91
    port: 50029
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_27
    type: vmess
    server: v24.hdacd.com
    port: 30824
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 2
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_28
    type: vmess
    server: 120.232.240.91
    port: 50008
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_29
    type: vmess
    server: v8.hdacd.com
    port: 30808
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 2
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_30
    type: vmess
    server: 120.232.240.91
    port: 50010
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_31
    type: vmess
    server: 14.17.78.206
    port: 30000
    uuid: 024e75ef-d773-451f-b65c-c0059d53bce6
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_32
    type: vmess
    server: d.naiun.cac.cab
    port: 30201
    uuid: 9e697517-693f-4019-be45-3c4861b1b0b8
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
    network: ws
    ws-opts:
      path: /
      headers:
        Host: live.bilibili.com
  - name: 3.12免费节点_33
    type: vmess
    server: b.naiun.cac.cab
    port: 30201
    uuid: 9e697517-693f-4019-be45-3c4861b1b0b8
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
    network: ws
    ws-opts:
      path: /
      headers:
        Host: live.bilibili.com
  - name: 3.12免费节点_34
    type: vmess
    server: 216.167.101.148
    port: 58976
    uuid: 841dc449-5bde-4a3f-81ba-d068f965cfd7
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_35
    type: vmess
    server: 120.232.240.91
    port: 50006
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_36
    type: vmess
    server: 120.232.240.91
    port: 50021
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.12免费节点_37
    type: vmess
    server: 120.232.240.91
    port: 50014
    uuid: ef35bcc2-b0ae-4fd3-bc77-d82162696a2d
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
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
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
      - 3.12免费节点
      - 3.12免费节点_1
      - 3.12免费节点_2
      - 3.12免费节点_3
      - 3.12免费节点_4
      - 3.12免费节点_5
      - 3.12免费节点_6
      - 3.12免费节点_7
      - 3.12免费节点_8
      - 3.12免费节点_9
      - 3.12免费节点_10
      - 3.12免费节点_11
      - 3.12免费节点_12
      - 3.12免费节点_13
      - 3.12免费节点_14
      - 3.12免费节点_15
      - 3.12免费节点_16
      - 3.12免费节点_17
      - 3.12免费节点_18
      - 3.12免费节点_19
      - 3.12免费节点_20
      - 3.12免费节点_21
      - 3.12免费节点_22
      - 3.12免费节点_23
      - 3.12免费节点_24
      - 3.12免费节点_25
      - 3.12免费节点_26
      - 3.12免费节点_27
      - 3.12免费节点_28
      - 3.12免费节点_29
      - 3.12免费节点_30
      - 3.12免费节点_31
      - 3.12免费节点_32
      - 3.12免费节点_33
      - 3.12免费节点_34
      - 3.12免费节点_35
      - 3.12免费节点_36
      - 3.12免费节点_37
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
