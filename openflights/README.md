# OpenFlights

* ID - openflights
* Description - Airports and flights
* Data Source - [OpenFlights](https://openflights.org/data.html)
* License - [Database Contents License](https://opendatacommons.org/licenses/dbcl/1.0/)
* Size - 5.2 MB
* Node Count - 2,670
* Edge Count - 30,857

## Sample

### Nodes - Airports

```
"http://openflights.org/Airport/7579"	:airport	name:"Provo Municipal Airport"	iata:PVU	city:Provo
"http://openflights.org/Airport/1926"	:airport	name:"Owen Roberts International Airport"	iata:GCM	city:Georgetown
"http://openflights.org/Airport/18"	:airport	name:"Reykjavik Airport"	iata:RKV	city:Reykjavik
```

### Edges - 

```
"http://openflights.org/Airport/2287"	->	"http://openflights.org/Airport/2279"	:has_flight_to	airline:"Japan Airlines"	country:Japan	plane:"Boeing 777-300"
"http://openflights.org/Airport/2279"	->	"http://openflights.org/Airport/2287"	:has_flight_to	airline:"Japan Airlines"	country:Japan	plane:"Boeing 777-300"
"http://openflights.org/Airport/3376"	->	"http://openflights.org/Airport/3368"	:has_flight_to	airline:"China Eastern Airlines"	country:China	plane:"Boeing 737-800"
```

## How Generated

* https://github.com/ryotayamanaka/jist2018-tutorial/wiki/Hands-on-Part-1
* https://github.com/ryotayamanaka/jist2018-tutorial/wiki/Hands-on-Part-2
