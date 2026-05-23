# 工程本体论 — Engineering Ontology: Principles and Practice

## 关于本书 / About This Book

**《工程本体论》** 是一本系统讲述如何将本体论（Ontology）理论应用于工程领域的教材。
本书涵盖从本体论基础理论、OWL/RDF描述语言、SPARQL查询、推理机制，到完整的智能制造系统实战案例。

**"Engineering Ontology"** is a Chinese textbook on applying ontology theory to engineering domains.
It covers foundational ontology theory, OWL/RDF description languages, SPARQL querying,
reasoning mechanisms, and a full capstone case study on intelligent manufacturing knowledge management.

## 仓库结构 / Repository Structure

```
ontology-engineering-book/
├── ch01-ontology-foundations/     # 第1章：本体论基础理论
│   └── examples/
├── ch03-ontology-languages/       # 第3章：本体描述语言与工具
│   └── examples/
├── ch04-reasoning/                # 第4章：知识表示与推理机制
│   └── examples/
├── ch05-applications/             # 第5章：工程领域应用案例
│   └── examples/
└── ch08-capstone-manufacturing/   # 第8章：综合实战案例：智能制造知识管理系统
    └── src/
```

## 代码说明 / Code Overview

| 章节 | 内容 | 主要技术 |
|------|------|----------|
| Ch01 | 本体论基础理论 | 描述逻辑、SWRL规则、公理定义 |
| Ch03 | 本体描述语言与工具 | RDF/Turtle、OWL、SPARQL、Protégé |
| Ch04 | 知识表示与推理机制 | Tableau算法、SWRL、时态推理、概率推理 |
| Ch05 | 工程领域应用案例 | 自动驾驶、BIM、航空航天FMEA |
| Ch08 | 综合实战案例 | Java/Jena、Python/owlready2、OWL Manchester语法 |

## 如何使用 / How to Use

### 运行Java代码 (Ch08)
需要 Apache Jena 依赖：
```xml
<dependency>
  <groupId>org.apache.jena</groupId>
  <artifactId>apache-jena-libs</artifactId>
  <version>4.10.0</version>
</dependency>
```

### 运行Python代码 (Ch08)
```bash
pip install owlready2
python src/reasoner.py
```

### 查看OWL文件
推荐使用 [Protégé](https://protege.stanford.edu/) 打开 `.owl` 文件。

## 许可 / License

本仓库代码示例仅供学习参考，版权归原书作者所有。
Code examples in this repository are for educational purposes only.

---
*Generated from 《工程本体论》书稿一审0513 正.docx*
