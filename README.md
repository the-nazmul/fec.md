# How I answered the questions is described as follows

1. **Which industries contributed the most to the Republican and Democratic parties? How much was contributed to each party?**
   * Answer: *Republican/Conservative* for the Republican Party, *Media/Entertainment* for the Democratic Party. $21,553,578.00 was given to the Democratic Party, while $30,749,000.00 to the Republican Party. 
   * How I did it
      * I formatted the *Amount* tab to currency. Otherwise, the amount is not treated as currency, but as text.
      * I created a *pivot table* and applied *Industry* as the row, *Party* as column, and *Amount* as values (as both default and % of the grand total).
      * I found that *Republican/Conservative* was the industry that contributed the most to either of the parties. They contributed 14% or $7,514,000.00 to the Republican Party. The same group also contributed the most to the Republican Party; none of its money was donated to the Democratic Party. As for the Democratic Party, the *Media/Entertainment* industry was the top contributor, donating $1,880,000.00 to the party.

2. **How much did donors from the Misc. Business sector contribute to the Democratic party? Which donors were based in Miami Lakes, FL?**
   * Answer: $3,520,000.00; Windmere Corp.
   * How I did it
     * On the **Pivot Table** tab, I replaced *Industry* with *Sector* as column. I found that the *Misc. Business* contributed $3,520,000.00 to the Democratic Party.
     * On the same Pivot Table, I used *City* as row and *Donor* as values. I found that there are only one donor from Miami Lakes, FL which donated $100,000 to the Democratic Party twice. The donor’s name is Windmere Corp.

3. **What percentage of the tobacco industry’s donations does Philip Morris account for? How much is it?**
    * Answer: 68.54%; $2,070,000.00
    * How I did it
      * On the **Pivot Table** tab, I used *Industry* as row and *Amount* as values. From the resultant table, I clicked on the *Amount* ($3,020,000.00) that the *Tobacco* industry contributed to. It created a new tab where all the donors belonging to the tobacco industry. I created another Pivot Table, where I used *Donor* as row and *Amount* as values (% of the grand total). I found that both the amount and perchantage of Philip Morris’ contributions. 

4. **Describe (in two to three sentences — no need for a detailed story pitch) one potential story from this dataset that you’d find promising if this were a project you were working on. Give it a headline. Include up to three types of sources you would call to report out the story and a few of the questions you might ask. (These can be bullet points — no need for a long explanation.) Remember to detail the steps you took in analyzing the data to get to the story idea. Use the skills we’ve learned to help you.**
  * Headline: How parties helped or defied their donors; it would be an explanatory story which would try to explain whether the parties favored or defied the industries or sectors that donated them. I will analyze the parties’ voting and legislation records by the amount of money they received from each sector. I would call the Public Citizen, which keeps track of influence peddling in the government. I'd filter the amount of money parties received from different sectors and industries; and then find out the legislations involving different sectors that these parties pushed or opposed. 
5. **What data might be suitable to join with this data to provide context or additional stories? Give me two examples.**
  * Congress voting records data by party lines; the donation details of each congressional candidates of the parites.
