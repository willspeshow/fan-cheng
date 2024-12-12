# fan-cheng
{
  "spider": "https://lz.qaiu.top/lz/iiCeK2hicw6d;md5;7ee82ff7f6b078cf17f3475515bfa32f",
  "wallpaper": "https://api.mir6.com/api/ecybz",
  "logo": "https://d.kstore.dev/download/6474/tvbox/img/v0.png",
  "sites": [

    {
      "key": "热播影视",
      "name": "热播┃APP",
      "type": 3,
      "api": "csp_AppRB",
      "searchable": 1,
      "quickSearch": 1,
      "filterable": 1
    },

    {
      "key": "qqys",
      "name": "腾腾┃影视",
      "type": 3,
      "api": "https://yyrj.fun/drpy_libs/drpy2.min.js",
      "ext": "http://47.99.102.252/js/tx1.js"
    },
    {
      "key": "天天影视",
      "name": "天天┃影视",
      "type": 3,
      "api": "csp_AppTT",
      "searchable": 1,
      "quickSearch": 1,
      "filterable": 1
    },
   
    {
      "key": "十六万MV听歌📣",
      "name": "听歌┃歌曲",
      "type": 3,
      "api": "http://zb.hys.cool/app/lib/16万hys.js",
      "ext": "http://zb.hys.cool/app/lib/16万mv.js"
    },
    {
      "key": "t4直播转点播",
      "name": "教育┃教育",
      "type": 4,
      "api": "http://120.53.102.254/dsp16",
      "searchable": 1,
      "quickSearch": 1,
      "filterable": 0
    },
    
    {
      "key": "囧次元",
      "name": "🤨囧次元┃动漫",
      "type": 3,
      "api": "csp_XBPQ",
      "ext": {
        "分类url": "https://www.9ciyuan.cc/index.php/vod/show/area/{area}/by/time/class/{cateId}/id/20/page/{catePg}/year/{year}.html",
        "分类": "日韩动漫$日韩动漫#国产动漫$国产动漫#异世界$异世界#战斗$战斗#穿越$穿越#热血$热血#魔法$魔法#奇幻$奇幻"
      }
    },
    
    {
      "key": "88看球",
      "name": "88┃看球",
      "type": 3,
      "api": "csp_Kanqiu",
      "searchable": 1,
      "changeable": 0,
      "jar": "https://cik03-cos.7moor-fs1.com/im/4d2c3f00-7d4c-11e5-af15-41bf63ae4ea0/c8fd2c83-7f26-4d9a-983c-042d25692adf/2024-07-19/2024-07-19_20:22:16/1721391736606/43779109/danmu.jar;md5;924bd95dce1cd389c13fe5e19eedf8ba"
    },
    {
      "key": "MV大全",
      "name": "MV┃音乐",
      "type": 4,
      "api": "http://120.53.102.254/dsp/",
      "searchable": 1,
      "quickSearch": 1,
      "filterable": 1
    },
    {
      "key": "1905",
      "name": "能量┃1905",
      "type": 3,
      "api": "csp_Web1905",
      "searchable": 1,
      "quickSearch": 0,
      "filterable": 0
    },
    {
      "key": "push_agent",
      "name": "辅助┃推送",
      "type": 3,
      "api": "csp_Push",
      "searchable": 0,
      "quickSearch": 0,
      "filterable": 0
    },
    {
      "key": "config",
      "name": "辅助┃配置",
      "type": 3,
      "api": "csp_Config",
      "searchable": 0,
      "quickSearch": 0
    }
  ],
  "parses": [
    {
      "name": "聚合",
      "type": 3,
      "url": "Demo"
    },
    {
      "name": "线路1",
      "type": 0,
      "url": "https://jx.xmflv.com/?url=",
      "ext": {
        "header": {
          "user-agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/110.0.0.0 Safari/537.36 Edg/110.0.1587.57"
        }
      }
    },
    {
      "name": "盘古解析",
      "type": 0,
      "url": "https://www.pangujiexi.com/pangu/?url="
    },
    {
      "name": "解析1",
      "type": 1,
      "url": "http://pan.qiaoji8.com/tvbox/neibu.php?url=",
      "ext": {
        "flag": [
          "qq",
          "腾讯",
          "qiyi",
          "爱奇艺",
          "奇艺",
          "youku",
          "优酷",
          "sohu",
          "搜狐",
          "letv",
          "乐视",
          "mgtv",
          "芒果",
          "tnmb",
          "seven",
          "bilibili",
          "1905"
        ],
        "header": {
          "User-Agent": "okhttp/4.9.1"
        }
      }
    },
    {
      "name": "巧技二",
      "type": 1,
      "url": "https://zy.qiaoji8.com/gouzi.php?url=",
      "ext": {
        "flag": [
          "qq",
          "腾讯",
          "qiyi",
          "爱奇艺",
          "奇艺",
          "youku",
          "优酷",
          "sohu",
          "搜狐",
          "letv",
          "乐视",
          "mgtv",
          "芒果",
          "tnmb",
          "seven",
          "bilibili",
          "1905",
          "NetFilx"
        ],
        "header": {
          "User-Agent": "okhttp/4.9.1"
        }
      }
    }
  ],
  "flags": [
    "youku",
    "优酷",
    "优 酷",
    "优酷视频",
    "qq",
    "腾讯",
    "腾 讯",
    "腾讯视频",
    "iqiyi",
    "qiyi",
    "奇艺",
    "爱奇艺",
    "爱 奇 艺",
    "m1905",
    "xigua",
    "letv",
    "leshi",
    "乐视",
    "乐 视",
    "sohu",
    "搜狐",
    "搜 狐",
    "搜狐视频",
    "tudou",
    "pptv",
    "mgtv",
    "芒果",
    "imgo",
    "芒果TV",
    "芒 果 T V",
    "bilibili",
    "哔 哩",
    "哔 哩 哔 哩"
  ],
  "ijk": [
    {
      "group": "软解码",
      "options": [
        {
          "category": 4,
          "name": "opensles",
          "value": "0"
        },
        {
          "category": 4,
          "name": "overlay-format",
          "value": "842225234"
        },
        {
          "category": 4,
          "name": "framedrop",
          "value": "1"
        },
        {
          "category": 4,
          "name": "soundtouch",
          "value": "1"
        },
        {
          "category": 4,
          "name": "start-on-prepared",
          "value": "1"
        },
        {
          "category": 1,
          "name": "http-detect-range-support",
          "value": "0"
        },
        {
          "category": 1,
          "name": "fflags",
          "value": "fastseek"
        },
        {
          "category": 2,
          "name": "skip_loop_filter",
          "value": "48"
        },
        {
          "category": 4,
          "name": "reconnect",
          "value": "1"
        },
        {
          "category": 4,
          "name": "enable-accurate-seek",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec-auto-rotate",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec-handle-resolution-change",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec-hevc",
          "value": "0"
        },
        {
          "category": 1,
          "name": "dns_cache_timeout",
          "value": "600000000"
        }
      ]
    },
    {
      "group": "硬解码",
      "options": [
        {
          "category": 4,
          "name": "opensles",
          "value": "0"
        },
        {
          "category": 4,
          "name": "overlay-format",
          "value": "842225234"
        },
        {
          "category": 4,
          "name": "framedrop",
          "value": "1"
        },
        {
          "category": 4,
          "name": "soundtouch",
          "value": "1"
        },
        {
          "category": 4,
          "name": "start-on-prepared",
          "value": "1"
        },
        {
          "category": 1,
          "name": "http-detect-range-support",
          "value": "0"
        },
        {
          "category": 1,
          "name": "fflags",
          "value": "fastseek"
        },
        {
          "category": 2,
          "name": "skip_loop_filter",
          "value": "48"
        },
        {
          "category": 4,
          "name": "reconnect",
          "value": "1"
        },
        {
          "category": 4,
          "name": "enable-accurate-seek",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec",
          "value": "1"
        },
        {
          "category": 4,
          "name": "mediacodec-auto-rotate",
          "value": "1"
        },
        {
          "category": 4,
          "name": "mediacodec-handle-resolution-change",
          "value": "1"
        },
        {
          "category": 4,
          "name": "mediacodec-hevc",
          "value": "1"
        },
        {
          "category": 1,
          "name": "dns_cache_timeout",
          "value": "600000000"
        }
      ]
    }
  ],
  "rules": [
    {
      "name": "暴风",
      "hosts": [
        "bfzy",
        "bfbfvip",
        "bfengbf"
      ],
      "regex": [
        "#EXTINF.*?\\s+.*?adjump.*?\\.ts"
      ]
    },
    {
      "name": "量子",
      "hosts": [
        "vip.lz",
        "hd.lz",
        ".cdnlz"
      ],
      "regex": [
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:7\\.166667,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:4\\.066667,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "17.19"
      ]
    },
    {
      "name": "非凡",
      "hosts": [
        "vip.ffzy",
        "hd.ffzy",
        "super.ffzy"
      ],
      "regex": [
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:6\\.400000,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:6\\.666667,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "#EXTINF.*?\\s+.*?1171(057).*?\\.ts",
        "#EXTINF.*?\\s+.*?6d7b(077).*?\\.ts",
        "#EXTINF.*?\\s+.*?6718a(403).*?\\.ts",
        "17.99",
        "14.45"
      ]
    },
    {
      "name": "索尼",
      "hosts": [
        "suonizy"
      ],
      "regex": [
        "#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:1\\.000000,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "#EXTINF.*?\\s+.*?p1ayer.*?\\.ts",
        "#EXTINF.*?\\s+.*?\\/video\\/original.*?\\.ts"
      ]
    },
    {
      "name": "快看",
      "hosts": [
        "kuaikan"
      ],
      "regex": [
        "#EXT-X-KEY:METHOD=NONE\\r*\\n*#EXTINF:5,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "#EXT-X-KEY:METHOD=NONE\\r*\\n*#EXTINF:2\\.4,[\\s\\S]*?#EXT-X-DISCONTINUITY",
        "#EXT-X-KEY:METHOD=NONE\\r*\\n*#EXTINF:1\\.467,[\\s\\S]*?#EXT-X-DISCONTINUITY"
      ]
    },
    {
      "name": "一起看广告",
      "hosts": [
        "yqk88"
      ],
      "regex": [
        "18.4",
        "15.1666",
        "16.5333",
        "#EXT-X-DISCONTINUITY\\r*\\n*[\\s\\S]*?#EXT-X-CUE-IN"
      ]
    },
    {
      "name": "磁力广告",
      "hosts": [
        "magnet"
      ],
      "regex": [
        "更多",
        "请访问",
        "example",
        "社 區",
        "x u u",
        "直 播",
        "更 新",
        "社 区",
        "有趣",
        "有 趣",
        "英皇体育",
        "全中文AV在线",
        "澳门皇冠赌场",
        "哥哥快来",
        "美女荷官",
        "裸聊",
        "新片首发",
        "UUE29"
      ]
    },
    {
      "name": "火山嗅探",
      "hosts": [
        "huoshan.com"
      ],
      "regex": [
        "item_id="
      ]
    },
    {
      "name": "抖音嗅探",
      "hosts": [
        "douyin.com"
      ],
      "regex": [
        "is_play_url="
      ]
    },
    {
      "name": "农民嗅探",
      "hosts": [
        "toutiaovod.com"
      ],
      "regex": [
        "video/tos/cn"
      ]
    }
  ],
  "doh": [
    {
      "name": "Google",
      "url": "https://dns.google/dns-query",
      "ips": [
        "8.8.4.4",
        "8.8.8.8"
      ]
    },
    {
      "name": "Cloudflare",
      "url": "https://cloudflare-dns.com/dns-query",
      "ips": [
        "1.1.1.1",
        "1.0.0.1",
        "2606:4700:4700::1111",
        "2606:4700:4700::1001"
      ]
    },
    {
      "name": "AdGuard",
      "url": "https://dns.adguard.com/dns-query",
      "ips": [
        "94.140.14.140",
        "94.140.14.141"
      ]
    },
    {
      "name": "DNSWatch",
      "url": "https://resolver2.dns.watch/dns-query",
      "ips": [
        "84.200.69.80",
        "84.200.70.40"
      ]
    },
    {
      "name": "Quad9",
      "url": "https://dns.quad9.net/dns-quer",
      "ips": [
        "9.9.9.9",
        "149.112.112.112"
      ]
    }
  ],
  "lives": [
    {
      "name": "live",
      "type": 0,
      "url": "https://yyrj.fun/tv",
      "epg": "http://epg.112114.xyz/?ch={name}&date={date}",
      "logo": "https://epg.112114.xyz/logo/{name}.png"
    }
  ],
  "ads": [
    "static-mozai.4gtv.tv"
  ]
}
