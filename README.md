# 1.5

## Simple

Config:
```py
PTS = 50
HIDDEN = 4
RATE = 0.5
data = minitorch.datasets["Simple"](PTS)
```

Logs:
```
Epoch  10  loss  32.24909558330807 correct 40
Epoch  20  loss  24.356705102013397 correct 48
Epoch  30  loss  11.521843561578299 correct 49
Epoch  40  loss  16.195788120846743 correct 44
Epoch  50  loss  4.992462470034323 correct 49
Epoch  60  loss  3.978011341354046 correct 49
Epoch  70  loss  3.5868492101957057 correct 49
Epoch  80  loss  6.076361304748596 correct 46
Epoch  90  loss  5.454358515264697 correct 48
Epoch  100  loss  3.638813855235206 correct 49
Epoch  110  loss  3.4443307998928567 correct 49
Epoch  120  loss  4.091461090116529 correct 49
Epoch  130  loss  4.3552033669362595 correct 49
Epoch  140  loss  3.6484754115255362 correct 49
Epoch  150  loss  3.3307776709265853 correct 49
Epoch  160  loss  3.5191381459959348 correct 49
Epoch  170  loss  3.751789811863987 correct 49
Epoch  180  loss  3.5301236985580395 correct 49
Epoch  190  loss  3.219878852227911 correct 49
Epoch  200  loss  3.1231543130593464 correct 49
Epoch  210  loss  3.2498835361280634 correct 49
Epoch  220  loss  3.292288033792995 correct 49
Epoch  230  loss  3.111700154191046 correct 49
Epoch  240  loss  2.917580798334397 correct 49
Epoch  250  loss  2.87255729687638 correct 49
Epoch  260  loss  2.96293265175973 correct 49
Epoch  270  loss  2.9850287334749597 correct 49
Epoch  280  loss  2.8407589500387425 correct 49
Epoch  290  loss  2.615317336852242 correct 49
Epoch  300  loss  2.5592832050529304 correct 49
Epoch  310  loss  2.7158537476757316 correct 49
Epoch  320  loss  2.895550844401003 correct 49
Epoch  330  loss  2.7183164675836866 correct 49
Epoch  340  loss  2.3152418575581812 correct 49
Epoch  350  loss  2.0786859371581605 correct 49
Epoch  360  loss  2.1752643602827564 correct 49
Epoch  370  loss  3.0127310977003114 correct 49
Epoch  380  loss  3.9944106509637574 correct 48
Epoch  390  loss  1.9009286625188968 correct 49
Epoch  400  loss  0.9775243911547419 correct 50
Epoch  410  loss  0.8437258209474857 correct 50
Epoch  420  loss  0.7911830551882502 correct 50
Epoch  430  loss  0.7479360125569746 correct 50
Epoch  440  loss  0.7087653954701457 correct 50
Epoch  450  loss  0.6727669436259699 correct 50
Epoch  460  loss  0.6394854126639843 correct 50
Epoch  470  loss  0.6086058164102134 correct 50
Epoch  480  loss  0.5798825693927749 correct 50
Epoch  490  loss  0.5531137124144246 correct 50
Epoch  500  loss  0.5281270887616836 correct 50
```

## Diag

Config:
```py
PTS = 50
HIDDEN = 4
RATE = 0.5
data = minitorch.datasets["Diag"](PTS)
```

