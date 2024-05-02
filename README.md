# Big Data Solutions for Combating Financial Fraud

<br>

## **Table of Contents**

<img width="242" alt="Screenshot 2024-05-02 at 02 25 00" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/650322f1-f83a-470f-82c6-a1f6521f3ade">

<br><br>

## **Business Problem Definition**


In the fight against financial fraud, predicting fraudulent transactions within massive datasets is crucial. Our project aims to leverage advanced analytics and big data techniques to identify patterns of money laundering within a comprehensive synthetic financial transaction dataset provided by IBM. Below are our objectives:

Analyze synthetic transaction data and identify patterns indicative of fraud.
Investigate correlations between transaction features such as amount, currency, and payment format that are most frequently associated with detecting potential money laundering
Analyze temporal patterns, including transaction volume spikes, to identify potential instances of money laundering activities over time.
The proliferation of financial crimes, including money laundering, poses significant threats to both financial institutions and society at large. Financial fraud not only results in substantial economic losses but also undermines the integrity of financial systems and erodes public trust. As criminals continuously adapt their tactics to exploit vulnerabilities in traditional detection methods, there is an urgent need for innovative approaches to combat these illicit activities.

By leveraging advanced analytics and big data techniques to analyze vast amounts of transaction data, our project seeks to stay ahead of evolving fraud schemes and enhance the effectiveness of detection efforts. Identifying patterns indicative of fraud within massive datasets is crucial for preemptively flagging suspicious activities and preventing financial losses. Furthermore, understanding correlations between transaction features and detecting potential money laundering can provide valuable insights for refining risk assessment models and strengthening regulatory compliance measures. Moreover, analyzing temporal patterns, including transaction volume spikes, enables us to uncover subtle indicators of money laundering activities that may evade traditional detection methods. Detecting and disrupting these illicit activities in real-time not only mitigates financial risks for institutions but also contributes to broader efforts to combat organized crime, terrorism financing, and other illicit activities that exploit the financial system for nefarious purposes.

Overall, our project aims to contribute to the ongoing fight against financial fraud by leveraging cutting-edge analytics and big data techniques to identify and disrupt patterns of money laundering. By doing so, we not only protect the integrity of financial markets but also uphold the principles of transparency, accountability, and trust that underpin a healthy and resilient financial ecosystem.

<br><br>

<img width="1506" alt="Screenshot 2024-05-02 at 01 55 06" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/6e1e8f30-f655-4597-967e-9cb5f4305434">


<br><br>

## **Data Visualization**

<br>

### **What Does the Trend in Daily Laundering Amounts Reveal Over Time?**

<br>

<img width="772" alt="Screenshot 2024-05-02 at 02 04 47" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/ed8c5be8-db5e-4b39-8b12-cd40d01bb9b8">

Answer: The 'Laundering Amount Over Time' chart displays data points on a line graph, where each point represents the total amount laundered per day. These are plotted as dots connected by lines to illustrate the trend over time. The chart visually represents the daily changes in the total amount involved in laundering activities within the sampled dataset.

<br><br>

#### **What is the Proportional Distribution of Different Money Laundering Patterns Within Transaction Cycles?**

<br>

<img width="289" alt="Screenshot 2024-05-02 at 02 05 28" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/9ef04fc7-1492-4b63-b7fc-488ccde3feb2">

<img width="677" alt="Screenshot 2024-05-02 at 02 06 05" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/e5441c81-63b0-404d-9fe8-18a36c46df3b">

<br>

Answer: The pie chart presented above shows the distribution of transactions across different money laundering patterns within a cycle. Each segment's size reflects the proportion of transactions that fall under each laundering pattern type, with labels such as "STACK," "SCATTER-GATHER," "CYCLE," "FAN-IN," "FAN-OUT," "GATHER-SCATTER," "BIPARTITE," and "RANDOM." The presence of these labels helps in identifying the various methods of money laundering detected in the dataset. It appears that the laundering pattern types are relatively evenly distributed in the sampled data, with no single type dominating the chart. This suggests that, within the dataset sampled, there is a diverse range of money laundering patterns employed, rather than a concentration on any particular method. It's an indication that the entities involved in money laundering are using a variety of techniques to conduct their illicit activities.

