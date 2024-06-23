{
  "log": {
    "level": "warn",
    "output": "box.log",
    "timestamp": true
  },
  "dns": {
    "servers": [
      {
        "tag": "dns-remote",
        "address": "udp://1.1.1.1",
        "address_resolver": "dns-direct"
      },
      {
        "tag": "dns-trick-direct",
        "address": "https://sky.rethinkdns.com/",
        "detour": "direct-fragment"
      },
      {
        "tag": "dns-direct",
        "address": "1.1.1.1",
        "address_resolver": "dns-local",
        "detour": "direct"
      },
      {
        "tag": "dns-local",
        "address": "local",
        "detour": "direct"
      },
      {
        "tag": "dns-block",
        "address": "rcode://success"
      }
    ],
    "rules": [
      {
        "domain": [
          "ast.giga-downloader.com",
          "ask.giga-downloader.com",
          "fnv.giga-downloader.com",
          "sbn.giga-downloader.com",
          "mcic.giga-downloader.com",
          "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
          "rtlc.giga-downloader.com",
          "hwb.giga-downloader.com",
          "ptk.giga-downloader.com",
          "mci.giga-downloader.com",
          "arx.giga-downloader.com",
          "mtn.giga-downloader.com",
          "sht.giga-downloader.com",
          "mbt.giga-downloader.com",
          "speed.cloudflare.com",
          "upload.ir",
          "mkh.giga-downloader.com",
          "psm.giga-downloader.com",
          "shm.giga-downloader.com",
          "fnp.giga-downloader.com",
          "prs.giga-downloader.com",
          "dbn.giga-downloader.com",
          "rsp.giga-downloader.com",
          "atc.giga-downloader.com",
          "www.speedtest.net",
          "rtl.giga-downloader.com",
          "mkhc.giga-downloader.com",
          "smt.giga-downloader.com",
          "apt.giga-downloader.com",
          "mtnc.giga-downloader.com",
          "afn.giga-downloader.com",
          "ryn.giga-downloader.com"
        ],
        "server": "dns-direct"
      },
      {
        "domain_suffix": ".ir",
        "geosite": "ir",
        "server": "dns-direct"
      },
      {
        "domain": "cp.cloudflare.com",
        "server": "dns-remote",
        "rewrite_ttl": 3000
      }
    ],
    "final": "dns-remote",
    "static_ips": {
      "sky.rethinkdns.com": [
        "188.114.97.3",
        "188.114.96.3",
        "2a06:98c1:3121::3",
        "2a06:98c1:3120::3",
        "104.17.147.22",
        "104.17.148.22",
        "188.114.97.3",
        "188.114.96.3",
        "2a06:98c1:3120::3",
        "2a06:98c1:3121::3"
      ]
    },
    "independent_cache": true
  },
  "inbounds": [
    {
      "type": "tun",
      "tag": "tun-in",
      "mtu": 9000,
      "inet4_address": "172.19.0.1/28",
      "inet6_address": "fdfe:dcba:9876::1/126",
      "auto_route": true,
      "strict_route": true,
      "endpoint_independent_nat": true,
      "stack": "mixed",
      "sniff": true,
      "sniff_override_destination": true
    },
    {
      "type": "mixed",
      "tag": "mixed-in",
      "listen": "127.0.0.1",
      "listen_port": 2334,
      "sniff": true,
      "sniff_override_destination": true
    },
    {
      "type": "direct",
      "tag": "dns-in",
      "listen": "127.0.0.1",
      "listen_port": 6450
    }
  ],
  "outbounds": [
    {
      "type": "selector",
      "tag": "select",
      "outbounds": [
        "auto",
        "(1)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 0",
        "(2)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 1",
        "(3)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 2",
        "(4)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 3",
        "(5)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 4",
        "(6)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 5",
        "(7)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 6",
        "(8)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 7",
        "(9)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 8",
        "(10)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 9",
        "(11)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 10",
        "(12)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 11",
        "(13)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 12",
        "(14)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 13",
        "(15)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 14",
        "(16)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 15",
        "(17)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 16",
        "(18)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 17",
        "(19)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 18",
        "(20)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 19",
        "(21)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 20",
        "(22)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 21",
        "(23)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 22",
        "(24)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 23",
        "(25)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 24",
        "(26)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 25",
        "(27)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 26",
        "(28)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 27",
        "(29)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 28",
        "(30)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 29",
        "(31)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 30",
        "(32)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 31",
        "(33)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 32",
        "(34)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 33",
        "(35)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 34",
        "(36)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 35",
        "(37)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 36",
        "(38)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 37",
        "(39)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 38",
        "(40)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 39",
        "(41)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 40",
        "(42)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 41",
        "(43)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 42",
        "(44)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 43",
        "(45)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 44",
        "(46)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 45",
        "(47)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 46",
        "(48)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 47",
        "(49)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 48",
        "(50)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 49"
      ],
      "default": "auto"
    },
    {
      "type": "urltest",
      "tag": "auto",
      "outbounds": [
        "(1)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 0",
        "(2)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 1",
        "(3)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 2",
        "(4)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 3",
        "(5)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 4",
        "(6)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 5",
        "(7)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 6",
        "(8)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 7",
        "(9)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 8",
        "(10)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 9",
        "(11)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 10",
        "(12)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 11",
        "(13)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 12",
        "(14)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 13",
        "(15)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 14",
        "(16)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 15",
        "(17)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 16",
        "(18)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 17",
        "(19)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 18",
        "(20)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 19",
        "(21)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 20",
        "(22)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 21",
        "(23)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 22",
        "(24)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 23",
        "(25)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 24",
        "(26)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 25",
        "(27)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 26",
        "(28)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 27",
        "(29)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 28",
        "(30)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 29",
        "(31)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 30",
        "(32)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 31",
        "(33)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 32",
        "(34)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 33",
        "(35)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 34",
        "(36)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 35",
        "(37)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 36",
        "(38)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 37",
        "(39)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 38",
        "(40)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 39",
        "(41)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 40",
        "(42)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 41",
        "(43)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 42",
        "(44)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 43",
        "(45)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 44",
        "(46)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 45",
        "(47)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 46",
        "(48)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 47",
        "(49)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 48",
        "(50)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 49"
      ],
      "url": "http://cp.cloudflare.com/",
      "interval": "10m0s",
      "idle_timeout": "1h40m0s"
    },
    {
      "type": "vless",
      "tag": "(1)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 0",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mcic.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(2)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 1",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(3)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 2",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mci.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(4)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 3",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mtn.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(5)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 4",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mtnc.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(6)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 5",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "rtl.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(7)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 6",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "rtlc.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(8)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 7",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mkh.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(9)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 8",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mkhc.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(10)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 9",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "hwb.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(11)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 10",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "ast.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(12)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 11",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "sht.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(13)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 12",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "prs.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(14)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 13",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "mbt.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(15)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 14",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "ask.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(16)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 15",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "rsp.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(17)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 16",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "afn.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(18)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 17",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "psm.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(19)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 18",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "arx.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(20)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 19",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "smt.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(21)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 20",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "shm.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(22)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 21",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "fnv.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(23)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 22",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "dbn.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(24)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 23",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "apt.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(25)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 24",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "fnp.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(26)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 25",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "ryn.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(27)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 26",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "sbn.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(28)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 27",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "ptk.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vless",
      "tag": "(29)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 28",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "atc.giga-downloader.com",
      "server_port": 443,
      "uuid": "bc827d67-f095-4c65-9327-33039decb888",
      "tls": {
        "enabled": true,
        "server_name": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com",
        "utls": {
          "enabled": true,
          "fingerprint": "random"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/ws5/8082",
        "headers": {
          "Host": "123456789_123456789_123456789_123456789_123456789_123456789_000.giga-downloader.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vmess",
      "tag": "(30)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 29",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "172.67.170.103",
      "server_port": 443,
      "uuid": "76221bfb-e92f-4e80-81c5-6fe48f50ac0b",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "glweidf.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "glweidf.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vless",
      "tag": "(31)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 30",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "www.speedtest.net",
      "server_port": 443,
      "uuid": "8b7efacf-8e83-4e51-ab55-1263baccd4b2",
      "tls": {
        "enabled": true,
        "server_name": "7f905f51.garywelch.pages.dev",
        "utls": {
          "enabled": true,
          "fingerprint": "randomized"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/Tel-@V2ray_Alpha/",
        "headers": {
          "Host": "7f905f51.garywelch.pages.dev"
        },
        "max_early_data": 2560,
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vmess",
      "tag": "(32)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 31",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "172.67.131.108",
      "server_port": 443,
      "uuid": "1052f24e-7b09-45eb-b0c5-d858eb124192",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "glweidf.cfd",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "glweidf.cfd"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(33)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 32",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.21.44.106",
      "server_port": 443,
      "uuid": "93ea486a-bada-42a4-ac38-d088b320fa1e",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "xmivideo.cfd",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "xmivideo.cfd"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(34)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 33",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.21.15.212",
      "server_port": 443,
      "uuid": "76221bfb-e92f-4e80-81c5-6fe48f50ac0b",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "glweidf.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "glweidf.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(35)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 34",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "172.67.170.13",
      "server_port": 443,
      "uuid": "76221bfb-e92f-4e80-81c5-6fe48f50ac0b",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "glweidf.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "glweidf.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vless",
      "tag": "(36)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 35",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.18.202.232",
      "server_port": 443,
      "uuid": "17a7bf97-fef5-4101-a5c5-7c730fabeeee",
      "tls": {
        "enabled": true,
        "server_name": "bpb-worker-panel-h5f.pages.dev",
        "utls": {
          "enabled": true,
          "fingerprint": "firefox"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/",
        "headers": {
          "Host": "bpb-worker-panel-h5f.pages.dev"
        },
        "max_early_data": 2560,
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vmess",
      "tag": "(37)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 36",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.21.4.6",
      "server_port": 443,
      "uuid": "1052f24e-7b09-45eb-b0c5-d858eb124192",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "glweidf.cfd",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "glweidf.cfd"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(38)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 37",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "172.67.174.42",
      "server_port": 443,
      "uuid": "bc864078-dcf3-4bf4-8dbf-ca9f200b56be",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "gwdef.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "gwdef.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vless",
      "tag": "(39)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 38",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.21.40.63",
      "server_port": 443,
      "uuid": "03728bdd-745c-4ef6-a01f-70b006d3bbae",
      "tls": {
        "enabled": true,
        "server_name": "thorianite.toptechnonews.com",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/nimws",
        "headers": {
          "Host": "thorianite.toptechnonews.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vmess",
      "tag": "(40)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 39",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.21.83.108",
      "server_port": 443,
      "uuid": "6c168fcc-2231-4f3b-8c1e-f6391692df4a",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "hms02.fxiaomi.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/link",
        "headers": {
          "Host": "hms02.fxiaomi.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(41)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 40",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "172.67.161.77",
      "server_port": 443,
      "uuid": "edbb1059-1633-4271-b66e-ed4fba47a1bf",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "linde06.indiavideo.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "linde06.indiavideo.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(42)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 41",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "104.21.15.36",
      "server_port": 443,
      "uuid": "edbb1059-1633-4271-b66e-ed4fba47a1bf",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "linde06.indiavideo.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "linde06.indiavideo.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vless",
      "tag": "(43)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 42",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "190.93.246.241",
      "server_port": 443,
      "uuid": "beeedc2e-aaa6-4a60-b771-6daec05746d9",
      "tls": {
        "enabled": true,
        "server_name": "backup.github-land-pro-world-wiki-ped-discord-digikala-bale-meeting.com",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/49651/scenic_photo",
        "headers": {
          "Host": "backup.github-land-pro-world-wiki-ped-discord-digikala-bale-meeting.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vmess",
      "tag": "(44)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 43",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "172.67.196.112",
      "server_port": 443,
      "uuid": "edbb1059-1633-4271-b66e-ed4fba47a1bf",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "linde06.indiavideo.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "linde06.indiavideo.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(45)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 44",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "188.114.99.134",
      "server_port": 443,
      "uuid": "edbb1059-1633-4271-b66e-ed4fba47a1bf",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "linde06.indiavideo.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "linde06.indiavideo.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(46)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 45",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "188.114.99.183",
      "server_port": 443,
      "uuid": "edbb1059-1633-4271-b66e-ed4fba47a1bf",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "linde06.indiavideo.sbs",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "linde06.indiavideo.sbs"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "trojan",
      "tag": "(47)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 46",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "198.41.220.10",
      "server_port": 443,
      "password": "2cba4104747d49d18319e5ade1b93ab5",
      "tls": {
        "enabled": true,
        "server_name": "jobscareerforstudent.com",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/6b777a91",
        "headers": {
          "Host": "jobscareerforstudent.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(48)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 47",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "upload.ir",
      "server_port": 443,
      "uuid": "f584de15-2034-4170-a723-f48c2bae5e0f",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "afrhms16v.bestxray.buzz",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/linkws",
        "headers": {
          "Host": "afrhms16v.bestxray.buzz"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(49)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 48",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      },
      "server": "speed.cloudflare.com",
      "server_port": 443,
      "uuid": "2a8a10fb-9ca3-367e-a234-cf09f841be4f",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "us2e-20240116.v2freevpn.com",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/us2ekjds3nay",
        "headers": {
          "Host": "us2e-20240116.v2freevpn.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vmess",
      "tag": "(50)-@𝑺𝒊𝑵𝑨𝑩𝒊𝑮𝑶 § 49",
      "server": "speed.cloudflare.com",
      "server_port": 80,
      "uuid": "2a8a10fb-9ca3-367e-a234-cf09f841be4f",
      "security": "auto",
      "authenticated_length": true,
      "transport": {
        "type": "ws",
        "path": "/us2ekjds3nay",
        "headers": {
          "Host": "us2e-20240116.v2freevpn.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "dns",
      "tag": "dns-out"
    },
    {
      "type": "direct",
      "tag": "direct"
    },
    {
      "type": "direct",
      "tag": "direct-fragment",
      "tls_fragment": {
        "enabled": true,
        "size": "20-40",
        "sleep": "4-8"
      }
    },
    {
      "type": "direct",
      "tag": "bypass"
    },
    {
      "type": "block",
      "tag": "block"
    }
  ],
  "route": {
    "geoip": {
      "path": "geo-assets/sagernet-sing-geoip-geoip.db"
    },
    "geosite": {
      "path": "geo-assets/sagernet-sing-geosite-geosite.db"
    },
    "rules": [
      {
        "inbound": "dns-in",
        "outbound": "dns-out"
      },
      {
        "port": 53,
        "outbound": "dns-out"
      },
      {
        "clash_mode": "Direct",
        "outbound": "direct"
      },
      {
        "clash_mode": "Global",
        "outbound": "select"
      },
      {
        "domain_suffix": ".ir",
        "geosite": "ir",
        "geoip": "ir",
        "outbound": "bypass"
      }
    ],
    "final": "select",
    "auto_detect_interface": true,
    "override_android_vpn": true
  },
  "experimental": {
    "cache_file": {
      "enabled": true,
      "path": "clash.db"
    },
    "clash_api": {
      "external_controller": "127.0.0.1:6756",
      "secret": "5fkZY5ShVvuY5-7u"
    }
  }
}
