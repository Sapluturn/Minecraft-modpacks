# 旷野食光 · Wander & Feast

Minecraft 1.21.1 / NeoForge 21.1.265 整合包，当前版本 0.9。本仓库存放发布文件。

## 仓库结构

```
Minecraft-modpacks/
├── README.md
└── 旷野食光 Wander & Feast/
    ├── 整合包 Modpacks/
    │   ├── 栖居 Homesteaded v0.9.zip
    │   ├── 远行 Expedition v0.9.zip
    │   └── export_config.txt
    └── 附录 Extras/
        ├── 汇流 Confluence v0.9.zip
        ├── 0.9版本说明.md
        ├── 0.9 Release Notes.md
        ├── 旷野食光-整合包介绍.txt
        └── Wander and Feast - Pack Overview.txt
```

## 各文件是什么

**整合包 Modpacks/** —— 主推的两个分化版本，导入启动器即可安装。

- `栖居 Homesteaded v0.9.zip` —— 收敛到居所与庭院，110 个模组。
- `远行 Expedition v0.9.zip` —— 铺开到路途与荒野，107 个模组。
- `export_config.txt` —— PCL2 导出时的选项记录，仅供追溯，安装用不到。

**附录 Extras/** —— 汇流版与说明文件。

- `汇流 Confluence v0.9.zip` —— 两套内容同时保留的合版，122 个模组。它是分化版本的来源，但不作为首选发行版本，故放在附录而非主包目录。
- `0.9版本说明.md` / `0.9 Release Notes.md` —— 本版说明：初版定位、包内结构、汉化组成、已知限制。中英各一份。
- `旷野食光-整合包介绍.txt` / `Wander and Feast - Pack Overview.txt` —— 整合包介绍：主打内容、各版本定位、硬件要求。中英各一份。

三个版本的具体差异、玩法与已知限制，请看上述两份说明与两份介绍，本文件不再重复。

## 格式与安装

三个包的后缀是 `.zip`，实际是 Modrinth 的 `mrpack` 格式（根目录为 `modrinth.index.json` 与 `overrides/`）。启动器按内容识别，直接拖入即可；改后缀为 `.mrpack` 也能用。模组与光影由索引在线下载，安装时需要联网。

PCL2：版本管理 → 安装整合包 → 选择对应 zip。Modrinth App、Prism Launcher、HMCL 同理。三个包均只含客户端内容，不含服务端。

---

# Wander and Feast

A Minecraft 1.21.1 / NeoForge 21.1.265 modpack. Current version: 0.9. This repository holds the release files.

## Repository layout

```
Minecraft-modpacks/
├── README.md
└── 旷野食光 Wander & Feast/
    ├── 整合包 Modpacks/
    │   ├── 栖居 Homesteaded v0.9.zip
    │   ├── 远行 Expedition v0.9.zip
    │   └── export_config.txt
    └── 附录 Extras/
        ├── 汇流 Confluence v0.9.zip
        ├── 0.9版本说明.md
        ├── 0.9 Release Notes.md
        ├── 旷野食光-整合包介绍.txt
        └── Wander and Feast - Pack Overview.txt
```

## What each file is

**整合包 Modpacks/** — the two recommended variants. Import into a launcher to install.

- `栖居 Homesteaded v0.9.zip` — focused on home and garden; 110 mods.
- `远行 Expedition v0.9.zip` — focused on the road and the wild; 107 mods.
- `export_config.txt` — the export options recorded by PCL2. Useful only for tracing how the packs were exported; not needed for installation.

**附录 Extras/** — the combined variant and the documentation.

- `汇流 Confluence v0.9.zip` — both content sets kept together; 122 mods. It is the source the two variants were trimmed from, but it is not the recommended release, which is why it sits in Extras rather than with the main packs.
- `0.9版本说明.md` / `0.9 Release Notes.md` — release notes: what 0.9 is, the pack structure, how the translations are split, known limitations. One Chinese, one English.
- `旷野食光-整合包介绍.txt` / `Wander and Feast - Pack Overview.txt` — pack overview: what the pack is about, how the variants differ, hardware requirements. One Chinese, one English.

For the differences between the three variants, gameplay, and known limitations, read those two notes and two overviews; this file does not repeat them.

## Format and installation

The three archives carry a `.zip` suffix but are Modrinth `mrpack` files (a `modrinth.index.json` and an `overrides/` folder at the root). Launchers detect them by content, so drag and drop works; renaming to `.mrpack` works too. Mods and shaders are downloaded from the index, so an internet connection is required during installation.

PCL2: Versions → Install modpack → pick the archive. Modrinth App, Prism Launcher and HMCL work the same way. All three packs are client-side only; no server pack is provided.
