Log infos:
- Start time
- Duration
- Weather:
    * Fair
    * Rain
    * Snow
    * Hail
    * Sleet
    * Freezing Rain
    * Fog
    * Other
- Road Type
    * Highway
    * Major Road
    * Local Road
    * Rural Road
    * Urban Road
    * Parking Lot
- Time of Day
    * Day
    * Night
- Notes Textarea



# Devlog 4

Pretty big devlog, the main thing that I've been working on is the migration function from RoadReady to this app, in which you can upload a file and it'll parse it into driving logs for you. It utilizes a regex and then also string splitting to identify logs inside a PDF, before then populating the entire drive log. Understanding how regexs work and how to get it to work consistently across formats was quite difficult, but I do think I learned a lot from it.

It took quite a lot of iterations to get to this point, for example just trying to iterate through each character to find patterns or potentially using an AI api to look through the parsed text to try and find it, but I think that I'm happy with what has come out. Obviously there's a lot of discrepencies and the app still looks like buns, but hopefully that'll change soon!