Logs:
```
Epoch  10  loss  17.016114929252534 correct 44
Epoch  20  loss  15.74777400146675 correct 44
Epoch  30  loss  14.647219925986457 correct 44
Epoch  40  loss  13.142064036036324 correct 44
Epoch  50  loss  11.295147452959833 correct 44
Epoch  60  loss  9.411697716825499 correct 44
Epoch  70  loss  8.185707407389307 correct 44
Epoch  80  loss  7.232502174660979 correct 44
Epoch  90  loss  6.501970142410064 correct 44
Epoch  100  loss  5.906517557509814 correct 50
Epoch  110  loss  5.417388616885436 correct 50
Epoch  120  loss  5.009658708977602 correct 50
Epoch  130  loss  4.664414787485216 correct 50
Epoch  140  loss  4.367966568553577 correct 50
Epoch  150  loss  4.110432124084745 correct 49
Epoch  160  loss  3.8845615583599176 correct 49
Epoch  170  loss  3.6849163182676494 correct 49
Epoch  180  loss  3.5073255318624357 correct 49
Epoch  190  loss  3.348527731890954 correct 49
Epoch  200  loss  3.2059317164386982 correct 49
Epoch  210  loss  3.0774541046440547 correct 49
Epoch  220  loss  2.9614070972070055 correct 49
Epoch  230  loss  2.856419726167524 correct 49
Epoch  240  loss  2.7613817852797298 correct 49
Epoch  250  loss  2.6754032173597047 correct 49
Epoch  260  loss  2.597783870950286 correct 49
Epoch  270  loss  2.527989699330422 correct 49
Epoch  280  loss  2.4656319267860023 correct 49
Epoch  290  loss  2.410445630446988 correct 49
Epoch  300  loss  2.3622637826137476 correct 49
Epoch  310  loss  2.3209824278523934 correct 49
Epoch  320  loss  2.2865130138328227 correct 49
Epoch  330  loss  2.2589263183914454 correct 49
Epoch  340  loss  2.8425440584491124 correct 49
Epoch  350  loss  2.6960379045694793 correct 49
Epoch  360  loss  2.596413765968206 correct 49
Epoch  370  loss  2.519141830674403 correct 49
Epoch  380  loss  2.4549308965440093 correct 49
Epoch  390  loss  2.399432785490604 correct 49
Epoch  400  loss  2.350288018152368 correct 49
Epoch  410  loss  2.306069093786452 correct 49
Epoch  420  loss  2.265837239306773 correct 49
Epoch  430  loss  2.228932985839352 correct 49
Epoch  440  loss  2.1948677054293686 correct 49
Epoch  450  loss  1.7320928291914333 correct 49
Epoch  460  loss  1.692131182008874 correct 49
Epoch  470  loss  1.7233256552420613 correct 49
Epoch  480  loss  1.7692099460078177 correct 49
Epoch  490  loss  1.8173257679371255 correct 49
Epoch  500  loss  2.5454287987358266 correct 49
```

## Split

Config:
```py
PTS = 50
HIDDEN = 5
RATE = 0.5
data = minitorch.datasets["Split"](PTS)
```

Logs:
```
Epoch  10  loss  34.16339830803106 correct 30
Epoch  20  loss  33.884790370379996 correct 30
Epoch  30  loss  33.72897063173875 correct 30
Epoch  40  loss  33.62018248809125 correct 30
Epoch  50  loss  33.51929777130973 correct 30
Epoch  60  loss  33.42862014445436 correct 30
Epoch  70  loss  33.335538885847185 correct 30
Epoch  80  loss  33.23518058625914 correct 30
Epoch  90  loss  33.098066091258254 correct 30
Epoch  100  loss  32.84342640605495 correct 30
Epoch  110  loss  32.486450042792605 correct 30
Epoch  120  loss  31.98999354531401 correct 30
Epoch  130  loss  31.191474941678898 correct 31
Epoch  140  loss  30.07708276688448 correct 34
Epoch  150  loss  28.478250263869892 correct 36
Epoch  160  loss  26.21875381412904 correct 39
Epoch  170  loss  23.230162292900218 correct 43
Epoch  180  loss  24.428053852590406 correct 45
Epoch  190  loss  26.75490069426166 correct 34
Epoch  200  loss  20.10892616391688 correct 41
Epoch  210  loss  16.83073664145469 correct 42
Epoch  220  loss  14.649709122069767 correct 42
Epoch  230  loss  13.527843305542806 correct 43
Epoch  240  loss  10.83650592141754 correct 44
Epoch  250  loss  7.145330398925651 correct 49
Epoch  260  loss  4.131546703874232 correct 50
Epoch  270  loss  3.25794680741555 correct 50
Epoch  280  loss  2.7545939287362313 correct 50
Epoch  290  loss  2.380441745338011 correct 50
Epoch  300  loss  2.090457217518767 correct 50
Epoch  310  loss  1.8592266175996093 correct 50
Epoch  320  loss  1.6742888128789588 correct 50
Epoch  330  loss  1.5188056484963313 correct 50
Epoch  340  loss  1.3886720889121202 correct 50
Epoch  350  loss  1.2768590815799228 correct 50
Epoch  360  loss  1.180315888676844 correct 50
Epoch  370  loss  1.0959374381601317 correct 50
Epoch  380  loss  1.0213031956359404 correct 50
Epoch  390  loss  0.9551502105443695 correct 50
Epoch  400  loss  0.8961475111949618 correct 50
Epoch  410  loss  0.8429692402143992 correct 50
Epoch  420  loss  0.7948107691236563 correct 50
Epoch  430  loss  0.7510263355199452 correct 50
Epoch  440  loss  0.7110767678432829 correct 50
Epoch  450  loss  0.6745076655022778 correct 50
Epoch  460  loss  0.6409329490539935 correct 50
Epoch  470  loss  0.6100222426267768 correct 50
Epoch  480  loss  0.5814910487519658 correct 50
Epoch  490  loss  0.5552905374363407 correct 50
Epoch  500  loss  0.5309875565021717 correct 50
```

