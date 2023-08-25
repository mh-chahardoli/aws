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
How do you determine what your priorities are?
</summary>

The process of determining priorities involves several key steps that revolve around understanding the business context, evaluating needs and risks, fostering collaboration, and clarifying responsibilities. To effectively determine priorities:

1. **Shared Understanding and Business Goals**: Having a thorough understanding of the overall team workload, individual responsibilities within that workload, and the common business goals is essential for effective team performance.. Setting priorities that align with these goals is essential for achieving overall business success.

2. **Customer Needs and Stakeholder Involvement**: Priorities should be established by considering the requirements of both internal and external customers. Key stakeholders, including business, development, and operations teams, should participate in this evaluation process. This ensures that efforts are directed towards areas that deliver the most significant value.

3. **Compliance and Governance**: To establish priorities, it's important to be aware of organizational guidelines, compliance obligations, and external factors such as regulatory standards. Adhering to these requirements ensures that the chosen priorities align with legal and industry-specific mandates.

4. **Risk Assessment and Trade-offs**: Evaluating potential threats to the business, including risks related to business, information security, and liabilities, is essential. Balancing these risks with potential benefits and trade-offs helps in making informed decisions about where to focus efforts.

5. **Collaboration and Interdependence**: Teams should have a clear understanding of their roles in achieving business outcomes. This includes recognizing their responsibilities, ownership, decision-making processes, and authority. Collaborative efforts and shared goals across teams maximize the overall benefits.

6. **Flexibility and Adaptation**: Priorities need to be regularly reviewed and updated based on changing needs. Business environments evolve, and staying flexible allows for adjustments to be made as circumstances shift.

7. **Ownership and Accountability**: Each application, workload, platform, and infrastructure component should have designated owners. Processes and procedures also require identified owners to ensure clarity in their definition and execution. This accountability ensures that responsibilities are clear and tasks are carried out effectively.

8. **Business Value and Innovation**: The ability to comprehend the value and purpose of different components and processes within the business, and how they align with the overall objectives, guides the decisions and behaviors of team members, enabling them to make valuable contributions to the business goals.

9. **Communication and Agreements**: Defining agreements between teams that outline how they collaborate and support each other is crucial. Open lines of communication facilitate effective cooperation and alignment towards common goals.

10. **Continuous Improvement**: The determination of priorities is an ongoing process. Regularly assessing the effectiveness of chosen priorities, evaluating risks, and making necessary adjustments is key to optimizing business outcomes over time.

In essence, the process of determining priorities involves a holistic understanding of the business landscape, collaboration among teams, risk assessment, accountability, and adaptability to changes. This comprehensive approach ensures that efforts are directed towards activities that drive business success while effectively managing risks and promoting innovation.
  </details>

<detail>
<summary>
How do you structure your organization to support your business outcomes?
</summary>

Structuring an organization to effectively support business outcomes requires a comprehensive approach that encompasses various key strategies and practices. By implementing the following measures, you can create an environment that facilitates success:

1. **Empowerment and Support for Team Members**: Provide the necessary resources and support to enable team members to take effective action in line with business goals. Engage senior leadership to establish expectations and gauge success, creating a framework for performance measurement.

2. **Engaged Senior Leadership**: Senor leadership should act as sponsors, advocates, and drivers for the adoption of best practices and the evolution of the organization. Their involvement sets the tone for organizational culture and direction.

3. **Risk Management and Effective Communication**: Encourage team members to take proactive actions when outcomes are at risk. They should be empowered to escalate concerns to decision-makers and stakeholders when risks are identified, ensuring timely resolution. Provide clear and timely communication regarding known risks and planned events. This enables team members to respond promptly and appropriately, mitigating potential issues.

4. **Encourage Experimentation and Learning**: 
  </detail>