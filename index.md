# PKU Applied Math Lunch Seminar

## 应用数学青年讨论班（午餐会）日程表

本学期（2025春）应用数学拔尖计划将开展午餐会，本学期由**武朔南**和**赵振华**同学负责。
往期日程可以参考：[2024年秋](2024Fall.html) [2024年春](2024Spring.html) [2023年秋](2023Fall.html) 

本学期日程如下：

1. Mar 12

   **赵悦**，北京大学，博士生

   题目：Deep Learning Methods for Solving High-dimensional PDEs: EPR-Net and Deep Picard Iteration
   <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>: In this talk, we explore two deep learning methods for solving high-dimensional PDEs. First, we introduce EPR-Net, a novel deep learning approach for constructing potential landscapes of high-dimensional non-equilibrium steady-state (NESS) systems. The coincidence between the minimum loss of EPR-Net and the entropy production rate in NESS theory allows simultaneous potential landscape construction and clear physical interpretation. EPR-Net can be combined with dimensionality reduction and extended to systems with state-dependent diffusion coefficients. Next, we propose Deep Picard Iteration (DPI) for solving high-dimensional nonlinear parabolic PDEs. DPI combines Picard iteration with neural networks, avoiding the computational difficulties of directly optimizing PDE objective functions. It uses the Feynman-Kac formula for function evaluation, the Bismut-Elworthy-Li formula for gradient estimation. Numerical experiments demonstrate DPI’s faster convergence, lower computational cost, and higher solution accuracy compared to existing methods.
    </p>
    <p>
    <b>报告人信息</b>: 赵悦，北京大学大数据科学中心博士生，主要研究方向为深度学习与科学计算。
    </p>
    </details>

1. Mar 19

    **何明东**, University of Oxford，博士生

    题目：Structure-preserving discretisation for the magneto-frictional equations in the Parker Conjecture

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:The Parker conjecture, which explores whether magnetic fields in perfectly conducting plasmas can develop tangential discontinuities during magnetic relaxation, remains an open question in astrophysics. Helicity conservation provides a topological barrier during relaxation, preventing topologically nontrivial initial data relaxing to trivial solutions; preserving this mechanism discretely over long time periods is therefore crucial for numerical simulation. This work presents an energy- and helicity-preserving finite element discretization for the magneto-frictional system, for investigating the Parker conjecture. The algorithm preserves a discrete version of the topological barrier and a discrete Arnold inequality. We also discuss extensions to domains with nontrivial topology. This is a joint work with Patrick E. Farrell (Oxford)，Kaibo Hu (Edinburgh) and Boris D. Andrews (Oxford).
    </p>
    <p>
    <b>报告人信息</b>: 何明东，英国牛津大学数学系数值分析组博士生，导师为 Prof. Patrick E. Farrell, 主要研究方向为偏微分方程数值解，目前工作在于多物理场尤其是磁流体方程组的有限元保结构离散，快速求解器以及相关应用。
    </p>
    
    </details>

1. Mar 26

    **李子牛**, 香港中文大学（深圳），博士生

    题目：Large Language Model Post-Training: Formulation and Algorithms

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:Post-training is essential for adapting Large Language Models (LLMs) to specialized downstream tasks. This process typically involves Supervised Fine-Tuning (SFT) for instruction following and Reinforcement Learning (RL) for capability enhancement—approaches central to flagship products like ChatGPT and DeepSeek-R1. In this talk, we present new mathematical formulations for both SFT and RL. We identify several key properties that distinguish LLM post-training from classical supervised learning and standard reinforcement learning frameworks. Based on these insights, we introduce two new training algorithms: GEM for SFT and ReMax for RL. Specifically, GEM preserves output diversity, enhancing exploration in subsequent RL stages, while ReMax significantly reduces the computation complexity and opens a new paradiagm of RL for LLMs. Both algorithms come with theoretical guarantees using tools from optimization theory. This talk is expected to benefit researchers and practitioners interested in LLM implementation and those exploring the theoretical foundations of LLMs.
    </p>
    <p>
    <b>报告人信息</b>: 李子牛，香港中文大学（深圳）数据科学学院博士生，师从罗智泉（Tom Luo）教授。研究主要集中在机器学习算法设计与理论分析，特别关注大语言模型与强化学习应用。研究成果曾获得NeurIPS 2024 FITML Workshop最佳论文亚军、NeurIPS 2023 Spotlight以及UAI 2023 Oral演讲等荣誉。
    </p>
    
    </details>

