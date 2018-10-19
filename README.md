# GeoTrash
A community-driven web application tool that collects different recycle bin location points. During EcoMake 2018 Purdue, a weekend-long engineering design competition centered on sustainability, our team decided to focus on creating a convenient way to recycle. See also the [presentation](https://docs.google.com/presentation/d/1WXI5iPwDKlXD41j7sttsrGVgGEepeZANfk_znRWAIQw/edit?usp=sharing) for this project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
In server.py, the main() function starts the server. Configure your operating system or process manager to run this program to start the server.
```
http_server = tornado.httpserver.HTTPServer(app, ssl_options={
    "certfile": "/your/certificate/",
    "keyfile": "/your/keyfile/",
})
```

### Installing
Run ./server.py to start the server on your local device.

### Additional Information
Here is more information on [running and deploying](https://www.tornadoweb.org/en/stable/guide/running.html?highlight=listen).

## Built With

* [Tornado](https://www.tornadoweb.org/en/stable/) - Web framework
* [Leaflet](https://leafletjs.com/) - Mapping applications

## Authors
* [Joseph Barr](https://github.com/JosephMBarr)
* [JT Singhal](https://github.com/JTSinghal)
* [Rick Kase](https://github.com/kaseDev)
* [Youngsik Yoon](https://github.com/JeroSik)

See also the list of [contributors](https://github.com/JeroSik/GeoTrash/graphs/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* [EcoMake 2018 Purdue](https://www.ecomake.org/) from 10/12-10/14
