###API
####获取热门话题文章列表
https://api.readhub.cn/topic?lastCursor=&pageSize=20

response(下同):
    {
        "data": [{
            "id": "7HmYyYMmqcE",
            "nelData": {
                "state": true,
                "result": [{
                    "weight": 0.173791438341141,
                    "nerName": "Cortana",
                    "entityId": "baike_13209604",
                    "entityName": "Cortana",
                    "entityType": "product",
                    "entityUniqueId": "baike_13209604",
                    "finance": null
                }]
            },
            "newsArray": [{
                "id": 1073154,
                "url": "http://tech.163.com/18/1028/15/DV7C3GJS00098IEO.html",
                "title": "沈向洋的微软小娜“易主” 被移至Office产品部门",
                "siteName": "网易科技",
                "mobileUrl": "http://tech.163.com/18/1028/15/DV7C3GJS00098IEO.html",
                "autherName": "",
                "duplicateId": 1,
                "publishDate": "2018-10-28T07:02:54.000Z"
            }],
            "createdAt": "2018-10-28T07:55:40.538Z",
            "eventData": [],
            "publishDate": "2018-10-28T07:55:40.522Z",
            "summary": "对此，福布斯报道称，该事件或许对领导Cortana项目的微软全球执行副总裁、微软 AI及微软研究事业部负责人沈向洋影响巨大 ... 他目前任职微软全球执行副总裁微软人工智能及微软研究事业部负责人，还是美国国家工程院院士、全球顶级机器视觉专家，是微软公司执行副总裁、微软十二常委之一，是目前微软公司华人最高职位者 ... 2007年，升任微软全球资深副总裁，在微软应用与服务部门负责微软必应搜索引擎的全球产品研发工作。",
            "title": "沈向洋的微软小娜“易主” 被移至Office产品部门",
            "updatedAt": "2018-10-28T08:13:06.227Z",
            "timeline": "7Hn2kXTeQPm",
            "order": 78695,
            "extra": {
                "instantView": true
            }
        }],
        "pageSize": 1,
        "totalItems": 24961,
        "totalPages": 24961
    }

####获取科技动态文章列表
https://api.readhub.cn/news?lastCursor=&pageSize=10
####获取开发者资讯文章列表
https://api.readhub.cn/technews?lastCursor=&pageSize=10
####获取区块链快讯文章列表
https://api.readhub.cn/technews?lastCursor=&pageSize=10
####获取招聘行情列表
https://api.readhub.cn/jobs?lastCursor=&pageSize=10

