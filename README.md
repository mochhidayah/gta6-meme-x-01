[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/mochhidayah/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/mochhidayah/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

# Took a Sick Day for GTA 6

A GTA 6 launch-week meme for the [make.fun bounty](https://make.fun/bounty/gta6-meme-x-01): after 13 years of waiting, a gamer burns a sick day on Vice City — while his AI agent is already earning real money on make.fun. The picture is `meme.png` (1080x1080): a Vice City sunset living room, a gamer on the couch with a controller, the TV glowing with a neon Vice City street, and make.fun's white ghost mascot — sparkle eyes, magenta star coin — sitting on the couch arm with him. Caption in big bold meme lettering: "TOOK A SICK DAY FOR GTA 6" / "MY AI AGENT'S ALREADY EARNING ON MAKE.FUN".

## The meme

- `meme.png` — the final meme, 1080x1080 PNG. Scene generated in-session, caption composited with Python PIL (DejaVu Sans Bold, white with black outline). The ghost in the scene is the make.fun ghost, drawn to match the press-kit mark.
- `media-generation-scene-*.png` — the raw generated scene before the caption was added.

## How to post it

1. Post `meme.png` on X from a public account, with the exact text in `POST-TEXT.txt` (it carries the make.fun bounty link, a tag of @makefunai, and the play code `makefun-horizon-clay-kangaroo`).
2. Copy the post's address (`https://x.com/<handle>/status/<id>`) into `POST.json`, replacing the placeholder.
3. Run the program the way the grader does: `mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts` — it copies `POST.json` to `out/POST.json`.
4. Keep the post up and the account public until the results are out.

## Files

- `main.ts` — the entry program (Node 22, standard library only): copies `POST.json` to the output directory.
- `POST.json` — the post's address on X (placeholder until the meme is posted).
- `POST-TEXT.txt` — the exact text to post with the meme.
- `meme.png` — the meme.
- `AGENT.md` — the bounty's agent guide (from the kit).
