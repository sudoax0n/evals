# 2026-08-28 Orbital Salvage

<p align="center">
  <img src="hero.png" alt="A salvage craft and utility drone working between a damaged orbital station and a satellite above Earth at sunrise." width="100%">
</p>

One prompt, five models, one self-contained HTML file each.

- Claude Opus 5 Max: [claude-opus-5-max/index.html](claude-opus-5-max/index.html)
- GPT-5.6 Sol xhigh: [gpt-5.6-sol-xhigh/index.html](gpt-5.6-sol-xhigh/index.html)
- GPT-5.6 Luna Max: [gpt-5.6-luna-max/index.html](gpt-5.6-luna-max/index.html)
- Muse Spark 1.2: [muse-spark-1.2/index.html](muse-spark-1.2/index.html)
- MiniMax M3: [minimax-m3/index.html](minimax-m3/index.html)
- Exact prompt: [prompt.md](prompt.md)
- Labeled Opus 5 Max vs Sol xhigh video: [opus-5-max-vs-gpt-5.6-sol-xhigh.mp4](opus-5-max-vs-gpt-5.6-sol-xhigh.mp4)

The original labeled 2×2 recording stays on X. The later Opus 5 Max vs Sol xhigh side-by-side is included here because it is the direct follow-up to this run.

## What showed up on screen

**Claude Opus 5 Max** made the strongest film in this run: the harsh sunrise, silhouettes, industrial wreckage, work lights, and camera choreography gave the salvage mission a scale the other outputs did not reach. Sol's repair state remained easier to score literally.

**GPT-5.6 Sol xhigh** made the strongest complete sequence in this run. The approach, dock, red-to-green repair, deployed arrays, and final sunrise stayed readable. The drone's remove-and-return chain was less explicit than Luna's close-up.

**GPT-5.6 Luna Max** was the closest challenger and made the clearest repair-drone close-up. Its camera work had more drama, but both solar arrays were not shown unfolding as clearly as Sol's.

**Muse Spark 1.2** showed a simpler red-to-green repair. The service craft arrived abruptly, the drone chain was hard to follow, and the arrays did not visibly complete the requested deployment.

**MiniMax M3** established an approach, then lost the active subject in near-empty green frames for roughly ten seconds. The dock, drone repair, state change, and array deployment never formed a readable chain.

Short version: Opus 5 Max made the better film. Sol xhigh made the repair easier to score. Luna Max still separated from Muse Spark and MiniMax M3.

## Video alignment

The raw 32-second recordings began late in each authored loop. For the X comparison, each clip was cut at its true restart and the leading end-of-loop fragment was appended to the back:

| Model | Restart cut |
|---|---:|
| Claude Opus 5 Max | 3.50s |
| GPT-5.6 Sol xhigh | 1.65s |
| GPT-5.6 Luna Max | 1.9s |
| Muse Spark 1.2 | 0.9s |
| MiniMax M3 | 3.4s |

No frames were dropped. Every aligned pane remains 32.000 seconds, 1,920 frames, and 60fps.

## Provenance

Abhinav supplied the same Orbital Salvage prompt manually to all five runs. Every clean-workspace input manifest records the same 2,020-byte prompt and SHA-256 `4e6dd75858e0b2c18c6eb35aed5fe2641a07a5181c75bbd9861c37af09162e17`.

Sol's run record identifies `gpt-5.6-sol-xhigh` with the `codex-clean-xhigh-manual-download` harness. Luna, Muse, and MiniMax came from manual Arena downloads. The Opus output was supplied as a finished ZIP; its exact harness was not recorded, so it remains explicitly unspecified rather than guessed. The MiniMax display name follows the operator's run record; its saved manifest label is the literal `m3`.

The files below are byte-identical copies of the saved model outputs:

| Model | Bytes | SHA-256 |
|---|---:|---|
| Claude Opus 5 Max | 64,209 | `cb97154a6457678a76a3273c2dba55e2835be40b10108553fb97ec9e5f2ad850` |
| GPT-5.6 Sol xhigh | 38,359 | `177e6addbc8e0c9417ffa9c9b13face61c9813588015b245671bf79c0e455405` |
| GPT-5.6 Luna Max | 48,013 | `dea2085cf16166fef95a8f91113bca8772c999d5c5fa7a1653b2b1669e563bc4` |
| Muse Spark 1.2 | 59,273 | `f491b1840cce1103af45a14c8625c5c6392afdb447b9106f58c13edcda694bd5` |
| MiniMax M3 | 45,926 | `529bb9041376a432d8174e0986309080935a376993f9885437a7bf02377c8e41` |

This is one run per model, not a statistical benchmark. The pages load Three.js from a CDN at runtime. The included side-by-side is 1920×640, 60fps, and 32 seconds. Each pane was rotated to its exact authored loop opening without dropping frames; only the model names are burned in. Local paths, operator notes, browser profiles, and other recording artifacts were excluded.

## Generation chats

Not included. No clean generation-chat exports were present beside these four outputs.
