# Weather App using Flask

This is a simple weather application built using Flask, a lightweight web framework for Python. It fetches weather data from the OpenWeatherMap API based on the user's input city and displays the current temperature, weather description, and an icon representing the weather condition.

## Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/VinayKasani/Weather-App
```

2. Navigate to the project directory:

```
cd Weather-App
```

3. Install the required dependencies using pip:

```
pip install -r requirements.txt
```

## Usage

1. Sign up on [OpenWeatherMap](https://openweathermap.org/) to get an API key.

2. Create a `.env` file in the root directory of the project and add your OpenWeatherMap API key:

```
OPENWEATHERMAP_API_KEY=your-api-key
```

3. Run the Flask application:

```
python app.py
```

4. Open your web browser and navigate to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

5. Enter the name of the city for which you want to check the weather and submit the form.

6. The application will display the current weather information for the specified city.

## File Structure

- **app.py**: The main Python file containing the Flask application code.
- **templates/**:
  - **index.html**: The HTML template for the home page.
  - **weather.html**: The HTML template for displaying weather information.
  - **error.html**: The HTML template for displaying error messages.
- **.env**: Environment file to store sensitive information such as API keys.
- **requirements.txt**: File containing the list of Python packages required for the application.

## Dependencies

- Flask: A micro web framework for Python.
- requests: HTTP library for making requests to APIs.
- python-dotenv: Python module that reads the contents of `.env` files and adds them to the environment variables.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
