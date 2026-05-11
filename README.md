# 🏫 校园网安全规划设计 | Campus Network Security Design

本仓库托管了我的计算机网络技术专业毕业设计项目。该项目旨在设计并模拟一套高可用、高安全性的校园网络架构。

This repository hosts my graduation project for Computer Network Technology. It aims to design and simulate a highly available and secure campus network architecture.

---

## 📄 项目概述 | Project Overview

**中文**：
这是一个为计算机网络技术专业毕业设计构建的完整网络仿真项目。本设计依据**等保2.0二级**要求，通过 Cisco Packet Tracer 模拟器实现了业务隔离、边界防护及网关冗余。方案涵盖了出口 NAT 配置、防火墙区域划分、VLAN 间 ACL 访问控制以及 HSRP 网关热备份，为高校数字化转型提供了一套低成本、可落地的参考范式。

**English**:
This is a comprehensive network simulation project for my graduation. Based on the **Cybersecurity Classification Protection 2.0 (Level 2)** requirements, it utilizes Cisco Packet Tracer to implement service isolation, perimeter defense, and gateway redundancy. The solution covers NAT configuration, firewall zone segmentation, inter-VLAN ACL control, and HSRP gateway failover, providing a cost-effective reference model for university digital transformation.

## 🛠️ 核心技术栈 | Key Technologies

**中文**：
- **VLAN & 三层交换**：实现广播域隔离与跨网段路由。
- **NAT/PAT**：解决公网 IP 资源短缺，实现内网多部门共享出口。
- **HSRP**：核心网关冗余备份，保障业务连续性。
- **ACL (访问控制列表)**：实施最小权限原则，精细化控制流量。
- **OSPF 动态路由**：实现全网（含分校区）的路由可达。
- **Cisco ASA 防火墙**：构建 Inside/DMZ/Outside 三区域纵深防御。

**English**:
- **VLAN & Inter-VLAN Routing**: Isolate broadcast domains and enable inter-subnet routing.
- **NAT/PAT**: Conserve public IP addresses and allow multiple internal departments to share the internet gateway.
- **HSRP**: Provide gateway redundancy to ensure business continuity.
- **ACL (Access Control Lists)**: Enforce least-privilege access and filter traffic precisely.
- **OSPF Dynamic Routing**: Ensure full network connectivity (including branch campuses).
- **Cisco ASA Firewall**: Establish a defense-in-depth architecture with Inside, DMZ, and Outside zones.

## 📂 文件结构 | File Structure

**中文**：
1.  **`graduation-thesis-campus-network-security.pdf`** 
    - 毕业设计论文全文（含详细配置命令与测试截图）。
2.  **`campus-network-security-design.pkt`** 
    - **Cisco Packet Tracer 源文件**。包含完整的设备拓扑与配置，可直接运行测试。

**English**:
1.  **`graduation-thesis-campus-network-security.pdf`** 
    - Full text of the graduation thesis (including detailed configurations and test screenshots).
2.  **`campus-network-security-design.pkt`** 
    - **Cisco Packet Tracer source file**. Contains the complete topology and configurations, ready for simulation.

## 🚀 如何运行 | How to Run

**中文**：
1.  **阅读文档**：直接在 GitHub 上预览 PDF。
2.  **查看拓扑**：下载 `.pkt` 文件，使用 **Cisco Packet Tracer** (建议 8.0 或以上版本) 打开。
3.  **测试验证**：在模拟器中尝试 Ping 测试，验证 VLAN 隔离与 NAT 上网功能。

**English**:
1.  **Read the Docs**: Preview the PDF directly on GitHub.
2.  **Inspect the Topology**: Download the `.pkt` file and open it with **Cisco Packet Tracer** (version 8.0+ recommended).
3.  **Test & Verify**: Perform Ping tests in the simulator to verify VLAN isolation and NAT internet access.
