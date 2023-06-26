---
marp: true
theme: uncover
paginate: true
header: Cloud & Devops - Eduard Bargués
footer: Barcelona Technology School S.L.
# **class: invert**
# **color: Set text color**
# **backgroundColor**
---

<!--
_class: invert
-->

# **Cloud and DevOps**

1. Hello Cloud
2. Software development
3. AWS & Serverless
4. Security in AWS
5. Advanced Security & CICD
6. Testing, Cost and Security at Ohpen
7. 🥳 **Final Recap + Guest speaker** 🥳

![bg opacity](images/barcelonaLandscape.png)

---

# **Today class ...**

- `09:00`-`11:00`: Recap

- `11:00`-`11:30`: Break + Conference setup

- `11:30`-`13:00`: Conference + Q&A

---

# **DEV**elopment & **OP**eration**S**

> Culture, practices, and tools that teams use to deliver services at high velocity.

[What is Devops?](https://aws.amazon.com/devops/what-is-devops/)

---

# DevOps **Culture**

> Break barries between siloed [teams](https://teamtopologies.com/):
> `Development`, `QA`, `Security`, and `Operations`

- Improve the productivity of developers and reliability of operations.
- Communicate frequently, increase efficiency, and improve quality.
- Full ownership with Customer-first mindset.

---

# DevOps **Practices**

- Frequent and small updates.
- Decoupled architectures: Micro-services, Event-driven
- **C**ontinuous **I**ntegration and **D**elivery
- Infrastructure automation: IaC such as Terraform
- Monitoring: execution and performance via Cloudwatch
- ...

---

# DevOps **Tools**

![bg left:65% w:100%](images/devops_tools.png)

---

![bg](https://osolabs.com/blog/wp-content/uploads/2019/09/devops-tools-690x460-1.png)

---

# **Security** recap

![bg left:60% w:100%](images/security_1.png)

---

# Security **IAM roles**

> How do we translate user permissions into Services?

- Roles can be assumed if allowed.
- Roles don't have credentials but temporary keys.
- AWS services use IAM roles. [Let's see it](https://github.com/EduardBargues/bts_session5_13_06_2023).
- How are our lambdas allowed to access our Dynamodb?

![bg left:20% w:100%](images/any_question.png)

---

# **Permissions at Ohpen**

- How users access AWS?
- How does Github deploy?
- How we ensure nobody can deploy from laptop?

![bg left:40% h:100%](images/ohpen_logo.png)

---

[Active Directory](https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/Overview)
&
AWS SSO

![bg left:65% h:100%](images/security_ohpen.png)