<br><br>

**What is the breakdown of transactions by currency and laundering type?**

<br>

<img width="680" alt="Screenshot 2024-05-02 at 02 07 37" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/07e700fc-583a-4731-80e3-8461682b78d0">

<br>

Answer: Based on the chart provided, it's evident that within laundering-related transactions, US Dollars and Euros are the predominant currencies. Remarkably, within these currencies, laundering types such as STACK, SCATTER-GATHER, and GATHER-SCATTER demonstrate substantial prevalence. Additionally, it can be observed that the laundering type SCATTER-GATHER appears in almost all currencies, highlighting its widespread occurrence. Therefore, emphasis on addressing these types of money laundering could be beneficial.

<br><br>

**What is the trend regarding at what time most money laundering transactions occur?**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 08 34" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/0ddba158-d5e9-4198-8744-fee0ad8987da">

<br>

Answer: This graph shows the number of transactions for each hour of the day. The horizontal axis (x-axis) represents the 24 hours of the day. The vertical axis (y-axis) represents the number of transactions. From the graph, we can see that the highest number of money laundry transactions is around 13:00 (1 PM), while the hours late at night and early in the morning show fewer transactions, as shown by shorter bars. An interesting observation is that money laundering transactions reach their peak at 5 AM before reaching the next peak in the afternoon.

<br><br>

**What is the range of transaction volume for each currencies involved in laundering?**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 09 01" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/5fa12661-5cdd-4599-b95f-85ca141a446d">

<br>

Answer: In the above graph, we have gathered data for the top 5 currencies involved in laundering activities, ranking them based on their transaction volume. The plotted currencies—US Dollar, Euro, Ruble, Yuan, and Yen offers insight into the distribution of transaction volumes within the dataset. The width of each violin plot segment reflects the prevalence of each currency within the dataset. Notably, the US Dollar appears to have a broader spread compared to the other currencies. Conversely, the Ruble has the narrowest width, indicating its relatively minor presence in the laundering activity dataset. The Yen displays an average transaction volume exceeding 100 billion units. On the other hand, the US Dollar, despite its widespread presence, showcases an average transaction volume hovering around 100 million units. By analyzing the details of transaction volume and prevalence, this visualization provides valuable insights into the distribution of laundering activities among the top 5 currencies.

<br><br>

**On which day of the week do fraudulent transactions peak, and what are the potential strategies to combat this?**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 09 46" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/7a69f8c5-8161-4cdc-8673-0f2c8a678c9e">

<br>

Answer: The plot reveals a spike in fraudulent transactions on Saturdays. This trend could be attributed to potential lower vigilance due to weekend staffing. Addressing this might include enhanced monitoring with tools to detect fraud patterns, using anomaly detection to flag irregularities, ensuring sufficient weekend staff, implementing real-time analysis to intercept suspicious activities, and educating customers on fraud risks. Proactively adjusting strategies can help institutions safeguard against heightened weekend fraud risks.

<br><br>

**What patterns can be observed in transactions throughout the day?**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 10 34" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/a27452bd-4238-48fa-983a-a6e16ab4f62a">

<br>

Answer: The chart shows two key transaction trends throughout the day. There's a significant rise in the number of transactions around noon, possibly aligning with peak business hours. Meanwhile, the average transaction value remains consistent, except for a pronounced increase at 3 PM, which does not coincide with the peak number of transactions. This discrepancy at 3 PM could be significant for fraud detection, signaling unusual, high-value transactions. This exceptional spike at an off-peak hour might necessitate further investigation for potential fraud or money laundering.

<br><br>

**Distribution of fraud and non fraud transactions across different currencies**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 11 15" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/166cdf2a-85f6-4876-a2e4-5171e6e6f730">

<br>

The graph distinguishes between fraudulent transactions (depicted in red) and non-fraudulent transactions (depicted in blue). It's notable that the number of transactions is evenly spread out across currencies, with USD and Euro showing the highest transaction volumes. Despite the even distribution, there's a significant spike in the average transaction value for both USD and Euro. This spike could indicate that fraudulent activities are more prevalent in transactions involving these currencies, possibly due to their widespread use and higher values, making them attractive targets for fraudulent activities. Further investigation into the nature of these transactions could provide insights into why USD and Euro transactions are particularly susceptible to fraudulent activities.

