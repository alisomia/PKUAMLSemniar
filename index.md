# PKU Applied Math Lunch Seminar

## 应用数学青年讨论班（午餐会）日程表

本学期（2024秋）应用数学拔尖计划将开展午餐会，本学期由**吴清玉**和**沈城烽**同学负责。
往期日程可以参考：[2024年春](2024Spring.html) [2023年秋](2023Fall.html)

本学期日程如下：

1. Sep 11

    **王泽昊**, UCSD，博士生

    题目：声音合成与处理中的高效计算：问题、技术及其在当代音乐与声音艺术中的应用

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:

    随着电子和数字技术的兴起，音乐和声音艺术经历了巨大的变革。与传统的大规模计算挑战不同，计算在音乐和声音艺术中的应用面临着独特的限制，例如对实时性和交互性的需求、在低功耗微控制器上实现的必要性，以及在精确性与听觉感知之间的微妙平衡。在此次演讲中，我将重点探讨当代音乐和声音艺术中的声音合成与处理的高效计算。我将首先介绍计算在这些艺术领域中的应用，特别是在声音合成与处理方面。随后，我将讨论各种算法及其在不同硬件平台上的实现，结合我在物理建模声音合成和乐器设计方面的研究与实践。最后，我将分享我对这些较为成熟的技术在音乐和声音艺术实践中潜在应用的看法。
    </p>
    <p>
    <b>报告人信息</b>:

    王泽昊是一名计算机音乐研究者和实践者，常驻于圣地亚哥和上海。他目前是加州大学圣地亚哥分校（UCSD）音乐系的计算机音乐博士候选人，导师为Tom Erbe教授和Miller Puckette教授，同时也在上海纽约大学（NYU Shanghai）担任Alex Ruthmann教授的访问研究员。此前，他在北京大学数学科学学院获得了学士学位。他的研究涵盖了音乐声学、声音合成和乐器设计，并与斯坦福大学CCRMA、爱丁堡大学和纽约大学等知名机构的艺术家和研究人员紧密合作。他的研究曾在包括斯坦福大学CCRMA、罗切斯特大学以及斯德哥尔摩皇家音乐学院在内的多个国际场合进行展示。王泽昊也是一位活跃的作曲家和声音设计师，特别专注于戏剧艺术领域。他为戏剧艺术创作的作曲与声音设计曾在北京和纽约市上演。
    </p>
    
    </details>

1. ~~Sep 18~~
1. Sep 25

    **陈畅**, 北京大学，博士生
    
    题目：Centauri: Enabling Efficient Scheduling for Communication-Computation Overlap in Large Model Training via Communication Partitioning

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    Efficiently training large language models (LLMs) necessitates the adoption of hybrid parallel methods, integrating multiple communications collectives within distributed partitioned graphs. Overcoming communication bottlenecks is crucial and is often achieved through communication and computation overlaps. However, existing overlap methodologies tend to lean towards either fine-grained kernel fusion or limited operation scheduling, constraining performance optimization in heterogeneous training environments.
    In this talk, we introduce Centauri, an innovative framework that encompasses comprehensive communication partitioning and hierarchical scheduling schemes for optimized overlap. We propose a partition space comprising three inherent abstraction dimensions: primitive substitution, topology-aware group partitioning, and workload partitioning. To determine the efficient overlap of communication and computation operators, we decompose the scheduling tasks in hybrid parallel training into three hierarchical tiers: operation, layer, and model. Through these techniques, our framework Centauri effectively overlaps communication latency and enhances hardware utilization.
    </p>
    <p>
    <b>报告人信息</b>:

    陈畅是北京大学前沿交叉学科研究院的博士研究生，导师为杨超。她的研究方向为高性能与分布式计算，大规模机器学习系统和分布式系统。她在本次报告的工作获得了ASPLOS 2024 Best Paper award。

    </p>
    </details>


