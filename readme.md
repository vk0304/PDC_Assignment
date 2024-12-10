Name : Vivek Kumar        Roll NO : 21B-179-CS


# PDC Assignment: Parallel and Serial Programming

This project contains implementations of both serial and parallel programming techniques for processing and analyzing student fee data efficiently.

## Overview
The project demonstrates:
- **Serial Programming**:
  - A straightforward approach to process data sequentially.
  - Calculates the most consistent payment day for each student based on fee records.

- **Parallel Programming**:
  - Utilizes Python's `multiprocessing` library for improved efficiency.
  - Splits the data into chunks and processes them in parallel to calculate consistent payment days.

## Files
1. **serial_programming.py**:
   - Implements the serial approach for analyzing student fee payment consistency.
   
2. **parallel_programming.py**:
   - Implements the parallel approach using multiprocessing for better performance on larger datasets.
   
3. **students.csv**:
   - Contains the details of students, including their IDs and other related information.

4. **student_fees.csv**:
   - Contains fee payment records, including payment dates.

## Technologies Used
- Python
- Pandas library
- Multiprocessing library

## Key Features
- Efficient calculation of the most consistent payment day for each student.
- Demonstrates the difference between serial and parallel approaches.

## Usage
1. Ensure all required files (`students.csv` and `student_fees.csv`) are in the project directory.
2. Run either `serial_programming.py` or `parallel_programming.py` to analyze the data.

```bash
python serial_programming.py
# OR
python parallel_programming.py
