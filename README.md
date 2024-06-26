# moon

A **simple** CLI built in Go that fetches weather information using the OpenWeather API.

## Features

- Fetches current weather data for a specified city.
- Displays temperature, humidity, weather description, and wind speed.

## Prerequisites

- An API key from [OpenWeather](https://openweathermap.org/api)

## Installation

1. Clone the repository:
    ```bash
    git clone git@github.com:leanghok120/moon.git
    ```
2. Navigate to the project directory:
    ```bash
    cd moon/cmd/moon
    ```
3. Edit the main.go and add your OpenWeather api key:
    ```go
    api_key = "your Openweather api key"
    ```

5. Install moon
    ```bash
    go install .
    ```

6. Now you have moon installed
    ```bash
    moon -c antarctica
    ```

## Usage

Fetches weather info about city

```bash
moon -c london
```

Fetches weather info about country

```bash
moon -c netherlands
```

### More information

If you want to fetch more weather information, you can use the -L flag

```bash
moon -L -c netherlands
```

## Example

```bash
$ moon -c london
Location: London
Temperature: 15 celsius
Humidity: 82%
Description: light rain
Wind Speed: 4.1 m/s
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For questions or support, please open an issue on the GitHub repository.
