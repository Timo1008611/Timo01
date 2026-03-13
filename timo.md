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
  - name: 3.13.2免费节点
    type: vless
    server: 141.11.21.219
    port: 53458
    uuid: de73ea62-68e4-45e2-8cc3-87c6d4b23aa0
    servername: a.sezar.top
    tls: true
  - name: 3.13.2免费节点_1
    type: vmess
    server: 103.181.164.237
    port: 52283
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_2
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
  - name: 3.13.2免费节点_3
    type: vmess
    server: 103.181.164.145
    port: 54022
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_4
    type: vless
    server: 198.41.208.22
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.site
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.site
  - name: 3.13.2免费节点_5
    type: vless
    server: 198.41.209.105
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.syt.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.syt.pp.ua
  - name: 3.13.2免费节点_6
    type: vless
    server: 162.159.38.182
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.ccff.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.ccff.de5.net
  - name: 3.13.2免费节点_7
    type: vless
    server: 162.159.26.142
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip1.zrfme.site
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip1.zrfme.site
  - name: 3.13.2免费节点_8
    type: vless
    server: 162.159.45.66
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.gm.ug.cx
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.gm.ug.cx
  - name: 3.13.2免费节点_9
    type: vless
    server: staticdelivery.nexusmods.com
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.subs.indevs.in
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.subs.indevs.in
  - name: 3.13.2免费节点_10
    type: vless
    server: 162.159.44.52
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: zrfs.sylu.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: zrfs.sylu.net
  - name: 3.13.2免费节点_11
    type: vless
    server: 162.159.39.194
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfnb.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfnb.de5.net
  - name: 3.13.2免费节点_12
    type: vless
    server: 162.159.39.61
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfn.indevs.in
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfn.indevs.in
  - name: 3.13.2免费节点_13
    type: vless
    server: 162.159.44.52
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip2.zrfme.site
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip2.zrfme.site
  - name: 3.13.2免费节点_14
    type: vless
    server: 162.159.39.116
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.ere.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.ere.de5.net
  - name: 3.13.2免费节点_15
    type: vless
    server: staticdelivery.nexusmods.com
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.com.cfd
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.com.cfd
  - name: 3.13.2免费节点_16
    type: vless
    server: 162.159.62.217
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.drd.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.drd.pp.ua
  - name: 3.13.2免费节点_17
    type: vless
    server: 104.18.40.30
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.ee.cd
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.ee.cd
  - name: 3.13.2免费节点_18
    type: vless
    server: 162.159.43.232
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.us.ci
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.us.ci
  - name: 3.13.2免费节点_19
    type: vless
    server: 162.159.13.156
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfs.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfs.pp.ua
  - name: 3.13.2免费节点_20
    type: vless
    server: 162.159.45.250
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.syt.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.syt.pp.ua
  - name: 3.13.2免费节点_21
    type: vless
    server: 162.159.44.79
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.durl.dpdns.org
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.durl.dpdns.org
  - name: 3.13.2免费节点_22
    type: vless
    server: store.ubi.com
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.qqq.hidns.co
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.qqq.hidns.co
  - name: 3.13.2免费节点_23
    type: vless
    server: 162.159.44.243
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.xyz
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.xyz
  - name: 3.13.2免费节点_24
    type: vless
    server: 162.159.38.245
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfnb.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfnb.pp.ua
  - name: 3.13.2免费节点_25
    type: vless
    server: 162.159.39.225
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.indevs.in
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.indevs.in
  - name: 3.13.2免费节点_26
    type: vless
    server: 162.159.61.129
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.111.hidns.vip
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.111.hidns.vip
  - name: 3.13.2免费节点_27
    type: vless
    server: 162.159.24.5
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfs.nn.kg
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfs.nn.kg
  - name: 3.13.2免费节点_28
    type: vless
    server: 162.159.39.153
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.gv.uy
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.gv.uy
  - name: 3.13.2免费节点_29
    type: vless
    server: store.ubi.com
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfnoe.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfnoe.pp.ua
  - name: 3.13.2免费节点_30
    type: vless
    server: 104.17.146.99
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.ddly.dpdns.org
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.ddly.dpdns.org
  - name: 3.13.2免费节点_31
    type: vless
    server: 162.159.45.138
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.asss.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.asss.pp.ua
  - name: 3.13.2免费节点_32
    type: vless
    server: 104.19.40.252
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.site
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.site
  - name: 3.13.2免费节点_33
    type: vless
    server: 162.159.44.60
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfsub.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfsub.pp.ua
  - name: 3.13.2免费节点_34
    type: vless
    server: 162.159.45.171
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.ndjp.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.ndjp.net
  - name: 3.13.2免费节点_35
    type: vless
    server: 104.18.38.145
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.lsmoo.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.lsmoo.pp.ua
  - name: 3.13.2免费节点_36
    type: vless
    server: 104.19.138.39
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.ddly.dpdns.org
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.ddly.dpdns.org
  - name: 3.13.2免费节点_37
    type: vless
    server: 162.159.152.73
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.ndjp.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.ndjp.net
  - name: 3.13.2免费节点_38
    type: vless
    server: 104.17.93.65
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.subs.indevs.in
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.subs.indevs.in
  - name: 3.13.2免费节点_39
    type: vless
    server: 162.159.235.195
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: zrfs.sylu.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: zrfs.sylu.net
  - name: 3.13.2免费节点_40
    type: vless
    server: www.visa.cn
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip1.aizrf.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip1.aizrf.de5.net
  - name: 3.13.2免费节点_41
    type: vless
    server: 104.17.94.139
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.lsmoo.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.lsmoo.pp.ua
  - name: 3.13.2免费节点_42
    type: vless
    server: 162.159.38.182
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.loc.cc
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.loc.cc
  - name: 3.13.2免费节点_43
    type: vless
    server: 162.159.236.35
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfv.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfv.pp.ua
  - name: 3.13.2免费节点_44
    type: vless
    server: 104.17.233.124
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.ccwu.cc
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.ccwu.cc
  - name: 3.13.2免费节点_45
    type: vless
    server: 104.18.85.223
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.ndjp.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.ndjp.net
  - name: 3.13.2免费节点_46
    type: vless
    server: 104.26.14.182
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.ee.cd
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.ee.cd
  - name: 3.13.2免费节点_47
    type: vless
    server: 104.19.58.9
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.eea.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.eea.pp.ua
  - name: 3.13.2免费节点_48
    type: vless
    server: cloudflare.182682.xyz
    port: 8080
    uuid: bec1ba6b-606c-442d-8181-588e4343bcde
    network: ws
    tls: false
    ws-opts:
      path: bec1ba6b
      headers:
        Host: supporting-washington-kilometers-poly.trycloudflare.com
  - name: 3.13.2免费节点_49
    type: vless
    server: 104.17.163.111
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfnoe.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfnoe.pp.ua
  - name: 3.13.2免费节点_50
    type: vless
    server: 104.19.37.168
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.subs.indevs.in
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.subs.indevs.in
  - name: 3.13.2免费节点_51
    type: vless
    server: 104.26.10.21
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.drr.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.drr.pp.ua
  - name: 3.13.2免费节点_52
    type: vless
    server: 104.26.13.111
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfme.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfme.pp.ua
  - name: 3.13.2免费节点_53
    type: vless
    server: 104.19.55.58
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfs.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfs.pp.ua
  - name: 3.13.2免费节点_54
    type: vless
    server: 23.144.124.6
    port: 50080
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_55
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
  - name: 3.13.2免费节点_56
    type: trojan
    server: cool-lioness.rooster465.autos
    port: 443
    password: ZY07256934
    skip-cert-verify: false
    tls: false
  - name: 3.13.2免费节点_57
    type: vless
    server: 154.211.8.18
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfsub.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfsub.pp.ua
  - name: 3.13.2免费节点_58
    type: vless
    server: 175.208.111.195
    port: 50001
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_59
    type: vless
    server: 211.245.68.145
    port: 10088
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_60
    type: vless
    server: 14.47.40.12
    port: 30910
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_61
    type: vless
    server: 222.109.53.68
    port: 10162
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_62
    type: vless
    server: 203.170.125.48
    port: 34273
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_63
    type: vless
    server: 203.170.125.48
    port: 26074
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_64
    type: vless
    server: 221.145.26.198
    port: 18791
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_65
    type: vless
    server: 211.57.249.235
    port: 50001
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_66
    type: vless
    server: 222.113.169.156
    port: 14100
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_67
    type: vless
    server: 211.194.9.159
    port: 20244
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_68
    type: vless
    server: 146.56.45.128
    port: 32157
    uuid: 14b02e2a-8930-4afb-8412-ea4a4954ca5b
    network: ws
    servername: ylnhh.cc.cd
    tls: true
    ws-opts:
      path: /Telegram🇨🇳 @WangCai2
      headers:
        Host: ylnhh.cc.cd
  - name: 3.13.2免费节点_69
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
  - name: 3.13.2免费节点_70
    type: vless
    server: 8.39.125.91
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.111.hidns.vip
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.111.hidns.vip
  - name: 3.13.2免费节点_71
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
  - name: 3.13.2免费节点_72
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
  - name: 3.13.2免费节点_73
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
  - name: 3.13.2免费节点_74
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
  - name: 3.13.2免费节点_75
    type: trojan
    server: delicate-buck.rooster465.autos
    port: 443
    password: ZY07256934
    skip-cert-verify: false
    tls: false
  - name: 3.13.2免费节点_76
    type: vless
    server: 27.50.48.8
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.gv.uy
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.gv.uy
  - name: 3.13.2免费节点_77
    type: trojan
    server: free-duckling.rooster465.autos
    port: 443
    password: ZY07256934
    skip-cert-verify: false
    tls: false
  - name: 3.13.2免费节点_78
    type: vless
    server: 172.64.229.178
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.vurl.dpdns.org
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.vurl.dpdns.org
  - name: 3.13.2免费节点_79
    type: vless
    server: 173.245.59.142
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfsub.de5.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfsub.de5.net
  - name: 3.13.2免费节点_80
    type: vless
    server: 173.245.59.198
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.aww.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.aww.pp.ua
  - name: 3.13.2免费节点_81
    type: vless
    server: 173.245.59.240
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.drr.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.drr.pp.ua
  - name: 3.13.2免费节点_82
    type: vless
    server: 166.117.33.104
    port: 443
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_83
    type: vless
    server: 173.245.59.89
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip2.zrfme.site
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip2.zrfme.site
  - name: 3.13.2免费节点_84
    type: vless
    server: zrf666.cf.090227.xyz
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.ndjp.net
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.ndjp.net
  - name: 3.13.2免费节点_85
    type: vless
    server: time.is
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.lsmoo.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.lsmoo.pp.ua
  - name: 3.13.2免费节点_86
    type: vless
    server: 172.64.157.102
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfnb.indevs.in
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfnb.indevs.in
  - name: 3.13.2免费节点_87
    type: vless
    server: staticdelivery.nexusmods.com
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrf.bbroot.com
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrf.bbroot.com
  - name: 3.13.2免费节点_88
    type: vless
    server: 172.67.68.213
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.ees.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.ees.pp.ua
  - name: 3.13.2免费节点_89
    type: vless
    server: time.is
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.cfsub.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.cfsub.pp.ua
  - name: 3.13.2免费节点_90
    type: vless
    server: 172.67.119.77
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.gm.ug.cx
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.gm.ug.cx
  - name: 3.13.2免费节点_91
    type: vless
    server: icook.tw
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.zrfs.nn.kg
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.zrfs.nn.kg
  - name: 3.13.2免费节点_92
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
  - name: 3.13.2免费节点_93
    type: vless
    server: 172.67.66.72
    port: 443
    uuid: 3ad8ffb8-f1b2-4a86-93f6-e0edf6891d15
    network: ws
    servername: snip.asss.pp.ua
    tls: true
    ws-opts:
      path: /?ed=2560
      headers:
        Host: snip.asss.pp.ua
  - name: 3.13.2免费节点_94
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
  - name: 3.13.2免费节点_95
    type: vless
    server: 204.197.163.166
    port: 8500
    uuid: 948fac3c-42bf-41a6-a5f9-704d36ff0d8d
    network: ws
    servername: snippet.danfeng.theworkpc.com
    tls: true
    ws-opts:
      path: /danfeng?ed=2560
      headers:
        Host: snippet.danfeng.theworkpc.com
  - name: 3.13.2免费节点_96
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
  - name: 3.13.2免费节点_97
    type: ss
    server: iepl.huli168.com
    port: 19822
    cipher: aes-256-gcm
    password: g4JtpkuxkwRH4jhj
  - name: 3.13.2免费节点_98
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_99
    type: vmess
    server: 38.55.194.138
    port: 443
    uuid: 462d9694-62b5-4781-a287-61a422b920e8
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    network: ws
    ws-opts:
      path: /vvip
      headers:
        Host: mn1ray.jagoanvip.xyz
  - name: 3.13.2免费节点_100
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_101
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_102
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_103
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_104
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_105
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_106
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_107
    type: vmess
    server: 83.229.121.113
    port: 443
    uuid: 462d9694-62b5-4781-a287-61a422b920e8
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    network: ws
    ws-opts:
      path: /vvip
      headers:
        Host: mn1ray.jagoanvip.xyz
  - name: 3.13.2免费节点_108
    type: vmess
    server: 38.55.193.78
    port: 443
    uuid: 462d9694-62b5-4781-a287-61a422b920e8
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    network: ws
    ws-opts:
      path: /vvip
      headers:
        Host: mn1ray.jagoanvip.xyz
  - name: 3.13.2免费节点_109
    type: vmess
    server: 43.134.87.15
    port: 443
    uuid: 462d9694-62b5-4781-a287-61a422b920e8
    alterId: 0
    cipher: auto
    tls: true
    skip-cert-verify: false
    network: ws
    ws-opts:
      path: /vvip
      headers:
        Host: mn1ray.jagoanvip.xyz
  - name: 3.13.2免费节点_110
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_111
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_112
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_113
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_114
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_115
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_116
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_117
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_118
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_119
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_120
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_121
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_122
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_123
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_124
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_125
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_126
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_127
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_128
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_129
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_130
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_131
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_132
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_133
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_134
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_135
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_136
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_137
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_138
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_139
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_140
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_141
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_142
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_143
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_144
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_145
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_146
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_147
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_148
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_149
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_150
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_151
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_152
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_153
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_154
    type: vmess
    server: 103.181.164.237
    port: 34114
    uuid: 418048af-a293-4b99-9b0c-98ca3580dd24
    alterId: 64
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_155
    type: vmess
    server: v12.hdacd.com
    port: 30812
    uuid: cbb3f877-d1fb-344c-87a9-d153bffd5484
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_156
    type: vless
    server: 162.159.152.17
    port: 443
    uuid: 081efe27-f6b8-4f60-aedb-3c9effe9c67d
    network: ws
    servername: 80bab3a2.gon-7ye.pages.dev
    tls: true
    ws-opts:
      path: /
      headers:
        Host: 80bab3a2.gon-7ye.pages.dev
  - name: 3.13.2免费节点_157
    type: vmess
    server: 82.198.246.97
    port: 180
    uuid: d13fc2f5-3e05-4795-81eb-44143a09e552
    alterId: 0
    cipher: auto
    tls: false
    skip-cert-verify: false
  - name: 3.13.2免费节点_158
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
  - name: 3.13.2免费节点_159
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
  - name: 3.13.2免费节点_160
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
  - name: 3.13.2免费节点_161
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
  - name: 3.13.2免费节点_162
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
  - name: 3.13.2免费节点_163
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
  - name: 3.13.2免费节点_164
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
  - name: 3.13.2免费节点_165
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
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
  - name: ♻️ 自动选择
    type: url-test
    proxies:
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
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
      - 3.13.2免费节点
      - 3.13.2免费节点_1
      - 3.13.2免费节点_2
      - 3.13.2免费节点_3
      - 3.13.2免费节点_4
      - 3.13.2免费节点_5
      - 3.13.2免费节点_6
      - 3.13.2免费节点_7
      - 3.13.2免费节点_8
      - 3.13.2免费节点_9
      - 3.13.2免费节点_10
      - 3.13.2免费节点_11
      - 3.13.2免费节点_12
      - 3.13.2免费节点_13
      - 3.13.2免费节点_14
      - 3.13.2免费节点_15
      - 3.13.2免费节点_16
      - 3.13.2免费节点_17
      - 3.13.2免费节点_18
      - 3.13.2免费节点_19
      - 3.13.2免费节点_20
      - 3.13.2免费节点_21
      - 3.13.2免费节点_22
      - 3.13.2免费节点_23
      - 3.13.2免费节点_24
      - 3.13.2免费节点_25
      - 3.13.2免费节点_26
      - 3.13.2免费节点_27
      - 3.13.2免费节点_28
      - 3.13.2免费节点_29
      - 3.13.2免费节点_30
      - 3.13.2免费节点_31
      - 3.13.2免费节点_32
      - 3.13.2免费节点_33
      - 3.13.2免费节点_34
      - 3.13.2免费节点_35
      - 3.13.2免费节点_36
      - 3.13.2免费节点_37
      - 3.13.2免费节点_38
      - 3.13.2免费节点_39
      - 3.13.2免费节点_40
      - 3.13.2免费节点_41
      - 3.13.2免费节点_42
      - 3.13.2免费节点_43
      - 3.13.2免费节点_44
      - 3.13.2免费节点_45
      - 3.13.2免费节点_46
      - 3.13.2免费节点_47
      - 3.13.2免费节点_48
      - 3.13.2免费节点_49
      - 3.13.2免费节点_50
      - 3.13.2免费节点_51
      - 3.13.2免费节点_52
      - 3.13.2免费节点_53
      - 3.13.2免费节点_54
      - 3.13.2免费节点_55
      - 3.13.2免费节点_56
      - 3.13.2免费节点_57
      - 3.13.2免费节点_58
      - 3.13.2免费节点_59
      - 3.13.2免费节点_60
      - 3.13.2免费节点_61
      - 3.13.2免费节点_62
      - 3.13.2免费节点_63
      - 3.13.2免费节点_64
      - 3.13.2免费节点_65
      - 3.13.2免费节点_66
      - 3.13.2免费节点_67
      - 3.13.2免费节点_68
      - 3.13.2免费节点_69
      - 3.13.2免费节点_70
      - 3.13.2免费节点_71
      - 3.13.2免费节点_72
      - 3.13.2免费节点_73
      - 3.13.2免费节点_74
      - 3.13.2免费节点_75
      - 3.13.2免费节点_76
      - 3.13.2免费节点_77
      - 3.13.2免费节点_78
      - 3.13.2免费节点_79
      - 3.13.2免费节点_80
      - 3.13.2免费节点_81
      - 3.13.2免费节点_82
      - 3.13.2免费节点_83
      - 3.13.2免费节点_84
      - 3.13.2免费节点_85
      - 3.13.2免费节点_86
      - 3.13.2免费节点_87
      - 3.13.2免费节点_88
      - 3.13.2免费节点_89
      - 3.13.2免费节点_90
      - 3.13.2免费节点_91
      - 3.13.2免费节点_92
      - 3.13.2免费节点_93
      - 3.13.2免费节点_94
      - 3.13.2免费节点_95
      - 3.13.2免费节点_96
      - 3.13.2免费节点_97
      - 3.13.2免费节点_98
      - 3.13.2免费节点_99
      - 3.13.2免费节点_100
      - 3.13.2免费节点_101
      - 3.13.2免费节点_102
      - 3.13.2免费节点_103
      - 3.13.2免费节点_104
      - 3.13.2免费节点_105
      - 3.13.2免费节点_106
      - 3.13.2免费节点_107
      - 3.13.2免费节点_108
      - 3.13.2免费节点_109
      - 3.13.2免费节点_110
      - 3.13.2免费节点_111
      - 3.13.2免费节点_112
      - 3.13.2免费节点_113
      - 3.13.2免费节点_114
      - 3.13.2免费节点_115
      - 3.13.2免费节点_116
      - 3.13.2免费节点_117
      - 3.13.2免费节点_118
      - 3.13.2免费节点_119
      - 3.13.2免费节点_120
      - 3.13.2免费节点_121
      - 3.13.2免费节点_122
      - 3.13.2免费节点_123
      - 3.13.2免费节点_124
      - 3.13.2免费节点_125
      - 3.13.2免费节点_126
      - 3.13.2免费节点_127
      - 3.13.2免费节点_128
      - 3.13.2免费节点_129
      - 3.13.2免费节点_130
      - 3.13.2免费节点_131
      - 3.13.2免费节点_132
      - 3.13.2免费节点_133
      - 3.13.2免费节点_134
      - 3.13.2免费节点_135
      - 3.13.2免费节点_136
      - 3.13.2免费节点_137
      - 3.13.2免费节点_138
      - 3.13.2免费节点_139
      - 3.13.2免费节点_140
      - 3.13.2免费节点_141
      - 3.13.2免费节点_142
      - 3.13.2免费节点_143
      - 3.13.2免费节点_144
      - 3.13.2免费节点_145
      - 3.13.2免费节点_146
      - 3.13.2免费节点_147
      - 3.13.2免费节点_148
      - 3.13.2免费节点_149
      - 3.13.2免费节点_150
      - 3.13.2免费节点_151
      - 3.13.2免费节点_152
      - 3.13.2免费节点_153
      - 3.13.2免费节点_154
      - 3.13.2免费节点_155
      - 3.13.2免费节点_156
      - 3.13.2免费节点_157
      - 3.13.2免费节点_158
      - 3.13.2免费节点_159
      - 3.13.2免费节点_160
      - 3.13.2免费节点_161
      - 3.13.2免费节点_162
      - 3.13.2免费节点_163
      - 3.13.2免费节点_164
      - 3.13.2免费节点_165
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
