# Step-by-step Mixing Workflow: Track Gain → EQ → Compression (MPC One+)

## Quick goals (before you start)
- Leave **headroom**: final pre-master mix peaks ~ **-6 dB**.
- Track peaks target: **-12 dB to -6 dB** (raw/gain stage).
- Work in this order: **Track Gain → Static Balance → Clean EQ → Compression → Creative EQ/Saturation → Effects → Bus/Master Processing → Automation & Checks**.

---

## 0. Preparation
- Import/trim samples, remove silence/clicks.  
- Label tracks clearly (Kick, Snare, 808, Bass, Lead, Pads, Vox, etc.).  
- Create buses: **Drums Bus**, **Perc Bus**, **Bass Bus**, **Melody Bus**, **Vocal Bus**.

---

## 1. Track Gain (FOUNDATION)
- **When:** first thing after importing audio, before EQ/compression.
- **What to do:** Use the channel gain/fader to set raw level so peaks sit around **-12 to -6 dB**.
- **Why:** prevents pre-EQ clipping and gives room for processors.
- **Quick check:** meters should rarely hit 0 dB, master bus clean.
- **Tip:** If a track is extremely hot, lower gain instead of cutting with EQ.

---

## 2. Static Balance (Faders & Panning)
- **When:** after gain staging, before heavy processing.
- **What to do:** Set rough fader levels to get a good balance — start with **drums + bass** then add other elements. Pan percussive elements for width.
- **Why:** ensures compression/EQ are applied to levels you actually want in the mix.

---

## 3. Corrective (Surgical) EQ — First Pass
- **When:** after static balance, before most compression.
- **What to do:**  
  - HPF non-bass tracks (vocals, synths, pads) around **80–150 Hz**.  
  - Remove resonances (narrow cuts).  
  - Cut obvious mud in **200–400 Hz** with surgical Q.
- **Why:** cleaning low rumble and resonances helps compressors behave predictably.
- **Order note:** Put HPF **before** any compressor on the chain so the compressor doesn’t react to unwanted low rumble.

---

## 4. Compression — Control Dynamics
- **When:** after corrective EQ (and after HPF), once levels are roughly balanced.
- **What to do:**  
  - Use gentle settings to **control peaks** and add consistency.  
  - Typical settings (starting points):  
    - Kick/Snare: **4:1**, Attack **10–30 ms**, Release **50–100 ms**, GR **3–5 dB**.  
    - Bass/808: **3:1**, Attack **20–40 ms**, Release medium, GR **3–6 dB**.  
    - Vocals/Leads: **3:1**, fast attack, medium release, GR **2–5 dB**.  
- **Why:** compressing after cleaning makes the compressor react to musical content (not rumble).
- **Tip:** If you want punch: use **slower attack** to let transients through, faster attack for taming.

---

## 5. Tonal (Creative) EQ — Shape Sound
- **When:** after compression (or use a second EQ after the compressor).
- **What to do:**  
  - Add gentle boosts for presence/air: **2–5 kHz** (presence), **10–12 kHz** (air).  
  - Shape character — small boosts or gentle shelving.
- **Why:** adjusting tone after dynamics gives you a more musical result.

---

## 6. Parallel Processing / Special Techniques
- **When:** after you have basic balance and control.
- **What to do:**  
  - **Parallel compression** for drums/vocals: send to a bus, heavy-compress that bus, blend back in.  
  - **Saturation / Tape emulation**: add warmth on buses (subtle).
  - **Sidechain compression**: duck bass/808 under kick if needed (or automate volume if MPC lacks sidechain).
- **Why:** adds perceived loudness, thickness, and separation without destroying dynamics.

---

## 7. Reverb & Delay (Space)
- **When:** after compression and tonal shaping.
- **What to do:**  
  - Use **sends/aux** for reverb/delay.  
  - HPF reverb sends (cut lows below ~300–500 Hz) so reverb doesn't muddy the low-end.  
  - Use pre-delay (20–40 ms) on vocal reverb to keep clarity.
- **Why:** keeping effects on sends preserves dynamics and keeps processing efficient.

---

## 8. Bus & Master Processing (Glue)
- **When:** after individual tracks are processed and arranged.
- **What to do:**  
  - Apply gentle **bus compression** on drum bus (2:1–4:1, GR 2–4 dB).  
  - Apply **master bus glue** (2:1, slow attack, GR 1–3 dB).  
  - Add final subtle EQ and a limiter: Ceiling **-0.3 to -0.8 dB**, target master LUFS **-8 to -9** (or your target).
- **Why:** bus processing ties elements together and prepares the mix for mastering.

---

## 9. Automation & Final Tweaks
- **When:** after everything sits well together.
- **What to do:** automate volume/pan/reverb sends for dynamic changes (drops, buildups, vocal phrases).
- **Why:** automation brings life and fixes clashes that static processing can't.

---

## 10. Final Checks & Export
- **When:** last step.
- **What to do:**  
  - Check **mono compatibility**.  
  - Compare with **reference tracks**.  
  - Listen on multiple systems.  
  - Export: **24-bit WAV**, master peaking < 0 dB, recommended pre-master headroom ~ **-6 dB**.
- **Why:** ensures translateability and keeps quality for mastering.

---

## Quick Troubleshooting (If something still masks another sound)
- **Vocals buried:** cut competing instrument at **2–5 kHz** or automate that instrument down during vocal phrases.  
- **Kick & bass clash:** use short **sidechain** on bass or carve low mids in bass/kick (boost kick 60–80 Hz, cut bass 70–100 Hz slightly).  
- **Thin sound:** add subtle saturation, small boost at 100–300 Hz for warmth, and a little air at 10–12 kHz.  
- **Harsh top-end:** narrow cut at 2–4 kHz or compress high band lightly.

---

## Mini Cheat (Order-of-operations)
1. **Track Gain** (set peaks -12 → -6 dB)  
2. **Static Balance** (faders/panning)  
3. **Corrective EQ** (HPF, remove resonance)  
4. **Compression** (control dynamics)  
5. **Tonal EQ / Saturation** (shape tone)  
6. **Parallel FX / Sidechain** (thickness & separation)  
7. **Reverb/Delay (sends)** (space)  
8. **Bus Glue & Master Limiter** (cohesion & loudness)  
9. **Automation / Final checks** → Export

---

## Example: Kick channel quick steps
1. Lower track gain so kick peaks ~ **-6 dB** on its channel.  
2. HPF at **30 Hz** (if needed).  
3. Corrective EQ: cut **200–300 Hz** mud.  
4. Compress: **4:1**, attack **10–30 ms**, release **50–100 ms**, GR **3–5 dB**.  
5. Tonal EQ: small boost **60–80 Hz** for thump, boost **2–4 kHz** for click if needed.  
6. Send to drum bus (light bus compression) and proceed.

---

## Final Tips
- Adjust **gain first** — EQ & compression after — this avoids “chasing meters.”  
- Use **two EQs** if needed: one surgical (before comp) and one musical (after comp).  
- Save incremental versions (A/B).  
- Take breaks to avoid ear fatigue.

