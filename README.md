# MongoDB Atlas Performance Analysis

Cloud-based database performance analysis using MongoDB Atlas, Apache JMeter and Python.

---

## Project Overview

This project presents the design and evaluation of a cloud-based MongoDB environment for database performance analysis.

The solution combines cloud computing, NoSQL databases, REST API development, performance testing and statistical analysis.

---

## Dataset

Netflix Movies and TV Shows Dataset

- titles.csv
- credits.csv

---

## Technologies

- MongoDB Atlas
- Python
- Google Colab
- Apache JMeter
- Flask
- ngrok
- Pandas
- NumPy
- SciPy

---

## Project Workflow

1. Prepare dataset
2. Create MongoDB Atlas cluster
3. Import collections
4. Build Flask API
5. Execute Apache JMeter performance tests
6. Analyse results
7. Verify statistical hypothesis

---

## Performance Tests

### Test 1

Comparison of:

- count_documents() on titles collection
- count_documents() on credits collection

### Test 2

Comparison of:

- find(limit=1000) on titles collection
- find(limit=1000) on credits collection

Statistical analysis:

- IQR
- Shapiro-Wilk Test
- Levene Test
- Student's t-test
- Welch Test

---

## Results

The experiments confirmed statistically significant differences in database response times.

Larger collections required longer execution times, demonstrating the impact of dataset size on MongoDB performance.

---

## Skills Demonstrated

- Database Performance Testing
- MongoDB Atlas
- Cloud Computing
- Python
- REST API Development
- Apache JMeter
- Statistical Analysis
- Data Engineering