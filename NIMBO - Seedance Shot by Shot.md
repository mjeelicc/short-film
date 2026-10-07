# NIMBO

*A silent animated short film, 7:00. Written for AI generation with Seedance: 77 shots, each one generation.*

---

## HOW THIS SCRIPT IS BUILT FOR SEEDANCE

Every shot is one self-contained generation with one subject action, one camera move and one place. Each prompt is written in the order Seedance responds to best: subject, action, setting, camera, mood. Append the **Style line**, the scene's **Grade line** and the **Avoid line** below to every prompt.

**Rules applied to the whole film**

- **Clip length:** Every shot runs 3 to 10 seconds. Per-generation caps vary by platform and version (roughly 12 to 15 seconds on Seedance 2.0, longer on 2.5), so nothing here depends on a long take. Shots under 4 seconds are generated at 4 seconds and trimmed in the edit.
- **One camera move per shot,** using only moves the model handles well: fixed (locked off), slow push-in, pull-out, pan, tracking, orbit, aerial and handheld. Smash zooms, whip pans, compound crane moves and in-shot transitions were removed. Cuts, dissolves, fades, speed changes and the title are all done in the edit.
- **Two actions never share a shot.** Where the old script had a sequence in one shot, it is now split into separate shots.
- **One expression change per shot.** Expressions are big and simple: eyes wide, lip wobble, cheeks sinking, a small smile blooming.
- **No text anywhere.** The shop signs and the painted circles contain no writing. The title is added in post.
- **No fingers.** Every character has soft mitten-like stubby arms. There are no extreme close-ups on hands.
- **Small casts per frame.** No more than three or four characters share a frame. Storm crowds are shown as dark silhouettes in rain, seen from behind or from above.
- **Simple mechanics.** The brass legs are chunky with two or three visible parts. Close-ups show one joint at a time.
- **Moderate speed in the storm.** Handheld shots use moderate shake and strong silhouettes, because fast complex motion can warp.
- **No age words in prompts.** The characters are written as "small cloud characters" with reference images carrying their look, since prompts with words like child, kid, boy or girl can be flagged.
- **Sound is built in post.** Music and effects are added in the edit so the motifs stay consistent across 77 shots. The notes under each scene and shot are the sound plan.

**Workflow**

1. Build the reference sheets below with an image model.
2. Attach only the references each shot lists (two to four per shot).
3. Where a shot continues the previous one, use the previous shot's last frame as the first frame.
4. Generate two to three takes per shot and keep the best.
5. Assemble, add transitions, fades, sound and the title in the edit.

**Reference images**

| Tag | Reference sheet |
| --- | --- |
| @Image1 | Nimbo with legs: small round fluffy grey-white cloud, big glossy dark eyes, rosy cheeks, tiny stubby mitten arms pressed close to his body, oversized thin brass piston legs strapped on with worn leather buckles, stands very upright |
| @Image2 | Nimbo without legs: same body, slightly lighter and fluffier |
| @Image3 | Luma: pearl-white cloud, faint lilac shimmer, wispy cowlick, no legs, soft tail of mist, softly glowing palms, always grinning |
| @Image4 | The Vendor: slightly larger stern grey cloud, brass goggle over one eye, rusty brass legs |
| @Image5 | The legless cloud: small cream cloud, rusted stiff stumps, empty tin cup |
| @Image6 | The Low Streets: dark wet stone, chains on every wall, roped lampposts, ankle-high mist, a painted white holding circle on the ground beside each chain (no writing) |
| @Image7 | The causeway: long iron bridge over a void at sunset |
| @Image8 | The rooftop at dusk with an iron awning |
| @Image9 | The sky world: glowing cloud islands, rivers of mist, vapor whales |
| @Image10 | The empty legs: a pair of rusty brass piston legs standing upright on a small stone plinth, leather straps hanging open and one torn, a tiny knitted scarf in coral and mustard stripes draped over one knee |
| @Image11 | The scarf cloud: a small legless peach-cream cloud, always laughing, wearing the same tiny knitted coral and mustard striped scarf |

**Style line:** Stylized 3D animated short film look, soft rounded shapes, matte felt-like cloud texture, painterly storybook lighting, gentle film grain, 16:9.

**Avoid line:** No text, no letters, no logos, no subtitles, no extra characters, no jitter, no morphing, no bent or extra limbs, no cuts or scene changes inside the clip.

---

## CHARACTER CONTRAST

The contrast is never explained. It lives in posture, movement, expression and what each character does when the same thing happens.

|  | NIMBO | LUMA |
| --- | --- | --- |
| **Nature** | Cute, uptight, scared, an introvert who follows the rules | Cute, carefree, clumsy and always happy |
| **Posture** | Very upright, arms pressed to his sides, small precise steps | Loose and wobbly, arms flung wide, drifts in curves, often upside down |
| **Movement** | Staccato and mechanical: tick, clank, hiss | Flowing and a little late, bumping into things |
| **Face** | Wide worried eyes, tight lips, blushes easily, laughs only when he cracks | Wide grin, sparkling eyes, head tilts, cowlick bobbing |
| **Want** | To get through the day oiled, in order and unnoticed | Whatever is shiny, or next |
| **With others** | Stays at the edge, avoids eye contact, flinches | Waves at everyone and everything, including a lamppost |
| **The rules** | Steps only on the painted circles, counts oil drops, bows his head at a funeral, grips a chain at the siren | Does not know or care. Chains are toys, the siren is a game, oil is something shiny |
| **The sky** | Cannot look at it. He does not know what a cloud is. To him, floating means being swept away and dying | She belongs to it. The wind that terrifies the town makes her giggle |
| **Sound** | Leg clanks and hisses | Music box theme, soft bounces, silent giggles |

