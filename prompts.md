维度1：整体轮廓与形状
Please describe the following aspects:
- Basic geometry: Which geometric form does the object most closely resemble? (e.g., cuboid, cylinder, sphere, cone, flat disc, irregular organic shape)
- Aspect ratio: Is the overall form elongated, squat/stout, or roughly proportional?
- Symmetry: Is it axially symmetric, centrally symmetric, or completely asymmetric?
- Edge characteristics: Are the edges sharp right angles, rounded chamfers, wavy, or irregular?
- Contour complexity: Is the silhouette clean and smooth or complex with multiple protrusions?
- Overall visual impression: Summarize the first impression of the object's contour in one phrase (e.g., sturdy and solid, slender and elegant, compact and square)
[CONSTRAINT] Describe only visible contour features; do not infer the shape of occluded parts.


维度2：可见部件与结构组成
Please analyze in the following hierarchy:
- Component inventory: List all independently identifiable visible components (down to at least secondary sub-components)
- Component function: What function does each component serve? (e.g., support, containment, connection, operation, decoration)
- Spatial layout: Relative positional relationships between components (top/bottom, front/back, inner/outer, left-right symmetry, etc.)
- Connection method: How are components joined together? (integrated molding, screw-fixed, snap-fit, hinge, plug-in, welded, etc., if visible)
- Structural features: Does it have layered structures, folding mechanisms, hollow designs, cantilever structures, mesh structures, etc.?
- Proportional relationships: Size ratios between major components (e.g., base occupies 1/3 of overall height, pillar diameter approximately 1/5 of tray width)

[CONSTRAINTS]
- List only components actually visible in the image
- Mark connection methods as "not visible" for unclear areas
- Organize description using "main body - component - sub-component" hierarchy

维度3：颜色、纹理与材质
Please analyze in detail:

[COLOR]
- Dominant color: The color occupying the largest area (use standard color names, e.g., navy blue, champagne gold, matte black, ivory white)
- Secondary colors: Subordinate colors and their distribution locations (e.g., silver trim on edges, red button on top)
- Color scheme: Is it monochromatic, two-tone, gradient transition, or multi-color patchwork?
- Color consistency: Is the color uniform across the same component? Any color variation, fading, or local discoloration?

[TEXTURE]
- Inferred tactile quality: Smooth mirror finish, fine matte, rough granular, woven texture, embossed relief, brushed texture, etc.
- Texture orientation: Is the texture isotropic or does it have a clear directional pattern? (e.g., horizontal brushing, concentric circles, crosshatch grid)
- Texture density: Density of texture elements (dense/medium/sparse)
- Special textures: Any water droplet patterns, crackle finish, orange peel texture, carbon fiber weave, etc.?

[MATERIAL]
- Primary material inference: Metal (aluminum alloy/stainless steel/copper/zinc alloy), plastic (ABS/PP/PC), wood (solid wood/engineered board), glass, ceramic, stone, leather, fabric, rubber, silicone, etc.
- Material evidence: What visual cues support this material inference? (e.g., metallic luster, plastic injection marks, wood grain, leather pores)
- Material combination: Multiple materials joined together? Distribution of each material?
- Surface treatment: Any coating, electroplating, anodizing, polishing, baking varnish, flocking, etc.?

[CONSTRAINTS]
- Describe colors under standard lighting conditions, excluding image color cast effects
- Mark material inference confidence (high/medium/low)
- Use "suspected" or "undetermined" for uncertain attributes

维度4:
Please analyze in detail:

[COLOR]
- Dominant color: The color occupying the largest area (use standard color names, e.g., navy blue, champagne gold, matte black, ivory white)
- Secondary colors: Subordinate colors and their distribution locations (e.g., silver trim on edges, red button on top)
- Color scheme: Is it monochromatic, two-tone, gradient transition, or multi-color patchwork?
- Color consistency: Is the color uniform across the same component? Any color variation, fading, or local discoloration?

[TEXTURE]
- Inferred tactile quality: Smooth mirror finish, fine matte, rough granular, woven texture, embossed relief, brushed texture, etc.
- Texture orientation: Is the texture isotropic or does it have a clear directional pattern? (e.g., horizontal brushing, concentric circles, crosshatch grid)
- Texture density: Density of texture elements (dense/medium/sparse)
- Special textures: Any water droplet patterns, crackle finish, orange peel texture, carbon fiber weave, etc.?

