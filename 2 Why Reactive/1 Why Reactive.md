## Why Reactive - Review Questions

- what problem is Reactive Architecture trying to solve?
- where reactive architecture came from?

### Technical specs of systems a decade or more ago

- the size of software installations were small (approximately 2 to 10 nodes).
- size of data has small. 
- giga byte's worth of data at-rest was being handled. 
- "at-rest data" would typically not be changing actively. 
- data was typically pulled once a day and batch Jobs were being run on them and then that data would remain fairly static for a period.
- most systems had long maintainence windows.

### Technical specs of present day Systems

- software installations can go into the tens, the hundreds, or even the thousands of nodes.
- we're now dealing with petabytes of data in some cases.
- data isn't at rest anymore it's changing constantly. 
- data is being processed in real-time
- we are now looking at a hundred percent time, or at least close enough.

### Modern Software Users

- Modern World relies heavily on systems to perform day to day tasks
- System downtime can have severe impact on business
- Unresponsive systems lead to user dis-satisfaction

#### The primary goal of reactive architecture is to provide an experience that is responsive under all conditions.