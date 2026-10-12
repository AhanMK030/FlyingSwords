# 人皇幡 / Human Sovereign Banner

飞剑 Mod 新增的成长神器，使用专属模型、武器图标、黑气粒子特效与原版大棒攻击动作。

## 初始获取

载入存档后打开 **UMM → Flying Swords / 飞剑 → 领取初始人皇幡**。

每个存档只能领取一把初始+0成长版人皇幡。领取不赠送魂精，不解封能力。已持有成长版、已有永久解封进度或已经领取过的存档不能重复领取，丢弃后也不会恢复领取资格。旧存档的已有成长版、魂精、解封与附魔均保留。

UMM中已移除飞剑、名剑和人皇幡各阶段测试领取选项；飞剑与名剑仍可从商人获取。此前已经领取的固定阶段测试人皇幡仍受支持，但不再提供新的测试领取入口。正常人皇幡在队伍物品栏或队伍成员装备中时，队伍击杀指定首领即可解封；仅放在共享仓库不算持有。

## 成长阶段

| 阶段 | 首领 / 地点 | 增强 | 重击 | 触及 | 本源能力 |
| --- | --- | --- | --- | --- | --- |
| 0 | 初始 | +0 | 20/×3 | 5尺 | 炼魂、炼魂化财、融魂入幡 |
| 1 | 序章盾牌迷宫：水元素 | +1 | 20/×3 | 5尺 | 元素之躯 |
| 2 | 第一章市场广场：食魂魔 | +2 | 19–20/×3 | 5尺 | 摄魂护体 |
| 3 | 第二章眷泽城：灾劫巨口 | +3 | 19–20/×3 | 10尺 | 血战不休 |
| 4 | 第三章午夜庙宇：取乐的黑暗 | +4 | 19–20/×3 | 10尺 | 夺法 |
| 5 | 第四章科利菲尔：影龙米勒兹梅拉 | +5 | 18–20/×3 | 10尺 | 蚀骨 |
| 6 | 第五章无可逃脱的监狱（象牙迷宫）：苍白女士／Ashen Lady的最终战斗形态 | +5 | 18–20/×3 | 10尺 | 万魂朝皇 |

始终为原版大棒类别的双手近战武器，基础伤害 **1d12钝击、寒铁**。使用大棒的原版熟练、专攻、精通重击与武器训练规则。正常武器的数值采用已击败首领对应的最高阶段；本源能力只来自实际解封的首领，跳过首领不会补送其能力。存档共享解封状态，丢弃与长休均不重置。

## 本源能力

- **元素之躯**：引用实际水元素免疫组件，免疫毒素、睡眠、麻痹、震慑、重击、精准伤害、夹击与寒冷。
- **摄魂护体**：装备者在队伍击杀时累积 `max(1, floor(CR))` 临时生命值，上限为其最大生命值的50%；受伤按原版临时生命值规则消耗，长休清空。
- **血战不休**：装备者在队伍击杀时累积人皇幡命中与伤害各+1，最多+3，长休清空。
- **夺法**：每轮首次命中随机窃取一个可驱散、有限持续时间的正面法术增益，保留剩余持续时间和原施法者。排除永久、区域、神话及非普通法术来源的效果。
- **蚀骨**：每次命中额外造成1点体质属性伤害，沿用原版属性伤害及免疫规则。
- **万魂朝皇**：六项基本属性各+4独特加值，可与其他来源叠加，多柄人皇幡不重复叠加。

武器详情的介绍只保留来历文字。能力规则显示在原版附魔信息和技能说明中。

## 魂精与原版技能栏

队伍击杀普通敌人时，在队伍持有人皇幡的前提下获得 `max(1, floor(CR))` 魂精；使用原版挑战等级字段，缺失时按1计。己方、召唤物、假单位及禁止经验结算的制造单位不产出；同一单位只结算一次。余额随存档共享，长休保留。在“炼魂化财”和“融魂入幡”的原版技能提示中查看余额。

装备人皇幡后使用原版技能栏：

