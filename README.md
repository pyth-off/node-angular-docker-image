# Node.JS image for Angular

A simple Node.Js image to run your Angular project

## Installation

Clone the repository and then

```bash
docker build -t pythoff/node22.5.1 .
```
Of course, you can tag the image with any name you like.

## Usage

Update the docker-compose file to match your image name.
Make sure you are mapping the correct ports, by default npm runs on 4200.
Adapt your directory mapping to your angular configuration.
Use the .env file to declare environment variables and reference them in the docker-compose.yml if needed.
After that,

```bash
docker-compose up
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