<br><br>

**How do perpetrators of money laundering typically change currency and payment format?**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 12 00" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/2eced111-1871-4290-90bf-338463f6c3ca">

<br>

Answer: From the graph, we can see the visualization of one example of the longest transaction chain in one cycle, which consists of 24 transactions in one cycle with the "Random" Money Laundering type. From the graph, we observe that the transaction perpetrator carried out transactions in cross-currency several times, namely in US Dollar, Euro, and UK Pound, to obscure them from the detection of that suspicious transaction.

<br><br>

**Interrelationships between different transaction features within laundering networks**

<br>

<img width="716" alt="Screenshot 2024-05-02 at 02 13 03" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/62e82e28-ff86-4604-a0e6-ec1d6d2ffe00">

<br>

Answer: The network graph offers a visual representation of the intricate relationships between sender and receiver banks, along with the associated currency and transaction types utilized in each transaction. In this specific depiction, a sample of rows from the dataset is employed to unveil underlying patterns. As observed in the graph, transactions originating from bank 0243028 are directed towards bank 0231993, denominated in USD, followed by subsequent transfers to bank codes 009927 and 0099479, eventually being converted into UK Pound. Notably, the entire sequence of transactions is facilitated through the ACH transaction type, showcasing a clear flow of funds and currency conversions along the banking network. This visualization aids in understanding the complex web of financial transactions and highlights the pathways through which funds are transferred and currencies are exchanged among various banks.

<br><br>

**Evolution of laundering patterns over time**

<br>

<img width="792" alt="Screenshot 2024-05-02 at 02 13 49" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/1e0166ee-9c41-4b50-ac75-9e5d5fd7c387">

<br>

Answer: The graph provides a comprehensive visualization of transaction dynamics across seven distinct timestamps within the dataset, capturing the evolution of each transaction over time. Various transaction details, including sender and receiver bank information, receiving currency, and payment format, are meticulously plotted along different axes. Each timeline is represented by uniquely colored lines, showcasing the pattern observed for transactions at each timestamp. For instance, a notable case illustrated in the graph involves a transaction initiated from sender bank 013119, which is received by bank 02335362. This transaction occurs in the ACH format, with the currency involved being EURO. Such visualizations offer valuable insights into the sequential flow of transactions, enabling analysts to discern patterns, identify trends, and gain a deeper understanding of the transactional behavior within the dataset.

<br><br>

**Which money laundering typology involves the most bank accounts, and what does this suggest about the complexity of these schemes?**

<br>

<img width="799" alt="Screenshot 2024-05-02 at 02 14 46" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/3d10a9fd-5461-4d4b-9fd6-407d86187b1e">

<br>

Answer: The bar chart demonstrates that the "Scatter-Gather" and "Gather-Scatter" typologies involve the most distinct bank accounts compared to other types. This suggests that these methods of money laundering are more complex and possibly more organized, as they involve the distribution and collection of funds across many accounts. The complexity of these schemes may make them harder to detect and could indicate a more widespread network of collusion. It is important for financial institutions to pay special attention to these patterns in transactions to effectively combat money laundering.

<br><br>

**What does the variation in cycle duration reveal about different money laundering typologies?**

<br>
 
<img width="803" alt="Screenshot 2024-05-02 at 02 15 38" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/368b6379-7f44-430d-8370-6c6c1cf5af5a">

 <br>
 
Answer: The graph presents the average, minimum, and maximum duration of money laundering cycles for various typologies. The "Gather-Scatter" typology shows a significant variation, with cycle durations ranging from a few days to over two months, suggesting highly irregular patterns. This variability could indicate the use of sophisticated techniques designed to evade detection. In contrast, typologies like "Fan-in" and "Fan-out" display shorter and more consistent cycle durations, potentially reflecting simpler or more straightforward methods. The broad range in cycle durations for certain typologies underlines the need for dynamic monitoring systems that can adapt to the diverse timings of these illicit activities.

