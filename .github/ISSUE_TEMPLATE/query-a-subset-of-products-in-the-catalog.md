---
name: Query a Subset of Products in the Catalog
about: template's purpose to query a subset of prod
title: ''
labels: ''
assignees: ''

---

**As a** Customer  
**I need** the ability to query a subset of products in the catalog  
**So that** I can find products that meet specific criteria.  

### Details and Assumptions
* Query parameters should support filtering by category, price, and rating.  
* The response time for queries should be under 2 seconds.

### Acceptance Criteria  
```gherkin
Given a customer applies filters to query products,
When they submit the query,
Then the catalog should return only the products that match the specified criteria.
