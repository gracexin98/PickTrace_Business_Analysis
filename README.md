# PickTrace_Business_Analysis
<b>
Real world data for a real world business. <br>
Applied: Excel, Data Analysis, Business Intelligence Analysis. 
</b>

## Project Background
PickTrace is a software company that helps specialty crop producers manage their employees and payroll systems. For the project, PickTrace President Harrison Steed is looking for an analysis about apple and pear picking across several different apple and pear varieties and several different farms in Washington state.
<br>
PickTrace Company Website : http://picktrace.com/company/

## Data
The data is from PickTrace company website, includes 2020 fruits pickup data in Washington state. 

## 1. What are benchmark estimates of picker productivity for different apple and pear varieties?
Figure 1 shows the apple variety Honey Crisp has highest picker productivity. Pickers can pick 8110 pounds of Honey Crisp in 1 hour. Scarlett has lowest picker productivity, which is 937 pounds per hour. Since the apple piece is counted as 1000 pounds per bin, there is a special case that pickers work several hours and get paid, but picked apples are very small amount of 1000 pounds, and the apple piece is counted as 0. Apple varieties Opal and Sweetie are such a special case, so they are considered as outliers. Figure 2 shows the pear variety Bosc has highest picker productivity, which is 2014 pounds per hour. Green Anjou has lowest picker productivity, which is 1500 pounds per hour.

![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/1.png)
![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/2.png)

## 2. Which producers (farms) have the highest and lowest picker productivities?
There are 6 farms to produce different apple and pear varieties. They all grow apples, but only Farm 1 and 3 produce pears. Figure 3 shows for apples, Farm 6 has highest picker productivity, which is 2098 pounds per hour. Farm 4 has lowest picker productivity, which is 1103 pounds per hour.

Figure 4 states the farms picker productivities of pears. Only Farm 1 and Farm 3 grow pears. Farm 3 has higher picker productivity, which is 3501 pounds per hour. Farm 1 pickers pick 529 pounds of pears per hour.

![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/3.png)
![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/4.png)

## 3. What are the average apple and pear picking costs for different varieties at different farms?
Figure 5 compares the average picking cost for Farm 1-6 for different apple and pear varieties and Figure 6 with exact data. Pickers are paid by piece rate wage instead of hourly wage. For example, in Farm 2, two pickers both pick up 5 bins of Gala. They are paid the same wage, $145, but one worked 3.69 hours and the other worked 8.33 hours. Since the picking costs are related to total pieces, Farm 6 Opal and Sweetie which 0 total piece are considered as outliers. Farm 6 Honey Crisp has extremely high picking cost due to very small amount of total piece. Farm 6 Honey Crisp is not included in Figure 5, and its average picking cost is $13.48/pound.

![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/5.png)
![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/6.png)

## 4. What apple and pear varieties are most profitable? If apple farms are going to plant new orchards, which varieties should they choose?
Figure 7 compares net profit of different apple and pear varieties in dollars per pound. Since limited apple and pear varieties have real price data, price of missing varieties is considered the same as average apple and pear marketing price. Honey Crisp has highest net profit among apple varieties, which is $1.06/pound. Bosc has highest net profit among pear varieties, which is $0.67/pound. No need to worry that Farm 6 Honey Crisp has extremely high picking cost. It only happened in Farm 6. The possible reasons are low picker productivity and report the wrong piece number. Honey Crisp net profit among 6 farms is highest. I will suggest new farm to plant Honey Crisp.

![alt text](https://github.com/gracexin98/PickTrace_Business_Analysis/blob/main/git_graph/7.png)


