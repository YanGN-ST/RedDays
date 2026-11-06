**[English](README.md) | 简体中文**

<p align="center">
  <img src="./assets/readme/hero-zh-v2.svg" width="100%" alt="RedDays: 把假期放进日历。">
</p>

自动更新的日历订阅源，涵盖中国法定节假日、香港公众假期、农历及其他历法。

## 订阅

在 macOS 日历选择「文件 → 新建日历订阅」，粘贴地址。也可以将 `https://` 换成 `webcal://` 打开。

| 日历 | 订阅地址 |
|---|---|
| 大陆假期详细版 | `https://yangn-st.github.io/RedDays/reddays-detailed.ics` |
| 大陆假期极简版 | `https://yangn-st.github.io/RedDays/reddays-minimal.ics` |
| 调休补班 | `https://yangn-st.github.io/RedDays/reddays-workonly.ics` |
| 节气农历 | `https://yangn-st.github.io/RedDays/reddays-lunar.ics` |
| 每日黄历 | `https://yangn-st.github.io/RedDays/reddays-almanac.ics` |
| 香港假期简体 / 繁体 | `https://yangn-st.github.io/RedDays/reddays-hk.ics` / `https://yangn-st.github.io/RedDays/reddays-hk-tc.ics` |
| 民族节日 | `https://yangn-st.github.io/RedDays/reddays-ethnic.ics` |
| 回历每日 | `https://yangn-st.github.io/RedDays/reddays-hijri.ics` |
| 基督教历 | `https://yangn-st.github.io/RedDays/reddays-christian.ics` |

详细版逐日列出假期和补班，极简版列出假期首日和补班，补班版只列补班日。普通周末不单独列出。补班事件包含时间和提醒。

## 数据来源与范围

大陆和香港假期分别依据官方公告。节气农历使用天文计算，民族节日参考地方资料，伊斯兰节日可能因官方见月公告与推算相差一天。每日黄历属于民俗推演，仅供参考。基督教历采用西方教会算法。

次年假期以官方公告和数据校验为准。订阅刷新由设备系统调度。工程说明见 [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md)。

## 许可

假期数据来自官方公告，代码使用 [MIT](LICENSE) 许可。
