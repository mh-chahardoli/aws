# Fundamental

<details>
<summary>
In AWS well architected framework, what does the component mean?
</summary>

A component is the code, configuration,and AWS Resources that together deliver against a requirement. A component is often the unit of technical ownership, and is decoupled from other components.

</details>

<details>
<summary>
In AWS well architected framework, what does the workload mean?
</summary>

The term workload is used to identify a set of components that together deliver business value. A workload is usually the level of detail that business and technology leaders communicate about.

</details>

<details>
<summary>
In AWS well architected framework, what does the architecture mean?
</summary>

We think about architecture as being how components work together in a workload. How components communicate and interact is often the focus of architecture diagrams.

</details>

<details>
<summary>
In AWS well architected framework, what does the milestone mean?
</summary>

Milestones mark key changes in your architecture as it evolves throughout the product lifecycle(design, implementation, testing, go live, and in production).

</details>

<details>
<summary>
In AWS well architected framework, what does the technology portfolio mean?
</summary>

Within an organization the technology portfolio is the collection of workloads that are required for the business to operate.

</details>

<details>
<summary>
In AWS well architected framework, what does the level of effort mean?
</summary>

The level of effort is categorizing the amount of time, effort, and complexity a task requires for implementation. Each organization needs to consider the size and expertise of the team and the complexity of the workload for additional context to properly categorize the level of effort for the organization.

- High: The work might take multiple weeks or multiple months. This could be broken out into multiple stories, releases, and tasks.
- Medium: The work might take multiple days or multiple weeks. This could be broken out into multiple releases and tasks.
- Low: The work might take multiple hours or multiple days. This could be broken out into multiple tasks.
</details>

<details>
<summary>
Describe some general design principles.
</summary>

- **Stop guessing your capacity needs**
  - If you make a poor capacity decision when deploying a workload,you might end up sitting on expensive idle resources or dealing with the performance implications of limited capacity. With cloud computing, these problems can go away. You can use as much or as little capacity as you need, and scale up and down automatically.
- **Test systems at production scale**
  - In the cloud, you can create a production-scale test environment on demand, complete your testing, and then decommission the resources. Because you only pay for the test environment when it's running, you can simulate your live environment for a fraction of the cost of testing on premises.
- **Automate with architectural experimentation in mind**
  - Automation permits you to create and replicate your workloads at low cost and avoid the expense of manual effort. You can track changes to your automation, audit the impact, and revert to previous parameters when necessary.
- **Consider evolutionary architectures**
  - In a traditional environment, architectural decisions are often implemented as static, onetime events, with a few major versions of a system during its lifetime. As a business and its context continue to evolve, these initial decisions might hinder the system's ability to deliver changing business requirements. In the cloud, the capability to automate and test on demand lowers the risk of impact from design changes. This permits systems to evolve over time so that businesses can take advantage of innovations as a standard practice.
- **Drive architectures using data**
  - In the cloud, you can collect data on how your architectural choices affect the behavior of your workload. This lets you make fact-based decisions on how to improve your workload. Your cloud infrastructure is code, so you can use that data to inform your architecture choices and improvements over time.
- **Improve through game days**
  - Test how your architecture and processes perform by regularly scheduling game days to simulate events in production. This will help you understand where improvements can be made and can help develop organizational experience in dealing with events.
  </details>

<details>
<summary>
What is Operational Excellence Pillar about?
</summary>

The Operational Excellence pillar includes the ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures to deliver business value.
</details>

<details>
<summary>
Describe some operational excellence design principles.
</summary>

- **Perform operations as code**
  - In the cloud, you can apply the same engineering discipline that you use for application code to your entire environment. You can define your entire workload (applications, infrastructure) as code and update it with code. You can implement your operations procedures as code and automate their run process by initiating them in response to events. By performing operations as code, you limit human error and achieve consistent responses to events.
- **Make frequent, small, reversible changes**
  - Design workloads to permit components to be updated regularly. Make changes in small increments that can be reversed if they fail (without affecting customers when possible).
- **Refine operations procedures frequently**
  - As you use operations procedures, look for opportunities to improve them. As you evolve your workload, evolve your procedures appropriately. Set up regular game days to review and validate that all procedures are effective and that teams are familiar with them.
- **Anticipate failure**
  - Perform “pre-mortem” exercises to identify potential sources of failure so that they can be removed or mitigated. Test your failure scenarios and validate your understanding of their impact. Test your response procedures to verify that they are effective, and that teams are familiar with their process. Set up regular game days to test workloads and team responses to simulated events.
- **Learn from all operational failures**
  - Drive improvement through lessons learned from all operational events and failures. Share what is learned across teams and through the entire organization.
  </details>

<details>
<summary>
Describe some best practice areas for operational excellence in the cloud
</summary>

</details>

# Operational Excellence Pillar

# Security Pillar

# Reliability Pillar

# Performance Efficiency Pillar

# Cost Optimization Pillar

# Sustainability Pillar