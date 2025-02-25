# Process Scheduling Simulator

## Project Overview
This project is a **Process Scheduling Simulator** built using **Streamlit**, **Pandas**, and **Altair**. The tool provides interactive visualization of different CPU scheduling algorithms, allowing users to input processes and simulate their execution.

## Features
- **Visual Representation** of CPU scheduling algorithms
- **User Input** for custom process scheduling
- **Gantt Chart** for execution order visualization
- **Performance Metrics** such as Average Turnaround Time & Waiting Time
- **Interactive UI** with CSS styling and background image support

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/process-scheduling-simulator.git
   cd process-scheduling-simulator
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Dependencies
Ensure you have the following Python libraries installed:
```bash
streamlit
pandas
altair
```

## Usage
- Select a scheduling algorithm from the dropdown menu.
- Enter process details such as **Arrival Time**, **Burst Time**, and **Priority** (if applicable).
- Click **Add Process** to store input.
- Click **Calculate** to simulate scheduling and view results.
- View **Gantt Chart**, **Waiting Time**, and **Turnaround Time** metrics.


## Contributors
- **Muhammad Adeel** - 2022331
- **Hussain Ahmad** - 2022220
- **Mustafa Shah** - 2022407
- **Saud Khan** - 2022533

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to our university and mentors for guiding us through this project!
