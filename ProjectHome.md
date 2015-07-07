# EPFL Dataset #
The original video comes from [CVLAB website](http://cvlab.epfl.ch/data/pom/). This dataset consists of 5 different scenarios that are filmed by three or four cameras from different angles. We extract individuals from the original videos and annotate each of them with ID and location (bounding box). Besides, we also annotate the body part configurations for each query instance.

In total, there are 70 reference images for 30 different individuals, (normalized to 175 pixels in height), and 80 shots in 360 x 288, which contain 294 targets to be re-identified.


## Examples ##
<img src='http://human-reid-dataset.googlecode.com/files/EPFL-Example.png' width='600px'>


<h2>Naming Rules</h2>
For a query instance image "S00102045.png", "001" denotes the video scenario number, "02" denotes the individual number in this scenario. "S00102" can represent the unique individual ID in the whole dataset, and "045" denotes the person view of this instance (45 degree).<br>
<br>
For a video shot image "G001-03.png", "001" denotes the video scenario number, and "03" denotes the video shot number.<br>
<br>
For a target individual image "G001-03_S00102.png", "G001-03" denotes the video shot ID, and "S00102" denotes the individual ID groundtruth.<br>
<br>
<br>
<h2>Downloads</h2>
<a href='https://bitbucket.org/merayxu/person-re-id-datasets/downloads/EPFL.zip'>EPFL</a>



<h1>CAMPUS-Human Dataset</h1>
This database includes general and realistic challenges for people re-identification in surveillance. We record videos using 3 cameras from different views and extract individuals as well as video shots within the videos. We also annotate the body part configurations for each query instance and annotate ID and locations (bounding box) for each video shot.<br>
<br>
In total, there are 370 reference images (normalized to 175 pixels in height), for 74 individuals, with IDs and locations provided. We extract 214 shots (640 x 360) containing 1519 target individuals. Note that the targets often appear with diverse poses/views or occluded by other people within the scenarios.<br>
<br>
<br>
<h2>Examples</h2>
<img src='http://human-reid-dataset.googlecode.com/files/CAMPUS-Human-Example.png' width='600px'>


<h2>Naming Rules</h2>
Following the same naming rules as EPFL dataset.<br>
<br>
<h2>Downloads</h2>
<a href='https://bitbucket.org/merayxu/person-re-id-datasets/downloads/CAMPUS-Human.zip'>CAMPUS-Human</a>