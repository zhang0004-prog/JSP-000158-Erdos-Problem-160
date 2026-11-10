# Erdős Problem #160 — Research Progress Announcement

## Erdős 问题 #160——研究进展正式公告

**Researcher / 研究者：** Hongzhao Zhang（张洪诏）  
**Affiliation / 团队：** DAZHuzhang. Art Team（大主张.艺术团队）  
**Project ID / 项目编号：** JSP-000158  
**Announcement Date / 发布日期：** November 10, 2026  
**Research Status / 研究状态：** OPEN / UNRESOLVED

---

# PART I. 中文正式公告

## 关于 Erdős Problem #160 的阶段性研究成果公告

本人张洪诏，现正式公布关于 Erdős Problem #160（JSP-000158）的阶段性研究成果。

本研究围绕一个核心组合数论问题展开：对于正整数集合 $[N]=\{1,2,\ldots,N\}$，寻找最少的颜色数，使得每一个非平凡四项等差数列都至少包含三种不同的颜色。

问题可表示为：

$$
h(N)=\min\left\{k:
\forall (a,a+d,a+2d,a+3d)\subseteq[N],\ d\ne0,\quad
\left|\{f(a),f(a+d),f(a+2d),f(a+3d)\}\right|\ge3
\right\}.
$$

本项目致力于研究这一问题的有限结构、渐近性质、组合约束和潜在证明方法。

经过持续研究，目前已经形成有限计算、组合结构、傅里叶分析、凸几何、Behrend 型构造及跨颜色联合约束等多个研究模块。

## 一、有限规模染色计算成果

本研究完成了多个有限规模的精确染色分析。

### 1. 三色染色研究

- $N=12$：存在 6 个有效三色染色。
- $N=13$：不存在有效三色染色。
- 对应的四项等差数列约束数量分别为 18 和 22。

由此得到：

$$h(N)\ge4,\qquad N\ge13.$$

### 2. 四色染色研究

在四色染色研究中：

- $N=22$：发现 144 个有效四色染色。
- 这些染色对应 6 个规范化代表。
- 每个有效染色均使用全部 4 种颜色。
- $N=23$：不存在有效四色染色。

通过独立搜索方法及规范化计数交叉核验，得到：

$$h(N)=4,\qquad 13\le N\le22,$$

以及：

$$h(N)\ge5,\qquad N\ge23.$$

以上是本项目目前最明确的有限规模数学成果。

## 二、四色染色的结构与对称性研究

项目进一步研究了有限四色解的对称结构。

主要内容包括：

- 颜色置换对称性；
- 位置反转对称性；
- 规范化代表；
- 短周期结构；
- 染色从 $N=21$ 向 $N=22$ 的扩张障碍。

研究记录显示：

- 对应的对称群大小为 48；
- $N=21$ 有 4,272 个有效染色；
- 规范化后有 178 个代表；
- 严格 7 周期代表有 14 个，但均不能扩张到 $N=22$；
- 178 个代表中只有 5 个能够扩张到 $N=22$。

这些结果揭示了有限四色解中存在的非平凡结构限制。

## 三、组合匹配与 C4 证明研究

本项目建立了基于违规四项等差数列窗口的组合匹配框架。

已经完成的局部成果包括：

- 45 个违规窗口的结构记录；
- 最大不相交窗口族大小为 5；
- 建立了 248,832 个 EXACT5 候选组合的分析空间；
- 对 36 个骨架进行了进一步分析；
- 已排除其中 12 个零覆盖骨架。

当前仍有 23 个骨架需要进一步审计。

因此，该路线已经建立了明确的组合证明框架，但更强下界尚未完成无条件证明。

## 四、傅里叶分析与频率结构

研究建立了全局频率划分、核函数协调及颜色指标对齐等分析模块。

已经记录的局部成果包括：

- 全局频率划分核对；
- 全局核函数协调；
- 零频率严格正性；
- 非零频率约束；
- H0 几何适用范围审计。

相关结果按照证明范围分别记录为已验证、条件验证或开放状态。

这一方向的核心目标，是将频率信息转化为能够约束全部颜色类的全局不等式。

## 五、Behrend 倾斜分割与凸几何

项目建立了 Behrend 型结构与高维凸几何之间的研究路线。

研究核心对象为：

$$
K_c=\operatorname{conv}\left\{(a_1^2,\ldots,a_6^2):
 a\in\{0,\ldots,m-1\}^6,\ c\cdot a=0\right\}.
$$

目前已经完成一个重要的局部分支：

$$c_{vv}=(2,-3,1,-2,3,-1),$$

其中：

$$m=4,\qquad s=\frac94.$$

该分支已归档双单纯形分离证书，并记录：

$$\frac94\mathbf1_6\in\operatorname{int}(K_{vv}).$$

研究下一步将继续处理 $c_{uv}$、$c_{uu}$ 和 $c_{vv}$ 三个分支之间的统一关系。

## 六、跨颜色联合约束：核心理论方向

