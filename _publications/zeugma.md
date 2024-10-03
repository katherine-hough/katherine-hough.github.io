---
title: "Crossover in Parametric Fuzzing"
collection: publications
category: conferences
date: 12-04-2024
venue: 'International Conference on Software Engineering'
paperurl: 'https://katherine-hough.github.io/files/zeugma.pdf'
citation: "
Katherine Hough and Jonathan Bell. 
2024. 
Crossover in Parametric Fuzzing. 
In Proceedings of the IEEE/ACM 46th International Conference on Software Engineering (ICSE '24). 
Association for Computing Machinery, New York, NY, USA, Article 129, 1–12. 
https://doi.org/10.1145/3597503.3639160
"
excerpt: "
<details>
    <summary>Abstract</summary>
    <p>
        Parametric fuzzing combines evolutionary and generator-based fuzzing to create structured test inputs that exercise
        unique execution behaviors. Parametric fuzzers internally represent inputs as bit strings referred to as &quot;parameter
        sequences&quot;. Interesting parameter sequences are saved by the fuzzer and perturbed to create new inputs without the need
        for type-specific operators. However, existing work on parametric fuzzing only uses mutation operators, which modify a
        single input; it does not incorporate crossover, an evolutionary operator that blends multiple inputs together.
        Crossover operators aim to combine advantageous traits from multiple inputs. However, the nature of parametric fuzzing
        limits the effectiveness of traditional crossover operators. In this paper, we propose linked crossover, an approach for
        using dynamic execution information to identify and exchange analogous portions of parameter sequences. We created an
        implementation of linked crossover for Java and evaluated linked crossover's ability to preserve advantageous traits. We
        also evaluated linked crossover's impact on fuzzer performance on seven real-world Java projects and found that linked
        crossover consistently performed as well as or better than three state-of-the-art parametric fuzzers and two other forms
        of crossover on both long and short fuzzing campaigns.
    </p>
</details>
"
---

Parametric fuzzing combines evolutionary and generator-based fuzzing to create structured test inputs that exercise
unique execution behaviors. Parametric fuzzers internally represent inputs as bit strings referred to as "parameter
sequences". Interesting parameter sequences are saved by the fuzzer and perturbed to create new inputs without the need
for type-specific operators. However, existing work on parametric fuzzing only uses mutation operators, which modify a
single input; it does not incorporate crossover, an evolutionary operator that blends multiple inputs together.
Crossover operators aim to combine advantageous traits from multiple inputs. However, the nature of parametric fuzzing
limits the effectiveness of traditional crossover operators. In this paper, we propose linked crossover, an approach for
using dynamic execution information to identify and exchange analogous portions of parameter sequences. We created an
implementation of linked crossover for Java and evaluated linked crossover's ability to preserve advantageous traits. We
also evaluated linked crossover's impact on fuzzer performance on seven real-world Java projects and found that linked
crossover consistently performed as well as or better than three state-of-the-art parametric fuzzers and two other forms
of crossover on both long and short fuzzing campaigns.