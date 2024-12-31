路由规则
https://wiki.metacubex.one/config/rules/?h=domain+suffix#domain-regex

DOMAIN：完整域名匹配

如：DOMAIN, www.apple.com, Proxy

如果请求的域完全匹配，则规则匹配。

DOMAIN-SUFFIX：匹配域名后缀

如：DOMAIN-SUFFIX, apple.com, Proxy

如果请求的域匹配后缀，则规则匹配。例如：apple.com 可匹配 www.apple.com、itunse.apple.com 和 apple.com

DOMAIN-KEYWORD：域名关键词匹配

如：DOMAIN-KEYWORD, apple, Proxy

如果请求的域包含关键字，则规则匹配。例如：www.apple.com、itunes.apple.com、apple.com、applemusic.com

HOST-WILDCARD 规则是 QuantumultX 规则

HOST-WILDCARD：域名通配符匹配

如：HOST-WILDCARD, * apple.com, proxy

支持通配符  *和？：*.goo?le.com 
