---
title: "OAuth-OpenID Connect Based Authorization to Secure Guest Network/Hotspot"
collection: publications
category: projects
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper presents an OAuth and OpenID Connect-based authentication and authorization mechanism to secure Guest Wi-Fi networks.'
#date: 2010-10-01
#venue: 'Journal 1'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Sowmiya Dhandapani. (2010). "OAuth-OpenID Connect Based Authorization to Secure Guest Network/Hotspot." <i>Journal 1</i>, 1(2).'
---

Guest Wi-Fi networks, commonly provided by businesses for visitors and customers, offer convenience but often lack adequate security. Many small and medium-sized enterprises (SMEs) do not have the infrastructure for proper authentication, authorization, and accounting (AAA), leading to open or static-password networks that are vulnerable to unauthorized access and misuse.

This paper proposes a secure solution using the Open Authorization (OAuth) and OpenID Connect frameworks. Authentication is delegated to trusted identity providers like Google or Facebook, while authorization logic is enforced at the access point level.

By treating the "Internet" as a protected resource and applying a "Deny by Default" policy, the system ensures only authenticated and authorized users can access the network. A prototype implementation is demonstrated using OpenWrt (an open-source wireless router OS), where a web server handles OAuth-based login and issues temporary access to the Wi-Fi network based on successful user validation.

This approach improves the security of guest networks by combining federated identity with localized access control, offering a scalable, standards-based method for securing public Wi-Fi access.
