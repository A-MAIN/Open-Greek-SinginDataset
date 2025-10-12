## Base OGSD Phoneme guide
the Greek phonemes on this repository are based on X-SAMPA and [CMUSphinx's Phoneset](https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/Greek/) with a few alterations and additions to better represent the graphemes for easy recognizability whilst also be closely realized with the ipa symbols. this compares to [the original SAMPA chart](https://www.phon.ucl.ac.uk/home/sampa/grk-uni.htm), IPA symbols, The CMU Sphinx Dictionary phoneset for Greek, and the VOCALOID & [eSpeak](https://github.com/espeak-ng/espeak-ng/blob/master/dictsource/el_rules) equivalents of X-SAMPA.
If you want to include these phonemes to your voicebank, I recommend you use the "el/" tag.

Base set | original IPA |  original (X)-SAMPA | CMUSphinx | Category | Example
------- | ------- | ------- | ------- | ------- | ------- 
a | a | a | a0, a1 | vowel | π**α**ς
e | e | e | e0, e1 | vowel | π**ε**ς, **αί**τιο
i | i | i | i0, i1 | vowel | **ί**διος, ξ**υ**ρ**ι**σμένο, εαριν**ή**, π**ει**ς, **οι**κία
o | o | o | o0, o1 | vowel | **ο**δ**ό**ς, π**ω**ς
u | u | u | u0, u1 | vowel | π**ου**
y  | j ʝ | j, jj / j\ | j | semivowel | **γ**έρος, **γ**η, κρα**γι**όν, δ**ι**αβάζω
b | b | b | b | stop | **μπ**ορώ
d | d | d | d | stop | πέ**ντ**ε
dz | d͡z | dz | [d z] | affricate | **τζ**άμι
f | f | f | f | fricative | **φ**εύγω, αυ, ευ (the latter two are situational)
g | g | g | g | stop | ό**γκ**ος
k | k | k | k | stop | **κ**όμμα
l | l | l | l | liquid | **λ**ίμα
m | m | m | m | nasal | **μ**όνος
n | n | n | m | nasal | **ν**όμος
p | p | p | p | stop | **π**ήρα
r | ɾ | 4 / r | r | liquid | **ρ**ήμα
rr | r | R / rr | r | liquid | ά**ρ**τος
s | s | s | s | fricative | **σ**ελίδα, πλάτο**ς**
t | t | t | t | stop | **τ**είνω
ts | t͡s | ts | ts | affricate | **τσ**άγια, μα**τς**
v | v | v | v | fricative | **β**άση, αυ, ευ (the latter two are situational)
x | x | x | h | fricative | **χ**ώμα
z | z | z | z | fricative | **ζ**άρη
D / dh | ð | D | dh | fricative | **δ**έμα
G / gh | ɣ | G / Q | gh | fricative | **γ**αστρονομική
Ν / ng | ŋ | N | ng | allophone nasal | α**γγ**ούρι, ά**γ**χος
Τ / th | θ | T | th | fricative | **θ**έμα
ks | /ks/ | [k s] | [k s] | cluster | **ξ**έχασε
ps | /ps/ | [p s] | [p s] | cluster | **ψ**ήνω
kj | kʲ / c | kj / k', c | kj | post-palatalized stop | **κ**αι, σα**κ**ί, σ**κι**άζω (the [kj] phoneme on the training data, doesnt apply to the [e] and [i] vowels)
gj | gʲ / ɟ | gj / g', J\ | [g i0] |  post-palatalized stop | ά**γγ**ελος, **γκ**ίνια, **γκι**ώνης (the [gj] phoneme on the training data, may sometimes don't apply to the [e] and [i] vowels according to the context of the grapheme)
ll | ʎ | L / l^ | l | palatalized liquid | ε**λι**ά
nj | ɲ | J / n^ | n |  palatalized nasal | **νι**ώθω
xj | xʲ / ç | xj / x', C | hs | post-palatalized fricative | **χ**έρι, μονα**χ**ή, **χι**όνι (the [xj] phoneme on the training data, doesnt apply to the [e] and [i] vowels)

### Common global phonemes
DiffSinger | ENUNU / NNSVS | IPA | X-SAMPA <sup><sub>(VOCALOID)</sub></sup> | Notes
------- | ------- | ------- | ---------- | -------
SP | sil | n/a | Sil / Asp | silence
AP | br, exh, axh | n/a | Br | breath sounds
SP, AP | pau | n/a | Sil, Br | silence, breaths, and unsung segments in general (when working with ENUNU Training, it is reccomended to use it instead of [br] and [sil] due to recent errors)
cl | cl | ʔ / V.O.T | ? | glottal stop, can be substituted with [q]
vf | vf | ◌̰ | n/a | vocal fry