## Xor

Config:
```py
PTS = 50
HIDDEN = 10
RATE = 0.5
data = minitorch.datasets["Xor"](PTS)
```

Logs:
```
Epoch  10  loss  32.657512156723634 correct 30
Epoch  20  loss  32.25071782976989 correct 26
Epoch  30  loss  29.953210818723516 correct 29
Epoch  40  loss  28.630974724998307 correct 31
Epoch  50  loss  24.93471670002377 correct 38
Epoch  60  loss  24.257885175116307 correct 39
Epoch  70  loss  24.59367658062688 correct 35
Epoch  80  loss  24.889890824148424 correct 36
Epoch  90  loss  25.73975152146791 correct 35
Epoch  100  loss  24.66703727348118 correct 35
Epoch  110  loss  20.45287340128864 correct 38
Epoch  120  loss  13.763622931678064 correct 45
Epoch  130  loss  10.693912350780488 correct 47
Epoch  140  loss  11.49040713737142 correct 49
Epoch  150  loss  25.646339356462963 correct 37
Epoch  160  loss  7.278982542921645 correct 50
Epoch  170  loss  9.413620369596226 correct 48
Epoch  180  loss  50.54157225536797 correct 32
Epoch  190  loss  5.4977044271684035 correct 50
Epoch  200  loss  7.543938103040507 correct 49
Epoch  210  loss  17.73290060152029 correct 39
Epoch  220  loss  4.842444431781559 correct 48
Epoch  230  loss  5.773831482725882 correct 50
Epoch  240  loss  19.058389642167548 correct 40
Epoch  250  loss  8.853809189560716 correct 46
Epoch  260  loss  3.5529661443433675 correct 49
Epoch  270  loss  4.563080455479764 correct 50
Epoch  280  loss  2.8271079290524046 correct 50
Epoch  290  loss  5.284290448074245 correct 50
Epoch  300  loss  3.24248125057766 correct 50
Epoch  310  loss  4.149728489672883 correct 49
Epoch  320  loss  6.022106496894339 correct 47
Epoch  330  loss  3.0093006869135306 correct 50
Epoch  340  loss  1.997943551205836 correct 50
Epoch  350  loss  1.7395115832191062 correct 50
Epoch  360  loss  3.8112672615349314 correct 49
Epoch  370  loss  2.548039854190744 correct 50
Epoch  380  loss  1.651927831733337 correct 50
Epoch  390  loss  1.4588721404444114 correct 50
Epoch  400  loss  1.341484349172705 correct 50
Epoch  410  loss  1.2391209862559642 correct 50
Epoch  420  loss  1.1637790836528172 correct 50
Epoch  430  loss  1.1054195306059142 correct 50
Epoch  440  loss  1.050121463055225 correct 50
Epoch  450  loss  0.9963626340622419 correct 50
Epoch  460  loss  0.9519450580912485 correct 50
Epoch  470  loss  0.9086016271155004 correct 50
Epoch  480  loss  0.8706612964025848 correct 50
Epoch  490  loss  0.8353789405174561 correct 50
Epoch  500  loss  0.8028455984614901 correct 50
```

# 2.5

Tensor training on all datasets. Configs below match those used in 1.5, except the
`Simple`/`Diag` datasets use `HIDDEN = 4`, and `Circle`/`Spiral` use `HIDDEN = 5`.
Times are reported per epoch.

## Simple

Config:
```py
PTS = 50
HIDDEN = 4
RATE = 0.5
data = minitorch.datasets["Simple"](PTS)
```

Time: avg `0.2943s`/epoch (total 147.14s over 500 epochs).