**The comedy pattern:** Nimbo follows a rule. Luma breaks it without noticing. Nimbo panics. Nothing bad happens. Over time Nimbo loosens. This repeats at the lamppost, the siren surfing, the careless oil shelf, the twirl and the circles in the street.

**The arcs:** Nimbo moves from rigid to loose, and finally to free. Luma does not change. She smiles through the rope, the storm, the dead legs and the slipping grip, even while being saved, and treats all of it as a game. Her smile falls exactly once, in Shot 65 when Nimbo is carried away, and it returns in her last shot when she waves at the sky.

**Writing rule for Seedance:** Personality is always written as visible action (a grin, a wave, a bounce, a rigid stance, a tight lip), never as an adjective alone.

---

## STRUCTURE BLUEPRINT

**Logline:** In a town where every cloud is bolted to the ground because the sky means death, a small cloud who has never imagined floating must unbuckle the heavy legs that keep him safe to save the one he loves.

**Dramatic question:** Will Nimbo give up his legs and face the sky to save Luma?

**Theme:** What keeps you safe can keep you from living.

**Irony:** The legs he wears to avoid being swept away nearly cost him Luma. Being swept away is what sets him free. The town mourns the clouds the sky took, and they were never gone.

**The town's blindness:** Nobody in the Low Streets knows what a cloud is. The legs are older than anyone can remember, and floating is understood only as being swept away and dying. Nimbo is not hiding a dream. He has never suspected one. The audience understands what he is long before he does, and that dramatic irony runs through the whole film.

| Beat | Time | Shot |
| --- | --- | --- |
| Opening image: a blank sky nobody looks at | 0:00 | Shot 1 |
| World rules: a funeral for a cloud the wind took | 0:13 | Shots 5 to 8 |
| Inciting incident: his legs seize, out of oil | 1:04 | Shot 19 |
| Plot Point 1: he takes Luma's hand | 1:36 | Shot 27 |
| Midpoint: he discovers lightness, then the storm appears | 3:14 | Shots 41 to 42 |
| All is lost: Luma is slipping away | 4:59 | Shot 59 |
| Plot Point 2: he chooses to unbuckle, a leap of trust in Luma's world | 5:08 | Shot 60 |
| Climax: he lets go, saves Luma, is swept away | 5:14 | Shots 61 to 65 |
| Resolution: the sky revealed, loop to the opening | 5:48 | Shots 66 to 77 |

**Proportions:** Act 1 1:48 (26%), Act 2 3:20 (48%), Act 3 1:52 (27%).

**Plants and payoffs**

| Plant | Payoff |
| --- | --- |
| The blank sky nobody looks at (Shot 1) | The sky revealed and the framing repeated, now alive (Shots 70 and 77) |
| The paper that rises while the camera refuses to follow (Shot 4) | The camera finally follows him up (Shot 66) |
| The funeral: mourners with bowed heads around empty brass legs, a knitted scarf draped on the knee, nobody looking up (Shots 5 to 8) | A legless cloud in the sky wears the same scarf, alive, laughing and waving (Shot 72) |
| Nobody looks up, even to grieve (Shots 5 to 7) | The town finally looks up (Shots 73 and 75) and Luma waves at the sky (Shot 76) |
| Empty brass legs left behind (Shots 5 and 6) | Nimbo's own legs lie empty on the stones (Shot 62), and Luma lays the vial beside them (Shot 76) |
| The legless cloud with her empty cup (Shot 13) | Luma heals her (Shot 34) and the cup fills with golden rain (Shot 74) |
| Oil as currency, counted drop by drop (Shots 6, 7 and 9 to 12) | The sky's rain is free, and the Vendor feels it (Shot 75) |
| Luma's glowing palm (Shot 26) | It fails as the storm pulls at her (Shot 45) |
| The inch he rises on the rooftop, his one clue that lightness exists (Shot 40) | The leap of trust at the climax (Shots 60 to 63) |
| The ribboned vial Nimbo gives Luma (Shot 35) | She sets it beside his empty legs at the end (Shot 76) |

---

# ACT 1: THE WEIGHT

*Setup. The grey world and its rules, told through a funeral. Nimbo's absolute fear of the sky. His legs fail and a stranger changes his path. (0:00 to 1:48)*

## Scene 1: The Low Streets *(0:00 to 0:26)*

