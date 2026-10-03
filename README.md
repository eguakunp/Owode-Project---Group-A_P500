# Project Implementation Brief (PIB)

## 1. Project Overview

### 1.1 Purpose

This Project Implementation Brief (PIB) defines the agreed scope for the custom redevelopment of the **Owode Commerce platform by PM Tribe**.

It is intended to provide the team with a clear, practical, and actionable implementation scope for the duration of the engagement. The objective is to eliminate ambiguity around what is expected to be delivered while allowing the team the flexibility to make appropriate technical implementation decisions.

This document defines **what the platform should do**, not necessarily how it should be implemented.

Where additional clarification is required, the existing production platform and the accompanying reference documentation shall be used as supporting materials.

---

### 1.2 About Owode Commerce

Owode Commerce is a commerce infrastructure platform that enables independent merchants to create, manage, and grow modern commerce businesses through a shared technology platform.

Unlike traditional online marketplaces that primarily aggregate products from multiple sellers into a single catalogue, Owode provides merchants with the operational tools required to run independent commerce businesses while benefiting from a shared discovery ecosystem.

The platform enables merchants to:

* Create professional online storefronts
* Manage products and inventory
* Receive secure online payments
* Process customer orders
* Configure seller-managed delivery
* Build customer trust through reviews and reputation
* Receive performance insights
* Grow through promotions and rewards
* Operate across multiple digital sales channels

The platform is designed primarily for **mobile-first commerce** and supports merchants who sell through channels such as **WhatsApp, Instagram, Facebook, TikTok**, and other online communities.

---

### 1.3 Project Goal

The goal of this engagement is to rebuild the existing Owode Commerce platform as a **modern, modular, production-ready web application** capable of replacing the current production system.

The rebuilt platform should preserve existing business capabilities while significantly improving:

* Maintainability
* Scalability
* Usability
* Long-term extensibility

Upon successful completion, the delivered platform should be suitable for production deployment and serve as the primary technology foundation for Owode Commerce.

---

### 1.4 Implementation Philosophy

The primary objective is **business continuity, not feature experimentation**.

Most of the required functionality already exists on the current production platform and has been validated through real-world usage.

Accordingly, the team's responsibility is to reproduce, modernize, and improve these proven business capabilities rather than redesign the product from first principles.

The existing production platform should therefore be regarded as the **functional reference implementation** throughout the engagement.

> Where this document and the reference platform differ, this Project Implementation Brief shall take precedence unless otherwise agreed in writing by the Product Owner.

---

# 2. Project Objectives

The project shall deliver a modern commerce platform that enables merchants to efficiently operate digital businesses while providing customers with a secure and intuitive purchasing experience.

The implementation should prioritise:

* Operational reliability
* Maintainability
* Readiness for future growth

To ensure effective delivery within the engagement timeline, requirements are prioritised using the **MoSCoW prioritisation framework**.

---

## 2.1 Must Have (M)

The following capabilities are **mandatory** for successful project completion.

The delivered platform shall:

* Support user registration, authentication, and role-based access.
* Enable seller onboarding and storefront creation.
* Enable sellers to manage products, pricing, and inventory.
* Support product categories, search, and marketplace discovery.
* Support shopping cart and checkout workflows.
* Integrate **Paystack** for secure payment processing.
* Support **Paystack Split Payments** based on platform commission rules.
* Support order creation, management, and fulfilment.
* Implement seller-managed delivery configuration.
* Provide wallet functionality for rewards and credits.
* Implement the **OGIE Reward Engine** for approved reward issuance.
* Provide administrative interfaces for managing:

  * Users
  * Stores
  * Products
  * Orders
  * Wallets
  * Rewards
  * Platform content
* Support platform content management, including:

  * Homepage content
  * Static pages
  * Blog articles
  * Help centre articles
  * Landing pages
* Generate audit records for important financial and administrative actions.
* Migrate agreed production data from the existing platform.
* Be responsive across desktop and mobile devices.
* Be suitable for production deployment upon acceptance.

> **These capabilities constitute the minimum acceptable scope for project completion.**

---

## 2.2 Should Have (S)

The following capabilities are highly desirable and should be delivered where practical within the engagement period.

* Nearby product and seller discovery.
* Promotion management.
* Seller analytics dashboards.
* Marketplace reporting dashboards.
* Reward history and wallet history.
* Configurable platform settings.
* Comprehensive notification management.
* Basic business intelligence dashboards.
* Event-driven tracking for significant business activities.

Where implementation constraints arise, these features may be simplified provided the **core business workflows remain unaffected**.

---

## 2.3 Could Have (C)

The following capabilities may be implemented if time permits and doing so does not compromise delivery of higher-priority functionality.

* Enhanced search ranking improvements.
* Additional reporting capabilities.
* Extended seller performance metrics.
* Additional administrative productivity tools.
* Improved automation for operational workflows.
* Enhanced promotional capabilities.

These items should only be considered after all **Must Have** and **Should Have** requirements have been satisfied.

---

## 2.4 Won't Be Included in This Engagement (W)

The following items are explicitly **outside the scope** of this engagement.

* Native mobile applications.
* Cross-border commerce capabilities.
* Multi-language support beyond the initial implementation.
* Advanced artificial intelligence features.
* Advanced recommendation engines.
* Marketplace advertising platform.
* Public developer APIs.
* Enterprise organisation accounts.
* Subscription billing beyond the initial membership structure.
* Additional payment gateways beyond the agreed Paystack implementation.

The architecture should remain extensible so these capabilities can be introduced in future phases without requiring major redesign.

---

# 3. Existing Platform & Reference Implementation

The current production platform available at https://owode.co shall serve as the **primary functional reference** throughout this engagement.

The existing platform represents several years of operational learning, validated business workflows, and refined user experience. It should therefore be used to understand:

* Intended platform behaviour
* Workflow sequencing
* Interface expectations
* Business logic

wherever applicable.

The objective of this project is **not** to reproduce the underlying WordPress implementation. Instead, the objective is to reproduce and improve the proven business capabilities currently delivered by the production platform using a **modern custom architecture**.

Unless otherwise specified within this document, existing functionality that supports core business operations should be preserved.

The team is encouraged to review the production platform continuously during implementation to:

* Reduce ambiguity
* Validate expected behaviour
* Ensure consistency with established business workflows

Detailed page inventories, functional workflows, and interface references are provided separately in the accompanying appendices and should be used together with this document during implementation.

Where improvements are identified that enhance:

* Usability
* Performance
* Maintainability

without altering agreed business behaviour, such improvements are encouraged and should be discussed with the **Product Owner during sprint reviews**.

The Product Owner shall remain available throughout the engagement to:

* Provide clarification
* Approve implementation decisions
* Validate completed functionality against the agreed project scope

Detailed page inventories, functional workflows and interface references are provided separately in the accompanying appendices and should be used together with this document during implementation.
Where improvements are identified that enhance usability, performance or maintainability without altering agreed business behaviour, such improvements are encouraged and should be discussed with the Product Owner during sprint reviews.
The Product Owner shall remain available throughout the engagement to provide clarification, approve implementation decisions and validate completed functionality against the agreed project scope.
