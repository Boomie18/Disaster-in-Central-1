# The Curriculum Time Machine

Interactive live classroom motivation activity for the master's report **Curriculum Reforms in Teacher Education — Enhanced Teacher Education Curriculum Anchored on Outcome-Based Education**.

## Live participation
1. Presenter opens the activity and selects **Launch as Presenter**.
2. A room code and QR code appear.
3. Participants join on their phones.
4. The class moves through three reform moments: **2004 → 2012 → 2017**.
5. Participants make curriculum-design decisions; the presenter sees live response patterns.

## Technical approach
- Static HTML/CSS/JS, suitable for GitHub Pages or another static host.
- PeerJS handles WebRTC data connections. The presenter acts as the live room hub.
- QR code is generated in-browser.
- Interaction sounds use the browser Web Audio API, so no audio files are required.
- Google Fonts: DM Sans + Space Grotesk.

## Facilitation
Keep the presenter screen projected. After Round 3, transition with:
> “The curriculum has changed. But the real question remains: What kind of teacher does our curriculum actually prepare?”

Then introduce the formal discussion of OBE and the Enhanced Teacher Education Curriculum.

## Hosting
The repository folder is ready for static hosting. GitHub Pages must be enabled for the repository before a public Pages URL becomes available.
