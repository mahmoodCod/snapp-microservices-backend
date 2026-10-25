# Business Scope

## 1. Purpose

This document defines the preliminary business scope of the multi-product platform.

It distinguishes the initial product ecosystem from the features that may be introduced later. It does not define the final implementation plan or technical architecture.

## 2. Product Ecosystem

The intended ecosystem includes the following initial products:

1. Ride-hailing.
2. Food delivery.
3. Parcel delivery.
4. Digital payment and credit.

The platform is designed to connect these products through explicitly defined business workflows and shared capabilities where appropriate.

## 3. Initial Business Scope

### 3.1 Ride-Hailing

Potential initial capabilities:

- Passenger ride requests.
- Pickup and destination information.
- Fare estimation.
- Driver assignment.
- Ride lifecycle tracking.
- Ride cancellation.
- Ride completion.
- Payment coordination.

### 3.2 Food Delivery

Potential initial capabilities:

- Restaurant discovery.
- Restaurant menus and item availability.
- Cart and food-order creation.
- Restaurant order acceptance or rejection.
- Order lifecycle tracking.
- Delivery coordination.
- Order cancellation.
- Payment and refund coordination.

### 3.3 Parcel Delivery

Potential initial capabilities:

- Parcel delivery requests.
- Sender and recipient information.
- Pickup and destination details.
- Delivery pricing.
- Courier assignment.
- Delivery status tracking.
- Delivery completion and exception handling.
- Payment coordination where applicable.

### 3.4 Digital Payment and Credit

Potential initial capabilities:

- Payment requests associated with business operations.
- Payment status tracking.
- Refund workflows.
- Financial transaction traceability.
- Payment-provider integration.
- Wallet operations if included in the approved MVP.
- Credit-related workflows if included in the approved MVP.

Wallet and credit functionality must be scoped carefully. Their inclusion does not imply that all payment methods, lending capabilities, or financial products will be implemented in the first release.

### 3.5 Shared Platform Capabilities

Potential shared capabilities include:

- Customer identity and authentication.
- Product access and navigation.
- Authorization and access policies.
- Notifications.
- Customer support entry points.
- Operational monitoring and auditability.

The exact boundaries and implementation of shared capabilities will be determined during domain modeling and architecture design.

## 4. Cross-Product Integration Scope

The platform is intended to support selected workflows across product boundaries.

Potential initial examples:

- A food order coordinating with delivery capabilities.
- A ride or food order initiating a payment operation.
- A payment outcome being communicated to the initiating product.
- A customer using a common identity across eligible products.

Not every possible integration must be implemented in the first release. The MVP must prioritize a small number of complete, testable end-to-end workflows.

## 5. Potential Future Products and Capabilities

The following are candidates for future consideration, not confirmed commitments:

- Grocery and supermarket delivery.
- Additional local commerce categories.
- Intercity transportation.
- Subscription and loyalty programs.
- Merchant-facing business tools.
- Expanded credit and financial products.
- Advanced analytics and AI-powered customer or operational assistance.

Each future capability must be evaluated against business value, operational complexity, dependencies, and regulatory considerations.

## 6. Out of Scope Until Approved

The following are not automatically included in the initial implementation:

- Full feature parity with an established commercial super-app.
- Real-money financial operations without appropriate provider arrangements and compliance review.
- Unrestricted lending or credit issuance.
- Every possible product category.
- Nationwide operational coverage.
- Fully automated dispatch or pricing based on unvalidated business policies.
- AI systems making high-impact financial or operational decisions without appropriate controls.

These items may be reconsidered after the MVP and relevant requirements have been approved.

## 7. MVP Selection Principles

The initial MVP should:

- Demonstrate at least one complete business workflow.
- Have clear business ownership for each operation.
- Include appropriate failure and recovery behavior.
- Be testable with repeatable scenarios.
- Provide observable outcomes.
- Avoid unnecessary scope expansion.
- Demonstrate meaningful cross-product integration when selected for the MVP.

The final product sequence and MVP capabilities remain open until reviewed and approved.

## 8. Scope Change Management

Any proposed scope change should document:

- The business problem it addresses.
- The users and products affected.
- Dependencies on other products.
- Operational and financial implications.
- Acceptance criteria.
- Whether it belongs in the MVP or a later release.

## 9. Status

**Status:** Draft

This document defines the preliminary scope boundaries. The MVP and delivery priorities will be finalized during requirements analysis.