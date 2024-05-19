# Dubstech-Datathon-24

I have built a model to Predict the total amount of sales (quantity) in the next 2 years for: Each Product ID
##Steps:
- Started from Data exploration and cleaning.
- Handled the null values in Order Date using backfill imputing.
- Filtering only the successful sales: 'Order Status == Completed' and 'Payment Status == Received'
- Found there is not linear relationship between features and Sales quantity.
- So implemented non-linear model - Decision Tree.
