# img-warehouse

二次元随机图图库仓库，镜像自 [栗次元 API](https://t.alcy.cc)，按分类整理 PC 横图、移动竖图及原神、初音未来、萌版等专题图片，可作为个人图床 / 随机图接口的静态资源使用。

- 图片格式：WebP 原图（无缩略参数）
- 抓取时间：2026-10-26
- 命名规则：`序号_原站文件名`，序号与图库预览页顺序一致
- 唯一图片总数：约 **3049 张**（`acg` 为 `pc` 的复制，不计入）

## 目录结构

| 目录 | 分类 | 图片数 | 随机图接口 |
| :--- | :--- | ---: | :--- |
| [`pc`](./pc) | PC 横图 | 665 | https://t.alcy.cc/pc |
| [`mp`](./mp) | 移动竖图 | 1008 | https://t.alcy.cc/mp |
| [`moe`](./moe) | 萌版横图 | 127 | https://t.alcy.cc/moe |
| [`moemp`](./moemp) | 萌版竖图 | 80 | https://t.alcy.cc/moemp |
| [`ys`](./ys) | 原神横图 | 64 | https://t.alcy.cc/ys |
| [`ysmp`](./ysmp) | 原神竖图 | 35 | https://t.alcy.cc/ysmp |
| [`miku`](./miku) | 初音未来横图 | 405 | https://t.alcy.cc/miku |
| [`mikump`](./mikump) | 初音未来竖图 | 665 | https://t.alcy.cc/mikump |
| [`acg`](./acg) | 二次元自适应（复制自 `pc`） | 665 | https://t.alcy.cc/ycy |

## 自适应分类

“自适应”接口由对应横图与竖图组合而成，可根据设备方向自动返回合适的图片：

| 自适应分类 | 接口 | 构成 |
| :--- | :--- | :--- |
| 二次元自适应 | https://t.alcy.cc/ycy | PC 横图 `pc` + 移动竖图 `mp` |
| 萌版自适应 | https://t.alcy.cc/moez | 萌版横图 `moe` + 萌版竖图 `moemp` |
| 原神自适应 | https://t.alcy.cc/ysz | 原神横图 `ys` + 原神竖图 `ysmp` |
| 初音未来自适应 | https://t.alcy.cc/mikuz | 初音未来横图 `miku` + 初音未来竖图 `mikump` |

## 使用方式

直接通过原站接口获取随机图，也可以将本仓库的图片部署到任意静态托管（如 GitHub Pages、Vercel、对象存储）后自行搭建随机图接口。

```
# 随机返回一张 PC 横图
https://t.alcy.cc/pc

# 随机返回一张移动竖图
https://t.alcy.cc/mp
```

## 版权说明

图片版权归原画师及 [栗次元 API](https://t.alcy.cc) 所有，本仓库仅供个人学习与收藏，**请勿商用**。如有侵权，请联系删除。
