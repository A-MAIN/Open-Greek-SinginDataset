## Base OGSD Phoneme guide
the Greek phonemes on this repository are based on X-SAMPA with a few alterations and additions. this compares to [the original SAMPA chart](https://www.phon.ucl.ac.uk/home/sampa/grk-uni.htm), IPA symbols, and VOCALOID equivalents.
If you want to include these phonemes to your voicebank, I recommend you use the "el/" tag.

Base set | original IPA |  original (X)-SAMPA | Category| Example
------- | ------- | ------- | ------- | ------- 
a | a | a | vowel | π**α**ς
e | e | e | vowel | π**ε**ς, **αί**τιο
i | i | i | vowel | **ί**διος, ξ**υ**ρ**ι**σμένο, εαριν**ή**, π**ει**ς, **οι**κία
o | o | o | vowel | **ο**δ**ό**ς, π**ω**ς
u | u | u | vowel | π**ου**
y  | jʝ | j, jj / j\ | semivowel | **γ**έρος, **γ**η, κρα**γι**όν, δ**ι**αβάζω
b | b | b | stop | **μπ**ορώ
d | d | d | stop | πέ**ντ**ε
dz | d͡z | dz | affricate | **τζ**άμι
f | f | f | fricative | **φ**εύγω, αυ, ευ (the latter two are situational)
g | g | g | stop | ό**γκ**ος
k | k | k | stop | **κ**όμμα
l | l | l | liquid | **λ**ίμα
m | m | m | nasal | **μ**όνος
n | n | n | nasal | **ν**όμος
p | p | p | stop | **π**ήρα
r | ɾ | 4 / r | liquid | **ρ**ήμα
rr | r |  r / rr | liquid | ά**ρ**τος
s | s | s | fricative | **σ**ελίδα, πλάτο**ς**
t | t | t | stop | **τ**είνω
ts | t͡s | ts | affricate | **τσ**άγια, μα**τς**
v | v | v | fricative | **β**άση, αυ, ευ (the latter two are situational)
x | x | x | fricative | **χ**ώμα
z | z | z | fricative | **ζ**άρη
D | ð | D | fricative | **δ**έμα
G | ɣ | G | fricative | **γ**αστρονομική
Ν | ŋ | N | allophone nasal | α**γγ**ούρι, ά**γ**χος
Τ | θ | T | fricative | **θ**έμα
ks | /ks/ | [k s] | cluster | **ξ**έχασε
ps | /ps/ | [p s] | cluster | **ψ**ήνω
kj | c | c | palatalized stop | **κ**αι, σα**κ**ί, σ**κι**άζω (the [kj] phoneme on the training data, doesnt apply to the [e] and [i] vowels)
gj | ɟ | gj / g', J\ | palatalized stop | ά**γγ**ελος, **γκ**ίνια, **γκι**ώνης
ll | ʎ | L | palatalized liquid | ε**λι**ά
nj | ɲ | J | palatalized nasal | **νι**ώθω (this is only exclusive to the DiffSinger phonemeset as of writing this)
xj | ç | C | palatalized fricative | **χ**έρι, μονα**χ**ή, **χι**όνι (the [xj] phoneme on the training data, doesnt apply to the [e] and [i] vowels)

### Global common phonemes
DiffSinger | ENUNU | IPA | X-SAMPA | Notes
------- | ------- | ------- | ---------- | -------
SP | sil | n/a | n/a | silence
AP | br | n/a | n/a | breath sounds
SP, AP | pau | n/a | n/a | silence, breaths, and unsung segments in general (when working with ENUNU Training, it is reccomended to use it instead of [br] and [sil] due to recent errors)
cl | cl | V.O.T | ? / _} | glottal stop, can be substituted with [q]
vf | vf | n/a | n/a | vocal fry
