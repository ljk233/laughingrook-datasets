
## The International E-road Network (`eroads_edge_list`)

[The International E-road Network and Neo4j](http://lassewesth.blogspot.com/2018/07/the-international-e-road-network-and.html)

Data on the road network in Europe as an *edge list*.
Nodes are cities, and the edges between them represent connecting links.

### Data disctionary

- `str` road_number
- `str` origin_country_code
- `str` origin_reference_place
- `str` destination_country_code
- `str` destination_reference_place
- `int` distance
- `bool` watercrossing

## Network of Thrones (`network_of_thrones_*`)

Character Interaction Networks for George R. R. Martin's "A Song of Ice and Fire" saga.

### Data dictionary

- NODES
  - `str` Id
  - `str` Label
- EDGES
  - `str` Source
  - `str` Target
  - `str` Type
  - `int` id
  - `weight` weight

### Source

[Network of Thrones](https://networkofthrones.wordpress.com/) (Andrew Beveridge)

### License

No changes have been made to the data.
[Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