1. **炼魂化财**展开为1、10、50、100或全部，1魂精换50金币。余额不足的选项不可使用。
2. **融魂附魔**展开一个原版小框，18项**融魂·附魔名称**都在框内以开关形式选择。+1/+2可同时选择1项，+3/+4选择2项，+5选择3项；+0不能选择。已开启的选项再次点击即可取消。
3. 选择后使用 **融魂入幡** 确认并支付全部费用。新组合替换旧组合，不返还旧费用。
4. **清空融魂选择**仅取消待确认选项，不花费魂精，不移除已生效的组合。

所有附魔持续到下一次完整长休。未花费魂精与永久解封保留。没有总增强等效+10的限制；相同附魔不可重复选择，同元素基础附魔与爆发附魔不能同时选择。

| 魂精 / 每项 | 原版附魔 |
| --- | --- |
| 20 | 炽焰、寒霜、电击、酸蚀、雷鸣、幽冥、觅心 |
| 40 | 焰爆、冰爆、电爆、酸爆、神圣、邪恶、公理、混沌 |
| 60 | 邪恶异界生物破敌、追击 |
| 80 | 光能 |

邪恶异界生物破敌的60魂精是本方案的自定义费用。具体攻击效果使用游戏已有附魔蓝图。

## 当前验证范围

编译、实际游戏程序集的蓝图与规则回归检查、存档字段序列化和安装包完整性检查。专属外观采用提供的人皇幡模型，保留原版大棒双手挥击动作。尚需实机验证六个首领的完整剧情流程、附魔的最终战斗表现以及原版技能栏交互。

## 外观与黑气

全部成长版和测试版采用专属模型与物品图标。黑气由两层 Unity ParticleSystem 实现：软烟团与旋绕烟丝。+0没有黑气；+1/+2淡黑气；+3/+4浓黑气；+5（第五、第六阶段）强烈黑气萦绕。解封时会自动更新浓度。材质关闭自发光，使用适配游戏 Owlcat 渲染管线的透明混合着色器。攻击预览使用原版骨架与原版大棒对应的 AxeTwoHanded 动画，并非游戏录像。

## English quick start

Load a save, then open **UMM → Flying Swords → Claim Initial Human Sovereign Banner**. This grants one initial +0 progressing banner per save, without essence or unlocks. Existing normal banners and permanent unlocks count as having claimed it. Dropping the weapon does not restore claim eligibility. Weapon-testing grant options have been removed; previously granted fixed-stage trial items remain supported. See [the English Nexus introduction](NexusBannerDescription.en.md) for all powers and required bosses.

This is a cold-iron, two-handed melee **Greatclub**, dealing **1d12 bludgeoning**, with a **×3** critical multiplier. Party kills grant CR-based soul essence while the party carries a banner. The six listed hidden bosses permanently unlock their corresponding powers while a normal banner is present. Save-wide essence and unlocks survive rest, dropping the banner.

While wielding it, use the native ability bar to **Refine Souls into Gold** (1 essence = 50 gold). Expand **Infusion Enchantments** to select any of the 18 enchantment toggles, then confirm with **Infuse Souls into the Banner**. Click an active toggle again to deselect it. Up to one/two/three enchantments are allowed at +1/+3/+5. Replacing a combination pays its complete cost again. Temporary enchantments, Soul Ward and Blood Battle stacks clear after a completed rest; permanent unlocks and unused essence remain. Existing saves gain the new menu automatically; old banner toggle shortcuts are consolidated once, preserving unrelated action-bar slots.

The supplied banner model and painted inventory icon replace the placeholder. Native Greatclub (AxeTwoHanded) attacks are retained. Two Unity particle layers provide faint mist at +1/+2, dense mist at +3/+4, and intense swirling black mist at +5; +0 has no mist. The shader includes the game's Owlcat ForwardLit pass. Preview videos use the native skeleton and clip in Unity, rather than in-game footage. Full in-game boss, toolbar and combat testing remains necessary.
