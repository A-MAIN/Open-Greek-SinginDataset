## Base OGSD Phoneme guide
the Greek phonemes on this repository are based on X-SAMPA with a few additions and romanizations, however there's also an arpa-like equivalent replacing the certain uppercase phonemes and extras. this compares to [the original SAMPA chart](https://www.phon.ucl.ac.uk/home/sampa/grk-uni.htm), IPA symbols, and VOCALOID equivalents.
if you wnat to include these phonemes to your voicebank, I recommend you use the "el/" tag.

Base set | ARPA-ised set | original IPA |  original (X)-SAMPA | Category | Example
------- | ------- | ------- | ------- | ------- | ------- 
a | a | a | a | vowel | π**α**ς
e | e | e | e | vowel | π**ε**ς, **αί**τιο
i | i | i | i | vowel | **ί**διος, ξ**υ**ρ**ι**σμένο, εαριν**ή**, π**ει**ς, **οι**κία
o | o | o | o | vowel | **ο**δ**ό**ς, π**ω**ς
u | οu | u | u | vowel | π**ου**
y  | y | j ʝ | j, jj / j\ | semivowel | **γ**έρος, **γ**η, κρα**γι**όν, δ**ι**αβάζω
b | b | b | b | stop | **μπ**ορώ
d | d | d | d | stop | πέ**ντ**ε
D | dh | ð | D | fricative | **δ**έμα
dz | dz | d͡z | dz | affricate | **τζ**άμι
f | f | f | f | fricative | **φ**εύγω, αυ, ευ (the latter two are situational)
g | g | g | g | stop | ό**γκ**ος
G | gh | ɣ | G | fricative | **γ**αστρονομική
k | k | k | k | stop | **κ**όμμα
l | l | l | l | liquid | **λ**ίμα
m | m | m | m | nasal | **μ**όνος
n | n | n | n | nasal | **ν**όμος
Ν | ng | ŋ | N | allophone nasal | α**γγ**ούρι
p | p | p | p | stop | **π**ήρα
r | r | ɾ | 4 | liquid | **ρ**ήμα
rr | rr | r |  r | liquid | ά**ρ**τος
s | s | s | s | fricative | **σ**ελίδα, πλάτο**ς**
t | t | t | t | stop | **τ**είνω
Τ | th | θ | T | fricative | **θ**έμα
ts | ts | t͡s | ts | affricate | **τσ**άγια, μα**τς**
v | v | v | v | fricative | **β**άση, αυ, ευ (the latter two are situational)
x | x | x | x | fricative | **χ**ώμα
z | z | z | z | fricative | **ζ**άρη
ks | ks | /ks/ | [k s] | cluster | **ξ**έχασε
ps | ps | /ps/ | [p s] | cluster | **ψ**ήνω
c | ky | c | c | palatalized stop | **κ**αι, σα**κ**ί, σ**κι**άζω (in the arpa-ized set, the [ky] combination doesnt apply to the [e] and [i] vowels)
C | xy | ç | C | palatalized fricative | **χ**έρι, μονα**χ**ή, **χι**όνι  (in the arpa-ized set, the [xy] combination doesnt apply to the [e] and [i] vowels)
gj | gy | ɟ | gj / g', J\ | palatalized stop | ά**γγ**ελος, **γκ**ίνια, **γκι**ώνης
ll | ll | ʎ | L | palatalized liquid | ε**λι**ά
nj | ny | ɲ | J | palatalized nasal | **νι**ώθω (this is only exclusive to the DiffSinger phonemeset as of writing this)

### Global common phonemes
DiffSinger | ENUNU | IPA | X-SAMPA | Notes
------- | ------- | ------- | ---------- | -------
SP | sil | n/a | n/a | silence
AP | br | n/a | n/a | breath sounds
SP, AP | pau | n/a | n/a | silence, breaths, and unsung segments in general (when working with ENUNU Training, it is reccomended to use it instead of [br] and [sil] due to recent errors)
cl  | cl | V.O.T | ? / _} | glottal stop, can be substituted with [q]
vf  | vf | n/a | n/a | vocal fry
