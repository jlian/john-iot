# Press a (physical) button for a tweet

This is a simple program for https://aka.ms/iot-devkit which lets me press the button B to send the current temperature and humidity to Azure and then Twitter. But right now the only code in the repository is for the MXChip board. 

The device sits on my desk at work. The goal is to do this everyday when I leave work and then after some time I would have a Twitter log of the temperature/humidity for when I'm leaving. Super useful, I know ;)

See it in action at https://twitter.com/john_iot

## Some ideas for the future

- Install a camera so it also tweets a picture of the outside when I press the button
- Send the info to some sort of database or data visualization platform as well so I can have a graph
- Have Twilio integration so people that care can get text when I leave work (hi mom)
