# example-java-maven
Example Java (maven) repository containing fake data with vulnerable dependencies

There is at least one vulnerable dependency in this repository:

* CVE-2015-7501: Remote code execution during deserialisation (https://access.redhat.com/security/cve/CVE-2015-7501)

Run OWASP Dependency Check Maven Plugin

    mvn org.owasp:dependency-check-maven:check
