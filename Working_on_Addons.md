# Working on Addons

很久以前弄過一些插件的翻譯，後來~~太懶了~~停止了大部份工作，只修復錯漏或機翻。最近拾起來是因為經典版帶起一波新插件的誕生潮，然後又看見某圈養用戶的簡體翻譯**逮著機會就嘲諷zhTW**，僅管他明知道有些機翻是外文作者因為翻譯人員短缺自己扔goolgle翻譯做的。

讓官方版本有完整的中文化可用，從而杜絕圈養行為，一個已經15年的遊戲現在才來說這個其實有點晚了。

這個列表是給自己的工作做個紀錄，免得忘記後續完善工作。

## 協力

* AltzUI
    * 主要協力在WOWInterface收集用戶反饋，並代為上傳更新。
* Bigwigs
    * 主要協力翻譯和資料收集，資料收集並不針對特定對象，可以查看[本項目的ReadMe](https://github.com/EKE00372/WOWThings/blob/master/README.md)。
* ClassicCodex
    * 模仿pfQuest導入了芒果單機的資料，但因為這個資料來源本身就有錯誤所以還有漫長的校對工作要做。

## 翻譯

* wMarker
    * 極早期，後來出過作者自己機翻新詞條卻銘謝我結果被朋友打了（並沒有）的事
* [Bigwigs](https://github.com/BigWigsMods/BigWigs/commits?author=EKE00372)
    * zhTW/zhCN
    * 主要是zhTW，zhCN主貢獻者是Adavak
* [LittleWigs](https://github.com/BigWigsMods/LittleWigs/commits?author=EKE00372)
    * zhTW/zhCN
    * 主要是zhTW，zhCN主貢獻者是Adavak
* BFAInvasionTimer
* LegionInvasionTimer
* [Questie](https://github.com/AeroScripts/QuestieDev/commits?author=EKE00372)
    * zhTW/zhCN
* [Guidelime](https://github.com/max-ri/Guidelime/commits?author=EKE00372)
    * zhTW/zhCN
    * 關於WORD_LIST系列的詞條：這個東西只在「在遊戲內使用插件的導入工具導入一個中文版的指南文本」時才會發揮作用，也就是說只有在下面四種條件都成立的情況下才會發揮作用。向作者Borick詢問後，他的建議是不必去翻譯這些東西：
        * 編寫的語言是中文
        * 照著WORD_LIST翻譯詞條的格式編寫
        * 純文字的文本，不像CURSE上製成附加模組的攻略
        * 分享出來再被其他人導入
* Guidelime_Shiku
    * zhTW/zhCN
    * 實施上應該去翻sage......但是sage不願意授權，因為他還在頻繁更新攻略。
* nPlates
    * zhTW/zhCN
* KuiNameplates
    * zhTW/zhCN
* [YaHT](https://github.com/Aviana/YaHT/commits?author=EKE00372)
    * zhTW/zhCN
* [LunaUnitFrames](https://github.com/Aviana/LunaUnitFrames/commits?author=EKE00372)
    * zhTW/zhCN
* AuctionFaster
    * zhTW/zhCN
    * 修正某些奇怪的翻譯詞條，否則把一個句子切成多段根本沒法翻，不同語言的語序是不一樣的。
* [odui_classic](https://github.com/obble/modui_classic/commits?author=EKE00372)
    * zhTW/zhCN
    * 聊天的GlobalStrings待補，這部份要等作者更改格式才會去補。
* Monkey Mods
    * zhTW/zhCN
    * 修正對東亞語系的支援問題，免得全是問號還要改字體
* RealMobHealth
    * zhTW/zhCN
    * zhCN主貢獻者是HopeASD
    * 增加了選項的詳細說明
* RgsCT
* RSPlates(Col)
    * zhTW/enUS
* Nioro
    * zhTW
* EnhancedChatFilterMODFix
    * zhTW
    * 作者覺得沒人用就把locale刪了，又給它加回來，哪天又刪了誰嚎一下......
* Gearmenu
    * zhTW/zhCN
    * zhCN主貢獻者是HopeASD
    * 某些詞條直接引用GlobalStrings

## 維護

* KeepIronskin
    * 酒僧的小工具
* diminfo
    * 訊息條

## 原作

* EKPlates
    * 名條
* EKMinimap
    * 小地圖
* MooseLight
    * 自動調整亮度
* oUF_Ruri
   * ouf的頭像和名條
* oHWell
    * **經典版**的自動下座騎、自動站立、快速取消變身

## 翻譯挖坑

* wago.io
     * https://github.com/oratory/wago.io/issues/52
* TradeSkillMaster
     * 這是2011年就挖的坑
* WCL
     * 這可有點難了......
* zhTW本地化的外部備份
     * Unit/Object/QuestName/QuestLog/Item這些東西的本地化清單
     * 芒果單機的清單不完整，而且與經典版不同的詞條相當多
* Ruf
     * 這頭像挺順眼的。
* [AHDB](https://www.curseforge.com/wow/addons/auction-house-database)
* 一些需要補完的
     * PitBull4
     * [RacipeRadarClassic](https://www.curseforge.com/wow/addons/recipe-radar-classic)
     * 某些已經完成70%以上的只要後續補完就可以了......
* [GB/T 15834―2011标点符号用法]https://people.ubuntu.com/~happyaron/l10n/GB(T)15834-2011.html
     * 備忘，畢竟不熟
