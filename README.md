**TenantEase – Property Rental Management System**

**Project Overview**

TenantEase is a Salesforce-based application designed to manage rental units, rental agreements, statements and tenant payments.

The project explores how Salesforce can be used to organise rental property information and manage related records through custom objects, relationships and backend development.

**Technologies Used**

- Salesforce Platform
- Custom Objects and Fields
- Object Relationships
- Apex
- Visualforce
- API Callouts
- Authorize.Net Sandbox

**Features Implemented**

**1. Property and Rental Management**
- Created custom objects to manage rental units and related rental information.
- Configured fields to capture property details.
- Established relationships between relevant Salesforce objects.

**2. Rental Agreements and Statements**
- Created custom objects for rental agreements and statements.
- Configured relationships to organise rental records.

**3. Payment Management**
- Created a Payment object to maintain payment-related information.
- Developed Apex classes for backend processing.
- Integrated Salesforce with Authorize.Net Sandbox using API callouts.
- Generated hosted payment tokens.

**4. Payment Integration**
- Created a Visualforce payment page.
- Connected Salesforce to the Authorize.Net hosted checkout.
- Tested the checkout using sandbox payment details.
- Observed an error message when entering an invalid card number.
- Successfully completed a sandbox payment test and received an email confirmation.

**Payment Flow**
1. User opens the Salesforce payment page.
2. Salesforce requests a hosted payment token through Apex.
3. Authorize.Net generates the hosted checkout form.
4. User enters sandbox payment details.
5. Payment is processed in the sandbox environment.
6. An email confirmation is received after successful testing.

## Screenshots & Demo

### Schema Builder

Created the Salesforce data model from scratch using Schema Builder, defining custom objects and their relationships.

**1. Rental Management Schema**

Includes the Tenant, Rental Agreement and Contact objects and their relationships.

![Rental Management Schema](screenshots/rental-management-schema.png)

**2. Statement and Payment Schema**

Includes the Statement and Payment objects and their relationships.

![Statement and Payment Schema](screenshots/statement-payment-schema.png)

### Payment Integration – Execution Demo

The video demonstrates the Salesforce and Authorize.Net Sandbox payment integration, including:

- Opening the Visualforce payment page.
- Redirecting to the Authorize.Net hosted checkout.
- Error handling when an invalid card number is entered.
- Processing a successful sandbox payment.
- Receiving the payment confirmation email.

**Video Demonstration:** [Watch Payment Integration Demo](ADD_YOUR_VIDEO_LINK_HERE)

Continuous learning, building and exploring!
