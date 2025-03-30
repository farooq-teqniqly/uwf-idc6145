## Project Title: Temporal Congestion Analysis and Predictive Modeling of Ride-Hailing Trips in NYC Using High-Volume FHV Data

## Proposal

The objective of this project is to analyze and predict traffic congestion patterns in New York City using High-Volume For-Hire Vehicle (FHV) trip data from trip providers such as Uber and Lyft<sup>1</sup>. Specifically, it seeks to uncover how trip durations and speeds vary across different times and providers, and to build a predictive model that estimates expected trip duration or congestion likelihood. These insights can aid transportation policy, ride-hailing efficiency, and commuter decision-making.

This project clearly qualifies as a big data problem. The dataset includes over 200 million trip records collected across 12 months of 2024, reflecting high volume. The data is semi-structured, with structured fields but requiring feature engineering and transformation to derive meaningful congestion metrics.

The proposed approach is practical and appropriately scoped—combining distributed processing in PySpark with statistical modeling in R. It involves the Big Data lifecycle phases of:

**Data Processing:** Ingesting 12 monthly Parquet files into PySpark, cleaning the data through filtering and outlier removal, and engineering features such as pickup hour, day, and provider.

**Data Analysis:** Performing temporal aggregations (e.g., average speed per hour or day) to uncover congestion patterns, and using R to develop predictive models, and analyze and visualize the results.

1. **“TLC Trip Record Data.”** *TLC*, [www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). Accessed 30 Mar. 2025.
