# NIMBO

*A silent animated short film, 7:00 plus a short credits coda. Written for AI generation with Seedance: 82 shots, each one generation.*

---

## HOW THIS SCRIPT IS BUILT FOR SEEDANCE

Every shot is one self-contained generation with one subject action, one camera move and one place. Each prompt is written in the order Seedance responds to best: subject, action, setting, camera, mood. Append the **Style line**, the scene's **Grade line** and the **Avoid line** below to every prompt.

**Rules applied to the whole film**

- **Clip length:** Every shot runs 3 to 10 seconds. Per-generation caps vary by platform and version (roughly 12 to 15 seconds on Seedance 2.0, longer on 2.5), so nothing here depends on a long take. Shots under 4 seconds are generated at 4 seconds and trimmed in the edit.
- **One camera move per shot,** using only moves the model handles well: fixed (locked off), slow push-in, pull-out, pan, tracking, orbit, aerial and handheld. Smash zooms, whip pans, compound crane moves and in-shot transitions were removed. Cuts, dissolves, fades, speed changes, the title and the credits are all done in the edit.
- **Two actions never share a shot.** Where a sequence needs more than one beat, it is split into separate shots.
- **One expression change per shot.** Expressions are big and simple: eyes wide, lip wobble, cheeks sinking, a small smile blooming.
- **No text anywhere.** The shop signs and the painted circles contain no writing. The title and the credits are added in post.
- **No fingers.** Every character has soft mitten-like stubby arms. There are no extreme close-ups on hands.
- **Small casts per frame.** No more than three or four characters share a frame, except in the sky world and in street crowds, where distant clouds are small background figures. Storm crowds are shown as dark silhouettes in rain, seen from behind or from above.
- **Simple mechanics.** The electronic legs are chunky with two or three visible parts: a glowing battery cell at the knee, a copper coil at the thigh and a looping cable. Close-ups show one part at a time.
- **Gentle electricity.** Sparks and zaps are small, soft blue-white arcs. They are never fast lightning bolts, because fast complex motion can warp.
- **Moderate speed in the storm.** Handheld shots use moderate shake and strong silhouettes.
- **No age words in prompts.** The characters are written as "small cloud characters" with reference images carrying their look, since prompts with words like child, kid, boy or girl can be flagged. Families and young are shown by relative size and clusters, never by those words.
- **Sound is built in post.** Music and effects are added in the edit so the motifs stay consistent across the film. The notes under each scene and shot are the sound plan.

**Workflow**

1. Build the reference sheets below with an image model.
2. Attach only the references each shot lists (two to four per shot).
3. Where a shot continues the previous one, use the previous shot's last frame as the first frame.
4. Generate two to three takes per shot and keep the best.
5. Assemble, add transitions, fades, sound, the title and the credits in the edit.

**Reference images**

| Tag | Reference sheet |
| --- | --- |
| @Image1 | Nimbo with legs: small round fluffy grey-white cloud, big glossy dark eyes, rosy cheeks, tiny stubby mitten arms pressed close to his body, oversized thin electronic legs with a glowing amber battery cell at each knee, a copper coil at the thigh and a looping cable, strapped on with worn leather buckles, stands very upright |
| @Image2 | Nimbo without legs: same body, slightly lighter and fluffier |
| @Image3 | Luma: pearl-white cloud, faint lilac shimmer, wispy cowlick with tiny blue-white sparks glittering along it, no legs, soft tail of mist, palms that crackle with tiny blue-white sparks, always smiling |
| @Image4 | The Vendor: slightly larger stern grey cloud, brass goggle over one eye, dented copper electronic legs |
| @Image5 | The legless cloud: small cream cloud, dead stumps trailing frayed cables, empty tin cup |
| @Image6 | The Low Streets: dark wet stone, chains on every wall, roped lampposts with bare glowing filament bulbs, ankle-high mist, a painted white holding circle on the ground beside each chain (no writing) |
| @Image7 | The causeway: long iron bridge over a void at sunset |
| @Image8 | The rooftop at dusk with an iron awning |
| @Image9 | The sky world: glowing cloud islands, rivers of mist, vapor whales, clusters of cloud life drifting in every size |
| @Image10 | The memorial: a pair of empty electronic legs with dark knee cells, cables and leather straps hanging open, a tiny knitted coral and mustard striped scarf draped over one knee, set before a plain blank stone slab with no writing |
| @Image11 | The scarf cloud: small peach-cream cloud on electronic legs, wearing a tiny knitted coral and mustard striped scarf |

**Style line:** Stylized 3D animated short film look, soft rounded shapes, matte felt-like cloud texture, painterly storybook lighting, gentle film grain, 16:9.

**Avoid line:** No text, no letters, no logos, no subtitles, no extra characters, no jitter, no morphing, no bent or extra limbs, no cuts or scene changes inside the clip.

---

## CHARACTER CONTRAST

The contrast is never explained. It lives in posture, movement, expression and what each character does when the same thing happens.

|  | NIMBO | LUMA |
| --- | --- | --- |
| **Nature** | Cute, uptight, scared, an introvert who follows the rules | Cute, carefree, clumsy, always smiling, and warm toward Nimbo |
| **Want** | To get through the day charged, in order and unnoticed | Whatever is shiny, or next |
| **Posture** | Very upright, arms pressed to his sides, small precise steps | Loose and wobbly, arms flung wide, drifts in curves, often upside down |
| **Movement** | Staccato and mechanical: buzz, click, whir | Flowing and a little late, bumping into things |
| **Face** | Wide worried eyes, tight lips, blushes easily, laughs only when he cracks | Soft smile or wide grin, sparkling eyes, head tilts, cowlick bobbing |
| **With others** | Stays at the edge, avoids eye contact, flinches | Waves at everyone and everything, including a lamppost. The town pities her because she has no legs |
| **With each other** | Watches her constantly, ties ropes, panics for her | Amused by his panics, but she notices every tear and answers it with comfort. Carefree about the world, never careless about him |
| **The rules** | Steps only on the painted circles, watches his knee light, grips a chain at the siren | Chains are toys, the siren is a game, charge is something shiny. She never lectures |
| **The sky** | Cannot look at it. He does not know what a cloud is. To him, floating means being swept away and dying | She seems naive about it: the wind that terrifies the town fills her with wonder. In the sky we learn she always knew |
| **Sound** | Leg buzzes, clicks and whirs | Music box theme, soft bounces, tiny crackles of static, silent giggles |

