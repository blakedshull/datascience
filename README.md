#Sales Predictions with a focus on Soda
##An exploration of Sales statistics in order to develop better models to predict Sales tth 
**Author:  Blake Shull**

###Business problem: We do not have a strong ability to predict sales

###Data:
Data has been collected across several supermarkets on several thousand products, as well as their MSRP, category, visibility, 
###Methods
Numerical categories with missing values have been dropped, categorical ones have been imputed with "Unknown"
Duplicates have been removed
Several graphs have been constructed to explore the data in various stores, from pie charts showing a % of sales to bar charts side-by-side comparing supermarkets and their total sales.

Linear, Decision Tree, and Bagged Tree regressions have all been performed.  Decision Tree is our best model right now, but it is not very strong.  The Bagged Tree model is probably going to be the best option, however, I need to figure out how to regularize that further.  These were done in order to create models that can predict sales.  

###Results

This set of graphs analyzes Soda sales in order to predict what kind of affect a sugary drink tax would have on each supermarket.  Here we have their sales side-by-side:
![image](https://user-images.githubusercontent.com/107661416/182067728-27806c86-aa0a-46fd-8598-266f9eed4e5d.png)
This gives us a better idea of how little supermarkets (19) vs big supermarkets (27) might be affected:
![image](https://user-images.githubusercontent.com/107661416/182067877-8eb077a8-2413-45ba-9b8d-ebfbacf13cdc.png)
![image](https://user-images.githubusercontent.com/107661416/182067889-9e0782a6-2a18-4dfd-827d-3d0eaa2b8c5f.png)Visual 1 Title
sample image
In other words, proportionally, soft drinks affect the two (and others) very similarly.


###Describe your final model
My final model is a decision tree, but will return to the project for bagged tree modeling, once I figure out regularization more.  Still, that is outside the scope, and until we have better data, the decision tree is most important.

The model can help us understand that Soda sales are equally important in all supermarkets, give or take a percentage point.  With this understanding, fear of being disproportionately affected seems unlikely.

###Recommendations:
Frankly, if every store has an equally vested interest, the smallest stores, unless they are high margin, will be hit harder just by nature of losing volume.  Recommended that the stores in the area cooperate to help control legislation or smaller stores drop soda.

###Limitations & Next Steps
Again, the bagged tree model needs updating.  Also, we do not have an understanding of price sensitivity, since pricing data was not supplied.  This would be very valuable.

For further information
For any additional questions, please contact email: blake.shull@gmail.com