<br><br>

**How do different money laundering typologies distribute across various transaction amount ranges?**

<br>

<img width="803" alt="Screenshot 2024-05-02 at 02 16 25" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/ecfe2b40-8757-4fd0-85be-c80cc68bde9f">

<br>

Answer: The chart demonstrates a prevalence of smaller transactions within the ' 0−
 3000' range across various laundering methods, likely a strategy to evade detection by staying under the radar of regulatory thresholds. Typically, as the transaction value increases, the occurrence of transactions tends to decrease due to heightened visibility and risk. However, there is a notable increase in transactions within the '$21001+' bracket, implying that for substantial sums, launderers may opt for significantly higher amounts, possibly to optimize the laundering process or to accommodate the volume of illicit funds. This spike at high transaction levels, especially in "Scatter-Gather" and "Stack" methods, suggests a preference for these typologies when handling large amounts of money. The data underscores the importance of thorough monitoring across all transaction levels, tailored to the nuances of different laundering techniques.

<br><br>

**What is the distribution of Cross-Currency Transaction among the Money Laundering transaction?**

<br>

<img width="804" alt="Screenshot 2024-05-02 at 02 17 31" src="https://github.com/yachu1005/Big-Data-Solutions-for-Combating-Financial-Fraud/assets/145074370/97118ca8-c5dc-4c92-a426-cc78e1669ed7">

<br>

Answer: Based on the graph, we can see that the most common cross-currency transaction in the transactions is Euro-US Dollar, followed by Yen-US Dollar, Euro-Yuan, US Dollar-Yen, and other currency pairs. Of these cross-currency transactions, the most prevalent money laundering method is STACK. This could be because STACK money laundering type typically involves multiple layers of transactions to further obscure the source of funds and changing currencies will adds another layer of complexity for the stack to the laundering process, making it harder to follow the money trail.

<br><br>

## **Future Improvement**

For future improvement in the detection and analysis of money laundering, integrating additional data sources could provide significant benefits. Incorporating diverse data such as real-time transaction feeds, geographic information, and external watchlists could enrich the analysis, allowing for the identification of nuanced patterns and correlations not visible through transaction data alone. Furthermore, experimenting with advanced machine learning models, including ensemble methods, deep learning networks, or anomaly detection systems, could enhance detection rates and reduce false positives. Expanding the temporal analysis to cover longer periods and conducting comparative year-over-year reviews might also yield insights into long-term trends and help predict future laundering activities based on past patterns. Moreover, developing a collaborative framework where multiple financial institutions can share insights and data, while respecting privacy norms, would lead to a more comprehensive view of money laundering tactics. Lastly, continuously updating analysis techniques to align with new regulatory requirements and emerging financial instruments, like cryptocurrencies, can help stay ahead of launderers who adapt quickly to the changing financial landscape.

<br><br>

## **Conclusion**

This comprehensive analysis of money laundering transactions using big data analytics has illuminated several key aspects of financial fraud. Our findings emphasize the importance of transaction timing and methods of currency conversion as crucial elements in laundering schemes. Notably, peak periods for laundering activities were identified, providing critical insights for financial institutions to enhance their monitoring systems during these times. Our study also uncovered the predominance of certain currencies and transaction methods in laundering processes, with the USD and Euro being particularly prominent due to their global acceptance and ease of use in large-scale transactions. Furthermore, sophisticated laundering patterns like "Scatter-Gather" and "Cycle" typologies were prevalent, indicating that launderers employ complex strategies to evade detection. The use of machine learning models aimed to enhance detection capabilities, though challenges like data imbalance limited the effectiveness of our initial models. However, the insights gained pave the way for further refining these models and incorporating advanced analytical tools. Moving forward, building on these insights will be crucial. By implementing the suggested improvements and integrating broader data sets, we can develop more robust defenses against money laundering. This endeavor will not only help protect the integrity of financial systems but also contribute to a broader understanding of financial crimes and their prevention mechanisms. These efforts represent a step toward a more secure and transparent financial environment, highlighting the pivotal role of data analytics in combating financial fraud.


