# Mods

---

## Fix D-Pad Responsiveness

The d-pad can feel stiff, diagonals may not register well, or one direction might be less clicky than the others. There are a few different things that can cause this.

### Middle Pivot Peg Too Tall

The center peg on the underside of the d-pad can be too tall. It props the d-pad up so the directional pegs don't fully reach the switches, especially when pressing diagonals. Filing the center peg down a little fixes this.

> "What finally seems to have done the trick was to file down the D-pad's middle post just a little bit." — davedane

- davedane — [initial report](https://discord.com/channels/1363136046757318927/1466970817954054205/1544093109665669121), [filing photos](https://discord.com/channels/1363136046757318927/1466970817954054205/1544794555348549652)
- klazo — [confirmed same issue, filed the peg](https://discord.com/channels/1363136046757318927/1466970817954054205/1545263911475880057)
- wavebeam64 — [confirmed the stock dpad doesn't match project STL](https://discord.com/channels/1363136046757318927/1466970817954054205/1547268476375142530)

### Uneven Case Posts

The plastic posts inside the shell that the PCB sits on can be different heights around the d-pad area. This tilts the board so it doesn't make even contact with the d-pad. Check which posts are taller and file them level.

> "For the DIY users I recommend that you try to spot which stems are higher than others instead of just filing down them all." — davedane

- davedane — [instructions and photos](https://discord.com/channels/1363136046757318927/1466970817954054205/1544669281935958109)
- nelson.no — [attempted the trim](https://discord.com/channels/1363136046757318927/1466970817954054205/1544781056555880538)
- eli.eli.eli — originally gave guidance in another channel

### Uneven Actuator Pegs

Some factory d-pads have one actuator peg that's thinner than the other three. That direction feels less responsive and less clicky. The fix is to 3D print a replacement from the official STL.

- davedane — [photo of thin peg](https://discord.com/channels/1363136046757318927/1466970817954054205/1543974164220739685)
- klazo — [confirmed same defect](https://discord.com/channels/1363136046757318927/1466970817954054205/1545039897948201021)
- lag4221 — [confirmed one leg was different](https://discord.com/channels/1363136046757318927/1466970817954054205/1545039897948201021)
- aalu29605 — [asked if all dpads have this](https://discord.com/channels/1363136046757318927/1466970817954054205/1547263257520111769)

---

## Tape Mod for D-Pad Responsiveness

> "after enough playtime the tapes beginning to wear through and diagonals are steadily getting harder to input" — klazo

> "I tried putting tape beneath the middle post too but then I couldn't press any directions" — davedane

- klazo — [initial experiments with tape](https://discord.com/channels/1363136046757318927/1466970817954054205/1544099293219135518), [tape wearing through](https://discord.com/channels/1363136046757318927/1466970817954054205/1545263911475880057)
- davedane — [tried tape under middle post, didn't work](https://discord.com/channels/1363136046757318927/1466970817954054205/1544093109665669121)

---

## 3D Printed / Resin Replacement D-Pad

> "Open source hardware rocks! I can order new 3D printed or resin D-pads from anywhere! (the factory D-pad was faulty)" — davedane

> "I love the d-pad resin prints you did. Makes me want to get custom colors ordered. I would even like to consider a fancier shell." — wavebeam64

> "i wish i had access to several dpads for experimentation but for now this is just my speculation" — klazo

- **Source:** [button_dpad.stl](https://github.com/gamebub/gamebub-mechanical/blob/main/handheld_rev4/button_dpad.stl)
- davedane — [ordered multiple resin prints](https://discord.com/channels/1363136046757318927/1466970817954054205/1543904286172512387), [comparison photos](https://discord.com/channels/1363136046757318927/1466970817954054205/1543974068292947988)
- wavebeam64 — [ordered resin prints](https://discord.com/channels/1363136046757318927/1466970817954054205/1546894919187304509), [tested at 0.08mm layer height](https://discord.com/channels/1363136046757318927/1466970817954054205/1547115451945844919)
- klazo — [planning to order printed dpads for experimentation](https://discord.com/channels/1363136046757318927/1466970817954054205/1544099293219135518)
- forcen — [looking for local 3D printers](https://discord.com/channels/1363136046757318927/1466970817954054205/1546533707039375370)

---

## Button Rattle Silencing

> "If you want to silence the rattling buttons (in my case: power, volume, start, reset, menu) you can fold some paper and put it between the button and the switch. Works perfectly. The folding depends on the thikness of the paper and its easier if you tape the folded paper in itself with some double sided tape." — .h4xx0r.

- .h4xx0r. — [original report](https://discord.com/channels/1363136046757318927/1466970817954054205/1544421608683212892)

---

## Shoulder Button Spring Replacement (Cherry MX)

> "And for the shoulder buttons the Cherry MX switch spring fits perfectly. Used some to make them more stiff (MX clear)." — .h4xx0r.

- .h4xx0r. — [original report](https://discord.com/channels/1363136046757318927/1466970817954054205/1544421608683212892)

---

## Grip Tape / Texture on Back

> "i think the ergonomics are fine but adding Texture to the back would help" — bigoli126

- bigoli126 — [discussion about grip tape and sanding](https://discord.com/channels/1363136046757318927/1466970817954054205/1545486307650969630)
- davedane — [suggested double-sided tape with textured plastic plates](https://discord.com/channels/1363136046757318927/1466970817954054205/1545490052476571659)
- virtualmango — [posted grip experiments with photos](https://discord.com/channels/1363136046757318927/1466970817954054205/1545486162880372889)

---

## Polycarbonate Spray Paint (Translucent Color)

Spray the inside of the clear shell with polycarbonate-safe spray paint for a translucent colored effect. No paint feel on hands since it's on the interior.

- **Paint:** Tamiya PS-45 (and other PS-series polycarbonate paints)
- **Method:** Remove shell, tape off exterior, spray inside surface

> "I made my original Odroid handhelds sort of an atomic purple by removing the shells and taping them off so I could spray the insides of them with Tamiya PS-45 spray paint meant for polycarbonate. It goes on and remains translucent." — esmith13

- esmith13 — [confirmed technique on transparent Odroid handhelds](https://discord.com/channels/1363136046757318927/1466970817954054205/1535344215872118935)