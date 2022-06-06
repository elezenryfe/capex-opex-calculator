# capex-opex-calculator
calculating the total cost of a product over a period of time with a certain numbers of users

# Problem Statement

Imagine that the bank you work for is about to buy a software product for the
implementation of a new application. After researching the market, it has been concluded
that there are 3 alternatives: a commercial package (Product A), a cloud based SaaS
product (Product B) and a commercially supported open source software (Product C).
Your manager has asked you to perform a comparative study of the 5-year costs of the 3
products, based on the variation of number of users that will have access to the application
and prepare a power-point presentation that summarizes your findings and conclusions.

After contacting the products’ vendors, talking to your colleagues at the bank and
researching the market you have identified the following facts:

**Product A**

Product A consists of 6 components (sub-products) that are all required for the new
application, however, they are licensed independently:
1. Sub-product A1 that is licensed on a per user basis, costing £100 per end-user that will have
access to the application.
2. Sub-product A2 that is licensed on a per user basis, costing £150 per end-user that will have
access to the application.
3. Sub-product A3 that is also licensed on a per user basis, costing £300 per end-user will have
access to the application.
4. Sub-product A4 that is licensed based on the number of CPUs that are installed on the
application server that the product will “run”, with a cost of £5000 per installed CPU.
5. Sub-product A5 that is licensed based on the number of CPUs that are installed on the
application server that the product will “run”, with a cost of £4000 per installed CPU.
6. Sub-product A6 that is licensed based on the number of CPUs that are installed on the
application server that the product will “run”, with a cost of £3000 per installed CPU.

It is estimated that in order to be able to perform adequately in the production
environment, Product A requires 2 CPUs for up to 300 Users, 4 CPUs for 301 to 600
Users and 8 CPUs for 601 to 1000 Users.

Additionally, the new application will have a disaster recovery site for which the
license cost for product A is calculated as 30% of the license fee of the production site
assuming that the production site license fee is calculated with 0 (zero) Users.

Note that, given its purpose, the disaster site still needs to have the appropriate
processing power in order to be able to accommodate the same number of users as the
production environment.

Additionally, starting from the second year, for Product A, the bank will have to pay
the product vendor an annual 18% maintenance fee over the final product license fee
(where the final product license fee includes both the production and the disaster
recovery sites license).

The implementation/customizations fee that the vendor will apply for Product A is
fixed and equal to £200 000. Moreover, starting from the second year, the vendor will
apply an annual 15% maintenance fee over the implementation/customizations fee.

**Product B**

The cloud based SaaS product (Product B) uses a hybrid license and subscription
based pricing. The license for Product B is based on the number of different users that
will have access to the product. The facts for Product B are as follows:

1. The initial license fee for end-users (i.e. business users) is £350 per end-user.
2. The subscription based fee, is due on an annual basis, starts from the first year,
with a cost of £300 per end-user.

There is no disaster recovery site costs for Product B, given that this is a cloud-based
solution.

There are no implementation/customizations fees involved for Product B.

**Product C**

The commercially supported open source product (Product C) license is subscriptionbased (i.e. maintenance only), starts from the first year and costs £25 000 per year, per CPU installed on the application server that the product will run.
It is also estimated that in order to be able to perform adequately in the production
environment, Product B requires 2 CPUs for up to 400 Users, 6 CPUs for 401 to 600
Users and 8 CPUs for 601 to 1000 Users. The licensing cost of the disaster site for
Product C is zero.

The implementation/customizations fee that the vendor will apply for Product C is
fixed and equal to £500 000. Moreover, there is no annual maintenance fee involved
for Product C.

**H/W**

Each CPU (H/W) of the production and disaster environments is acquired at a cost of
£5,000 and has an annual maintenance fee of 10% over the acquisition cost. The
CPU’s (H/W) maintenance fee starts from the second year.

**Questions**

Based on the facts above, in order to prepare the presentation to your manager, you
should perform the following tasks:
1. Devise the mathematical formulas that calculate the 5-year costs for each of the 3
products above (the 5-year costs should include all costs involved).
2. Based on the previous formulas develop an application, implement the formulas
you devised and also build a diagram to show (in the same diagram) the 5-year
TCO costs of each of the products as a variation of the number of end-users.
