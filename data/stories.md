## Generated Story 1 no stop number
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## Generated Story 1 no stop number 2
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* thanks
    - utter_thanks

## Generated Story 1 no stop number - aa
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* thanks
    - utter_thanks

## Generated Story 1 no line number - aaa
* greet
    - utter_greet
* search_bus_time{"stop_number": "40421"}
    - slot{"stop_number": "40421"}
    - utter_ask_line_number
* search_bus_time{"line_number": "9"}
    - slot{"line_number": "9"}
    - slot{"stop_number": "40421"}
    - action_next_bus
* goodbye
    - utter_goodbye

## Generated Story 2 no stop number or line number
* greet
    - utter_greet
* search_bus_time
    - utter_ask_stop_number
* search_bus_time{"stop_number": "66666"}
    - slot{"stop_number": "66666"}
    - utter_ask_line_number
* search_bus_time{"line_number": "22"}
    - slot{"stop_number": "66666"}
    - slot{"line_number": "22"}
    - action_next_bus
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye


## Generated Story 3 no line number
* greet
   - utter_greet
* search_bus_time{"stop_number": "77777"}
   - slot{"stop_number": "77777"}
   - utter_ask_line_number
* search_bus_time{"line_number": "33"}
   - slot{"stop_number": "77777"}
   - slot{"line_number": "33"}
   - action_next_bus
* affirm
    - utter_affirm
* goodbye
   - utter_goodbye

## Generate Story 4 line and stop number
* greet 
    - utter_greet
* search_bus_time{"stop_number": "88888", "line_number": "44"}
    - slot{"stop_number": "88888", "line_number": "44"}
    - action_next_bus
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye

## 4a 
* greet
    - utter_greet
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "88888", "line_number": "44"}
    - slot{"stop_number": "88888", "line_number": "44"}
    - action_next_bus
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## 4b 
* greet 
    - utter_greet
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "50432", "line_number": "c23"}
    - slot{"stop_number": "8504328888", "line_number": "c23"}
    - action_next_bus
* goodbye
    - utter_goodbye 


## 4c 
* greet 
    - utter_greet
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "23000", "line_number": "7"}
    - slot{"stop_number": "23000", "line_number": "7"}
    - action_next_bus
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye


## 4d 
* greet 
    - utter_greet
* search_bus_time{"stop_number": "40322", "line_number": "N9"}
    - slot{"stop_number": "40322", "line_number": "N9"}
    - action_next_bus
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## 4da 
* greet 
    - utter_greet
* search_bus_time{"stop_number": "56032", "line_number": "03"}
    - slot{"stop_number": "56032", "line_number": "03"}
    - action_next_bus
* thanks
    - utter_thanks
    
## 3a
* greet
   - utter_greet
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "77777"}
   - slot{"stop_number": "77777"}
   - utter_ask_line_number
* search_bus_time{"line_number": "33"}
   - slot{"stop_number": "77777"}
   - slot{"line_number": "33"}
   - action_next_bus
* affirm
    - utter_affirm
* goodbye
   - utter_goodbye

## 3b
* greet
   - utter_greet
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "77777"}
   - slot{"stop_number": "77777"}
   - utter_ask_line_number
* garbage
    - slot{"stop_number": "77777"}
    - utter_garbage
* search_bus_time{"line_number": "33"}
   - slot{"stop_number": "77777"}
   - slot{"line_number": "33"}
   - action_next_bus
* thanks
    - utter_thanks
* goodbye
   - utter_goodbye

## 3c
* greet
   - utter_greet
* search_bus_time{"stop_number": "57839"}
   - slot{"stop_number": "57839"}
   - utter_ask_line_number
* search_bus_time{"line_number": "22"}
   - slot{"stop_number": "57839"}
   - slot{"line_number": "22"}
   - action_next_bus

## 3ssc
* greet
   - utter_greet
* search_bus_time{"stop_number": "57839"}
   - slot{"stop_number": "57839"}
   - utter_ask_line_number
* search_bus_time
    - utter_ask_line_number
 * search_bus_time
    - utter_ask_line_number   
* search_bus_time{"line_number": "22"}
   - slot{"stop_number": "57839"}
   - slot{"line_number": "22"}
   - action_next_bus
* thanks
    - utter_thanks

## 3d
* greet
   - utter_greet
* search_bus_time{"stop_number": "77777"}
   - slot{"stop_number": "77777"}
   - utter_ask_line_number
* search_bus_time{"line_number": "33"}
   - slot{"stop_number": "77777"}
   - slot{"line_number": "33"}
   - action_next_bus
* goodbye
   - utter_goodbye

## 1a
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye


## 1b
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* affirm
    - utter_affirm


## 1c
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* garbage
    - utter_garbage
* search_bus_time
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus

## 1d
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* goodbye
    - utter_goodbye


## 1e
* greet
    - utter_greet
* garbage
    - utter_garbage
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus

## 1f
* garbage
    - utter_garbage