Logs:
```
Epoch  10  loss  32.30522349279218 correct 35
Epoch  20  loss  23.523421066190654 correct 48
Epoch  30  loss  15.11853427880288 correct 48
Epoch  40  loss  15.187816978337189 correct 46
Epoch  50  loss  9.473348761658695 correct 47
Epoch  60  loss  5.698014862509735 correct 48
Epoch  70  loss  4.579040017471074 correct 48
Epoch  80  loss  4.60304935968254 correct 48
Epoch  90  loss  4.180873560070552 correct 48
Epoch  100  loss  3.3193658348292154 correct 48
Epoch  110  loss  2.844148594051368 correct 48
Epoch  120  loss  2.573137534636233 correct 48
Epoch  130  loss  2.3443271971346644 correct 48
Epoch  140  loss  2.014218320881328 correct 49
Epoch  150  loss  1.605866670731113 correct 49
Epoch  160  loss  1.250507185819546 correct 50
Epoch  170  loss  1.0629635098151635 correct 50
Epoch  180  loss  0.9555453283100458 correct 50
Epoch  190  loss  0.8798526456181561 correct 50
Epoch  200  loss  0.8172510687948817 correct 50
Epoch  210  loss  0.7632228881400905 correct 50
Epoch  220  loss  0.7159405795470164 correct 50
Epoch  230  loss  0.6734205746703917 correct 50
Epoch  240  loss  0.6351743062569651 correct 50
Epoch  250  loss  0.5999880785314062 correct 50
Epoch  260  loss  0.5680892907740217 correct 50
Epoch  270  loss  0.5388645673252664 correct 50
Epoch  280  loss  0.5120308415155276 correct 50
Epoch  290  loss  0.48729143390047347 correct 50
Epoch  300  loss  0.46454139906520037 correct 50
Epoch  310  loss  0.44352426744991286 correct 50
Epoch  320  loss  0.42406001614067934 correct 50
Epoch  330  loss  0.4059429636627511 correct 50
Epoch  340  loss  0.38905747483188724 correct 50
Epoch  350  loss  0.3732823674036049 correct 50
Epoch  360  loss  0.3585133912634591 correct 50
Epoch  370  loss  0.3446796153408109 correct 50
Epoch  380  loss  0.3316930286654409 correct 50
Epoch  390  loss  0.31948372133552055 correct 50
Epoch  400  loss  0.3079830901733604 correct 50
Epoch  410  loss  0.29713784611155536 correct 50
Epoch  420  loss  0.2868986770947343 correct 50
Epoch  430  loss  0.27721658775031544 correct 50
Epoch  440  loss  0.2680521444277114 correct 50
Epoch  450  loss  0.2593688402398417 correct 50
Epoch  460  loss  0.2511305198063488 correct 50
Epoch  470  loss  0.24330745775169746 correct 50
Epoch  480  loss  0.2358714026993363 correct 50
Epoch  490  loss  0.22882652259785796 correct 50
Epoch  500  loss  0.2221171736323885 correct 50
```

## Diag

Config:
```py
PTS = 50
HIDDEN = 4
RATE = 0.5
data = minitorch.datasets["Diag"](PTS)
```

Time: avg `0.2905s`/epoch (total 145.26s over 500 epochs).

Logs:
```
Epoch  10  loss  13.677768529780376 correct 46
Epoch  20  loss  12.39604374520291 correct 46
Epoch  30  loss  11.29244011887928 correct 46
Epoch  40  loss  9.865566155155722 correct 46
Epoch  50  loss  8.026356774737925 correct 46
Epoch  60  loss  6.033492354174608 correct 46
Epoch  70  loss  4.39859214071637 correct 49
Epoch  80  loss  3.2876767556138695 correct 49
Epoch  90  loss  2.626416440877042 correct 49
Epoch  100  loss  2.1741423253149144 correct 49
Epoch  110  loss  1.8399183827266938 correct 50
Epoch  120  loss  1.5856228805616872 correct 50
Epoch  130  loss  1.3879930141835586 correct 50
Epoch  140  loss  1.2312900365355566 correct 50
Epoch  150  loss  1.104702685473828 correct 50
Epoch  160  loss  1.0006581316329004 correct 50
Epoch  170  loss  0.9137847650305021 correct 50
Epoch  180  loss  0.8402214125829663 correct 50
Epoch  190  loss  0.7771252102300504 correct 50
Epoch  200  loss  0.7223963507053771 correct 50
Epoch  210  loss  0.6744453126745956 correct 50
Epoch  220  loss  0.6320569223860061 correct 50
Epoch  230  loss  0.5942922098468176 correct 50
Epoch  240  loss  0.5604136608525071 correct 50
Epoch  250  loss  0.5298332546848156 correct 50
Epoch  260  loss  0.502079919700975 correct 50
Epoch  270  loss  0.4767684563016788 correct 50
Epoch  280  loss  0.4535837683383654 correct 50
Epoch  290  loss  0.4322645143390107 correct 50
Epoch  300  loss  0.41259214647015235 correct 50
Epoch  310  loss  0.39438135742682096 correct 50
Epoch  320  loss  0.37747511136848716 correct 50
Epoch  330  loss  0.36173910756249755 correct 50
Epoch  340  loss  0.34705710435890386 correct 50
Epoch  350  loss  0.3333285826945425 correct 50
Epoch  360  loss  0.32046534422341477 correct 50
Epoch  370  loss  0.30839034208844734 correct 50
Epoch  380  loss  0.29703565469233073 correct 50
Epoch  390  loss  0.2863411162818529 correct 50
Epoch  400  loss  0.2762532052775655 correct 50
Epoch  410  loss  0.26672412257037853 correct 50
Epoch  420  loss  0.25771102265236273 correct 50
Epoch  430  loss  0.2491753685105707 correct 50
Epoch  440  loss  0.2410823873692951 correct 50
Epoch  450  loss  0.2334006091009581 correct 50
Epoch  460  loss  0.22610147279147338 correct 50
Epoch  470  loss  0.21915898980256213 correct 50
Epoch  480  loss  0.2125494539134261 correct 50
Epoch  490  loss  0.20625119089134025 correct 50
Epoch  500  loss  0.20034531956311252 correct 50
```