**The comedy pattern:** Nimbo follows a rule. Luma breaks it without a care. Nimbo panics. Nothing bad happens. Over time Nimbo loosens. This repeats at the lamppost, the siren surfing, the careless battery shelf, the twirl and the circles in the street. In the sky the pattern completes: Nimbo breaks every rule, bumps into a cloud, bows to it and keeps going.

**The arcs:** Nimbo moves from rigid to loose, and finally to free. Luma does not change. She smiles through the rope, the storm, the dead legs and the slipping grip, even while being saved, and her smile never falls. She is carefree about the world and never careless about Nimbo: whenever he is truly distressed she sees it and comforts him. She frowns exactly once, playfully, in Shot 78, when Nimbo zaps her back.

**Luma's secret:** Luma is from the sky and has always known it is safe. Until Shot 73 she reads as a naive, carefree cloud with no concept of dying, and the film gives no hints otherwise. Everything she does before then reads two ways, naive on first viewing and knowing on the second.

**Writing rule for Seedance:** Personality is always written as visible action (a grin, a wave, a bounce, a rigid stance, a tight lip), never as an adjective alone.

---

## STRUCTURE BLUEPRINT

**Logline:** In a town where every cloud is bolted to the ground because the sky means death, a small cloud who has never imagined floating unbuckles the heavy legs that keep him safe to save the one he loves, and finds a living world above that was never a threat.

**Dramatic question:** Will Nimbo give up his legs and face the sky to save Luma?

**Theme:** What keeps you safe can keep you from living.

**Irony:** He gives up everything to save someone who never needed saving, and the sacrifice sets him free. The legs he wears to avoid being swept away nearly cost him Luma. Being swept away is what sets him free. The town mourns the clouds the sky took, and they were never gone.

**The town's blindness:** Nobody in the Low Streets knows what a cloud is. The legs are older than anyone can remember, and floating is understood only as being swept away and dying. Nimbo is not hiding a dream. He has never suspected one. The town never learns the truth. Only the audience does, in the coda.

| Beat | Time | Shot |
| --- | --- | --- |
| Opening image: a blank sky nobody looks at | 0:00 | Shot 1 |
| World rules: a cloud is swept away | 0:13 | Shots 4 to 6 |
| Inciting incident: his legs die, out of charge | 1:04 | Shot 19 |
| Plot Point 1: he takes Luma's hand | 1:36 | Shot 27 |
| Midpoint: he discovers lightness, then the storm appears | 3:14 | Shots 41 to 42 |
| All is lost: Luma is slipping away | 4:59 | Shot 59 |
| Plot Point 2: he chooses to unbuckle, believing it is goodbye | 5:08 | Shot 60 |
| Climax: he lets go, saves Luma, is swept away | 5:14 | Shots 61 to 65 |
| Discovery: the sky revealed | 5:48 | Shots 66 to 72 |
| Luma's reveal: she appears, and she always knew | 6:27 | Shots 73 to 75 |
| The zaps and the chase into the horizon | 6:39 | Shots 76 to 81 |
| Coda: the grave, over the credits | after 7:00 | Shot 82 |

**Proportions:** Act 1 1:48 (26%), Act 2 3:20 (48%), Act 3 1:52 (27%).

**Plants and payoffs**

| Plant | Payoff |
| --- | --- |
| The blank sky nobody looks at (Shot 1) | The sky revealed and alive (Shots 70 and 81) |
| The scarf cloud swept away, her legs left on the stones, the scarf settling over them (Shots 3 to 6) | Nimbo's own legs fall the same way (Shot 62). The coda grave shows the same legs and scarf (Shot 82), the audience's wink that the belief is a hoax |
| Nimbo's low knee light (Shot 8) | His legs die on the causeway (Shot 19) |
| Luma's sparks: cowlick (Shot 43), lightning inside her (Shot 53) | The zap (Shot 76), and Nimbo can zap too, charged by the storm (Shots 67, 69 and 77) |
| Luma's touch revives dead legs (Shot 26) | The playful zaps in the sky (Shots 76 to 79) |
| The legless cloud with her empty cup (Shot 13) | Luma revives her legs (Shot 34), and she shelters in the storm (Shot 50) |
| Charge as currency, counted bar by bar (Shots 8 and 9 to 12) | In the sky, power is free: sparks fly in play (Shots 76 to 79) |
| The inch he rises on the rooftop, his one clue that lightness exists (Shot 40) | The leap of trust at the climax (Shots 60 to 63) |
| Luma's calm, tender smile in the storm (Shots 53 to 59, 64 and 65) | The reveal that she always knew (Shots 73 to 75) |

---

# ACT 1: THE WEIGHT

*Setup. The grey world and its rules, told by one death and no explanation. Nimbo's absolute fear of the sky. His legs fail and a stranger changes his path. (0:00 to 1:48)*

## Scene 1: The Low Streets *(0:00 to 0:26)*

**Summary:** The opening image. A world built to hold on, with its rules told by a single gust and nothing else. We meet Nimbo, who only wants to get through the day charged, in order and unnoticed.\
**Append to every prompt in this scene:** Grade: desaturated slate grey-green, cold blue shadows, amber lamp glow, soft overcast light. The knitted scarf is the only saturated color in the scene, keep it coral and mustard.\
**Sound (added in post):** Low drone, slow tentative pizzicato, leg buzzes and clicks, faint wind hum, a siren wail, then silence.

**Shot 1: The blank sky** | 3s, generate at 4s and trim | Refs: none

> A blank white-grey overcast sky fills the whole frame, a few thin wisps of mist drifting very slowly across it. Camera: fixed, pointing straight up, with an almost imperceptible slow push-in. Flat, bright, empty, slightly menacing.

*Edit:* Wind hum fades in.

**Shot 2: Down to the street** | 3s, generate at 4s and trim | Refs: @Image6

> The pale sky, then the view moves slowly downward past wet iron rooftops to a narrow dark stone street with chains hung along every wall, ropes knotted around lampposts and ankle-high mist. Camera: one slow smooth pan downward, nothing else moves. Quiet, heavy mood.

*Edit:* Start on the last frame of Shot 1.

