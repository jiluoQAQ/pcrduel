# 注意
### 请注意，Git不包含魔改数据库文件，DLC数据文件，需要到群内自行下载。
### 有部分人问如何分离unit目录，如果您是使用我的魔改版，您可以自行到chara_duel中修改，搜索unit，相信您能明白
### 如果您有任何问题，欢迎提issues！如果您对本游戏有好的想法，也可以提，可能的话我会并入主分支亦或是为您开放一个单独的分支
### 我只是在原版基础上进行了一些粗陋的改动，框架是由大佬编写的，在此感谢！
## 原版注意事项
### 目前为了方便，通过决斗获得女友是可以超过爵位上限的，这个可以自己修改。
### 游戏可能存在bug，python新手多包涵。
### 领金币和查金币指令，与赛跑是一样的，二者的金币也是互通的，如果两个都安可以注释掉一个。
### 贵族签到的每日次数由于hoshino默认，不是跨群独立的，想修改可以自己修改。
### 女友列表就是你自己的_pcr_data列表，减去黑名单列表，可以自己调整不想出现的女友。
### ~~氪金功能没有写在说明书中，最好不要开启，开启氪金十分无聊。~~ 我写了嘤嘤嘤  
### 新增的dlc需相应的pcrdata和unit头像包，我会放在github的release里，我用的pcrdata为旧版，请根据自己的调整。
### ~~如果想自己创建dlc，请在源码中dlc部分，按格式添加，json文件里也需要加个空列表。(这里后续应该会优化)~~ 这个问题已经被解决了
### 新增了在招募时发送角色立绘功能，这个需要角色有立绘包。如果有的话，请在同目录下的fullcard文件夹里，按文件夹中范例，{角色id}31.png的格式添加立绘，如果没有角色立绘，则发送角色头像。

## 贵族决斗指令表
### 注意：仅适用于魔改版，如有改动，请以实际为准
| 关键词     | 作用     |
| :-------------: | :-------------:|
|创建贵族       | 可以在本群创建自己的贵族，会被随机分配一个PCR女友。       |  
|查询贵族 |可以查询自己的贵族状态。
|贵族约会/招募女友 |可以花费500金币招募一个女友，女友数不能超过爵位上限。
|升级贵族/升级爵位 |可以花费金币提升自己的爵位,提升爵位时女友数需已达到上限。
|贵族决斗+@成员 |可以向另一个贵族发起决斗，两个人必须都是贵族且已拥有女友，输者会随机被抢走一个女友。
|领金币 |可以在金币归零时领取150金币。
|查金币 |可以查询自己现在的金币数。
|贵族签到 |可以领取金币和声望，数量与爵位和运气有关。
|为(用户qq)充值xx金币 |可以为该用户充值金币
|重置决斗 |可以解锁决斗开关。(限管理员以上，这个仅用于决斗卡死无法再开的时候)
|查女友+角色名 |可以查询某位角色的归属。
|分手+角色名 |可以和角色分手(需要支付分手费和声望)。
|贵族帮助 |可以查看游戏说明书。
|dlc帮助 |可以查看dlc系统功能
|本群贵族 |可以查看本群贵族统计，剩余女友，及加载dlc的状况
|加冕称帝 |可以由国王提升至皇帝
|飞升成神 |可以由皇帝提升至神
|贵族等级表 |可以查看贵族提升消耗及权利
|为@某人转账xxx金币 |用以向某人转账金币，需要扣除手续费
|用xxx金币与@qq交易女友+角色名|进行女友交易，需要扣除买入方的声望，需要扣除手续费
|声望/金币/女友排行|查看排行榜
|查询庆典|查看目前正在进行的庆典状况
|梭哈支持XX号|是男人就梭哈！投入所有的金币支持某位选手
|扣除QQ号的XXX声望|特殊情况用，扣除某人声望
|声望招募|使用声望必定招募女友
|免费招募|免费招募必定招募一名女友
|皇室婚礼+角色名|和一名角色结婚
|确认离婚|和自己的妻子离婚
|确认重开|删除自己的角色，从头再来
|重置角色qq|删除一名玩家的数据库，令其重新开始
|重置金币qq|清空一名玩家的金币
|设定群XXX为X号死|操盘（这个功能十分无聊，但可以防止人脱坑）
|初始化本群庆典|按照配置内的设置，快速初始化本群庆典
|开启/关闭本群XX庆典|群内开关庆典
|好感帮助|可以查看好感系统帮助
|购买上限|可以增加女友上限(国王以上可用)
|时装帮助|可以查看好感系统帮助
|会战帮助|可以查看会战/世界boss系统帮助
|副本帮助|查询副本系统指令
|战斗帮助|查询战斗系统指令

1.添加转账功能    
2.添加声望兑换功能    
3.添加女友交易功能   
4.添加扩充女友上限功能
5.半成品女友商城系统(上架功能，有需求自行完善魔改)
6.添加时装系统
7.添加女友角色，战力系统

8.添加副本系统，副本可以产出装备，礼物，提升好感

9.添加会战，世界Boss系统，具体配置文件见下方

10.添加编组，保存队伍功能，副本，会战，世界boss都添加了组队判断

11.添加挂机修炼功能

12.添加经验池模块

13.添加装备分解

14.添加抽武器

15.添加抽卡UR保底兑换，参考游戏：乖离性MA、原神

16.添加每月会战奖励结算功能，顺便添加名次查询

17.增加角色升星功能，提升角色rank上限

18.增加角色转生功能

19.增加新装备：戒指，转生后才能装备，目前添加了2个，一个按照好感度增加战力，一个按照转生等级增加战力



