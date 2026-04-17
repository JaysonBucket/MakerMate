# Maker Mate – Copilot Create Preparation Agent

Microsoft 365 Copilot Create enables users to generate videos, visuals, and stories from natural language prompts or uploaded material. However, generation results depend heavily on prompt structure, deployment context, and narrative clarity—factors that are not explicitly surfaced during the Create interaction.

Maker Mate is a declarative Microsoft 365 Copilot agent that guides users through the media preparation process prior to generation. It extracts storytelling context from uploaded material (e.g. PowerPoint, PDF, or strategic customer briefings) and translates it into a structured storyboard and production‑note document optimized for Copilot Create.

This mitigates the single‑document upload constraint in Create and enables asset‑grounded scene progression while separating viewer‑facing messaging from internal production logic such as loop behaviour or sound‑off playback.  

--> sample outcome: https://youtu.be/dloW_o5IaAY (took about 12 minutes from idea to finish)


<img width="430" height="310" alt="image" src="https://github.com/user-attachments/assets/da364076-07fc-43f6-a788-061d3c3144ac" />



## Value

Copilot Create typically relies on a single prompt or uploaded file to generate complete visual outputs. As a result:

- prompt ambiguity may lead to inconsistent scene sequencing  
- uploaded content may be interpreted as direct visual input  
- internal framing notes may be narratively exposed  
- unattended playback scenarios (e.g. expo displays) may not support audio  
- CTA elements such as QR codes may be animated unintentionally  
- videos may include hard endings and fail to loop  

Maker Mate addresses these limitations by preparing a Create‑ready narrative structure before generation. Users are guided through goal, audience, playback model, and asset mapping—ensuring that uploaded material informs the storyline rather than being reused as visual media.

Storyboard and production notes are consolidated into a single document that can be uploaded into Create, supporting scene‑based messaging and consistent playback behaviour without requiring manual reconstruction in Clipchamp.

## How It Works

1. Users upload contextual material such as presentations or strategic descriptions  
2. Maker Mate extracts narrative fragments (goals, actors, challenges, value propositions)  
3. Based on audience and deployment scenario, narrative directions are proposed  
4. Upon approval, a structured scene‑based storyboard is generated  
5. Viewer‑facing messaging is separated from production logic  
6. Storyboard and production guidance are consolidated into a single document  
7. The document can be uploaded into Copilot Create for generation  
8. Optional post‑generation edit paths are suggested  

This allows Copilot Create to generate visually coherent outputs based on structured storytelling rather than raw prompts.

## Features

### Guided Create Preparation

Maker Mate walks users through a structured preparation workflow prior to generation in Microsoft 365 Copilot Create.  
Instead of relying on a single prompt, users are guided through:

- communication goal  
- target audience  
- deployment context  
- playback environment  
- tone and CTA behaviour  

This ensures that generation parameters typically hidden in Create are explicitly defined before production begins.

### Upload-Grounded Storytelling

Uploaded materials such as:

- presentations  
- capability decks  
- customer situation descriptions  
- requirement summaries  
- persona definitions  

are treated as contextual grounding rather than direct visual input.

Maker Mate extracts narrative fragments (e.g. goals, actors, challenges, value propositions) and aligns them with the intended communication objective—enabling coherent storyline development without requiring manual scripting.

### Scene-Based Storyboard Generation

Instead of relying on Create to infer scene structure, Maker Mate generates an explicit storyboard layer that includes:

- message progression by scene  
- on-screen text messaging  
- optional viewer-facing narration  
- visual guidance per scene  
- CTA placement  
- loop bridge construction  

This storyboard acts as the viewer-facing narrative foundation for generation.

### Production Logic Separation

Viewer-facing messaging is explicitly separated from:

- viewing model assumptions  
- loop behaviour  
- playback environment  
- sound-off requirements  
- policy constraints  
- scan-safe QR hold rules  

This prevents internal production notes from being narrated in voiceover during Create generation.

### Single-Document Consolidation

Microsoft Copilot Create allows only a single document upload for reference.

Maker Mate consolidates:

- storyboard  
- production guidance  
- asset mapping  

into one uploadable document optimized for **Method A** (Create from description).

This mitigates structural ambiguity during generation and supports consistent scene sequencing without post-generation manual reconstruction.

### Loop-Safe Video Preparation

Prepared videos support unattended playback environments such as:

- digital signage  
- expo displays  
- event screens  
- autoplay intranet pages  

Maker Mate ensures:

- seamless loop behaviour  
- entry-anytime comprehension  
- sound-off message visibility  
- no hard narrative ending  

### Asset-to-Scene Mapping

Uploaded reference materials may be:

- integrated  
- used for inspiration  
- partially adapted  
- excluded by policy  

Maker Mate assigns structured references (A#) and maps them to scenes, enabling Create to align generated visuals with user-provided context.

### Post-Generation Edit Routing

After generation, Maker Mate classifies requested changes as:

- **Minor** – suitable for "Edit with AI"  
- **Major** – requiring re-prompting or Clipchamp editing  

This reduces iteration effort and clarifies next steps for refinement.

---