**Shot 3: The chained street** | 3s, generate at 4s and trim | Refs: @Image6, @Image11

> Three small cloud characters shuffle slowly toward the camera on electronic legs through low mist, each stepping carefully from one painted white circle on the ground to the next, heads down, small blue sparks flickering at their knees. Two are in dusty grey and cream. The third, at the back, wears a tiny knitted scarf in coral and mustard stripes and lags a few steps behind the others. Camera: slow smooth pull-out, backward, wide shot. Weary, cautious mood.

*Edit:* PLANT. The scarf is the only color in the frame, so the audience notices her before she is taken.

**Shot 4: The siren** | 4s | Refs: @Image6, @Image11

> High-angle wide shot of the chained street. A siren sounds. Along both walls, small cloud characters, each standing on a painted white circle beside a chain, grab the chain with both stubby arms and hold on tight. The scarf cloud is stranded in the open street, several circles away from the nearest chain, spinning in place with wide eyes. Camera: fixed. Tense stillness.

*Edit:* Add a siren wail in post just before the shot. Everyone else in the street makes it to a chain and holds on. Only she is left exposed. Keep the background clouds small and distant.

**Shot 5: The gust** | 4s | Refs: @Image11, @Image6

> A violent gust hits the street. The leather straps on the scarf cloud's electronic legs snap, her legs drop away and clatter onto the wet cobblestones, and she lifts straight up with her eyes wide in terror, her mouth open and her stubby arms reaching down toward the chain she could not reach, rising out of the top of the frame. Along the walls, every other cloud holds its chain tight, staring in horror. Camera: fixed wide shot at street level. Sudden, brutal.

*Edit:* A public event. Everyone holds on and everyone sees, and only she is taken. She believes it is death too. Her terror mirrors Nimbo's own tumble in Shot 67.

**Shot 6: The scarf** | 3s, generate at 4s and trim | Refs: @Image10

> At stone level, the tiny knitted coral and mustard scarf drifts down through the air and settles over the raised knee of a pair of empty electronic legs lying on the wet cobblestones, their leather straps torn and trailing, the knee cell lights flickering out one by one. Camera: fixed. Quiet, stunned.

*Edit:* PLANT. This is all that is left. The same legs and scarf return in the coda, Shot 82.

**Shot 7: The street watches** | 3s, generate at 4s and trim | Refs: @Image1, @Image6

> Nimbo, a small round grey-white cloud character with big glossy dark eyes, rosy cheeks and electronic legs, stands very upright on a painted white circle gripping a chain with both stubby arms. He stares ahead with wide eyes as his lower lip begins to tremble. Behind him, the other clouds along the street slowly lower their heads in silence. Camera: fixed medium close-up, eye level.

*Edit:* Cut here from the scarf. The whole street saw, and the silent bowed heads are the town's entire grief. Nimbo's fear is part of everyone's.

**Shot 8: The knee light** | 3s, generate at 4s and trim | Refs: @Image1

> Close-up on the knee of Nimbo's electronic leg. A small glowing amber battery cell in a glass and brass housing flickers low and dim, and a tiny blue spark jumps and fades. Camera: fixed close-up.

*Edit:* PLANT. He is low on charge. This is what drives him to the charging stall in the next scene.

---

## Scene 2: The Price of a Charge *(0:26 to 0:56)*

**Summary:** Charge is the world's currency. Nimbo's cell is nearly dead and he can afford only a sliver of power, and he cannot look at the sky.\
**Append to every prompt in this scene:** Grade: amber lamplight against cold blue, golden charged cells are the warmest color in frame, blown-out white sky in the alley.\
**Sound (added in post):** Sparse celesta over cell clinks and a faint electric hum. A stumble on a wrong note at the legless cloud. High thin violin and rising wind in the alley.

**Shot 9: The charging stall** | 4s | Refs: @Image6

> A cramped dark wooden stall with rows of small glowing amber battery cells on the shelves, one cell charging in a brass clamp beside a hand-cranked dynamo and a copper coil, a needle gauge with no numbers on the counter, warm amber light against the cold blue street. Two small cloud characters wait in line. Camera: slow push-in toward the glowing cells. Precious, fragile mood.

**Shot 10: The Vendor** | 3s, generate at 4s and trim | Refs: @Image4

> The Vendor, a slightly larger stern grey cloud character with a brass goggle over one eye, stands behind a counter with arms crossed, looking down. He glances at the needle gauge, frowns, softens, then frowns again. Camera: fixed medium close-up, low angle.

**Shot 11: The offer** | 5s | Refs: @Image1, @Image4

> Over-the-shoulder view from behind Nimbo at a counter. Nimbo sets a dead grey battery cell, a brass cog, a button and a bent spoon on the counter. The Vendor looks at the small pile, slowly shakes his head, then shrugs. Nimbo looks up with huge hopeful eyes and a trembling lower lip. Camera: fixed medium two-shot.

**Shot 12: A sliver of charge** | 4s | Refs: @Image1, @Image4

> The Vendor sighs, rolls his eyes, clamps the dead cell into the charger and turns the crank, and a thin thread of gold light fills the cell a quarter of the way. He slides it across the counter. Nimbo catches it in both stubby arms, hugs it to his chest and bows repeatedly in thanks, eyes shining. Camera: fixed medium two-shot, same framing as the previous shot.

**Shot 13: The legless cloud** | 5s | Refs: @Image5, @Image1

> A small cream cloud character with dead stumps trailing frayed cables sits in a gutter corner holding an empty tin cup. Her eyes follow Nimbo's glowing cell with longing as he passes, stops, looks at her, then lowers his eyes and walks on. Camera: slow tracking sideways at low angle, drifting past Nimbo to reveal her.

*Edit:* Sound: the celesta hits a wrong note as he looks away.

**Shot 14: The gap** | 3s, generate at 4s and trim | Refs: @Image1

> A narrow stone alley ends in a bright slice of blank white sky. Nimbo enters from the left, small against the tall walls, buzzing toward the bright gap. Camera: fixed, symmetrical wide shot centered on the gap. Rising dread.

**Shot 15: The flinch** | 3s, generate at 4s and trim | Refs: @Image1

> Close-up on Nimbo's face as he glances up. His big glossy eyes fill with white sky, his pupils shrink, his cheeks sink and his mouth trembles. Camera: fixed close-up with a very slow push-in.

