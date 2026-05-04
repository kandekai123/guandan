AI掲蛋策略对决系统
AI Guandan Strategy Duel System
游戏简介与操作指南  |  Game Introduction & Operation Guide
一、游戏简介  |  Game Introduction
1.1 什么是掲蛋  |  What is Guandan
掲蛋是流行于江苏、安徽等地的一种四人升级扑克游戏，由两对家合作对抗。游戏使用两副扑克牌（108张），通过出牌、贡牌、还贡等机制进行升级竞争，先打到A级的一方获胜。
Guandan is a four-player partnership trick-taking card game popular in Jiangsu and Anhui provinces, China. Using two decks (108 cards), two teams compete to upgrade their rank through playing cards, tribute, and return mechanisms. The first team to reach Level A wins.
1.2 AI策略对决  |  AI Strategy Duel
本系统是一个支持人机对战的智能掲蛋模拟器。核心亮点是将AI策略以文本形式开放给玩家，支持通过自然语言编程更新上传自定义AI策略。玩家可以让自己的AI策略与内置AI进行对决，或批量模拟统计胜率。
This system supports human-vs-AI play in Guandan. The core feature is that AI strategies are exposed as editable text files, allowing players to improve them through natural language programming. Players can pit their custom AI against the built-in AI, or run batch simulations to compare win rates.
1.3 核心特色  |  Key Features
● 人机对战：玩家坐庄，与3个AI对家对决  |  Human player vs 3 AI opponents
● 模拟对战：批量模拟（默认500局），统计得分与胜率  |  Batch simulation (default 500 rounds) with scoring statistics
● AI策略上传：下载模板、修改、上传自定义AI  |  Download template, edit, upload custom AI
● 双榜排行榜：最近上传榜 + 对战胜率榜（≥500局）  |  Upload leaderboard + Battle win-rate leaderboard (>=500 rounds)
● 微信分享与记录导出  |  WeChat sharing & game log export
二、掲蛋规则  |  Guandan Rules
2.1 升级机制  |  Level System
游戏从2级开始，按 2→3→4→5→6→7→8→9→10→J→Q→K→A 的顺序升级。先打到A级的一方获胜。级牌（当前等级）是每局的“主牌”，其中红心花色级牌为“逢人配”（可当任意牌配合出牌）。
The game starts at Level 2, progressing through 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K, and finally A. The first team to reach Level A wins. The current level card is the "game rank" (main card), and the heart-suited rank card is the "Wild Card" (逢人配) that can substitute for any card in combinations.
2.2 贡牌与还贡  |  Tribute & Return
每局结束后，未打完手牌的玩家需向对家贡牌：末游给头游贡最大牌，三游给二游贡最大牌。头游和二游收到贡牌后选择还贡（给回对家一张不需要的牌）。如果一方包揽1、2名，则对家双贡，且还贡后贡者先出牌。
After each round, players who did not finish must tribute their highest card to opponents: last place gives to first place, third to second. The first and second players return an unwanted card. If one team sweeps 1st and 2nd place, opponents double-tribute and the tributed team leads the next round.
2.3 牌型大小  |  Card Hierarchy
单张：王炸 > 6炸 > 5炸 > 4炸 > 同花顺 > 杂顺 > 三带二 > 三带一 > 三张 > 对子 > 单张。王炸是两张大王，是最大的炸弹。逢人配单独出牌时等同于普通主牌。
Single: King Bomb > 6-Bomb > 5-Bomb > 4-Bomb > Flush > Straight > Full House > Triple+Single > Triple > Pair > Single. King Bomb (two Jokers) is the highest bomb. The Wild Card (逢人配) alone counts as a normal game-rank card.
三、操作指南  |  Operation Guide
3.1 正常对局  |  Normal Game
1. 点击“正常对局”进入游戏界面  |  Click "Normal Game" to enter the play screen
2. 左上角记牌器显示各种牌的剩余数量  |  Card tracker (top-left) shows remaining card counts
3. 点击手牌进行选择，再点次取消选择  |  Click cards to select/deselect
4. 选择牌后点击“出牌”，或点击“不出”过牌  |  Click "Play" to play selected cards, or "Pass" to skip
5. 按钮排：提示 / 不出 / 出牌 / 记牌 / 自动  |  Buttons: Hint / Pass / Play / Tracker / Auto
3.2 模拟对战  |  Simulation Battle
1. 点击“模拟对战”进入模拟界面  |  Click "Simulation Battle" to enter the simulation screen
2. 可选择上传榜中的AI策略作为对家  |  Select an AI from the upload leaderboard as opponent
3. 设置模拟回合数（默认500局，最高1万局）  |  Set round count (default 500, max 10,000)
4. 点击“开始模拟”，系统自动运行  |  Click "Start Simulation" to run automatically
5. 模拟结束后显示：A队/B队胜率、得分统计  |  Results: team win rates and score totals
得分规则：1+2名=3分，1+3名=2分，1+4名=1分，其他=0分  |  Scoring: 1st+2nd=3pts, 1st+3rd=2pts, 1st+4th=1pt, others=0
6. 模拟达500局可上传到对战胜率榜  |  500+ rounds unlocks upload to battle leaderboard
3.3 AI策略上传  |  AI Strategy Upload
1. 首页点击“下载当前AI策略模板”，获取编程基础  |  Download the AI strategy template from home page
2. 用文本编辑器修改AI策略（自然语言编程）  |  Edit the strategy using natural language programming
3. 保存为.txt文件，大小不超过200KB  |  Save as .txt file, max 200KB
4. 正常对局界面“新增AI策略”处上传  |  Upload via "New AI Strategy" on the play screen
5. 同名文件自动重命名（加(1)(2)…）  |  Duplicate filenames auto-renamed (1)(2)...
3.4 排行榜  |  Leaderboards
• 最近上传榜：显示最近上传的20个AI策略，可下载.txt  |  Recent Uploads: last 20 uploaded strategies, downloadable
• 对战胜率榜：显示≥500局模拟的前10名，可下载模型  |  Battle Win-Rate: top 10 with >=500 rounds, models downloadable
• 删除需管理密码（默认87654321）  |  Delete requires admin password (default: 87654321)

--- 感谢使用 AI掲蛋策略对决系统 ---
Thank you for using the AI Guandan Strategy Duel System
