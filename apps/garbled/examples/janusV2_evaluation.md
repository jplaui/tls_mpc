#### janusV2_transparent16B.mpcl
Circuit: #gates=5812784 (XOR=4659956 XNOR=0 AND=1152266 OR=561 INV=1 xor=4659956 !xor=1152828 levels=863203 width=2073) #w=5816840

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 284.218958ms │ 44.61% │       │
│ Xfer    │  69.243458ms │ 10.87% │  60MB │
│ OT Init │      11.25µs │  0.00% │  22kB │
│ OT      │ 116.527542ms │ 18.29% │ 239kB │
│ Eval    │ 167.146625ms │ 26.23% │       │
│ Result  │     20.667µs │  0.00% │  133B │
│ Total   │   637.1685ms │        │  60MB │
│ ├╴Sent  │              │ 99.75% │  60MB │
│ ├╴Rcvd  │              │  0.25% │ 153kB │
│ ╰╴Flcd  │              │        │   923 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 116,52+167,14+0,02 = 283.68 ms
com offline:  = 
com online:  = 

#### janusV2_transparent32B.mpcl
Circuit: #gates=5849817 (XOR=4690461 XNOR=0 AND=1158682 OR=673 INV=1 xor=4690461 !xor=1159356 levels=863235 width=2073) #w=5854129

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │   256.8395ms │ 42.12% │       │
│ Xfer    │  65.476208ms │ 10.74% │  60MB │
│ OT Init │     21.542µs │  0.00% │  55kB │
│ OT      │ 124.404583ms │ 20.40% │ 253kB │
│ Eval    │ 163.084375ms │ 26.74% │       │
│ Result  │     18.125µs │  0.00% │  133B │
│ Total   │ 609.844333ms │        │  60MB │
│ ├╴Sent  │              │ 99.73% │  60MB │
│ ├╴Rcvd  │              │  0.27% │ 163kB │
│ ╰╴Flcd  │              │        │   928 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 124,40+163,08+0,01 = 287.49 ms
com offline:  = 
com online:  = 


#### janusV2_transparent64B.mpcl
Circuit: #gates=5923882 (XOR=4751470 XNOR=0 AND=1171514 OR=897 INV=1 xor=4751470 !xor=1172412 levels=863299 width=2073) #w=5928706

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 261.395042ms │ 40.42% │       │
│ Xfer    │  72.843083ms │ 11.26% │  61MB │
│ OT Init │     19.042µs │  0.00% │  56kB │
│ OT      │ 131.815958ms │ 20.38% │ 282kB │
│ Eval    │ 180.638167ms │ 27.93% │       │
│ Result  │     10.166µs │  0.00% │  133B │
│ Total   │ 646.721458ms │        │  61MB │
│ ├╴Sent  │              │ 99.71% │  61MB │
│ ├╴Rcvd  │              │  0.29% │ 181kB │
│ ╰╴Flcd  │              │        │   939 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 131,81+180,63+0,01 = 312.45 ms
com offline:  = 
com online:  = 

#### janusV2_transparent128B.mpcl
Circuit: #gates=6072014 (XOR=4873490 XNOR=0 AND=1197178 OR=1345 INV=1 xor=4873490 !xor=1198524 levels=863427 width=2073) #w=6077862

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 301.336208ms │ 40.71% │       │
│ Xfer    │  73.215667ms │  9.89% │  62MB │
│ OT Init │     19.291µs │  0.00% │  58kB │
│ OT      │ 158.290542ms │ 21.38% │ 339kB │
│ Eval    │ 207.413875ms │ 28.02% │       │
│ Result  │     10.625µs │  0.00% │  133B │
│ Total   │ 740.286208ms │        │  63MB │
│ ├╴Sent  │              │ 99.65% │  62MB │
│ ├╴Rcvd  │              │  0.35% │ 218kB │
│ ╰╴Flcd  │              │        │   961 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 158,29+207,41+0,01 = 365.71 ms
com offline:  = 
com online:  = 


#### janusV2_transparent256B.mpcl
Circuit: #gates=6368282 (XOR=5117534 XNOR=0 AND=1248506 OR=2241 INV=1 xor=5117534 !xor=1250748 levels=863683 width=3130) #w=6376178

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 319.637708ms │ 37.29% │       │
│ Xfer    │  76.838917ms │  8.97% │  65MB │
│ OT Init │     18.542µs │  0.00% │  61kB │
│ OT      │ 205.483541ms │ 23.97% │ 454kB │
│ Eval    │ 255.085667ms │ 29.76% │       │
│ Result  │     11.375µs │  0.00% │  133B │
│ Total   │  857.07575ms │        │  66MB │
│ ├╴Sent  │              │ 99.56% │  65MB │
│ ├╴Rcvd  │              │  0.44% │ 292kB │
│ ╰╴Flcd  │              │        │  1006 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 205,48+255,08+0,01 = 460.57 ms
com offline:  = 
com online:  = 


