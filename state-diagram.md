# STATE DIAGRAM CHECKLIST
### Diagram basics
□ Give the diagram a name     
□ Only one object’s lifecycle is shown   



### Start and end
□ Add initial state (solid black circle)   
□ Add at least one final state (bullseye)   


### States
□ States drawn as rounded rectangles   
□ States are conditions (NOT actions)   
□ Names are nouns/adjectives (e.g. “Paid”, “Active”)  
□ Model stable states first   



### Transitions
□ Arrows show movement between states   
□ Every arrow has an event name   
  
Format:  
event [condition] / action   



### Guards (conditions)
□ Written inside square brackets [ ]   
□ Must evaluate true/false  

### Actions / activities
□ Action after slash “/”   
□ entry / exit / do allowed inside states    



### Events types
□ Change event (condition becomes true)   
□ Signal/call event (user/system action)   
□ Time event (after time passes)   



### Layout quality
□ Minimise crossing lines   
□ Contains only essential elements   



### Final logic check
□ Every state reachable  
□ No dead-end state except final  
□ Each transition has a trigger  
