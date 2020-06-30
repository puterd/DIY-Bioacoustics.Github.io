

## Authors: 

Alice Potts

![Alice](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/22635033_10159674572470554_1015735572_n.jpg)

Minwoo Kim

![Minwoo](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/Minwoo%2BKim.jpg)

Filippo Sanzeni

![Filippo](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/AAEAAQAAAAAAAAVYAAAAJGY3NjJiYzQ1LWIyMGItNDlmZC1hNTc0LTUyODZhYTcxM2E1OA.jpg)

Davin Browner Conaty

![Davin](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/22447373_791137924400541_1585141808_n.jpg)

# Collaborators: 

John Innes Centre: 

![JIC](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/JIC---White-background.jpg)



# Synopsis:



We are developing an open source and DIY sensor/service for biologists, using sound recordings to identify and track different species of leafhoppers through the different calls they make in order to monitor crop health. The sensor could also be utilised by citizen scientists, farmers and visual artists/computational designers.

![Project Summary](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/Overview.jpg)

![Leafhopper](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/2383551818_4a9235daee_o.jpg)

# Scientific Basis:

We will be developing an open source and DIY sensor/service for biologists, using sound recordings to identify and track different species of leafhoppers, to monitor crop health remotely. The sensor/service could also be utilised by citizen scientists, farmers and visual artists/computational designers.

Non-invasive bioacoustic monitoring has become an increasingly effective way of monitoring ecosystem diversity and health. Bioacoustics paired with machine learning has been cited as an effective way of automatically identifying animals such as frogs (Xie, 2017), birds (Zhao et al, 2017) and fish (Sattar et al, 2016) amongst other animals. Bioacoustics is an area of scientific research which would benefit from (i) continued expansion of machine learning and automated identification of insect species (ii) creation of open source hardware for conducting research. Our aim is to contribute to (i) by applying bioacoustics and machine learning to insect recognition and to (ii) by creating an open source, diy and hackable acoustic sensor for identification of various insect species.

Recent work on insect recognition and intelligent traps is seen in (Silva et al, 2014) and on methods of creating low cost sensors for insect recognition in (Silva et al, 2015). Problems with ambient noise in traditional acoustic recording are identified in (Chen et al, 2014) and they show how low cost optical sensors provide more accuracy and high data capacity than previous methods. We hope to build on this work by creating an innovative open source model and associated hardware for conducting research into insect ecosystems.

Insects are vectors of diseases while also pollinating a large proportion of the world’s food production. Further to this, they also constitute a growing food market which is expected to be worth 55 billion dollars by 2023. (Global Market Insight, 2016).

Our aim is to contribute to ongoing research into insect recognition and ecosystems by applying bioacoustics and machine learning to insect recognition and to the democratisation of scientific research by creating an open source, diy and hackable acoustic sensor for identification of various insect species. The final sensor would be non-invasive, weatherproof and wireless and would link to a dashboard, displaying visually the patterns and statistics gathered which could eventually be linked to and open data structure such as wiki data for sharing information about various environments throughout the world. In the first phase of development we will be using already available kits on the market for rapid prototyping and proof of concept. The second step will be creating a custom PCB which would fit all of the necessary components and circuitry. 


# Hardware + Schematics: 

![setup](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/Hardware/setup.jpg)
![breadboard](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/Hardware/breadboard.jpg)
![sensor_pcb](https://github.com/Davincb/DIY-Bioacoustics.Github.io/blob/master/Hardware/sensor_pcb.jpg)

BOM: 

R1 - 5M
R2 - 150k
R3 - 100k
R4, R5 - 1k
R6 - 1M

C1 - 10u

U1 - TLC2902

MISC:
T1 - 10M trimmer
J1 - piezoelectric disc
J2 - 3.5mm jack


# Code and Software:

# License: 

MIT License

Copyright (c) [2017] [Davin Browner Conaty, Minwoo Kim, Filippo Sanzeni, Alice Potts]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


