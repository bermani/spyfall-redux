# Spyfall Redux

Spyfall on your mobile device!

New features and content! More decks, a new look, QOL improvements and some secrets ;)

Play at [spyfall.isaacdb.com](https://spyfall.isaacdb.com)!

Modified from the [original repo](https://github.com/mpcovcd/spyfall)

## Disclaimer

[Spyfall](http://international.hobbyworld.ru/spyfall) is a party game designed by Alexandr Ushan and published by [Hobby World](http://international.hobbyworld.ru/). This is an unofficial fan project designed to complement the physical game, and is not endorsed in any way by the designer or publisher.

## Running your own instance with custom locations

[Install meteor](https://www.meteor.com/install)

Clone the repository:

	git clone https://github.com/mpcovcd/spyfall.git ./spyfall

Enter the spyfall directory:

	cd spyfall/spyfall

Edit the locations file as required:

	nano lib/locations.js

Run the meteor server to test locally:

	meteor --settings settings/example.json

Sadly, production deployment has gotten a little trickier since meteor.com stopped providing easy free hosting. I recommend a combination of digitalocean.com and mupx for a relatively easy and robust solution.

## Links

[BoardGameGeek Discussion Thread](http://www.boardgamegeek.com/thread/1279239/app/page/1)
