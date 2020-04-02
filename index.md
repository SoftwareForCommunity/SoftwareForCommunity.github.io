---
title: Software for Communities
layout: layout_home
---

# Coronavirus

## Essentials

Information related to the status of the SARS-CoV-2 (COVID-19).

* **Update 2020-03-30**: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
* [Updates from CDC](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/summary.html)
* [Here's a link to some more content!](#)

## Real-Time Updates

Updates on the status of various cities.

* **(2020-03-30) New York City: Avengers headquarters goes into lockdown**: [A quick, 1 sentence summary](#)
* **(2020-03-28) Washington DC: City replaces all the batteries in local birds**: [A quick, 1 sentence summary](#)
	* (2020-03-29) Retraction: birds are real
* Something else

<details><summary>Find updates for your city.</summary>

### Cities
* [Chicago](#)
* [Los Angeles (LA)](#)
* [New York City (NYC)](#)
* [Washington D.C. (DC)](#)

</details>

<p></p>

## Small Business Owners

*Note: You can only apply for EIDL or PPP; <b>you cannot apply for both</b>. These sources update daily, so be sure to double check the links below.*

### Economic Injury Disaster Loan (EIDL) - Applications open now

<details><summary>Click here for more details.</summary>

This 7(b) loan is for up to $2 million dollars to be used on anything like debt, rent, mortgage, utilities, payroll (except for refinancing.) There is no forgiveness - the interest rate is 3.75% for small businesses, 2.75% for non-profits, and small businesses with credit elsewhere are not eligible. Payments to this loan start at 11 months after the loan is approved, with long-term payments available for up to 30 years.

You submit an application to the SBA, who will decide your loan amount based off of last year’s tax returns. The business must demonstrate that it is losing income due to COVID-19. On the application, you can check off the box to be considered for a $10,000 emergency cash advance grant. This grant will be part of your loan amount, but will be completely forgiven if you use it towards rent, utilities, and payroll. You may qualify for the loan, but not qualify for the advance grant. Or, you may qualify for both the loan and the advance grant.

* Click [here](https://www.uschamber.com/co/start/strategy/applying-for-sba-disaster-relief-loan) for more information from the US Chamber of Commerce.
* Check out the [SBA EIDL Fact Sheet](./en/files/SBADisasterAssistance_ResourcesforBusinesses.pdf).
* Check out the links to the [application](https://covid19relief.sba.gov/#/) and [homepage] (https://www.sba.gov/page/coronavirus-covid-19-small-business-guidance-loan-resources#section-header-2). A sample application will be [here](#) when it is ready.

</details>

### Paycheck Protection Program (PPP) - Applications open April 3 for small businesses and April 10 for independent contractors

<details><summary>Click here for more details.</summary>

This 7(a) loan is for 2.5 times your monthly average payroll costs based off last year (up to $10 million). This can be used on payroll, rent, and utilities. If you use at least 75% of the total loan amount on payroll within 8 weeks (and this is a hard rule, as an SBA customer service rep told me), then your total loan will be forgivable. If not, then you will repay your loan at 0.5% interest rate. Loan repayments begin 6 months after the loan is approved and must be repaid within 2 years.

You can submit the PPP application to an approved SBA lender or federally insured depository institution. You don’t have to demonstrate loss of income - just proof that you maintain payroll. A sample application is up on the SBA site, but the real form will be available on April 3. Use this sample to prepare your numbers. Documentation of payroll will be required. 

* SBA PPP homepage (check [here](https://www.sba.gov/funding-programs/loans/paycheck-protection-program-ppp) starting April 3).
* For a sample application, click [here](https://home.treasury.gov/system/files/136/Paycheck-Protection-Program-Application-3-30-2020-v3.pdf).
* Check out the [U.S. Treasury PPP Fact Sheet](https://home.treasury.gov/system/files/136/PPP--Fact-Sheet.pdf).
* For additional information, check out [this](https://www.washingtonpost.com/business/2020/03/30/heres-how-get-small-business-loan-under-349-billion-coronavirus-aid-bill/) article from the Washington Post.
* If your business is with Wells Fargo, their portal for PPP is up, but the application will be open when ready [here](https://update.wf.com/coronavirus/smallbusinessrelief/).

</details>

## Recent Posts

Posts recently submitted to the site.

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &rarr; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<br></br>

