# Comfort Zones Garden Design, a review draft

A one-page site for Marilee Kuhlmann's garden design studio, Comfort Zones. Review draft, October 2026: it is marked
`noindex` and will move to czgardens.com once Marilee is happy with it.

    python3 -m http.server 8791 --directory .     # then open http://localhost:8791

## How it is made

- **Look:** Marilee's own colours, measured from her garden photographs (dusk plum #382e40, evening lavender #8992c0,
  aloe rust #b4532e, eucalyptus night #23271f, olive #4d5c41, decomposed-granite sand #ebe3d6) and her sage green
  #7cb68b. Lato for the mark and headings, Newsreader for the words.
- **Motion:** measured from kingriver.com.au with Art Globe's look-and-feel reader: smooth scroll (Lenis), things that
  rise 42 px and fade in on cubic-bezier(0.22, 1, 0.36, 1), photographs that settle from a slight zoom, a pinned
  sideways track for the process, an intro curtain, a wordmark that comes into focus.
- **Gardens:** eleven projects designed by Marilee with Urban Water Group, each opening a full-screen gallery
  (`img/projects/`, descriptions in `img/projects/projects.json`). Photographs by Saxon Holt and Urban Water Group.

## Still to settle with Marilee

1. The wording, everywhere: change anything that does not sound like her.
2. Which gardens to show, and how to credit Urban Water Group and Saxon Holt.
3. A larger portrait (`img/marilee.jpg` is 500x667), and any colours or logo she already uses.
4. Phone or service area beside marilee@czgardens.com, if she wants them.
