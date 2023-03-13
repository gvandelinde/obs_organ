# Wilingness is a question of lying
__Wilingness increase__:
- 'help remove at...' is followed by a collaberative removal
	-> Line 501.
- 'Rescue together' is follwed by a collaberative rescue mission
- Found message is followed by the victim being rescueud later
- Collect message holds up
- Search action is followed by a Found in... which actually holds.

__Wilingness decrease__:
- A human messages 'help remove at ...', but isn't there waiting. (-> maybe add timeframe?)
- A human messages 'help remove at ...', but there's no obstacle. (-> maybe add timeframe?)
    -> messages containing 'Remove'
    -> require observation of rooms/obstacles.
    
- A human messages 'rescueue together', but doesn't come (timeframe).
    -> message 'Rescue together'

- The human messages 'I've found a victim in area A', but the victim isn't there.
    -> messages contains 'Found'

- A human says 'I'm collecting victim', but the victim isn't collected after a different message from the human.
    -> this requires observations of rescued victims.

- A human says I will search in area A, then continues searching a different area but there is something unreported (obstacle or victim) in area A.
    (This might be something that only comes up when all the rooms are "searched" collaberatively, but not bu the robot itself)
    -> messages containing 'Search'


# Implementation
For all of the above measures, the robot needs to make observations of the state of the room.


Option: have array of booleans that indicate that something just happended, say one element that represents "the bot is wait"