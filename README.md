I wanted to improve my Power BI skills — but not by following another perfectly polished tutorial.

Many online tutorials showcase beautiful dashboards. However, because the data is already clean and structured, they often skip the messy, real-world challenges that analysts actually face. They also tend to revolve around generic topics like sales or HR analytics.

So I decided to start from scratch — with raw data, real inconsistencies, and a problem worth solving.



## 1. Data Collection

To find a dataset that genuinely interested me, I explored multiple options on Kaggle. After reviewing several possibilities, I chose the [**Food Delivery Dataset**](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset/data?select=train.csv), as it offered a more operational perspective compared to traditional sales or HR dashboards.

This dataset stood out because it focuses on delivery performance, delays, weather impact, and customer ratings — all critical components of logistics and supply chain analytics.

Instead of building another revenue dashboard, I wanted to explore operational efficiency.



## 2. Data Preprocessing (Python)

As part of my workflow, I used Python for preprocessing before importing the data into Power BI.

I loaded the dataset into Jupyter Notebook and performed the following steps:

- Removed duplicates
    
- Handled null and empty values
    
- Converted columns into appropriate data types (e.g., datetime, numeric)
    
- Renamed columns for clarity and consistency
    
- Removed unnecessary fields that did not contribute to the analysis
    

Cleaning the dataset significantly improved readability and analytical clarity. Once structured properly, patterns started becoming more visible.

_(You can find the full preprocessing notebook here: [https://github.com/Me-Pasha/food-delivery-power-bi-dashboard/blob/main/Data_Preprocessing_Food_Delivery_Dataset.ipynb])_



## 3. Designing the Dashboard

After cleaning the data, the next step was turning insights into a structured, stakeholder-focused dashboard.

Rather than jumping directly into visuals, I followed a structured approach.

<img src="https://github.com/Me-Pasha/food-delivery-power-bi-dashboard/blob/main/dashboard-making-workflow.png" width="200" />

### Step 1: Defining the Stakeholder & Persona

Before designing anything, I asked a simple question:

> Who is this dashboard for?

This question helps narrow down focus and prevents creating a dashboard overloaded with irrelevant metrics.

For this dataset, I identified the primary stakeholder as:

**Operations / Supply Chain Team**

Then I mapped out the types of questions they would likely ask:

- Where are we losing time in the delivery process?
    
- Is the delay happening before pickup or during delivery?
    
- Does weather impact delivery performance?
    
- How does delivery performance affect customer ratings?
    

This clarity helped guide the entire dashboard structure.



### Step 2: Selecting Key Performance Indicators (KPIs)

To avoid overwhelming the user, I selected 3–6 focused KPIs that directly address stakeholder concerns:

- **Average Total Time Taken**
    
- **Average Restaurant Delay**
    
- **Average Delivery Delay**
    
- **Average Customer Rating**
    

These KPIs serve as high-level performance indicators, allowing stakeholders to quickly assess operational efficiency before diving deeper into analysis.



### Step 3: Choosing Charts & Visual Hierarchy

Each visual was selected based on how effectively it explains the KPI.

The guiding principle was:

> Clarity and actionability over visual complexity.

To enhance user experience, I structured the dashboard using F-pattern and Z-pattern layouts. This ensures:

- High-priority KPIs appear at the top
    
- Supporting visuals follow natural reading flow
    
- More complex charts are placed lower, where users can spend focused attention
    

The goal was not to impress with visuals — but to guide decision-making.



### Visual Inspiration & Design Approach

| Earlier Basic Dashboard                                        | Insipiration (Dribble)                                        |
| ---------------------------------------------------------------| ------------------------------------------------------------- |
| ![Earlier Basic Dashboard](https://github.com/Me-Pasha/food-delivery-power-bi-dashboard/blob/main/Basic-power-bi-dashboard.png)| ![Inspiration Dribble](https://github.com/Me-Pasha/food-delivery-power-bi-dashboard/blob/main/original-food-delivery-inspiration.webp) |

**FINAL**
![Final Dashboard](https://github.com/Me-Pasha/food-delivery-power-bi-dashboard/blob/main/Food-dashboard-Power-BI.png)

As someone still developing design intuition, I didn’t want to overcomplicate aesthetics.

I researched clean, minimal dashboard designs and drew inspiration from a calm, balanced layout I found online. I adapted:

- A muted, professional color palette
    
- Subtle background tones
    
- Consistent spacing and alignment
    

After several iterations, the design evolved into something uniquely mine — simple, focused, and functional.



## Key Takeaways from This Project

This project wasn’t just about Power BI.

It taught me:

- Clean data is the foundation of meaningful analysis
    
- Stakeholder clarity prevents dashboard clutter
    
- Good dashboards answer questions — they don’t just display numbers
    
- Simplicity often communicates better than complexity
    

Most importantly, I learned that working with imperfect, real-world data is where actual analytical growth happens.