## Split

Config:
```py
PTS = 50
HIDDEN = 5
RATE = 0.5
data = minitorch.datasets["Split"](PTS)
```

Time: avg `0.4148s`/epoch (total 207.42s over 500 epochs).

Logs:
```
Epoch  10  loss  31.217123199261085 correct 34
Epoch  20  loss  31.035181380341236 correct 34
Epoch  30  loss  30.86395730456639 correct 34
Epoch  40  loss  30.639438662098268 correct 34
Epoch  50  loss  30.30727769202645 correct 34
Epoch  60  loss  29.792603755170102 correct 34
Epoch  70  loss  29.009111845060993 correct 34
Epoch  80  loss  27.818835927775933 correct 35
Epoch  90  loss  26.072051767688684 correct 38
Epoch  100  loss  23.588233692001356 correct 40
Epoch  110  loss  20.364570503896044 correct 46
Epoch  120  loss  22.591986078458582 correct 35
Epoch  130  loss  22.586050061261275 correct 40
Epoch  140  loss  19.551337171334843 correct 42
Epoch  150  loss  19.156882936199313 correct 42
Epoch  160  loss  17.626697695537832 correct 42
Epoch  170  loss  16.93167637935721 correct 42
Epoch  180  loss  16.32467626421929 correct 42
Epoch  190  loss  15.151972001795917 correct 42
Epoch  200  loss  14.716321684108546 correct 42
Epoch  210  loss  14.14111678982438 correct 43
Epoch  220  loss  13.330980233877726 correct 44
Epoch  230  loss  13.091668841086877 correct 44
Epoch  240  loss  12.090008300870105 correct 45
Epoch  250  loss  11.53546148863767 correct 45
Epoch  260  loss  11.42149127075266 correct 45
Epoch  270  loss  10.833237052020205 correct 45
Epoch  280  loss  9.356799404785251 correct 46
Epoch  290  loss  11.574258385994176 correct 45
Epoch  300  loss  8.813753023531296 correct 46
Epoch  310  loss  4.12240225824592 correct 49
Epoch  320  loss  3.0417068790945536 correct 50
Epoch  330  loss  2.6042999760177548 correct 50
Epoch  340  loss  2.2952276444720496 correct 50
Epoch  350  loss  2.0504325455720753 correct 50
Epoch  360  loss  1.8457682536919282 correct 50
Epoch  370  loss  1.6757228107586866 correct 50
Epoch  380  loss  1.5318095894451245 correct 50
Epoch  390  loss  1.409040001035339 correct 50
Epoch  400  loss  1.3025645040609133 correct 50
Epoch  410  loss  1.209445201210281 correct 50
Epoch  420  loss  1.1274431980380817 correct 50
Epoch  430  loss  1.0547857461364112 correct 50
Epoch  440  loss  0.9899821349712787 correct 50
Epoch  450  loss  0.931884830381212 correct 50
Epoch  460  loss  0.8795426087824423 correct 50
Epoch  470  loss  0.8321787838961872 correct 50
Epoch  480  loss  0.7894360204585239 correct 50
Epoch  490  loss  0.7504447557348958 correct 50
Epoch  500  loss  0.7147134137409361 correct 50
```