1. Apr 2

    **李柄辉**， 北京大学， 博士生

    题目：Theoretical Understanding of Adversarial Examples: Expressive Power and Training Dynamics

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:In recent years, machine learning methods—especially deep learning—have shown exceptional performance in domains like computer vision, natural language processing, speech recognition, and game playing. However, deep neural networks still face fundamental limitations in robustness and reliability. A key issue is their vulnerability to adversarial examples—small perturbations that cause incorrect predictions while being imperceptible to humans. This poses significant concerns for deploying deep models in safety-critical applications, such as autonomous driving. In this talk, we aim to provide a theoretical account of adversarial examples in deep learning. Our analysis is grounded in two key perspectives: the expressive power of neural networks and the underlying principles of feature learning. By connecting these theoretical foundations, we seek to shed light on the mechanisms that give rise to adversarial vulnerability and offer insights into potential pathways for improving model robustness.
    </p>
    <p>
    <b>报告人信息</b>: 李柄辉，北京大学前沿交叉学科研究院国际机器学习研究中心2023级博士生，主要研究方向为深度学习的理论基础以及人工智能方法在数学问题中的应用。</p>
    
    </details>

1. Apr 23

    **吴天昊**，清华大学，博士生

    题目：Capacity-Constrained Optimal Transport: Models and Algorithms

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:In this talk, we explore algorithms for a variant of optimal transport called capacity-constrained optimal transport, which adds extra constraints on the set of feasible couplings to limit the mass transported between each pair of source and sink. Due to the large number of constraints in this problem, existing algorithms are both time-consuming and space-consuming. We consider a regularized problem that naturally satisfies the capacity constraints and consequently propose an alternating algorithm called the double regularization method. In our method, each alternate iteration step is to solve several single-variable equations. Theoretical analysis further provides a convergence guarantee to our method. Building on this, we introduce the sampled double regularization method based on importance sampling. In this approach, we approximate each single-variable equation by sampling a subset of its terms according to a designed sampling distribution. Theoretical analysis establishes the unbiasedness of this estimator and provides a bound on the approximation error.
    </p>
    <p>
    <b>报告人信息</b>: 吴天昊，清华大学数学科学系博士生，主要研究方向为最优输运及其应用，特别是在图问题与图算法中的应用。</p>
    
    </details>

1. May 14

    **陈日增**，北京大学，博士生

    题目：A Geometric Approach to Decision Problems over the Reals

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:Given a Boolean combination of polynomial equations and inequalities, and assuming further that all variables are quantified by "for all" or "exists", the decision problem over the reals is to decide whether this logic formula is true or not (e.g. every monic real cubic admits a real root). In this talk, we will introduce a new geometric decision algorithm for this problem. The new algorithm is based on rebuilding the foundations of cylindrical algebraic decomposition (the classical algorithm for the same problem) from a geometric aspect. Experimental results have shown that our algorithm outperforms the existing methods.
    </p>
    <p>
    <b>报告人信息</b>: 陈日增，北京大学数学科学学院应用数学专业2021级博士生，师从夏壁灿教授。研究方向涉及计算代数几何、实代数几何以及可计算性理论之间的领域交叉。曾获北京大学校长奖学金，华罗庚奖学金等荣誉。已有四篇文章被 Math. Comp., J. Symb. Comput., ISSAC 发表或接收。</p>
    
    </details>

1. May 21

    **刘水根**, National University of Singapore, 博士生

    题目：Localization Methods for High Dimensional Distribution Generation

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:In this talk, I will introduce a general strategy for sampling from high-dimensional distributions by exploiting conditional independence structure that arises from local interactions in many spatial and temporal systems. The structure induces a form of low-dimensionality that can be exploited algorithmically. I will introduce how to localize existing sampling methods, turning a high-dimensional problem into many low-dimensional subproblems. This localization not only reduces statistical complexity, but also enables efficient local and parallel computation. As examples, I will discuss MALA-within-Gibbs sampler and localized diffusion models. The localization method is grounded in a novel marginal Stein’s method, which provides quantitative estimates of the correlation decay in localized systems. This yields refined controls of the localization error, for instance, a dimension-free transport inequality for marginals. These results offer a unified perspective on how locality can be leveraged to make high-dimensional sampling both tractable and theoretically controlled.
    </p>
    <p>
    <b>报告人信息</b>: 刘水根，新加坡国立大学数学学院博士生，主要研究方向为不确定量化和高维采样，导师为童心教授和包维柱教授。</p>

