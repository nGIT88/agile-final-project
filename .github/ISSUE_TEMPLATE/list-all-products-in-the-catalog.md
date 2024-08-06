---
name: List All Products in the Catalog
about: " template's purpose is to list all products"
title: ''
labels: ''
assignees: ''

---

**As a** Customer  
**I need** the ability to list all products in the catalog  
**So that** I can browse available products easily.  

### Details and Assumptions
* The listing should support pagination and sorting options.  
* Users can filter by categories and price range.

### Acceptance Criteria  
```gherkin
Given a customer accesses the product catalog,
When they request to list all products,
Then the catalog should display all available products with pagination.