#### janusV2_transparent512B.mpcl
Circuit: #gates=6960826 (XOR=5605630 XNOR=0 AND=1351162 OR=4033 INV=1 xor=5605630 !xor=1355196 levels=864195 width=5930) #w=6972818

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 352.409292ms │ 31.21% │       │
│ Xfer    │    75.4655ms │  6.68% │  71MB │
│ OT Init │      15.25µs │  0.00% │   3kB │
│ OT      │ 360.853125ms │ 31.95% │ 683kB │
│ Eval    │ 340.573833ms │ 30.16% │       │
│ Result  │     11.708µs │  0.00% │  133B │
│ Total   │ 1.129328708s │        │  72MB │
│ ├╴Sent  │              │ 99.39% │  71MB │
│ ├╴Rcvd  │              │  0.61% │ 439kB │
│ ╰╴Flcd  │              │        │  1096 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 360,85+340,57+0,01 = 701.43 ms
com offline:  = 
com online:  = 

#### janusV2_transparent1024B.mpcl
Circuit: #gates=8145930 (XOR=6581838 XNOR=0 AND=1556474 OR=7617 INV=1 xor=6581838 !xor=1564092 levels=865219 width=11530) #w=8166114

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 396.365375ms │ 26.16% │       │
│ Xfer    │ 100.329792ms │  6.62% │  82MB │
│ OT Init │     19.667µs │  0.00% │  17kB │
│ OT      │ 492.805833ms │ 32.52% │   1MB │
│ Eval    │   525.6405ms │ 34.69% │       │
│ Result  │     12.833µs │  0.00% │  133B │
│ Total   │    1.515174s │        │  84MB │
│ ├╴Sent  │              │ 99.13% │  83MB │
│ ├╴Rcvd  │              │  0.87% │ 734kB │
│ ╰╴Flcd  │              │        │  1275 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 492,80+525,64+0,01 = 1.01845 s
com offline:  = 
com online:  = 

#### janusV2_transparent2048B.mpcl
Circuit: #gates=10516170 (XOR=8534286 XNOR=0 AND=1967098 OR=14785 INV=1 xor=8534286 !xor=1981884 levels=867267 width=22730) #w=10552738

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 526.621584ms │ 22.09% │       │
│ Xfer    │ 112.792041ms │  4.73% │ 105MB │
│ OT Init │     13.584µs │  0.00% │  46kB │
│ OT      │    871.321ms │ 36.55% │   2MB │
│ Eval    │ 873.117125ms │ 36.63% │       │
│ Result  │     12.833µs │  0.00% │  133B │
│ Total   │ 2.383878167s │        │ 108MB │
│ ├╴Sent  │              │ 98.77% │ 106MB │
│ ├╴Rcvd  │              │  1.23% │   1MB │
│ ╰╴Flcd  │              │        │  1632 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 871,32+873,11+0,01 = 1.7444 s
com offline:  = 
com online:  = 

#### janusV2_transparent4096B.mpcl
Circuit: #gates=15256714 (XOR=12439246 XNOR=0 AND=2788346 OR=29121 INV=1 xor=12439246 !xor=2817468 levels=871363 width=45130) #w=15326050

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 988.135625ms │ 22.12% │       │
│ Xfer    │ 185.969958ms │  4.16% │ 152MB │
│ OT Init │     14.125µs │  0.00% │  38kB │
│ OT      │ 1.652106209s │ 36.98% │   3MB │
│ Eval    │  1.64120225s │ 36.74% │       │
│ Result  │     13.708µs │  0.00% │  133B │
│ Total   │ 4.467441875s │        │ 156MB │
│ ├╴Sent  │              │ 98.40% │ 153MB │
│ ├╴Rcvd  │              │  1.60% │   2MB │
│ ╰╴Flcd  │              │        │  2347 │
└─────────┴──────────────┴────────┴───────┘

exec offline:  = 
exec online: 1,65+1,64 = 3.29 s
com offline:  = 
com online:  = 

#### janusV2_transparent8192B.mpcl



exec offline:  = 
exec online:  =  s
com offline:  = 
com online:  = 


#########################
########################
########################