**Summary:** The opening image. A world built to hold on, with its rules told by a funeral and nothing else. We meet Nimbo, who only wants to get through the day oiled, in order and unnoticed.\
**Append to every prompt in this scene:** Grade: desaturated slate grey-green, cold blue shadows, amber lamp glow, soft overcast light. The knitted scarf is the only saturated color in the scene, keep it coral and mustard.\
**Sound (added in post):** Low drone, slow tentative pizzicato, leg clanks and hisses, faint wind hum. One muted bell toll at the funeral.

**Shot 1: The blank sky** | 3s, generate at 4s and trim | Refs: none

> A blank white-grey overcast sky fills the whole frame, a few thin wisps of mist drifting very slowly across it. Camera: fixed, pointing straight up, with an almost imperceptible slow push-in. Flat, bright, empty, slightly menacing.

*Edit:* Wind hum fades in. This frame is reused as the reference for the final shot.

**Shot 2: Down to the street** | 3s, generate at 4s and trim | Refs: @Image6

> The pale sky, then the view moves slowly downward past wet iron rooftops to a narrow dark stone street with chains hung along every wall, ropes knotted around lampposts and ankle-high mist. Camera: one slow smooth pan downward, nothing else moves. Quiet, heavy mood.

*Edit:* Start on the last frame of Shot 1.

**Shot 3: The chained street** | 3s, generate at 4s and trim | Refs: @Image6

> Three small cloud characters in dusty grey and cream shuffle slowly toward the camera on rusty brass piston legs through low mist, each stepping carefully from one painted white circle on the ground to the next, heads down, steam puffing from their knees. Camera: slow smooth pull-out, backward, wide shot. Weary, cautious mood.

**Shot 4: The freeze** | 4s | Refs: @Image6

> High-angle wide shot of the chained street. Three small cloud characters, each standing on a painted white circle beside a chain, stop at once, grab the chain with both stubby arms and squeeze their eyes shut. A gust ripples the mist and a single sheet of paper lifts off the ground and rises out of the top of the frame. Camera: fixed, does not follow the paper. Tense stillness.

*Edit:* Add a siren wail in post just before the freeze. Cut as the paper leaves frame. The gust that scared everyone leads straight into what the gust costs.

**Shot 5: The funeral** | 4s | Refs: @Image10, @Image6

> Four small cloud characters in dusty grey and cream stand in a half circle on painted white circles, heads bowed low, in front of a pair of empty rusty brass piston legs standing upright on a small stone plinth, the leather straps hanging open and one torn. A tiny knitted scarf in coral and mustard stripes is draped over one brass knee. Nobody looks up. Camera: wide shot at street level with a very slow push-in. Hushed, solemn mood.

*Edit:* Bell toll. This is the whole rulebook in one frame: being swept away means death, the legs are what keep you alive, and nobody looks up, even to grieve. Leave the straps open or torn, so the town reads the wind's violence and the audience may later read something else.

**Shot 6: The offering** | 3s, generate at 4s and trim | Refs: @Image10

> A small cloud character in dusty grey on brass legs steps forward from a painted white circle, tips a tiny oil can with both stubby arms and a single golden drop falls onto the foot of the empty brass legs, then steps back, head still bowed. Camera: fixed medium shot at knee height. Reverent mood.

*Edit:* Oil is sacred. Each mourner gives one drop.

**Shot 7: Nimbo at the edge** | 3s, generate at 4s and trim | Refs: @Image1

> Nimbo, a small round grey-white cloud character with big glossy dark eyes, rosy cheeks and brass piston legs, stands very upright on the last painted white circle at the back of the mourners, eyes fixed on the stones, arms pressed to his sides. He tips a tiny oil can over his own brass knee and a single golden drop falls, then nods once, serious and precise. Camera: fixed medium shot, eye level.

*Edit:* Introduce Nimbo as a rule-follower who counts every drop. That drop is the last in his can, which is why he needs the stall in the next scene.

**Shot 8: The scarf** | 3s, generate at 4s and trim | Refs: @Image10

> Close-up on the tiny knitted coral and mustard scarf draped over the brass knee of the empty legs. A golden drop of oil slides down the metal beside it and a soft gust stirs the scarf's fringe. Camera: fixed close-up. Quiet, sad mood.

*Edit:* PLANT. Hold the scarf clearly in frame. It returns alive in Shot 72.

---

## Scene 2: The Price of a Drop *(0:26 to 0:56)*

**Summary:** Oil is the world's currency. Nimbo has just given his last drop at the funeral and cannot afford much more, and he cannot look at the sky.\
**Append to every prompt in this scene:** Grade: amber lamplight against cold blue, golden oil is the warmest color in frame, blown-out white sky in the alley.\
**Sound (added in post):** Sparse celesta over vial clinks. A stumble on a wrong note at the legless cloud. High thin violin and rising wind in the alley.

**Shot 9: The stall** | 4s | Refs: @Image6

> A cramped dark wooden market stall with shelves of tiny glass vials, each holding one glowing golden drop, warm amber light against the cold blue street. Two small cloud characters wait in line. Camera: slow push-in toward the glowing vials. Precious, fragile mood.

**Shot 10: The Vendor** | 3s, generate at 4s and trim | Refs: @Image4

> The Vendor, a slightly larger stern grey cloud character with a brass goggle over one eye, stands behind a counter with arms crossed, looking down. He glances at a tiny brass scale, frowns, softens, then frowns again. Camera: fixed medium close-up, low angle.

