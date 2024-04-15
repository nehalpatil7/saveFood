# saveFood

## Food Waste Reduction App
### Inspiration
The inspiration behind our Food Waste Reduction App stems from two critical issues: food waste and food insecurity. We observed that many restaurants and grocery stores often have surplus food that goes to waste due to lack of efficient channels for redistribution. Simultaneously, numerous individuals and families in our community struggle with food insecurity, lacking access to nutritious meals. We saw an opportunity to bridge this gap by creating a mobile app that connects surplus food providers with local food banks and community organizations.

### Built With
1. html
2. css
3. express.js
4. python
5. flask
6. mysql


### Running the application
1. Navigate to backend directory
2. Run commands
   i. pip install Flask
   ii. pip install flask_cors
   iii. pip install pymysql
   iv. pip install pymon
4. Install MySQL on your local machine
5. Make sure MySQL is running; Create necessary databases and tables; FoodInventory(id, foodName, quantity, expiry_date, address)
6. Update DB connection details in __init__.py file
7. Run command
   i. pymon __init__.py
   OR
   i. python3 __init__.py
   OR
   i. export FLASK_APP = __init__.py
   ii. export FLASK_ENV = "development"
   iii. flask run
9. Navigate to the link displayed on terminal after the backend server starts
