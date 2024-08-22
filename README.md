# real_estate_data_visualization

This project creates an interactive map visualization of California housing data using Python, Folium, and scikit-learn.

## Description

This script fetches California housing data, processes it, and generates an interactive HTML map. Each data point is represented by a circle marker on the map, with the size and color of the marker indicating different aspects of the housing data.

## Features

- Fetches California housing data using scikit-learn
- Creates an interactive map using Folium
- Visualizes median house value using color gradients
- Represents average room number using marker size
- Includes a popup with detailed information for each data point
- Adds a mini-map for easy navigation

## Requirements

To run this project, you need to have Python installed along with the following libraries:
- pandas
- matplotlib
- scikit-learn
- folium

You can install these libraries using pip:
- pip install pandas scikit-learn folium matplotlib

## Usage

1. Clone this repository:
- git clone https://github.com/timothymwine/real_estate_data_visualization.git

2. Navigate to the project directory:
- cd real_estate_data_visualization

3. Run the script:
- python main.py

4. Open the generated `real_estate.html` file in a web browser to view the map.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.