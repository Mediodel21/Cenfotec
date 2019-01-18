# Curso-Xamarin
Curso Xamarin
La aplicacion utiliza API de NBA (stats.nba.com) para mostrar las estadisticas de equipos y jugadores de la NBA.
Los niveles de la API son : Equipo, Jugadores y Estadisticas del Jugador.
No hay pulgas reportadas por la etapa del proyecto (inicial).
Pendientes: Integracion via REST con el API, desarrollo de los niveles 2 y 3. 

NBA API PHP Library
Introduction
The NBA provides an enormous amount of undocumented filterable public data via URL endpoints on their websites. This includes statistical data as well as general/historical information about the league, its teams, players, and more. Most of this information is returned as JSON data, but there are also endpoints that retrieve data in XML and PDF formats.

The goal of this library is to provide an easy-to-use client to access and process all currently-known NBA endpoints. At this time, that number is 253. No other library has more than 100 endpoints.

Endpoints / Requests
Each endpoint in the library is tied to a Request class. For more information about how these requests work, see the Requests section of the documentation. At the highest level, requests are available from the following domains:

http://api.nba.net
http://data.nba.net
http://gleague.nba.com
http://www.nba.com
http://stats.nba.com
http://stats-prod.nba.com
The sidebar has a request reference that provides easy access to information about every request. This is not just a programming reference; even non-programmers can run full examples right from this site to retrieve data, and even filter all available options on every report.

Go ahead, try out an example!

Requirements
In order to use this library you need to be using PHP 7.0 or later and composer for package management.

Open-Source
This library is completely open source and released under the MIT license. You may fork the code for your own use, but if you have potential improvements or enhancements to the code, I welcome discussion and pull requests to place them into the main library.

Support / Troubleshooting
If you think you have discovered a bug in this library, please open an issue on GitHub. For updates, please check out the blog and follow NBASense out on Twitter.

If you are having trouble retrieving requests that access stats.nba.com/stats/, it appears that the NBA has blocked off access to these endpoints on some level; this blocking seems to occur on many cloud hosting providers such as Amazon AWS, Digital Ocean, and Heroku.

In my testing, these endpoints have always worked when developing locally.

Author
The NBA API PHP Library (and this website) was developed by Jason Roman. Feel free to contact me with any questions, comments, or suggestions to improve this library at j@jayroman.com or on Twitter at @_jasonroman
