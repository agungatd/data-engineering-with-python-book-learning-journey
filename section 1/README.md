# Section 1 - Building Data Pipeline - Extract, Transform, and Load (ETL)

## Chapter 1, What is Data Engineering
Data engineering, at its simplest, is the creation of pipeline to move data from one source or format to another. This may or may not involve data transformations, processing 
engines, and the maintenance of infrastructure. 

Data engineers use a variety of programming languages, but most commonly Python, 
Java, or Scala, as well as proprietary and open source transactional databases and data 
warehouses, both on-premises and in the cloud, or a mixture.

Data engineers need to 
be knowledgeable in many areas – programming, operations, data modeling, databases, 
and operating systems.

## Chapter 2, Building Our Data Engineering Infrastructure
In this chapter, I learned how to install and configure many of the tools used by data 
engineers. I now have two working databases – Elasticsearch and PostgreSQL – as well as two tools for building data pipelines – Apache NiFi and Apache Airflow

**Tools summary:**
* **Apache NiFi:** <br>
  NiFi allows you to build data pipelines using prebuilt processors that you can configure for your needs. You do not need to write any code to get NiFi pipelines working. It also provides a scheduler to set how frequently you would like your pipelines to run. In addition, it will handle backpressure – if one task works faster than another, you can slow down the task.
* **Apache Airflow:** <br>
  Apache Airflow performs the same role as Apache NiFi; however, it allows you to create your data flows using pure Python.
* **Apache Elasticsearch:** <br>
  Elasticsearch is a search engine. In this book, it will be used as a NoSQL database. also using Kibana as its GUI.
* **PostgreSQL:** <br>
  PostgreSQL is an open source relational database. It compares to Oracle or Microsoft SQL Server. In this book, it will be the relational database of choice.
## Chapter 3, Reading and Writing Files

## Chapter 4, Working with Databases

## Chapter 5, Cleaning and Transforming Data

## Chapter 6, Building a 311 Data Pipeline

## Chapter 7 - 11, Continue to Section 2
[Section 2 Relative Path](data-engineering-with-python-book-learning-journey/blob/main/section%202/README.md)

[Section 2](https://github.com/agungatd/data-engineering-with-python-book-learning-journey/blob/main/section%202/README.md)