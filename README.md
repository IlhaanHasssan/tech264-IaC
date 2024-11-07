# ***INFRASTRUCTURE AS CODE*** 🏦
- [***INFRASTRUCTURE AS CODE*** 🏦](#infrastructure-as-code-)
  - [***What is IaC?*** 💭](#what-is-iac-)
  - [***Benefits of IaC?*** 😁](#benefits-of-iac-)
  - [***When/where to use IaC?*** 📅](#whenwhere-to-use-iac-)
  - [***What are the tools available for IaC?*** 🔨](#what-are-the-tools-available-for-iac-)
  - [***What is configuration management (CM)?*** 🖥️](#what-is-configuration-management-cm-️)
  - [***What is provisioning of infrastructure? Do CM tools do it? 🔦***](#what-is-provisioning-of-infrastructure-do-cm-tools-do-it-)
  - [***What is Ansible and how does it work?*** ⭕](#what-is-ansible-and-how-does-it-work-)
  - [***Who is using IaC and Ansible in the industry?*** ™️](#who-is-using-iac-and-ansible-in-the-industry-️)
  - [***How Terraform and Ansible fit into the bigger picture***](#how-terraform-and-ansible-fit-into-the-bigger-picture)
  - [***Greenfielding vs Brownfielding***](#greenfielding-vs-brownfielding)
## ***What is IaC?*** 💭
**Infrastructure as Code (IaC)** is a method to manage and provision computing infrastructure using machine-readable configuration files, rather than manual processes.

## ***Benefits of IaC?*** 😁
- **Consistency**: Reduces human error by automating setup processes.
- **Speed**: Faster deployment of infrastructure.
- **Scalability**: Easily replicate environments.
- **Version control**: Configuration can be versioned and tracked.
- **Collaboration**: Enables collaboration by treating infrastructure like software code.

## ***When/where to use IaC?*** 📅
- **Cloud environments**: To manage resources in public or private clouds.
- **DevOps practices**: To automate and streamline infrastructure provisioning.
- **CI/CD pipelines**: Automate deployment and infrastructure management.

## ***What are the tools available for IaC?*** 🔨
- **Terraform**
- **AWS CloudFormation**
- **Pulumi**
- **Ansible**
- **Chef**
- **Puppet**

## ***What is configuration management (CM)?*** 🖥️
**Configuration Management (CM)** is the practice of managing and maintaining the desired state of an organization's infrastructure, ensuring systems are configured correctly and consistently. These are tools like Puppet, Chef and Ansible.

## ***What is provisioning of infrastructure? Do CM tools do it? 🔦***
**Provisioning of infrastructure** refers to the process of setting up and configuring resources such as servers, networks, and storage. **Yes**, some CM tools like Ansible, Chef, and Puppet can also handle infrastructure provisioning in addition to configuration management. Tools for this include Terraform ! *Ansible can do this though it isn't it's primary function so it isn't as good as terraform*

## ***What is Ansible and how does it work?*** ⭕
**Ansible** is an open-source automation tool for configuration management, application deployment, and infrastructure provisioning. It works by using **playbooks** (YAML files) to define automation tasks, and it operates agentlessly over SSH or PowerShell.

## ***Who is using IaC and Ansible in the industry?*** ™️
- **Tech companies** (e.g., Google, Facebook)
- **Cloud providers** (e.g., AWS, Microsoft Azure)
- **Financial services** (e.g., Capital One)
- **E-commerce** (e.g., Amazon)
- **Telecommunications** (e.g., AT&T)


## ***How Terraform and Ansible fit into the bigger picture***
<br>

![alt text](/tech264-docker-kubernetes/dk-images/image.png)

<br>

---

## ***Greenfielding vs Brownfielding***
- Greenfielding means starting a project or development from scratch. Think of it as building on an empty "green field," where you have no existing structures or constraints to worry about. You get to design everything from the ground up, using the latest tools, technologies, and best practices without dealing with any outdated or legacy systems.

- Brownfielding is the opposite—working on or improving an existing project or system. Imagine building on a "brown field" that already has old buildings or structures on it. In this case, you have to work with or around what’s already there, which may include outdated tech or design choices that make changes or upgrades more complicated.

**In summary:**

- Greenfield: New project, starting fresh, total freedom.
- Brownfield: Existing project, updating or improving, dealing with old setups.