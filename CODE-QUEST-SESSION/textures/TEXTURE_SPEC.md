# CODE QUEST - Texture Specifications

Use these specs when asking ChatGPT to generate textures.
All textures should be **256x256 pixels** PNG format with transparency where noted.

---

## PLAYER TEXTURES

### player_torso.png
- **Size:** 256x256
- **Style:** Futuristic green armor/tech suit
- **Details:** Glowing circuit patterns, metallic segments, cyber warrior look
- **Colors:** Green (#00ff00) as primary, cyan (#00ffff) accents

### player_head.png
- **Size:** 256x256
- **Style:** Sci-fi helmet with visor
- **Details:** Smooth helmet with glowing visor slit, tech patterns
- **Colors:** Green base, cyan visor glow

### player_arm.png
- **Size:** 256x256
- **Style:** Armored arm segments
- **Details:** Mechanical joints, armor plating
- **Colors:** Darker green (#00cc00), metallic highlights

### player_leg.png
- **Size:** 256x256
- **Style:** Armored leg segments
- **Details:** Knee guards, boot details, armor plating
- **Colors:** Dark green (#009900), metallic

### player_weapon.png
- **Size:** 256x256
- **Style:** Energy blade / cyber sword
- **Details:** Glowing blade, tech handle
- **Colors:** Cyan (#00ffff) blade, gray handle

---

## ENEMY TEXTURES

### enemy_torso.png
- **Size:** 256x256
- **Style:** Menacing red armor / demon tech
- **Details:** Spiky, aggressive look, glowing cracks
- **Colors:** Red (#ff0000) primary, orange (#ff6600) accents

### enemy_head.png
- **Size:** 256x256
- **Style:** Evil helmet/skull face
- **Details:** Yellow glowing eye visor, menacing shape
- **Colors:** Dark red, yellow (#ffff00) eyes

### enemy_arm.png
- **Size:** 256x256
- **Style:** Clawed arm armor
- **Details:** Sharp edges, battle-worn
- **Colors:** Dark red (#aa0000)

### enemy_leg.png
- **Size:** 256x256
- **Style:** Heavy armored legs
- **Details:** Stomping boots, thick armor
- **Colors:** Dark red (#880000)

### enemy_claw.png
- **Size:** 256x256
- **Style:** Three-fingered claw weapon
- **Details:** Sharp metallic claws, glowing orange
- **Colors:** Orange (#ff6600), metallic

---

## ENVIRONMENT TEXTURES

### ground.png
- **Size:** 512x512 (tileable)
- **Style:** Tech floor / arena ground
- **Details:** Grid pattern, metallic plates, subtle glow lines
- **Colors:** Yellow (#ffdd00) base, orange (#cc8800) grid lines

---

## CHATGPT PROMPT TEMPLATE

Copy this prompt to ChatGPT:

```
Generate a 256x256 pixel game texture for [TEXTURE NAME].
Style: [STYLE from above]
Details: [DETAILS from above]
Colors: [COLORS from above]
The texture should be seamless/tileable if possible.
Make it look like a retro-futuristic video game texture.
Output as PNG.
```

---

## FILE NAMING

Save generated textures with these exact names in the textures folder:
- player_torso.png
- player_head.png
- player_arm.png
- player_leg.png
- player_weapon.png
- enemy_torso.png
- enemy_head.png
- enemy_arm.png
- enemy_leg.png
- enemy_claw.png
- ground.png
