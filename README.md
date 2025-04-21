# PROPOSAL TP-DSW-305


## TEAM
### TEAM MEMBERS
* Mayra Belen, Zapata - 42969
* Sarahis, Cabezas - xxxxx


## SUBJECT
### OVERVIEW

### 'ManyBooks'

The project is about developing a full stack web application for a simple ecommerce platform focused on selling books. The system will allow users to browse a catalog of books, apply filters, view detailed information, and simulate purchases. Additionally, there will be an admin interface where administrators can manage book inventory, categories, and users. The main objective is to apply the knowledge acquired in the Software Development course using modern technologies and best development practices.

### MODEL OR CLASESS DIAGRAM
!https://drive.google.com/file/d/1gHukMO8L6qGPykdk_W5BR_u2bZn6RbK8/view?usp=sharing


## FUNCTIONAL SCOPE

### MINIMUM SCOPE

Regularity:
|Req|Detail|
|:-|:-|
|Simple CRUD|1. CRUD-User<br>2. CRUD-Book<br>|
|Dependent CRUD|1. CRUD-Purchase {depends on} CRUD-User, CRUD-Book<br>|

Additional Requirements for AD:
|Req|Detail|
|:-|:-|
|CRUD |1. CRUD-category <br>2. CRUD-Review <br>|
|CUU/Epic|1. User purchases books and leaves a review (A user selects a book, adds it to the cart, completes the purchase, and can later leave a review for that book. This flow adds value by connecting catalog browsing with post-purchase engagement and feedback.)|
