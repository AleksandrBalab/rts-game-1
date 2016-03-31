WEB1: RTS
WEB1: RTS: Write an HTML5 Real-Time Strategy game.

In this project, you'll be creating an HTML5 web-based real-time strategy game.

The setting, style, and objective of the game are up to you, but the final project must satisfy the following requirements:
	-It must be playable using the Google Chrome web browser.
	-It does not have to be served from an OSU web server, but this would be preferred.
	-It will be single player only.
	-A user's progress must be able to be saved, such that the user can leave and come back to resume the game. You can use cookies or a server-based DB for this.
	-Your game must allow individual "units" to be constructed that serve some purpose in a 2D area.
	-There must be a computer/AI opponent that resists and plays counter to your efforts. This AI must have 2 distinct settings - an easier mode, and a harder mode.
	-An individual game must be winnable, with reasonable to serious effort/skill, within 15 minutes. A new player should not be able to beat the game.
	-Data about the individual units must be loaded from separate files on the web server (one unit per file).

Recommend Division of Labor:
	-Graphics and Engine developer: handles the display of the various game components on the page.
	-AI Developer: writes the software that plays counter to your efforts.
	-Units and Balance Developer: handles the creation of unit data files and the format for those files, and writes the code that loads them into the engine. Perhaps also handles the web development and user data storage (save games).
