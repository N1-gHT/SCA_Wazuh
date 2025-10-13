# SCA_Wazuh
Wazuh ruleset is used to détect configuration problem, application errors, system anomalies or security policy violation.
This ruleset is following the CIS BenchMark recommandation. \

## Directory Structure

    |--- wazuh/ruleset
    |   |--- sca
    |   |--- README.md

## Web references

* [Wazuh website](http://wazuh.com)
* [OSSEC project website](http://ossec.github.io)
* [CIS BenchMark website](https://www.cisecurity.org/cis-benchmarks)


## Update to come

This is a two-phase project: the first phase involves writing all the rules, and the second phase involves testing and correcting errors.
### Currently in phase 1.

## Template to use : 

```yml
X.X.X.X Title of the rule. (Automated|Manual)
    - id: id_rule
    title: "title of the rule"
    description: "description of the rule "
    rationale: " why is this rule is important"
    remediation: "remediation to valide the rule"
    level: "level of the cis rule"
    references:
      - ""
    compliance:
      - cis: [""]
      - others: [""] 
    condition: all|any
    rules:
      use "" (button 3 for special caracter on azerty)
      use '' (button 4 for special caracter on azerty) when you want to do a commande (ex 'c:findmnt -kn /home -> r:^\s*/home\s')
```
