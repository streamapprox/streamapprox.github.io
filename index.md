---
layout: default
---

<div style="text-align:center;">
  <img class="img-spark-flink" src="/images/spark-flink1.png" alt="spark-flink" style="height: 80px; weight: 800px;"/>
</div>


<div class="large-2 large-push-2 columns" markdown="0" style="text-align:center;">
        <a href="https://dl.acm.org/citation.cfm?id=3135989&CFID=841147905&CFTOKEN=42765808">
            <img class="t0" width="40%" src="/images/acm-icon.png" alt="Paper">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Paper</div>
        </a>
</div>

<div class="large-2 large-push-2 columns" markdown="0" style="text-align:center;">
        <a href="https://arxiv.org/abs/1709.02946">
            <img class="t0" width="40%" src="/images/report-icon.png" alt="Technical report">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Technical report</div>
        </a>
</div>    

<div class="large-2 large-push-2 columns" markdown="0" style="text-align:center;">
        <a href="/docs/bib.md">
            <img class="t0" width="40%" src="/images/bibtex-icon.png" alt="Bibtex">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">BibTex</div>
        </a>   
</div>

<div class="large-2 large-push-2 columns" markdown="0" style="text-align:center;">
        <a href="https://github.com/streamapprox?tab=repositories">
            <img class="t0" width="40%" src="/images/github-icon.png" alt="Source code">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Source code</div>
        </a>
</div>

-------
<!-- <div class="large-2 medium-push-2 columns" style="text-align:center;position:relative;left:29%;right:auto;">
        <a href="/slides/Middleware17.pptx">
            <img class="t0" width="45%" src="/images/pptx-icon.png" alt="Middleware"> <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Middleware'17</div>
        </a>
</div>

<div class="large-2 medium-push-2 columns" style="text-align:center;position:relative;left:29%;right:auto;">
        <a href="/slides/FlinkForward17.pptx">
            <img class="t0" width="45%" src="/images/pptx-icon.png" alt="Flink Forward">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Flink Forward'17</div>
        </a>
</div>

<div class="large-2 medium-push-2 columns" style="text-align:center;position:relative;left:29%;right:auto;">
        <a href="/slides/SparkSummit17.pptx">
            <img class="t0" width="45%" src="/images/pptx-icon.png" alt="Spark Summit">
            <div style="text-align:center; margin: 0 0 0 0; font-size: 0.8em;">Spark Summit'17</div>
        </a>
</div> -->

<div style="text-align:center; font-size: 0.9em; border-bottom: 3px double #8c8b8b;">
        <div style="text-align:center; margin: 0 0 0 0; font-size: 0.5em;">
        <img width="6%" src="/images/pptx-icon.png" alt="Slides">
        </div>
        <a href="/slides/Middleware17.pptx">Middleware'17</a>|
        <a href="/slides/FlinkForward17.pptx">Flink Forward'17</a>|
        <a href="/slides/SparkSummit17.pptx">Spark Summit'17</a>
</div> 


# Introduction
Approximate computing has recently emerged as a promising computing paradigm which allows making a systematic trade-off between the output accuracy and computation efficiency. Approximate computing is based on the observation that for many practical applications it is acceptable to approximate rather than produce exact output results. The idea behind approximate computing is to compute over a partial subset instead of the entire input data to achieve efficient execution.

Unfortunately, state-of-the-art systems for approximate computing, such as BlinkDB and ApproxHadoop, are primarily geared towards batch analytics, where the input data remains unchanged during the course of sampling. Thus, these state-of-the-art systems cannot be deployed in the context of stream analytics where new data continuously arrives as an unbounded stream.

<div>
  <img style="text-align:center;" class="img-overivew" src="/images/overview.png" alt="overview" style="height: 120px; weight: 680px;"/>
</div>


In this work, we design StreamApprox, a Spark/Flink-based stream analytics system for approximate computing.  StreamApprox implements an online stratified reservoir sampling algorithm in Spark Streaming to produce approximate output with rigorous error bounds.

# Source Code
<!-- Source code will be available soon. -->
The source code of StreamApprox is available <a href="https://github.com/streamapprox?tab=repositories"> here </a>
<!-- * Cluster deployment <a href="https://github.com/streamapprox/flink-setup"> script </a> -->

<!-- * <a href="https://github.com/streamapprox/spark"> Spark-based implementation </a> -->

------
# News
* This work has been accepted to USENIX Middleware'17, see you in Las Vegas, Nevada!


-------
