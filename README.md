# ABNBCloneV3

ABNBCloneV3 is the third named repository of the Holberton AirBNB Clone projects series. The overarching goal of the series is to learn the tools associated with web development well enough to be able to replicate the popular web platform. The main component of this project is a RESTful API that allows interaction with the main application.

## RESTful API

The API is built using Flask and provides endpoints for managing amenities, cities, places, reviews, states, and users. The API is designed to handle 404 errors gracefully and provides a method for closing storage.

### Key Files

- `api/__init__.py`: Initializes the API.
- `api/v1/views/amenities.py`: Handles all endpoint actions related to amenities.
- `api/v1/views/index.py`: Handles all endpoint actions related to the index.
- `api/v1/views/cities.py`: Handles all endpoint actions related to cities.
- `api/v1/views/places_reviews.py`: Handles all endpoint actions related to place reviews.
- `api/v1/views/users.py`: Handles all endpoint actions related to users.
- `api/v1/views/places.py`: Handles all endpoint actions related to places.
- `api/v1/views/states.py`: Handles all endpoint actions related to states.
- `api/v1/app.py`: This is where the Flask instance is created and configured. It also handles 404 errors and closes the storage.

## How to Run

The application can be started by running the `start_flask()` function in `api/v1/app.py`. The host and port can be configured using the `HBNB_API_HOST` and `HBNB_API_PORT` environment variables, respectively.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Authors

- **Philip Taylor** - [Oggal](https://github.com/Oggal)
- **Chris Stamper** - [ZeroDayPoke](https://github.com/ZeroDayPoke)
- **Allie Tatum** - [actatum88](https://github.com/actatum88)
