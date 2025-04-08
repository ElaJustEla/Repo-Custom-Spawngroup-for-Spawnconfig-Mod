# 🎮Repo-Custom-Spawngroup-for-Spawnconfig-Mod

## 📚 Contents
- [🙏 Credits](#credits)
- [📝 Information](#information)
- [📦 Setup](#setup)
- [❌ Removal](#removal)
- [🌐 Global Changes](#global-changes)
- [🔥 Challenge Events](#challenge-events)
- [📅 Events](#events)

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
3. Introduce 9 Events.

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
1. If an enemy type is selected, up to **three instances** of that entity group will spawn.
2. From **level 11 onwards**:
   1. All enemies are guaranteed to appear in each level.
   2. Each Spawn rate may be **tripled**, in addition to the global rule above.

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
   - An additional chance to triple again.
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
