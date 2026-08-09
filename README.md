# Pawan Kumar - Cinematic Portfolio

**Condensed, cinematic portfolio with video hero and Three.js animations.**

## What Changed

### Structure
- **Was:** 10 sections, ~6 minute scroll
- **Now:** 5 sections, ~2-3 minute scroll

### Sections
1. **Hero** - Your talking-head video + Three.js warm particles + "India to France" overlay
2. **Story** - Timeline combining Maritime → Alliance → EDHEC into one flowing section
3. **Now** - Vanivert AI current work
4. **Proof** - LBO + IM deliverables side by side
5. **Connect** - Contact links + embedded chat questions

### Removed
- ✅ Chapter transition cards (no more waiting timers)
- ✅ Verbose text (everything condensed)
- ✅ Separate sections for Ocean, Builder, Pivot, Beginning, Education, Languages

### Added
- ✅ Fullscreen cinematic video hero
- ✅ Three.js floating particles (warm orange, additive blending)
- ✅ GSAP-style scroll animations
- ✅ Timeline with visual dots (combines your 3 careers)
- ✅ Embedded chat questions (16 recruiter Q&A)
- ✅ Video controls (play/pause, mute/unmute)

## Deploy

Same as before:

```bash
cd portfolio-v2
npx vercel --prod
```

Or drag the `portfolio-v2/` folder onto **vercel.com/new**.

## Assets

- `assets/hero-video.mp4` - Your talking-head video (6.6MB)
- `assets/*.jpg` - Your photos (for future sections if needed)

## File Size

- HTML: 31 KB
- Video: 6.6 MB
- Photos: ~500 KB
- **Total:** ~7.1 MB

## Browser Support

- Chrome, Safari, Firefox, Edge (modern versions)
- Mobile responsive
- Three.js requires WebGL (99%+ support)

## Next Steps

1. Deploy and test
2. If approved, I'll add:
   - Airplane animation on hero (India → France flight path)
   - Ship/wave animations for maritime timeline item
   - Server network for Alliance timeline item
   - Voice waveform for Vanivert section
   - ElevenLabs voice integration (when you share API key)

---

**Designed in Lille · 2026**