####获取文章详情
https://readhub.cn/topic/@文章id

    response：
    {
        "routing": {
            "locationBeforeTransitions": {
                "pathname": "/topic/7HmymgOM9hE",
                "search": "",
                "hash": "",
                "state": null,
                "action": "PUSH",
                "key": "308n4p",
                "query": {},
                "$searchBase": {
                    "search": "",
                    "searchBase": ""
                }
            }
        },
        "app": {
            "sizeMode": "lg",
            "globalMessages": [],
            "ads": [],
            "isWechatReady": false,
            "SSR_ENV": {
                "platform": "pc"
            },
            "indexs": [3, 9, 2, 6, 7, 5, 1, 0, 8, 11, 12, 4, 13, 10],
            "tdk": {
                "title": "推特因未能及时解决邮件炸弹威胁向前白宫秘书致歉 - Readhub",
                "description": "发送该威胁推文的是一名叫 Cesar Sayoc 的人，他曾被控向前美国总统奥巴马、前国务卿希拉里 · 克林顿等政治名人寄过管状炸弹 ... 当地时间周五，Twitter 表示，他们本应删除掉这些威胁信息，现在他们已经就这一事件展开了调查 ... Sayoc 则因涉嫌向知名民主党人发送邮件炸弹以及批评特朗普总统而被捕。",
                "keywords": "科技,媒体,通信,科技资讯,聚合阅读,精选,无码科技,"
            }
        },
        "topic": {
            "data": [],
            "openList": [],
            "pageSize": 20,
            "totalItems": 0,
            "init": false,
            "isLoadAll": false,
            "autoLoading": true,
            "newTopicCount": 0,
            "error": null,
            "selectedIndex": -1,
            "hideNotify": false,
            "scrollTop": null
        },
        "timeline": {
            "activeType": "all",
            "items": {
                "all": {
                    "data": [],
                    "pageSize": 10,
                    "totalItems": 0,
                    "init": false,
                    "isLoadAll": false,
                    "autoLoading": true,
                    "error": null,
                    "scrollTop": null
                },
                "tech": {
                    "data": [],
                    "pageSize": 10,
                    "totalItems": 0,
                    "init": false,
                    "isLoadAll": false,
                    "autoLoading": true,
                    "error": null,
                    "scrollTop": null
                },
                "blockchain": {
                    "data": [],
                    "pageSize": 10,
                    "totalItems": 0,
                    "init": false,
                    "isLoadAll": false,
                    "autoLoading": true,
                    "error": null,
                    "scrollTop": null
                }
            },
            "highQualityNews": [],
            "init": false,
            "newsScrollTop": null,
            "techScrollTop": null
        },
        "topic_detail": {
            "data": {
                "id": "7HmymgOM9hE",
                "entityTopics": [{
                    "weight": 0.761942858497301,
                    "nerName": "Twitter Safety",
                    "entityId": "baike_2443267",
                    "entityName": "Twitter",
                    "entityType": "product",
                    "entityUniqueId": "baike_2443267",
                    "finance": {
                        "code": "NYSE:TWTR",
                        "name": "Twitter",
                        "price": "225.98 亿美元"
                    }
                }, {
                    "weight": 0.469744016726812,
                    "nerName": "奥巴马",
                    "entityId": "baike_190467",
                    "entityName": "奥巴马",
                    "entityType": "person",
                    "entityUniqueId": "baike_190467",
                    "finance": null
                }, {
                    "weight": 0.295701305071513,
                    "nerName": "希拉里",
                    "entityId": "baike_4119832",
                    "entityName": "希拉里",
                    "entityType": "person",
                    "entityUniqueId": "baike_4119832",
                    "finance": null
                }],
                "newsArray": [{
                    "id": "7HmTqwx9tDv",
                    "url": "http://tech.sina.com.cn/i/2018-10-28/doc-ihnaivxp6178893.shtml",
                    "title": "推特因未能及时解决邮件炸弹威胁向前白宫秘书致歉",
                    "siteName": "新浪科技",
                    "mobileUrl": "http://tech.sina.com.cn/i/2018-10-28/doc-ihnaivxp6178893.shtml",
                    "autherName": "",
                    "duplicateId": 1,
                    "publishDate": "2018-10-28T00:54:00.000Z"
                }],
                "createdAt": "2018-10-28T05:59:01.266Z",
                "entityEventTopics": [],
                "publishDate": "2018-10-28T05:59:01.212Z",
                "summary": "发送该威胁推文的是一名叫Cesar Sayoc的人，他曾被控向前美国总统奥巴马、前国务卿希拉里·克林顿等政治名人寄过管状炸弹 ... 当地时间周五，Twitter表示，他们本应删除掉这些威胁信息，现在他们已经就这一事件展开了调查 ... Sayoc则因涉嫌向知名民主党人发送邮件炸弹以及批评特朗普总统而被捕。",
                "title": "推特因未能及时解决邮件炸弹威胁向前白宫秘书致歉",
                "updatedAt": "2018-10-28T05:59:52.178Z",
                "timeline": {
                    "topics": [{
                        "id": "7HmymgOM9hE",
                        "title": "推特因未能及时解决邮件炸弹威胁向前白宫秘书致歉",
                        "createdAt": "2018-10-28T05:59:01.266Z"
                    }, {
                        "id": "7H5e3HO3DjU",
                        "title": "Twitter将允许用户重新查看被删除推文",
                        "createdAt": "2018-10-17T16:58:35.331Z"
                    }, {
                        "id": "7GjT8Dnd3pL",
                        "title": "Twitter将推出消息流排序切换模式",
                        "createdAt": "2018-09-20T08:55:23.094Z"
                    }, {
                        "id": "NK5FmC7nJT",
                        "title": "Twitter’s next big move is a revamped hub for everything you want to see",
                        "createdAt": "2018-06-13T16:32:29.224Z"
                    }, {
                        "id": "3vBh6pQewuP",
                        "title": "Twitter 调整算法 过滤公共内容",
                        "createdAt": "2018-05-15T18:54:26.691Z"
                    }],
                    "commonEntities": [],
                    "id": "7H6GhyV9niG"
                },
                "order": 78676,
                "hasInstantView": false
            },
            "init": true,
            "error": null,
            "fetched": true,
            "scrollTop": null,
            "fetching": false
        },
        "labCenter": {
            "feature": {},
            "titleScore": {
                "score": "",
                "flagLocation": "50%",
                "fillColor": "#666"
            },
            "textDiagnose": {},
            "hasSendFeedback": false,
            "titleScoreError": false,
            "textDiagnoseError": false,
            "feedbackError": false
        },
        "recruitment": {
            "items": [],
            "charts": [],
            "pageSize": 10,
            "totalItems": 0,
            "init": false,
            "isLoadAll": false,
            "autoLoading": true,
            "error": null,
            "scrollTop": null
        },
        "popup": {
            "isVisible": false,
            "content": null
        },
        "gift": {
            "qrCode": "",
            "thanks": false,
            "people": 0,
            "avatars": []
        },
        "daily": {
            "list": []
        },
        "subCenter": {
            "list": [],
            "result": null
        },
        "@@dva": 0,
        "loading": {
            "global": false,
            "models": {
                "app": false,
                "topic_detail": false
            },
            "effects": {
                "app/changeSizeMode": false,
                "app/switchToWPM": false,
                "app/fetchAds": false,
                "topic_detail/initTopic": false,
                "topic_detail/fetchTopic": false,
                "topic_detail/setTDK": false,
                "app/initWechat": false,
                "topic_detail/fetchStockPrice": false
            }
        }
    }