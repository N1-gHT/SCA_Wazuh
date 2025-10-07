# SCA_Wazuh
Wazuh ruleset is used to détect configuration problem, application errors, system anomalies or security policy violation
This ruleset is following the CIS BenchMark recommandation

## Directory Structure

    |--- wazuh/ruleset
    |   |--- sca
    |   |--- README.md

## Web references

* [Wazuh website](http://wazuh.com)
* [OSSEC project website](http://ossec.github.io)
* [CIS BenchMark website](https://www.cisecurity.org/cis-benchmarks)


## Update to come

- creating rule for 1.1.1.10
- file every description, rationale and remediation 

## Template to use : 

X.X.X.X Title of the rume. (Automated|Manual)
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
        if it's a command use ' (button 4 for special caracter on azerty)
        else use " (button 3 for special caracter on azerty)