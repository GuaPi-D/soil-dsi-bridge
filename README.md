# soil-dsi-bridge

一个将 SOIL 本体与 D-SI 本体核心语义元素对齐的 FAIR 桥接本体

A FAIR bridge ontology aligning core semantic elements of the SOIL and D-SI ontologies

Eine FAIR Brückenontologie, die zentrale semantische Elemente der SOIL- und D-SI-Ontologien ausrichtet

---

## 📚 Language | 语言 | Sprache

* [简体中文](#简体中文)
* [English](#english)
* [Deutsch](#deutsch)

---

## 简体中文

### 项目概述 🚀

* **名称**：Bridge Ontology: SOIL ↔ D-SI(DCC)
* **Persistent ID**：[https://w3id.org/soil-dsi-bridge](https://w3id.org/soil-dsi-bridge)
* **版本**：1.0
* **许可协议**：CC BY 4.0（[查看协议](https://creativecommons.org/licenses/by/4.0/)）
* **作者**：Z. D.（ORCID: [0009-0004-9085-4516](https://orcid.org/0009-0004-9085-4516)）、K. W.
* **创建日期**：2025-05-20

此桥接本体通过 `owl:equivalentClass`、`owl:equivalentProperty` 及 `rdfs:subPropertyOf` 等映射关系，实现测量量、数值、单位、时间、不确定度等核心元数据在 SOIL 与 D-SI 两套本体中的双向对齐，帮助实现数据的可查找、可获取、可互操作、可重用。

### 使用方法 ⚙️

在 Turtle 文件开头导入并声明命名空间：

```ttl
@prefix bridge: <https://w3id.org/soil-dsi-bridge#> .
@base  <https://w3id.org/soil-dsi-bridge#> .

<https://w3id.org/soil-dsi-bridge>
    a owl:Ontology .
```

或者在 OWL/XML 应用中引用：

```xml
<owl:Ontology rdf:about="https://w3id.org/soil-dsi-bridge"/>
```

**本体文件下载**

* [`soil-dsi-bridge.ttl`](soil-dsi-bridge.ttl)

### 创建者 🎓

* **Z. D.** （ORCID: [0009-0004-9085-4516](https://orcid.org/0009-0004-9085-4516)）
* **K. W.**

### 引用方式 📖

```
Z. D. (2025). Bridge Ontology: SOIL ↔ D-SI. Version 1.0. CC BY 4.0. Available at https://w3id.org/soil-dsi-bridge
```

---

## English

### Project Overview 🚀

* **Name**: Bridge Ontology: SOIL ↔ D-SI(DCC)
* **Persistent ID**: [https://w3id.org/soil-dsi-bridge](https://w3id.org/soil-dsi-bridge)
* **Version**: 1.0
* **License**: CC BY 4.0 ([see details](https://creativecommons.org/licenses/by/4.0/))
* **Authors**: Z. D. (ORCID: [0009-0004-9085-4516](https://orcid.org/0009-0004-9085-4516)), K. W.
* **Created**: 2025-05-20

This bridge ontology uses mappings such as `owl:equivalentClass`, `owl:equivalentProperty`, and `rdfs:subPropertyOf` to align core metadata—quantity kinds, values, units, time, uncertainty, etc.—between the SOIL and D-SI ontologies, enabling FAIR (Findable, Accessible, Interoperable, Reusable) measurement data interoperability.

### Usage ⚙️

Import in Turtle:

```ttl
@prefix bridge: <https://w3id.org/soil-dsi-bridge#> .
@base  <https://w3id.org/soil-dsi-bridge#> .

<https://w3id.org/soil-dsi-bridge>
    a owl:Ontology .
```

Or reference in OWL/XML:

```xml
<owl:Ontology rdf:about="https://w3id.org/soil-dsi-bridge"/>
```

**Download**

* [`soil-dsi-bridge.ttl`](soil-dsi-bridge.ttl)

### Authors 🎓

* **Z. D.** (ORCID: [0009-0004-9085-4516](https://orcid.org/0009-0004-9085-4516))
* **K. W.**

### Citation 📖

```
Z. D. (2025). Bridge Ontology: SOIL ↔ D-SI. Version 1.0. CC BY 4.0. Available at https://w3id.org/soil-dsi-bridge
```

---

## Deutsch

### Projektübersicht 🚀

* **Name**: Brückenontologie: SOIL ↔ D-SI(DCC)
* **Persistent ID**: [https://w3id.org/soil-dsi-bridge](https://w3id.org/soil-dsi-bridge)
* **Version**: 1.0
* **Lizenz**: CC BY 4.0 ([Lizenzdetails](https://creativecommons.org/licenses/by/4.0/))
* **Autoren**: Z. D. (ORCID: [0009-0004-9085-4516](https://orcid.org/0009-0004-9085-4516)), K. W.
* **Erstellungsdatum**: 2025-05-20

Diese Brückenontologie verwendet Mappings wie `owl:equivalentClass`, `owl:equivalentProperty` und `rdfs:subPropertyOf`, um zentrale Metadaten—Mengenarten, Werte, Einheiten, Zeit, Unsicherheit etc.—zwischen den SOIL- und D-SI-Ontologien auszurichten und so die FAIRen (Findable, Accessible, Interoperable, Reusable) Messdaten-Interoperabilität zu gewährleisten.

### Verwendung ⚙️

Import als Turtle:

```ttl
@prefix bridge: <https://w3id.org/soil-dsi-bridge#> .
@base  <https://w3id.org/soil-dsi-bridge#> .

<https://w3id.org/soil-dsi-bridge>
    a owl:Ontology .
```

Oder in OWL/XML referenzieren:

```xml
<owl:Ontology rdf:about="https://w3id.org/soil-dsi-bridge"/>
```

**Download der Ontologie**

* [`soil-dsi-bridge.ttl`](soil-dsi-bridge.ttl)

### Autoren 🎓

* **Z. D.** (ORCID: [0009-0004-9085-4516](https://orcid.org/0009-0004-9085-4516))
* **K. W.**

### Zitationsweise 📖

```
Z. D. (2025). Brückenontologie: SOIL ↔ D-SI. Version 1.0. CC BY 4.0. Verfügbar unter https://w3id.org/soil-dsi-bridge
```

---

感谢关注与使用！
Thank you for your interest and use!
Vielen Dank für Ihr Interesse und Ihre Nutzung!

如有建议或问题，欢迎提交 [Issue](https://github.com/GuaPi-D/soil-dsi-bridge/issues)。
If you have suggestions or questions, please open an [Issue](https://github.com/GuaPi-D/soil-dsi-bridge/issues).
Bei Anregungen oder Fragen eröffnen Sie bitte ein [Issue](https://github.com/GuaPi-D/soil-dsi-bridge/issues).
