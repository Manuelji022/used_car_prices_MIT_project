# used_car_prices_MIT_project
MIT Applied Data Science Final Capstone Project

## **Problem Definition**

### **The Context:**

 - Why is this problem important to solve?

 - Consumer benefit: With accurate predictions of used car prices, consumers can make informed decisions while purchasing or selling used cars. They can ensure they are not overpaying or underselling, and they can budget appropriately for their purchase.
 - Economic indicator: The used car market can also serve as an economic indicator, as changes in used car prices can reflect broader economic trends. This is something we are seeing in the current year, as used price cars are used to measure how the inflaction is affecting the economy.
 - Finance and Insurance: Financial institutions can use these predictions to make decisions about car loans or insurance pricing.
 - Demographic information: The data can also be used to understand the demographics of the used car market, it could help us to identify patterns in the india population based on the model each city uses or the price they are willing to pay for a car.


### **The objective:**

 - What is the intended goal?

To accurately predict the sale price of a used car based on various features.

### **The key questions:**

- What are the key questions that need to be answered?

- Which features have the most impact on the selling price of a used car?
- How accurately can we predict the selling price of a used car?
- What will be the selling price of a used car given specific features such as make, model, age, mileage, condition, etc.?
- What is the best predictive model for this task?
- How reliable or robust is the model to changes in the data? 
- What are the trends in the used car market in India? For example, which car models tend to retain their value?


### **The problem formulation**:

- What is it that we are trying to solve using data science?

Specifically, we want to build a model that can predict the selling price of used cars in India based on various features such as car make and model, age, mileage, fuel type, transmission type, and potentially other characteristics available in the dataset.

Since the selling price of a used car is a continuous variable, this is a regression problem.

### **Data Dictionary**

**S.No.** : Serial Number

**Name** : Name of the car which includes Brand name and Model name

**Location** : The location in which the car is being sold or is available for purchase (Cities)

**Year** : Manufacturing year of the car

**Kilometers_driven** : The total kilometers driven in the car by the previous owner(s) in KM

**Fuel_Type** : The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG)

**Transmission** : The type of transmission used by the car (Automatic / Manual)

**Owner** : Type of ownership

**Mileage** : The standard mileage offered by the car company in kmpl or km/kg

**Engine** : The displacement volume of the engine in CC

**Power** : The maximum power of the engine in bhp

**Seats** : The number of seats in the car

**New_Price** : The price of a new car of the same model in INR 100,000

**Price** : The price of the used car in INR 100,000 (**Target Variable**)