# Android Chess Engines Testing
Tournament results, speed tests, testing scripts, ... of some very strong Android engines available in my repos. 
At the moment, tournaments with armv8 builds of SFnps230227, SFSnps230227, and CFishNN_230302 are on the way. 
Reasonable tests with my old hardware need time. Test equipment: 
Amazon FireHD8 (7th gen.), CfA v6.2.1,  Parallel Space App, two instances of CfA running, CPU load < 65% 4th core often stopped.
At the moment, I'm just collecting data, thus no final results are presented.
However, results of the several 100 game matches, made each day, are updated as soon as available [here](https://github.com/Joachim26/Android_Chess_Engines_Testing/blob/main/DailyUpdatedTestResults.txt) and also below:


________________________________________
TC=schnell, 100 games

CFvsSFS:
45.0:55.0
49.0:51.0
45.5:54.5
= 139.5:160.5 = -24 Elo

CFvsSF:
53.5:46.5
48.5:51.5
53.0:47.0
= 155.0:145.0 = +12 Elo

SFSvsSF:
54.5:45.5
55.0:45.0
56.5:43.5
= 166.0:134.0 = +37 Elo
________________________________________
TC=10+1s, 100 games

CFvsSFS:
46.5:53.5
50.0:50.0
51.0:49.0
52.5:47.5
50.5:49.5
56.5:43.5
= 307.0:293.0 = +8 Elo

CFvsSF:
53.0:47.0
52.5:47.5
51.5:48.5
48.0:52.0
53.0:47,0
51.0:49.0
= 309.0:291.0 = +10 Elo

SFSvsSF:
50.5:49.5
54.0:46.0
47.0:53.0
49.5:50.5
50.5:49.5
48.5:51.5
= 300.0:300.0 = +0 Elo
________________________________________
TC=60+1s, 100 games

CFvsSFS:
49.0:51.0
51.5:48.5
48.0:52.0
45.0:55.0
49.5:50.5
= 243.0:257.0 = -10 Elo

CFvsSF:
48.0:52.0
51.0:49.0
53.5:46.5
47.5:52.5
56.5:43.5
= 256.5:243.5 = +9 Elo

SFSvsSF:
51.5:48.5
46.5:53.5
48.5:51.5
49.0:51.0
50.0:50.0
= 245.5:254.5 = -6 Elo
________________________________________
For comparison reasons, a small number of tests 
on a more modern hardware with Snapdragon 662, 
about 3 to 3.5 times faster than the FireHD8, 
will be performed.

TC=schnell, 100 games

CFvsSFS:
50.5:49.5


________________________________________
TC=10+1s, 100 games

CFvsSFS:
52.5vs47.5
