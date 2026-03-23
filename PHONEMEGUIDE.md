## Base OGSD Phoneme guide
the Greek phonemes on this repository are based on X-SAMPA and [CMUSphinx's Phoneset](https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/Greek/) with a few alterations and additions to better represent the graphemes for easy recognizability whilst also be closely realized with the ipa symbols. this compares to [the original SAMPA chart (Web Archived)](https://web.archive.org/web/20250120132641/https://www.phon.ucl.ac.uk/home/sampa/grk-uni.htm), IPA symbols, The CMU Sphinx Dictionary phoneset for Greek, and the VOCALOID & [eSpeak](https://github.com/espeak-ng/espeak-ng/blob/master/dictsource/el_rules) equivalents of X-SAMPA.
If you want to include these phonemes to your voicebank, I recommend you use the "el/" tag.

Base set | original IPA |  original (X)-SAMPA | CMUSphinx | Category | Example
------- | ------- | ------- | ------- | ------- | ------- 
a | a | a | a | vowel | π**α**ς (p**a**s)
e | e | e | e | vowel | π**ε**ς, **αί**τιο (p**e**s, **ai**tio)
i | i | i | i | vowel | **ί**διος, ξ**υ**ρ**ι**σμένο, εαριν**ή**, π**ει**ς, **οι**κία (**i**dios, ks**y**r**i**smeno, ear**i**n**i**, p**ei**s, **oi**kia)
o | o | o | o | vowel | **ο**δ**ό**ς, π**ω**ς (**o**d**o**s, p**o**s)
u | u | u | u | vowel | π**ου** (p**ou**)
y  | ʝ (j) | jj / j\ (j) | j | semivowel | **γ**έρος, **γ**η, κρα**γι**όν, δ**ι**αβάζω (**g**eros, **g**i, kra**gi**on, d**i**abazo)
b | b | b | b | stop | **μπ**ορώ (**b**oro)
d | d | d | d | stop | πέ**ντ**ε (pe**nt**e)
dz | d͡z | dz | [d z] | affricate | **τζ**άμι (**tz**ami)
f | f | f | f | fricative | **φ**εύγω, αυ, ευ (**f**evgo, a**f**, e**f**. the latter two are situational)
g | g | g | g | stop | ό**γκ**ος (o**nk**os)
k | k | k | k | stop | **κ**όμμα (**k**omma)
l | l | l | l | liquid | **λ**ίμα (**l**ima)
m | m | m | m | nasal | **μ**όνος (**m**onos)
n | n | n | n | nasal | **ν**όμος (**n**omos)
p | p | p | p | stop | **π**ήρα (**p**ira)
r | ɾ | 4 / r | r | liquid | **ρ**ήμα (**r**ima)
rr | r | R / rr | r | liquid | ά**ρ**τος (a**r**tos)
s | s | s | s | fricative | **σ**ελίδα, πλάτο**ς** (**s**elida, plato**s**)
t | t | t | t | stop | **τ**είνω (**t**eino)
ts | t͡s | ts | ts | affricate | **τσ**άγια, μα**τς** (**ts**agia, ma**ts**)
v | v | v | v | fricative | **β**άση, αυ, ευ (**v**asi, a**v**, e**v**. the latter two are situational)
x | x | x | h | fricative | **χ**ώμα (**ch**oma)
z | z | z | z | fricative | **ζ**άρη (**z**ari)
D / dh | ð | D | dh | fricative | **δ**έμα (**d**ema)
G / gh | ɣ | G | gh | fricative | **γ**αστρονομική (**g**astronomiki)
Τ / th | θ | T | th | fricative | **θ**έμα (**th**ema)
ng | ŋ | N | ng | allophone nasal | α**γγ**ούρι, ά**γ**χος (a**ng**ouri, a**n**chos)
ks | /ks/ | [k s] | [k s] | cluster | **ξ**έχασε (**ks**echase)
ps | /ps/ | [p s] | [p s] | cluster | **ψ**ήνω (**ps**ino)
kj | kʲ (c) | kj / k' | kj | post-palatalized stop | **κ**αι, σα**κ**ί, σ**κι**άζω (**k**ai, sa**k**i, s**ki**azo. the [kj] phoneme on the training data, doesnt apply to the [e] and [i] vowels)
gj | gʲ (ɟ) | gj / g' | [g i0] |  post-palatalized stop | ά**γγ**ελος, **γκ**ίνια, **γκι**ώνης (an**g**elos, **nk**inia, **nki**onis. the [gj] phoneme on the training data, may sometimes don't apply to the [e] and [i] vowels according to the context of the grapheme)
ll | ʎ | L | l | palatalized liquid | ε**λι**ά (e**li**a)
nj | ɲ | J | n |  palatalized nasal | **νι**ώθω (**ni**otho)
xj | xʲ (ç) | xj / x' | hs | post-palatalized fricative | **χ**έρι, μονα**χ**ή, **χι**όνι, π**οι**ος (**ch**eri, mona**ch**i, **chi**oni, p**oi**os. the [xj] phoneme on the training data, doesnt apply to the [e] and [i] vowels)

### Common global phonemes
DiffSinger | ENUNU / NNSVS / Synthesizer V | IPA | X-SAMPA <sup><sub>(VOCALOID)</sub></sup> | Notes
------- | ------- | ------- | ---------- | -------
SP | sil | n/a | Sil / Asp | silence
AP | br | n/a | Br | breath sounds
SP, AP | pau | n/a | Sil, Br | silence, breaths, and unsung segments in general (when working with ENUNU Training, it is reccomended to use it instead of [br] and [sil] due to recent errors)
cl | cl | ʔ / V.O.T | ? | glottal stop, can be substituted with [q]
vf | vf | ◌̰ | n/a | vocal fry
