# Weekly Step Analysis  

## Introduction  
Tracking daily steps is a great way to monitor physical activity and compare progress over time. This analysis examines the number of steps walked each day over a week and compares the data with friends to observe trends and motivation levels.  

## Methodology  
1. **Data Collection:** Step data was collected using a fitness tracker.  
2. *Comparison:* Daily steps were compared against past weeks and friends’ data.  
3. Analysis was performed using `Python` for data visualization.  

## Data Summary  
Below is a table summarizing the step count for the past week:  

| Day       | Steps Taken | Friend's Steps |
|-----------|------------|---------------|
| Monday    | 8,000      | 7,500         |
| Tuesday   | 7,500      | 8,000         |
| Wednesday | 9,000      | 7,800         |
| Thursday  | 6,500      | 8,500         |
| Friday    | 10,000     | 9,200         |
| Saturday  | 12,500     | 11,000        |
| Sunday    | 11,000     | 12,300        |

## Key Observations  
- **Peak Activity:** The highest number of steps was recorded on *Saturday*.  
- **Low Activity:** *Thursday had the lowest step count.*  
- **Friend Comparison:** My step count was generally higher, except on Thursday.  

## Code Used for Analysis  
The following Python snippet was used for visualizing the step count:  

[Google Fit](https://www.google.com/fit/)
![Step Count Visualization](https://example.com/steps-chart.jpg)
> 

```python
import matplotlib.pyplot as plt  

days = ["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]  
steps = [8000, 7500, 9000, 6500, 10000, 12500, 11000]  

plt.plot(days, steps, marker='o', linestyle='-', color='b')  
plt.xlabel("Days")  
plt.ylabel("Steps")  
plt.title("Steps Walked Over the Week")  
plt.show()  

