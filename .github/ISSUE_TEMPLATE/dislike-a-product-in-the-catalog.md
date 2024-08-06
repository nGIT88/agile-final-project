---
name: Dislike a Product in the Catalog
about: template's purpose dislike a product
title: ''
labels: ''
assignees: ''

---

**As a** Customer  
**I need** the ability to Dislike a product in the catalog  
**So that** I can express my preferences regarding products.  

### Details and Assumptions
* Users can dislike products without needing to create an account.  
* Disliked products should also be tracked per user.

### Acceptance Criteria  
```gherkin
Given a product exists in the catalog,
When a customer clicks the Dislike button,
Then the product should be marked as disliked for that customer.