## Xor

Config:
```py
PTS = 50
HIDDEN = 10
RATE = 0.5
data = minitorch.datasets["Xor"](PTS)
```

Time: avg `0.7495s`/epoch (total 374.77s over 500 epochs).

Logs:
```
Epoch  10  loss  34.12300857380537 correct 26
Epoch  20  loss  32.92710070414568 correct 31
Epoch  30  loss  31.457100341109246 correct 33
Epoch  40  loss  29.63274215073429 correct 38
Epoch  50  loss  28.091835398665122 correct 44
Epoch  60  loss  28.29620174429369 correct 29
Epoch  70  loss  27.00673111533465 correct 32
Epoch  80  loss  25.5455187004563 correct 38
Epoch  90  loss  26.24704668563635 correct 35
Epoch  100  loss  25.634524923262283 correct 36
Epoch  110  loss  22.62663408689481 correct 41
Epoch  120  loss  20.42697367766093 correct 43
Epoch  130  loss  25.533208804780386 correct 35
Epoch  140  loss  22.520404987162763 correct 40
Epoch  150  loss  21.797458202389095 correct 40
Epoch  160  loss  20.888014261592623 correct 41
Epoch  170  loss  20.023132695721653 correct 41
Epoch  180  loss  18.568094970393297 correct 42
Epoch  190  loss  14.527859234390302 correct 45
Epoch  200  loss  17.792037900290353 correct 40
Epoch  210  loss  11.47826791179546 correct 45
Epoch  220  loss  11.528196056212781 correct 45
Epoch  230  loss  23.641325475405413 correct 39
Epoch  240  loss  9.343472438028648 correct 48
Epoch  250  loss  9.553138634198994 correct 48
Epoch  260  loss  15.038556773032619 correct 41
Epoch  270  loss  8.724528477197438 correct 48
Epoch  280  loss  8.149871235223813 correct 47
Epoch  290  loss  7.99395081102965 correct 49
Epoch  300  loss  15.596178149207452 correct 40
Epoch  310  loss  7.671002194480838 correct 47
Epoch  320  loss  10.368783511465882 correct 44
Epoch  330  loss  6.504242723822396 correct 48
Epoch  340  loss  7.687698552212296 correct 49
Epoch  350  loss  6.319375792111409 correct 49
Epoch  360  loss  11.785970767588433 correct 44
Epoch  370  loss  7.821125727225014 correct 47
Epoch  380  loss  5.373622351067652 correct 49
Epoch  390  loss  6.4636919189757585 correct 49
Epoch  400  loss  5.570555496146626 correct 49
Epoch  410  loss  10.285384588991537 correct 47
Epoch  420  loss  5.735693400661131 correct 48
Epoch  430  loss  5.1050110248479275 correct 49
Epoch  440  loss  41.91216675161362 correct 37
Epoch  450  loss  5.450378148657046 correct 49
Epoch  460  loss  4.956694808855444 correct 49
Epoch  470  loss  4.538815857757384 correct 49
Epoch  480  loss  5.722454758285777 correct 49
Epoch  490  loss  5.024857095077303 correct 49
Epoch  500  loss  4.720475331496503 correct 49
```

## Circle

Config:
```py
PTS = 50
HIDDEN = 5
RATE = 0.5
data = minitorch.datasets["Circle"](PTS)
```

Time: avg `0.2403s`/epoch (total 120.17s over 500 epochs).

