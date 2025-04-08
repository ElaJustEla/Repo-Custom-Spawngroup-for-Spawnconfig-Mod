# 🎮Repo-Custom-Spawngroup-for-Spawnconfig-Mod
# 🎮适用于 SpawnConfig 模组的自定义 SpawnGroup 配置
## 📚 Contents
- [🙏 Credits](#-credits)
- [📝 Information](#-information)
- [📦 Setup](#-setup)
- [❌ Removal](#-removal)
- [🌐 Global Changes](#-global-changes)
- [🔥 Challenge Events](#-challenge-events)
- [📅 Events](#-events)

## 📚 中文目录 (Contents for Mandarin)
- [🙏 鸣谢](#-鸣谢)
- [📝 信息](#-信息)
- [📦 安装](#-安装)
- [❌ 卸载](#-卸载)
- [🌐 全局更改](#-全局更改)
- [🔥 挑战事件](#-挑战事件)
- [📅 普通事件](#-普通事件)


## 🙏 Credits

- [**Index154**](https://thunderstore.io/c/repo/p/Index154/SpawnConfig/) – Creator of the **SpawnConfig** mod, which makes this customization possible.
- **You** – For using and supporting this config file!

## 📝 Information

⚠️Notice:
Due to current limitations, events capped with levels will not function properly beyond level 9999.

🚫Warning for New Players:
This script is not recommended for beginners. It assumes the player is experienced enough to handle all enemies with at least 13 Strength and a Stun Gun or similar Items.

🔧Modification:
1. Adjusted enemy spawn rates.
2. Added 3 new Challenge Events.
3. Introduced 9 Events.

## 📦 Setup

This modification require the mod [**SpawnConfig** by Index154](https://thunderstore.io/c/repo/p/Index154/SpawnConfig/)

- Launch REPO **with SpawnConfig installed** at least once to generate the config folder

- Replace **SpawnGroup.json** located at
- ⇒ BepInEx\config\SpawnConfig

## ❌ Removal
- Delete the current **SpawnGroup.json** from
   - ⇒ BepInEx\config\SpawnConfig
- Restore the default file by *copying* **SpawnGroup.json** from
   - ⇒ BepInEx\config\SpawnConfig\Defaults into
   - ⇒ BepInEx\config\SpawnConfig

## 🌐 Global Changes:
1. If an enemy type is defaultly selected, up to **three instances** of that entity group will spawn.
2. In addition to the global rule above, from **level 11 onwards**:
   1. All enemies are guaranteed to appear in each level.
   2. Each Spawn rate may be **tripled**.

⇒ a single enemy group (e.g. One Bowtie, or A pack of 4 Gnomes) can multiply up to 6 groups total.

📌 **Note:** **once a Challenge Event/ Event is triggered**, no other enemy types will spawn beyond the event specifications.

## 🔥 Challenge Events:

ℹ️ *All Challenge Events will have a chance to trigger from level 12.*

1. **Solar Eclipse**:
   - Doubles the spawn count for **all Monster Level 3** enemies.
   - 50% Chance to double the spawn density.
   - ⇒ up to **4 instances** of the same Level 3 entity may spawn.
2. **Blood Moon**:
   - Spawns **all enemy types**, then doubles their spawn count.
   - 33% chance for the spawn rate to double again.
   - ⇒ All enemies may appear **up to 4 time each**.
3. **Full Moon**:
   - Spawns **all Monster Level 2** enemies and triples their count.
   - An additional chance to double again.
   - ⇒ Level 2 enemies may spawn **up to 6 instances per group**.

## 📅 Events:

ℹ️ *All Events are available from all levels.*

1. **Lunar Eclipse** (available from Level 9):
   - Spawns the following **Monster Level 1** enemies:
   1. 5 Peepers
   2. 2 Shadow Child
   3. 8 Gnomes
   4. 5 Ducks
   5. 3 Spewers
   - 50% chance to double spawn density.
   - ⇒ all listed enemies will spawn accordingly, potentially at **double rates**.
2. **Beholder**:
   - Spawn 15 Peepers.
   - 50% chance to double the count.
3. **Yippee Day**:
   - Spawn 10 Ducks.
   - Spawn rate may be **tripled**.
4. **Chef's Choice**:
   - Spawn 10 Chefs.
5. **Rumbling**:
   - Spawn 10 Bowties.
6. **Basketball**:
   - Spawn 10 Upscreams.
7. **Space**:
   - Spawn 10 Trudges.
8. **Relay Race**:
   - Spawn 10 Hiddens.
9. **Restricted**:
   - Spawn 10 Ducks and 15 Peepers.

## 🙏 鸣谢

- [**Index154**](https://thunderstore.io/c/repo/p/Index154/SpawnConfig/) – **SpawnConfig** 模组的作者，使本自定义配置得以实现。
- **你** – 感谢你使用和支持本配置文件！

## 📝 信息

⚠️注意：  
由于当前限制，等级上限超过 9999 的事件将无法正常运作。

🚫新手警告：  
此脚本**不推荐新手使用**，它假设玩家至少拥有使用 13 点力量和一把电击枪或类似道具，具备应对所有敌人的经验。

🔧修改内容：
1. 调整了敌人生成概率。
2. 添加了 3 个全新挑战事件。
3. 引入了 9 个普通事件。

## 📦 安装

此配置需要安装模组 [**SpawnConfig by Index154**](https://thunderstore.io/c/repo/p/Index154/SpawnConfig/)

- 先运行一次已安装 SpawnConfig 的 REPO，让其生成配置文件夹。
- 替换以下路径中的 **SpawnGroup.json** 文件：
  - ⇒ BepInEx\config\SpawnConfig

## ❌ 卸载

- 删除当前路径下的 **SpawnGroup.json** 文件：
  - ⇒ BepInEx\config\SpawnConfig
- 从默认配置文件夹中恢复原文件：
  - ⇒ 将 BepInEx\config\SpawnConfig\Defaults 中的 **SpawnGroup.json**
  - ⇒ *复制* 到 BepInEx\config\SpawnConfig 中

## 🌐 全局更改：

1. 在原始规则下，若游戏选择某类敌人，则最多会生成该组敌人的**最多三倍数量**。
2. 在以上规则的基础上，从 **第 11 级起**：
   1. 所有敌人将**必定**出现在每一关。
   2. 每种敌人生成概率可能**增加至三倍**，并与上述规则叠加。

⇒ 举例：单一敌人组（如一个 蝴蝶结怪，或一组 4 个地精）最多可生成 **6 组**。

📌 **注意：** 一旦**挑战事件或普通事件被触发**，其设定范围外的敌人将不再生成。

## 🔥 挑战事件：

ℹ️ *所有挑战事件将在第 12 级开始有机会触发。*

1. **日蚀**：
   - 所有 **3 级怪物** 敌人生成数量翻倍。
   - 50% 概率使生成密度再次翻倍。
   - ⇒ 最多生成 **4 个相同 3 级敌人数量**。

2. **血月**：
   - 所有敌人类型都会生成，然后其数量翻倍。
   - 33% 概率再翻倍一次。
   - ⇒ 每种敌人最多可出现 **4 次**。

3. **满月**：
   - 所有 **2 级怪物** 敌人生成，并将数量提升为三倍。
   - 有额外几率再次翻倍。
   - ⇒ 每种 2 级敌人最多可生成 **6 个**。

## 📅 普通事件：

ℹ️ *所有事件从任意等级开始都可能触发。*

1. **月蚀**（从第 9 级起可触发）：
   - 生成以下 **1 级怪物**：
     1. 5 个窥视者（Peepers）
     2. 2 个暗影之子（Shadow Child）
     3. 8 个地精（Gnomes）
     4. 5 只鸭子（Ducks）
     5. 3 个喷吐者（Spewers）
   - 50% 概率将生成密度翻倍。
   - ⇒ 所有列出的敌人都将按设定生成，可能会再次**翻倍**。

2. **監視日**：
   - 生成 15 个窥视者。
   - 50% 概率翻倍数量。

3. **鸭鸭日**：
   - 生成 10 只鸭子。
   - 生成率可能生成**三倍**。

4. **厨师之选**：
   - 生成 10 个厨师。

5. **地鸣**：
   - 生成 10 个蝴蝶结怪（Bowties）。

6. **篮球赛**：
   - 生成 10 个尖叫者（Upscreams）。

7. **太空**：
   - 生成 10 个跺行者（Trudges）。

8. **接力棒**：
   - 生成 10 个隐身者（Hiddens）。

9. **禁区**：
   - 同时生成 10 只鸭子和 15 个窥视者。
