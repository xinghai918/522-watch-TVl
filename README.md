port: 7890
socks-port: 7891
allow-lan: true
mode: Rule
log-level: info
external-controller: :9090
proxies:
  - {name: (感谢关注youtube：8度科技) 54, server: cc.hciahciphcie.club, port: 443, type: vmess, uuid: 9a297bb1-06e3-4e6f-97fa-3d3202d46596, alterId: 2, cipher: auto, tls: true, skip-cert-verify: false, network: ws, ws-path: /84c3f/, ws-headers: {Host: cc.hciahciphcie.club}, udp: true}
  - {name: 🇲🇾 github.com/freefq - 马来西亚  7, server: 118.107.244.110, port: 5003, type: ss, cipher: aes-256-gcm, password: g5MeD6Ft3CWlJId, udp: true}
  - {name: 🇷🇺 github.com/freefq - 俄罗斯  14, server: t8.ssrsub.com, port: 11033, type: trojan, password: a0daa9d9-6257-4ae9-9959-ccfb993f122c, sni: t8.ssrsub.com, skip-cert-verify: false, udp: true}
  - {name: 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11, server: t1.ssrsub.com, port: 11033, type: trojan, password: a0daa9d9-6257-4ae9-9959-ccfb993f122c, sni: t1.ssrsub.com, skip-cert-verify: false, udp: true}
  - {name: 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4, server: t1.ssrsub.com, port: 11033, type: trojan, password: a0daa9d9-6257-4ae9-9959-ccfb993f122c, sni: t1.ssrsub.com, skip-cert-verify: false, udp: true}
  - {name: 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18, server: t5.ssrsub.com, port: 11033, type: trojan, password: a0daa9d9-6257-4ae9-9959-ccfb993f122c, sni: t5.ssrsub.com, skip-cert-verify: false, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  1, server: 134.195.196.71, port: 2375, type: ss, cipher: aes-256-gcm, password: faBAoD54k87UJG7, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  16, server: 198.57.27.218, port: 2376, type: ss, cipher: aes-256-gcm, password: faBAoD54k87UJG7, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  17, server: 134.195.198.252, port: 2376, type: ss, cipher: aes-256-gcm, password: faBAoD54k87UJG7, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  2, server: 134.195.196.214, port: 5004, type: ss, cipher: aes-256-gcm, password: g5MeD6Ft3CWlJId, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  4, server: 134.195.196.214, port: 8080, type: ss, cipher: aes-256-gcm, password: KixLvKzwjekG00rm, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  5, server: 134.195.196.154, port: 7307, type: ss, cipher: aes-256-gcm, password: FoOiGlkAA9yPEGP, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  6, server: 134.195.198.178, port: 8090, type: ss, cipher: aes-256-gcm, password: PCnnH6SQSnfoS27, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  7, server: 134.195.198.95, port: 7306, type: ss, cipher: aes-256-gcm, password: FoOiGlkAA9yPEGP, udp: true}
  - {name: 🇺🇸 github.com/freefq - 北美地区  8, server: 134.195.198.252, port: 2375, type: ss, cipher: aes-256-gcm, password: faBAoD54k87UJG7, udp: true}
proxy-groups:
  - name: 🚀 节点选择
    type: select
    proxies:
      - ♻️ 自动选择
      - DIRECT
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: ♻️ 自动选择
    type: url-test
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
    proxies:
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: 🌍 国外媒体
    type: select
    proxies:
      - 🚀 节点选择
      - ♻️ 自动选择
      - 🎯 全球直连
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: 📲 电报信息
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: Ⓜ️ 微软服务
    type: select
    proxies:
      - 🎯 全球直连
      - 🚀 节点选择
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: 🍎 苹果服务
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: 📢 谷歌FCM
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - ♻️ 自动选择
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
  - name: 🎯 全球直连
    type: select
    proxies:
      - DIRECT
      - 🚀 节点选择
      - ♻️ 自动选择
  - name: 🐟 漏网之鱼
    type: select
    proxies:
      - 🚀 节点选择
      - 🎯 全球直连
      - ♻️ 自动选择
      - (感谢关注youtube：8度科技) 54
      - 🇲🇾 github.com/freefq - 马来西亚  7
      - 🇷🇺 github.com/freefq - 俄罗斯  14
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 11
      - 🇷🇺 github.com/freefq - 俄罗斯克拉斯诺亚尔斯克G-Core Lab 4
      - 🇷🇺 github.com/freefq - 俄罗斯新西伯利亚州新西伯利亚 18
      - 🇺🇸 github.com/freefq - 北美地区  1
      - 🇺🇸 github.com/freefq - 北美地区  16
      - 🇺🇸 github.com/freefq - 北美地区  17
      - 🇺🇸 github.com/freefq - 北美地区  2
      - 🇺🇸 github.com/freefq - 北美地区  4
      - 🇺🇸 github.com/freefq - 北美地区  5
      - 🇺🇸 github.com/freefq - 北美地区  6
      - 🇺🇸 github.com/freefq - 北美地区  7
      - 🇺🇸 github.com/freefq - 北美地区  8
rules:
 - GEOIP,CN,🎯 全球直连
 - MATCH,🐟 漏网之鱼
