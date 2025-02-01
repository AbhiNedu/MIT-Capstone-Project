1.	Business Understanding
    The project involves predicting sales amounts using regression techniques, with a focus on understanding the key factors that drive sales performance across different categories, SKUs, and promotions.
2.	 Dataset Understanding
    The dataset includes sales transactions with the following attributes:
          • Category: Type of product (e.g., electronics, clothing).
          • Size: Size specification of the product.
          •	Date: Date of the sale.
          •	Status: Status of the sale (e.g., completed, pending).
          •	Fulfillment: Order fulfillment method (e.g., delivery, in-store pickup).
          •	Style: Product style or variation.
          •	SKU: Unique inventory identifier.
          •	ASIN: Amazon identifier.
          •	Courier Status: Courier delivery status.
          •	Qty: Quantity sold.
          •	Amount: Sale value in the specified currency.
          •	B2B: Business-to-business transaction indicator.
          •	Shipping Location: Includes city, state, postal code, and country.
          •	Promotion IDs: Promotions applied to the sale.
          •	Currency: Transaction currency.
3.	Data Limitations
      •	High cardinality in categorical variables such as SKU, ASIN, and Ship City.
      •	Skewed distribution of the target variable (Amount).
      •	Resource limitations for implementing certain advanced models like XGBoost with hyperparameter tuning.
4.	Benefits of the Project
      •	Enables data-driven pricing and inventory management.
      •	Optimizes promotional campaigns and enhances customer targeting.
      •	Identifies underperforming products and areas for improvement.