**Shot 11: The offer** | 5s | Refs: @Image1, @Image4

> Over-the-shoulder view from behind Nimbo at a counter. Nimbo sets a brass cog, a button and a bent spoon on the counter. The Vendor looks at the small pile, slowly shakes his head, then shrugs. Nimbo looks up with huge hopeful eyes and a trembling lower lip. Camera: fixed medium two-shot.

**Shot 12: One vial** | 4s | Refs: @Image1, @Image4

> The Vendor sighs, rolls his eyes and slides one tiny glowing vial across the counter. Nimbo catches it in both stubby arms, hugs it to his chest and bows repeatedly in thanks, eyes shining. Camera: fixed medium two-shot, same framing as the previous shot.

**Shot 13: The legless cloud** | 5s | Refs: @Image5, @Image1

> A small cream cloud character with stiff rusted stumps instead of legs sits in a gutter corner holding an empty tin cup. Her eyes follow Nimbo's vial with longing as he passes, stops, looks at her, then lowers his eyes and walks on. Camera: slow tracking sideways at low angle, drifting past Nimbo to reveal her.

*Edit:* Sound: the celesta hits a wrong note as he looks away.

**Shot 14: The gap** | 3s, generate at 4s and trim | Refs: @Image1

> A narrow stone alley ends in a bright slice of blank white sky. Nimbo enters from the left, small against the tall walls, clanking toward the bright gap. Camera: fixed, symmetrical wide shot centered on the gap. Rising dread.

**Shot 15: The flinch** | 3s, generate at 4s and trim | Refs: @Image1

> Close-up on Nimbo's face as he glances up. His big glossy eyes fill with white sky, his pupils shrink, his cheeks sink and his mouth trembles. Camera: fixed close-up with a very slow push-in.

*Edit:* Cut straight from this to the next shot.

**Shot 16: Scuttling away** | 3s, generate at 4s and trim | Refs: @Image1

> Nimbo squeezes his eyes shut, hugs himself and scuttles quickly forward on his brass legs, steam puffing from his knees, leaving the bright gap behind. Camera: fixed wide shot, same framing as the alley shot.

*Edit:* Footstep rhythm speeds up like a racing heartbeat.

---

## Scene 3: The Causeway *(0:56 to 1:22)*

**Summary:** The inciting incident. Out of oil, his legs seize on an open bridge as the wind rises.\
**Append to every prompt in this scene:** Grade: sickly yellow-grey sunset, cold deep shadows, wind blowing mist.\
**Sound (added in post):** Trembling high strings. Nimbo's leg rhythm turns uneven.

**Shot 17: The bridge** | 4s | Refs: @Image7

> Aerial view of a long iron causeway crossing a vast open void at sunset, a few tiny cloud characters scurrying across it, mist blowing through the railings. Camera: slow aerial descent toward the bridge. Uneasy mood.

**Shot 18: Crossing** | 4s | Refs: @Image1, @Image7

> Nimbo walks along the iron bridge toward the camera on his brass legs, eyes locked on his feet, small puffs of steam rising from his shoulders. Camera: smooth tracking shot moving backward in front of him, medium shot.

**Shot 19: The stutter** | 3s, generate at 4s and trim | Refs: @Image1

> Close-up of Nimbo's left brass leg mid-step. The piston hitches, steam spits from the knee joint, the leg locks and his body jerks to a stop. Camera: fixed low angle with a slight handheld sway.

*Edit:* INCITING INCIDENT. Add a grinding shriek in post.

**Shot 20: Empty** | 4s | Refs: @Image1

> Nimbo holds up a tiny empty glass vial and shakes it upside down. Nothing falls. His eyes widen, his lower lip wobbles and a tear gathers. Camera: fixed medium close-up.

**Shot 21: The wind builds** | 4s | Refs: @Image7, @Image1

> Wide shot of the causeway as grey clouds ripple on the horizon and the wind picks up. Two small cloud characters on brass legs sprint past Nimbo, who stands frozen mid-frame. Camera: fixed wide shot.

*Edit:* Siren far away, added in post.

**Shot 22: Holding on** | 4s | Refs: @Image1

> Nimbo throws both stubby arms around a railing post, one brass leg dragging stiffly. Small wisps of his fluffy body peel upward from his head and shoulders in the wind. He squeezes his eyes shut. Camera: fixed low-angle medium shot.

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

> Luma, a pearl-white cloud character with a faint lilac shimmer, a wispy cowlick and no legs, tumbles slowly off Nimbo's back, bounces off the railing and wobbles in the air, upside down for a moment, grinning widely and utterly unbothered. She gives a big cheerful wave. Nimbo, rigid, stares at her with huge horrified eyes and his mouth open, as if watching something fatal. Camera: fixed medium shot, focus shifts from Nimbo to Luma.

*Edit:* Luma is amused by the wind that terrifies everyone else. For Nimbo this is incomprehensible: a cloud doing the one thing his world treats as fatal, and laughing. He has never seen it before and does not understand it.

**Shot 26: The touch** | 5s | Refs: @Image1, @Image3