在对傅里叶分析、$U^3$ 结构、能量守恒及 Behrend 型构造进行综合研究后，本项目逐步明确了一个共同的理论瓶颈：

> 现有局部方法尚未提供足够强的跨颜色联合约束。

单色稳定性、双颜色关系、局部频率消失以及能量守恒，均不足以自动推出原问题所需的全局渐近下界。

因此，研究目前将重点集中在：

$$\mathcal J(A_1,A_2,\ldots,A_k)\ge\Phi(N,k)$$

这一类跨颜色联合不等式的寻找和证明。

这是当前研究最重要的理论目标，而不是已经完成的定理。

## 七、文献与证明审计

研究还建立了独立的文献审计和证明证据管理体系。

主要涉及：

- Deng–Tidor–Zhao 的对称 4-AP 染色理论；
- Ruzsa 1993 年相关定理及原文证明省略问题；
- Raghavan 的 3-AP 自由集上界；
- Shi–Dong 的 4-AP 染色上界。

本研究特别区分原问题与对称 ABBA 染色问题，避免将不同数学对象混为一谈。

所有研究结论均尽量区分原始来源、独立推导、计算验证、条件性结论及尚未解决的问题。

## 八、当前研究状态

截至 2026 年 11 月 10 日：

- 有限三色及四色研究已经取得明确成果；
- 四色结构和周期性研究已经形成系统记录；
- C4 组合证明仍有开放骨架；
- 傅里叶及频率分析已经建立多个局部结果；
- Behrend 倾斜分割已经形成局部凸几何证书；
- 跨颜色联合约束仍然是核心理论障碍。

必须明确：**Erdős Problem #160 目前仍然是 OPEN / UNRESOLVED。**

本公告公布的是阶段性研究成果，不宣称已经完成该问题的完整证明。

## 九、未来研究方向

下一阶段主要集中于：

1. 建立跨颜色联合约束不等式；
2. 完成 Behrend 倾斜分割的三个主要分支；
3. 继续审计 C4 剩余组合骨架；
4. 完善傅里叶频率结构与全局颜色约束之间的联系；
5. 建立可复现、可审计的国际研究档案。

### 结语

数学研究不仅在于寻找最终答案，也在于逐步识别问题的真实结构、建立可靠的证明工具，并明确现有理论尚未跨越的障碍。

本项目将继续坚持严格的数学定义、可复核的计算记录、透明的证明状态及开放的学术审计原则。

希望通过公开研究资料，与全球组合数学、解析数论及加法组合学研究者交流，寻找解决 Erdős Problem #160 的新方法。

Hongzhao Zhang（张洪诏）  
DAZHuzhang. Art Team（大主张.艺术团队）

---

# PART II. ENGLISH OFFICIAL ANNOUNCEMENT

## Research Progress Announcement on Erdős Problem #160

I, Hongzhao Zhang, hereby announce the current research progress on Erdős Problem #160 (JSP-000158).

The project investigates a fundamental problem in additive and combinatorial number theory: determining the minimum number of colors required to color $[N]=\{1,2,\ldots,N\}$ so that every nontrivial four-term arithmetic progression contains at least three distinct colors.

Formally, define

$$
h(N)=\min\left\{k:
\forall (a,a+d,a+2d,a+3d)\subseteq[N],\ d\ne0,\quad
\left|\{f(a),f(a+d),f(a+2d),f(a+3d)\}\right|\ge3
\right\}.
$$

The research focuses on finite coloring structures, asymptotic behavior, combinatorial constraints, and potential proof strategies.

The project has developed several interconnected research components, including finite computation, combinatorial structure, Fourier analysis, convex geometry, Behrend-type constructions, and cross-color joint constraints.

## 1. Finite Coloring Results

The project has completed several exact finite-scale coloring investigations.

### Three-color results

- $N=12$: exactly 6 valid three-colorings.
- $N=13$: no valid three-coloring.
- The corresponding numbers of four-term arithmetic progression constraints are 18 and 22.

Consequently,

$$h(N)\ge4,\qquad N\ge13.$$

### Four-color results

- $N=22$: exactly 144 valid four-colorings.
- These correspond to 6 canonical representatives.
- Every valid coloring uses all four colors.
- $N=23$: no valid four-coloring exists.

Independent search procedures and canonical counting were used for cross-verification.

These results establish:

$$h(N)=4,\qquad 13\le N\le22,$$

and

$$h(N)\ge5,\qquad N\ge23.$$

These are among the project’s clearest finite mathematical achievements.

## 2. Structural Analysis of Four-Colorings

The project has also investigated the symmetry and structural properties of finite four-colorings.

The work includes:

- Color-permutation symmetry;
- Position reversal symmetry;
- Canonical representatives;
- Short-period structures;
- Extension obstructions from $N=21$ to $N=22$.

The recorded results include:

- A symmetry group of order 48;
- 4,272 valid colorings at $N=21$;
- 178 canonical representatives;
- 14 strictly 7-periodic representatives, none of which extends to $N=22$;
- Only 5 of the 178 representatives extend to $N=22$.

