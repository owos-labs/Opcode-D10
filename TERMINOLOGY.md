# Opcode:// D10 — Terminology Table

Canonical EN ↔ CN reference for rules text, translation, and cross-language linking.  
Abbreviations stay in English in both languages unless noted.

**Legend:** *canonical* = use this pairing; *alias* = appears in text but prefer canonical; *open* = inconsistent across files — pick one and align.

---

## System & Meta

| English | 中文 | Notes |
| --- | --- | --- |
| Opcode:// D10 | Opcode:// D10 | Product name; do not translate |
| Skill Check | 技能检定 | |
| Extended Check | 长线检定 | |
| Specialisation / Specialization | 专精 | EN uses both spellings |
| Difficulty | 难度 | |
| Critical Success | 大成功 | |
| Critical Failure | 大失败 | |
| Margin of failure | 失败数 | Stun save penalty |
| Player Character (PC) | PC / 人形角色 | CN uses「人话：PC」in 1.3 |
| Game Master (GM) | GM / DM | CN sometimes writes DM |
| Optional rule | 可选规则 | |
| Extension rule | 扩展规则 | |

---

## Attributes

| English | 中文 | Abbr. | Notes |
| --- | --- | --- | --- |
| Reflex | 反射 | REF | |
| Intelligence | 智力 | INT | |
| Willpower | 毅力 | WIL | |
| Charisma | 魅力 | CHR | |
| Constitution | 体质 | BOD | EN header says Constitution; skill **Fortitude** covers saves |
| Luck | 幸运 | LUK | |
| Mental Attributes | 心智属性 | | |
| Physical Attributes | 生理属性 | | |
| Derived Attributes | 衍生属性 | | |
| Special Attributes | 特殊属性 | | |

---

## Derived Attributes

| English | 中文 | Abbr. | Formula (EN) | Notes |
| --- | --- | --- | --- | --- |
| Movement Speed | 移动速度 | MOV | `(BOD + REF) × 2` m | *open:* CN 1.1 writes `BOD+REF` without `×2` — align to EN |
| Perception Range | 感知距离 | SENS | `(REF + WIL) × 2` m | A/V/S sub-ranges in rules |
| Hit Points | 受击点数 | HP | `(WIL×0.5 + BOD×2) + 6` | CN keeps「受击点数」; HP abbr. OK in tables |
| Weight Tolerance | 负重 / 最大承载重量 | WGT | `20 + 10×BOD` kg | *alias:* 1.1 uses「负重」; 1.1.1 uses「最大承载重量」→ prefer **负重 (WGT)** in prose, spell out formula in 1.1.1 |
| Carryable Weight | 可承载重量 | | | Loose gear + hands + pack capacity |
| Encumbrance | 负重（当前） | | | Current load vs WGT thresholds |
| Initiative | 主动性 / 先攻 | | `1D10 + REF + mods` | CN often adds「先攻」in parentheses |

---

## Core Skills

| English | 中文 | Key Attributes (EN) | Notes |
| --- | --- | --- | --- |
| Focus / Perception | 专注 / 洞察 | WIL | SLLS = 停下，观察，聆听，闻嗅 |
| Survival | 生存 | WIL | |
| Medical | 医疗 | WIL | |
| Composure | 沉着 | WIL / BOD | |
| Seduction | 煽动 | CHR / WIL / BOD | Also used for intimidation |
| Social | 社交 | CHR / INT | |
| Disguise | 伪装 | CHR / WIL | |
| Operate | 器用 | REF / INT | Vehicles, tools, computers |
| Library | 图书馆 | INT / WIL | Research / databases |
| Reconnaissance | 侦察 | INT | Perception saves often `INT + 感知：侦察` |
| Fabrication | 制造 | INT | |
| Knowledge | 知识 | INT | |
| Concealment | 潜藏 | INT / WIL / REF | Stealth uses this skill |
| Marksmanship | 射击 | REF | Underbarrel = 下挂 |
| Athletics | 运动 | REF | Includes climbing |
| Acrobat | 特技 | REF | Fine manipulation, locks, craft |
| Martial Arts | 武术 | REF / BOD | Requires style specialisation |
| Archery | 弓道 | REF | |
| Fortitude | 强韧 | BOD / WIL | Used in Stun/Death saves (`+强韧`) |
| Swimming / Unconventional Environment Movement | 游泳 / 非常规环境移动 | BOD / REF | |
| Brawling | 搏击 | BOD | |
| Pulling / Lifting | 拉举 | BOD | |

