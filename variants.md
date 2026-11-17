# Variants - one field changed at a time

Base: `tamil_prompt.json` - a Chettinad courtyard in Karaikudi at first light
during Margazhi, medium shot. All images generated from the same JSON pasted
as the prompt.

| Image | Field changed | New value | Expected effect |
|-------|---------------|-----------|-----------------|
| `images/1_base_dawn.png` | (none - base template) | - | The scene as designed |
| `images/2_golden_hour.png` | `setting.time_of_day` + `lighting` | "golden hour" / "warm low sun across the courtyard, long shadows" | Same scene, warmer and more directional |
| `images/3_close_up.png` | `camera.shot` + `camera.lens` | "close-up" / "85mm" | Same scene, tight on the hands and jasmine |

Video: the `motion` block in the JSON extends the same template for a 5-second
clip (slow push-in, hands threading the garland). Run it in a video tool that
accepts JSON prompts; the scene fields stay identical to the base image.