> Luma drifts down with a playful bounce and presses her stubby palm onto Nimbo's stuck brass knee, as if playing a game. A soft lilac and gold glow spreads from her palm over the metal, the piston shudders and the leg bends, and a soft wisp of Nimbo's fluff lifts from his shoulder. Nimbo stares at the knee, mouth open, not noticing the wisp. Camera: fixed medium close-up on the knee and both faces.

*Edit:* Music box theme enters in full. Hint only: her touch does not so much fix the metal as remind a cloud what it is. Never explain it.

**Shot 27: Taking her hand** | 5s | Refs: @Image1, @Image3

> Luma holds out her palm to Nimbo with a big bouncy grin. He looks at her hand, glances up at the sky, then back at her, hesitates, and slowly takes it with both stubby arms. Camera: fixed medium shot with a slight push-in.

*Edit:* PLOT POINT 1. Nimbo makes a choice.

**Shot 28: Crossing together** | 7s | Refs: @Image1, @Image3, @Image7

> Nimbo crosses the causeway gripping Luma's hand with both stubby arms, stepping stiffly on his brass legs, while Luma happily lets a gust lift her like a balloon on a string, giggling, her mist tail streaming. Nimbo tugs her back down with wide eyes. Camera: smooth tracking shot from the side, medium wide.

*Edit:* Dissolve to Scene 5 in post.

---

# ACT 2: THE LIGHTNESS

*Confrontation. Luma changes Nimbo's world, friendship becomes love, then the storm begins to call and everything he built to stay safe turns against him. (1:48 to 5:08)*

## Scene 5: Things Get Lighter *(1:48 to 2:54)*

**Summary:** Fun and games. Friendship grows into love as colors warm and Nimbo's legs need less oil.\
**Append to every prompt in this scene:** Grade: teal and honey, soft warm morning light, glowing mist, getting warmer with each shot.\
**Sound (added in post):** Luma's theme grows into a playful arrangement with pizzicato and glockenspiel, Nimbo's leg rhythm as percussion, soft wordless giggles.

**Shot 29: The lamppost** | 6s | Refs: @Image3, @Image1, @Image6

> Luma drifts slowly into an iron lamppost, bounces off, spins once, gives the post a tiny apologetic bow and a cheerful wave. Behind her Nimbo stands rigid on a painted white circle, watching in worry. Camera: fixed medium shot. Gentle comedy.

**Shot 30: Nimbo laughs** | 4s | Refs: @Image1

> Close-up of Nimbo trying to keep a stern, rigid face with lips pressed tight, then cracking and bursting into a squeaky silent laugh, eyes squeezed into happy arcs, cheeks glowing pink. Camera: fixed close-up.

*Edit:* His first crack. Warm music begins.

**Shot 31: Morning routine** | 9s | Refs: @Image1, @Image3

> Luma hums and rests her glowing palm on Nimbo's brass knee, wiggling her mist tail. Nimbo stands stiff with his arms pressed to his sides, then loosens a little as his leg bends smoothly, and gives a small shy bounce. Camera: fixed close-up on the knee, Luma's palm and Nimbo's face.

*Edit:* Generate three variants (dawn, noon, evening light) and cut them as three beats of about 3 seconds. Nimbo is a little looser in each.

**Shot 32: Siren surfing** | 8s | Refs: @Image1, @Image3, @Image6

> A siren sounds. Two small cloud characters in the background freeze, gripping chains with eyes shut. Nimbo grips a chain with one stubby arm. A gust lifts Luma like a kite, her arms spread, giggling, while Nimbo holds on to her wispy tail with his other arm, eyes wide in panic. Camera: fixed medium wide shot.

*Edit:* Luma treats the siren like a game.

**Shot 33: Careless with oil** | 6s | Refs: @Image4, @Image3, @Image1

> At the oil stall, Luma floats up to a shelf and happily pats a glowing vial, which rolls toward the edge. Nimbo dives and catches it just in time, hugging it to his chest, eyes wide. Luma claps her stubby arms, delighted. The Vendor stares in alarm. Camera: fixed medium shot.

*Edit:* She does not know what oil is worth.

**Shot 34: Healing** | 8s | Refs: @Image5, @Image3, @Image1

> In the gutter, Luma floats beside the small cloud with rusted stumps and, humming cheerfully, presses her glowing palm onto them as if it were nothing. A soft glow spreads, the metal creaks and the stumps bend into working legs. The small cloud gasps, eyes wide and shining. Nimbo watches from the background, awestruck. Camera: slow push-in.

**Shot 35: The gift** | 6s | Refs: @Image1, @Image3

> Nimbo holds out a small glowing vial tied with a scrap of ribbon. Luma looks at it, then at his face, then hugs it to her chest like treasure, a tear and a smile. Camera: fixed medium shot with a slow push-in.

**Shot 36: Twirl** | 9s | Refs: @Image1, @Image3

> Luma pulls Nimbo into a twirl by both hands. Nimbo is stiff and stumbling at first, then loosens up and spins freely, his brass legs clicking in rhythm, glowing mist swirling around them. Both laugh silently. Camera: slow orbit around them, medium shot.

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

