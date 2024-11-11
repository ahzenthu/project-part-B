# start here
Repository Proposal

User Group: data scientists, urban planners, transportation analysts, policymakers, supply chain/distribution analysts, etc.

Information Needs: access to reliable structured data for better transportation routes, traffic pattern analytics, and infrastructure planning.

Use cases:
1. Traffic analysis: using the data to analyze when and where traffic flows in many regions
2. Infrastructure planning: using the data to plan the most efficient roads
3. Public safety: Identify high-risk accident zones or improve emergency services times by finding better routes

System Specifications
DataBase: PostgreSQL with PostGIS for spatial data support, also MongoDG for JSON structured data and Google BigQuery for large scale querying.
Access: Having a security system in place and adhere to data privacy laws.

Objectives of the System:
Provide well-organized, diverse, up to date GPS data for many different purposes. All while meeting data privacy and legal standards.

Development plan:
1. Data Ingestion, collecting raw data from multiple reliable sources.
2. Metadata sorting, apply whatever the agreed upon metadata template to the raw data (kinda like data cleaning then sorting)
3. Reposition, move the cleaned and sorted data into the clean github data files
4. Analysis, use the data!

Testing: have data scientists use the clean data to analyze it, or build machine learning model to predict data, depends on your goal with the data. share through github with readme.md for clearness.

TimeLine: 2-3 weeks for the data collection/cleaning, 3-4 weeks for deep testing (depending on the goal of course)

Skills Needed: general domain knowledge, Data enginerring for the data ingestion, data scientists for the cleaning, and analysis.
