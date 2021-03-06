# ATLC2 Qualifier

Bundle for use with [NodeCG](http://nodecg.com/) in Amaz Productions' ATLC2 Qualifier, a Hearthstone esports event. Documentation format and most of the "How to use" section borrowed from [NodeCG for Smash](https://github.com/mparkms/nodecg-for-smash).

This bundle was not designed for distribution or re-use. I shoe-horned React into NodeCG in order to learn the basics of React. I don't recommend React in NodeCG. This README was written several months after the conclusion of the event. 

## How to use

1. Install [git](https://git-scm.com/). Make sure to select 'Use Git from the Windows Command Prompt' if you're on Windows.
2. Install NodeCG as shown in the instructions on the [NodeCG website.](http://nodecg.com/) If it tells you `bower` is not recognized, type in `npm install -g bower`.
3. From this point on, all commands should be in the regular command line, not Node.js. Exit Node.js by hitting ctrl-C twice if you're in Node.js.
4. Install nodecg-cli as shown [here.](https://github.com/nodecg/nodecg-cli)
5. In the command line in the folder you installed NodeCG, enter `nodecg install jafarrar/atlc2-qualifier`
6. Start NodeCG by entering `nodecg start` into command prompt in the folder where NodeCG is installed and go to `localhost:9090` in your browser.
7. Install [OBS Studio](https://obsproject.com/)
8. Add the views listed on the Graphics page at `localhost:9090/dashboard/#!/graphics` as Browser Sources in similarly-named OBS scenes

## Overview of included dashboard panels

### Bracket

Add the names of the series listed below, then assign players to them as the tournament progresses. This is not a proper bracket editor. This module's CSS is unfortunately hard-coded to look for certain values. Those values are:

* Quarter Finals 1
* Quarter Finals 2
* Quarter Finals 3
* Quarter Finals 4
* Semi Finals 1
* Semi Finals 2
* Grand Final

### Broadcast

Here you can update the following information:

* Caster names and Twitter handles (Caster Cams)
* Lower third information (Up Next)
* Countdown timer (Up Next)
* Flyout (Caster Cams & In Game)

### Players

This iteration of the bundle was designed for 8 players. Here you can add players, update their personal information, and set what decks they're using. Upload player pictures in NodeCG's Assets view, then select the appropriate one as you're editing the player.

### Series

Set and edit the data for the active series. This information is used in the Caster Cams and In Game scenes. 

## Credits

* [NodeCG](http://nodecg.com/)
* [NodeCG for Smash Documentation](https://github.com/mparkms/nodecg-for-smash)