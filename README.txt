GANESHA VS. ANALASURA — THE FIRE WITHIN

Files:
- index.html : complete HTML/CSS/JavaScript comic reader
- images/    : add cover.png and page_001.png through page_012.png

Artwork filenames:
cover.png
page_001.png
page_002.png
page_003.png
page_004.png
page_005.png
page_006.png
page_007.png
page_008.png
page_009.png
page_010.png
page_011.png
page_012.png

audio/track1-fire_rising.mp3     -> plays on pages 1–4  (Analasura's rampage)
audio/track2-divine_answer.mp3   -> plays on pages 5–9  (Ganesha's confrontation)
audio/track3-cooling_grace.mp3   -> plays on pages 10–12 (durva grass / resolution)

MUSIC BEHAVIOR
--------------
- Each track loops seamlessly on its own while the reader stays within
  its page range — nothing restarts or cuts out if the user lingers.
- Moving into a new range (e.g. page 4 -> page 5) automatically
  crossfades from the old track into the new one.
- Moving backward works the same way — tracks switch based on
  whichever page you land on, not just forward navigation.
- The music mapping lives in the `musicRanges` array near the top of
  the <script> section in index.html — edit the `upToPage` numbers or
  filenames there if you want different boundaries or track names.

Features:
- 12-page cinematic comic reader
- speech bubbles and narration
- fire, battle, divine and cooling visual effects
- subtle zoom, flash and shake effects
- swipe navigation on touch devices
- keyboard navigation
- clickable progress dots
- responsive mobile/desktop layout
- background music toggle
- missing-image placeholders
- story note about regional/devotional variations
- final Ganpati Bappa Morya-ready ending screen

No framework or backend is required. Open index.html in a browser.

Jai Ganesha! Ganpati Bappa Morya! 🙏
