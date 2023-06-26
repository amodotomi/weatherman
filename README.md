# weatherman

weatherman is a simple weather app made with native javascript

u can find it here: https://amodotomi.github.io/weatherman

## Installation

- to clone the repo

```bash
git clone https://github.com/amodotomi/weatherman
```

## Usage
- you have to have your openweather api key to use it
- paste your api key in api.js file (js folder)
  
example: 
```
export const getWeatherData = async (city) => {
    try {
        const response = await fetch(`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=633f35fdf4df62e35d09ia55b9148165&lang=en&units=metric`);      // example api key (have to be your openweather api key)

        return await response.json();

    } catch (error) {
        console.error(error);
    }
};
```

- then you just need to start a server on localhost and enjoy !

## that's all! feel free to use! ^_^
## Contributing

- Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

- Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
