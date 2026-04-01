# MSDS460 Final Project
## Optimization
### By Kurt Bouska and Daniel Chee

------------------------

**PROBLEM DESCRIPTION**

NU Industries operates two manufacturing plants that produce three products: Widgets, Gadgets, and Flugels. The finished products are shipped to the Distribution Center for final distribution to the customers. Five periods of production are to be scheduled.

According to the Sales Department, the production requirements that must be met due to contracts during the planning horizon are as follows:

Product| Period 1 | Period 2 | Period 3 | Period 4 | Period 5 |
-------|----------|----------|----------|----------|----------|
Widgets| 70       | 125      | 185      | 190      | 200      |
Gadgets| 200      | 300      | 295      | 245      | 240      |
Flugels| 140      | 175      | 205      | 235      | 230      |

Also, the Marketing & Forecasting Department anticipates that NU Industries can cultivate additional demand within the distribution area through effective advertising. The M&F Department projects that each \$160 invested in advertising Widgets in a particular period creates additional demand for one Widget in the next period. The corresponding values for Gadgets and Flugels are \$120 and \$180, respectively. However, the total advertising budget is limited to \$70,000 for the entire planning horizon.

Throughout the planning horizon, NU Industries will sell Widgets for \$2490, Gadgets for \$1990, and Flugels for \$2970. The products can be manufactured at either of NU's Manufacturing Plants.

The Engineering Department has provided the following manufacturing and inventory data.

<br/>

**Plant A**
The production requirements at Plant A are summarized below.
    • Each Widget requires 194 pounds of Raw Material 1, 8.6 pounds of Raw Material 2, and 9.5 hours of Labor.
    • Each Gadget requires 230 pounds of Raw Material 1 and 7.1 hours of Labor.
    • Each Flugel requires 178 pounds of Raw Material 1, 11.6 pounds of Raw Material 2, and 11.1 hours of Labor.

Regular time labor availability is limited to 2500 hours in each period, but overtime can be scheduled in any amount if necessary. Labor costs during periods 1 and 2 are \\$11/hour for regular time and \$16.50/hour for overtime. Labor costs are expected to rise by 5% at the end of period 2.

The product inventory area can store a combined maximum of 70 units, and inventory costs are as follows. It costs \$7.50 to store one Widget from one period to the next. The corresponding costs for Gadgets and Flugels are \$5.50 and \$6.50, respectively.

<br/>

**Plant B**
The production requirements at Plant B are summarized below.  Plant B is the more modern of the two facilities and is able to produce the products in a slightly more efficient manner.
    • Each Widget requires 188 pounds of Raw Material 1, 9.2 pounds of Raw Material 2, and 9.1 hours of Labor.
    • Each Gadget requires 225 pounds of Raw Material 1 and 7.8 hours of Labor.
    • Each Flugel requires 170 pounds of Raw Material 1, 10.8 pounds of Raw Material 2, and 10.6 hours of Labor.

Regular time labor availability is limited to 3800 hours in each period, but overtime can be scheduled in any amount if necessary. Labor costs during periods 1 and 2 are \$11/hour for regular time and \$16.50/hour for overtime. Labor costs are expected to rise by 10% at the end of period 2.

The product inventory area can store a combined maximum of 50 units, and inventory costs are as follows. It costs \$7.80 to store one Widget from one period to the next. The corresponding costs for Gadgets and Flugels are \$5.70 and \$7.00, respectively.

<br/>

**Raw Material**
A maximum of 70 tons of Raw Material 1 and 2.5 tons of Raw Material 2 are available from a raw material vendor each period. Because of the proximity of the vendor to the plants, Raw Material 1 delivered to Plant A costs \$1.25/pound and Raw Material 2 delivered to Plant A costs \$2.65/pound. The corresponding costs for Plant B are \$1.45/pound for Raw Material 1 and \$2.90/pound for Raw Material 2. Each plant only purchases raw material that can be used within a given period, since storage areas are limited.  (Note, 1 ton = 2000 pounds)

<br/>

**Transportation Costs**
There is an average transportation cost associated with the shipment of each unit of finished product from each plant to the Distribution Center. The cost depends on the product and the plant of origin. The unit shipping costs are given in the following table.

Product| Plant A | Plant B |
-------|---------|---------|
Widgets| \$6.30  | \$6.50  |
Gadgets| \$4.60  | \$5.00  |
Flugels| \$5.50  | \$5.70  |

Demand in a given period must be satisfied by utilizing the units produced in that period or by using inventory from a previous period. The problem is to determine the marketing, production, distribution, inventory strategy that maximizes profit. Assume that there is no inventory at the start of the first period and there should be no inventory at the end of the planning horizon. All other plant overhead is assumed to be constant and can be ignored for this analysis. Also, ignore integer restrictions; that is, assume that fractional units can be manufactured, stored, etc. (For reporting purposes, you can round everything off to the nearest tenth.)

<br/><br/>

Once solving for the baseline case.  Do a complete sensitivity analysis, and make business recommendations.  For example, if you could increase advertising budget – how much?  Which raw material do you need more of?  Recreate these scenarios and provide profit considerations.

Also, if you solved this problem as an integer problem, how much does that differ your recommendations (above).
