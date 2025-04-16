## Base OGSD Phoneme guide
the Greek phonemes on this repository are based on X-SAMPA with a few additions and romanizations, however there's also an arpa-like equivalent replacing the certain uppercase phonemes. this compares to [the original SAMPA chart](https://www.phon.ucl.ac.uk/home/sampa/grk-uni.htm).

Base set | ARPA-ised set |  original SAMPA | Category | Example
------- | ------- | ------- | ------- | ------- 
a | a | a | vowel | α
e | e | e | vowel | ε, αι
i | i | i | vowel | ι, η, υ, ει, οι
o | o | o | vowel | ο, ω
u | οu | u | vowel | ου
b | b | b | stop | μπ
c  | ky | c | palatalized stop | κε, κι, κια, κιο, κιου (in the arpa-ized set, the [k y] combination doesnt apply to the [e] and [i] vowels)
C  | xy | C | palatalized fricative | χε, χι, χια, χιο, χιου (in the arpa-ized set, the [x y] combination doesnt apply to the [e] and [i] vowels)
d | d | d | stop | ντ
D | dh | D | fricative | δ
dz | dz | dz | affricate | τζ
f | f | f | fricative | φ, αυ, ευ (the latter two are situational)
g | g | g | stop | γκ
G | gh | G | fricative | γ
gj | gy | gj / g\ | palatalized stop | γγε, γκι, γκια, γκιο, γκιου
k | k | k | stop | κ
ks | ks | [k s] | cluster | ξ
l | l | l | liquid | λ
ll | ll | L | semivowel | λια, λιου, λιο, λιε
m | m | m | nasal | μ
n | n | n | nasal | ν
Ν | ng | N | allophone nasal | α**γγ**ούρι
p | p | p | stop | π
ps | ps | [p s] | cluster | ψ
r | r | r | liquid | ρ
rr | rr | rr | liquid | ά**ρ**τος
s | s | s | fricative | σ, ς
t | t | t | stop | τ
Τ | th | T | fricative | θ
ts | ts | ts | affricate | τσ, τς
v | v | v | fricative | β, αυ, ευ (the latter two are situational)
x  | x | x | fricative | χ
y  | y | j, jj / j\ | semivowel | γε, γι, για, γιο, γιου 
z  | z | z | fricative | ζ

### Global common phonemes
DiffSinger | ENUNU | X-SAMPA | Notes
------- | ------- | ---------- | -------
SP | sil | n/a | silence
AP | br | n/a | breath sounds
SP, AP | pau | n/a | silence, breaths, and unsung segments in general (when working with ENUNU Training, it is reccomended to use it instead of [br] and [sil] due to recent errors)
cl  | cl | ? / _} | glottal stop
vf  | vf | n/a | vocal fry
