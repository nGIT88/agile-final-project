---
name: " Delete a Product from the Catalog"
about: template's purpose to delete a product
title: ''
labels: ''
assignees: ''

---

**As a** Product Manager  
**I need** the ability to delete a product from the catalog  
**So that** I can remove discontinued or unavailable items.  

### Details and Assumptions
* There should be a confirmation step before deletion to prevent accidental removals.  
* Deleted products should not appear in customer searches.

### Acceptance Criteria  
```gherkin
Given a user with product deletion permissions,
When they confirm the deletion of a product,
Then the product should be removed from the catalog and no longer visible to customers.
