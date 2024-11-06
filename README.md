# Task Tracker by Michael Deming

A basic but intuititve Task Tracker application. 

Tasks are given a *days_to_complete* (int) when created. This, in combination with 
the *date_created* (date via datetime), sets a *date_due* (date via datetime). Tasks are sorted/ranked by their *days_to_complete* in ascending order. Future updates will utilize *date_due*. 

Tasks priorty is set by *days_to_complete* automatically:

- 1 -> 3 Days to Complete == Priority 1
- 4 -> 6 Days to Complete == Priority 2
- 7+ Days to Complete == Priority 3

Tasks can be visually filtered by priority grouping when displaying tasks.

## Requirements

- Python 3.8 or higher

## Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/yourusername/task-tracker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd task-tracker
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the app:
    ```bash
    python task-tracker.py
    ```

## Acknowledgements

- **Youtube Stream Chat & Discord**: Thanks to those who provided input and assistance.


