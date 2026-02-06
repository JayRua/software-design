# USE CASE DIAGRAM CHECKLIST
### System boundary

□ Draw one big rectangle to represent the system   
□ Put system name at top of the box  
□ Everything inside box = system behaviour  
□ Everything outside box = actors  

### Actors

□ Draw actors as stick figures   
□ Use role names (Student, Admin, Customer) not real names   
□ Every actor is connected to at least one use case   



### Use cases

□ Draw use cases as ovals  
□ Place all use cases inside the system box  
□ Each use case represents a complete user goal   
□ Name using verb + noun (e.g. “Borrow Book”)   



### Associations

□ Draw plain lines between actor and use case   
□ No arrows on normal association lines  
□ Actor may connect to multiple use cases  
□ Use case may connect to multiple actors   



### Include relationship

□ Label relationship `<<include>>`       
□ Dashed arrow  
□ Arrow points TO the included use case  
□ Means ALWAYS happens   

(Remember: reuse common behaviour)  

### Extend relationship

□ Label relationship `<<extend>>`       
□ Dashed arrow  
□ Arrow points TO the base use case  
□ Means OPTIONAL behaviour   
□ Should have a condition  

### Actor generalisation (if present)

□ Solid line with hollow triangle arrow  
□ Arrow points to the general actor   



### Final logic check

□ Every use case provides value to an actor   
□ No isolated use cases  
□ No UI actions (no “click button” wording)  
□ Take off your reality goggles. Remember broad strokes!  
