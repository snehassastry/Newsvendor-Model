# Newsvendor-Model

As a part of our optimization class at UT Austin, my team and I tried to decode the Newsvendor model to understand the optimal price at which the newspaper must be sold and the order quantity that the vendor has to order in order to maximize the profits. The model is a fundamental building block in the supply chain industry. There are multiple ways of dealing with it - assuming price as a constant and then finding out the optimal order quantity based on the previous demand data observed (or the probability of various demands) but we know that the demand is also a function of the price at which the newspapers are sold, therefore adding price as another variable would add another layer of complexity. The optimal service level usually depends only on the marginal profit (incremental profit) and the marginal loss, but the quantity to be stocked depends on mean value and the safety stock. Bootstrapping is another way to improve our results by adding a confidence interval to the estimates obtained.

An expansion of this project woould be adding another layer of complexity to maximise the porfits for the entire supply chain instead of just the newsvendor. This helps in risk sharing between different players in the supply chain. 

It is advised to go through the report before going through the code. The dataset for this project consisted of demand and price data for n consecutive days. 

### Collaborators: 
Advaith Shankar, Gayathree Gopi, Jason Antal 

### Under the supervision of : 
Prof. Daniel Mitchell 