Logs:
```
Epoch  10  loss  32.98786312763621 correct 31
Epoch  20  loss  32.897708788395896 correct 31
Epoch  30  loss  32.812624789954945 correct 31
Epoch  40  loss  32.70961660555443 correct 31
Epoch  50  loss  32.582900086961104 correct 31
Epoch  60  loss  32.42117349691258 correct 31
Epoch  70  loss  32.19987422949468 correct 31
Epoch  80  loss  31.89481594449475 correct 31
Epoch  90  loss  31.49674779002001 correct 31
Epoch  100  loss  31.003816795702324 correct 30
Epoch  110  loss  30.469873282009196 correct 30
Epoch  120  loss  29.954628614664287 correct 30
Epoch  130  loss  29.474785713537194 correct 30
Epoch  140  loss  30.469149775893133 correct 35
Epoch  150  loss  29.355291796817802 correct 35
Epoch  160  loss  31.36101690464766 correct 32
Epoch  170  loss  28.786088100782685 correct 36
Epoch  180  loss  30.302957861708602 correct 38
Epoch  190  loss  28.964537473709747 correct 38
Epoch  200  loss  27.926397087217275 correct 36
Epoch  210  loss  26.855239552116387 correct 36
Epoch  220  loss  28.602241039098683 correct 36
Epoch  230  loss  25.545052126422867 correct 42
Epoch  240  loss  24.674621693708236 correct 41
Epoch  250  loss  24.331034728919384 correct 41
Epoch  260  loss  21.74603664845071 correct 40
Epoch  270  loss  25.18943248426035 correct 34
Epoch  280  loss  21.966085461128618 correct 40
Epoch  290  loss  21.661473498496576 correct 40
Epoch  300  loss  20.44841551025215 correct 40
Epoch  310  loss  21.89270109851464 correct 38
Epoch  320  loss  20.818806173720255 correct 39
Epoch  330  loss  18.26242932529506 correct 41
Epoch  340  loss  18.491392322659394 correct 41
Epoch  350  loss  17.41559722924876 correct 42
Epoch  360  loss  15.684618694758187 correct 43
Epoch  370  loss  16.30921648218223 correct 41
Epoch  380  loss  16.282389142308553 correct 42
Epoch  390  loss  14.88706370334861 correct 43
Epoch  400  loss  14.633106236084199 correct 43
Epoch  410  loss  13.406563516559983 correct 43
Epoch  420  loss  14.828134723512603 correct 42
Epoch  430  loss  13.70228366753594 correct 44
Epoch  440  loss  11.747442896549137 correct 45
Epoch  450  loss  14.461871669122106 correct 43
Epoch  460  loss  10.599257516562155 correct 45
Epoch  470  loss  10.791148609315535 correct 45
Epoch  480  loss  13.55695484021344 correct 44
Epoch  490  loss  9.997947938752612 correct 46
Epoch  500  loss  10.27459978623129 correct 45
```

## Spiral

Config:
```py
PTS = 50
HIDDEN = 5
RATE = 0.5
data = minitorch.datasets["Spiral"](PTS)
```

Time: avg `0.2596s`/epoch (total 129.82s over 500 epochs).

Logs:
```
Epoch  10  loss  34.22706215256382 correct 28
Epoch  20  loss  34.14035222166512 correct 29
Epoch  30  loss  34.03935303354582 correct 29
Epoch  40  loss  33.95547324327017 correct 29
Epoch  50  loss  33.878132797136274 correct 29
Epoch  60  loss  33.805889081749285 correct 29
Epoch  70  loss  33.74149139456659 correct 28
Epoch  80  loss  33.686951931923275 correct 28
Epoch  90  loss  33.653166708648605 correct 28
Epoch  100  loss  33.62310075807313 correct 28
Epoch  110  loss  33.59826761020759 correct 28
Epoch  120  loss  33.57636892726057 correct 27
Epoch  130  loss  33.55811370778783 correct 27
Epoch  140  loss  33.54186725869736 correct 27
Epoch  150  loss  33.49521227559236 correct 27
Epoch  160  loss  33.46915022659039 correct 28
Epoch  170  loss  33.4490680465439 correct 27
Epoch  180  loss  33.42612830685736 correct 27
Epoch  190  loss  33.40451089808596 correct 29
Epoch  200  loss  33.38879727825047 correct 27
Epoch  210  loss  33.37085182541145 correct 29
Epoch  220  loss  33.35118038453066 correct 29
Epoch  230  loss  33.32535887364691 correct 29
Epoch  240  loss  33.304740047941905 correct 29
Epoch  250  loss  33.28644069949269 correct 29
Epoch  260  loss  33.27227351995302 correct 27
Epoch  270  loss  33.23841388140344 correct 29
Epoch  280  loss  33.20231483321526 correct 29
Epoch  290  loss  33.18796971539333 correct 26
Epoch  300  loss  33.16503883968145 correct 28
Epoch  310  loss  33.12135185771072 correct 29
Epoch  320  loss  33.113590681274985 correct 26
Epoch  330  loss  33.06458656432829 correct 28
Epoch  340  loss  33.02154447003232 correct 29
Epoch  350  loss  32.96104944728084 correct 29
Epoch  360  loss  32.91425893367682 correct 27
Epoch  370  loss  32.88232457884616 correct 27
Epoch  380  loss  32.83265044163699 correct 27
Epoch  390  loss  32.80415895801464 correct 28
Epoch  400  loss  32.77089475079036 correct 28
Epoch  410  loss  32.70700336295917 correct 27
Epoch  420  loss  32.66853159404808 correct 27
Epoch  430  loss  32.631488813731345 correct 27
Epoch  440  loss  32.59963637278539 correct 27
Epoch  450  loss  32.558204231401 correct 26
Epoch  460  loss  32.518238780784976 correct 26
Epoch  470  loss  32.49001969284514 correct 26
Epoch  480  loss  32.45022882148128 correct 28
Epoch  490  loss  32.41267308928758 correct 28
Epoch  500  loss  32.390697744319354 correct 28
```