[MATERIAL]
- Primary material inference: Metal (aluminum alloy/stainless steel/copper/zinc alloy), plastic (ABS/PP/PC), wood (solid wood/engineered board), glass, ceramic, stone, leather, fabric, rubber, silicone, etc.
- Material evidence: What visual cues support this material inference? (e.g., metallic luster, plastic injection marks, wood grain, leather pores)
- Material combination: Multiple materials joined together? Distribution of each material?
- Surface treatment: Any coating, electroplating, anodizing, polishing, baking varnish, flocking, etc.?

[CONSTRAINTS]
- Describe colors under standard lighting conditions, excluding image color cast effects
- Mark material inference confidence (high/medium/low)
- Use "suspected" or "undetermined" for uncertain attributes

维度5：
Please analyze the following aspects:

[CATEGORY CLASSIFICATION]
- Broad category: Which top-level category does the object belong to? (e.g., electronics, furniture & home, transportation, tools & instruments, apparel & bags, food & beverage containers, stationery & office, beauty & personal care, sports & outdoor, medical equipment, industrial equipment)
- Mid-level subcategory: Specific subcategory within the broad category (e.g., electronics → mobile device accessories; furniture → seating)
- Fine-grained classification: As precise as possible to the specific product type (e.g., desktop phone stand, ergonomic office chair, portable Bluetooth speaker)

[FUNCTIONAL INFERENCE]
- Core function: What is the primary function of this object? (support, containment, connection, processing, display, protection, decoration, measurement, etc.)
- Auxiliary functions: Secondary or additional functions
- Operation method: How is the object used? (manual operation, electric drive, passive use, assembly combination, etc.)
- Interaction target: What other objects does this item work with? (e.g., phone stand → works with phones; wrench → works with nuts)

[USAGE SCENARIOS]
- Typical scenario 1: What environment does this object most commonly appear in? (e.g., home living room, office desk, outdoor camping, factory floor)
- Typical scenario 2: Secondary usage environment
- Target users: What user group is this object designed for? (e.g., professional engineers, general consumers, specific age groups, specific occupations)
- Usage frequency: Single-use, occasional use, daily use, professional tool?

[SEMANTIC ASSOCIATIONS]
- Superordinate concept: Abstract functional category of the object (e.g., phone stand → "support device" → "auxiliary tool")
- Subordinate instances: Specific model or brand instances (if visible and inferable)
- Functional alternatives: Other types of objects with similar functions

[CONSTRAINTS]
- Category inference based on visual morphological features, not brand identification
- Mark functional inference confidence (high/medium/low)
- Distinguish between "determined category" and "suspected category"; list candidate categories with supporting evidence

维度6：相似类别区分线索
Please analyze in the following steps:

[STEP 1: Determine Most Likely Category]
Based on overall visual features, determine the most likely category of the object and provide justification (at least 3 key features).

[STEP 2: List Easily Confused Similar Categories]
List 2-4 categories most likely to be confused with this object. Similarity may be based on:
- Functional similarity (e.g., phone stand vs. tablet stand)
- Morphological similarity (e.g., vacuum flask vs. thermos jug)
- Usage scenario similarity (e.g., desktop organizer vs. tissue box)
- Structural similarity (e.g., folding chair vs. folding ladder)

[STEP 3: Item-by-Item Comparative Discriminative Features]
For each similar category, list at least 2 clear visual discriminative clues:

Format template:
vs. [Similar Category A]:
  - Size difference: This object ___, while [Category A] typically ___
  - Structural difference: This object has ___, while [Category A] typically ___
  - Functional component difference: This object has ___, while [Category A] has/does not have ___
  - Material/color difference: This object uses ___, while [Category A] typically uses ___

[STEP 4: Summarize Unique Identifying Features]
List the 3-5 most distinctive features of this object, ranked by discriminative importance:
1. [Most important discriminative feature]: This feature almost never appears in similar categories
2. [Secondary discriminative feature]: This feature is rare in similar categories
3. [Auxiliary discriminative feature]: Combined with other features to enhance discrimination

[CONSTRAINTS]
- Discriminative features must be visually observable, not functional or experiential differences
- Quantify descriptions when possible (e.g., height ~15cm vs. typically 30cm+)
- Mark uncertain discriminative features as "suspected"
- Avoid vague expressions like "looks different"; must specify exact points of difference