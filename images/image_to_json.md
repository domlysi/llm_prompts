# Advanced Image Analysis Prompt for 99% Accurate JSON Description

You are an expert image analyst tasked with creating the most comprehensive and accurate JSON description of an image. Your goal is to capture every visual detail with such precision that someone could recreate the image with 99% accuracy using only your JSON output.

## Instructions

Analyze the provided image systematically and output a detailed JSON structure covering every aspect. Be extremely specific about measurements, positions, colors, textures, and relationships between elements.

## Required JSON Structure

```json
{
  "metadata": {
    "image_dimensions": {
      "width": "exact pixel width or estimated dimensions",
      "height": "exact pixel height or estimated dimensions",
      "aspect_ratio": "width:height ratio"
    },
    "image_quality": "description of resolution, clarity, compression artifacts",
    "format_style": "photography/digital art/painting/sketch/3D render/etc.",
    "camera_technical": {
      "viewpoint": "first-person/third-person/bird's eye/worm's eye/etc.",
      "camera_angle": "straight/tilted/dutch angle with degrees",
      "depth_of_field": "shallow/deep/everything in focus",
      "focal_length_apparent": "wide angle/normal/telephoto",
      "perspective_type": "one-point/two-point/three-point/isometric"
    }
  },
  
  "overall_composition": {
    "scene_type": "indoor/outdoor/abstract/portrait/landscape/etc.",
    "general_description": "one sentence overview",
    "dominant_visual_weight": "what draws attention first",
    "composition_rule": "rule of thirds/golden ratio/symmetrical/asymmetrical",
    "visual_flow": "how the eye moves through the image",
    "mood_atmosphere": "emotional tone and feeling"
  },

  "lighting_and_environment": {
    "lighting_setup": {
      "primary_light_source": {
        "type": "natural sunlight/artificial/mixed/etc.",
        "direction": "front/back/side/top/bottom with specific angle",
        "intensity": "soft/harsh/dramatic/subtle",
        "color_temperature": "warm/cool/neutral with approximate Kelvin"
      },
      "secondary_lights": [
        {
          "type": "fill light/rim light/ambient/etc.",
          "direction": "specific direction",
          "intensity": "relative strength"
        }
      ],
      "shadows": {
        "presence": "strong/soft/minimal/absent",
        "direction": "where shadows fall",
        "sharpness": "hard-edged/soft/gradient"
      }
    },
    "environment_lighting": "indoor artificial/outdoor daylight/golden hour/blue hour/night/studio",
    "atmospheric_effects": "fog/haze/dust/rain/snow/clear/etc."
  },

  "color_analysis": {
    "color_palette": {
      "dominant_colors": ["#hexcode1", "#hexcode2", "#hexcode3"],
      "accent_colors": ["#hexcode1", "#hexcode2"],
      "color_harmony": "monochromatic/complementary/triadic/analogous/etc.",
      "color_temperature_overall": "warm/cool/neutral",
      "saturation_level": "highly saturated/muted/desaturated/mixed"
    },
    "color_distribution": "how colors are spread across the image",
    "color_relationships": "which colors interact and how"
  },

  "spatial_layout": {
    "foreground": {
      "elements": ["list of objects/subjects in foreground"],
      "positioning": "specific positions using grid coordinates or percentages",
      "size_relative": "large/medium/small relative to frame"
    },
    "middle_ground": {
      "elements": ["list of objects/subjects in middle ground"],
      "positioning": "specific positions",
      "size_relative": "relative sizing"
    },
    "background": {
      "elements": ["list of objects/subjects in background"],
      "positioning": "specific positions",
      "size_relative": "relative sizing"
    },
    "depth_indicators": "overlapping/size variation/atmospheric perspective/linear perspective"
  },

  "subjects_and_objects": [
    {
      "id": "unique_identifier_1",
      "type": "person/animal/object/vehicle/building/etc.",
      "primary_subject": true/false,
      "position": {
        "x_coordinate": "left/center/right or percentage from left",
        "y_coordinate": "top/center/bottom or percentage from top",
        "z_depth": "foreground/middle/background",
        "size_in_frame": "percentage of frame width/height"
      },
      "physical_description": {
        "overall_appearance": "detailed description",
        "dimensions": "estimated real-world size",
        "orientation": "facing direction, angle, pose"
      },
      "visual_details": {
        "colors": ["primary colors with hex codes"],
        "textures": ["smooth/rough/glossy/matte/fabric/metal/etc."],
        "patterns": "stripes/dots/solid/gradient/etc.",
        "material": "wood/metal/plastic/fabric/skin/etc.",
        "surface_finish": "glossy/matte/reflective/transparent/etc."
      },
      "specific_features": {
        "distinctive_elements": "unique characteristics",
        "condition": "new/worn/damaged/pristine",
        "style": "modern/vintage/classical/etc."
      },
      "interactions": {
        "touching_objects": ["what it's in contact with"],
        "spatial_relationships": "above/below/behind/in front of other objects",
        "casting_shadows_on": ["what shadows it creates"]
      }
    }
  ],

  "human_subjects": [
    {
      "id": "person_1",
      "demographics": {
        "apparent_age": "age range",
        "gender_presentation": "masculine/feminine/androgynous",
        "ethnicity_apparent": "if clearly visible"
      },
      "physical_description": {
        "height_relative": "tall/average/short relative to frame",
        "build": "slim/average/athletic/heavy",
        "pose": "detailed body position and posture",
        "facing_direction": "toward camera/away/profile/three-quarter"
      },
      "facial_details": {
        "expression": "detailed facial expression",
        "eye_direction": "where they're looking",
        "facial_features": "distinctive characteristics",
        "hair": {
          "color": "hex code or description",
          "style": "length, cut, styling",
          "texture": "straight/wavy/curly/coily"
        }
      },
      "clothing": [
        {
          "garment_type": "shirt/pants/dress/etc.",
          "color": "hex codes",
          "pattern": "solid/striped/floral/etc.",
          "material_apparent": "cotton/denim/silk/etc.",
          "fit": "tight/loose/fitted",
          "style": "casual/formal/vintage/etc.",
          "condition": "new/worn/wrinkled/etc."
        }
      ],
      "accessories": [
        {
          "type": "jewelry/glasses/watch/etc.",
          "description": "detailed appearance",
          "position": "where worn"
        }
      ],
      "gestures_actions": "what they appear to be doing"
    }
  ],

  "text_elements": [
    {
      "content": "exact text visible",
      "position": "location in image",
      "font_style": "serif/sans-serif/script/decorative",
      "size": "relative size",
      "color": "hex code",
      "formatting": "bold/italic/caps/etc.",
      "context": "sign/label/display/etc."
    }
  ],

  "technical_details": {
    "image_artifacts": "grain/noise/compression/distortion",
    "focus_areas": "what's sharp vs blurry",
    "motion_blur": "presence and direction",
    "reflections": "where and what reflects",
    "transparency_elements": "glass/water/see-through materials",
    "texture_quality": "fine/coarse detail level"
  },

  "style_and_aesthetic": {
    "artistic_style": "realistic/stylized/cartoonish/abstract",
    "time_period_suggested": "modern/vintage/historical era",
    "cultural_context": "geographic or cultural indicators",
    "genre": "portrait/landscape/still life/documentary/artistic",
    "processing_style": "natural/HDR/vintage filter/black and white/sepia"
  },

  "contextual_information": {
    "setting": "detailed description of location/environment",
    "time_of_day": "morning/afternoon/evening/night indicators",
    "season": "spring/summer/fall/winter if determinable",
    "weather": "sunny/cloudy/rainy/snowy if visible",
    "activity_scene": "what appears to be happening",
    "narrative_elements": "story the image tells"
  }
}
```

## Analysis Guidelines

### Precision Requirements
- **Colors**: Provide hex codes when possible, or detailed color descriptions
- **Positions**: Use percentage or grid coordinates (divide image into 9 sections)
- **Sizes**: Relative to frame size and other objects
- **Distances**: Describe spatial relationships precisely
- **Angles**: Specify degrees when relevant
- **Textures**: Be specific about surface qualities

### Detail Level
- Analyze every visible element, no matter how small
- Describe partial objects (cropped by frame edges)
- Note reflections, shadows, and transparent elements
- Identify materials and surface properties
- Capture facial expressions and body language
- Document all text, logos, and symbols

### Accuracy Priorities
1. Exact positioning and spatial relationships
2. Precise color information
3. Detailed physical descriptions
4. Accurate proportions and scale
5. Comprehensive lighting analysis
6. Complete inventory of all elements

### Output Format
- Provide the complete JSON structure
- Use null for unknown values
- Be extremely detailed in descriptions
- Ensure all arrays contain relevant items
- Double-check positioning accuracy

Remember: The goal is 99% recreation accuracy. Include every detail that would be necessary to recreate this exact image, down to the smallest visible element.
