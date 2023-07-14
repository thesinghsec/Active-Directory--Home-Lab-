# Active Directory Home Lab

Welcome to the Active Directory Home Lab repository! This repository serves as a resource for managing and documenting your Active Directory (AD) home lab setup. It includes scripts and guides to help you set up and explore various aspects of Active Directory, such as domain population and setup, external exploitation, C2 exploitation, credential harvesting, offensive PowerShell, and more. The lab consists of two Windows 10 Pro machines, one Ubuntu mail server, and one Windows domain controller.

## Table of Contents
- [Introduction](#introduction)
- [Motivation](#motivation)
- [Getting Started](#getting-started)
- [Lab Setup](#lab-setup)
- [Usage](#usage)
- [What You Can Learn](#what-you-can-learn)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Active Directory Home Lab repository provides you with an environment to learn and experiment with Active Directory security and offensive techniques. It covers a wide range of topics, including domain population and setup, external exploitation, C2 exploitation, credential harvesting, offensive PowerShell, and more. By setting up this lab, you can gain hands-on experience and enhance your understanding of Active Directory security.

## Motivation
The motivation behind creating this Active Directory home lab is to provide a practical learning platform for security enthusiasts, system administrators, and anyone interested in exploring Active Directory security. By having a dedicated lab environment, you can safely conduct experiments, test various offensive techniques, and gain valuable insights into how misconfigurations occur and how to remediate them. This lab aims to bridge the gap between theory and practice, allowing you to develop real-world skills and improve your knowledge of Active Directory security.

## Getting Started
To get started with the Active Directory home lab, you'll need the following:
- Two Windows 10 Pro machines
- One Ubuntu mail server
- One Windows domain controller

## Lab Setup
1. **Domain Population and Setup:** Use the scripts provided in the [domain_setup](./domain_setup) directory to populate and set up the Active Directory domain. Refer to the [DomainSetup.md](./docs/DomainSetup.md) guide for detailed instructions.

2. **Windows 10 Pro Machines:** Set up the Windows 10 Pro machines as workstations using the scripts and configuration files available in the [workstation_setup](./workstation_setup) directory. See the [WorkstationSetup.md](./docs/WorkstationSetup.md) file for more information.

3. **Ubuntu Mail Server:** Install and configure the Ubuntu mail server using the steps outlined in the [MailServerSetup.md](./docs/MailServerSetup.md) document.

## Usage
Once your Active Directory home lab is set up, you can start exploring various offensive techniques and security concepts. The repository provides scripts and guides for the following topics:
- Domain population and setup
- External exploitation and email phishing
- C2 exploitation
- Offensive routing and port forwarding
- Credential harvesting and passing
- Domain takeover and remediation
- Offensive PowerShell

Feel free to customize and modify the lab environment according to your requirements. Experiment with different scenarios, test security controls, and learn from the provided resources.

## What You Can Learn
By working with the Active Directory Home Lab, you can gain valuable knowledge and skills in the following areas:

- **Active Directory Configuration:** Learn how to set up and configure an Active Directory domain, including domain population, user management, and group policies.
- **External Exploitation and Email Phishing:** Explore techniques for identifying and exploiting vulnerabilities from an external perspective, including email phishing attacks and their impact on Active Directory security.
- **C2 Exploitation:** Understand the concept of Command and Control (C2) and explore offensive techniques involving C2 frameworks.
- **Offensive Routing and Port Forwarding:** Gain hands-on experience with offensive routing and port forwarding techniques, enabling you to bypass security controls and establish covert channels.
- **Credential Harvesting and Passing:** Learn how to harvest and pass credentials using various methods and tools, and understand the implications for Active Directory security.
- **Domain Takeover and Remediation:** Explore the techniques used to take over a domain and learn effective strategies for remediating domain takeover vulnerabilities.
- **Offensive PowerShell:** Dive into offensive PowerShell techniques, including username and password list generation, password spraying, and more.
- **Real-World Misconfigurations and Remediation Strategies:** Understand common misconfigurations that occur in real-world pentests and learn effective remediation strategies to report to clients.

## Contributing
Contributions to the Active Directory Home Lab repository are welcome! If you have any improvements, bug fixes, additional scripts, or resources to share, we encourage you to contribute to the project.

## License
The Active Directory Home Lab repository is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute the code and resources in this repository for both personal and commercial purposes. However, please note that the code and resources are provided "as is" without any warranty. The authors and contributors of this repository will not be liable for any damages or liabilities arising from the use, misuse, or inability to use the code or resources.

If you choose to use or build upon this project, we kindly request that you provide attribution by referencing or linking to this repository.

By actively engaging with the lab and experimenting with these topics, you can enhance your understanding of Active Directory security, develop practical skills, and strengthen your overall knowledge of offensive techniques and their impact on system security.

Remember, always practice ethical hacking and adhere to responsible use guidelines when conducting any security experiments.

Happy learning!
