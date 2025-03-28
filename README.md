# SNAZZYBONES: A Rockbox Theme

A theme for the [Rockbox](https://en.wikipedia.org/wiki/Rockbox) targeting 320x240 screens. I use it on my iPod 5.5G.

My goals for this theme are:
- It is as **simple** and **calm** as possible.
- The "Now Playing" screen is especially **simple** and **calm**. When listening, it is the listener's refuge. It should not even include the current time.


**Simple**: include only what is necessary, laid out in the cleanest possible way.  
**Calm**: Animation and movement should be minimized.


## Installation

1. [Install Rockbox](https://www.rockbox.org/download/)
1. Download this repository and move the contents of `dot-rockbox` into the `.rockbox` directory on your music player.

## Inspiration and Credit

SNAZZYBONES is based on two great themes:
- [SNAZZY](https://themes.rockbox.org/index.php?themeid=3627&target=cowond2) by Chris Graves
- [BONES](https://themes.rockbox.org/index.php?themeid=3579&target=cowond2) by Chuck Lardo

See `LICENSES.md` for more information.


# TODO

- [ ] Put screenshots in the README.
- [ ] Once the theme stabilizes, submit it to the Rockbox website.
- [ ] The smallest text in the theme is fuzzy. Find an alternative font to replace 15-VictorMono that looks sharper, doesn't require anti-aliasing at such a small size.


## WPS
- [ ] Show the artist name and album separately, rather than switching back and forth between them.
- [ ] Use more of the screen real estate, if it can be done without destroying its beauty. Using more of the screen will reduce title scrolling.

## SBS
- [ ] Reduce the size of the title, if doing so frees up space for something else.
- [ ] Remove "ROCKBOX" text at top left, move "LOCKED" text to top left. This will align it with the physical hold switch on the iPod 5.5G.
- [ ] Time and date: figure out how to have it stop switching between the two, and instead show either both or just the time. Perhaps put just the time at the top center.
- [ ] Experiment with using the BONES SBS font size. SNAZZY and BONES both show five list items at a time, which seems like the minimum usable number. The iPod 4G shows six, and the iPod 5G stock firmware shows nine.


