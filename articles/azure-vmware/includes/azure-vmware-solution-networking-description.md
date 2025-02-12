---
title: Azure VMware Solution networking and connectivity
description: Azure VMware Solution networking and connectivity description.
ms.topic: include
ms.date: 05/28/2021
---

<!-- Used in introduction.md and concepts-networking.md -->

Azure VMware Solution offers a private cloud environment accessible from on-premises and Azure-based resources. Services such as Azure ExpressRoute, VPN connections, or Azure Virtual WAN deliver the connectivity and require specific network address ranges and firewall ports for enabling the services.

When deploying a private cloud, private networks for management, provisioning, and vMotion get created. Use these private networks to access vCenter and NSX-T Manager and virtual machine vMotion or deployment.

ExpressRoute Global Reach is used to connect private clouds to on-premises environments. The connection requires a virtual network with an ExpressRoute circuit to on-premises in your subscription.

Virtual machines (VMs) deployed on the private cloud are accessible to the internet through the Azure Virtual WAN public IP functionality.  By default, internet access is disabled for new private clouds. For more information, see [Enable public internet access in Azure VMware Solution](../enable-public-internet-access.md).



