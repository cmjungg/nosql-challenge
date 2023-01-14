# Eat Safe, Love

# Contains
	-NoSQL_setup_finished.ipynb
	-NoSQL_analysis_finished.ipynb
	-Resources/establishments.json
	-README.md

# NoSQL_setup_finished.ipynb
-Import Data
mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json

-Update Database
	-Add new establishment
	-Convert latitude and longitude to decimal
	-Remove data with LocalAuthorityName: 'Dover'
# NoSQL_analysis_finished.ipynb
- Find and Print the following questions:
	- 1. Which establishments have a hygiene score equal to 20?
	- 2. Which establishments in London have a RatingValue greater than or equal to 4?
	- 3. What are the top 5 establishments with a RatingValue of '5' sorted by lowest hygiene score, near to the new restaurant added, "Penang Flavours"?
	- 4. How many establishments in each Local Authority area have a hygiene score of 0?

---

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.