*Edit:* Cut straight from this to the next shot.

**Shot 16: Scuttling away** | 3s, generate at 4s and trim | Refs: @Image1

> Nimbo squeezes his eyes shut, hugs himself and scuttles quickly forward on his electronic legs, blue sparks flickering at his knees, leaving the bright gap behind. Camera: fixed wide shot, same framing as the alley shot.

*Edit:* Footstep rhythm speeds up like a racing heartbeat.

---

## Scene 3: The Causeway *(0:56 to 1:22)*

**Summary:** The inciting incident. Out of power, his legs die on an open bridge as the wind rises.\
**Append to every prompt in this scene:** Grade: sickly yellow-grey sunset, cold deep shadows, wind blowing mist.\
**Sound (added in post):** Trembling high strings. Nimbo's leg buzz turns uneven.

**Shot 17: The bridge** | 4s | Refs: @Image7

> Aerial view of a long iron causeway crossing a vast open void at sunset, a few tiny cloud characters scurrying across it, mist blowing through the railings. Camera: slow aerial descent toward the bridge. Uneasy mood.

**Shot 18: Crossing** | 4s | Refs: @Image1, @Image7

> Nimbo walks along the iron bridge toward the camera on his electronic legs, eyes locked on his feet, his knee lights glowing a dim amber and tiny blue sparks flickering at his knees. Camera: smooth tracking shot moving backward in front of him, medium shot.

**Shot 19: The stutter** | 3s, generate at 4s and trim | Refs: @Image1

> Close-up of Nimbo's left electronic leg mid-step. The knee light flickers, sparks spit from the cell housing, the light goes dark, the leg locks and his body jerks to a stop. Camera: fixed low angle with a slight handheld sway.

*Edit:* INCITING INCIDENT. Add a descending electrical whine and a dead click in post.

**Shot 20: Dead** | 4s | Refs: @Image1

> Nimbo pulls the battery cell from his knee, holds it up and shakes it. It is dark. Nothing happens. His eyes widen, his lower lip wobbles and a tear gathers. Camera: fixed medium close-up.

**Shot 21: The wind builds** | 4s | Refs: @Image7, @Image1

> Wide shot of the causeway as grey clouds ripple on the horizon and the wind picks up. Two small cloud characters on electronic legs sprint past Nimbo, who stands frozen mid-frame. Camera: fixed wide shot.

*Edit:* Siren far away, added in post.

**Shot 22: Holding on** | 4s | Refs: @Image1

> Nimbo throws both stubby arms around a railing post, one dead leg dragging stiffly. Small wisps of his fluffy body peel upward from his head and shoulders in the wind. He squeezes his eyes shut. Camera: fixed low-angle medium shot.

**Shot 23: Nobody stops** | 3s, generate at 4s and trim | Refs: @Image1

> Over-the-shoulder shot from behind Nimbo. A passing cloud character glances back at him, hesitates, then runs on. Nimbo's face in profile crumples. Camera: fixed medium shot.

---

## Scene 4: Luma *(1:22 to 1:48)*

