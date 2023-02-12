# HashMap
* implemented very efficient "Robin-Hood hashing" technique
* $O(n)$ memory, $O(1)$ per query

# For using
* clone this repo
* include ```hash_map.h``` header
# Code example: 
```C++

#include <iostream>
#include "hash_map.h"

HashMap <int, int> hash_map;
hash_map[100] = 900;
hash_map[200] = 500;
hash_map.erase(100);
auto iterator = hash_map.find(200);
std::cout << iterator->second << '\n';
```