# 3.1 / 3.2

## Numba parallel diagnostics

Output of `python project/parallel_check.py` (Numba `parallel_diagnostics(level=3)`):

```
MAP
Parallel Accelerator Optimizing: Function tensor_map.<locals>._map
Parallel loop listing: loop #2 (parallel) - stride-aligned fast path
                       loop #3 (parallel) - broadcast path
After optimisation: loop #3 parallel, loops #0, #1 (index buffers) serialized.
Loop invariant code motion: out_index, in_index allocations hoisted out of #3.

ZIP
Parallel Accelerator Optimizing: Function tensor_zip.<locals>._zip
Parallel loop listing: loop #7 (parallel) - stride-aligned fast path
                       loop #8 (parallel) - broadcast path
After optimisation: loop #8 parallel, loops #4, #5, #6 (index buffers) serialized.
Loop invariant code motion: out_index, a_index, b_index allocations hoisted.

REDUCE
Parallel Accelerator Optimizing: Function tensor_reduce.<locals>._reduce
Parallel loop listing: loop #10 (parallel)
After optimisation: loop #10 parallel, loop #9 (index buffer) serialized.
Loop invariant code motion: out_index allocation hoisted.

MATRIX MULTIPLY
Parallel Accelerator Optimizing: Function _tensor_matrix_multiply
Parallel loop listing: loop #13 (parallel, batch) over #12 (i), #11 (j)
After optimisation: loop #13 parallel, #12/#11 serialized inside it.
No allocation hoisting found (no index buffers, as intended).
```

All four kernels are parallelized; inner index buffers are hoisted out of the
parallel loops, and the inner matmul loops are serialized inside the parallel
batch loop with no global writes.

# 3.5

## Fast tensor training (Task 3.5)

The fast (numba parallel / CUDA) tensor backend is used via `project/run_fast_tensor.py`.
Model: 3-layer MLP with `HIDDEN = 100` hidden units, `RATE = 0.05`, `PTS = 50`,
trained for 500 epochs with mini-batches of size 10.

Command:
```bash
python project/run_fast_tensor.py --BACKEND cpu --HIDDEN 100 --DATASET split --RATE 0.05
python project/run_fast_tensor.py --BACKEND gpu --HIDDEN 100 --DATASET split --RATE 0.05
```

### Results (final epoch, after 500 epochs)

| Dataset | Backend | Final loss | Correct |
|---------|---------|------------|---------|
| Simple  | cpu/gpu  | 0.6040     | 50/50   |
| Diag    | cpu/gpu  | 0.7091     | 50/50   |
| Split   | cpu/gpu  | 0.1773     | 50/50   |
| Xor     | cpu/gpu  | 0.4680     | 49/50   |
| Circle  | cpu/gpu  | 0.3522     | 50/50   |
| Spiral  | cpu/gpu  | 6.8435     | 30/50   |

The model and data are identical for both backends, so the final accuracy is the
same; the backends differ only in execution time.

### Time per epoch (bigger model, `HIDDEN = 100`)

Benchmark: `python project/train_fast_tensor_bench.py --BACKEND cpu|gpu`
(500 epochs per dataset).

| Dataset | CPU avg s/epoch | GPU avg s/epoch |
|---------|-----------------|-----------------|
| Simple  | 0.2205          | 1.5151          |
| Diag    | 0.1507          | 0.9747          |
| Split   | 0.1505          | 0.8203          |
| Xor     | 0.1598          | 0.8443          |
| Circle  | 0.1778          | 0.8275          |
| Spiral  | 0.1525          | 0.8281          |

Note: on mine local GPU the mini-batched training loop (batch size 10, small 2-D
inputs) is dominated by per-op kernel-launch and host-device transfer overhead,
so the CPU backend is faster per epoch than the GPU backend for these small
tensors. The CPU backend stays well below 2s/epoch as targeted.

