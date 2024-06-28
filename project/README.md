# FPGA Development Board Recommender System

This project implements a recommender system for selecting FPGA development boards based on user-specified hardware requirements. It's designed to assist in choosing the most suitable board for prototyping projects in a SAPR laboratory environment.

## Project Components

1. `app.ipynb`: Jupyter Notebook containing the interactive application code.
2. `dataset.xlsx`: Excel file with detailed specifications of various FPGA development boards.
3. `documentation.pdf`: Comprehensive project documentation in Russian.

## Features

- Interactive user interface built with ipywidgets in Jupyter Notebook
- Customizable selection of board characteristics
- Intelligent scoring system to match user requirements with board specifications
- Support for multiple FPGA board models including DE1-SoC, DE10-Lite, DE10-Standard, DE10-Nano, and DE0-CV

## How It Works

1. Users select desired characteristics through dropdown menus.
2. The system evaluates available boards based on user input.
3. The most suitable board is recommended based on a scoring algorithm.

## Technologies Used

- Python
- pandas for data manipulation
- ipywidgets for interactive UI elements
- Jupyter Notebook for application deployment

## Getting Started

1. Clone the repository
2. Ensure you have Jupyter Notebook installed with Python 3
3. Install required dependencies: `pip install pandas ipywidgets`
4. Open `app.ipynb` in Jupyter Notebook
5. Run the cells to start the interactive application

## Documentation

For detailed information about the project, including the dataset structure, developer documentation, and user guide, please refer to `documentation.pdf` (in Russian).

