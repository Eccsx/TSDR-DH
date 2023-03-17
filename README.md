<div id="top"></div>

<div align="center">
    <a href="https://github.com/Eccsx/TSDR-Dataset-Hub">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/France_road_sign_A2b.svg/2326px-France_road_sign_A2b.svg.png" alt="Logo" height="80">
    </a>
    <h3 align="center">Traffic Sign Detection and Recognition</h3>
    <p align="center">
        Dataset Hub
    </p>
</div>



<!-- ABOUT THE PROJECT -->

## About

For my end-of-studies internship as a computer science engineering student, I joined the [Astek Innovation Lab](https://astekgroup.fr/innovation/) in Paris (France) for a research subject about the detection and classification of traffic signs.

While searching and reading publications, I noticed two things. There are a lot of public datasets with multiples specifications and for different tasks. But no easy way to search through them and choose which one to use.

That's why I decided to create the repository, with the idea of offering a single place to display all the information related to traffic sign datasets.

<p align="right"><a href="#top"><i>back to top</i></a></p>

<!-- METHODOLOGY -->

## Methodology

For a dataset to be displayed in this repository, it must fit the following requirements:

- Designed for traffic sign detection and/or recognition
- Introduced and described within a publication
- Contains more than several dozen images
- Named by its original authors or the scientific community

About the characteristics of each dataset, I refer to the original articles and showcase websites if such exist.

<p align="right"><a href="#top"><i>back to top</i></a></p>

<!-- DATA -->

## Data

Each dataset is checked for the following features:

- **year** — Year of the data publication
- **origin** — Origin of the data (*e.g.* country, other dataset)
- **name** — Name of the dataset
- **task** — Purpose of the dataset (detection, classification)
- **type** — Type of the data (images, video sequences)
- **instance** — Number of instances
- **class** — Number of traffic sign classes
- **kind** — Data's kind (real, synthetic)
- **weather** — Weather conditions among the data
- **alteration** — Alteration among the traffic signs
- **artifact** — Visual aterfacts among the data

<p align="right"><a href="#top"><i>back to top</i></a></p>

<!-- DATASETS -->

<div id="datasets"></div>

## Datasets

<table style="text-align: center">
 <colgroup><col>
 </colgroup><tbody><tr>
  <td rowspan="2">year</td>
  <td rowspan="2">origin</td>
  <td rowspan="2">name</td>
  <td colspan="2">tasks</td>
  <td colspan="2">type</td>
  <td rowspan="2">instances</td>
  <td rowspan="2">classes</td></td>
  <td colspan="2">kind</td>
  <td colspan="6">weather</td>
  <td colspan="4">alterations</td>
  <td colspan="5">artifacts</td>
 </tr>
 <tr>
  <td>detection</td>
  <td>classfication</td>
  <td>image</td>
  <td>video</td>
  <td>real</td>
  <td>synthetic</td>
  <td>day</td>
  <td>night</td>
  <td>rain</td>
  <td>snow</td>
  <td>haze</td>
  <td>fog</td>
  <td>occlusion</td>
  <td>faded color</td>
  <td>damage</td>
  <td>illumination</td>
  <td>blur</td>
  <td>noise</td>
  <td>codec</td>
  <td>vibration</td>
  <td>glare</td>
 </tr>
 <tr>
  <td>2003</td>
  <td>Netherlands</td>
  <td><a href="#rugtsd">RUGTSD</a></td>
  <td>✓</td> <!-- detection -->
  <td>✗</td> <!-- classifcation -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>48</td> <!-- instances -->
  <td>3</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthethic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- nigth -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✗</td> <!-- occlusion -->
  <td>✗</td> <!-- faded color -->
  <td>✗</td> <!-- damage -->
  <td>✗</td> <!-- illumination -->
  <td>✗</td> <!-- blur -->
  <td>✗</td> <!-- noise -->
  <td>✗</td> <!-- codec -->
  <td>✗</td> <!-- vibration -->
  <td>✗</td> <!-- glare -->
</tr>
<tr>
  <td>2008</td>
  <td>Sweden</td>
  <td><a href="#ftsd">FTSD</a></td>
  <td>✓</td> <!-- detection -->
  <td>✗</td> <!-- classifcation -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>3,415</td> <!-- instances -->
  <td>17</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthethic -->
  <td>✓</td> <!-- day -->
  <td>✓</td> <!-- nigth -->
  <td>✓</td> <!-- rain -->
  <td>✓</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✓</td> <!-- fog -->
  <td>✓</td> <!-- occlusion -->
  <td>✓</td> <!-- faded color -->
  <td>✓</td> <!-- damage -->
  <td>✓</td> <!-- illumination -->
  <td>✓</td> <!-- blur -->
  <td>✓</td> <!-- noise -->
  <td>✗</td> <!-- codec -->
  <td>✗</td> <!-- vibration -->
  <td>✗</td> <!-- glare -->
</tr>
<tr>
  <td>2010</td>
  <td>France</td>
  <td><a href="#stereopolis">Stereopolis</a></td>
  <td>✓</td> <!-- detection -->
  <td>✗</td> <!-- classifcation -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>847</td> <!-- instances -->
  <td>4</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthethic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- nigth -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✗</td> <!-- occlusion -->
  <td>✗</td> <!-- faded color -->
  <td>✗</td> <!-- damage -->
  <td>✗</td> <!-- illumination -->
  <td>✗</td> <!-- blur -->
  <td>✗</td> <!-- noise -->
  <td>✗</td> <!-- codec -->
  <td>✗</td> <!-- vibration -->
  <td>✗</td> <!-- glare -->
 </tr>
</tbody></table>



<p align="right"><a href="#top"><i>back to top</i></a></p>

<h3 id="rugtsd">RUG Traffic Sign Image Database</h3>

> C. Grigorescu and N. Petkov, "Distance sets for shape filters and shape recognition," in *IEEE Transactions on Image Processing*, vol. 12, no. 10, pp. 1274-1286, Oct. 2003, doi: 10.1109/TIP.2003.816010.

License ➔ *n/a*

Link ➔ http://www.cs.rug.nl/~imaging

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="ftsd">Fleyeh Traffic Signs Database</h3>

> Fleyeh, H. (2008). Traffic and Road Sign Recognition.

License ➔ *n/a*

Link ➔ http://users.du.se/~hfl/traffic_signs/

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="stereopolis">Stereopolis</h3>

> R. Belaroussi, P. Foucher, J. -P. Tarel, B. Soheilian, P. Charbonnier and N. Paparoditis, "Road Sign Detection in Images: A Case Study," 2010 20th International Conference on Pattern Recognition, Istanbul, Turkey, 2010, pp. 484-488, doi: 10.1109/ICPR.2010.1125.

License ➔ *n/a*

Link ➔ *n/a*

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>
