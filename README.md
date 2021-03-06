# alsamonitor

A simple volume monitor.  Unlike the builtin xmobar one, it doesn't poll but
only updates when informed by alsa of changes.

# batterymonitor

A battery monitoring script.  It's a wrapper around upower (so you'll need
that installed).  Unlike the builtin xmobar monitors, not only does it work
consistently, but it also doesn't poll.

# mpdmonitor

This is a script that I use with xmobar to control mpd.  It displays current
track information in a pretty form for xmobar as its primary function.

As a secondary function, whenever the play queue is empty, it enqueues a
random album (random album by random artist) to the queue.  This is great for
people who work well with music playing, but for whom trying to find the next
album from their library to play is time-consuming (and also for people who
like to listen to full albums).

It should probably be noted that my xmonad config has keys bound to clearing
the current play queue.