### Operate — common specialisations

| English | 中文 |
| --- | --- |
| Computers | 电脑 |
| Industrial Machinery | 工业机械 |
| Heavy Vehicles | 重型载具 |
| Tactical Driving | 战术驾驶 |
| Rotary Wing Aircraft | 旋翼飞行器 |
| Fixed Wing Aircraft | 固定翼飞行器 |
| Specialized Vehicles | 特殊载具 |
| Unmanned Systems & Vehicles (US&V) | 无人系统和载具 |

---

## Extension Skills

| English | 中文 | Key Attributes | Notes |
| --- | --- | --- | --- |
| Artillery | 炮术 | INT | Rifled/s smoothbore guns, rockets, mortars, missiles |
| Heavy Weapons | 重武器 | REF | HMG, autocannon, AGL at direct fire; *open:* CN header once wrote「重火力」as attr label — use **重武器** |
| Guided Weapons (specialisation) | 制导武器 | | Under Artillery or cross-skill |
| Counter-Battery (specialisation) | 反炮击 | | `炮术（反炮击）` |
| Driving (vehicle category) | 驾驶（载具类别） | | Extension: vehicles |

---

## Difficulty & Checks

| English | 中文 | Value |
| --- | --- | --- |
| Easy | 简单 | 10 |
| Normal | 普通 | 15 |
| Hard | 困难 | 20 |
| Very Hard | 非常困难 | 25 |
| Nearly Impossible | 几乎不可能 | 30 |
| Under Pressure | 承受压力 | +2 |
| Untrained | 未受训 | +5 |
| Luck Save | 幸运豁免 | |
| Perception Save | 感知豁免 | |
| Reflex Save | 反射豁免 | |
| Agility Save | 敏捷豁免 | Used vs suppression, some guided weapons |
| Fortitude Save | 强韧豁免 | |
| Stun Save | 晕眩豁免 | `1D10 + WIL + 强韧 vs 10 + 晕眩点数` |
| Death Save | 死亡豁免 | `1D10 + BOD + 强韧 vs 10 + 已受到的伤害` |
| Stabilise Wounds | 稳定伤势 | Standard action; CN 稳定伤势 |
| Stun Meter / Stun Points | 晕眩点数计量槽 / 晕眩点数 | |

---

## Health & Body

| English | 中文 | Notes |
| --- | --- | --- |
| Health System | 健康系统 | |
| Body part | 身体部位 / 身体组件 | CN table uses 身体组件名称 |
| Head | 头部 | |
| Torso | 躯干 | |
| Primary Hand | 主手 | |
| Secondary Hand | 副手 | |
| Left Leg | 左腿 | |
| Right Leg | 右腿 | |
| Hit location | 命中位置 / 受击目标 | |
| Destroyed (state) | 摧毁（效果） | Limb barely functional |
| Separated (state) | 分离（状态） | Not necessarily amputation |
| Overflow damage | 伤害溢出 | >2 in one hit triggers Separated |
| Soft Kill / Combat Incapacitation | 软击杀 / 重伤脱战 | Optional rule |
| Simplified Health Pool | 简易生命槽 | Optional rule |

---

## Combat

