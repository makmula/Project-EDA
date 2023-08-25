# Aviation Analysis to See which Airplanes you Should Buy

# Business Problem

MACB  company is expanding in to new industries to diversify its portfolio. And are they are interested in purchasing and operating airplanes for commercial and private enterprises.
Which aircrafts have less risk to have accidents?
What are some factors they maybe having accidents?


What are some factors they maybe having accidents?

## The Dataset

Our Data was taken out from a file in Kaggle named ‘Aviation Accident Database & Sypnoses, up to 2023’ which the Data Frame had 90348 rows and  31 columns

## Methods

This project uses mostly cleaning and sorting datasets in order to do descriptive analysis, to gain a description of trends over time. Accidents of airplanes may end up giving us a pattern, and to see the causes of those accidents.

## Results

Though time the numbers of accidents have been decreasing:

![Timeline of accidents](https://github.com/makmula/Project-EDA/blob/master/Image/Timeline%20graph%20Aviation.png)


There has been a positive decrease thoughtout the years. This decrease can be cause by many factors. However at the ended of the line graph 
it shows a little increase of accidents again.

![Engine vs Accidents](https://github.com/makmula/Project-EDA/blob/master/Image/Engines%20to%20accidents.png)

 - Planes with fewer engines are more likely to crash!
 - As you May be able to see in BOEING brand have models with 4 engines.


![Models with more engines]([Models_with_4_or_more_engines.png](https://github.com/makmula/Project-EDA/blob/master/images/Models%20with%204%20or%20more%20engines.png))

The models that have 4 engines or more are 747, the Heaviside2, B17. This airplanes that more engines are made in recent years starting 2015 mostly.

![Accidents vs Month](Months_vs_Accidents.png)

June, July, and August have high accident counts. There are too many flights around this time of the year and this can be a reason why accidents happen more. However, it can be due to the weather.

![Weather vs Accidents](Accidents_by_Weather_.png)

- VMC: Visual flight, clear weather
- IMC : Fly by a flight instrument and is usually in bad weather

  Weather does not influence having an airplane accident, since most accidents happen when vision its clear!

## Recommendations

- Based on the research we've done we recommend the 747, the Heaviside2, B17
- Makes with more engines are the best and safest to buy.
- Having less transit of airplanes  in June, July and August can reduced accidents that were usually happening at this time of the year.
- Planes built in recent years are safer. 

## Next Steps

- Find out where can we get more planes 4 or more engines
- Gather more data on our recommendation as time goes by
- Find out if our planes are commercial or private.

## Repository Structure
├── data
├── images
├── .gitignore
├── Aviation Data Analysis.pdf 
├── Final_Notebook.ipynb
└── README.md
