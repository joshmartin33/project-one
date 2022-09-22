<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/joshmartin33/project-one.git">
    <img src="images/logo.png" alt="Logo" width="80" height="70">
  </a>

<h3 align="center">Project-1</h3>

  <p align="center">
    Victorian education related to population density
    <br />
    <a href="https://github.com/joshmartin33/project-one.git"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/joshmartin33/project-one/blob/main/analysis.ipynb">View Analysis</a>
    ·
    <a href="https://github.com/joshmartin33/project-one/issues">Report Bug</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#research-questions">Research Questions</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#creators">Creators</a></li>
    <li><a href="#citing-and-referencing">Citing and Referencing</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


We are seeking to research how population density affects the education industry within Victoria. Analyzing what options exist within more rural areas compared to dense urbanized areas. We will utilize the google api to create a heatmap to describe the success of high ranking highschool as create a heatmap displaying the amount of schools in victoria. Our hope is to illustrate how more urbanized and densely populated areas have more access to more options and possibly more effective resources. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Research Questions -->
## Research Questions


* Is there a relationship with Geolocation and academic success?

* Is there a relationship with Geolocation and the choices of schools?

* Which school sector has best chance of success?

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Installation

1. Get an API Key at [https://mapsplatform.google.com/](https://mapsplatform.google.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/joshmartin33/project-one.git
   ```
3. Install gmaps packages [https://jupyter-gmaps.readthedocs.io/en/latest/install.html/](https://jupyter-gmaps.readthedocs.io/en/latest/install.html)
   ```sh
   $ pip install gmaps
   ```
4. Create `api_keys.py` file in the same folder location as `analysis.ipynb`
   ```js
   api_keys.py
   ```
5. Enter your API in `api_keys.py`
   ```js
   g_key = "YOUR KEY HERE"
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Creators -->
## Creators

Josh Martin - [https://github.com/joshmartin33](https://github.com/joshmartin33)

Ryan Peregrin - [https://github.com/PJRyn](https://github.com/PJRyn)

Udeshi Pereira - [https://github.com/Shaloomi](https://github.com/Shaloomi)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Citing and Referencing -->
## Citing and Referencing

* School Data Victoria - SearchResults.xlsx. (2022). Retrieved from [https://asl.acara.edu.au/School-Search?state=VIC](https://asl.acara.edu.au/School-Search?state=VIC)

* VCE Results Data Victoria - 2021SeniorSecondaryCompletionAndAchievementInformation.xlsx. (2021.) Retrieved from [https://www.vcaa.vic.edu.au/administration/research-and-statistics/Pages/SeniorSecondaryCompletion.aspx](https://www.vcaa.vic.edu.au/administration/research-and-statistics/Pages/SeniorSecondaryCompletion.aspx)

* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>