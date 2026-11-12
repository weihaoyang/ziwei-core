# 紫微斗数算法与古籍对照 · Ziwei Core

从 [知几排盘](https://github.com/weihaoyang/qimen-llm-chart) 提取的紫微斗数 TypeScript 算法与回归测试，依赖 iztro；包含共享历法代码。

```sh
npm install
npm run patch:3meta
npm test
npm run typecheck
```

运行前执行补丁以修正本地历法和奇门依赖；入口 `src/lib/ziwei/chart.ts`。尚未发布 npm 包。

## 古籍对照

测试逐格对照[日本国立公文书馆明刊《新镌希夷陈先生紫微斗数全书》](https://www.digital.archives.go.jp/file/1078787) 所录木、金、土、火四局 120 个起紫微位置，以及水二局可辨认条目；另保留字迹待核的位置。馆藏影像使用条件见[影像权利记录](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/sources/RIGHTS.md)。

本仓不附影像，也不收录整理者与授权待核的现代电子重排本转录。判例与异文边界见[研究论文](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)。算法对照不能验证占断效果。

## 授权

代码 [GPL-3.0-only](LICENSE)，源自知几排盘；第三方依赖许可见 `LICENSES/`。馆藏数据与影像按各自来源适用的条件使用。
