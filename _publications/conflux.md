---
title: "A Practical Approach for Dynamic Taint Tracking with Control-Flow Relationships"
collection: publications
category: manuscripts
date: 24-12-2021
venue: 'Transactions on Software Engineering and Methodology'
paperurl: 'https://katherine-hough.github.io/files/conflux.pdf'
citation: "
Katherine Hough and Jonathan Bell. 
2021.
A Practical Approach for Dynamic Taint Tracking with Control-Flow Relationships. 
ACM Transactions on Software Engineering and Methodology 31, 2, Article 26 (April 2022), 43 pages. 
https://doi.org/10.1145/3485464
"
excerpt: '
<details>
    <summary>Abstract</summary>
    <p>
    Dynamic taint tracking, a technique that traces relationships between values as a program executes, has been used to
    support a variety of software engineering tasks. Some taint tracking systems only consider data flows and ignore control
    flows. As a result, relationships between some values are not reflected by the analysis. Many applications of taint
    tracking either benefit from or rely on these relationships being traced, but past works have found that tracking
    control flows resulted in over-tainting, dramatically reducing the precision of the taint tracking system. In this
    article, we introduce Conflux, alternative semantics for propagating taint tags along control flows. Conflux aims to
    reduce over-tainting by decreasing the scope of control flows and providing a heuristic for reducing loop-related
    over-tainting. We created a Java implementation of Conflux and performed a case study exploring the effect of Conflux on
    a concrete application of taint tracking, automated debugging. In addition to this case study, we evaluated Conflux’s
    accuracy using a novel benchmark consisting of popular, real-world programs. We compared Conflux against existing taint
    propagation policies, including a state-of-the-art approach for reducing control-flow-related over-tainting, finding
    that Conflux had the highest F1 score on 43 out of the 48 total tests.
    </p>
</details>
'
---
Dynamic taint tracking, a technique that traces relationships between values as a program executes, has been used to
support a variety of software engineering tasks. Some taint tracking systems only consider data flows and ignore control
flows. As a result, relationships between some values are not reflected by the analysis. Many applications of taint
tracking either benefit from or rely on these relationships being traced, but past works have found that tracking
control flows resulted in over-tainting, dramatically reducing the precision of the taint tracking system. In this
article, we introduce Conflux, alternative semantics for propagating taint tags along control flows. Conflux aims to
reduce over-tainting by decreasing the scope of control flows and providing a heuristic for reducing loop-related
over-tainting. We created a Java implementation of Conflux and performed a case study exploring the effect of Conflux on
a concrete application of taint tracking, automated debugging. In addition to this case study, we evaluated Conflux’s
accuracy using a novel benchmark consisting of popular, real-world programs. We compared Conflux against existing taint
propagation policies, including a state-of-the-art approach for reducing control-flow-related over-tainting, finding
that Conflux had the highest F1 score on 43 out of the 48 total tests.