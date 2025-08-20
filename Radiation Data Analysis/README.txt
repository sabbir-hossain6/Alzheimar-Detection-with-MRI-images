This folder contains 16 csv files in total. Each csv file has three columns:
  x: position of measurements in meters
  y: position of measurements in meters
  counts: gamma-ray counts rates in counts per second.

The x, y positions are transformed using the original longitude and latitude. For privacy concerns, we have removed the time and original longitude and latitude information.

Among the 16 files, background.csv is the background radiation measurements collected without any radioactive sources. For the rest 15 files, they are named in the format of:
  {source strength}uCi_{distance}m.csv

Source strength varies from 100 uCi to 2000 uCi, and distance varies from 1 meter to 10 meters. For example, 100uCi_1m.csv means that the simulated radioactive sources have the strength of 100 uCi, and they are placed 1 meter away from the walking path. The influence of the injected radioactive source is reflected in the change of radiation counts.

When source is placed 1 meter away from walking path, their positions are listed below (in (x, y) format):

(55.872717247072593, 196.92621508810504),
(54.766691312307643, 328.8033980886974),
(310.65636620422441, 330.58251691497173),
(446.80768246330786, 331.3608814010247),
(450.63602771295325, 281.65674919101247),
(172.72012940018126, 245.4072031058494),
(86.488895976259869, 23.573324449903453),
(360.92253839543372, 50.48249669747984),
(453.70060444398746, 179.13502682536154),
(167.95823653179627, 204.48747010012468).

When source is placed 5 meters away from walking path, their positions are listed below (in (x, y) format):

(59.954728147614432, 200.48445274065375),
(58.593571895374346, 324.80038072922645),
(306.74454132085037, 326.57949955550083),
(442.98090596069596, 328.35861838248246),
(447.14919921582498, 285.6597665504834),
(176.12182930540212, 243.4056944254066),
(86.488872452199644, 27.687536735043984),
(358.11605322183294, 53.26236986326827),
(450.38403137701783, 176.5775435123269),
(171.44494557689936, 206.1553939993148)

When source is placed 10 meters away from walking path, their positions are listed below (in (x, y) format):

(64.972195974115991, 205.15463965980075),
(63.696080148696403, 320.0189988837026),
(301.8122432194121, 321.24214307667773),
(441.53534415355057, 323.466041609167),
(442.30167338973928, 290.7747331765527),
(180.37394816132053, 241.51538067275536),
(86.573886952055929, 32.69130843402901),
(354.88433591814044, 56.82060751581697),
(446.47216753898539, 173.79767034653847),
(175.35684901285742, 209.15765701927168).