# JSON Prompting for Tamil Visuals - Social Eagle Week 2 Day 2

One reusable JSON template for culturally specific Tamil visuals. Each decision
lives in its own field, so you change one thing and hold the rest still.

## Files

- `tamil_prompt.json` - the reusable template: subject, setting (place, era,
  time of day), lighting, camera (shot, lens, angle), palette, style, aspect
  ratio, avoid list, and a `motion` block for video.
- `variants.md` - the three generated images and exactly which field changed
  between them.
- `images/` - the generated images.

## The scene in one sentence (decided before any JSON)

An elderly Chettiar woman stringing a jasmine garland in the teak-pillared
courtyard of a Chettinad mansion in Karaikudi, at first light in Margazhi,
with a fresh kolam on the damp Athangudi tiles.

Specifics chosen on purpose: Chettinad architecture is not Thanjavur, a
Kanchipuram silk is not a generic sari, and a Margazhi dawn is not any
morning. The avoid list keeps out the postcard cliches and modern intrusions.

## How to reuse

Change one field at a time and regenerate. If your tool takes plain text,
paste the whole JSON as the prompt.
