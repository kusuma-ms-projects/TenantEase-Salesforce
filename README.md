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

**Screenshots**

Screenshots of the Salesforce application and payment integration will be added here.

- Schema Builder – Custom objects and relationships
- Rental Unit Entry – Property details form
- Visualforce Payment Page
- Authorize.Net Hosted Checkout
- Payment Confirmation Email

**Learning and Implementation Journey**

Only custom object creation is covered in Dipika's YouTube playlist. Although the first video's overview gives the impression that the complete project is covered, the remaining implementation is not covered in the playlist.

I explored the remaining implementation using Salesforce documentation, ChatGPT, Claude and other learning resources. 

This project helped me gain practical exposure to Salesforce configuration, Apex development, Visualforce and third-party payment gateway integration.

It also helped me understand how backend knowledge is useful even when working on UAT, particularly when communicating with development teams and investigating issues beyond the user interface.

Feel free to reach out if you are exploring a similar project or get stuck along the way. Happy to share what I learned!

Continuous learning, building and exploring!
