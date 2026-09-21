# wipe-line

Project page for a **π0.5 policy that erases hand-drawn lines** on a real bimanual ALOHA:
a person draws a line anywhere on a whiteboard, and under the single instruction
`wipe the line` the robot picks up the eraser, wipes that line off and puts the eraser back.

**→ https://theotaoliu.github.io/wipe-line-page/**

The page carries the task description, a step-by-step strip of one attempt, the training
setup, and the full uncut 2:59 recording of five consecutive attempts.

## Do not edit this repository by hand

It is generated. `index.html`, `media/`, `.nojekyll` and this README are mirrored here from
`docs/wipe-line-page/` in the private `openpi` fork by that directory's `deploy.sh`, and the
next sync overwrites whatever is edited here. Change the page there instead.

GitHub Pages publishes this repository through the workflow in `.github/workflows/pages.yml`
(Settings → Pages → Source: "GitHub Actions"), so the site is the repository root.
