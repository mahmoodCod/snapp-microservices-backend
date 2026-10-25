# Business Glossary

## 1. Purpose

This glossary establishes a shared vocabulary for business modeling, domain modeling, requirements analysis, and technical design.

Terms may be refined as the platform's business domains become more clearly defined.

## 2. Platform and Product Terms

### Super App Platform

A digital platform that brings multiple related products together through a connected user experience.

### Platform

The overall business and technical ecosystem that supports and connects the products.

### Product

A business offering with a defined purpose, users, workflows, and responsibilities. A product may contain multiple technical services.

### Business Domain

An area of the business with related concepts, policies, and responsibilities.

### Shared Capability

A capability used by multiple products whose business ownership and access rules must be explicitly defined.

### Cross-Product Workflow

A business process that requires cooperation between two or more products or business domains.

### Minimum Viable Product (MVP)

The smallest agreed scope that can demonstrate meaningful business value through a complete and testable workflow.

## 3. User and Organization Terms

### Customer

A person or organization that uses one or more platform products.

### Passenger

A customer acting in the context of a ride-hailing request.

### Driver

A person eligible to provide passenger transportation through the ride-hailing product.

### Restaurant

A business that offers food items and fulfills accepted food orders.

### Restaurant Operator

An authorized person who manages restaurant information, menus, availability, or orders.

### Sender

A person or organization that requests parcel transportation.

### Recipient

The intended receiver of a parcel.

### Delivery Courier

A person eligible to collect and deliver parcels or fulfill other approved delivery assignments.

### Stakeholder

A person, organization, or group interested in the platform's outcomes.

### Actor

A role performed by a person, organization, or external system participating in a business process.

## 4. Product Terms

### Ride Request

A request from a passenger for transportation between specified locations.

### Ride

The business operation that represents a passenger transportation service from initiation through its terminal outcome.

### Fare

The amount calculated or charged for a transportation service according to the applicable pricing policy.

### Food Order

A customer's request to purchase selected food items from a restaurant.

### Menu Item

A food product offered by a restaurant, subject to applicable availability and pricing rules.

### Parcel Delivery Request

A request to transport a parcel from a collection location to a destination.

### Delivery Assignment

A business assignment that allocates a delivery task to an eligible courier.

### Order Fulfillment

The activities required to prepare and deliver an accepted order according to the applicable business policy.

## 5. Payment and Financial Terms

### Payment

A financial operation intended to settle an amount associated with a business transaction.

### Payment Outcome

The authoritative business status of a payment operation, including applicable success, failure, pending, or unresolved states.

### Wallet

A capability that maintains a customer's platform-related financial balance, if included in the approved scope.

### Ledger

A structured record of financial entries used to track balance-affecting operations and support reconciliation.

### Refund

A financial operation intended to return an eligible amount associated with an earlier payment.

### Credit

A financial arrangement that allows an eligible customer to defer or otherwise structure payment under an approved policy.

### Reconciliation

The process of comparing financial records to identify and resolve discrepancies.

### Settlement

The process through which funds are transferred or financial obligations are finalized between relevant parties.

## 6. Architecture and Process Terms

### Business Rule

A policy or constraint that defines valid business behavior.

### Business Process

A sequence of business activities that achieves a defined outcome.

### Business State

A meaningful condition of a business entity at a particular point in its lifecycle.

### Authoritative Outcome

The confirmed result from the business owner responsible for an operation.

### Compensation

A business action intended to address a previously completed step when a larger workflow cannot proceed as intended.

### Idempotency

The property that repeated execution of an operation with the same logical request does not create unintended duplicate effects.

### Independent Deployment

The ability to deploy a technical service without requiring every other service to be deployed at the same time, subject to compatibility requirements.

### Microservice

An independently deployable software service with a defined responsibility and explicit interaction boundaries.

### Service Boundary

The defined boundary of a technical service's responsibilities and interactions.

### Data Ownership

The responsibility for maintaining and enforcing the rules governing a particular set of business data.

### API Contract

A defined agreement about the requests, responses, errors, and compatibility expectations between software components.

### Domain Event

A record that a meaningful business occurrence has happened within a domain.

## 7. Terminology Principles

- Business products and technical microservices are different concepts.
- A shared user account does not imply shared business permissions.
- A payment outcome is not the same as an order outcome.
- A requested refund is not the same as a completed refund.
- A delivery assignment is not the same as a completed delivery.
- Technical terms must not replace clearly defined business concepts.
- Terms with financial or legal implications must be reviewed before being treated as policy.

## 8. Status

**Status:** Draft

This glossary will evolve as business and domain models become more precise.