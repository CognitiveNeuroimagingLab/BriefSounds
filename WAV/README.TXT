Neuroscan Sound Conversion Notes.

August 11, 1995
Charles Brown

WAV.ZIP and WAV(SCL).ZIP contain sound files converted from 16-bit
signed stereo SND (Neuroscan) format to 8-bit unsigned mono WAV
(Windows) format.  SND.ZIP contains the original SND files.

These sounds had originally been recorded in 8-bit mono on a Macintosh,
with a playback speed of 11128.5 Hz.  Unfortunately, WAV files are limited
in their playback speeds. These files are set at 11025 Hz BUT THEY HAVE
NOT BEEN ADJUSTED TO ACCOUNT FOR THE TIME DIFFERENCE.

WAV.ZIP contains a straight translation of all our SND files with no attempt
to normalize the dB levels.

In WAV(SCL).ZIP, I attempted (who knows how reasonably) to normalize
the 100 sounds for which we have Neuroscan dB settings.  I did this by
scaling all the sound files by their deviation from the average dB setting for
the entire set (the larger the Neuroscan dB setting, the greater the
amplification required).

I have appended the list of the files with their Neuroscan settings and the
scaling factor tacked onto the end of each line:


File name codes:
A = Animal other than bird (cat. 1)
B = Bird (cat. 2)
H = Human body noises (cat. 3)
M = Music and musical instruments (cat. 4)
N = Noise (cat. 5)
V = Video-game-type noise (cat. 6)
P = Pure tones (list 3, cat. 7)

o = Old Rover sound
n = New sound


                ROVER-2 SOUNDS (*.snd EXTENSION)

No. File name  ms   List   Cat.   Attn(92 db)  Scale
1   AnMosqui   356   1      1       104        0.980
2   AnSheep    343   1      1       103        0.970
3   AoDog      218   1      1       105        0.989
4   AoWolf     388   1      1       114        1.074
5   AnSealio   397   1      1       105        0.989
6   AnHorse2   396   1      1       102        0.961
7   AnCrickt   395   1      1       110        1.036
8   AnCat1     398   1      1       108        1.017
9   AnFrog1    326   2      1       106        0.999
10  AoCow      288   2      1       108        1.017
11  AoPig      214   2      1       110        1.036
12  AnBee      351   2      1       103        0.970
13  AnChimp2   382   2      1       107        1.008
14  AnHorse1   377   2      1       107        1.008
15  AnCat2     395   2      1       103        0.970
16  AnWhale    368   2      1       103        0.970
17  BnOwl1     365   1      2       109        1.027
18  BnPecker   352   1      2       104        0.980
19  BnTurkey   399   1      2       103        0.970
20  BnWhip     397   1      2       102        0.961
21  BnRaven    214   1      2       103        0.970
22  BoBird     217   1      2       106        0.999
23  BoRoyal2   159   1      2       102        0.961
24  BnBobwhi   233   1      2       114        1.074
25  BoCrow     320   2      2       103        0.970
26  BoMallar   203   2      2       101        0.951
27  BnChickn   372   2      2       105        0.989
28  BoGull3    319   2      2       103        0.970
29  BnOwl2     388   2      2       102        0.961
30  BnLimpkn   345   2      2       106        0.999
31  BoCardin   246   2      2       105        0.989
32  BoLoons    351   2      2       105        0.989
33  HnKiss     388   1      3       109        1.027
34  HnCough2   396   1      3       109        1.027
35  HnCough1   389   1      3       106        0.999
36  HnSpeec2   397   1      3       104        0.980
37  HnBelch2   265   1      3       102        0.961
38  HnPrrrr    390   1      3       117        1.102
39  HnNose     340   1      3       109        1.027
40  HnClap     314   1      3       104        0.980
41  HnThroa2   280   2      3       105        0.989
42  HnHiccup   299   2      3       105        0.989
43  HnSneeze   161   2      3       117        1.102
44  HnBurp     228   2      3       105        0.989
45  HnLaugh    399   2      3       105        0.989
46  HnSpeec1   391   2      3       109        1.027
47  HnWhistl   399   2      3       104        0.980
48  HnBaby     392   2      3       102        0.961
49  MoSynth    351   1      4       107        1.008
50  MnTympan   357   1      4       112        1.055
51  MnDrum     358   1      4       113        1.065
52  MnPiccol   395   1      4       106        0.999
53  MnGuitar   397   1      4       104        0.980
54  MnTriang   349   1      4       103        0.970
55  MnFanfar   299   1      4       105        0.989
56  MnNotes    366   1      4       107        1.008
57  MoPiano    395   2      4       103        0.970
58  MnCymbol   312   2      4       106        0.999
59  MoDrum     289   2      4       113        1.065
60  MnBugle    359   2      4       104        0.980
61  MnXylop2   393   2      4       108        1.017
62  MnSynth1   358   2      4       106        0.999
63  MnGlass    276   2      4       103        0.970
64  MnSynth2   345   2      4       105        0.989
65  NoPhone    340   1      5       115        1.083
66  NnTrain    380   1      5       104        0.980
67  NnCoocko   344   1      5       105        0.989
68  NnThud     237   1      5       115        1.083
69  NnCar      390   1      5       104        0.980
70  NnRace     399   1      5       103        0.970
71  NnCork2    319   1      5       105        0.989
72  NnHelico   399   1      5       111        1.046
73  NnWater3   367   2      5       106        0.999
74  NnHorn2    322   2      5       105        0.989
75  NnDentst   382   2      5       111        1.046
76  NnExplos   394   2      5       106        0.999
77  NnKnock    280   2      5       106        0.999
78  NoSaw2     319   2      5       104        0.980
79  NnRattle   289   2      5       107        1.008
80  NnHammer   299   2      5       103        0.970
81  VnGame5    379   1      6       102        0.961
82  VoOoahoo   301   1      6       106        0.999
83  VnWhistl   303   1      6       110        1.036
84  VnGun2     340   1      6       105        0.989
85  VnGame2    240   1      6       104        0.980
86  VoZapdwn   305   1      6       103        0.970
87  VnGadget   397   1      6       109        1.027
88  VnBoing1   396   1      6       103        0.970
89  VoTweee    293   2      6       102        0.961
90  VoAhooa    292   2      6       106        0.999
91  VnPinbal   395   2      6       105        0.989
92  VnGame1    380   2      6       113        1.065
93  VnCartoo   282   2      6       103        0.970
94  VnGame4    368   2      6       103        0.970
95  VnGun3     357   2      6       106        0.999
96  VnGun1     249   2      6       106        0.999
97  Po1000Hz   336   3      7       105        0.989
98  Po700Hz    336   3      7       109        1.027
99  Pn1300Hz   336   3      7       103        0.970
100 Pn400Hz    336   3      7       114        1.074