| English | 中文 | Notes |
| --- | --- | --- |
| Combat Round | 战斗轮 | 3 seconds |
| Ambush | 伏击 | |
| Ambush Round / Ambush Window | 伏击轮 / 伏击窗口 | |
| Action Queue | 动作队列 | |
| Movement Action | 移动动作 | |
| Free Action | 自由动作 | |
| Standard Action / Action | 标准动作 / 动作 | |
| Full Action / Full Round Action | 整轮动作 | |
| Aim | 瞄准 | |
| Suppressive Fire | 火力压制 | |
| Unified penalty | 统一惩罚值 | Multi-action penalty |
| Ranged Attack | 远程攻击 | |
| Melee Attack | 近战攻击 | |
| Rate of Fire (ROF) | 射速 | Rounds per minute |
| Walk your fire | Walk your fire | Keep English in CN narrative examples OK |
| Penetration | 穿透 / 穿甲 | AR context: 穿甲; ammo stat: 穿透 |
| Over-penetration | 过穿 | |

### Fire modes

| English | 中文 | Abbr. |
| --- | --- | --- |
| Semi-Automatic | 半自动 | SA |
| Full Automatic | 全自动 | FA |
| Burst | 爆发 | B |

### Weapon reliability

| English | 中文 | Abbr. |
| --- | --- | --- |
| Unreliable | 不可靠 | U |
| Normal | 一般 | N |
| Very Reliable | 非常可靠 | V |

### Concealability (weapons)

| English | 中文 | Abbr. |
| --- | --- | --- |
| Excellent | 优良 | E |
| Good | 出色 | G |
| Common | 普通 | C |
| Poor | 较差 | P |
| Non-Concealable | 不可隐蔽 | N |

---

## Combat Information (Target Localization)

EN tier names map to CN as below — **do not swap 精确 / 完全**.

| English | 中文 | Attack modifier | Notes |
| --- | --- | --- | --- |
| Approximate Location / Approximate Localization | 模糊定位 | Cannot direct-attack | Know presence, outgoing damage, initiative |
| Exact Localization | 精确定位 | −5 | Rough position, no direct LOS |
| Full Localization / Precise Location | 完全定位 | 0 | Visual or sensor contact |

Cover aim modifiers (stack with localization):

| English | 中文 | Modifier |
| --- | --- | --- |
| Base: Exact Location | 基础：精确定位 | +5 |
| Base: Precise Location | 基础：完全定位 | +0 |
| Cover: 1/3 Height | 掩体：1/3高度遮蔽 | +2 |
| Cover: Half Height | 掩体：半身遮蔽 | +3 |
| Cover: Full Height | 掩体：全身遮蔽 | +5 |

---

## Armor & Cover

| English | 中文 | Abbr. | Notes |
| --- | --- | --- | --- |
| Armour / Armor | 护甲 | | |
| Armour Rating | 护甲等级 / 护甲值 | AR | |
| Structural Strength Points | 结构强度点数 | SSP | Cover degradation |
| Coverage (Primary) | 主要防护区域 | | Hard plates |
| Coverage (Secondary) | 次要防护区域 | | Soft armour |
| Armour Material | 防护材料 / 护甲材质 | | |
| Cover | 掩体 | | Provides AR + SSP + aim difficulty |
| Concealment (environment) | 遮蔽物 | | Visibility only; bushes, smoke |
| Concealability (armor table) | 隐蔽性 | F/P/N | F=concealable under clothes, etc. |

---

## Weapons & Ammunition

| English | 中文 | Notes |
| --- | --- | --- |
| Weapon | 武器 | |
| Ranged weapon | 远程武器 | |
| Melee weapon | 近战武器 | |
| Projectile / ballistic weapon | 射弹武器 | |
| Calibre / Caliber | 口径 | |
| Accuracy | 精度 | |
| Reliability | 可靠性 | |
| Range | 射程 | |
| Underbarrel launcher / Underbarrel | 下挂 | UBGL in examples |
| Magazine | 弹匣 | |
| Accessory | 配件 | |
| Ammunition | 弹药 | |
| Damage dice | 伤害骰 | |
| Projectile Count (shotgun) | 投射物数量 | |
| Explosive | 爆炸物 | |
| Artillery calibre | 火炮口径 | ≥37 mm, D10 or D20 |

