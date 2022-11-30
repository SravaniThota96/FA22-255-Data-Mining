# FA22-255-Data-Mining

`Apriori` - **Implememted python code from scratch for Apriori**

Calculate the Support of individual item
Support = freq(X) / N

* Count the frequency of each item.
* Calculate the support.
* If Support is >= threshold_support, then consider that item.
* Check which items as a group are brought together based on confidence metric.
* Confidence = freq(X, Y) / freq(X).
* Confidence gives what percent item Y will be purchased if X is purchased.
 
Colab Link:https://colab.research.google.com/drive/15Y3didd7hTc2BWlyaI9KK1T3V2Ug1sDm?usp=sharing


`FpGrowth` - **Implemented python code from scratch for Fpgrowth**

* Count frequency and create header table.
* Delete the items below minSup.
* HeaderTable column [Item: [frequency, headNode]].
* Init Null head node.
* Update FP tree for each cleaned and sorted itemSet.
* Traverse from root to leaf, update tree with given item.
* Sort the items with frequency and create a list.
* Start with the lowest frequency.
* Pattern growth is achieved by the concatenation of suffix pattern with frequent patterns generated from conditional FP-tree.
* Find all prefix path, constrcut conditional pattern base.
* Construct conditonal FP Tree with conditional pattern base.
* Mining recursively on the tree.
* Calcualte the Support and Confidence.

Colab Link: https://colab.research.google.com/drive/1slS4l1iMgBeht-cGfXJEVh7C1sxdovs5?usp=sharing

`Performed market-basket analysis on Databricks Platform`
* Used groceries dataset and found out that Dairy Products are often associated with Vegetables and Fruits using Aprori algorithm.

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2057687678962354/1809417862016328/3677998733216538/latest.html
