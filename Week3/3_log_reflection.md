"Staple A averaged 160.89 PKR across the period." | Green | Recomputed via Python `groupby().mean()` | Accepted: Mathematically exact, though skewed by the week 3 outlier.
"The median price of Staple A (112.50 PKR) better represents the typical week than the mean." | Amber | Compared mean vs median and inspected the raw price series. | Accepted: Correct statistical reasoning regarding outlier distortion. |
"Prices rose because of increased fuel transportation costs." | Red | Checked dataset columns (`date`, `item`, `city`, `price`, `unit`). | **Rejected / Flagged:** Fuel and transport data are entirely absent from the dataset; this is an unsupported causal claim. |


Classmate:"I still don't get it. If the mean of Staple A is 160.89 PKR, why do you keep saying the price is actually around 112.50 PKR? Isn't the mean the official mathematical average?"
Me:"Mean is mathematical average, but averages are affected heavily by extreme numvbers in a dataset and can cause alot of deviation in mean so median is better to represent data." 
Classmate:"Oh! So the 1,250 outlier acts like that billionaire in the room?"
Me:"When data has extreme errors median is safe for representing typical price

Reflection
My first draft initially overstepped by implying that the upward price trends were directly driven by broad inflation rates. Looking closely at the data, our descriptive statistics only show what happened to prices over time, not why it happened.
