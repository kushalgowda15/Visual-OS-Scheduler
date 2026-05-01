# Visual OS Scheduler

A Python-based simulator for visualizing CPU scheduling algorithms. This project provides a graphical interface to analyze how different scheduling strategies execute processes over time.

---

## Overview

This application allows users to:
- Simulate common CPU scheduling algorithms  
- Load or generate process datasets  
- Visualize execution timelines using charts  
- Compare algorithm behavior interactively  

---

## Algorithms Implemented

- First Come First Serve (FCFS)  
- Shortest Remaining Time Next (SRTN)  
- Round Robin (RR)  
- Highest Priority First (HPF)  

---

## Tech Stack

- Python 3  
- Tkinter (GUI)  
- Matplotlib (Visualization)  
- NumPy  

---

## Project Structure

```
Visual_OS_Scheduler/
├── scheduler.py
├── process_generator.py
└── testcases/
    ├── Generator Samples/
    └── Scheduler Samples/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/visual-os-scheduler.git
cd visual-os-scheduler
```

Install dependencies:

```bash
pip install matplotlib numpy
```

---

## Usage

### Run Scheduler

```bash
python scheduler.py
```

### Run Process Generator

```bash
python process_generator.py
```

---

## Input Format

### Scheduler Input

```
<number_of_processes>
<process_id> <arrival_time> <burst_time> <priority>
```

Example:

```
3
1 0 5 2
2 2 3 1
3 4 1 3
```

---

### Generator Input

```
<number_of_processes>
<mean_arrival> <std_arrival>
<mean_burst> <std_burst>
<lambda_priority>
```

---

## Features

- Interactive GUI for simulation  
- Graphical timeline visualization  
- Custom input support  
- Random process generation  

---

## Future Improvements

- Add more scheduling algorithms (e.g., Multilevel Queue, MLFQ)  
- Include performance metrics (waiting time, turnaround time)  
- Export results to files  
- Improve UI/UX  

---

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.

---

## License

This project is intended for educational use. Add a license if distributing publicly.
