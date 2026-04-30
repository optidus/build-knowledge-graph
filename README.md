# 🔗 BigQuery Property Graph Auto-Builder
This notebook automatically converts your existing BigQuery tables into a Property Graph — no manual schema design required.

It uses Gemini to analyze your table schemas, identify the right nodes and edges, generate the graph DDL, and then produce a set of sample GQL questions you can ask immediately.

What you need
* A BigQuery dataset with relational tables
* A short description of your domain
* A few examples of the business questions you want to answer
What you get
* ✅ Automatic node and edge identification with reasoning
* ✅ A CREATE PROPERTY GRAPH DDL statement, ready to run
* ✅ 5 sample GQL queries tailored to your graph and business questions


