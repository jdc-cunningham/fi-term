- [ ] drive display
- [ ] setup API with DB
- [ ] setup desktop interface to update info for display
- [ ] create mobile app that ingests this data
- [ ] create display cycler
- [ ] design basic 3D printed stand

### 07/18/2026

3:19 PM

Alright I have like just under 6 hrs before I go back out to the bars (karaoke) I am sober so I'm being a good boy.

But last night I was there till after 4 AM since they're open till 5 AM for the world cup.

I'm going to 3D print a basic stand (2D type) and then get something displayed on the screen.

This means figuring out how to drive it with that library I found that's written in NodeJS, this one:

https://github.com/gaweee/epd2in13

The code is short so I should be able to read/understand it and not be worried about anything malicious

I had an idea too the table row entries will have a total amount for debt and from the 2 most recent rows say if it went up or down the total debt with an up/down arrow next to the displayed total.

Oh the display's orientation is not what I expected, I need to make sure it can rotate 180 deg before I do the 3D printed part

The hardcoded resolution in the `epd2in13` package seems off my display says 250x122 and they've got it at 212x104 I'll have to see if that matters or it's like that for a reason

4:06 PM

I'm struggling to progress, I ate some food

I installed the dependencies, I slept for like 5 hrs or so, kind of tired

I should at least get this sample code to run

4:50 PM

Yeah... I'm kinda just chilling my bad... I blame it on the poor sleep, the 5 AM bar thing won't last long, once world cup is done

I did set up git on the pi zero w though and pulled the code down there so I can try the display test code

7:28 PM

Alright I had a nap, let me try and fire this up

7:39 PM

This pi zero w is so underpowered takes a while to install stuff

---

### 07/16/2026

10:47 PM

Just updating the pi right now

I found a NodeJS library to drive the e-paper display

I want everything to be one language for this project eg. JavaScript

Also going to use sqlite as it's less work than using mysql client

Still don't have a design in mind for the charts... I see this display can show red that's interesting

The display being a rectangle does dictate what the UI will show