#时装系统配置
config.json文件：时装数据，目前已加一个示例，可以根据示例自行添加
字段说明：
fid 时装id用于绑定角色时装立绘
name 时装名称
cid 用于绑定角色
pay_score 购买所需金币
pay_sw 购买所需声望
favor 购买后增加好感度
xd_flag 是否限定(0非限定1限定)
add_ce 穿戴时装加的战力
content 时装获取条件
fashion文件夹：时装图片存放处，放JPG格式图片，图片名为时装的FID，每张图片的大小尽量保存在200k以下，防止因为图片太大，同一角色时装太多导致消息无法发出

#副本json字段说明 dungeon.json文件
"1":{  
	"did":副本id,
	"name":副本名称,
	"model":副本难度说明,
	"recommend_ce":副本推荐战力,
	"add_exp":胜利后角色添加经验,
	"add_favor":胜利后角色增加的好感,
	"dun_score":胜利后得到的副本币,
	"drop":{ 副本掉落
		"favor":{ 礼物掉落合计占比最高100%
			"1":80, 掉落一个礼物占比
			"2":20 掉落一个礼物占比
		},
		"equipment":{ 装备掉落
			"num":{ 装备掉落数量合计占比最高100%，同理增加2，3，4件
				"0":80, 不掉装备几率
				"1":20 掉落一件装备几率
			},
			"quality":{ 装备掉落品质
				"1":100 品质1的装备掉落几率合计占比最高100%，对应装备表level字段
			}
		}
	},
	"content":副本描述
}

#装备json字段说明 equipment.json文件
"1":{
	"level":1, 装备品质
	"model":"绿色", 装备品质描述
	"eid":[1,2,3,4], 改品质装备的eid数组
	"e_list":{ 装备列表
		"1":{  
			"eid":1, 装备id
			"level":1, 装备品质
			"type_id":2, 装备位置id
			"type":"护手", 装备位置目前只设置了4个位置的装备
			"name":"木盾", 装备名称
			"add_ce":10, 装备添加的战力
			"dun_score":50 装备兑换所需的副本币
		},
		"2":{  
			"eid":2,
			"level":1,
			"type":"武器",
			"name":"铁剑",
			"add_ce":10,
			"dun_score":50
		},
		"3":{  
			"eid":3,
			"level":1,
			"type":"衣服",
			"name":"皮衣",
			"add_ce":10,
			"dun_score":50
		},
		"4":{  
			"eid":4,
			"level":1,
			"type":"鞋子",
			"name":"草鞋",
			"add_ce":10,
			"dun_score":50
		}
	}
},

#BOSSjson字段说明 bossinfo.json文件
"1":{  
		"zhoumu":[1,2], BOSS周末数
		"bosslist":{
			"1":{
				"bossid":1, BOSSid,目前一周目只设置5个boss，需要添加或者删除boss请修改源代码的boss上限
				"name":"红美铃", BOSS名称，对应BOSS图片
				"hp":100000, BOSS血量，世界BOSS为血量X10
				"ce":10000, BOSS战力，用来计算伤害，可以根据自己群的平均战力调整
				"fenshu":1, BOSS输出最终分数 还未实装
				"add_exp":100, 战斗增加的经验
				"dropequip":1, BOSS死后每个人根据出刀数量得到的装备等级
				"dropnum":1 BOSS死后掉落的每个人根据出刀数量得到的装备数量
			},
			"2":{
				"bossid":2,
				"name":"十六夜咲夜",
				"hp":120000,
				"ce":11000,
				"fenshu":1.1,
				"add_exp":100,
				"dropequip":1,
				"dropnum":1
			},
			"3":{
				"bossid":3,
				"name":"帕秋莉",
				"hp":150000,
				"ce":12000,
				"fenshu":1.1,
				"add_exp":100,
				"dropequip":1,
				"dropnum":1
			},
			"4":{
				"bossid":4,
				"name":"蕾米莉亚",
				"hp":170000,
				"ce":13000,
				"fenshu":1.2,
				"add_exp":100,
				"dropequip":1,
				"dropnum":1
			},
			"5":{
				"bossid":5,
				"name":"芙兰朵露",
				"hp":200000,
				"ce":15000,
				"fenshu":1.2,
				"add_exp":100,
				"dropequip":1,
				"dropnum":1
			}
		}
	},
	
#gechajson字段说明 equipgecha.json文件
"1":{
	"name":"博丽神社的宝藏", 装备池名称，抽卡是按照名称来指定具体抽的池子的
	"up_num":100, 第n抽之前没有抽到SSR/SSR以上装备时，必定抽到SSR/SSR以上装备的次数
	"up_equip":[110,111,112,117], 当前UP的武器
	"gecha":{ 普通概率卡池
		"quality":{
			"2":80, 等级与对应概率
			"3":15,
			"4":4,
			"5":1
		},
		"equip":{
			"2":[5,6,7,8,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,54,55,56,57], 等级与对应可以抽到的装备列表
			"3":[58,59,60,61,62,63,64,65,66,67,80,81,82,83,84,135],
			"4":[102,103,104,105,106,107],
			"5":[110,111,112,117]
		}
	},
	"xgecha":{ 小保底抽取卡池，只第10次必定抽到SR或以上装备
		"quality":{
			"3":85,
			"4":10,
			"5":5
		},
		"equip":{
			"3":[58,59,60,61,62,63,64,65,66,67,80,81,82,83,84,135],
			"4":[102,103,104,105,106,107],
			"5":[110,111,112,117]
		}
	},
	"dgecha":{ 大保底抽取卡池，只第n次必定抽到SSR或以上装备
		"quality":{
			"4":80,
			"5":20
		},
		"equip":{
			"4":[102,103,104,105,106,107],
			"5":[110,111,112,117]
		}
	}
}
