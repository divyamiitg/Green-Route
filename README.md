
# Green Route

## Features

- Displays the shortest distance between source and destination.
- Displays shortest path one must take to reach destintion with minimum distance.

## API Reference

#### Get shortest distance between node A and node B 

```http
  GET /shortd/<int:A>/<int:B>
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `source` | `integer` | **Required**|
| `destination` | `integer` |     **Required**      |




## Tech Stack

**Client:** React

**Server:** Flask, Python


## Used By

This project is used by the following:

- Students of IIT Guwahati
- Delivery/Courier persons coming to IIT Guwahati 


## FAQ

#### How will obtain my shortest path from source to destination?

Every possible source and destination is mapped with a number ranging from (1 to 64). Path in the application will display the nodes in order to reach the destination. 



 