These observations reveal substantial structural restrictions on finite four-color solutions.

## 3. Combinatorial Matching and the C4 Proof Program

A combinatorial framework based on matching families of violating arithmetic-progression windows has been developed.

Recorded progress includes:

- 45 violating windows;
- A maximum pairwise-disjoint family of size 5;
- An EXACT5 candidate space of 248,832 combinations;
- Further analysis of 36 structural skeletons;
- Exclusion of 12 zero-cover skeletons.

Twenty-three skeletons remain open for further examination.

Thus, this approach has produced a concrete combinatorial proof framework, but a stronger lower bound has not yet been established unconditionally through this route.

## 4. Fourier Analysis and Frequency Structure

The project has developed analytical components involving global frequency partitioning, kernel reconciliation, and color-index alignment.

Recorded local results include:

- Global frequency partition reconciliation;
- Global kernel reconciliation;
- Strict positivity at zero frequency;
- Nonzero-frequency constraints;
- An audit of the geometric scope of H0.

The results are separately classified as verified, conditionally verified, or open, according to their actual proof scope.

The main objective is to convert frequency information into global inequalities capable of controlling all color classes simultaneously.

## 5. Behrend-Type Tilted Partitions and Convex Geometry

A research program connecting Behrend-type constructions with high-dimensional convex geometry has been developed.

The central object is

$$
K_c=\operatorname{conv}\left\{(a_1^2,\ldots,a_6^2):
 a\in\{0,\ldots,m-1\}^6,\ c\cdot a=0\right\}.
$$

One important branch has been archived with a dual-simplex separation certificate.

For

$$c_{vv}=(2,-3,1,-2,3,-1),$$

with

$$m=4,\qquad s=\frac94,$$

the recorded result is

$$\frac94\mathbf1_6\in\operatorname{int}(K_{vv}).$$

Further work is directed toward establishing the corresponding relationships among the three branches $c_{uv}$, $c_{uu}$, and $c_{vv}$.

## 6. Cross-Color Joint Constraints: The Central Theoretical Direction

A synthesis of the Fourier, $U^3$, energy-conservation, and Behrend-type approaches has identified a common theoretical bottleneck:

> Existing local methods do not yet provide a sufficiently strong joint constraint across all color classes.

Single-color stability, pairwise color relations, local frequency vanishing, and energy identities do not automatically yield the global asymptotic lower bound required by the original problem.

The central research objective is therefore to establish inequalities of the general form

$$\mathcal J(A_1,A_2,\ldots,A_k)\ge\Phi(N,k),$$

where the functional $\mathcal J$ genuinely couples all color classes.

This is an open research objective, not an established theorem.

## 7. Literature and Proof Auditing

The project has also developed a source-first literature and proof-auditing framework.

The principal references include:

- Deng–Tidor–Zhao on symmetric four-term arithmetic progression colorings;
- Ruzsa (1993) and the omitted proof in the relevant theorem;
- Raghavan on bounds for progression-free sets;
- Shi–Dong on improved upper bounds for four-term progression colorings.

Particular attention is paid to distinguishing the original Erdős problem from the narrower symmetric ABBA-coloring problem.

The research records distinguish original sources, independent deductions, computational verification, conditional conclusions, and unresolved gaps.

## 8. Current Research Status

As of November 10, 2026:

- Finite three-color and four-color investigations have produced explicit results.
- Four-color structural and periodicity analyses have been recorded.
- The C4 combinatorial proof program still contains open skeletons.
- Fourier and frequency analysis have established several local results.
- The Behrend-type tilted partition program has produced a local convex-geometric certificate.
- Cross-color joint constraints remain the principal theoretical obstacle.

**Erdős Problem #160 remains OPEN / UNRESOLVED.**

This announcement presents research progress and does not claim a complete solution of the original problem.

## 9. Future Research Directions

The next stage will focus on:

1. Establishing a cross-color joint inequality;
2. Completing the three principal branches of the Behrend-type tilted partition program;
3. Auditing the remaining C4 combinatorial skeletons;
4. Connecting Fourier frequency structure with global color constraints;
5. Developing a reproducible and auditable international research archive.

### Closing Statement

Mathematical research is not only about obtaining a final answer. It is also about identifying the underlying structure of a problem, developing reliable proof techniques, and clearly understanding the obstacles that remain.

This project will continue to follow rigorous mathematical definitions, reproducible computational records, transparent proof-status classifications, and open scholarly scrutiny.

Researchers in combinatorics, analytic number theory, and additive combinatorics are warmly invited to examine the research materials, provide feedback, and explore new approaches to Erdős Problem #160.

Hongzhao Zhang  
DAZHuzhang. Art Team

---

**Project:** Erdős Problem #160  
**Project Identifier:** JSP-000158  
**Status:** OPEN / UNRESOLVED  
**Date:** November 10, 2026