1. ~~Oct 2~~ (假期)
1. Oct 9

    **张东航**，中国科学院数学与系统科学研究院，博士后

    题目：p-Multigrid method for elliptic problem

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    In this talk, we propose the two-level and W-cycle algorithms of p-multigrid method designed to solve the linear systems of equations generated from p-version symmetric interior penalty discontinuous Galerkin (SIPDG) discretizations for elliptic problems. This SIPDG discretization employs hierarchical Legendre polynomial basis functions, where we can design restriction and prolongation operators between different discrete polynomial spaces naturally. Inspired by the uniform convergence theory of the W-cycle algorithm of hp-multigrid method in [P. F. Antonietti, et.al., SIAM J. Numer. Anal., 53 (2015)], we extend their work by providing a more refined matrix-based analysis. Specifically, we estimate the spectral radius of the stiffness matrix and its diagonal matrix, assess the approximation property of coarsest level correction, and analyze the smoothing properties of polynomial smoother based on fourth-kind Chebyshev polynomial iterative method. Building on these foundations, we provide a rigorous matrix-based convergence analysis for the proposed p-multigrid method, considering both inherited and non-inherited bilinear forms of SIPDG discretization. Our theoretical results show significant improvement over [P. F. Antonietti, et.al., SIAM J. Numer. Anal., 53 (2015)], reducing the required number of smoothing steps from O(p^2) to O(p), where p is the polynomial degree of the discrete broken polynomial space. Moreover, the convergence rate remains independent of the mesh size. Finally, several numerical experiments are presented to validate our theoretical findings.
    </p>
    <p>
    <b>报告人信息</b>:

    张东航，2015-2020 中国科学院数学与系统科学院，计算数学博士；2020-2023北京大学北京国际数学研究中心，博士后; 2023年至今，中国科学院数学与系统科学研究院基础软件研究中心。

    </p>
    </details>
1. Oct 16

   **王修远**，北京大学，博士生

   题目：Multi-scale Self-similar Finite-time Blowups of Some 1D Models for the 3D Incompressible Euler Equations

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    The fundamental problem on the global regularity of the 3D Euler and Navier-Stokes equations with smooth initial data remains one of the most challenging open problems in fluid dynamics. To investigate the competition between advection and vortex stretching in the 3D Euler equations, several one-dimensional models have been proposed, including the generalized Constantin–Lax–Majda model and the one-dimensional Hou-Luo model. In this talk, we will present our recent results on self-similar finite-time blowup solutions for these models. We establish the existence of exact self-similar finite-time blowups using a novel fixed-point method and present new findings regarding the existence of singular blowup profiles. Additionally, we will introduce a novel class of asymptotically self-similar blowup that has multi-scale features, revealing a potential new mechanism for blowup in the 3D Euler equations.
    </p>
    <p>
    <b>报告人信息</b>:

    王修远是北京大学数学科学学院的计算数学博士生，导师为黄得老师，研究方向是流体力学方程的爆破解存在性问题。本次报告的部分工作发表于期刊Archive for Rational Mechanics and Analysis。

    </p>
    </details>
1. Oct 23

   **李世凤**，武汉大学，博士后

   题目：Numerical Methods and Analysis of Computing Quasiperiodic Systems

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    Quasiperiodic systems are important space-filling ordered structures, without decay and translational invariance. How to solve quasiperiodic systems accurately and efficiently is of great challenge. A useful approach, the projection method (PM) [J. Comput. Phys. , 256: 428, 2014], has been proposed to compute quasiperiodic systems. However, there is a lack of theoretical analysis of PM. In this report, we present a rigorous convergence analysis of the PM by establishing a mathematical framework of quasiperiodic functions and their high-dimensional periodic functions. We also give a theoretical analysis of the quasiperiodic spectral method (QSM) based on this framework. Moreover, we investigate the accuracy and efficiency of PM, QSM and periodic approximation method in solving the linear time-dependent quasiperiodic Schrödinger equation.
    </p>
    <p>
    <b>报告人信息</b>:

    李世凤，武汉大学博士后，主要从事准周期系统的计算方法及理论分析的研究。目前，在SINUM、Automatica、J Sci. Conput.等国内外知名期刊接受并发表了多篇论文。

    </p>
    </details>
1. Oct 30

   **谢中林**，北京大学，博士生

   题目：ODE-based Learning to Optimize

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    Recent years have seen a growing interest in understanding acceleration methods through the lens of ordinary differential equations (ODEs). Despite the theoretical advancements, translating the rapid convergence observed in continuous-time models to discrete-time iterative methods poses significant challenges. In this talk, we present a comprehensive framework integrating the inertial systems with Hessian-driven damping (ISHD) and learning-based approaches for developing optimization methods. We first establish the convergence condition for ensuring the convergence of the solution trajectory of ISHD. Then, we show that provided the stability condition, the sequence generated through the explicit Euler discretization of ISHD converges, which gives a large family of practical optimization methods. In order to select the best optimization method in this family, we introduce the stopping time, the time required for an optimization method derived from ISHD to achieve a predefined level of suboptimality. Then, we formulate a novel learning to optimize (L2O) problem aimed at minimizing the stopping time subject to the convergence and stability condition. Empirical validation of our framework is conducted through extensive numerical experiments. These experiments showcase the superior performance of the learned optimization methods.
    </p>
    <p>
    <b>报告人信息</b>:

    谢中林，北京大学数学科学学院博士生，导师为文再文教授。他于2021年在北京大学获得学士学位。他的研究兴趣集中在深度学习和优化领域，包括加速算法、学习优化和基于微分方程设计优化算法。

    </p>
    </details>
