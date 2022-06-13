# 歡迎來到 Aqualand!  

這是一個可能對您有所幫助的命令指南。  

> `[]` 標識一個可選參數  
> `<>` 標識一個必填參數  

## 傳送  

| 命令 | 說明 | 費用 |
| - | - | - |
| `/rtp`<br>`/randomtp` | 隨機傳送 | $20 |
| `/warp [name]` | 選擇傳送點或傳送到指定位置 | $15 |
| `/sethome <name>` | 將家設置為您當前的位置 | $300 |
| `/delhome <name>` | 移除一個家 |  |
| `/home <name>` | 傳送到你家 | $20 |
| `/suicide` | 自殺 | $10 |
| `/back` | 傳送到你上次死去的地方 | $30 |
| `/tpa <player>` | 請求將自己傳送到對方的位置 | $20 |
| `/tpahere <player>` | 請求將對方傳送到自己的位置 | $20 |
| `/tpacancel [player]` | 取消所有未完成的傳送請求。指定[player]以取消與他們的請求 |  |
| `/tpaaccept [player\|*]` | 接受傳送請求 |  |
| `/tpadeny [player\|*]` | 拒絕傳送請求 |  |

注意：如果玩家正在玩基岩版，請同時輸入點（在玩家 ID 前面）

例子:  
`/tpa .Notch`  
`/tpa Notch`  

## 查詢  

| 命令 | 說明 |
| - | - |
| `/list` | 列出所有在線玩家 |
| `/ping` | Pong! |
| `/rg info` | 顯示有​​關您當前位置的區域信息 |
| `/rg list` | 列出您自己的區域 |
| `/rules` | 查看伺服器規則 |
| `/tps` | 獲取伺服器當前的每秒刻數 |
| `/warnings` | 顯示自己近期的警告 |
| `/dupeip <player>`<br>`/alts <player>` | 顯示共享同一IP位址的玩家 |

### 調查員模式  

啟用: `/co i`  
禁用: `/co i`  

如果你發現你的建築被破壞，你可以使用它。  
歡迎隨時向管理員報告  

## 经济  

| 命令 | 說明 |
| - | - |
| `/bal`<br>`/balance`<br>`/money` | 檢查您的餘額 |
| `/baltop`<br>`/balancetop` | 查看富豪榜(不包括銀行存款) |
| `/pay <player> <amount>` | 付款給其他玩家 |
| `/worth <<itemname>\|<id>\|hand\|inventory\|blocks> [-][amount]` | 查看手上或指定物品的建議價格 |

### 銷售  

`/sell hand`: 將選中的物品賣給伺服器  

`/sell all`: 將背包中的所有物品出售給伺服器  

注意：該指令可能無法正常使用  

### 管理您的店鋪  

| 命令 | 說明 |
| - | - |
| `/shop help` | 顯示商店的幫助 |
| `/shop buy` | 變更商店為購買模式 |
| `/shop sell` | 變更商店為出售模式 |
| `/shop remove` | 移除商店 |

如何創建商店  
您可以在 COSTCO 或您的建築裏創建商店  
要創建商店，您需要一個箱子和選定的商品  
拿着選定的商品長按箱子  
然後輸入金額  

## 聊天

| 命令 | 說明 |
| - | - |
| `/msg`<br>`/m`<br>`/pm`<br>`/t`<br>`/tell`<br>`/w`<br>`/whisper` | 向指定玩家發送私信 |
| `/r`<br>`/reply` | 快速回复上一位給你發消息的玩家 |
| `/teammsg <message>` | 向運行命令的實體的團隊中的所有玩家發送消息 |
| `/mail [read\|clear\|clear [number]\|send [to] [message]]` | 管理郵件 |

## 雜項  

