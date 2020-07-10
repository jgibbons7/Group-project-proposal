# Stories with Data Project Plan

## IDEAS AND USERS

### What problem does your app solve?
- Educating America on social inequality and injustice.

### How does this solve those problems?
- Through data visualization and statistics.

### Who is your target user?
- Skeptical citizens who don’t see a problem.

### How much experience do they have with technology?
- Minimal to none.

## FEATURES

- US Map displaying statistics from FBI API.

- US Map displaying stats from the Harvard Implicit Association Test.

- Navigate statistical breakdowns by state.

- Footer - links to outside websites.  

- Link to local government to sign petitions.

- Recognition for the ones helping the cause.

- Node Mailer to local officials.



WIREFRAME
COMPONENT TREE
ENDPOINTS

GET - /api/footer/links 
GET - /api/map/fbi
GET - /api/map/iat
GET - /api/senate/contact

PUT - /api/footer/links, body
DELETE - /api/footer/links/:id
POST - /api/footer/links, body

