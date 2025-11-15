# Analysis-vector:

During any review analyze the codebase in this order

- start with the low-hanging issue detection flow to quickly identify and address any obvious vulnerabilities or misconfigurations that can be easily fixed.

`@audit-info` tag to check:
> low-hanging issue detection

---

- focus on the fund drain/advantage flow to identify any vulnerabilities that could lead to financial losses or unfair advantages within the system for the attacker. Here think like a blackhat and check how to manipulate the system

`@audit-info` tag to check:
> fund drain/advantage flow

---

- conduct the user-abuse/loss flow, here you main objective to be a "pain-in-the-ass" for the user so that you can tarnish the repuation of the protocol and if you can find any vector that can lead to fund-draining while doing user-abuse then that is even better

`@audit-info` tag to check:
> user-abuse/loss flow

---

- proceed to the protocol-assault flow to evaluate the system's defenses against potential attacks that could compromise its integrity or functionality but not/maybe potential fund-draining

`@audit-info` tag to check:
> protocol-assault flow
---