> Nimbo takes Luma's stubby hands. She gently draws him forward. His brass legs tilt and his feet lift one inch off the tiles. His eyes go wide in pure shock, his mouth falls open and he looks down at the gap beneath his feet. Camera: fixed medium shot, low angle.

**Shot 41: He floats** | 9s | Refs: @Image1, @Image3

> In slow motion, Nimbo rises a few inches above the rooftop with his heavy brass legs dangling, Luma beaming below. He looks down at his dangling legs in astonishment, then up at the starry sky with the stars reflected in his glossy eyes, and wonder spreads across his face until a wide shy smile blooms. Camera: slow push-in, low angle.

*Edit:* MIDPOINT. A real discovery: he never suspected he could float. Shock and wonder first, fear second. This inch is his one clue that lightness exists. Luma's theme swells into its warmest chord.

**Shot 42: The flash** | 6s | Refs: @Image8

> Extreme wide shot of the dark horizon. Deep inside a distant bank of black cloud, a flicker of white lightning lights it from within. Camera: fixed, locked off.

*Edit:* Delayed low rumble in post.

**Shot 43: He sinks** | 6s | Refs: @Image1, @Image3

> Nimbo's smile drops, his eyes dart to the horizon in sudden dread and he sinks back down, brass feet thudding onto the tiles. Beside him Luma turns her head toward the storm and tiny sparks glitter along her cowlick. Camera: fixed medium two-shot.

*Edit:* The lullaby breaks on a discordant note.

**Shot 44: Hand in hand** | 8s | Refs: @Image1, @Image3

> Nimbo and Luma sit close together on the rooftop, hands joined, watching distant lightning flicker. Nimbo, now relaxed against her shoulder, looks at Luma with worry, and Luma, as always, smiles and shrugs it off. Camera: slow push-in, medium shot from behind and to the side.

*Edit:* Fade to black in post.

---

## Scene 7: The Storm Calls *(3:43 to 4:13)*

**Summary:** The storm pulls at Luma, her power weakens and Nimbo's legs begin to fail again. He tries to protect her.\
**Append to every prompt in this scene:** Grade: cold indigo night, pulses of white on the horizon every few seconds.\
**Sound (added in post):** Low ominous drone, distant thunder, Luma's theme fragmenting.

**Shot 45: The glow fails** | 6s | Refs: @Image3, @Image1

> Luma presses her palm to Nimbo's brass knee. The soft glow flickers, dims and goes out. Nimbo's leg shudders and lags and he looks at her in alarm. Luma looks at her own palm, tilts her head, then shrugs with a cheerful smile. Camera: fixed medium close-up.

**Shot 46: Sleepwalking** | 8s | Refs: @Image3, @Image1, @Image6

> Night. Luma, eyes closed and smiling, drifts out of Nimbo's doorway toward the dark horizon like a kite on a string. Nimbo lunges, catches the end of her wispy tail and hauls her back. She wakes, blinks, sees his panicked face and giggles, patting his cheek as if nothing happened. Camera: fixed high-angle wide shot.

**Shot 47: The rope** | 7s | Refs: @Image1, @Image3

> Nimbo ties a rope between his wrist and Luma's, pulling the knot tight, checking it, then checking it again. Luma, delighted, wiggles her wrist to bounce the rope like a toy leash. Nimbo, still worried, stares at her. Camera: fixed medium two-shot with a slow push-in.

**Shot 48: Doors bolted** | 3s, generate at 4s and trim | Refs: @Image6

> At night, a small cloud character on brass legs drags a heavy chain across a doorway as thunder rolls. Camera: fixed medium shot.

*Edit:* Siren wails continuously from here.

**Shot 49: The Vendor ties down** | 3s, generate at 4s and trim | Refs: @Image4

> The Vendor hurries to tie ropes over his shelves of glowing vials, his goggle flashing with distant lightning. Camera: fixed medium shot.

**Shot 50: Cup in the doorway** | 3s, generate at 4s and trim | Refs: @Image5

> The healed small cloud drags her tin cup into a stone doorway on her newly working legs and looks up nervously at the lightning. Camera: fixed medium shot.

---

## Scene 8: The Storm *(4:13 to 5:08)*

**Summary:** All is lost. The rope snaps, the legs die and Luma is torn away. The darkest hour.\
**Append to every prompt in this scene:** Grade: bruised indigo and violet, black clouds, white lightning flashes, heavy rain.\
**Sound (added in post):** Full orchestral storm, timpani and brass stabs, screaming siren, roaring wind.

**Shot 51: The wall of black** | 7s | Refs: @Image6

> Extreme wide, low angle. A colossal black thundercloud rolls over the grey city, lightning forking inside it, its shadow swallowing the streets. Camera: slow pull-out. Terrifying scale.

**Shot 52: Chaos on the ground** | 6s | Refs: @Image6

> Heavy rain and wind. Three small cloud characters cling to chains and lampposts, brass legs scraping the stones, eyes squeezed shut, while debris and lantern glass fly past. Camera: handheld with moderate shake, medium wide.

*Edit:* Keep the characters as dark silhouettes in rain.

**Shot 53: The tower** | 7s | Refs: @Image1, @Image3

