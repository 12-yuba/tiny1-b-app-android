# Tiny1-b 热成像 AI 修改版

> **作品来自 Lyu 原版修改，使用 Gemini 完成补全。**
>
> **【安全提醒】** 本程序为纯本地代码优化补全，理论无任何恶意程序，请放心使用。

## 当前版本：分支 2 —— 默认不开启超分（带记忆效果）

### 本次增强功能

- **2 个独立矩形框测温**：计算局部最高温、最低温、平均温与极值位置指针
- **3 个任意点自定义测温**：支持屏幕自由拖拽与二级菜单精准增减
- **超分/降噪开机记忆**：支持开机自启记忆档位，无需每次手动打开
- **伪彩模式名称修复**：彻底修复调色板 3~7 号中文乱码

### 连接说明

程序支持 **Tiny1-B** 和 **CT256 模块**。如果插上没反应，请检查：

1. 是否开启 OTG 功能
2. 设备端下拉电阻设置是否正确
3. 手机供电能力是否正常

---

## English

# Tiny1-b Thermal Imaging — AI Modified Edition

> **This work is modified from the original version by Lyu, with completion assisted by Gemini.**
>
> **[Security Notice]** This program is a purely local code optimization/completion. It contains no malicious code in theory — feel free to use it.

## Current Version: Branch 2 — Super-Resolution OFF by Default (with Memory Effect)

### Enhancements in This Version

- **2 independent rectangular measurement boxes**: calculates local max / min / average temperature, with extreme-value position pointers
- **3 freely-placeable custom measurement points**: supports free dragging on screen and precise increase/decrease via a secondary menu
- **Super-resolution / denoise boot memory**: remembers the selected level across reboots — no need to re-enable it every time
- **Pseudo-color mode name fix**: thoroughly fixes the Chinese garbled-text issue for palettes No. 3–7

### Connection Notes

The program supports the **Tiny1-B** and the **CT256 module**. If nothing happens after plugging in, please check:

1. Whether OTG is enabled
2. Whether the pull-down resistor setting on the device side is correct
3. Whether the phone's power supply is sufficient
