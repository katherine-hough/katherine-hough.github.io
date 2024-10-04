---
title: "Revealing Injection Vulnerabilities by Leveraging Existing Tests"
collection: publications
category: conferences
date: 01-10-2020
venue: 'International Conference on Software Engineering'
paperurl: 'https://katherine-hough.github.io/files/rivulet.pdf'
citation: "
Katherine Hough, Gebrehiwet Welearegai, Christian Hammer, and Jonathan Bell. 
2020. 
Revealing Injection Vulnerabilities by Leveraging Existing Tests. 
In Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering (ICSE '20). 
Association for Computing Machinery, New York, NY, USA, 284–296. 
https://doi.org/10.1145/3377811.3380326
"
excerpt: "
<details>
    <summary>Abstract</summary>
    <p>
        Code injection attacks, like the one used in the high-profile 2017 Equifax breach, have become increasingly common, now
        ranking #1 on OWASP's list of critical web application vulnerabilities. Static analyses for detecting these
        vulnerabilities can overwhelm developers with false positive reports. Meanwhile, most dynamic analyses rely on detecting
        vulnerabilities as they occur in the field, which can introduce a high performance overhead in production code. This
        paper describes a new approach for detecting injection vulnerabilities in applications by harnessing the combined power
        of human developers' test suites and automated dynamic analysis. Our new approach, Rivulet, monitors the execution of
        developer-written functional tests in order to detect information flows that may be vulnerable to attack. Then, Rivulet
        uses a white-box test generation technique to repurpose those functional tests to check if any vulnerable flow could be
        exploited. When applied to the version of Apache Struts exploited in the 2017 Equifax attack, Rivulet quickly identifies
        the vulnerability, leveraging only the tests that existed in Struts at that time. We compared Rivulet to the
        state-of-the-art static vulnerability detector Julia on benchmarks, finding that Rivulet outperformed Julia in both
        false positives and false negatives. We also used Rivulet to detect new vulnerabilities.
    </p>
</details>
"
---

Code injection attacks, like the one used in the high-profile 2017 Equifax breach, have become increasingly common, now
ranking #1 on OWASP's list of critical web application vulnerabilities. Static analyses for detecting these
vulnerabilities can overwhelm developers with false positive reports. Meanwhile, most dynamic analyses rely on detecting
vulnerabilities as they occur in the field, which can introduce a high performance overhead in production code. This
paper describes a new approach for detecting injection vulnerabilities in applications by harnessing the combined power
of human developers' test suites and automated dynamic analysis. Our new approach, Rivulet, monitors the execution of
developer-written functional tests in order to detect information flows that may be vulnerable to attack. Then, Rivulet
uses a white-box test generation technique to repurpose those functional tests to check if any vulnerable flow could be
exploited. When applied to the version of Apache Struts exploited in the 2017 Equifax attack, Rivulet quickly identifies
the vulnerability, leveraging only the tests that existed in Struts at that time. We compared Rivulet to the
state-of-the-art static vulnerability detector Julia on benchmarks, finding that Rivulet outperformed Julia in both
false positives and false negatives. We also used Rivulet to detect new vulnerabilities.