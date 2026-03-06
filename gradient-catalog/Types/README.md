# 1️⃣ Linear Gradient

| Name | Code | What it teaches |
|------|------|----------------|
| Left to Right | `linear-gradient(to right, #e74c3c, #3498db)` | Direction keyword |
| Top to Bottom | `linear-gradient(to bottom, #e74c3c, #3498db)` | Default direction |
| Bottom to Top | `linear-gradient(to top, #e74c3c, #3498db)` | Reverse direction |
| Right to Left | `linear-gradient(to left, #e74c3c, #3498db)` | Opposite direction |
| Diagonal ↘ | `linear-gradient(to bottom right, #e74c3c, #3498db)` | Corner direction |
| Diagonal ↗ | `linear-gradient(to top right, #e74c3c, #3498db)` | Corner direction |
| 45° Angle | `linear-gradient(45deg, #e74c3c, #3498db)` | Degree angle |
| 90° Angle | `linear-gradient(90deg, #e74c3c, #3498db)` | Horizontal angle |
| 135° Angle | `linear-gradient(135deg, #e74c3c, #3498db)` | Diagonal angle |
| 180° Angle | `linear-gradient(180deg, #e74c3c, #3498db)` | Vertical angle |
| 3 Colors | `linear-gradient(to right, #e74c3c, #f39c12, #3498db)` | Multiple stops |
| 4 Colors | `linear-gradient(to right, #e74c3c, #f39c12, #2ecc71, #3498db)` | More stops |
| Color Stop 20% | `linear-gradient(to right, #e74c3c 20%, #3498db 80%)` | Stop position |
| Hard Edge | `linear-gradient(to right, #e74c3c 50%, #3498db 50%)` | Sharp cut, no blend |
| Midpoint Control | `linear-gradient(to right, #e74c3c 30%, #3498db)` | Blend midpoint |
| Transparent Fade | `linear-gradient(to right, #e74c3c, transparent)` | Fade to nothing |
| Double Fade | `linear-gradient(to right, transparent, #e74c3c, transparent)` | Center glow |

# 2️⃣ Radial Gradient

| Name | Code | What it teaches |
|------|------|----------------|
| Basic | `radial-gradient(#e74c3c, #3498db)` | Default radial |
| Circle | `radial-gradient(circle, #e74c3c, #3498db)` | Circle shape |
| Ellipse | `radial-gradient(ellipse, #e74c3c, #3498db)` | Ellipse shape |
| Center (default) | `radial-gradient(circle at center, #e74c3c, #3498db)` | Center origin |
| Top Left | `radial-gradient(circle at top left, #e74c3c, #3498db)` | Corner origin |
| Top Right | `radial-gradient(circle at top right, #e74c3c, #3498db)` | Corner origin |
| Bottom | `radial-gradient(circle at bottom, #e74c3c, #3498db)` | Bottom origin |
| Small Circle | `radial-gradient(circle closest-side, #e74c3c, #3498db)` | Size keyword |
| Large Circle | `radial-gradient(circle farthest-corner, #e74c3c, #3498db)` | Size keyword |
| 3 Colors | `radial-gradient(circle, #e74c3c, #f39c12, #3498db)` | Multiple stops |
| Spotlight | `radial-gradient(circle, white 10%, transparent 70%)` | Glow effect |
| Vignette | `radial-gradient(ellipse, transparent 60%, black 100%)` | Dark edges |
| Inner Glow | `radial-gradient(circle, #f39c12 0%, transparent 60%)` | Center highlight |

# 3️⃣ Conic Gradient

| Name | Code | What it teaches |
|------|------|----------------|
| Basic | `conic-gradient(#e74c3c, #3498db)` | Basic conic |
| Full Color Wheel | `conic-gradient(red, yellow, green, cyan, blue, magenta, red)` | Full rotation |
| Pie — 2 Slices | `conic-gradient(#e74c3c 50%, #3498db 50%)` | Half split |
| Pie — 3 Slices | `conic-gradient(#e74c3c 33%, #f39c12 33% 66%, #3498db 66%)` | 3 equal parts |
| Pie — 4 Slices | `conic-gradient(red 25%, blue 25% 50%, green 50% 75%, yellow 75%)` | 4 equal parts |
| From 45deg | `conic-gradient(from 45deg, #e74c3c, #3498db)` | Start angle |
| From 90deg | `conic-gradient(from 90deg, #e74c3c, #3498db)` | Start angle |
| Custom Position | `conic-gradient(from 0deg at top left, #e74c3c, #3498db)` | Origin point |
| Smooth Wheel | `conic-gradient(red, orange, yellow, green, blue, violet, red)` | Smooth rotation |

