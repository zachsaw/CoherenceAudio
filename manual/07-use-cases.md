# Use Cases

This chapter provides practical setup scenarios for four common real-world recording situations.

### The Coherence Audio Advantage: Pro Mixing on a Budget
In professional studios, engineers capture separate, perfectly synced tracks for independent mixing. Standard recording software cannot do this reliably with multiple USB microphones because each mic has its own internal clock, leading to audio drift and phase issues.

Coherence Audio’s drift correction acts as a virtual "master clock" for your USB microphones. It gives you the exact same multi-track flexibility as a high-end studio setup—allowing you to record and mix each microphone independently—without the expensive hardware.

### Total Cost of Ownership (TCO) Comparison
To understand the financial advantage of Coherence Audio, let’s compare the cost of building a standard 4-track recording setup (like a podcast or band recording) from scratch:

**Traditional XLR Setup**
*   **4-Channel Audio Interface:** $150 – $400+ *(e.g., Behringer UMC404HD or Focusrite Scarlett)*
*   **4x XLR Microphones:** $200 – $400+
*   **4x XLR Cables:** $60 – $80
*   **Total Cost:** **$410 to $880+**

**Coherence Audio USB Setup**
*   **Audio Interface:** $0 *(Coherence Audio replaces this)*
*   **4x USB Microphones:** $200 – $400+
*   **Powered USB Hub / Extension Cables:** $40 – $60
*   **Total Cost:** **$240 to $460+**

**The Verdict:** Even if you spend the exact same amount on microphones, Coherence Audio cuts your total hardware costs nearly in half by eliminating the interface and XLR cables. *(Furthermore, everyday guests are much more likely to already own a standard USB microphone than an XLR microphone, which can drop your actual out-of-pocket costs even lower).*

---

## Hardware Guidelines & Best Practices

Before diving into specific recording scenarios, it is crucial to understand the physical limitations of USB audio.

1. **Powering Multiple Microphones:** USB microphones require stable 5V power. Avoid unpowered USB hubs, as splitting a single port's power across multiple microphones causes dropouts. If using a laptop, use a wall-powered docking station (Thunderbolt or high-quality USB-C). For desktop PCs, plug microphones directly into the motherboard ports on the back of the computer.
2. **USB Cable Length Limits:** Standard passive USB cables have a strict maximum length (5 meters/16.4 feet for USB 2.0; 3 meters/10 feet for USB 3.0). If you need longer runs to reach instruments or guests, you **must use Active USB Extension Cables** (which feature built-in signal repeaters) to prevent audio dropouts.

---

## The Universal Coherence Audio Workflow

No matter which of the following use cases you are recording, the core software workflow remains exactly the same:

**1. Recording**
Plug in all your USB microphones. In Coherence Audio, simply add one track per USB microphone. Designate your highest-quality microphone as the clock master, enable **Drift Correction (Pro)**, and hit record. Coherence Audio will capture each microphone as a completely independent, time-aligned track.

**2. Post-Production & Mixing**
Once your recording is finished, Coherence Audio allows you to export your perfectly synced tracks directly to an **Audacity LOF file**. Open this file in Audacity (or import the audio files into your DAW of choice) to apply EQ, compression, noise reduction, and panning to each track independently, just like a professional studio.

---

## Use Case 1 — Podcast Interview (2–4 People)

**The scenario:** You are recording a podcast with two to four guests, each speaking into their own microphone. You want each voice on a separate track for independent editing and level adjustment.

**Why Coherence Audio?**
Recording four people simultaneously usually requires a multi-channel audio interface and expensive XLR cables. Coherence Audio lets you and your guests use simple USB microphones—no interface, no complex driver configuration, and no audio drift.

**Hardware Setup:**
*   **Host:** A premium USB dynamic or condenser microphone.
*   **Guests:** Standard, good-quality USB microphones.
*   **Placement:** Position each microphone 10–20 cm from the speaker's mouth to minimize room echo.

---

## Use Case 2 — Band Recording (Multi-Instrument Live Take)

**The scenario:** A band wants to record a live rehearsal or performance where each instrument (vocals, acoustic guitar, bass, cajon) is captured on its own microphone for a separate mix.

**The Challenge:**
Band recording requires several inputs simultaneously. A traditional approach uses a multi-channel USB audio interface that accepts multiple XLR inputs, costing hundreds of dollars. Coherence Audio lets you use multiple lower-cost USB microphones—one per source—as completely independent tracks. *(Note: You will likely need Active USB Extension cables to reach all instruments).*

**Hardware Setup:**
*   **Lead vocals:** USB dynamic microphone.
*   **Acoustic guitar:** USB condenser microphone positioned at the 12th fret.
*   **Bass (DI or amp):** USB dynamic microphone in front of the amp, or a basic USB guitar interface.
*   **Cajon / percussion:** USB condenser or dynamic microphone, positioned 30–50 cm from the instrument.

---

## Use Case 3 — Piano Recording (Close Mics + Room Mics)

**The scenario:** Recording a grand or upright piano using two microphones on the instrument (stereo close-mic) and two room microphones to capture the acoustic environment.

**Why This Is Demanding:**
Piano recording is highly phase-sensitive. Any timing misalignment between microphones—even a fraction of a millisecond—will cause **comb filtering** (a hollow, unnatural sound). This use case is the strongest argument for enabling Coherence Audio's drift correction. Without it, residual clock drift between USB microphones will inevitably ruin the phase alignment of the recording.

**Hardware Setup:**
*   **Close Mics:** Two matched USB condenser microphones placed near the piano strings/hammers. (Using matched pairs ensures identical frequency response).
*   **Room Mics:** Two additional USB microphones placed further back in the room to capture the natural reverb.

---

## Use Case 4 — Audiophile Microphone Comparison

**The scenario:** You want to objectively compare the sound character of two or more microphones recording the same source simultaneously (e.g., comparing a budget USB microphone against a high-end USB condenser).

**Why This Is Uniquely Suited to Coherence Audio:**
A single USB recording device cannot run two microphones simultaneously into separate, unmixed channels. Coherence Audio solves this by recording each USB microphone as its own completely independent stream. Each microphone's character is preserved exactly as captured, with no shared preamps or converters to color the sound.

**Hardware Setup & Testing:**
*   **Placement:** Position all microphones at the exact same distance and angle from the source. Identical placement is critical for a fair comparison.
*   **Gain Matching:** Adjust the input gain so all tracks peak at the exact same level (e.g., -12 dBFS). This prevents loudness bias.
*   **Source Material:** Record a mix of spoken word, broadband noise (white/pink noise), musical transients (claps/snaps), and pure silence.
*   **Analysis:** Export to Audacity to visually compare noise floors, plot frequency spectrums, and perform blind A/B listening tests.