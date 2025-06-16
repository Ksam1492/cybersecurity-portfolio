# OWASP A06: Defending Against Outdated and Vulnerable Software Components

📅 **Date:** April 10, 2025  
🎓 **Course:** CSIA 440 – Secure Software Development  
🎥 **Presentation Link:** [Watch on YouTube (Unlisted)](https://www.youtube.com/watch?v=QmlbUdctF7o&list=PLRX0EcV0YK7poUuMPa5CTAkxD_I7qLKIv&index=2)

## 🧠 Overview

This presentation explores **OWASP A06**, one of the Top 10 web application security risks: the use of **vulnerable and outdated components**. It highlights real-world threats, such as the Equifax breach, and provides actionable guidance on securing software supply chains through tools, policies, and development practices.

## 🔍 Key Topics Covered

- **What are Vulnerable Components?**  
  - Use of outdated libraries, frameworks, plugins, or server software  
  - Real examples: jQuery, WordPress plugins, and deprecated server stacks  

- **How Vulnerabilities Sneak In**  
  - Lack of inventory and tracking (no SBOM)  
  - Delayed patching due to deadlines or fear of breaking changes  
  - Transitive dependencies (hidden risks within imported packages)

- **Real-World Case: Equifax 2017**  
  - Failure to patch Apache Struts  
  - Breach affected 147M consumers  
  - Highlighted the importance of proactive security patching

- **Prevention Strategies**  
  - Maintain a Software Bill of Materials (SBOM)  
  - Use automated tools like Snyk, OWASP Dependency-Check, and GitHub Dependabot  
  - Integrate security checks into CI/CD pipelines  
  - Favor actively maintained libraries  
  - Assign patch management responsibilities

- **Developer Best Practices**  
  - Minimize dependencies and perform regular audits  
  - Subscribe to CVE/security feeds  
  - Use lockfiles and follow project security policies

## ✅ Takeaways

Outdated and vulnerable components are easy targets for attackers but preventable with proper tools and practices. This presentation encourages secure development habits, automation, and awareness to reduce risks across the software supply chain.

---

**Created by:** Sam Mendez  
**Format:** Video presentation with real-world examples and PowerPoint visuals  
