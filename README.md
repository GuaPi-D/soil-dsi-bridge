# soil-dsi-bridge
FAIR bridge ontology between SOIL and D-SI(DCC)
# SOIL ↔ D‑SI 桥接本体

本项目提供一个 **桥接本体**，将 [SOIL 本体](https://purl.org/soil/) 与 [D‑SI 本体](https://ptb.de/si) 的核心语义元素对齐，旨在支持**FAIR**（可查找、可获取、可互操作、可重用）测量数据的互操作性。

---

## 🚀 项目概述

- **名称**：Bridge Ontology: SOIL ↔ D‑SI(DCC)
- **Persistent ID**：<https://w3id.org/projects/soil-dsi-bridge>
- **版本**：1.0
- **许可协议**：CC BY 4.0（[查看协议](https://creativecommons.org/licenses/by/4.0/)）
- **作者**：[Z. D.](https://orcid.org/0009-0004-9085-4516) and K.W.
- **创建日期**：2025‑05‑20

此桥接本体通过 `owl:equivalentClass`、`owl:equivalentProperty` 以及 `rdfs:subPropertyOf` 等关系，完成了测量量、数值、单位、时间、不确定度等核心元数据在两套本体中的双向对齐。

---

## ⚙️ 使用方法

你可以在 Turtle 文件开头导入本体并声明命名空间：

```ttl
@prefix bridge: <https://w3id.org/projects/soil-dsi-bridge#> .
@base <https://w3id.org/projects/soil-dsi-bridge#> .

<https://w3id.org/projects/soil-dsi-bridge>
    a owl:Ontology .
```

或在 OWL/RDF 应用中直接引用：

```xml
<owl:Ontology rdf:about="https://w3id.org/projects/soil-dsi-bridge"/>
```

本体文件（Turtle 格式）下载：
- [`soil-dsi-bridge.ttl`](soil-dsi-bridge.ttl)

---

## 🎓 创建者

- **Z. D.** （ORCID: [0009‑0004‑9085‑4516](https://orcid.org/0009-0004-9085-4516)）
- **K.W.**

---

## 📖 引用方式

```
Z. D. (2025). Bridge Ontology: SOIL ↔ D‑SI. Version 1.0. CC BY 4.0. Available at https://w3id.org/projects/soil-dsi-bridge
```

---

感谢关注与使用！如有建议或问题，欢迎提交 [Issue](https://github.com/GuaPi-D/soil-dsi-bridge/issues)。
