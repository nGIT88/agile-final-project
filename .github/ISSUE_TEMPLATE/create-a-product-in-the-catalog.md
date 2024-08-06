---
name: Create a Product in the Catalog
about: this template is for creating a Product in the Catalog
title: ''
labels: ''
assignees: nGIT88

---

**As a** Product Manager  
**I need** the ability to create a product in the catalog  
**So that** I can add new items for customers to browse and purchase.  

### Details and Assumptions
* The product creation process should include fields for name, description, price, and images.  
* User permissions will control who can create products.

### Acceptance Criteria  
```gherkin
Given a user with product creation permissions,
When they fill out the product creation form and submit it,
Then the new product should be added to the catalog and visible to customers.