> At the base of an iron signal tower, Nimbo grips an iron beam with wide terrified eyes while a rope runs from his wrist to Luma, who streams sideways in the wind toward the storm with her arms spread as if flying, giggling, lightning crackling inside her body. Camera: fixed wide shot with a slight handheld sway.

**Shot 54: The rope snaps** | 4s | Refs: none

> Extreme close-up of a fraying rope under tension. Strands snap one by one and the rope breaks apart. Camera: fixed.

**Shot 55: Torn away** | 8s | Refs: @Image1, @Image3

> Luma is lifted off her feet toward the sky, giggling and waving at the clouds. Nimbo lunges, catches her hand with both stubby arms and is dragged off the ground, his brass legs scraping the stones in sparks. Camera: handheld with moderate shake, medium shot.

**Shot 56: The valve bursts** | 4s | Refs: @Image1

> Close-up on Nimbo's right brass leg. A valve bursts and sprays black oil, the piston jams and the leg collapses. Camera: fixed close-up.

**Shot 57: Stuck** | 5s | Refs: @Image1, @Image3

> Both of Nimbo's brass legs seize and jam their feet between the wet stones, a dead weight pinning him to the ground, as he clings to an iron beam with one stubby arm and to Luma's hand with the other. Luma dangles from his grip like a flag in the wind, grinning and kicking her mist tail, while Nimbo strains. She is slipping. Camera: fixed low-angle medium shot.

**Shot 58: Nobody helps** | 5s | Refs: @Image6, @Image4

> High-angle wide shot in heavy rain. Dark silhouettes of small cloud characters clutch their own chains with eyes shut. In the foreground the Vendor looks across the street at Nimbo and Luma, hesitates, then turns his face away. Camera: fixed.

**Shot 59: All is lost** | 9s | Refs: @Image1, @Image3

> Close-up on Luma, her face lit by lightning, her fingers slipping from his. She gives Nimbo a big warm grin and a cheerful wave with her free arm, as if this is all a game. Nimbo shakes his head with tears in his eyes, glances down at his dead legs, then back at her. Camera: slow push-in, close two-shot.

*Edit:* ALL IS LOST. Luma never stops smiling. Nimbo carries all the fear.

---

# ACT 3: THE SKY

*Resolution. Nimbo chooses. He lets go of everything he built to stay safe, saves Luma and is carried into a world he never knew existed. (5:08 to 7:00)*

## Scene 9: The Letting Go *(5:08 to 5:48)*

**Summary:** Plot Point 2 and the climax. Nimbo makes his active choice. He has never imagined floating, so he is not choosing freedom. The dead legs pin him to the stones and keep him from reaching Luma, and he makes a leap of trust in her world.\
**Append to every prompt in this scene:** Grade: violet strobing storm light, then one warm gold flash at the moment of release.\
**Sound (added in post):** The score builds, then drops out for two seconds as he unbuckles. Only a heartbeat and four clicks.

**Shot 60: The choice** | 6s | Refs: @Image1

> Extreme close-up on Nimbo's eyes with the storm reflected in them. His expression changes from terror to a quiet, resolute calm, the look of someone deciding to trust. Camera: fixed, very slow push-in.

*Edit:* PLOT POINT 2. Nimbo does it only for Luma. A real sacrifice, not a wish coming true.

**Shot 61: The buckles** | 6s | Refs: @Image1

> Medium shot. Nimbo looks down and with his stubby arms undoes the leather buckles on his brass legs one after another, each buckle popping open. Camera: fixed medium shot, low angle.

*Edit:* Add four click sounds in post and cut the music.

**Shot 62: The legs fall** | 6s | Refs: @Image1

> High-angle wide shot looking straight down. Two brass legs fall away and clatter onto the wet stones, small and ugly, then lie still. Camera: fixed, high angle. Total stillness.

*Edit:* Hold the silence for one beat.

**Shot 63: Nimbo lifts** | 8s | Refs: @Image2

> In slow motion, Nimbo, now without legs, rises softly from the ground, his round fluffy body stretching and loosening at the edges. His eyes widen in wonder as a warm golden flash lights his face. Camera: fixed low-angle close-up.

*Edit:* One sustained string note enters. Hint only: the golden flash echoes the glow of Luma's palm from Shot 26.

**Shot 64: The shove** | 6s | Refs: @Image2, @Image3

> Nimbo wraps both stubby arms around Luma and pushes her down into the sheltered side of the tower, where she clings to the iron with a startled giggle. He gives her a small, sure smile. Camera: fixed medium shot with a slight handheld sway.

**Shot 65: The wind takes him** | 8s | Refs: @Image2, @Image3

> A huge gust rips through the street. Nimbo lets go and rises, spinning, a small round shape against the lightning. Luma stretches her arm after him and her hand falls short, and her smile falls for the first time. Camera: low angle, slow pan upward following him.

*Edit:* Luma's theme breaks into one sustained note. This is the only moment Luma is not smiling.

---

## Scene 10: The Ascent and the Sky *(5:48 to 6:31)*

