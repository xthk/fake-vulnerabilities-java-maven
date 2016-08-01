# example-java-maven
Example Java (maven) repository containing fake data with vulnerable dependencies

There is at least one vulnerable dependency in this repository:

* CVE-2015-6420: Vulnerability in Java Deserialization (https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2015-6420)

Run OWASP Dependency Check Maven Plugin

    mvn org.owasp:dependency-check-maven:check
