---
title: "Dynamic Taint Tracking for Modern Java Virtual Machines"
collection: publications
category: conferences
date: 23-06-2025
preprint: true
venue: 'Foundations of Software Engineering'
paperurl: 'https://katherine-hough.github.io/files/galette_preprint.pdf'
excerpt: "
<details>
    <summary>Abstract</summary>
    <p>
        Dynamic taint tracking is a program analysis that traces the flow of information through a program. In the
        Java virtual machine (JVM), there are two prominent approaches for dynamic taint tracking: &quot;shadowing&quot;
        and &quot;mirroring&quot;. Shadowing is able to precisely track information flows, but is also prone to disrupting the
        semantics of the program under analysis. Mirroring is better able to preserve program semantics, but often
        inaccurate. The limitations of these approaches are further exacerbated by features introduced in the latest
        Java versions. In this paper, we propose Galette, an approach for dynamic taint tracking in the JVM that
        combines aspects of both shadowing and mirroring to provide precise, robust taint tag propagation in modern
        JVMs. On a benchmark suite of 3,451 synthetic Java programs, we found that Galette was able to propagate
        taint tags with perfect accuracy while preserving program semantics on all four active long-term support
        versions of Java. We also found that Galette's runtime and memory overheads were competitive with that of
        two state-of-the-art dynamic taint tracking systems on a benchmark suite of twenty real-world Java programs.
    </p>
</details>
"
---

Dynamic taint tracking is a program analysis that traces the flow of information through a program. In the
Java virtual machine (JVM), there are two prominent approaches for dynamic taint tracking: &quot;shadowing&quot;
and &quot;mirroring&quot;. Shadowing is able to precisely track information flows, but is also prone to disrupting the
semantics of the program under analysis. Mirroring is better able to preserve program semantics, but often
inaccurate. The limitations of these approaches are further exacerbated by features introduced in the latest
Java versions. In this paper, we propose Galette, an approach for dynamic taint tracking in the JVM that
combines aspects of both shadowing and mirroring to provide precise, robust taint tag propagation in modern
JVMs. On a benchmark suite of 3,451 synthetic Java programs, we found that Galette was able to propagate
taint tags with perfect accuracy while preserving program semantics on all four active long-term support
versions of Java. We also found that Galette's runtime and memory overheads were competitive with that of
two state-of-the-art dynamic taint tracking systems on a benchmark suite of twenty real-world Java programs.