1. ~~Nov 6~~
1. Nov 13

   **张振毅**， 北京大学

   题目：Learning stochastic dynamics from snapshots through regularized unbalanced optimal transport

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    从时间稀疏的快照分布中重建样本动力学是自然科学和机器学习中的一个重要问题，在生成模型，细胞轨迹推断中都有广泛应用。在这个报告中，我将介绍一种我们发展的从高维快照分布的样本中学习正则不平衡最优传输（Regularized Unbalanced Optimal Transport，RUOT）的深度学习方法，并推断样本的连续不平衡随机动力学。基于RUOT的框架，我们的方法实现了对动力学的建模，而无需对非平衡等信息的先验，允许这些直接从数据中学习。在理论方面，我们探索了RUOT和Schrödinger Bridge问题的联系，讨论了其中的关键挑战和潜在解决方案。我们综合了基因调控网络，高维混合高斯模型与血液中的scRNA-seq数据，验证了我们方法的有效性。与其他方法相比，我们的方法准确重建了样本的生长和运输的动力学，消除了错误的迁移，并构建了Waddington的发育能量景观。
    </p>
    <p>
    <b>报告人信息</b>:

    张振毅，北京大学数学科学学院博士生，导师为李铁军教授。研究兴趣为科学人工智能，数据驱动的动力学模型与计算方法。
   
    </p>
    </details>
1. Nov 20

   **张悦嘉**，复旦大学，博士生

   题目：Parallel Coordinate Descent Methods for Full Configuration Interaction

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    Solving the time-independent Schrödinger equation gives us full access to the chemical properties of molecules. Among all the ab-initio methods, full configuration interaction (FCI) provides the numerically exact solution under a predefined basis set. However, the FCI problem scales exponentially with respect to the number of bases and electrons and suffers from the curse of dimensionality. We develop a mutli-threaded parallel coordinate descent full configuration interaction algorithm, for the electronic structure ground-state calculation in the configuration interaction framework. The algorithm solves an unconstrained nonconvex optimization problem, via a modified block coordinate descent method with a deterministic compression strategy. CDFCI captures and updates appreciative determinants with different frequencies proportional to their importance. We demonstrate the efficiency of the algorithm on practical systems.
    </p>
    <p>
    <b>报告人信息</b>:

    张悦嘉，复旦大学数学科学学院博士生，导师是高卫国教授，第二导师是李颖洲青年研究员，专业是计算数学，主要研究方向是计算化学里的数值代数问题及高性能实现。
   
    </p>
    </details>
1. Nov 27

    **朱岳宸**， 北京大学

   题目：图形学中保结构的流体求解：对偶矢量、流映射与余伴随轨道

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    基于物理的计算是计算机图形学中的重要研究方向， 其在虚拟场景中模拟各类物体的形变和运动，解算多物理场的变化和耦合。图形学中的仿真相较于传统的物理模拟强调在较低的计算开销中尽可能做到实时模拟，并保持视觉上的真实性和结果的稳定性。近些年来，对 Navier–Stokes 中数学结构的分析为图形学中的算法设计提供了更多长时间演化稳定性的保证。在此次报告中，我将首先回顾几何流体动力学中对流体的描述。此后，我将讨论不同的视角所带来的仿真算法改进，与对应数值上更优的稳定性和视觉上更丰富的湍流效果。

    </p>
    <p>
    <b>报告人信息</b>:

    朱岳宸，本科毕业于北京大学计算机科学与技术方向，研究兴趣主要在物理模拟、离散微分几何和计算机图形学。目前在跟随陈宝权教授做研究助理。
   
    </p>
    </details>
1. Dec 4
1. Dec 11

    **李梦雨**， 中国人民大学

    TBA
1. Dec 18

   **程靖普**，National University of Singapore
1. Dec 25

    **刘茵**， BICMR

    TBA
1. Jan 1
1. Jan 8






-----
This webpage is maintained by Ting Lin (@alisomia)
