### What I Configured

*1:* Zero-Spend Budget
    > Allows AWS to notify me when my spend exceeds `£0` -- (£0.01)    
*2:* Monthly Cost Budget
     > Set a monthly cost budget that;    
          > Alerts me when the budget is on 85% spend    
          > When the forecasted budget is 100%    
          > When the budget is exceeded.    

#### COST MANAGEMENT BEST PRACTICES

Smart ways to avoid Surprise AWS bills and optimise spending
  1. Set a budget upfront
     > Define Spending Limits BEFORE you start
  2. Enable Alerts
     > Get notified on time - not after the damage is done. (in this case I set 85% threshold)
     > Use email notifications and you can add multiple users to be notified
  3. Monitor Regularly
     > Check costs weekly, not only when the bills arrive
     > Use cost Exxplorer to Spot Trends
  4. Use FREE TIER wisely
     > Know what's free and what is not
     > For learning, it is important that I am staying Free Tier Limit

### General Best Practice
1. Tag resources by project and by environment
2. Remove redundant EC2 instances to avoid unncessary cost --> `Like Turning Off the Lights When you Leave`
3. Don't use expensive instances for small tasks --> `Don't drive a SUV to the corner shop, when you could walk 5 mins`
   > Start small and scale up if needed.
4. Use Cost Allocation
   > Separate dev from production spending
   > Track cost by project and teams