| 命令 | 說明 | 費用 |
| - | - | - |
| `/afk` | 將您標記為離開 |  |
| `/hat`<br>`/head` | 獲得一些很酷的新頭飾 |  |
| `/sit` | 坐 |  |
| `/skin [help\|set <skin>\|clear\|update\|url <SkinUrl> [steve/slim]]` | 管理你的皮膚 |  |
| `/itemname [name]` | 重命名您當前持有的物品。將名稱留空以重置。您可以添加顏色代碼 | $5 |
| `/bl <lineNumber> <value>`<br>`/blocklocker <lineNumber> <value>` | 編輯您的木牌鎖 |  |
| `/kit`<br>`/kits` | 打開領取禮包GUI |  |

### 音樂  

`/jukebox`: 選擇要播放的音樂  

`/music`: 與 /jukebox 相同  

`/musicbox`: 音樂，但有更多選擇  

我推薦 /musicbox  
anime  

## MCMMO  

https://mcmmo.fandom.com/wiki/

### MCMMO技能  

#### -=採集系技能=-  
| 命令 | 說明 |
| - | - |
| `/excavation` | 顯示您的土壤學統計數據 |
| `/fishing` | 顯示您的釣魚學統計數據 |
| `/herbalism` | 顯示您的草藥學統計數據 |
| `/mining` | 顯示您的礦物學統計數據 |
| `/woodcutting` | 顯示您的伐木學統計數據 |
#### -=格鬥系技能=-  
| 命令 | 說明 |
| - | - |
| `/archery` | 顯示您的箭術統計數據 |
| `/axes` | 顯示您的斧技統計數據 |
| `/swords` | 顯示您的劍術統計數據 |
| `/taming` | 顯示您的馴獸統計數據 |
| `/unarmed` | 顯示您的格鬥統計數據 |
#### -=雜項技能=-  
| 命令 | 說明 |
| - | - |
| `/acrobatics` | 顯示您的體術統計數據 |
| `/alchemy` | 顯示您的煉金統計數據 |
| `/repair` | 顯示您的修理統計數據 |
| `/salvage` | 顯示您的回收統計數據 |
| `/smelting` | 顯示您的冶煉統計數據 |

### mcMMO命令  
| 命令 | 說明 |
| - | - |
| `/mcability` | 打開/關閉右擊時正在準備的mcMMO能力 |
| `/mccooldown` | 查看所有的mcMMO能力的冷卻時間 |
| `/mcinspect <player>`<br>`/mmoinspect` | 查看另一個玩家的詳細mcMMO訊息 |
| `/mcmmo help` | 顯示mcMMO的幫助 |
| `/mcnotify` | 打開/關閉mcMMO能力的聊天顯示通知 |
| `/mcrank` | 顯示等級 |
| `/mcstats` | 查看你的mcMMO統計訊息 |
| `/mctop` | 排行榜 |
| `/mmoinfo` | 讀取有關技能或機械的詳細訊息 |
| `/mmoxpbar <reset \| disable>`<br>`/mmoxpbar <show \| hide \| disable> <skillname>` | 玩家對mcMMO XP欄的設置 |

### mcMMO派對  
| 命令 | 說明 |
| - | - |
| `/p`<br>`/partychat`<br>`/pc`<br>`/pchat` | 切換聚會聊天 |
| `/party HELP` | 顯示Party的幫助 |
| `/ptp` | 傳送到一個mcMMO派對成員身邊 |

### 公會  
| 命令 | 說明 |
| - | - |
| `/guild` | 顯示Guild的幫助 |

## 關聯帳號  
| 命令 | 說明 |
| - | - |
| `/discord` | 顯示 Discord 伺服器的邀請鏈接 |
| `/discord link` | 將 Minecraft 帳戶與 Discord 帳戶關聯 |
| `/dynmap webregister` | 獲取 dynmap 的註冊碼 |
| `/linkaccount <player> [code]` | 鏈接您的基岩和java帳戶(本地鏈接) |
| `/unlinkaccount` | 取消鏈接您的基岩和 java 帳戶(本地鏈接) |
