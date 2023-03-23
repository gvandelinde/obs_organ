General remark: we want to scale the amount of change over the times these event are deceted. This would distinguish a small error from deliberate malintended behavior, and allow for forgiveness.

# Competence
**increase:**
- If the human communicates his search for a room, and along the line, it is followed by a message of finding a victim or obstacle in that room.
- and then rescuing the victim. (i.e. when a human performs a succesfull rescue)
 

**decrease:**
- Not communicating the rescue of a victim.
- If an agent says they've done someone, but it hasn't.
- Whenever a search isn't announced but there was searching done.
- When the human agent requests assitstance, but there is none needed. 

# [[Wilingness]] 
**increase:**
- Coming to assist the robot on carrying a mildly injured victim.
- Coming to assist the robot on carrying a mildly injured victim.

**decrease:**
- Not responding to the questions of the robot in a timely fashion.
- Respond to the robots question fo help(like carrying critical victim) with something unrelated and not coming ot help.

	Note: we Assume that competence is a measure of how good the human is at performing its own tasks with communication and willingness as the measure of how eager the human is to come help the robot.


## Questions:
```
Does all our code go into the _trustBeliefs function? (This would mean we are limited to messages)
What is a good way of going about processing other information (e.g. found victims, rescued victims, etc.)
Is there a message that corresponds to a victim being rescued?
What do you think of our current list of events?
```


# Work devision:
Individual: Ask questions during lab, communicate answers TA
-> Pablo

Individual: implement "look at values based on the world's state" (i.e. that are not message-based) based on TA advice
-> Gijs

Pair:
Competence increment
Competence decrement 
-> Apoorv & Pablo

Pair:
Willingness increment
Willingness decrement 
-> Youri & Gijs

# Next time: Discuss 
how to change behavior of robot.