# Sales-Prediction
Machine learning models
I. Problem Description
Predicting the sales of products across stores of a retail chain
A large Indian retail chain has stores across 3 states in India: Maharashtra, Telangana and
Kerala. These stores stock products across various categories such as FMCG (fast moving
consumer goods), eatables / perishables and others. Managing the inventory is crucial for
the revenue stream of the retail chain. Meeting the demand is important to not lose
potential revenue, while at the same time stocking excessive products could lead to losses.
In this hackathon you are tasked with building a machine learning model to predict the
sales of products across stores for one month. These models can then be used to power the
recommendations for the inventory management software at these stores.
II. The datasets are provided as cited below:
Target attribute: "sales" (continuous)
train_data.csv:
! date : The date for which the observation was
recorded
! product_identifier : The id for a product
! department_identifier : The id for a specific department in a
store
! category_of_product : The category to which a product belongs
! outlet : The id for a store
! state : The name of the state
! sales : The number of sales for the product