**Summary:** Nimbo faces what he feared most and finds a world he never knew existed. The camera finally follows what it refused to follow in Shot 4.\
**Append to every prompt in this scene:** Grade: lightning and black, brightening to dawn gold, then full saturation: liquid gold, rose, pearl and aquamarine.\
**Sound (added in post):** Orchestral swell, wind thinning, then a wordless choir and strings resolve Luma's theme for the first time. No mechanical sound at all.

**Shot 66: The city shrinks** | 7s | Refs: @Image2

> Aerial view looking down from above Nimbo as he rises. The city shrinks beneath: rooftops become toys, chains become threads, the signal tower becomes a pin, tiny silhouettes look up. Camera: slow aerial pull-out.

*Edit:* This is the camera following the rising paper from Shot 4.

**Shot 67: Tumbling** | 4s | Refs: @Image2

> Nimbo tumbles through rain and lightning with eyes squeezed shut and arms hugging his body, bouncing off a gust and spinning the other way. Camera: handheld with moderate shake.

**Shot 68: Eyes open** | 4s | Refs: @Image2

> Extreme close-up on Nimbo's closed eyes as violet light turns to gold across his face. His lids flutter and open. Camera: fixed close-up.

**Shot 69: Breaking through** | 4s | Refs: @Image2

> Low angle looking up. Nimbo bursts out of the top of the storm into blazing golden light with a soft lens flare, the storm becoming a dark floor below him. Camera: fixed, low angle.

**Shot 70: The reveal** | 10s | Refs: @Image2, @Image9

> A vast golden sky. Enormous glowing cloud islands drift in slow orbits, rivers of mist pour between them, colossal whales of vapor glide through the haze, and many small legless cloud characters drift in loose clusters trailing light. Tiny Nimbo hangs in the foreground with arms spread. No chains, no ropes. Camera: slow aerial pull-out revealing the scale.

*Edit:* The choir enters and Luma's theme resolves.

**Shot 71: Nimbo's face** | 8s | Refs: @Image2

> Close-up of Nimbo slowly rotating in the air, mouth open, eyes full of golden light, cheeks flushing pink. A shy smile grows wide as glittering tears spill out and fall away as soft rain. Camera: slow orbit, close-up.

**Shot 72: Sky friends** | 6s | Refs: @Image2, @Image11

> Three small legless cloud characters drift over and tap Nimbo's arm curiously. The one in front wears a tiny knitted scarf in coral and mustard stripes, laughs silently and waves at him with a stubby arm. Nimbo waves back, puzzled and delighted, and spins. Camera: fixed medium shot, the scarf in clear focus.

*Edit:* PAYOFF. The scarf from Shot 8: the cloud the town mourned is alive and happy. Nimbo never understands who it is, but the audience does. Everyone below has been mourning clouds who are fine.

---

## Scene 11: The Rain *(6:31 to 7:00)*

**Summary:** Resolution. The world below feels what he found and, for the first time, looks up. The ending loops back to the opening image.\
**Append to every prompt in this scene:** Grade: the storm thins, golden light falls across grey wet streets for the first time.\
**Sound (added in post):** Gentle wind, the choir fades to a solo glass harmonica carrying Luma's theme.

**Shot 73: Rain on the city** | 5s | Refs: @Image6

> High-angle wide shot of the grey wet city as the storm breaks apart and soft glittering golden raindrops fall through a shaft of light onto the streets, a few small cloud characters on the painted circles lifting their faces to the rain. Camera: fixed with a slow push-in.

**Shot 74: The cup fills** | 4s | Refs: @Image5

> The small cloud with the healed legs holds out her tin cup and it slowly fills with glittering golden drops. She looks at it in wonder. Camera: fixed close-up on the cup and her face.

*Edit:* Payoff: the empty cup from Shot 13.

**Shot 75: The Vendor looks up** | 4s | Refs: @Image4

> A glittering drop lands on the Vendor's brass goggle. He slowly tilts his head up to the sky, his stern face softening. Camera: fixed medium close-up.

*Edit:* Payoff: the rain is free. The Vendor is the first of the town to look up on purpose.

**Shot 76: Luma and the offering** | 8s | Refs: @Image3, @Image10

> Luma, soaked and shivering, stands at the base of the iron signal tower beside two empty brass legs lying on the wet stones. She sets the ribboned vial gently down against one of them, the way the mourners did, then lifts her face to the sky, a radiant smile breaking out, and waves up at it like greeting an old friend. Camera: fixed medium close-up with a slow push-in.

*Edit:* Payoff: the funeral from Shots 5 to 8 turned inside out. She gives the offering, but she looks up, smiling, because she knows where he is. Her smile returns. If the model merges the two actions, generate the vial and the wave as two takes and cut them together.

**Shot 77: The final shot** | 8s | Refs: @Image9

> Extreme wide shot looking straight up at the sky, the same framing as the opening shot, but now the sky is alive with golden light and glowing wisps of cloud, and a tiny round cloud figure floats far above with arms spread. Camera: fixed, locked off, with a very slow push-in.

*Edit:* Use the first frame of Shot 1 as the framing reference. Luma's theme resolves with the full choir. Slow fade to white in post, then the hand-drawn title NIMBO.

---

**END**