# Cloud-Service-Models-Case-Study
SDG Goal: SDG 4 – Quality Education

Project Description

This project analyzes a real-world dataset of learning resources and classifies them into Cloud Service Models:

SaaS (Software as a Service): End-user ready content like videos, tutorials, webinars, and documents.

PaaS/IaaS (Platform/Infrastructure as a Service): Resources that provide underlying platforms, data sets, APIs, code repositories, or cloud platforms.

By understanding the distribution of resources across these models, educators and organizations can better design, allocate, and consume learning resources in a cloud environment.

Dataset

The project uses the Learning Resources Database which contains columns like:

Resource Name – Name of the learning resource

Type – Type of resource (Video, Document, API, etc.)

Format – Resource format (PDF, Webinar, Code, etc.)

Methodology

Data Loading: Load the dataset using Pandas.

Classification: Apply a keyword-based logic to classify each resource into SaaS, PaaS/IaaS, or Unclassified.

Quantitative Analysis: Count the number of resources per cloud service model and calculate percentages.

Visualization: Generate bar charts and pie charts to display distribution.

Qualitative Analysis: Extract examples of resources for each cloud service model to illustrate the classification.

Visualization

Bar Chart: Shows the count of resources per cloud service model.

Pie Chart: Shows the percentage distribution of resources among cloud service models.

Tools & Libraries

Python 3.x

Pandas (for data processing)

Matplotlib & Seaborn (for visualizations)

Optional: Altair (for interactive visualizations)

Insights

The majority of resources are classified as SaaS, indicating most learning materials are end-user ready content.

A smaller portion may fall under PaaS/IaaS, representing platform-oriented resources like APIs, code repositories, or datasets.

This classification helps educators and organizations understand the nature of learning resources and optimize cloud usage.

How to Run

Clone the repository.

Install required libraries:

pip install pandas matplotlib seaborn


Place the dataset (Learning_Resources_Database Dataset.csv) in the same folder.

Run the Python script to generate classification and visualizations.
