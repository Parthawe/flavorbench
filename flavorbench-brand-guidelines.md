# FlavorBench brand guidelines

Version 2 · October 2026

## Purpose

FlavorBench helps people understand how AI models are made. Cooking supplies the vocabulary: research becomes an egg, data becomes grains, infrastructure becomes a stove, compute becomes heat, post-training becomes seasoning, evaluation becomes tasting, and a model becomes a finished dish. Each explanation leads to a source. The food kitchen provides actual curated recipe adaptations alongside that teaching metaphor.

## Direction

Use the clarity and appetite of a food browsing service. Uber Eats is the reference for bold, direct typography, prominent food imagery, compact navigation and a visible next action. FlavorBench applies those ideas to choosing a model and reading its recipe. It retains its own name, bowl mark, colors, open-source typeface and original illustrations.

The reference was inspected at https://www.ubereats.com/ in October 2026. It uses a strong black wordmark, bold sans-serif headings, prominent food photography and contrasting controls. These observations are a design reference, not an affiliation or permission to reuse its assets.

## Identity

Write the name as FlavorBench. The wordmark combines black “Flavor” with green “Bench”; use the same weight and baseline. The existing bowl mark sits to its left. Preserve a clear space of at least the mark’s height around standalone lockups. The minimum wordmark width is 140px on screen. Use a one-color white lockup on black. Do not stretch, tilt, outline or add a shadow to the logo.

Use the line “Every AI has a recipe.” when a short introduction is needed. It describes a teaching metaphor; follow it with enough context to make that clear. Do not repeat the line on every task page.

## Color

| Token | Value | Use |
| --- | --- | --- |
| Ink | #18281F | Text, navigation, primary buttons, book cover |
| Canvas | #F7F6F0 | Page surface |
| Paper | #FFFDF7 | Recipe pages, fields and food cards |
| Kitchen green | #126443 | Wordmark accent, selected controls and source links |
| Fresh tint | #E6EEE1 | Selected surfaces and short explanatory notes |
| Neutral | #ECEEE5 | Supporting panels and inactive controls |
| Divider | #D9DED5 | Rules and field borders |
| Secondary ink | #566158 | Metadata and supporting text |
| Amber | #F0C875 | Evidence and question highlights |

Ink and paper do most of the work. Green marks selection and navigation; it is never a model score. Amber supports evidence and questions. Red belongs to tomatoes and other food, not to poor ratings. Never construct a red-to-green performance scale.

## Typography

Use the locally hosted Manrope variable font for the whole interface. It is a licensed geometric sans-serif that gives headings and controls one voice. Do not use Uber Move or claim Manrope is an Uber typeface.

| Role | Desktop | Phone | Weight |
| --- | --- | --- | --- |
| Page heading | 48–64px | 36–44px | 800 |
| Section heading | 28px | 24px | 750 |
| Dish / book title | 28–34px | 28px | 750 |
| Main copy | 16px | 16px | 400–500 |
| Controls | 14px | 14px | 600–750 |
| Secondary metadata | 12–13px | 12–13px | 500 |

Use sentence case. Keep line height at least 1.6 for explanations and methods. Use tabular numerals for amounts and servings. Avoid script fonts, letter-spaced capitals and very light headings.

## Food and 3D imagery

Show one identifiable dish per menu card, with a consistent angle and generous crop. Food should look appetizing, with visible texture, natural lighting and simple tableware. The menu images are original AI-generated illustrations. Label this where images appear. They are not photographs of a tested recipe or outputs from the paired model.

The interactive Three.js kitchen remains the main explanatory object. Give it room, a neutral warm surface and enough contrast to recognize the egg, jar, stove, heat, spices, spoon and dish. Use click or drag feedback to explain a selection. Always provide equivalent labeled buttons and written content. Object size does not encode cost, data volume or performance.

## Layout and components

Use a centered content width up to 1256px with 32px desktop and 20px phone gutters. Manrope, dish illustrations and clear actions take cues from food browsing; FlavorBench’s purpose is AI education.

Home explains the premise with a kitchen still life and two exploration links. Kitchen uses one model selector, a large interactive tabletop, seven labeled object controls and one explanation panel. Model previews link to notebook-style reading pages. Sources uses compact bibliographic rows; source explainers have a clear reading column and related concepts. Cookbook uses static saved previews, avoiding repeated WebGL scenes.

Primary navigation is Kitchen, Recipe book, Sources, Cookbook and About. The logo opens Home. Food recipes, brand guidelines, data practices and the handbook are footer links. All destinations use real URLs and browser history.

Actions are at least 44px tall. Green marks selection and source links. Amber supports evidence and questions, without implying a rating. Fields have visible labels and focus. Use 8px action corners and 10–12px frames; leave browsing rows unboxed where possible.

The model dossier uses warm paper with a quiet notebook outline. Keep the existing bound notebook treatment for food instructions. Longer material belongs on reading pages; browsing previews stay concise.

On phones, Menu opens the primary links. Kitchen stacks scene, written objects and explanation. Model previews remain compact, and pages never scroll horizontally. Pantry settings start collapsed. Essential controls are at least 44px. Respect reduced motion and retain written alternatives for every 3D selection.

## Voice and trust

Use concrete verbs: choose, explore, read, cook, save. Explain what went in, what happened and what came out. Name the model release, distinguish a source statement from a metaphor, and show missing information as unknown.

Curated dishes are editorial pairings. Do not imply a cuisine measures a model’s abilities or establishes cultural ownership. Keep adaptation notes and links to food authors. Never invent endorsements, benchmark scores, environmental metrics or a live AI connection.

Cookbook storage is local to this browser. Live generation is conditional on a configured connection and must disclose its request. Keep loading, empty, error and WebGL fallback states useful. Respect reduced motion and visible keyboard focus.

## Applications

- Home: brief premise, visual demonstration and three featured evidence stories.
- Kitchen: open model/object exploration with one sourced explanation.
- Recipe book: compact model previews and dedicated release dossiers.
- Sources: searchable concepts, research, documentation and news; detailed evidence pages.
- Cookbook: separately saved model recipes, reading and food with open/remove controls.
- About: explanation method, editorial standards and limits.
- Food: secondary pantry, dish and written cooking notebook.
