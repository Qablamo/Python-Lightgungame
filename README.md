# PRIZE SHOOTER  (Dutch version: ALTIJD PRIJS!)

A Sinden lightgun carnival shooting gallery for Batocera, built with LÖVE 11.
Eight fairground stands, a prize shelf full of plushies to win,
synthesized fairground music, and a prize for every player.

## Install on Batocera
This is a LÖVE game, so it goes in the **love** folder (not pygame):
1. Unzip `Prize-Shooter.zip` into `/userdata/roms/love/`
   You get: `prize-shooter.love`, `gamelist.xml`, `images/` and `videos/`
   (box art, logo, screenshot and a preview video for the Batocera menu).
   If you already have a `gamelist.xml` in that folder (other LÖVE games), don't overwrite it:
   copy the `<game>` block from ours into yours instead.
2. Main menu > Game settings > Update gamelists
3. Start "Prize Shooter" from the LÖVE system

## Gun controls (the Sinden acts as an absolute mouse)
- Trigger: shoot
- Pump action / right button (also side buttons 4 and 5): reload
- Shooting into the white border or off-screen also reloads (if your gun reports it)
- Middle button: pause
- No gun? Gamepad (stick aims, A shoots, B reloads, Start pauses) or keyboard
  (arrows aim, Space shoots, R reloads, Esc pauses / quits from the main menu)

### Reload styles (Settings > RELOAD)
- AUTOMATIC: a fresh magazine of corks loads by itself
- MANUAL: pump / right button / shoot off-screen to reload the magazine
- PUMP EVERY SHOT: like a real single-shot carnival air rifle - one cork pellet,
  pump after every shot. The rifle on the counter recoils and racks along with you.

## The stands
- Shooting Stars: 40 shots. The dial calls a color; those stars score 5x. Gold stars 400.
  Black bomb stars cost 200.
- Shark Tooth: shoot out the teeth while the jaws are open. Shoot an eye to daze him.
  Don't hit the brown rotten tooth: he gets angry and chomps like crazy for a few seconds (-150).
- Lucky Ducks: three conveyor rows. Small ducks score more, gold ducks big, bombs cost 250.
- Rail Runners: bullseye 100 / middle 50 / outer 25. Side rails x1.5, pop-ups x2.
  Yellow-black bomb pop-ups cost 200.
- Tin Can Alley: physics stacks of 10 cans; knock them all down. PHOTO target = souvenir photo.
- Heart Shooting: hearts on a spinning wheel; dead center = double. The big heart takes 3 hits.
- Pyramid Shooting: 15 blocks, top layer first. Hitting a lower layer too early costs points.
- Balloon Wall: pop balloons; some hide prize tickets; catch the floating ones.
  Black bomb balloons cost 250.
- Carnival Tour: all 8 stands back to back, one combined score, grand prize at the end.
Hit streaks raise the multiplier up to x5; a miss resets it. Accuracy earns a bonus.

## Your prizes
- Every stand has 5 challenges and 5 prizes in its own theme: Squishy, Big Squishy, Small Plush,
  Big Plush and the Jumbo Grand Prize (perfect challenge). 40 toys in total. The Grand Prizes:
  Shooting Stars: MEGA UNICORN - Shark Tooth: MEGALODON - Lucky Ducks: JUMBO KING DUCK -
  Rail Runners: JUMBO SHERIFF BEAR - Tin Can Alley: JUMBO ALLEY CAT - Heart Shooting: JUMBO HEART BEAR -
  Pyramid Shooting: LIFE-SIZED CAMEL - Balloon Wall: JUMBO PARTY DINO
- PRIZES on the main menu opens Your Prizes (aim at a toy to see how to win it).
  From there: the Prize Counter, Your Bedroom and the Photo Album.
- Tickets: every round pays tickets (score, new toys, tickets found in balloons).
  Trade them at the Prize Counter for a toy you're stuck on. Toys you haven't won show as a "?"
  until you buy them. Grand Prizes are not for sale - they must be won.
- Your Bedroom fills up with every toy you win. Shoot a toy to give it a squeeze.

## Difficulty levels (LEVEL sign on the main menu, or Settings > DIFFICULTY)
- EASY: Kids mode - bigger targets, slower stands, more time, no bombs or rotten teeth, automatic reload, reticle on.
- MEDIUM: reload yourself (pump / right button / shoot off-screen), reticle on, bombs in the duck pond.
- HARD: no reticle, pump after every single shot, bombs.
- CUSTOM: your own choices in the Settings menu.
Every level keeps its own high scores (stands and Carnival Tour), so an Easy score never beats a Hard one.
Changing reload, Kids mode or the reticle yourself switches the level to CUSTOM.
Scores from before the levels existed are kept under CUSTOM.

## Settings
Reload style, Kids mode (bigger targets, slower stands, more time, no bombs; wins squishies),
Players (1, or 2 taking turns on one gun), language (English / Nederlands), music and sound volume,
Sinden border (off / thin / medium / thick), crosshair, theme (evening neon / daytime),
color symbols (shapes on colored targets for color-blind players), fullscreen.

Color-blind symbols, the reticle and music can also be switched on/off straight from the main menu
(the small signs next to the title). With the reticle OFF you aim purely with the gun while shooting;
on menu screens (and the pause menu) the reticle is always shown.

After a minute on the main menu the stands start a demo (attract mode). Pull the trigger to play.