* greet
    - utter_greet
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## 1fzzz
* garbage
    - utter_garbage
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## 1fddd
* search_bus_time{"line_number": "99"}
    - slot{"line_number": "99"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "55555"}
    - slot{"line_number": "99"}
    - slot{"stop_number": "55555"}
    - action_next_bus

## 2a
* greet
    - utter_greet
* search_bus_time
    - utter_ask_stop_number
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "66666"}
    - slot{"stop_number": "66666"}
    - utter_ask_line_number
* search_bus_time{"line_number": "22"}
    - slot{"stop_number": "66666"}
    - slot{"line_number": "22"}
    - action_next_bus
* goodbye
    - utter_goodbye


## 2b
* greet
    - utter_greet
* search_bus_time
    - utter_ask_stop_number
* garbage
    - utter_garbage
* search_bus_time{"stop_number": "66666"}
    - slot{"stop_number": "66666"}
    - utter_ask_line_number
* search_bus_time{"line_number": "22"}
    - slot{"stop_number": "66666"}
    - slot{"line_number": "22"}
    - action_next_bus
* thanks
    - utter_thanks


## 2c
* greet
    - utter_greet
* search_bus_time
    - utter_ask_stop_number
* search_bus_time{"stop_number": "66666"}
    - slot{"stop_number": "66666"}
    - utter_ask_line_number
* search_bus_time{"line_number": "22"}
    - slot{"stop_number": "66666"}
    - slot{"line_number": "22"}
    - action_next_bus
* affirm
    - utter_affirm


## 2d
* greet
    - utter_greet
* search_bus_time
    - utter_ask_stop_number
* search_bus_time{"stop_number": "66666"}
    - slot{"stop_number": "66666"}
    - utter_ask_line_number
* search_bus_time{"line_number": "22"}
    - slot{"stop_number": "66666"}
    - slot{"line_number": "22"}
    - action_next_bus


## Generate Story 5 location_start provided
* greet
    - utter_greet
* search_trip{"location_start": "Waterfront Station"}
    - slot{"location_start": "Waterfront Station"}
    - utter_ask_location_end
* search_trip{"location_end": "Main and Broadway"}
    - slot{"location_end": "Main and Broadway"}
    - slot{"location_start": "Waterfront Station"}
    - action_trip
* goodbye
    - utter_goodbye


## Generate Story 6 both start and end provided
* greet
    - utter_greet
* search_trip{"location_start": "Commercial-Broadway", "location_end": "Oakridge Mall"}
    - slot{"location_start": "Commercial-Broadway", "location_end": "Oakridge Mall"}
    - action_trip
* goodbye
    - utter_goodbye


## Generate Story 7 end provided
* greet
    - utter_greet
* search_trip{"location_end": "ubc"}
    - slot{"location_end": "ubc"}
    - utter_ask_location_start
* search_trip{"location_start": "sfu"}
    - slot{"location_start": "sfu"}
    - slot{"location_end": "ubc"}
    - action_trip
* goodbye
    - utter_goodbye


## Generate Story 8 neither start nor end provided
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* goodbye
    - utter_goodbye

##Generate Story 8A
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* garbage
    - utter_garbage
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip

## Generate Story 8B
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* thanks
    - utter_thanks


## Generate Story 8C
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* garbage
    - utter_garbage
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye

## Generate Story 8C1
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* garbage
    - utter_garbage
    - slot{"location_start": "41st and Fraser"}
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye


## Generate Story 8D
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* garbage
    - utter_garbage
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* goodbye
    - utter_goodbye

## Generate Story 8D1
* garbage
    - utter_garbage
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "metrotown"}
    - slot{"location_start": "metrotown"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "metrotown"}
    - action_trip
* goodbye
    - utter_goodbye


## Generate Story 8E
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* garbage
    - utter_garbage
    - slot{"location_start": "41st and Fraser"}
