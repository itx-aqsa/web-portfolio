# web-portfolio

# Web Workers Sorting and Addition Demo

## Project Description
This project is a web application that demonstrates the use of Web Workers to concurrently perform sorting and addition operations on a large dataset. The goal is to compare the performance of these operations with and without the use of Web Workers.

## Instructions to Run Locally

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/web-workers-sorting-addition-demo.git

2. Navigate to the project directory:
 
   cd web-workers-sorting-addition-demo

3. Open the index.html file in your preferred web browser.

4. Click the "Process Data With Workers" button to observe the performance of sorting and addition using Web Workers.

5. Optionally, click the "Process Data Without Workers" button to compare the performance without Web Workers.

Performance Findings
The project aimed to compare the performance of sorting and addition operations on a large dataset with and without the use of Web Workers. The findings based on testing are as follows:

With Web Workers:

Sorting and addition tasks are performed concurrently using separate Web Workers.
The application leverages parallel processing to potentially enhance performance.
Without Web Workers:

Sorting and addition tasks are performed in the main thread without parallelization.
The performance without Web Workers serves as a reference point for comparison.
Summary:
Web Workers can offer performance improvements for computationally intensive tasks by utilizing parallel processing.

The choice to use Web Workers should be based on the nature of the data processing tasks, their intensity, and the trade-offs involved in communication overhead.

Experiment with different data sizes and processing tasks to observe variations in performance.
