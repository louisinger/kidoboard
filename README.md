# Kidoboard

A first keyboard and a first mouse for two-year-olds, played with a grown-up. One file, no build, no account: open `index.html`.

Every key is an animal or a colour. Real photos, real recordings, the name spoken aloud. English and French.

## What a child does

**The keyboard**

1. **Press.** Any press shows an animal, says its name, then plays its call. Cause and effect, one thing at a time.
2. **Point.** "Where is the cow?" Two pictures. The child touches one, or presses any key on its side of the keyboard.
3. **Find.** "Where does the cow live?" Its key lights up on a small on-screen keyboard, at once for a new animal, later and later for a known one.

**The mouse**

1. **Move.** A lamp follows the pointer and wakes animals in the dark. No clicking.
2. **Click.** Big keys hide an animal each.
3. **Drag.** Carry a ball to the basket of its colour.
4. **Choose.** The Point game, answered with the mouse, with more pictures.

## For the grown-up

- **Key size.** Six big keys (the default), twelve, or every key. With big keys, every key of a zone answers as the one animal that lives there, so nobody moves house when the keys shrink.
- **A sitting ends by itself.** After 5, 10 or 15 minutes the app says goodbye between two pictures. Hold Esc or the house button for one second to leave at any time.
- **Your voice.** Record the words yourself; your recording replaces the computer voice.
- **Key stickers.** Print the pictures and stick them on the real keys.
- **Progress** is kept in the browser only.

Self-check: open `index.html#test`.

## Why it works this way

The first version of the redesign was built on intuition. This one was reviewed against published research on how two-year-olds learn. Each choice below names the finding behind it. Ages on the home screen are rough guides drawn from these studies, not norms.

### Played together, and short

- Paediatric guidance for this age is co-use and little of it. The American Academy of Pediatrics discourages solo media use under two and asks parents of 2 to 5 year olds to co-view and keep it to about an hour a day; the WHO says no more than an hour of sedentary screen time at two, and less is better.
  → The home screen says so plainly, and every picture in Press comes with a question for the adult to ask.
- Prompts built into an e-book made parents talk and ask more during shared reading (Troseth et al., 2020).
  → The question under each picture ("What does the cow say?", "Find something red in the room").
- Screen time ends more calmly at a natural stopping point, and when the technology stops by itself; a two-minute warning made things worse (Hiniker et al., 2016).
  → A sitting ends on its own, between two pictures, with no countdown.

### Few words, repeated, named in the clear

- Two-year-olds pick the right picture for a new word easily but have mostly forgotten it five minutes later. What helps is repetition, naming the thing again once it is chosen, and few competing objects (Horst & Samuelson, 2008; Horst, Scott & Pollard, 2010; Axelsson, Churchley & Horst, 2012).
  → Six animals at a time instead of thirty-six. Point starts with three words and adds one only when one is known. Two pictures, not four. When the child is right, the other picture fades and the word is said again.
- The youngest toddlers in a touchscreen study learned a word only when they had to touch the object itself; touching anywhere did not help (Kirkorian, Choi & Pempek, 2016).
  → Point asks for a specific answer. Press, where any key does something, comes first as cause and effect and is not expected to teach words on its own.
- A two-picture "where is the car?" touch task works from 16 months and is a validated measure of comprehension (Friend & Keplinger, 2003, 2008).
  → The format of Point.
- Toddlers learned new words only when the speech was about 10 dB louder than background sound (McMillan & Saffran, 2016).
  → The chime is over before the word starts, the cheer too. Nothing plays under a name. The next press waits until the name has been heard.
- At 21 months children learned words only from infant-directed speech; by 27 months adult-directed speech worked too (Ma et al., 2011).
  → The computer voice is slowed and raised a little, and a parent can record every word in their own voice.
- Children carry what they learn from a picture to the real thing more easily when the picture is a realistic photograph (Ganea, Pickard & DeLoache, 2008).
  → Photos and real recordings, kept from the original app.
- Two-year-olds learn colour words better when the colour comes after the noun, "the ball is red" rather than "the red ball" (Ramscar et al., 2010). Colour words are hard at this age in any case.
  → Colours come late, and are always said after the thing: "The ball is red."

### Less to decode

- Around two and a half, children mostly fail to use a model of a space as a map of the real space; around three they succeed. Photographs are easier than models (DeLoache, 1987, 2000).
  → The on-screen keyboard is a map of the real one, so a two-year-old cannot be expected to read it. It stays for the adult to point at, and for later. For the child: six big zones instead of thirty-six places, and printable stickers that turn "find the place" into "find the same picture".
- Educational apps help when the child is active, not distracted, when the content means something to them and when someone shares it; sounds and animations beside the point pull attention away (Hirsh-Pasek et al., 2015).
  → No confetti, no score, no background music. The only animation is the picture arriving.
- Lift-the-flap features in a first-words book hindered word learning in two-year-olds (Shinskey, 2021).
  → Click, where animals hide under keys, is practice for the hand. It is not counted as word learning.

### The mouse comes later

- There is little research on mouse use before three. Three-year-olds managed a simple cursor-placement task with a mouse, a joystick or a trackball (Strommen et al., 1996); four and five-year-olds point much less accurately than older children and adults (Hourcade et al., 2004).
  → The mouse track is labelled from about three, starts with moving only, and uses very large targets. Levels follow the child both ways: two smooth pages lift the level, a hard page brings it back down.
