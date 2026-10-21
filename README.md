# Killer 2s — iPhone beta

**Shed your hand. Save your 2s. Take the pile.**

A shedding card game (Tiến Lên / "Thirteen" / "Killer" — with our own ladder, kills and bombs) and a roguelike run
on top. Beta by **Devious Developments**.

## Install with AltStore (updates itself)

1. In **AltStore** → **Sources** → **+**, add this source:
   `https://raw.githubusercontent.com/yodahlorian/killer2s-beta/main/source.json`
2. Open **Devious Developments** → **Killer 2s** → **Free / Get**. New betas show up as updates in AltStore.

## Install by hand (Sideloadly)

1. Download the newest `Killer2s-<version>.ipa` from **[Releases → Latest](../../releases/latest)**.
2. Install it with **[Sideloadly](https://sideloadly.io)** (Windows / macOS) or **AltStore**, signing with your own Apple ID.
3. On the phone: **Settings → General → VPN & Device Management** → trust your Apple ID's developer profile.
4. Play in landscape.

A free Apple ID signs apps for 7 days; re-sideload to refresh. Each new beta replaces the file (one release, one file).

## Changelog

Newest first. 

### 0.6.8 — 2026-10-20
- The iPhone app now says plainly that it never uses the camera, microphone or photos.
- The pause menu re-centres itself if the phone rotates while it's open.

### 0.6.7 — 2026-10-20
- Fixed: opening the iPhone app switcher froze the game and hid the pause button. Now the pause menu opens when you come
  back, and a paused game with no menu showing unpauses itself.
- **Peek works straight away**: use it at the table and the next opponent's whole hand turns face up for the rest of that
  table (it used to wait for the next table).

### 0.6.6 — 2026-10-20
- **Clear stacking rules**: every enhancement trick now says what it is and what it stacks with: a MATERIAL (Gold,
  Stone), a FINISH (Holo, Chrome, Foil) or a MARK. A card holds one of each.
- **Replace warning**: using a bonus that would push one off (Holo on a Chrome card) asks first, "Replace with Holo" or
  "Keep it". The same bonus twice is refused, so you don't waste the trick.
- After a bonus stacks, the table tells you what the card is now ("now Stone + Holo + Marked").

### 0.6.5 — 2026-10-20
- **Enhanced cards shine**: every enhancement now has a live, moving finish, with the rank and pips inked on top.
  **Holo** is a rainbow film that shifts as you move (Balatro-style), **Chrome** has mirror bands that sweep across,
  **Foil** ripples blue-silver, **Gold** has a rolling sheen and twinkling glints, and **Stone** catches the light.
  On iPhone, tilt the phone and the light moves; on PC, it follows the mouse. Works on every deck.
- **Your own sort**: Sort now cycles by rank, by suit, and **by plays**: your hand chained into the fewest plays with the
  fewest cards left over, laid out singles, pairs, trips, runs, then your 2s.
- **Bonuses stack, one of each kind**: a card can have a material (Gold or Stone), a finish (Holo, Chrome or Foil) and a
  Mark, all at once, and each one pays. A new bonus of a kind the card already has replaces the old one.
- **Purchase confirmation in the Locker**: the first tap on a card for sale selects it and shows what it does; tap it
  again to buy. Tapping anywhere else cancels.
- **The Snitch works**: each opponent's highest card shows face-up on their seat, and updates as they play.
- **Pause menu**: the pause button in the table's top-left corner (or Esc / Start on a controller) stops the table:
  the CPUs wait, nothing moves. From it: Resume, **Sound** (volume and mute, remembered), How to play, and
  **Quit run** (it asks first) or Main menu at a quick table. On iPhone, leaving the app pauses the table too.
- **Peek works**: the next opponent's whole hand shows face-up for that table.
- Fixed: after a run, the main menu's deck cards kept that run's enhancements (stone Aces on the deck picker).

### 0.6.4 — 2026-10-20
- **Full Set, tightened**: the four have to be played together, one straight after another. If any other play lands in
  between (say a 5, then a 7, then a pair of 5s), the last 5 is just a 5.

### 0.6.3 — 2026-10-20
- **FULL SET, a new kind of kill**: when all four of a card end up on the stack, whoever lays the last of them wins it
  on the spot, whatever the suits. Got the other two 3s when someone plays a pair of 3s? Drop them: the stack clears,
  the pile is yours and you lead. A pair onto a single works too. In a run it scores like a KILL.
- **Faces at the table**: every opponent (and every boss) has a hand-drawn polaroid of their own, taped to their seat,
  in place of the numbered circle.
- **Shop info icons**: tap the little ⓘ on any card in the Locker to read what it does, with no more buying by accident.

### 0.6.2 — 2026-10-20
- **New app icon**: all four 2s fanned out in your hand, ♠ ♣ ♦ ♥, so every suit shows. On PC (exe, window, browser tab)
  the background is invisible, just the cards; on iPhone they sit on the studio dark (iOS doesn't allow see-through icons).
- First release to carry the 0.6.1 changes below (0.6.1 itself never went out).

### 0.6.1 — 2026-10-19
- **No more Godot logo anywhere**: the iPhone launch screen, the browser loading page and the PC boot all open on the
  studio dark, straight into our splash.
- The **PC exe carries the Killer 2s icon** and "Killer 2s · Devious Developments" in its file details.
- The title screen shows the new tagline: *Shed your hand. Save your 2s. Take the pile.*

### 0.6.0 — 2026-10-19 · "Killer 2s"
- **New name: Killer 2s** (was "Kill: TCG"). Tagline: *Shed your hand. Save your 2s. Take the pile.*
- **Studio splash**: the Devious Developments logo, then the title written on notebook paper. No more Godot stand-ins on boot.
- **App icon**: the 2♥ on green felt (window, browser tab, iPhone).
- **iPhone build** (this page) — sideload with Sideloadly or AltStore.
- It's all **Kills and Bombs**: "chop" is gone; a bomb on 2s is a BOMB.
- The top AI level is now **Kingpin**.

### 0.5.5 — 2026-10-19
- **Landscape on phones**: a phone held upright shows "turn your phone sideways"; Android locks landscape in fullscreen.
- The **Table Card** (right-hand panel) fills the whole column.
- **Tap/click the Table Report** to finish the handwriting instantly.
- **Enhanced cards stand out**: a thick rim in the material's colour + a sticker badge.
- The Locker's focus ring hugs the button (it was enormous).
- Table numbers read per circuit — "1 / 3", "2 / 3", "BOSS" (they showed 4/3, 6/3).
- Table Report: "RESULT" stamp box; "Paid out … (the House)".

### 0.5.4 — 2026-10-19
- **Table Card**: the run's side panel is a photocopied form — score, this play (points × cards), crew and tricks taped in.
- **Collection**: found items taped in; tricks, bosses, decks and enhancements on single lines.
- **Enhancement textures**: Holographic shimmers, Stone is granite, Chrome, Foil, Gold leaf, Marked — on cards and tiles.
- **Bombs play on any stack**, like kills; only a bigger bomb beats a bomb.
- Fixed: a card that could stand in a run was greyed out (any suit works in a run).
- Circuit map path no longer runs behind the names. How to Play rewritten (two pages).
- Renamed the opponent "Tardy Tom" → "Snooze Button Sid".

### 0.5.3 — 2026-10-19
- **Table Report** and **The Locker** are photocopied forms: blanks filled in by pen, the maths written out, items taped in.
- **Drag cards onto the pile to play** (green = legal, red snaps back).
- Locker hover text fixed; the title menu fits on every screen.

### 0.5.2 — 2026-10-19
- **New hand order**: single < pair < run of 3 < suited run of 3 < three of a kind < run of 4 < suited run of 4 < … < 2s.
- **The round ends the moment you go out** — your sweep is one big total.
- **Crew** (was "Accomplices"): 32 hand-drawn crew cards. Text sits on the notebook lines.

### 0.5.0 – 0.5.1 — 2026-10-18/19
- **Scoring = points × cards**: every play, every **pile** you take, and the **sweep** of every card left when you go out first.
- **Runs start one-on-one**, then 1 vs 2, then the full table.
- Opponents have names; every venue has its own table cloth.
- **Bomb ladder**: four of a kind < 3 pairs < 3 triples < 4 pairs < 4 triples < 5 pairs.
- Mixed-suit straights fixed; drag to sort; shortcut letters in the buttons; plays stay on the pile until it clears.
- Scaling crew multiply your score all run — the shop matters. Version shown on the title.

### 0.4.x — 2026-10-18
- Rules adopted from **Tiến Lên**, with our own **extended plays** (a higher play beats any lower one) and **2s kill**.
- Web + phone layouts, controller support, eight deck arts, a calmer Notebook card back.

### 0.1 – 0.3 — 2026-10-18
- The first builds: rules engine, six AI levels, the roguelike run (circuits, bosses, the Locker), deck arts.
