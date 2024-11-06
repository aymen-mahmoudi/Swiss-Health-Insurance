# Swiss-Health-Insurance

## Description
Unlike the other eurpean countires, the swiss health assurance is a bit different. The first element to consider is the *Franchise*, which is the annual amount the insured has to pay out-of-pocket for treatment, before the Swiss health insurer starts reimbursing. The *Franchise* is between 300 and CHF 2,500. (we only consider these two limits).

Once the *Franchise* has been met, your health insurer reimburses 90% of your healthcare costs. You pay the remaining 10%. In Switzerland, this 10% contribution is called the quote-part (
capped at CHF 700 per year)

Of course, if you choose the CHF 300 *Franchise*, the amount you pay monthly is higher (*Prime*).
In this simulation, we try to identify the annual medical expenses that lead to neutrality.

## Usage

# Roadmap
 <ul>
  <li>First visit https://www.priminfo.admin.ch/fr/praemien to get the cheapest *Prime* for the two *Franchise*</li>
  <li>Add these values to the variables PR300 and PR2500</li>
  <li>Run the code</li>
</ul> 

The generated curves shows, the reimboursement you got chossing the *Franchise* of 300 CHF for the different possible expenses ranging from 0 to 2500 CHF. The red horizontal line indicates the additional cost you annualy pay choosing the *Franchise* of 300 CHF.

The plot example below show the case when the diffenrece between the two *Franchise* is 100 CHF. 

<img src="screenshot_app.png"
     alt="gui" width="600" height="350"
      style="float: center"/>


We conclude that it is better to go with the *Franchise* of 2500 CHF only if the annual health expenses are expected to be below 1700 CHF







