[General]
dns-server = system
ipv6 = false

[Rule]
# === 三家券商 最高优先级 强制海外代理（放在最前面）===
DOMAIN-SUFFIX,collect.futunn.com,PROXY
DOMAIN-SUFFIX,futunn.com,PROXY
DOMAIN-SUFFIX,moomoo.com,PROXY
DOMAIN-SUFFIX,futuniu.com,PROXY
DOMAIN-SUFFIX,futustatic.com,PROXY
DOMAIN-SUFFIX,futuhk.com,PROXY
DOMAIN-SUFFIX,futu.com,PROXY
DOMAIN-SUFFIX,api.futunn.com,PROXY
DOMAIN-SUFFIX,trade.futunn.com,PROXY
DOMAIN-SUFFIX,quote.futunn.com,PROXY
DOMAIN-SUFFIX,static.futunn.com,PROXY
DOMAIN-SUFFIX,push.futunn.com,PROXY
DOMAIN-SUFFIX,sec.futunn.com,PROXY

DOMAIN-SUFFIX,longbridge.com,PROXY
DOMAIN-SUFFIX,lbkrs.com,PROXY
DOMAIN-SUFFIX,longbridge.hk,PROXY
DOMAIN-SUFFIX,openapi.longbridge.com,PROXY

DOMAIN-SUFFIX,tigerbrokers.com,PROXY
DOMAIN-SUFFIX,itiger.com,PROXY
DOMAIN-SUFFIX,tigertrade.app,PROXY
DOMAIN-SUFFIX,api.itiger.com,PROXY
DOMAIN-SUFFIX,trade.itiger.com,PROXY
DOMAIN-SUFFIX,quote.itiger.com,PROXY

# 关键词加强
DOMAIN-KEYWORD,futunn,PROXY
DOMAIN-KEYWORD,moomoo,PROXY
DOMAIN-KEYWORD,futu,PROXY
DOMAIN-KEYWORD,longbridge,PROXY
DOMAIN-KEYWORD,lbkrs,PROXY
DOMAIN-KEYWORD,tiger,PROXY
DOMAIN-KEYWORD,itiger,PROXY

# 国内主流App直连 + 其他海外走代理
RULE-SET,https://johnshall.github.io/Shadowrocket-ADBlock-Rules-Forever/sr_top500_whitelist.conf,PROXY

# 兜底
FINAL,PROXY
