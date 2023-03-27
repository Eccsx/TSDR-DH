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
- **artifact** — Visual artifacts among the data

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
  <td>✗</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>48</td> <!-- instances -->
  <td>3</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
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
  <td>✗</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>3,415</td> <!-- instances -->
  <td>17</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✓</td> <!-- night -->
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
  <td>✗</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>847</td> <!-- instances -->
  <td>4</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
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
  <td>2011</td>
  <td>Croatia</td>
  <td><a href="#mastif">MASTIF</a></td>
  <td>✗</td> <!-- detection -->
  <td>✓</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✓</td> <!-- video -->
  <td>11,000 ~</td> <!-- instances -->
  <td>7</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✓</td> <!-- occlusion -->
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
  <td>2011</td>
  <td>Sweden</td>
  <td><a href="#stsd">STSD</a></td>
  <td>✓</td> <!-- detection -->
  <td>✓</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>20,000 +</td> <!-- instances -->
  <td>7</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✓</td> <!-- occlusion -->
  <td>✗</td> <!-- faded color -->
  <td>✗</td> <!-- damage -->
  <td>✗</td> <!-- illumination -->
  <td>✓</td> <!-- blur -->
  <td>✗</td> <!-- noise -->
  <td>✗</td> <!-- codec -->
  <td>✗</td> <!-- vibration -->
  <td>✗</td> <!-- glare -->
</tr>
<tr>
  <td>2012</td>
  <td>U.S.A</td>
  <td><a href="#lisa">LISA</a></td>
  <td>✓</td> <!-- detection -->
  <td>✓</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✓</td> <!-- video -->
  <td>6,610</td> <!-- instances -->
  <td>49</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✓</td> <!-- occlusion -->
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
  <td>2016</td>
  <td>Italy</td>
  <td><a href="#dits">DITS</a></td>
  <td>✓</td> <!-- detection -->
  <td>✓</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>11,141</td> <!-- instances -->
  <td>58</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✓</td> <!-- night -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✓</td> <!-- fog -->
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
<tr>
  <td>2016</td>
  <td>Russia</td>
  <td><a href="#rtsd">RTSD</a></td>
  <td>✓</td> <!-- detection -->
  <td>✓</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>179,138</td> <!-- instances -->
  <td>156</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✓</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
  <td>✓</td> <!-- rain -->
  <td>✓</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✗</td> <!-- occlusion -->
  <td>✗</td> <!-- faded color -->
  <td>✗</td> <!-- damage -->
  <td>✓</td> <!-- illumination -->
  <td>✗</td> <!-- blur -->
  <td>✗</td> <!-- noise -->
  <td>✗</td> <!-- codec -->
  <td>✗</td> <!-- vibration -->
  <td>✓</td> <!-- glare -->
 </tr>
<tr>
  <td>2019</td>
  <td>Slovenia</td>
  <td><a href="#dfg">DFG</a></td>
  <td>✓</td> <!-- detection -->
  <td>✗</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>6,757</td> <!-- instances -->
  <td>200</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
  <td>✗</td> <!-- rain -->
  <td>✗</td> <!-- snow -->
  <td>✗</td> <!-- haze -->
  <td>✗</td> <!-- fog -->
  <td>✓</td> <!-- occlusion -->
  <td>✗</td> <!-- faded color -->
  <td>✗</td> <!-- damage -->
  <td>✓</td> <!-- illumination -->
  <td>✗</td> <!-- blur -->
  <td>✗</td> <!-- noise -->
  <td>✗</td> <!-- codec -->
  <td>✗</td> <!-- vibration -->
  <td>✗</td> <!-- glare -->
 </tr>
<tr>
  <td>2022</td>
  <td>U.S.A</td>
  <td><a href="#glare">GLARE</a></td>
  <td>✓</td> <!-- detection -->
  <td>✓</td> <!-- classification -->
  <td>✓</td> <!-- image -->
  <td>✗</td> <!-- video -->
  <td>2,157</td> <!-- instances -->
  <td>41</td> <!-- classes -->
  <td>✓</td> <!-- real -->
  <td>✗</td> <!-- synthetic -->
  <td>✓</td> <!-- day -->
  <td>✗</td> <!-- night -->
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
  <td>✓</td> <!-- glare -->
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

<h3 id="mastif">MASTIF Traffic Signs</h3>

