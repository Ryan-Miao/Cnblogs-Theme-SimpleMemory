博客园主题皮肤
============

## 配置

https://www.dbnuo.com/Cnblogs-Theme-SimpleMemory/docs/v1.1/#/Docs/Customization/config?id=%e7%a4%ba%e4%be%8b


页首代码:
```
<script type="text/javascript">
    window.cnblogsConfig = {
        GhVersions    : "d2d86a863c9e9c8fad1fda398f05d5dd5c2fdf9f", // 版本
        blogUser      : "Ryan Miao", // 用户名
        blogAvatar    : "https://pic.cnblogs.com/avatar/686418/20171018133750.png", // 用户头像
        blogStartDate : "2014-10-28", // 入园时间，年-月-日。入园时间查看方法：鼠标停留园龄时间上，会显示入园时间
        GhUserName    : "Ryan-Miao",
        GhRepositories: "Cnblogs-Theme-SimpleMemory",
        homeTopImg    : [
            "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114214124737-1332207510.jpg",
            "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114214851476-1666201764.png",
            "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114214930503-1799431660.png"
        ],
        essayTopImg: [
            "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114214124737-1332207510.jpg",
                "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114214851476-1666201764.png",
                "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114214930503-1799431660.png"
        ],
        fontIconExtend: "//at.alicdn.com/t/font_2204177_honuy9aiklh.css",
        menuNavList: [ // 列表数据 ["导航名称", "链接", "icon"]
            ["github", "https://github.com/Ryan-Miao", "icon-GitHub"],
            ["微信", "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114231420286-1381172159.jpg", "icon-weixin"],
            ["我的博客", "https://blog.rmiao.top/", "icon-blogger"],
            ["公众号", "https://images2018.cnblogs.com/blog/686418/201808/686418-20180822091328437-1109977663.jpg", "icon-gongzhonghao"],
        ],
        menuCustomList: {
            "链接": { // 标题
                "data": [ // 列表数据 ["列表", "链接"]
                    ["微信公众号markdown编辑器", "https://md.rmiao.top/"],
                    ["sql格式化", "https://ryan-miao.github.io/sql-format-with-highlight/index.html"],
                    ["geohash可视化", "	https://ryan-miao.gitee.io/geohash_tool/"]
                ],
                "icon": "icon-brush_fill" // 配置图标，参考文档：定制化/字体图标库
            }
        },
        essayTopAnimationRendered: false, //关闭首页banner动态
        bgAnimationRendered: false,  //页面动态
        //homeBannerTextType: "one", //一句话
        reward: {
            enable: true,
            wechatpay: "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114232706683-1057475691.jpg",
            alipay: "https://img2020.cnblogs.com/blog/686418/202011/686418-20201114232656966-233715838.jpg"
        },
        weChatOfficialAccounts: "https://images2018.cnblogs.com/blog/686418/201808/686418-20180822091328437-1109977663.jpg",
        advertising: true,
        
    }
</script>
<script src="https://cdn.jsdelivr.net/gh/BNDong/Cnblogs-Theme-SimpleMemory@v1.3.3/src/script/simpleMemory.min.js" defer></script>
```