### Warhead types

| English | 中文 | Abbr. |
| --- | --- | --- |
| High-Explosive | 高爆 | HE |
| High-Explosive Anti-Tank | 破甲 | HEAT |
| High-Explosive Squash Head | 碎甲 | HESH |
| Armour-Piercing / Kinetic Penetrator | 动能穿透 / 穿甲 | AP |
| Flechette | 镖弹 | |
| Shot / buckshot | 霰弹 | |
| Cluster munition | 集束弹 | |
| Canister | 子母弹 | |
| API (armour-piercing incendiary) | 穿甲燃烧 | API |

---

## Heavy Weapons & Artillery Extension

| English | 中文 | Notes |
| --- | --- | --- |
| Direct-fire heavy weapons | 直射重火力 | Artillery skill; miss = offset impact |
| Indirect fire / curved trajectory | 曲射 / 曲射重火力 | Mortars, howitzers |
| Point of impact / impact point | 落点 / 着弹点 | |
| Offset / deviation | 偏移 | |
| Machine gun / autocannon / anti-materiel rifle | 重机枪 / 机炮 / 反器材武器 | Use normal Marksmanship rules |
| Guided weapon | 制导武器 | |
| Fire-and-forget | 射后不管 | |
| Unguided launch | 非制导发射 | |
| Semi-automatic guidance / man-in-the-loop | 半自动制导 / 人在回路 | |
| Active guidance | 主动制导 | |
| Tracking (weapon stat) | 追踪（属性） | Fixed successes per round |
| Manual override | 手动超控 | |
| Launch platform | 发射平台 | |
| Time of flight | 着弹时间 | ≥3 s typical; may resolve next round |
| Artillery duel / artillery combat round | 炮战 / 火炮战斗轮 | Every 2nd normal round (~6.6 s) |
| Targeting difficulty pool | 定位难度 | Base 15 +10/km |
| Counter-battery radar | 反炮兵雷达 | Gen 1/2/3 in extension |
| Shoot-and-Scoot | Shoot-and-Scoot | Keep English |
| MLRS | 多射火箭系统 | |
| RPG / recoilless rifle | 火箭推进榴弹 / 无后坐力炮 | |

### Guidance modes (keep abbreviations)

| English | 中文 | Abbr. |
| --- | --- | --- |
| Manual Command Line of Sight | 手动视线制导 | MCLOS |
| Semi-Automatic Command Line of Sight | 半自动视线制导 | SACLOS |
| Manual Command to Line of Sight | — | MACLOS |
| Command to Line of Sight | — | CLOS |
| Command Off Line of Sight | — | COLOS |
| Terminal Velocity Missile / Track-via-Missile | — | TVM |
| Semi-Active Radar Homing | — | SARH |
| Computer vision | 计算机视觉 | CV |
| GNSS / GPS guidance | GNSS/GPS 制导 | |

---

## Open Alignments (fix when editing)

| Topic | EN | CN today | Recommendation |
| --- | --- | --- | --- |
| MOV formula | `(BOD+REF)×2` | `BOD+REF` in 1.1 | Fix CN to match EN |
| WGT label | Weight Tolerance | 负重 / 最大承载重量 | **负重 (WGT)** in 1.1; **最大承载重量** as section title in 1.1.1 only |
| BOD attribute name | Constitution | 体质 | Keep both; note Fortitude skill = 强韧 |
| Localization EN labels | Exact vs Precise | 精确 vs 完全 | Table above; EN "Exact" ≠ intuitive "precise" |
| Heavy Weapons attr line | REF + Heavy Weapons | 敏捷+重火力 | Use **反射+重武器** |
| Stabilise vs Stabilize | Stabilise Wounds | 稳定伤势 | EN `-ise`; CN 稳定 |

---

*Last synced against repo: 2026-10-03. Update this file when coining new terms in either language.*
