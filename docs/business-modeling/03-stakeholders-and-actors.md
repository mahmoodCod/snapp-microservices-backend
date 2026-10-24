# Stakeholders and Actors

## 1. Purpose

This document identifies the people, organizations, and external systems that interact with or influence the platform.

A stakeholder is a person or organization interested in the platform's outcomes. An actor is a role that interacts with the platform or participates in a business process.

The same person or organization may act in multiple roles.

## 2. Stakeholders

### SH-01: Platform Owner

Owns the overall business vision, product priorities, and platform-level policies.

### SH-02: Customers

Use one or more products to request services, place orders, make payments, or manage their activity.

### SH-03: Drivers

Provide passenger transportation through the ride-hailing product.

### SH-04: Restaurants

Maintain menus, manage item availability, receive food orders, and prepare accepted orders.

### SH-05: Delivery Partners

Transport parcels or fulfill delivery assignments associated with eligible products.

### SH-06: Payment and Credit Partners

Provide external payment processing or credit-related capabilities where applicable.

### SH-07: Operations and Customer Support

Monitor business operations, investigate incidents, assist customers, and resolve eligible disputes.

### SH-08: Platform Engineering and Security Teams

Maintain the technical platform, protect systems, monitor reliability, and manage technical incidents.

### SH-09: External Service Providers

Provide supporting capabilities such as notifications, maps, geolocation, or identity verification where required.

## 3. Actors by Product

### 3.1 Shared Platform Actors

| Actor | Responsibilities |
|---|---|
| Customer | Access eligible products and manage shared customer information |
| Platform Administrator | Manage authorized platform-level operations |
| Customer Support Agent | Handle support cases according to assigned permissions |
| External Identity Provider | Support identity-related workflows where integrated |
| Notification Provider | Deliver notifications through supported channels |

### 3.2 Ride-Hailing Actors

| Actor | Responsibilities |
|---|---|
| Passenger | Request, manage, and complete rides |
| Driver | Receive eligible assignments and fulfill rides |
| Ride Operations Agent | Handle authorized operational interventions |
| Mapping Provider | Supply relevant mapping or routing capabilities where integrated |

### 3.3 Food Delivery Actors

| Actor | Responsibilities |
|---|---|
| Customer | Browse restaurants and place food orders |
| Restaurant Operator | Manage menus, availability, and order acceptance |
| Delivery Courier | Fulfill delivery assignments |
| Food Operations Agent | Investigate order and fulfillment issues |

### 3.4 Parcel Delivery Actors

| Actor | Responsibilities |
|---|---|
| Sender | Create and manage eligible parcel requests |
| Recipient | Receive a parcel and participate in delivery confirmation where required |
| Delivery Courier | Collect and deliver parcels |
| Parcel Operations Agent | Handle authorized delivery exceptions |

### 3.5 Payment and Credit Actors

| Actor | Responsibilities |
|---|---|
| Customer | Initiate eligible payment or credit-related actions |
| Payment Provider | Process supported payment requests and return payment outcomes |
| Credit Provider | Evaluate or provide credit capabilities if integrated |
| Financial Operations Agent | Investigate financial discrepancies and authorized refunds |
| Reconciliation Process | Compare financial records and identify discrepancies |

The reconciliation process may be performed by an internal system rather than a human actor.

## 4. Actor Relationships

- A customer may act as a passenger, food-ordering customer, sender, or recipient.
- A delivery courier may fulfill assignments originating from different products if business policies and operational capabilities permit.
- A restaurant participates in food-ordering workflows but does not automatically gain access to unrelated customer or financial data.
- Payment providers participate in payment workflows but do not own the platform's product-order lifecycle.
- Support agents may access multiple products only within their authorized responsibilities.
- Platform administrators and product operators have different responsibilities and must not automatically receive identical permissions.

## 5. Preliminary Access Principles

- Authentication identifies an actor or account.
- Authorization determines which actions the actor may perform.
- Shared identity does not imply shared permissions across all products.
- Product-specific roles and eligibility requirements must be explicitly defined.
- Sensitive financial and administrative operations require appropriate access controls and auditability.

Detailed role models, permission policies, and identity architecture will be defined in later documents.

## 6. Open Questions

- Can one account operate as both a customer and a delivery partner?
- How will driver and courier eligibility be verified?
- Which support roles can view cross-product information?
- Which external providers are required for the MVP?
- How will business organizations and individual users be represented?

## 7. Status

**Status:** Draft

The actors and responsibilities are preliminary and will be refined during domain modeling and requirements analysis.