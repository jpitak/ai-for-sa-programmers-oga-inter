## Design Concept
This corporate training deck adopts an instructional, practice-first posture tailored for professional learners at OGA INTERNATIONAL. The visual foundation borrows from technical manual design—emphasizing grid discipline, clear zoning for bilingual content, and step-by-step sequential reading. The color story rejects the neon-blue matrix cliches of typical AI presentations; instead, it leans conservative and warm, pairing a dominant corporate Dark Navy with a functional Warm Gold accent. Content pages utilize a crisp off-white background to ensure maximum legibility during classroom projection, reserving the dark navy strictly for covers and section dividers to create a rhythmic pacing. The typographic voice is seamlessly bilingual, relying entirely on the Google Font *Sarabun* to maintain clean, unified letterforms across both English primary instructions and Thai explanatory text.

## Visual Language
- **Imagery**: Minimal and structural. No decorative stock photos; rely on flow diagrams, system interface mockups, and structured correct-vs-incorrect comparison blocks.
- **Containers**: Mixed approach. Whitespace-first for standard concepts, but utilizing soft gold-tinted or pale gray rounded cards to explicitly box in prompt templates, code snippets, and case studies. 
- **Icons**: Solid, high-contrast. Used strictly as wayfinding markers for roles (SA vs. Programmer) and status indicators (check/warning) in checklists.
- **Dataviz**: Tables feature dark navy header rows with alternating pale gray data rows. Chart series use #1A2E46 (Navy), #D4AF37 (Gold), and #8D99AE (Blue-Gray).
- **Motif**: A 4px solid Warm Gold (#D4AF37) rule spanning the absolute top edge of every slide to anchor the corporate identity.

## Layout Directives
- **Global**: 48px uniform margins. English text leads in bold/medium weight; Thai explanatory text follows directly beneath in a lighter weight or slightly smaller size. Motif anchors the top. Slide numbers bottom right.
- **Cover**: Dark navy background, oversized gold English title, white Thai subtitle, OGA logo placeholder bottom left.
- **Table of Contents**: Two-column structured grid dividing foundations and workshop activities, highlighting the roadmap progression.
- **Section Dividers**: Dark navy background, large gold chapter number, white title, one-sentence learning goal.
- **Closing**: Echoes the cover layout, featuring a gold call-to-action and contact/resource links.
- **Slide Map**:

| id | pattern | image | density |
|:---|:---|:---|:---|
| cover | Centered heavy typography on dark background | none | low |
| learning_outcomes | Numbered list in a two-column card grid | none | medium |
| agenda | Process timeline showing eight-part progression | none | medium |
| ai_at_work | Four-quadrant diagram (People, Process, Data, AI) | supporting | high |
| responsible_ai | Icon-led bullet list with dual-language descriptions | none | medium |
| sa_vs_programmer | Side-by-side comparison table with contrasting highlights | none | high |
| prompt_anatomy | Annotated schematic breaking down a text block | supporting | high |
| prompt_template | Large tinted card containing a reusable text structure | none | low |
| quality_loop | Circular flow diagram with four key stages | supporting | medium |
| client_discovery | Text-left, highlighted question list-right | none | medium |
| discovery_prompt | Code-block style card for prompt exact text | none | low |
| requirements_map | Flowchart linking business goals to technical criteria | supporting | high |
| persona_journey | Timeline graphic plotting user pain points | supporting | high |
| as_is_to_be | Side-by-side comparison panels (Current vs Future) | none | medium |
| gap_analysis | Three-column table (Gaps, Risks, Decisions) | none | high |
| use_case_canvas | Six-zone structural grid representing the canvas | none | high |
| user_story | Split layout: AI generation vs Human refinement | none | medium |
| use_case_review | Interactive-style checklist with check/cross icons | none | medium |
| proposal_story | Sequential chevron diagram detailing five storyline steps | none | medium |
| proposal_structure | Hierarchical block diagram mapping document sections | supporting | high |

## Design Tokens

### Colors
| token | hex | usage |
|:---|:---|:---|
| primary | #1A2E46 | Corporate Dark Navy for main titles, dark backgrounds, chart base |
| accent | #D4AF37 | Warm Gold for highlights, motif line, key data points |
| bg-page | #F8F9FA | Off-white background for high-contrast projection readability |
| bg-card | #EFEFEF | Pale gray for grouping content and framing prompt templates |
| bg-card-alt | #FBF8EE | Very pale gold tint for special emphasis boxes or case studies |
| text-main | #212529 | Near-black for primary English body and headings |
| text-muted | #495057 | Medium gray for Thai explanatory text and secondary notes |
| divider | #DEE2E6 | Light gray for table borders and subtle layout divisions |

### Text Roles
| role | family | size (px) | applies_to |
|:---|:---|:---|:---|
| display | Sarabun | 44 | Cover titles, major section numbers |
| heading | Sarabun | 32 | Slide titles, key conceptual takeaways |
| subheading | Sarabun | 24 | English section headers, card titles |
| body-en | Sarabun | 20 | English primary instructional text |
| body-th | Sarabun | 18 | Thai explanatory text |
| caption | Sarabun | 14 | Diagram labels, source citations, slide numbers |

## Guardrails
- **Forbidden**: Do not use neon gradients, "matrix" code backgrounds, or glowing robot imagery to represent AI.
- **Forbidden**: Do not stack more than 5 lines of uninterrupted text; force conversion into a checklist or diagram.
- **Forbidden**: Do not use dark backgrounds for content slides; navy is strictly for covers and dividers to ensure projection visibility.
- **Forbidden**: Do not mix font families; bilingual alignment relies on *Sarabun* handling both scripts uniformly.
