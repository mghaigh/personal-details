---
hide:
  - navigation
  - toc

---

**Notes:** An Address that Borrowers currently or previously have lived at.  


### Inherits from: 


None  


### Inherited by: 


None  


## Properties


| Name | Type | Notes | Required |
| :--- | :--- | :--- | :---: |
| street | [String](../core-types/primitives/string.md) | The **street** of this Address (**String**)  | Yes |
| town | [String](../core-types/primitives/string.md) | The **town** of this Address (**String**)  | Yes |
| country | [String](../core-types/primitives/string.md) | The **country** of this Address (**String**)  | Yes |
| currentlyLivesAtCount | [Integer](../core-types/primitives/integer.md) | The **currently lives at count** of this Address (**Integer**)  | Yes |
| isCurrentlyLivedAtByPersons | [[Person]](person.md) | The set of **Person** this **Address** is currently lived at by | Yes |