# 4️⃣ Repeating Linear Gradient

| Name | Code | What it teaches |
|------|------|----------------|
| Basic Stripes | `repeating-linear-gradient(to right, #e74c3c 0 20px, #3498db 20px 40px)` | Equal stripes |
| Diagonal Stripes | `repeating-linear-gradient(45deg, #e74c3c 0 10px, white 10px 20px)` | 45° stripes |
| Thin Lines | `repeating-linear-gradient(to right, black 0 2px, white 2px 20px)` | Ruled lines |
| Zebra Rows | `repeating-linear-gradient(to bottom, #f5f5f5 0 30px, white 30px 60px)` | Zebra table |
| Thick & Thin | `repeating-linear-gradient(to right, #e74c3c 0 5px, white 5px 30px)` | Unequal stripes |
| 3 Color Stripe | `repeating-linear-gradient(to right, red 0 10px, white 10px 20px, blue 20px 30px)` | Tricolor |
| Blended Stripe | `repeating-linear-gradient(45deg, #e74c3c, #3498db 10px, #e74c3c 20px)` | Gradient repeat |
| Vertical Lines | `repeating-linear-gradient(to right, black 0 1px, transparent 1px 30px)` | Grid lines |

# 5️⃣ Repeating Radial Gradient

| Name | Code | What it teaches |
|------|------|----------------|
| Bullseye | `repeating-radial-gradient(circle, #e74c3c 0 10px, white 10px 20px)` | Concentric rings |
| Soft Rings | `repeating-radial-gradient(circle, #e74c3c, #3498db 20px, #e74c3c 40px)` | Blended rings |
| Radar | `repeating-radial-gradient(circle, transparent 0 15px, #2ecc71 15px 17px)` | Ring outline |
| Dot Pattern | `repeating-radial-gradient(circle, #333 0 3px, transparent 3px 20px)` | Polka dots |
| Glow Rings | `repeating-radial-gradient(circle, #f39c12 0 5px, transparent 5px 30px)` | Glowing rings |

# 6️⃣ Repeating Conic Gradient

| Name | Code | What it teaches |
|------|------|----------------|
| Checkerboard | `repeating-conic-gradient(black 0 25%, white 25% 50%)` | Classic pattern |
| Color Slices | `repeating-conic-gradient(#e74c3c 0 30deg, #3498db 30deg 60deg)` | Repeating slices |
| Sunburst | `repeating-conic-gradient(#f39c12 0 10deg, #e74c3c 10deg 20deg)` | Sun ray effect |
| Pinwheel | `repeating-conic-gradient(#2ecc71 0 45deg, #3498db 45deg 90deg)` | 4 blade spin |
| Fine Rays | `repeating-conic-gradient(#e74c3c 0 5deg, white 5deg 10deg)` | Thin sunrays |

# 7️⃣ Multilayer Gradients

# 🎨 CSS Multilayer Gradient Practice

| Name | Code | What it teaches |
|------|------|----------------|
| Stripe over color | `repeating-linear-gradient(45deg, rgba(0,0,0,.1) 0 5px, transparent 5px 10px), linear-gradient(to right, #6a11cb, #2575fc)` | Layer stacking |
| Spotlight on dark | `radial-gradient(circle at 30% 30%, rgba(255,255,255,.15), transparent 60%), linear-gradient(135deg, #1a1a2e, #16213e)` | Light on dark |
| Double linear | `linear-gradient(to right, rgba(255,0,0,.3), transparent), linear-gradient(to bottom, blue, purple)` | Two directions |
| Grid pattern | `repeating-linear-gradient(to right, rgba(0,0,0,.05) 0 1px, transparent 1px 40px), repeating-linear-gradient(to bottom, rgba(0,0,0,.05) 0 1px, transparent 1px 40px)` | CSS grid lines |
| Radial + linear | `radial-gradient(circle at top right, #f39c12, transparent 50%), linear-gradient(135deg, #e74c3c, #8e44ad)` | Mixed types |
