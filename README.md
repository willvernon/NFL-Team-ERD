# NFL Team ER Model

![NFL Team ER Model Final](https://github.com/user-attachments/assets/113b0f39-ea2d-4b6d-a020-f6791ed1c4e5)

I chose an NFL team as my project because i think the structure of the business is very different from other businesses and was a fun challenge to do something different than previous class examples.

I decided to split each table into each department rather than one giant employees table. Specifically because certain coaching and player tenure are not steady so to allow for scalability and simplicity.

### ERD => Relational Model

front_office (front_office_id,name, title, department, salary, date_joined, phone, email, office_location, is_active, reports_to)

business_operations (business_operations_id, name, title, department, salary, date_joined, phone, email, office_location, is_active, reports_to)

player_support (player_support_id, name, title, department, salary, date_joined, phone, email, office_location, is_active, reports_to)

football_operations (football_operations_id, name, title, department, salary, date_joined, phone, email, office_location, is_active, reports_to)

players (player_id, name, unit, position, jersey_number, date_joined, phone, email, is_active, birth_date, height, weight, years_pro, college, drafted, office_location, contract_id,reports_to)

###