**Summary:** A clumsy stranger fixes what no one else will. Nimbo makes his first choice: he takes her hand.\
**Append to every prompt in this scene:** Grade: cold grey with a growing pocket of warm honey light and a faint lilac glow around Luma.\
**Sound (added in post):** A single clear glass chime (first note of Luma's theme), then a music box.

**Shot 24: The bump** | 3s, generate at 4s and trim | Refs: @Image1

> Close-up on the back of Nimbo's head as something soft bumps into him. His eyes snap wide open. Camera: fixed close-up.

*Edit:* Glass chime on the bump.

**Shot 25: Meet Luma** | 6s | Refs: @Image1, @Image3

> Luma, a pearl-white cloud character with a faint lilac shimmer, a wispy cowlick and no legs, tumbles slowly off Nimbo's back, bounces off the railing and wobbles in the air, upside down for a moment, smiling widely and utterly unbothered. She gives a big cheerful wave. Nimbo, rigid, stares at her with huge horrified eyes and his mouth open, certain she is being swept away. Camera: fixed medium shot, focus shifts from Nimbo to Luma.

*Edit:* Luma is amused by the wind that terrifies everyone else. Nimbo reacts exactly as the town would: he fears for her. He has never seen a cloud float and does not understand it. She reads as naive. Her wisdom is revealed only in the sky.

**Shot 26: The touch** | 5s | Refs: @Image1, @Image3

> Luma drifts down with a playful bounce and presses her stubby palm onto Nimbo's dead knee, as if playing a game. A tiny blue-white spark jumps from her palm into the leg, the knee light flickers back to amber, the coil hums, the leg bends, and a soft wisp of Nimbo's fluff lifts from his shoulder. Nimbo stares at the knee, mouth open, not noticing the wisp. Camera: fixed medium close-up on the knee and both faces.

*Edit:* Music box theme enters in full. Hint only: her touch does not so much repair the leg as remind a cloud what it is. Never explain it.

**Shot 27: Taking her hand** | 5s | Refs: @Image1, @Image3

> Luma holds out her palm to Nimbo with a big bouncy grin. He looks at her hand, glances up at the sky, then back at her, hesitates, and slowly takes it with both stubby arms. Camera: fixed medium shot with a slight push-in.

*Edit:* PLOT POINT 1. Nimbo makes a choice.

**Shot 28: Crossing together** | 7s | Refs: @Image1, @Image3, @Image7

> Nimbo crosses the causeway gripping Luma's hand with both stubby arms, stepping stiffly on his electronic legs, while Luma happily lets a gust lift her like a balloon on a string, her mist tail streaming. Nimbo tugs her back down with wide eyes. Camera: smooth tracking shot from the side, medium wide.

*Edit:* Dissolve to Scene 5 in post.

---

# ACT 2: THE LIGHTNESS

*Confrontation. Luma changes Nimbo's world, friendship becomes love, then the storm begins to call and everything he built to stay safe turns against him. (1:48 to 5:08)*

## Scene 5: Things Get Lighter *(1:48 to 2:54)*

**Summary:** Fun and games. Friendship grows into love as colors warm and Nimbo's legs need less charge.\
**Append to every prompt in this scene:** Grade: teal and honey, soft warm morning light, glowing mist, getting warmer with each shot.\
**Sound (added in post):** Luma's theme grows into a playful arrangement with pizzicato and glockenspiel, Nimbo's leg buzz and click as percussion, soft wordless giggles.

**Shot 29: The lamppost** | 6s | Refs: @Image3, @Image1, @Image6

> Luma drifts slowly into an iron lamppost, bounces off, spins once, gives the post a tiny apologetic bow and a cheerful wave. Behind her Nimbo stands rigid on a painted white circle, watching in worry. In the background a passing cloud pauses and shakes its head sympathetically at her legless drifting. Camera: fixed medium shot. Gentle comedy.

*Edit:* The town thinks she is one of them, a cloud with no legs, and fears for her.

**Shot 30: Nimbo laughs** | 4s | Refs: @Image1

> Close-up of Nimbo trying to keep a stern, rigid face with lips pressed tight, then cracking and bursting into a squeaky silent laugh, eyes squeezed into happy arcs, cheeks glowing pink. Camera: fixed close-up.

*Edit:* His first crack. Warm music begins.

**Shot 31: Morning routine** | 9s | Refs: @Image1, @Image3

> Luma hums and rests her palm on Nimbo's knee, wiggling her mist tail. A soft blue-white crackle runs through the leg and the knee light glows amber. Nimbo stands stiff with his arms pressed to his sides, then loosens a little as his leg bends smoothly, and gives a small shy bounce. Camera: fixed close-up on the knee, Luma's palm and Nimbo's face.

*Edit:* Generate three variants (dawn, noon, evening light) and cut them as three beats of about 3 seconds. Nimbo is a little looser in each.

**Shot 32: Siren surfing** | 8s | Refs: @Image1, @Image3, @Image6

> A siren sounds. Two small cloud characters in the background freeze, gripping chains, and one of them opens an eye and holds out the loose end of its chain toward Luma with a worried face. Nimbo grips a chain with one stubby arm. A gust lifts Luma like a kite, her arms spread, wide-eyed with wonder, while Nimbo holds on to her wispy tail with his other arm, eyes wide in panic. Camera: fixed medium wide shot.

*Edit:* Luma treats the siren like a game. The town offers her a chain because they fear for her.

**Shot 33: Careless with charge** | 6s | Refs: @Image4, @Image3, @Image1

> At the charging stall, Luma floats up to a shelf and happily pats a glowing cell, which rolls toward the edge. Nimbo dives and catches it just in time, hugging it to his chest, eyes wide. Luma claps her stubby arms, delighted. The Vendor stares in alarm. Camera: fixed medium shot.

*Edit:* Charge is just something shiny to her.

**Shot 34: Reviving legs** | 8s | Refs: @Image5, @Image3, @Image1

> In the gutter, Luma floats beside the small cloud with dead stumps and, humming cheerfully, touches her palm to them as if it were nothing. Blue-white sparks run along the frayed cables, the knee lights flicker on and the stumps bend into working legs. The small cloud gasps, eyes wide and shining. Nimbo watches from the background, awestruck. Camera: slow push-in.

**Shot 35: The gift** | 6s | Refs: @Image1, @Image3

> Nimbo holds out a small glowing battery cell tied with a scrap of ribbon. Luma looks at it, then at his face, then hugs it to her chest like treasure, a tear and a smile. Camera: fixed medium shot with a slow push-in.

**Shot 36: Twirl** | 9s | Refs: @Image1, @Image3

> Luma pulls Nimbo into a twirl by both hands. Nimbo is stiff and stumbling at first, then loosens up and spins freely, his electronic legs buzzing in rhythm, glowing mist and tiny blue sparks swirling around them. Both laugh silently. Camera: slow orbit around them, medium shot.

**Shot 37: Rules of the street** | 10s | Refs: @Image1, @Image3, @Image6

> Nimbo steps carefully from one painted white circle to the next along the misty street while Luma drifts a zigzag path around him, bumping a wall, a barrel, then Nimbo himself. Nimbo stops and glances at the next circle, then deliberately steps off the path and follows Luma, a small smile forming. Camera: smooth tracking from the side, medium wide.

*Edit:* A tiny rebellion. Dissolve to Scene 6.

---

## Scene 6: The Edge *(2:54 to 3:43)*

**Summary:** Luma invites Nimbo upward. The midpoint: he floats, then the storm appears.\
**Append to every prompt in this scene:** Grade: warm golden dusk, first stars, then a cold white flash on the horizon.\
**Sound (added in post):** Luma's theme as a lullaby on glass harmonica, then a low rumble underneath.

**Shot 38: Rooftop** | 6s | Refs: @Image8, @Image1, @Image3

> On a rooftop under an iron awning at golden dusk, Nimbo sits rigid and upright with his arms pressed to his sides. Luma floats upside down above him, her cowlick tickling his nose. His nose twitches and he sneezes a puff of fluff, and Luma laughs silently. Camera: fixed medium two-shot.

**Shot 39: The invitation** | 7s | Refs: @Image3, @Image1

> Luma looks up at the first stars, points upward with an excited bounce, then turns and holds out both stubby arms to Nimbo. Nimbo looks up at the stars, tilts his head in puzzlement, then looks at her open hands, uncertain. He has no idea what she is asking. Camera: fixed medium two-shot.

**Shot 40: The inch** | 7s | Refs: @Image1, @Image3

> Nimbo takes Luma's stubby hands. She gently draws him forward. His electronic legs tilt and his feet lift one inch off the tiles. His eyes go wide in pure shock, his mouth falls open and he looks down at the gap beneath his feet. Camera: fixed medium shot, low angle.

**Shot 41: He floats** | 9s | Refs: @Image1, @Image3

> In slow motion, Nimbo rises a few inches above the rooftop with his heavy electronic legs dangling, Luma beaming below. He looks down at his dangling legs in astonishment, then up at the starry sky with the stars reflected in his glossy eyes, and wonder spreads across his face until a wide shy smile blooms. Camera: slow push-in, low angle.

*Edit:* MIDPOINT. A real discovery: he never suspected he could float. Shock and wonder first, fear second. This inch is his one clue that lightness exists. Luma's theme swells into its warmest chord.

**Shot 42: The flash** | 6s | Refs: @Image8

> Extreme wide shot of the dark horizon. Deep inside a distant bank of black cloud, a flicker of white lightning lights it from within. Camera: fixed, locked off.

*Edit:* Delayed low rumble in post.

**Shot 43: He sinks** | 6s | Refs: @Image1, @Image3

> Nimbo's smile drops, his eyes dart to the horizon in sudden dread and he sinks back down, electronic feet thudding onto the tiles. Beside him Luma turns her head toward the storm and tiny sparks glitter along her cowlick. Camera: fixed medium two-shot.

*Edit:* The lullaby breaks on a discordant note.

**Shot 44: Hand in hand** | 8s | Refs: @Image1, @Image3

> Nimbo and Luma sit close together on the rooftop, hands joined, watching distant lightning flicker. Nimbo, now relaxed against her shoulder, looks at Luma with worry, and Luma smiles gently and squeezes his hand. Camera: slow push-in, medium shot from behind and to the side.

*Edit:* Fade to black in post.

---

## Scene 7: The Storm Calls *(3:43 to 4:13)*

**Summary:** The storm's static scrambles the town's legs and drowns Luma's spark. The storm calls her and she drifts toward it, happy. Nimbo's legs begin to fail again and he tries to protect her.\
**Append to every prompt in this scene:** Grade: cold indigo night, pulses of white on the horizon every few seconds.\
**Sound (added in post):** Low ominous drone, distant thunder, static crackle, Luma's theme fragmenting.

**Shot 45: The spark fails** | 6s | Refs: @Image3, @Image1

> Luma presses her palm to Nimbo's knee. The blue-white spark sputters and dies, and static crackles over the leg. The knee light stutters, the leg lags and he looks at her in alarm. Luma looks at her own palm, tilts her head, then gives him a gentle, reassuring smile. Camera: fixed medium close-up.

*Edit:* The storm's electrical interference scrambles the town's legs and drowns her small spark. Never explained.

**Shot 46: Sleepwalking** | 8s | Refs: @Image3, @Image1, @Image6

> Night. Luma, eyes closed and smiling, drifts out of Nimbo's doorway toward the dark horizon like a kite on a string. Nimbo lunges, catches the end of her wispy tail and hauls her back. She wakes, blinks, sees his panicked face and gives him a soft smile, patting his cheek. Camera: fixed high-angle wide shot.

**Shot 47: The rope** | 7s | Refs: @Image1, @Image3

> Nimbo ties a rope between his wrist and Luma's, pulling the knot tight, checking it, then checking it again. Luma tilts her head, then wiggles her wrist to bounce the rope like a toy leash, trying to make him smile. Nimbo, still worried, stares at her. Camera: fixed medium two-shot with a slow push-in.

**Shot 48: Doors bolted** | 3s, generate at 4s and trim | Refs: @Image6

> At night, a small cloud character on electronic legs drags a heavy chain across a doorway as thunder rolls. Camera: fixed medium shot.

*Edit:* Siren wails continuously from here.

**Shot 49: The Vendor ties down** | 3s, generate at 4s and trim | Refs: @Image4

> The Vendor hurries to tie ropes over his shelves of glowing cells, his goggle flashing with distant lightning. Camera: fixed medium shot.

**Shot 50: Cup in the doorway** | 3s, generate at 4s and trim | Refs: @Image5

> The revived small cloud drags her tin cup into a stone doorway on her newly working legs and looks up nervously at the lightning. Camera: fixed medium shot.

---

## Scene 8: The Storm *(4:13 to 5:08)*

**Summary:** All is lost, as Nimbo sees it. The rope snaps, the legs die and Luma is lifted away. The darkest hour.\
**Append to every prompt in this scene:** Grade: bruised indigo and violet, black clouds, white lightning flashes, heavy rain.\
**Sound (added in post):** Full orchestral storm, timpani and brass stabs, screaming siren, roaring wind.

**Shot 51: The wall of black** | 7s | Refs: @Image6

> Extreme wide, low angle. A colossal black thundercloud rolls over the grey city, lightning forking inside it, its shadow swallowing the streets. Camera: slow pull-out. Terrifying scale.

**Shot 52: Chaos on the ground** | 6s | Refs: @Image6

> Heavy rain and wind. Three small cloud characters cling to chains and lampposts, electronic legs sparking against the stones, eyes squeezed shut, while debris and lantern glass fly past. Camera: handheld with moderate shake, medium wide.

*Edit:* Keep the characters as dark silhouettes in rain.

**Shot 53: The tower** | 7s | Refs: @Image1, @Image3

> At the base of an iron signal tower, Nimbo grips an iron beam with wide terrified eyes while a rope runs from his wrist to Luma, who streams sideways in the wind toward the storm with her arms spread as if flying, eyes wide with wonder and her smile calm, blue-white lightning crackling inside her body. Camera: fixed wide shot with a slight handheld sway.

**Shot 54: The rope snaps** | 4s | Refs: none

> Extreme close-up of a fraying rope under tension. Strands snap one by one and the rope breaks apart. Camera: fixed.

**Shot 55: Lifted away** | 8s | Refs: @Image1, @Image3

> Luma is lifted off her feet toward the sky, her eyes wide with wonder. She looks down at Nimbo with a calm smile. Nimbo lunges, catches her hand with both stubby arms and is dragged off the ground, his electronic legs scraping the stones in sparks. Camera: handheld with moderate shake, medium shot.

**Shot 56: The cell cracks** | 4s | Refs: @Image1

> Close-up on Nimbo's right electronic leg. The knee cell cracks, blue sparks spray, the light goes dark and the leg collapses. Camera: fixed close-up.

**Shot 57: Stuck** | 5s | Refs: @Image1, @Image3

> Both of Nimbo's legs go dead and jam their feet between the wet stones, a dead weight pinning him to the ground, as he clings to an iron beam with one stubby arm and to Luma's hand with the other. Luma floats above him like a flag in the wind, her smile calm, squeezing his hand back, while Nimbo strains. Her hand is slipping from his. Camera: fixed low-angle medium shot.

**Shot 58: Nobody helps** | 5s | Refs: @Image6, @Image4

> High-angle wide shot in heavy rain. Dark silhouettes of small cloud characters haul themselves along their chains with both stubby arms into bolted doorways, one by one, until the street around the signal tower is empty. In the foreground the Vendor looks across the street at Nimbo and Luma, hesitates, then turns his face away and slips into his own doorway. Camera: fixed.

**Shot 59: All is lost** | 9s | Refs: @Image1, @Image3

> Close-up on Luma, her face lit by lightning, her hand slipping from his. Nimbo's eyes fill with tears, he glances down at his dead legs, then back at her. Luma sees his tears, her smile softens, and she gently wipes a tear from his cheek with her free stubby arm. Camera: slow push-in, close two-shot.

*Edit:* From Shot 58 on, nobody else is near the tower: Luma is the only one with him until he rises. ALL IS LOST, for Nimbo. Luma never stops smiling, and she never ignores him. Nimbo carries all the fear.

---

# ACT 3: THE SKY

*Resolution. Nimbo chooses. He lets go of everything he built to stay safe, believing it is the end, and is carried into a world he never knew existed, where Luma is waiting. (5:08 to 7:00)*

## Scene 9: The Letting Go *(5:08 to 5:48)*

**Summary:** Plot Point 2 and the climax. Nimbo makes his active choice. He has never imagined floating, so he is not choosing freedom: he believes he is giving his life for Luma's. The dead legs pin him to the stones, and he lets go of everything to get her to safety.\
**Append to every prompt in this scene:** Grade: violet strobing storm light, then one warm gold flash at the moment of release.\
**Sound (added in post):** The score builds, then drops out for two seconds as he unbuckles. Only a heartbeat and four clicks.

**Shot 60: The choice** | 6s | Refs: @Image1

> Extreme close-up on Nimbo's eyes with the storm reflected in them. His expression changes from terror to a quiet, resolute calm, the look of someone who has decided to give everything. Camera: fixed, very slow push-in.

*Edit:* PLOT POINT 2. The square is empty from here: only Nimbo and Luma. He believes this means death, and he does it only for Luma. A real sacrifice, not a wish coming true.

**Shot 61: The buckles** | 6s | Refs: @Image1

> Medium shot. Nimbo looks down and with his stubby arms undoes the leather buckles on his electronic legs one after another, each buckle popping open. Camera: fixed medium shot, low angle.

*Edit:* Add four click sounds in post and cut the music.

**Shot 62: The legs fall** | 6s | Refs: @Image1

> High-angle wide shot looking straight down. Two electronic legs fall away and clatter onto the wet stones, their knee lights flickering out, small and ugly, then lie still. Camera: fixed, high angle. Total stillness.

*Edit:* Hold the silence for one beat. This mirrors Shot 5.

**Shot 63: Nimbo lifts** | 8s | Refs: @Image2

> In slow motion, Nimbo, now without legs, rises softly from the ground, his round fluffy body stretching and loosening at the edges. His eyes widen in wonder as a warm golden flash lights his face. Camera: fixed low-angle close-up.

*Edit:* One sustained string note enters. Hint only: the golden flash echoes the spark from Luma's palm in Shot 26.

**Shot 64: The shove** | 6s | Refs: @Image2, @Image3

> Nimbo wraps both stubby arms around Luma and pushes her down into the sheltered side of the tower, where she settles against the iron. He gives her one precise nod and a small, sure, sad smile. She holds his gaze with a tender smile. Camera: fixed medium shot with a slight handheld sway.

*Edit:* He believes this is goodbye. To him and to the audience, she is naive and has no concept of dying.

**Shot 65: The wind takes him** | 8s | Refs: @Image2, @Image3

> A huge gust rips through the street. Nimbo lets go and rises, spinning, a small round shape against the lightning. In the shelter of the tower, Luma watches him go with the same tender smile, her arms resting at her sides. Camera: low angle, slow pan upward following him.

*Edit:* Luma's theme breaks into one sustained note. The music grieves and Luma does not. Her smile never falls and she does not reach for him.

---

## Scene 10: The Ascent and the Sky *(5:48 to 6:27)*

**Summary:** Nimbo faces what he feared most and discovers a living world, full of families going about their lives, with nothing to fear. He is only a visitor in it.\
**Append to every prompt in this scene:** Grade: lightning and black, brightening to dawn gold, then full saturation: liquid gold, rose, pearl and aquamarine.\
**Sound (added in post):** Orchestral swell, wind thinning, then a wordless choir and strings resolve Luma's theme for the first time. No mechanical sound at all.

**Shot 66: The city shrinks** | 7s | Refs: @Image2

> Aerial view looking down from above Nimbo as he rises. The city shrinks beneath: rooftops become toys, chains become threads, the streets are empty with doors bolted under the hammering rain, and the signal tower becomes a pin with a single tiny pearl-white glow at its base, looking up. Camera: slow aerial pull-out.

*Edit:* This is the last time we see the town until the coda. Nobody else is around: only Luma witnesses his ascent. It is a private moment.

**Shot 67: Tumbling** | 4s | Refs: @Image2

> Nimbo tumbles through rain and lightning with eyes squeezed shut and arms hugging his body, bouncing off a gust and spinning the other way, faint blue-white sparks crawling over his fluff as lightning strikes near. Camera: handheld with moderate shake.

*Edit:* PLANT. The storm is charging him.

**Shot 68: Eyes open** | 4s | Refs: @Image2

> Extreme close-up on Nimbo's closed eyes as violet light turns to gold across his face. His lids flutter and open. Camera: fixed close-up.

**Shot 69: Breaking through** | 4s | Refs: @Image2

> Low angle looking up. Nimbo bursts out of the top of the storm into blazing golden light with a soft lens flare, faint sparks still crawling over his fluff, the storm becoming a dark floor below him. Camera: fixed, low angle.

**Shot 70: The reveal** | 10s | Refs: @Image2, @Image9

> A vast golden sky. Enormous glowing cloud islands drift in slow orbits, rivers of mist pour between them, colossal whales of vapor glide through the haze, and clusters of legless cloud characters of every size drift together, large ones with tiny ones trailing behind on wisps of mist, all trailing light. Tiny Nimbo hangs in the foreground with arms spread. No chains, no ropes. Camera: slow aerial pull-out revealing the scale.

*Edit:* The choir enters and Luma's theme resolves.

**Shot 71: Nimbo's face** | 6s | Refs: @Image2

> Close-up of Nimbo slowly rotating in the air, mouth open, eyes full of golden light, cheeks flushing pink. A shy smile grows wide as a few glittering tears drift up from his cheeks like tiny bubbles. Camera: slow orbit, close-up.

**Shot 72: Life in the sky** | 4s | Refs: @Image2, @Image9

> Nimbo hangs small in the foreground, watching, as groups of legless cloud characters drift past at a distance: a large cloud with three tiny ones trailing behind it on a wisp of mist, two medium clouds tumbling together, a very large slow cloud with a tiny one riding on top. None of them notice him. Camera: fixed medium wide shot.

*Edit:* Nimbo is only a visitor. This gives the audience and Nimbo the idea that there is a whole life here, with families and everyday routine. No interaction.

---

## Scene 11: The Chase *(6:27 to 7:00)*

**Summary:** Luma appears unannounced and shows, without a word, that she always knew. A joking scare, a game of zaps and a chase end the film on the carefree feeling Luma has had all along, now shared with Nimbo and the audience.\
**Append to every prompt in this scene:** Grade: full saturation golden sky, liquid gold, rose, pearl and aquamarine, light and warm.\
**Sound (added in post):** Luma's music box theme in a bouncy full arrangement with glockenspiel and choir, soft electric crackles, wordless giggles. No mechanical sound at all.

**Shot 73: The tap** | 3s, generate at 4s and trim | Refs: @Image2, @Image3

> Nimbo hangs in the golden sky gazing at the distant islands, his fluff faintly crackling with blue-white sparks. A soft pearl-white stubby arm enters the frame from behind him and taps his shoulder twice. Nimbo slowly turns his head, puzzled. Camera: fixed medium shot from the front, with a slight push-in.

*Edit:* UNANNOUNCED. Luma has not been seen or hinted at since Shot 65. Do not show her face.

**Shot 74: The boo** | 3s, generate at 4s and trim | Refs: @Image2, @Image3

> Luma pops up upside down right in front of Nimbo's nose, cheeks puffed and eyes crossed in a silly "boo" face, her cowlick bobbing. Nimbo jumps back with his arms flung wide. Camera: fixed medium close-up.

*Edit:* A slight joking scare. The comedy peak of the film.

**Shot 75: He understands** | 3s, generate at 4s and trim | Refs: @Image2, @Image3

> Nimbo's frightened face melts into disbelief. He looks at Luma, then down at the dark storm floor far below, then back at her, and points a stubby arm at himself, then at the storm. Luma tilts her head, grins and gives a cheerful shrug. Camera: fixed medium two-shot.

*Edit:* THE REVEAL. In silent comedy: "I thought I was dead. You knew?" Her calm, her smiles and her wonder in the storm all re-read on a second viewing.

**Shot 76: The zap** | 3s, generate at 4s and trim | Refs: @Image2, @Image3

> Luma, grinning, taps Nimbo's shoulder with her palm and a small blue-white spark jumps. Nimbo's fluff frizzes straight out in every direction and his eyes bulge. Camera: fixed medium close-up.

*Edit:* Unsolicited. The first zap in the sky.

**Shot 77: His spark** | 4s | Refs: @Image2, @Image3

> Nimbo looks at his stubby arms in astonishment as tiny blue-white sparks crawl over his fluff. His astonishment turns to a mischievous grin and he points an arm at Luma, and a small spark leaps across and zaps her cheek. Camera: fixed medium two-shot.

*Edit:* He is charged from the storm. If the model merges the two beats, generate them as two takes and cut them together.

**Shot 78: The frown** | 3s, generate at 4s and trim | Refs: @Image3

> Close-up on Luma's face, her cowlick frizzed and a tiny puff of smoke curling from her cheek. Her smile drops into a frown, her brows scrunched and her cheeks puffed in playful indignation. Camera: fixed close-up.

*Edit:* The only frown of the film, and a playful one. The mirror of Nimbo's first laugh in Shot 30.

**Shot 79: Her zap and exit** | 3s, generate at 4s and trim | Refs: @Image2, @Image3

> Luma zaps Nimbo back with a bigger spark, her frown flipping into a beaming smile, and darts away upside down with her mist tail streaming, leaving Nimbo's fluff on end. Camera: fixed medium shot.

**Shot 80: The chase** | 6s | Refs: @Image2, @Image3, @Image9

> Wide aerial view of the golden sky. Luma zigzags upside down between enormous cloud islands, past a tiny cloud no bigger than a button and a colossal slow cloud, while Nimbo chases her, loose and wobbly with his arms flung wide, bumps into a soft cloud, bounces off and gives it a tiny apologetic bow without breaking stride. Camera: smooth aerial tracking shot following them.

*Edit:* Nimbo now moves like Luma: loose, a little late and bumping into things, with a bow and a wave. The world is observed in passing, never interacted with.

**Shot 81: Into the horizon** | 5s | Refs: @Image9

> Extreme wide aerial shot of the golden sky world with a glowing horizon. Two tiny figures chase each other, small blue-white sparks flicking between them, shrinking toward the glowing horizon until they are two points of light. Camera: fixed, locked off.

*Edit:* Luma's theme resolves with the full choir. Slow fade to white in post, then the hand-drawn title NIMBO, then cut to the coda.

---

## Coda: The Grave *(after 7:00, over the credits)*

**Summary:** The only return to the town since Shot 66, and the only grave in the film. It tells the audience, with a wink, that the belief is a hoax.\
**Append to every prompt in this shot:** Grade: desaturated slate grey-green, cold blue shadows, soft overcast light. The scarf is the only saturated color.\
**Sound (added in post):** Luma's music box theme plays on cheerfully. The only other sound is the wind in the scarf.

**Shot 82: The grave** | generate at 8s, extend or loop to the length of the credits | Refs: @Image10, @Image6

> A plain blank stone slab with no writing stands in a quiet corner of the Low Streets, with chains hanging on the wall behind it. Before the slab stand a pair of empty electronic legs propped upright, their knee cells dark, cables and leather straps hanging open. A tiny knitted coral and mustard scarf is draped over one knee, its fringe stirred only by the wind. Camera: fixed, locked off, no movement. Quiet, still.

*Edit:* The credits roll on the stone itself, added in post. Keep the music playful and the image still, so the audience is in on the joke. No other movement in the frame except the scarf.

---

**END**