- Dragging: one study found five to six-year-olds slower and less accurate at dragging than at pointing (Joiner et al., 1998); another found drag-and-drop faster and less error-prone than click-move-click at five to seven (Donker & Reitsma, 2007).
  → Drag accepts both: hold and carry, or click to pick up and click to drop.

### What is not backed by a study

The six-then-twelve key zones, the exact fading of the hint in Find, and the level rules for the mouse are design decisions in the spirit of the findings above. Nobody has tested Kidoboard itself with children.

## Sources

- American Academy of Pediatrics (2016). Media and Young Minds. *Pediatrics*, 138(5). Summary: <https://www.sciencedaily.com/releases/2016/10/161021121843.htm>
- World Health Organization (2019). Guidelines on physical activity, sedentary behaviour and sleep for children under 5 years of age. <https://www.who.int/news/item/24-04-2019-to-grow-up-healthy-children-need-to-sit-less-and-play-more>
- Axelsson, E. L., Churchley, K., & Horst, J. S. (2012). The right thing at the right time: why ostensive naming facilitates word learning. *Frontiers in Psychology*, 3, 88. <https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2012.00088>
- DeLoache, J. S. (1987). Rapid change in the symbolic functioning of very young children. *Science*, 238, 1556–1557.
- DeLoache, J. S. (2000). Dual representation and young children's use of scale models. *Child Development*, 71(2), 329–338. <https://doi.org/10.1111/1467-8624.00148>
- Donker, A., & Reitsma, P. (2007). Young children's ability to use a computer mouse. *Computers & Education*, 48(4), 602–617. <https://research.vu.nl/en/publications/young-childrens-ability-to-use-a-computer-mouse/>
- Friend, M., & Keplinger, M. (2003). An infant-based assessment of early lexicon acquisition. *Behavior Research Methods, Instruments, & Computers*, 35, 302–309. <https://doi.org/10.3758/BF03202556>
- Friend, M., & Keplinger, M. (2008). Reliability and validity of the Computerized Comprehension Task. *Journal of Child Language*, 35(1), 77–98. <https://pmc.ncbi.nlm.nih.gov/articles/PMC5501698>
- Ganea, P. A., Pickard, M. B., & DeLoache, J. S. (2008). Transfer between picture books and the real world by very young children. *Journal of Cognition and Development*, 9(1), 46–66. <https://doi.org/10.1080/15248370701836592>
- Hiniker, A., Suh, H., Cao, S., & Kientz, J. A. (2016). Screen time tantrums: how families manage screen media experiences for toddlers and preschoolers. *CHI 2016*, 648–660. <https://www.washington.edu/news/2016/05/05/two-minute-warnings-make-kids-screen-time-tantrums-worse/>
- Hirsh-Pasek, K., Zosh, J. M., Golinkoff, R. M., Gray, J. H., Robb, M. B., & Kaufman, J. (2015). Putting education in "educational" apps. *Psychological Science in the Public Interest*, 16(1), 3–34. <https://doi.org/10.1177/1529100615569721>
- Horst, J. S., & Samuelson, L. K. (2008). Fast mapping but poor retention by 24-month-old infants. *Infancy*, 13(2), 128–157. <https://doi.org/10.1080/15250000701795598>
- Horst, J. S., Scott, E. J., & Pollard, J. A. (2010). The role of competition in word learning via referent selection. *Developmental Science*, 13(5).
- Hourcade, J. P., Bederson, B. B., Druin, A., & Guimbretière, F. (2004). Differences in pointing task performance between preschool children and adults using mice. *ACM TOCHI*, 11(4), 357–386. <https://doi.org/10.1145/1035575.1035577>
- Joiner, R., Messer, D., Light, P., & Littleton, K. (1998). It is best to point for young children: a comparison of children's pointing and dragging. *Computers in Human Behavior*, 14(3), 513–529.
- Kirkorian, H. L., Choi, K., & Pempek, T. A. (2016). Toddlers' word learning from contingent and noncontingent video on touch screens. *Child Development*, 87(2), 405–413. <https://doi.org/10.1111/cdev.12508>
- Ma, W., Golinkoff, R. M., Houston, D., & Hirsh-Pasek, K. (2011). Word learning in infant- and adult-directed speech. *Language Learning and Development*, 7.
- McMillan, B. T. M., & Saffran, J. R. (2016). Learning in complex environments: the effects of background speech on early word learning. *Child Development*, 87(6), 1841–1855. <https://doi.org/10.1111/cdev.12559>
- Ramscar, M., Yarlett, D., Dye, M., Denny, K., & Thorpe, K. (2010). The effects of feature-label-order and their implications for symbolic learning. *Cognitive Science*, 34(6), 909–957. <https://doi.org/10.1111/j.1551-6709.2009.01092.x>
- Shinskey, J. L. (2021). Lift-the-flap features in "first words" picture books impede word learning in 2-year-olds. *Journal of Educational Psychology*, 113(4), 641–655. <https://doi.org/10.1037/edu0000628>
- Strommen, E. F., Revelle, G. L., Medoff, L. M., & Razavi, S. (1996). Slow and steady wins the race? Three-year-old children and pointing device use. *Behaviour & Information Technology*, 15(1), 57–64.
- Troseth, G. L., Strouse, G. A., Flores, I., Stuckelman, Z. D., & Russo Johnson, C. (2020). An enhanced eBook facilitates parent–child talk during shared reading by families of low socioeconomic status. *Early Childhood Research Quarterly*, 50, 45–58. <https://doi.org/10.1016/j.ecresq.2019.02.009>

Photos and sounds: see [CREDITS.md](CREDITS.md).
