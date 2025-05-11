# Route-Finder
The Route Finder App helps users find the shortest route between two locations using Dijkstra's Algorithm. Built with simplicity and efficiency in mind, the app is designed to showcase the power of algorithmic problem-solving in real-world scenarios.

## Features

- **Shortest Route Calculation**: Finds the optimal path between two places.
- **Interactive Map**: Visual representation of locations and routes.
- **User-Friendly Interface**: Simple and intuitive design for easy navigation.
- **Algorithm Visualization**: Highlights the steps of Dijkstra's Algorithm.
  
## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Map Integration**: Mapbox API
- **Algorithm**: Dijkstra's Algorithm for shortest path calculation

## Installation

Follow these steps to set up and run the application locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Route-Finder.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Route-Finder
   ```

3. **Install Dependencies**:
   ```bash
   pip install flask requests heapq
   ```

4. **Set Up Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add your Mapbox API token:
     ```env
     MAPBOX_API_TOKEN=your_mapbox_api_token_here
     ```

5. **Run the Application in your root directory**:
   ```bash
   python app.py
   ```

6. **Access the App**:
   Open Live Server from VS code

## Usage

1. Enter the starting and destination locations in the input fields.
2. Click the "Find Route" button to calculate the shortest path.
4. View the calculated route on the map and the total kilometer to complete the travel.
5. You may also find the nearby restaurents, tolls and hospitals

## Future Improvements

- Add support for multiple routing algorithms.
- Include real-time traffic data.
- Implement user authentication for saving favorite routes.
- Optimize for mobile devices.
