lorcon - Loss Of Radio CONnectivity

Copyright (c) 2005 - Joshua Wright <jwright@hasborg.com>
                     dragorn <dragorn@kismetwireless.net>

Project goals:
	Create what libradiate could have been:  A generic library for injecting
	802.11 frames, capable of injection via multiple driver frameworks, without
	forcing modification of the application code.

Tools:
    tx - A super-basic demo of the library capabilities that writes static
    packets to the interface

    tuntx - A more useful demo of the library capabilities, tuntx binds a
    tuntap virtual interface to a card via LORCON.  Write 802.11 frames to
    the tuntap virtual interface, they get transmitted out the card.
