<!-- <div class="row">
<div class="large-6 large-push-3 columns" markdown="0" style="text-align:center;">
  <img class="img-spark-flink" src="/images/spark-flink1.png" alt="spark-flink" style="height: 150px; weight: 635px;"/>
</div>
</div> -->

<!-- ------

<div class="row" style="text-align:center;">

<div style ="display: inline-block;">
<div class="large-2 large-push-4 columns" markdown="0"">
        <a href="https://streamapprox.github.io/">
            <img class="t0" width="5%" src="/images/report-icon.png" alt="Technical report">

        </a>
</div>
</div>

<div style ="display: inline-block;">   
<div class="large-2 large-push-4 columns" markdown="0">
        <a href="https://streamapprox.github.io/">
            <img class="t0" width="5%" src="/images/bibtex-icon.png" alt="Bibtex">
        </a>   
</div>
</div>

<div style ="display: inline-block;">
<div class="large-1 large-push-4 columns" markdown="0">
        <a href="https://github.com/streamapprox/">
            <img class="t0" width="5%" src="/images/github-icon.png" alt="Source code">
        </a>
</div>
</div>

</div>


------- -->
# Introduction
Approximate computing has recently emerged as a promising computing paradigm which allows making a systematic trade-off between the output accuracy and computation efficiency. Approximate computing is based on the observation that for many practical applications it is acceptable to approximate rather than produce exact output results. The idea behind approximate computing is to compute over a partial subset instead of the entire input data to achieve efficient execution.

Unfortunately, state-of-the-art systems for approximate computing, such as BlinkDB and ApproxHadoop, are primarily geared towards batch analytics, where the input data remains unchanged during the course of sampling. Thus, these state-of-the-art systems cannot be deployed in the context of stream analytics where new data continuously arrives as an unbounded stream.

In this work, we design StreamApprox, a Spark/Flink-based stream analytics system for approximate computing.  StreamApprox implements an online stratified reservoir sampling algorithm in Spark Streaming to produce approximate output with rigorous error bounds.

# Source Code
Source code will be available soon.
