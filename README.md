# Real_Estate_Market_Trends _Analysis- Using PCA Algorithm
This project demonstrates the use of Principal Component Analysis (PCA) to analyze and reduce the dimensionality of real estate data. By reducing 35 numerical features to 5 principal components, the project retains most of the variance while simplifying the data for better insights and predictive modeling.

# Abstract:
A key challenge for property sellers is to determine the sale price of the property. The ability to predict the exact property value is beneficial for property investors as well as for buyers to plan their finances according to the price trend. The property prices depend on the number of features like the property area, basement square footage, year built, number of bedrooms, and others. The prices can be predicted more accurately if the number of predictors is less. Several dimension reduction techniques are being applied to decrease this number of predictors.

# Problem Statement:
Perform exploratory data analysis on real estate data and implement Principal Component Analysis (PCA) for dimensionality reduction.

# Dataset Information:

The dataset describes nearly every aspect of residential homes in Ames, Iowa, using 79 explanatory variables. These variables include features such as property type, location, building condition, and sale details.

Key Features

Input Variables:

MSSubClass: Identifies the type of dwelling involved in the sale.

Examples: 1-Story, 2-Story, Duplex, etc.

MSZoning: General zoning classification of the sale.

Examples: Residential Low Density, Commercial, Agriculture, etc.

LotFrontage: Linear feet of street connected to the property.

LotArea: Lot size in square feet.

Street: Type of road access to property.

Examples: Gravel, Paved.

Alley: Type of alley access to property.

Examples: Gravel, Paved, None.

... (Details for all 79 variables available in the full dataset).

# Content Overview

1. Import Packages

Necessary libraries such as pandas, numpy, matplotlib, and sklearn are imported for data manipulation, visualization, and PCA.

2. Read Data

The dataset is loaded and inspected to understand its structure and key attributes.

3. Understand and Prepare the Data

	3.1 Data Types and Dimensions
	
		Understanding the types of features (numerical, categorical) and the shape of the dataset.
	
	3.2 Feature Engineering
	
		Perform feature transformations and encoding as needed.
	
	3.3 Missing Data Treatment

		Handle missing values through imputation or removal based on data distribution and relevance.

4. Compute Principal Components (from scratch)

	4.1 Prepare the Data
	
		Select numerical features for PCA.
	
	4.2 Scale the Data
	
		Normalize the data to ensure all features contribute equally.
	
	4.3 Covariance Matrix
	
		Compute the covariance matrix to understand feature relationships.
	
	4.4 Compute Eigenvalues and Eigenvectors
	
		Calculate eigenvalues and eigenvectors to determine the principal components.
	
	4.5 Decide Number of Principal Components
	
		Analyze cumulative explained variance to decide on the optimal number of components.
	
	4.6 Calculate Principal Components
	
		Transform the data into the new principal component space.

5. Compute Principal Components (using sklearn)

	Utilize sklearn's PCA implementation for efficient computation and validation of results.
6. Conclusion

	Using PCA, the 35 numerical variables were successfully reduced to 5 principal components. These components explain most of the variance in the dataset while minimizing information loss. This dimensionality reduction improves computational efficiency and aids in better prediction and analysis.

# Feedback and Suggestions:

Thank you for visiting my repository! If you have any questions or feedback, feel free to reach out.

I’d love to hear your thoughts, feedback, and suggestions! Feel free to connect with me:

 LinkedIn: [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
 
 Email: shivanandnashi97@gmail.com


Looking forward to connecting and exchanging ideas!

# ✨ Support this project!
If you found this project helpful or interesting, please consider giving it a ⭐ on GitHub!
Your support helps keep the project active and encourages further development.

Thank you for your support! 💖
