# Car Database

Use Alembic to create a database with these table schemas:

### cars

id - int and primary key

vin - text

model - text

make - text

engine - text

year - int

### dealerships

id - int and primary key

name - text

address - text

phone_number - text

### inventory

car_id - foreign key to cars.id

dealer_id - foreign key to dealerships.id

cost - float

is_sold - boolean

Primary key is car_id and dealer_id together (composite key)

## Submission

Submit a link to your github repo with these alembic files.