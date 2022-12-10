[<img alt="acosalens" width="300px" src="https://github.com/jindalvishal09/AWS/blob/main/Resources/other/Acosa_logo.png" />](https://acosalens.com)

# Why Devops

### ⚡ _What is DevOps?_
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver 
applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional
software development and infrastructure management processes. This speed enables organizations to better serve their customers and
compete more effectively in the market for access and billing. </br></br><img src="/Resources/Why_Needed/Devops_basic.png"/></br></br>

### ⚡ _Software Development in legacy system aka non-agile_
Every management process follows a set of principles. Here are the **three basic principles** the waterfall project management methodology goes by. 
1. **Sequential structure** :- The waterfall model **divides your operations into sequential phases.** You can only move to the next stage in your project once the current one is complete. This also means there’s **no space for changing course or revisiting a phase** after its completion. The only way to go back is to start all over again..
2. **Minimal customer involvement** :- A waterfall project involves **minimal customer interaction**. This is primarily due to the fact that operations only start after the customer’s requirements and objectives are clearly defined. The first meeting takes place before operations begin and the next when the project is in its final stages.
3. **Robust documentation** :- This methodology also involves **in-detail documentation** of all requirements, the development process, and the final outcome. This includes everything from the timeline to the precise route you will take to solve the client’s problems. Since there’s minimal to no customer communication during the development process, **every essential detail needs to be documented upfront.**


### ⚡ _5 Stages of the Waterfall Model – Software Development Cycle_

1. **Documenting Requirements** :- The waterfall model calls for extensive documentation upfront. In the first stage, you gather information from clients or end-users regarding their requirements and the results they expect from the software or product.This is a planning phase and is the last one where you can communicate with clients before work starts on the project
2. **Design** :- The second stage, also known as the analysis stage, is when you review the requirements and develop a design to meet them. Here, your team identifies the path it will take to deliver a solution and the relevant specifications. The second stage is often divided into two parts: the logical design and the physical design stage
</br></br><img src="/Resources/Why_Needed/water_fall.png"/></br></br>

3. **Implementation** :- This is where the action starts. The implementation phase is where the construction or coding, in the case of software development projects, happens. But this might be the shortest stage of all since the entire design is already in place. Your team will follow the documentation from the first two phases to flesh out the actual deliverable.More complex projects break down large software into smaller programs. Teams employ unit testing where they build and test one unit at a time which is later merged together for the final product. 
4. **Maintenance** :- The maintenance stage starts after you release the product and users start using it. You can only identify some issues once the client brings the deliverable to practical use. In case a bug or faulty feature arises, your maintenance team can take care of it. This stage ends when the client is fully satisfied or continues in case they need frequent updates

In a nutshell there are three teams or players into the play namely Development, Testing and IT operations. Developmet and testing being on the same side and IT operations as different. Both works with inherent conflict.

### ⚡ _Chronic Conflict Between Development and Operations_
Among many other key responsibilities, there are two major missions in your IT organization:

1. Your development team has to quickly deliver to respond changing demands from your clients and from the market your business serves for.
2. Your IT operations team has to guarantee stable, predictable, secure and continuous service to serve your clients and market.

**Now You’re in Technical Debt** Continuous firefighting, workarounds and unplanned activities to save your day will only result in accumulation of more technical debt. This not only impacts the performance of your development and operations, but it also negatively impacts all other units including your architecture, information security, testing, product management, release management and your business stakeholders.

You can resemble technical debt in financial debt. The more financial debt you have, the less options you have got to reach your desired goals. Ultimately it becomes almost impossible to give correct decision to reach the desired outcomes and you would be more likely to make additional financial debt.

This brings us to **Andrew Clay Shafer** iconic picture of a wall between developers and operations with a metaphorical depiction of work being thrown over the wall. He coined this **“the wall of confusion.”**
</br></br><img src="/Resources/Why_Needed/wall_of_confusion.png"/></br></br>

### ⚡ _Problems without DevOps_

1. Developers wait days/week for infrastructure provisioning.
2. Manual or ad-hoc deployement of software.
3. No standard software/tools used across teams/business units
4. Developers lack visibility to production enviroment
5. Security is configured ad hoc like deployement.

### ⚡ _Imagine a World Where Dev and Ops Become DevOps_
**DevOps** enables organizations to create a safe system of work, where small teams are able to quickly and independently develop, test, and deploy code and value
quickly, safely, securely, and reliably to customers. This allows organizations to maximize developer productivity, enable organizational learning, create high
employee satisfaction, and win in the marketplace.

### ⚡ _Benefits of DevOps_

1. **Speed** :- Move at high velocity so you can innovate for customers faster, adapt to changing markets better, and grow more efficient at driving business results. The DevOps model enables your developers and operations teams to achieve these results. For example, microservices and continuous delivery let teams take ownership of services and then release updates to them quicker.
2. **Reliability** :- Ensure the quality of application updates and infrastructure changes so you can reliably deliver at a more rapid pace while maintaining a positive experience for end users. Use practices like continuous integration and continuous delivery to test that each change is functional and safe. Monitoring and logging practices help you stay informed of performance in real-time.
3. **Scale** :- Operate and manage your infrastructure and development processes at scale. Automation and consistency help you manage complex or changing systems efficiently and with reduced risk. For example, infrastructure as code helps you manage your development, testing, and production environments in a repeatable and more efficient manner.
4. **Improved Collaboration** :- Build more effective teams under a DevOps cultural model, which emphasizes values such as ownership and accountability. Developers and operations teams collaborate closely, share many responsibilities, and combine their workflows. This reduces inefficiencies and saves time (e.g. reduced handover periods between developers and operations, writing code that takes into account the environment in which it is run).
5. **Security** :- Move quickly while retaining control and preserving compliance. You can adopt a DevOps model without sacrificing security by using automated compliance policies, fine-grained controls, and configuration management techniques. For example, using infrastructure as code and policy as code, you can define and then track compliance at scale.

### ⚡ _DevOps Practices_
1. **Continuous Integration** :- Continuous integration is a software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run. The key goals of continuous integration are to find and address bugs quicker, improve software quality, and reduce the time it takes to validate and release new software updates.
2. **Continuous Delivery** :- Continuous delivery is a software development practice where code changes are automatically built, tested, and prepared for a release to production. It expands upon continuous integration by deploying all code changes to a testing environment and/or a production environment after the build stage. When continuous delivery is implemented properly, developers will always have a deployment-ready build artifact that has passed through a standardized test process.
3. **Microservices** :- The microservices architecture is a design approach to build a single application as a set of small services. Each service runs in its own process and communicates with other services through a well-defined interface using a lightweight mechanism, typically an HTTP-based application programming interface (API). Microservices are built around business capabilities; each service is scoped to a single purpose. You can use different frameworks or programming languages to write microservices and deploy them independently, as a single service, or as a group of services.
4. **Infrastructure as Code** :- nfrastructure as code is a practice in which infrastructure is provisioned and managed using code and software development techniques, such as version control and continuous integration. The cloud’s API-driven model enables developers and system administrators to interact with infrastructure programmatically, and at scale, instead of needing to manually set up and configure resources. Thus, engineers can interface with infrastructure using code-based tools and treat infrastructure in a manner similar to how they treat application code. Because they are defined by code, infrastructure and servers can quickly be deployed using standardized patterns, updated with the latest patches and versions, or duplicated in repeatable ways.
 4.1 **Configuration Management** :- Developers and system administrators use code to automate operating system and host configuration, operational tasks, and more. The use of code makes configuration changes repeatable and standardized. It frees developers and systems administrators from manually configuring operating systems, system applications, or server software.
 4.2 **Policy as Code** :- With infrastructure and its configuration codified with the cloud, organizations can monitor and enforce compliance dynamically and at scale. Infrastructure that is described by code can thus be tracked, validated, and reconfigured in an automated way. This makes it easier for organizations to govern changes over resources and ensure that security measures are properly enforced in a distributed manner (e.g. information security or compliance with PCI-DSS or HIPAA). This allows teams within an organization to move at higher velocity since non-compliant resources can be automatically flagged for further investigation or even automatically brought back into compliance.
5. **Monitoring and Logging** :- Organizations monitor metrics and logs to see how application and infrastructure performance impacts the experience of their product’s end user. By capturing, categorizing, and then analyzing data and logs generated by applications and infrastructure, organizations understand how changes or updates impact users, shedding insights into the root causes of problems or unexpected changes. Active monitoring becomes increasingly important as services must be available 24/7 and as application and infrastructure update frequency increases. Creating alerts or performing real-time analysis of this data also helps organizations more proactively monitor their services.
6. **Communication and Collaboration** :- Increased communication and collaboration in an organization is one of the key cultural aspects of DevOps. The use of DevOps tooling and automation of the software delivery process establishes collaboration by physically bringing together the workflows and responsibilities of development and operations. Building on top of that, these teams set strong cultural norms around information sharing and facilitating communication through the use of chat applications, issue or project tracking systems, and wikis. This helps speed up communication across developers, operations, and even other teams like marketing or sales, allowing all parts of the organization to align more closely on goals and projects.

### ⚡ _References_

* [What is DevOps?](https://aws.amazon.com/devops/what-is-devops/)
* [Waterfall-Methodology](https://managementhelp.org/waterfall-methodology)
* **The DevOps Handbook**
* [What_Are_Your_Problems_In_IT_Without_DevOps](https://www.devops-certification.org/What_Are_Your_Problems_In_IT_Without_DevOps.php)
