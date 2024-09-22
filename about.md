---
layout: page
title: About
permalink: /about/
---

<style>

.photo{
    display: inline-block; /* Ensure the container is sized to its content */
    text-align: center;
    background-color: white;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1), 0 4px 10px rgba(0, 0, 0, 0.2);
    border: 1px solid #ddd;
    border-radius: 15px;
    padding: 10px; /* Adjusted padding for tighter spacing */
    margin: 10px; /* Added margin for spacing between containers */
}

.photo img {
    width: 128px; /* Set width */
    height: 128px; /* Set height, should be equal to width to make it a circle */
    border-radius: 50%;
    object-fit: cover; /* Ensures the image fits within the dimensions */
}

.photo-table {
    border: hidden !important; /* Remove borders with !important */
    border-collapse: collapse !important; /* Collapse table borders */
    text-align: center;
}

.photo-table td
{
    border: hidden !important; /* Remove borders with !important */
    border-collapse: collapse !important; /* Collapse table borders */
    background-color: #ffffff !important; /* Remove background color */
}

</style>

DARERL provides computer models and computing services to medical device manufacturers, enabling them to incorporate
human variation in their computerized testing and development processes. The core idea behind DARERL's product is to
offer access to a portfolio of multiple foundational mechanistic models for virtual development and testing, a departure
from the industry's current practice of using a single generic model. DARERL's competitive advantage lies in its in-house
software, which allows for faster automated up-scaling of models and statistical analysis on large collections of models.
This innovation moves the industry from single in-silico case studies to comprehensive in-silico clinical trials.
DARERL leverages extensive medical image datasets, expert knowledge of anatomical geometry in neural networks,
finite element analysis, and statistical population analysis.


<h2>The DARERL Team</h2>


<table class="photo-table">
  <tbody>
    <tr>
      
      <td>
        <div class="photo">
            <img width="256px" src="/assets/images/kenny.jpg" alt="Kenny Erleben">
        </div> 
        </td>

        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/sune.jpeg" alt="Sune Darkner">
        </div>
        </td>

        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/sandra_fredmark.jpeg" alt="Sandra Fredmark">
        </div> 
        </td>

    </tr>

    <tr> 
      <td>
        Kenny Erleben
        <br>
        CEO, Founder
        </td>
        <td>
        Sune Darkner
        <br>
        CTO, Founder
        </td>
        <td>
        Sandra Fredmark
        <br>
        VP of Legal
        </td>
    </tr>


    <tr>
        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/sarah_maria_niebe_abel.jpg" alt="Sarah Maria Niebe Abel">
        </div>
        </td>


        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/silas_nyboe_ørting.jpeg" alt="Silas Nyboe Ørting">
        </div>
        </td>

        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/hans_jacob_teglbjærg_stephensen.jpeg" alt="Hans Jacob Teglbjærg Stephensen">
        </div>
        </td>
    </tr>

    <tr>
        <td>
        Sarah Maria Niebe Abel<br>
        Senior Developer, Simulation Sepcialist
        </td>


        <td>
        Silas Nyboe Ørting<br>
        Senior Developer, Medical Image Specialist
        </td>

        <td>
        Hans Jacob Teglbjærg Stephensen
        <br>
        Senior Developer, ML & AI Specialist 
        </td>
    </tr>

  </tbody>
</table>



<h2>Our Advisory Board</h2>

<table class="photo-table">
  <tbody>
    <tr>

        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/karsten_bo_rasmussen.jpeg" alt="Karsten Bo Rasmussen">
        </div> 
        </td>
        
        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/enrique_morales_orcajo.jpg" alt="enrique_morales_orcajo">
        </div>
        </td>

        <td>
        <div class="photo">
            <img width="256px" src="/assets/images/michael_bachmann_nielsen.jpeg" alt="Michael Bachmann Nielsen, Professor of Radiology">
        </div>
        </td>

    </tr>

    <tr>

        <td>
        Karsten Bo Rasmussen<br>
        Industry Advisor<br>
        Hearing Aid Industry Opinion Leader
        </td>
        
        <td>
        Enrique Morales Orcajo<br>
        Technology Advisor<br>
        In Silico Medicine Opinion Leader
        </td>

        <td>
        Michael Bachmann Nielsen<br>
        Clinical Advisor<br>
        Professor of Radiology
        </td>

    </tr>

</tbody>
</table>

<h2>The need for Digitalizing Clinical Trials</h2>

Developing and testing new medical devices traditionally involves costly and time-consuming incremental tests of
physical prototypes. These tests carry a high risk of delays or unsuccessful regulatory approval. In
the conventional approach, each prototype must be built and tested sequentially in the real world, with each
experiment needing to be completed before the next can begin. DARERL transforms this process for our customers. Our
virtual solution enables testing on large populations of digital human models, bypassing real-world bottlenecks
and providing enhanced statistical analysis.

<h2>The History of DARERL</h2>

DARERL ApS was founded as a start-up company by Professor Kenny Erleben and Professor Sune Darkner from the University of Copenhagen.
The company emerged in connection with the EU RIA project, [Intelligent Robotic Endoscopes for Improved Healthcare Services (IRE)](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/org-details/999999999/project/101135082/program/43108390/details), funded under HORIZON-CL4-2023-DIGITAL-EMERGING-01.

The technology behind DARERL was originally published
and open-sourced under the Horizon 2020 project [RAINBOW](https://rainbow.ku.dk/),
which concluded on 31/03/2022.
The [European Commission Innovation Radar](https://innovation-radar.ec.europa.eu/innovation/35799) analyzed this innovation based on data
collected on 11/11/2019.
The JRC’s Market Creation Potential indicator framework assessed the innovation
as addressing the needs of existing markets and customers.

Early versions of DARERL's Digital Twin Technology were applied to [orthodontics](https://di.ku.dk/english/news/2024/straightening-teeth-ai-can-help/) and [orthopedic](https://di.ku.dk/english/news/2022/diku-creates-digital-twins-of-the-future/) use cases.
Our technology has produced some of the highest quality publicly available digital populations, such as [LibHip](https://github.com/diku-dk/libhip) and [Open-Full-Jaw](https://github.com/diku-dk/Open-Full-Jaw). 
Since 2019, the technology has matured, and as of 2024, it can handle more cases, including [virtual kidneys](https://github.com/diku-dk/RenalVesselSeg) and [colons](https://ire4health.eu).


DARERL technology has been tested and documented through a series of scientific [publications](pubs.md).