> Segvic, Sinisa & Brkić, Karla & Kalafatic, Zoran & Pinz, Axel. (2014). Exploiting temporal and spatial constraints in traffic sign detection from a moving vehicle. Machine Vision and Applications. 25. 10.1007/s00138-011-0396-y. 
>
> Segvic, Sinisa & Brkić, Karla & Kalafatic, Zoran & Stanisavljević, Vladimir & Ševrović, Marko & Budimir, Damir & Dadić, I.. (2010). A computer vision assisted geoinformation inventory for traffic infrastructure. 66 - 73. 10.1109/ITSC.2010.5624979.
>
> Bonači, I., Kusalić, Ivan, Kovaček, Ivan, Kalafatić, Z. & Šegvić, S. (2011) Addressing false alarms and localization inaccuracy in traffic sign detection and recognition. In: Wendel, A., Sternig, S. & Godec, M. (ed.)Proceedings of the Computer Vision Winter Workshop.
>
> Brkić, K., Pinz, A., Šegvić, S. & Kalafatić, Z. (2011) Histogram-Based Description of Local Space-Time Appearance. Lecture Notes in Computer Science, 6688, 206-217 doi:10.1007/978-3-642-21227-7_20.

License ➔ *n/a*

Link ➔ http://www.zemris.fer.hr/~ssegvic/mastif/datasets.shtml

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="stsd">Swedish Traffic Signs Dataset</h3>

> Fredrik Larsson and Michael Felsberg , Using Fourier Descriptors and Spatial Models for Traffic Sign Recognition , In Proceedings of the 17th Scandinavian Conference on Image Analysis, SCIA 2011, LNCS 6688, pp. 238-249. bib , doi:10.1007/978-3-642-21227-7_23
>
> Fredrik Larsson, Michael Felsberg, and Per-Erik Forssen , Correlating Fourier descriptors of local patches for road sign recognition , IET Computer Vision, 5(4): 244-254, 2011. bib , doi:10.1049/iet-cvi.2010.0040

License ➔ *n/a*

Link ➔ https://www.cvl.isy.liu.se/research/datasets/traffic-signs-dataset/

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="lisa">LISA Traffic Sign Dataset</h3>

> Andreas Møgelmose, Mohan M. Trivedi, and Thomas B. Moeslund, "Vision based Traffic Sign Detection and Analysis for Intelligent Driver Assistance Systems: Perspectives and Survey," IEEE Transactions on Intelligent Transportation Systems, 2012.

License ➔ Academic License Agreement

Link ➔ http://cvrr-nas.ucsd.edu/LISA/lisa-traffic-sign-dataset.html

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="dits">Data set of Italian Traffic Signs</h3>

> Youssef, Ali & Albani, Dario & Nardi, Daniele & Bloisi, Domenico. (2016). Fast Traffic Sign Recognition Using Color Segmentation and Deep Convolutional Networks. 10016. 10.1007/978-3-319-48680-2_19.

License ➔ *n/a*

Link ➔ http://www.diag.uniroma1.it/~bloisi/ds/dits.html

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="rtsd">Russian Traffic Sign images Dataset</h3>

> Shakhuro, V.I. & Konushin, Anton. (2016). Russian traffic sign images dataset. Computer Optics. 40. 294-300. 10.18287/2412-6179-2016-40-2-294-300. 

License ➔ *n/a*

Link ➔ https://graphics.cs.msu.ru/projects/traffic-sign-recognition.html

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="dfg">DFG Traffic Sign Dataset</h3>

> D. Tabernik and D. Skočaj, "Deep Learning for Large-Scale Traffic-Sign Detection and Recognition," in IEEE Transactions on Intelligent Transportation Systems, vol. 21, no. 4, pp. 1427-1440, April 2020, doi: 10.1109/TITS.2019.2913588.

License ➔ Attribution-NonCommercial-ShareAlike 4.0 International

Link ➔ https://www.vicos.si/resources/dfg/

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>

<h3 id="glare">GLARE</h3>

> Gray, Nicholas & Moraes, Megan & Bian, Jiang & Tian, Allen & Wang, Alex & Xiong, Haoyi & Guo, Zhishan. (2022). GLARE: A Dataset for Traffic Sign Detection in Sun Glare.

License ➔ Creative Commons Attribution 4.0 International Public License

Link ➔ https://github.com/NicholasCG/GLARE_Dataset

<p align="right"><a href="#datasets"><i>back to datasets</i></a></p>