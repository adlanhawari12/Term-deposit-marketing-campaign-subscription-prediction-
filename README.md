# term_deposit_marketing_campaign_capstone-3_adlan
capstone_3-adlan
Business Issues
Company Background : The bank wants to create a problem that helps decide which customers to target in its term deposit marketing campaign. This system will predict whether the customer will answer "yes" or "no" to the term deposit offer.

Background : The bank carries out a marketing campaign to promote term deposits to customers. To make this campaign more efficient, we wanted to use machine learning to predict which customers were likely to subscribe to term deposits after being contacted.

Potential losses from missed deposits can exceed marketing expenses due to increased costs of funds, the need to maintain liquidity, and the strategic importance of deposits to a bank's financial health. Therefore, banks must carefully balance their marketing investments to attract and retain deposits while managing the associated costs.

Based on the background and references that have been determined, it is concluded that the losses faced by banks are greater when they lose customers for deposits compared to the marketing costs incurred for bank marketing campaigns

-False Positive (FP): This occurs when the model predicts that a client will make a deposit, but in reality the client does not actually make a deposit. In the context of a marketing campaign, a false positive means a bank may consider a client to be a good prospect for making a deposit, and so may spend additional resources in an effort to attract them, but in reality, those efforts are not producing the expected results. Assume the funds spent on marketing are $500 USD
-False Negative (FN): This occurs when the model predicts that a client will not make a deposit, but in reality the client actually makes a deposit. In the context of a marketing campaign, a false negative means the bank may have missed an opportunity to attract clients who actually had the potential to make a deposit. These clients may have characteristics or behavior that should indicate a high probability of making a deposit, but because the model predictions were wrong, the bank took no action to target them. The assumed loss resulting from a wrong prediction is $1500 USD

The scoring metric used is "Recall". This is used because based on business problems, False Negative aspects need to be minimized. Therefore, it is necessary to use Recall to minimize False Negatives.
