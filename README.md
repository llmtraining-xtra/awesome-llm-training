<body>
<div><h1>awesome-llm-training</h1>

<div id="__source__">

<h2>I. PATOS on GPGPU Program</h2>

In this section, we mainly focus on the following parts:

<ol>
    <li>
        <b><font color="red">O</font>ptimize</b>: <u>Compiler</u> optimization on GPU program.
    </li>
    <li>
        <b><font color="red">T</font>est</b>: Automatically testing on GPU program using approach like fuzzing.
    </li>
    <li>
        <b><font color="red">A</font>nalyse</b>: Program analyse on GPU program, both <u>static and dynamic</u> method.
    </li>
    <li>
        <b><font color="red">P</font>rofiling</b>: How to lightweightly yet accurately analyse GPU state during runtime?
    </li>
    <li>
        <b><font color="red">S</font>chedule</b>: How to efficiently orchestrate GPU workload <u>during runtime</u>?
    </li>
</ol>

<h3>↘ Profile</h3>
<table>
<tr><th>Paper / Posts</th><th>Source</th></tr>

<tr>
<td>Timemory: Modular Performance Analysis for HPC [HPC'20]</td>
<td>[<a href="https://link.springer.com/chapter/10.1007/978-3-030-50743-5_22">Paper</a>] [<a href="https://github.com/NERSC/timemory">Repo</a>]</td>
</tr>

<tr>
<td>HPCToolkit performance tools: measurement and analysis components</td>
<td>[<a href="https://gitlab.com/hpctoolkit/hpctoolkit">Repo</a>]</td>
</tr>

</table>

<h3>↘ Schedule</h3>
<table>
<tr><th>Paper / Post</th><th>Source</th></tr>
<tr><td colspan="2" align="center"><font color="grey">TODO</font></td></tr>
</table>

<h3>↘ Test</h3>
<table>
<tr><th>Paper / Post</th><th>Source</th></tr>
<tr><td colspan="2" align="center"><font color="grey">TODO</font></td></tr>
</table>

<h3>↘ Optimize</h3>
<table>
<tr><th>Paper / Post</th><th>Source</th></tr>

<tr>
<td>MonoNN: Enabling a New Monolithic Optimization Space for Neural Network Inference Tasks on Modern
GPU-Centric Architectures [OSDI'24]</td>
<td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3627703.3629554">Paper</a>]</td>
</tr>

</table>

<h3>↘ Analyse</h3>
<table>
<tr><th>Paper / Post</th><th>Source</th></tr>
<tr><td colspan="2" align="center"><font color="grey">TODO</font></td></tr>
</table>


<h2>II. GPU Workload Understanding</h2>

In this section, we record materials that help to understand the workloads running beyond GPU.

<h3>↘ GPU Kernels</h3>
<table>
<tr><th>Paper / Post</th><th>Source</th></tr>
<tr>
<td>Colfax, an NVIDIA Elite partner across several competencies, is a thought leader in compute performance optimization and developer enablement. </td>
<td><a href="https://research.colfax-intl.com/">[Site]</a></td>
</tr>
</table>




<h2>III. Distributed ML Training and Inference</h2>

<h3>↘ Automatic Parallelism Configuration System</h3>
<table>
<tr><th>Paper / Post</th><th>Source</th></tr>

<tr>
<td>Aceso: Efficient Parallel DNN Training through Iterative Bottleneck Alleviation [Eurosys'24]</td>
<td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3627703.3629554">Paper</a>]</td>
</tr>

<tr>
<td>[OSDI'22] Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization</td>
<td>[<a href="https://www.usenix.org/system/files/osdi22-unger.pdf">Paper</a>]</td>
</tr>

<tr>
<td>[OSDI'22] Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning</td>
<td>[<a href="https://www.usenix.org/system/files/osdi22-zheng-lianmin.pdf">Paper</a>]</td>
</tr>

<tr>
<td>[ATC'22] Whale: Efficient Giant Model Training over Heterogeneous GPUs</td>
<td>[<a href="https://www.usenix.org/system/files/atc22-jia-xianyan.pdf">Paper</a>]</td>
</tr>

<tr>
<td>[NIPS'21] Piper: Multidimensional Planner for DNN Parallelization</td>
<td>[<a href="https://proceedings.neurips.cc/paper/2021/file/d01eeca8b24321cd2fe89dd85b9beb51-Paper.pdf">Paper</a>]</td>
</tr>

<tr>
<td>[PPoPP'21] DAPPLE: A Pipelined Data Parallel Approach for Training Large Models</td>
<td>[<a href="https://arxiv.org/pdf/2007.01045">Paper</a>]</td>
</tr>

<tr>
<td>[Eurosys'19] Supporting Very Large Models using Automatic Dataflow Graph Partitioning</td>
<td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3302424.3303953">Paper</a>]</td>
</tr>

<tr>
<td>[SOSP'19] PipeDream: generalized pipeline parallelism for DNN training</td>
<td>[<a href="https://par.nsf.gov/servlets/purl/10129641">Paper</a>]</td>
</tr>

<tr>
<td>[MLSys'19] Beyond Data and Model Parallelism for Deep Neural Networks</td>
<td>[<a href="https://proceedings.mlsys.org/paper_files/paper/2019/file/b422680f3db0986ddd7f8f126baaf0fa-Paper.pdf">Paper</a>]</td>
</tr>

<tr>
<td>大模型分布式训练并行技术 by 吃果冻不吐果冻皮 (zhihu)  </td>
<td>[<a href="https://zhuanlan.zhihu.com/p/598714869">Posts</a>][<a href="https://github.com/liguodongiot/llm-action">Repo</a>]</td>
</tr>
</table>


<h3>↘ Case Study: Recommendation System</h3>
<table>
<tr>
    <th>Paper / Post</th>
    <th>Source</th>
</tr>
<tr>
    <td>
        [Jun.5 2024] Is this the ChatGPT moment for recommendation systems? 
    </td>
    <td>
        [<a href="https://www.shaped.ai/blog/is-this-the-chatgpt-moment-for-recommendation-systems">Post</a>]
    </td>
</tr>
<tr>
    <td>
        [Apr. 2024] User Action Sequence Modeling: From Attention to Transformers and Beyond 
    </td>
    <td>
        [<a href="https://mlfrontiers.substack.com/p/user-action-sequence-modeling-from">Post</a>]
    </td>
</tr>
<tr>
    <td>
        [Mar.26 2024] 行动胜过言语: Meta落地工业界首个万亿级别参数的生成式推荐系统模型 
    </td>
    <td>
        [<a href="https://zhuanlan.zhihu.com/p/687478684">Post</a>]
    </td>
</tr>
</table>

</div>

</div>
</body>
