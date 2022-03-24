## Considering that this software will be a standalone application for now

### Protocol
- Two markers: Origin and Target
- Reaching from left to right
- 3 unperturbed sessions with 30 trials (reaching movements)
- 3 perturbed sessions with 30 trials (reaching movements)
- 2 minute rest between sessions and 5 minute rest between the last unperturbed
and the first perturbed sessions

### protocol_controller:
- prepare the class to specifically generate the proposed protocol
- need a session counter and a trial counter
- trial starts when cursor hits the origin (anywhere) and ends when the cursor
hits the target (anywhere)
- a method that writes the header
- a method that saves the experiment data
- save each trial separately
- display a message during rest

### reachingwindow:
- needs to initialize the experimental protocol
- needs to trigger events when the cursor hits the origin or the target
