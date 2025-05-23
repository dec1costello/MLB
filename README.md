<a name="readme-top"></a>
[GitHub](https://github.com/dec1costello) | [Kaggle](https://www.kaggle.com/dec1costello) | [LinkedIn](https://www.linkedin.com/in/declan-costello-7423aa137/)
<br />
Author: Declan Costello
<br />
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dec1costello/MLB)
<br />
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dec1costello/MLB/HEAD)


<p align="center">
<img height="150" width="800" src="https://github.com/user-attachments/assets/21161460-244f-49cd-8c18-a1d7cc9fb5d3"/>  
</p>

<h1 align="center">MLB Analysis</h1>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Objectives">Objectives</a></li>
    <li><a href="#Repo-Structure">Repo Structure</a></li>
       <li><a href="#Dependencies">Dependencies</a></li>
    <li><a href="#EDA">EDA</a></li>
    <li><a href="#Feature-Engineering">Feature Engineering</a></li>
    <li><a href="#Drag-Coefficient">Drag Coefficient</a></li>
      <li><a href="#Future-Roadmap">Future Roadmap</a></li>
  </ol>
</details>

## **Objectives**

Welcome to my analysis of the 2024 MLB Season, the primary objective of this project is to:
> **Provide value to the baseball community!**

I hope to contribute meaningful insights to the baseball community through this project. I encourage you to check out the js visuals on [NBViewer](https://nbviewer.org/github/dec1costello/MLB/tree/main/)!

## **Repo Structure**

This repo is organized as follows:

    📂 TOUR-Championship-Strokes-Gained-Analysis 📍
    │
    ├── README.md 
    ├── requirements.txt
    │
    ├── EDA.ipynb
    ├── FeatureEngineering.ipynb
    └── Drag.ipynb

## **Dependencies**

The [`requirements.txt`](https://github.com/dec1costello/MLB/blob/main/requirements.txt) text file in the root folder has the exact Python environment I used for this project.  
* One can try install Python packages I used with the following command:  

```console
pip install -r requirements.txt
```

## **EDA & Feature Engineering**

Here I explore pybaseball's 2024 data to observe relationships of BBIP.

<div align="center">

<table>
  <tbody>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/4b7f01d6-6e2c-4823-a0a5-8ac15ff42ae0" />
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/197e9b70-7de5-4352-abda-8f41c259ee99" />
      </td>
    </tr>
  </tbody>
</table>

</div>

#### Key Insights

* Along with Pull% and Launch Angle, it was interesting to see how speed off the bat relative to pitch speed can further seperate a batter from the field.


## **Drag Coefficient**

Inspired by ["Simplified Models for the Drag Coefficient of a Pitched Baseball" by David Kagan & Alan M. Nathan](http://baseball.physics.illinois.edu/DragTPTMay2014.pdf), [this notebook](https://nbviewer.org/github/dec1costello/MLB/blob/main/Drag.ipynb) observes how tempurature, humidity, and air pressure affect the drag coefficient of a moving baseball.

<div align="center">

<table>
  <tbody>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/4c07d112-47c7-4fa5-9a1b-249b338a6c9c" />
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/82601909-3f65-4d88-af66-38b260835ed1" />
      </td>
    </tr>
  </tbody>
</table>

</div>

#### Key Insights

* With MLB now mandating humidors to standardize ball quality, Dr. Nathan's research made me wonder whether the league might one day adjust seam height by stadium altitude as another way to level the playing field.


<!-- ROADMAP -->
## **Future Roadmap**

- [ ] TODO
    - [ ] [Pitch sequencing](https://mesa.readthedocs.io/latest/)
    - [ ] Spray by pitch location
    - [ ] Fastball take approach by x axis
     
<p align="right">(<a href="#readme-top">back to top</a>)</p>