1. May 28

    **朱旭**, 北京大学，博士生

    题目：Alternating Subspace Method for Efficient TDD Channel Reconstruction

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>: 移动通信技术中，信号的传输会受到多径传播的影响，因此需要额外加入导频信号辅助进行信道重构。为了不影响正常通讯，导频发送往往集中在较小的子带，因此需要额外的外推技术进行信道补全。近十年来，基于压缩感知的信道重构技术蓬勃发展，其中以基于 ADMM 的稀疏优化算法、基于近似消息传递 (AMP) 的统计计算方法以及基于 Turbo 译码的 Turbo CS 算法最为突出。然而，这些方法对观测矩阵有较高要求（高斯随机矩阵假设、部分 DFT 矩阵假设），这在实际通信系统的设置与规模下难以满足。我们将展示如何使用算子分裂的视角统一上述算法，并介绍在此基础上得到的交替子空间方法。该方法将开销较大的观测匹配模块限制在子空间，同时让算法保持不动点迭代的结构、保证其局部收敛性。我们将展示该算法在 TDD 上行信道重构的高效应用，以及如何在包含非理想因素的场景中保持精度。

    </p>
    <p>
    <b>报告人信息</b>: 朱旭，北京大学数学科学学院博士生，导师为李铁军教授。研究兴趣为统计计算、优化算法与信号处理。</p>

1. Jun 5

    **王立恒**，中国科学院数学与系统科学研究院, 博士生
    
    题目：Combining Variational Models and Deep Learning: Aiming for Interpretable Network Design in Image Segmentation

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>: 近十年来，深度学习方法在图像分割领域取得了显著进展，尤其是基于卷积神经网络和Transformer的模型在精度和效率上表现优异。然而，这些模型通常被视为“黑箱”，缺乏一定的可解释性，限制了其在医学影像领域的实际应用。与此同时，变分模型（如水平集方法）则利用目标的几何性质（如灰度、边界、质地等）进行分割，具有清晰的数学形式和可解释的分割机制，但其性能往往受限于手工设计能量函数的表达能力，同时也无法充分利用海量的图像数据。因此，将变分模型与深度学习相结合的研究范式应运而生，通过结合两者的互补优势，期望构建兼具高精度和可解释性的图像分割网络。本次报告主要回顾了近年来若干将两者相结合的方式，并对可能的发展方向进行展望。

    </p>
    <p>
    <b>报告人信息</b>: 王立恒，中国科学院数学与系统科学研究院博士生，导师为陈冲副研究员。研究兴趣为医学图像重建、医学图像处理。</p>

1. Jun 11

   **林挺**，北京大学，博士生

    题目：Finite element form-valued forms: A unified construction

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>: We provide a finite element discretization of $\ell$-form-valued $k$ form in $n$ dimensions for general $k$, $\ell$ and $n$ and polynomial degree. The construction generalizes finite element Whitney forms for the de~Rham complex and their higher-order and distributional versions, the Regge finite elements and the Christiansen--Regge elasticity complex, the TDNNS element for symmetric stress tensors, the MCS element for traceless matrix fields, the Hellan--Herrmann--Johnson (HHJ) elements for biharmonic equations, and discrete divdiv and Hessian complexes in [Hu, Lin, and Zhang, 2025]. The construction discretizes the Bernstein--Gelfand--Gelfand (BGG) diagrams. Applications of the construction include discretization of strain and stress tensors in continuum mechanics and metric and curvature tensors in differential geometry in any dimension. This talk is based on a joint work with Kaibo Hu (Edinburgh).

    </p>
    <p>
    <b>报告人信息</b>: 林挺，北京大学数学科学学院计算数学方向博士生。曾获北京大学未名学士，北京大学校长奖学金，东亚SIAM分会最佳论文奖一等奖等。2025年入选科协青年人才托举工程博士生专项。主要研究方向为有限元方法与深度学习中的逼近论，相关论文发表于Journal of the European Mathematical Society, Foundations of Computational Mathematics, Mathematics of Computation, Journal of Machine Learning Research, SIAM系列期刊等。</p>








-----
This webpage is maintained by Ting Lin (@alisomia)