#### janusV2_transparent2kB.mpcl (256 request, 2 kB response)
Circuit: #gates=12734508 (XOR=10373546 XNOR=0 AND=2344160 OR=16801 INV=1 xor=10373546 !xor=2360962 levels=867843 width=25860) #w=12776380

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 734.834875ms │ 24.57% │       │
│ Xfer    │ 203.666792ms │  6.81% │ 127MB │
│ OT Init │     16.125µs │  0.00% │  26kB │
│ OT      │ 1.004653666s │ 33.59% │   2MB │
│ Eval    │ 1.047443292s │ 35.02% │       │
│ Result  │     12.667µs │  0.00% │  133B │
│ Total   │ 2.990627417s │        │ 129MB │
│ ├╴Sent  │              │ 98.84% │ 127MB │
│ ├╴Rcvd  │              │  1.16% │   1MB │
│ ╰╴Flcd  │              │        │  1955 │
└─────────┴──────────────┴────────┴───────┘

exec offline: 734,83+203,66+0,016 = 938.5 ms
exec online: 1+1,04 = 2.04 s
com offline: 127+0,026 = 127.02 MB
com online: 2+0,000133 = 2 MB

#### janusV2_private2kB.mpcl (256 request, 2 kB response)
Circuit: #gates=17153701 (XOR=14052905 XNOR=0 AND=3083770 OR=17025 INV=1 xor=14052905 !xor=3100796 levels=867844 width=25860) #w=17195829

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 924.782584ms │ 28.66% │       │
│ Xfer    │ 214.801916ms │  6.66% │ 168MB │
│ OT Init │     16.334µs │  0.00% │  34kB │
│ OT      │ 986.631833ms │ 30.57% │   2MB │
│ Eval    │  1.10094275s │ 34.11% │       │
│ Result  │       10.5µs │  0.00% │  133B │
│ Total   │ 3.227185917s │        │ 170MB │
│ ├╴Sent  │              │ 99.12% │ 169MB │
│ ├╴Rcvd  │              │  0.88% │   1MB │
│ ╰╴Flcd  │              │        │  2586 │
└─────────┴──────────────┴────────┴───────┘

exec offline: 924,78+214,8+0,016 = 1.13 s
exec online: 0,98+1,1 = 2.08 s
com offline: 168+0,034 = 168.03 MB
com online: 2+0,000133 = 2 MB

#### janusV2_transparent.mpcl (256 request, 16 kB response)
Circuit: #gates=7751432 (XOR=6187654 XNOR=0 AND=1449312 OR=114465 INV=1 xor=6187654 !xor=1563778 levels=895747 width=46988) #w=7756568

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │   485.5255ms │ 45.91% │       │
│ Xfer    │ 143.571292ms │ 13.58% │  82MB │
│ OT Init │       24.5µs │  0.00% │  22kB │
│ OT      │ 172.936708ms │ 16.35% │ 274kB │
│ Eval    │ 255.474209ms │ 24.16% │       │
│ Result  │      37.25µs │  0.00% │  133B │
│ Total   │ 1.057569459s │        │  83MB │
│ ├╴Sent  │              │ 99.79% │  83MB │
│ ├╴Rcvd  │              │  0.21% │ 176kB │
│ ╰╴Flcd  │              │        │  1270 │
└─────────┴──────────────┴────────┴───────┘

exec offline: 485,52+143,57+0,024 = 629.11 ms
exec online: 172,93+255,47+0,037 = 428.43 ms
com offline: 82+0,022 = 82.02 MB
com online: 274+0.133 = 274.13 kB

#### janusV2_private.mpcl (256 request, 16 kB response + hash on private plaintext chunks)
Circuit: #gates=8388595 (XOR=6717024 XNOR=0 AND=1556881 OR=114689 INV=1 xor=6717024 !xor=1671571 levels=895748 width=46988) #w=8393987

┌─────────┬──────────────┬────────┬───────┐
│ Op      │         Time │      % │  Xfer │
├─────────┼──────────────┼────────┼───────┤
│ Garble  │ 552.542834ms │ 49.84% │       │
│ Xfer    │ 148.887291ms │ 13.43% │  88MB │
│ OT Init │     15.459µs │  0.00% │  64kB │
│ OT      │  175.36525ms │ 15.82% │ 274kB │
│ Eval    │ 231.712125ms │ 20.90% │       │
│ Result  │     76.333µs │  0.01% │  133B │
│ Total   │ 1.108599292s │        │  89MB │
│ ├╴Sent  │              │ 99.80% │  89MB │
│ ├╴Rcvd  │              │  0.20% │ 176kB │
│ ╰╴Flcd  │              │        │  1361 │
└─────────┴──────────────┴────────┴───────┘

exec offline: 552,54+148,88+0,015 = 701.43 ms
exec online: 175,36+231,71+0,076 = 407.14 ms
com offline: 88+0,064 = 88.06 MB
com online: 274+0.133 = 274.13 kB