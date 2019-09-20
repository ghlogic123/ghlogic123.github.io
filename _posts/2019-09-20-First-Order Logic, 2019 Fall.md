---
title: 'First-Order Logic, 2019 Fall'
layout: post
categories: 'Notes,Logic'
tags: FOL
---
# First-Order Logic, 2019 Fall

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=3 orderedList=false} -->

<!-- code_chunk_output -->

- [First-Order Logic, 2019 Fall](#first-order-logic-2019-fall)
  - [Week 1-2](#week-1-2)

<!-- /code_chunk_output -->

## Week 1-2

* Formal Language
* Meta & Obeject Language
* Truth Value
* Semantics of Propositional Logic

---

> Lewis实质蕴涵，与自然语言中“如果...那么”的区别

**Semantics:**

* 赋值：$V(p)=1$
* 赋值满足：$V\vDash \phi$
* 语义后承：$\Sigma \Vdash \phi$ 

> **Theorem 1**  对任意公式$\phi$: $\varnothing\Vdash\phi$ iff $\phi$是有效的。

> **Theorem 2** $\{\sigma_1,\cdots,\sigma_{n}\}\Vdash \phi$ iff $(\sigma_1\rightarrow(\sigma_2\rightarrow \cdots \rightarrow (\sigma_{n}\rightarrow \phi)\cdots))$是有效的。 


> Formal Proof
*-------------------------*
Math Proof &emsp; &emsp; Math Objects