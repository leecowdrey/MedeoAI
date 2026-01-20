# Generative AI with Medeo AI


## Generative AI - content creation for websites

It's interesting to see how much progress is being made and how quickly such content can be created but oh gosh a 71 second video with embedded slides and narration audio needed 80+ lines of input to 'present' 5 slides...

### Prompts

```
generate a presentation video:

1. Character Reference Image (Avatar)
Prompt: "Professional digital avatar character, business casual attire (navy blazer, light shirt), friendly and approachable appearance, neutral expression with slight smile, medium shot from chest up, facing forward, 3D rendered character (not real human), clean white background, natural proportions, professional lighting"

Style: "professional 3D digital rendering, high quality, clean and polished, photorealistic CGI style, studio lighting"

Model: Gemini-3-pro-image

2. Environment Reference Image (Conference Room)
Prompt: "Modern office conference room interior, professional setup with large digital presentation screen positioned on right side of frame taking up significant space, empty space on left side for presenter, subtle depth of field, soft professional office lighting, neutral color palette, camera angle showing both presentation area and presenter space clearly separated, empty room without people"

Style: "professional corporate photography, high quality, photorealistic, clean interior design, balanced composition with clear presentation screen area"

Model: Gemini-3-pro-image

3. Logo Reference Image
Prompt: "COWDREY company logo on white background, clean white text 'COWDREY' in modern sans-serif font with tagline 'Consulting - UK' underneath in smaller text, minimalist corporate branding design, professional and clean, isolated logo on pure white background"

Style: "corporate logo design, clean and professional, high contrast, vector-style clarity"

Model: Gemini-3-pro-image

4. Five Presentation Slides (Using Images-to-Image with 3 References)
Reference Media IDs for all slides:

Image 1: Character reference (avatar)
Image 2: Environment reference (conference room)
Image 3: Logo reference (COWDREY logo)
General Prompt Template: "Character from image_1 positioned on left side of frame in environment from image_2, [EXPRESSION AND GESTURE]. Large digital presentation screen on right side of frame is fully visible and unobstructed, displaying: exact logo from image_3 in top right corner [POSITION NOTE], large clear heading '[HEADING]' and fully readable content text: '[CONTENT TEXT]' Avatar does not block screen, all text clearly visible, same professional composition"

Style (all slides): "professional 3D digital rendering, high quality, photorealistic CGI style, corporate presentation aesthetic, balanced composition with clear unobstructed screen visibility"

Model: Gemini-3-pro-image

Slide 1 - Expertise
Expression: "welcoming expression with subtle open hand gesture presenting to camera" Heading: "Expertise" Content: "Telecommunication providers, XaaS service providers, enterprise businesses and governments, since 2001 we have been involved in software and solution sales across the globe."

Slide 2 - Technology
Expression: "engaged expression with presenting hand gesture" Position Note: "(same position)" Heading: "Technology" Content: "From representing market giants, technology innovators through to delivery with and to global integrators or direct to businesses, we strive to ensure the solution is a fit."

Slide 3 - Lifecycle
Expression: "thoughtful expression with subtle counting/listing hand gesture" Position Note: "(same position)" Heading: "Lifecycle" Content: "System engineering through pre & post sales, we have been involved from the simple to the complex across the broad range of product and solution sales."

Slide 4 - The I-in-Team
Expression: "confident expression with collaborative hand gesture (hands coming together)" Position Note: "(same position)" Heading: "The I-in-Team" Content: "Operating independently, as part of or leading a local or global distributed team, we ensure realistic technical planning is the key to success. Whether traditional Waterfall, DevOps with CI/CD, Agile or other methodologies, we work the way your business needs."

Slide 5 - Thank You
Expression: "warm grateful expression with both hands in thank you gesture" Position Note: "(same position)" Heading: "Thank You" Content: "For more information please visit https://www.cowdrey.net/"

5. Voice Generation (British Accent)
Voice: British Nick Edu (voice_01KBNAF3Z6TPB1DVPT53KV3SW7)

Professional, clear, confident, engaging British male voice
Scripts:

Slide 1 Audio (12.4s): "Expertise with Telecommunication providers, anything as a service providers, enterprise businesses and governments, since 2001 we have been involved in software and solution sales across the globe."

Slide 2 Audio (10.0s): "Broad range of Technology from market giants, technology innovators through to delivery with and to global integrators or direct to businesses, to ensure the solution is a fit."

Slide 3 Audio (8.3s): "lifecycle system engineering through pre and post sales, involved from the simple to the complex across the broad range of product and solution sales."

Slide 4 Audio (21.3s): "Operating independently, as part of, or leading a local or global distributed team, ensuring that realistic technical planning is the key to success. Whether traditional Waterfall or agile, DevOps, with Continuous Integration and Delivery, or mixed with other methodologies to form hybrid model, work is completed the way your business needs."

Slide 5 Audio (5.0s): "Thank you for your time, please visit the cowdrey.net web site for further information"

6. Timeline Structure
Total Duration: ~71 seconds

Timing:

Slide 1: 0-14.4s (audio 0-12.4s + 2s pause)
Slide 2: 14.4-27.6s (audio 14.4-24.4s + 3.2s pause)
Slide 3: 27.6-40.1s (audio 27.6-35.9s + 4.2s pause)
Slide 4: 40.1-63.4s (audio 40.1-61.4s + 2s pause)
Slide 5: 63.4-71.0s (audio 63.4-68.4s + 2.6s pause)
Key Production Notes:

Each slide starts immediately with its audio (no pause before)
2-second pause at the end of each slide
Avatar positioned on left, presentation screen on right
Consistent environment, lighting, and logo placement across all slides
British accent voiceover throughout
Workflow Summary
Generate 3 reference images (character, environment, logo)
Use Images-to-Image with all 3 references simultaneously for each slide
Generate all 5 voiceovers with British accent
Assemble timeline with slides starting with audio + 2s end pauses
Final video: 71 seconds, 16:9 aspect ratio, silent video with subtitles
```


## Resulting Content

[Content](content.mp4)

<video src="https://github.com/leecowdrey/MedeoAI/raw/refs/heads/main/content.mp4" controls preload></video>


## Gratitude

Thanks for [Medeo AI](https://www.linkedin.com/in/leecowdrey/#) (https://medeo.app) for the free time

## Disclaimer

> The quality of the created content is purely down to myself and the 30 minutes spent learning and using Medeo AI