* search_trip{"location_end": "waterfront station"}
    - slot{"location_end": "waterfront station"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* thanks
    - utter_thanks

## Generate Story 8F
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* garbage
    - utter_garbage
    - slot{"location_start": "41st and Fraser"}
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye

## Generate Story 8G
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* affirm
    - utter_affirm

## Generate Story 8H
* greet
    - utter_greet
* search_trip
    - utter_ask_location_start
* search_trip{"location_start": "41st and Fraser"}
    - slot{"location_start": "41st and Fraser"}
    - utter_ask_location_end
* search_trip{"location_end": "Downtown"}
    - slot{"location_end": "Downtown"}
    - slot{"location_start": "41st and Fraser"}
    - action_trip
* thanks
    - utter_thanks

## Generate Story 5A
* greet
    - utter_greet
* search_trip{"location_start": "vcc"}
    - slot{"location_start": "vcc"}
    - utter_ask_location_end
* garbage
    - utter_garbage
* search_trip{"location_end": "bcit"}
    - slot{"location_end": "bcit"}
    - slot{"location_start": "vcc"}
    - action_trip
* goodbye
    - utter_goodbye

## Generate Story 5B
* greet
    - utter_greet
* search_trip{"location_start": "vfs"}
    - slot{"location_start": "vfs"}
    - utter_ask_location_end
* search_trip{"location_end": "vgh"}
    - slot{"location_end": "vgh"}
    - slot{"location_start": "vfs"}
    - action_trip
* thanks
    - utter_thanks

## Generate Story 5C
* search_trip{"location_start": "Waterfront Station"}
    - slot{"location_start": "Waterfront Station"}
    - utter_ask_location_end
* search_trip{"location_end": "Main and Broadway"}
    - slot{"location_end": "Main and Broadway"}
    - slot{"location_start": "Waterfront Station"}
    - action_trip
* goodbye
    - utter_goodbye

## Generate Story 5D
* greet
    - utter_greet
* search_trip{"location_start": "ubc"}
    - slot{"location_start": "ubc"}
    - utter_ask_location_end
* garbage
    - utter_garbage
* search_trip{"location_end": "yvr"}
    - slot{"location_end": "yvr"}
    - slot{"location_start": "ubc"}
    - action_trip
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye


## Generate Story 6A
* greet
    - utter_greet
* search_trip{"location_start": "airport", "location_end": "Oakridge Mall"}
    - slot{"location_start": "airport", "location_end": "Oakridge Mall"}
    - action_trip
* affirm
    - utter_affirm

## Generate Story 6B
* greet
    - utter_greet
* search_trip{"location_start": "Commercial-Broadway", "location_end": "Oakridge Mall"}
    - slot{"location_start": "Commercial-Broadway", "location_end": "Oakridge Mall"}
    - action_trip
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye


## Generate Story 6C
* garbage 
    - utter_garbage
* search_trip{"location_start": "Commercial-Broadway", "location_end": "Oakridge Mall"}
    - slot{"location_start": "Commercial-Broadway", "location_end": "Oakridge Mall"}
    - action_trip
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye

## Generate Story 6D
* greet
    - utter_greet
* garbage 
    - utter_garbage
* search_trip{"location_start": "yvr", "location_end": "Oakridge"}
    - slot{"location_start": "yvr", "location_end": "Oakridge"}
    - action_trip
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye


## Generate Story 7A
* greet
    - utter_greet
* search_trip{"location_end": "UBC"}
    - slot{"location_end": "UBC"}
    - utter_ask_location_start
* garbage 
    - utter_garbage
    - slot{"location_end": "UBC"}
* search_trip{"location_start": "Kitsilano"}
    - slot{"location_start": "Kitsilano"}
    - slot{"location_end": "UBC"}
    - action_trip
* affirm
    - utter_affirm
* goodbye
    - utter_goodbye

## Generate Story 7B
* greet
    - utter_greet
* search_trip{"location_end": "UBC"}
    - slot{"location_end": "UBC"}
    - utter_ask_location_start
* garbage 
    - utter_garbage
    - slot{"location_end": "UBC"}
* search_trip{"location_start": "Kitsilano"}
    - slot{"location_start": "Kitsilano"}
    - slot{"location_end": "UBC"}
    - action_trip
* thanks
    - utter_thanks

## Generate Story 7C
* greet
    - utter_greet
* search_trip{"location_end": "UBC"}
    - slot{"location_end": "UBC"}
    - utter_ask_location_start
* search_trip{"location_start": "Kitsilano"}
    - slot{"location_start": "Kitsilano"}
    - slot{"location_end": "UBC"}
    - action_trip
* thanks
    - utter_thanks
* goodbye
    - utter_goodbye


## Generate Story 7D
* greet
    - utter_greet
* search_trip{"location_end": "UBC"}
    - slot{"location_end": "UBC"}
    - utter_ask_location_start
* search_trip{"location_start": "Kitsilano"}
    - slot{"location_start": "Kitsilano"}
    - slot{"location_end": "UBC"}
    - action_trip
* affirm
    - utter_affirm

## Generated Story 1313
* greet
    - utter_greet
* search_bus_time{"line_number": "128"}
    - slot{"line_number": "128"}
    - utter_ask_stop_number
* search_bus_time{"stop_number": "51344"}
    - slot{"line_number": "128"}
    - slot{"stop_number": "51344"}
    - action_next_bus
* goodbye
    - utter_goodbye

## Generated Story 1314
* greet
    - utter_greet
* search_trip{"location_end": "Burrard Station"}
    - slot{"location_end": "Burrard Station"}
    - utter_ask_location_start
* search_trip{"location_start": "Bard on the Beach"}
    - slot{"location_start": "Bard on the Beach"}
    - slot{"location_end": "Burrard Station"}
    - action_trip
* goodbye
    - utter_goodbye

## Generated Story -6109847072426567524
* greet
    - utter_greet
* search_trip{"location_start": "sfu"}
    - slot{"location_start": "sfu"}
    - utter_ask_location_end
* search_trip{"location_end": "ubc"}
    - slot{"location_start": "sfu"}
    - slot{"location_end": "ubc"}
    - action_trip
* affirm
    - utter_affirm

