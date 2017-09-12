---
layout: default
---

<div style="text-align:center;">
  <img class="img-spark-flink" src="/images/spark-flink1.png" alt="spark-flink" style="height: 80px; weight: 600px;"/>
</div>


<div class="large-2 large-push-3 columns" markdown="0" style="text-align:center;">
        <a href="https://arxiv.org/abs/1709.02946">
            <img class="t0" width="40%" src="/images/report-icon.png" alt="Technical report">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Technical report</div>
        </a>
</div>    

<div class="large-2 large-push-3 columns" markdown="0" style="text-align:center;">
        <a href="https://streamapprox.github.io/">
            <img class="t0" width="40%" src="/images/bibtex-icon.png" alt="Bibtex">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">BibTex</div>
        </a>   
</div>

<div class="large-2 large-push-3 columns" markdown="0" style="text-align:center;">
        <a href="https://streamapprox.github.io/">
            <img class="t0" width="40%" src="/images/github-icon.png" alt="Source code">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Source code</div>
        </a>
</div>
-------
# Introduction
Approximate computing has recently emerged as a promising computing paradigm which allows making a systematic trade-off between the output accuracy and computation efficiency. Approximate computing is based on the observation that for many practical applications it is acceptable to approximate rather than produce exact output results. The idea behind approximate computing is to compute over a partial subset instead of the entire input data to achieve efficient execution.

Unfortunately, state-of-the-art systems for approximate computing, such as BlinkDB and ApproxHadoop, are primarily geared towards batch analytics, where the input data remains unchanged during the course of sampling. Thus, these state-of-the-art systems cannot be deployed in the context of stream analytics where new data continuously arrives as an unbounded stream.

<div>
  <img style="text-align:center;" class="img-overivew" src="/images/overview.png" alt="overview" style="height: 120px; weight: 680px;"/>
</div>


In this work, we design StreamApprox, a Spark/Flink-based stream analytics system for approximate computing.  StreamApprox implements an online stratified reservoir sampling algorithm in Spark Streaming to produce approximate output with rigorous error bounds.

# Source Code
<!-- Source code will be available soon. -->
We partially release the source code. Full <a href="https://github.com/streamapprox?tab=repositories"> source code </a> will be available, when the work gets published.
* Cluster deployment <a href="https://github.com/streamapprox/flink-setup"> script </a>
* <a href="https://github.com/streamapprox/spark"> Spark-based implementation </a>

------
# News
* This work has been accepted to USENIX Middleware'17, see you in Las Vegas, Nevada!


-------
