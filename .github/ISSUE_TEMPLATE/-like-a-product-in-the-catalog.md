---
name: " Like a Product in the Catalog"
about: template's purpose to like a product
title: ''
labels: ''
assignees: ''

---

**As a** Customer  
**I need** the ability to Like a product in the catalog  
**So that** I can easily find and recommend products I enjoy.  

### Details and Assumptions
* Users can like products without needing to create an account.  
* Liked products should be tracked per user.

### Acceptance Criteria  
```gherkin
Given a product exists in the catalog,
When a customer clicks the Like button,
Then the product should be marked as liked for that customer.
