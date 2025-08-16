Build a ML model to predict if the hotel room would be sold out. With this model, we will use it to assess the stock level of any given competitor's hotel (which is a blackbox to us) to enable us price our hotel room more strategically.

Each data point (training data) consists of: 
- date time, including if is weekend, if is holiday or special event day
- hotel info, including location (e.g. popular area or not), number of rooms
- room type, and info (e.g size, tier compared to other rooms)
- listed prices 

The label for each data point could be (please brainstorm):
- if the specific room at that specific time is sold out
- or, if at this specific time, the room will be sold out immediately (e.g. the next datapoint about this room type will be marked as sold out)

Please expand this requirement doc so it covers:
- high level, what's the ML model's prediciton goal, how would it help with predict competitor's stock level to help us price our room
- ML components: data, feature, label, offline evaluation etc.
- execution milestone from scratch: e.g. collecting data; build prototype model; deploy online; connect to downstream price model; online evaluation etc.

(this is a rough idea, please feel free to brainstorm and expand the idea; especially internet searching for similar idea for pricing modelling)
