---
layout: splash
permalink: /my_docs/stage1
author_profile:
comments:
---

<!--- ---------------------------------------------------------------------------------------- ---->
<!--- ---------------------------------------------------------------------------------------- ---->
<font face="Georgia" size="4">
<p align="centre"><h3> O2A: One-shot Observational learning with Action vectors </h3></p>
</font>

<font face="Georgia" size="4">
<h4><b>Abstract: </b> </h4>
<p align="justify">
Results of robotic experiments. 

</a>
</p>
</font>



<!--- ---------------------------------------------------------------------------------------- ---->
<!--- ---------------------------------------------------------------------------------------- ----
<font face="Georgia" size="4">
<h4><b>Abstract: </b> </h4>
<p align="justify">
Observation learning is the process of learning a task by observing an expert demonstrator. Our principal contribution is a one-shot learning method for robot manipulation tasks in which only a single demonstration is required. The key idea is to encode the demonstration in an activity space defined by a previously trained activity classifier. The distance between this encoding and equivalent encodings from trials of a robot performing the same task provides a reward function supporting iterative learning of task completion by the robotic manipulator. We use reinforcement learning for experiments with a simulated robotic manipulator, and stochastic trajectory optimisation for experiments with a real robotic manipulator.
We show that the proposed method can be used to learn tasks from a single demonstration under varying conditions of viewpoints, object properties, morphology of manipulators and scene backgrounds.<a href="https://arxiv.org/abs/1810.07483"> [view paper] </a>
</p>
</font>

<!--- ---------------------------------------------------------------------------------------- ---->
<!--- ---------------------------------------------------------------------------------------- ----
<font face="Georgia" size="4">
<h4><b>Overview: </b> </h4>
<p align="center">
<video width="512" height="320" controls autoplay loop>
  <source src="./../Humanoids_Video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
</p>
</font>

<!--- ---------------------------------------------------------------------------------------- ---->
<!--- ---------------------------------------------------------------------------------------- ---->



<font face="Georgia" size="4">

<h4><b> Reaching a target (Simulation)</b> </h4>
<table style="display:inline-block; border:10px; !important">

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal policy <br> execution - V1</th>
    <th style="text-align:center">Optimal policy <br> execution - Obj1</th>
    <th style="text-align:center">Optimal policy <br> execution - BG</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../demo_reach_0deg_new.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp1.V1.Proposed.r2.e14_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp1.Prop.C1.r2.e02_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp1.prop.B1.r1e19_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>
  </tr>

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal policy <br> execution- V2</th>
    <th style="text-align:center">Optimal policy <br> execution - Obj2</th>
    <th> &emsp; </th>

    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal policy execution- M</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../demo_reach_180deg_new.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp1.prop.v2.r4e16_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp1.prop.C2.r3e07_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

     <th> &emsp; </th>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../demo_reach_0deg_h_s.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>

     </figcaption>
    </figure></td>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp1.Prop.M1.r0e17_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>

     </figcaption>
    </figure></td>
  </tr>
</table>

<!--- ---------------------------------------------------------------------------------------- ---->
<h4><b> Pushing an object (Simulation)</b> </h4>
<table style="display:inline-block; border:10px; !important">

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;</th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal policy <br> execution - V1</th>
    <th style="text-align:center">Optimal policy <br> execution - Obj1</th>

    <th style="text-align:center">Optimal policy execution - BG</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;</th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../Demo_push_0deg.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2.Prop.V1.r3e03_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../E2C1prop.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../E2B0prop.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>
  </tr>

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal policy <br> execution- V2</th>
    <th style="text-align:center">Optimal policy <br> execution - Obj2</th>
    <th> &emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal policy <br> execution- M</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../Demo_push_180deg.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../prop_v1_run0_ep6.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../prop_c2_black.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

     <th> &emsp; </th>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../Demo_push_0deg)huma.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2.Porposed.M1.r3.e14.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>
  </tr>
</table>

<!--- ---------------------------------------------------------------------------------------- ---->

<h4><b> Pushing an object (real robot) </b> </h4>
<table style="display:inline-block; border:10px; !important">

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution - V1</th>
    <th style="text-align:center">Optimal sequence <br> execution - Obj1</th>
    <th style="text-align:center">Optimal sequence <br> execution - BG</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../Demo_real_push_v1.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2V1.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2_C1_0deg_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2BG_new.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>
  </tr>

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution- V2</th>
    <th style="text-align:center">Optimal sequence <br> execution - Obj2</th>
    <th> &emsp; </th>

    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution- M</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../Demo_real_push_v2.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>

     </figcaption>
    </figure></td>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2V2.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2_C2_180deg.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

     <th> &emsp; </th>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../Demo_real_push_v1_human.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>

     </figcaption>
    </figure></td>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2M1.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>

     </figcaption>
    </figure></td>
  </tr>
</table>

<!--- ---------------------------------------------------------------------------------------- ---->

<h4><b> Hammering (real robot) </b> </h4>
<table style="display:inline-block; border:10px; !important">

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution - V1</th>
    <th style="text-align:center">Optimal sequence <br> execution - Obj1</th>
    <th style="text-align:center">Optimal sequence <br> execution - Obj2</th>
    <th style="text-align:center">Optimal sequence <br> execution- M</th>
    <th style="text-align:center">Optimal sequence <br> execution - BG</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../hammer_v1.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp3V1.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp2Obj1_0deg.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp3Obj2_0deg.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp3M1.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp3BG.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


  </tr>

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp; </th>
    <th> &emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution- V2</th>


  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp; </th>
    <th> &emsp; </th>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../hammer_v2.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp3V2.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>



     <th> &emsp; </th>



  </tr>
</table>

<!--- ---------------------------------------------------------------------------------------- ---->

<h4><b> Sweeping (real robot) </b> </h4>
<table style="display:inline-block; border:10px; !important">

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>

    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution - V1</th>
    <th style="text-align:center">Optimal sequence <br> execution - BG</th>
    <th> &emsp;&emsp;&emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution- V2</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../sweep_v1.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp4V1.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp4BG.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../sweep_v2.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp4V2.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>
  </tr>
</table>

<!--- ---------------------------------------------------------------------------------------- ---->

<h4><b> Striking (real robot) </b> </h4>
<table style="display:inline-block; border:10px; !important">

  <tr style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;">
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>

    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution - V1</th>
    <th style="text-align:center">Optimal sequence <br> execution - BG</th>
    <th> &emsp;&emsp;&emsp; </th>
    <th style="text-align:center">Demonstration</th>
    <th style="text-align:center">Optimal sequence <br> execution- V2</th>
  </tr>

  <tr>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>
    <th> &emsp;&emsp;&emsp; </th>
    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <center><img style="display:block" src="./../hitting_v1.gif" style="width:120px;height:120px;" align="middle"></center>
     <figcaption>
     </figcaption>
    </figure></td>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp5V1.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp5BG.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

    <th> &emsp;&emsp;&emsp; </th>

    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../hitting_v2.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>


    <td style="border-bottom: none;padding:25px; border-width:0px; margin:0px;  !important;" align="center"><figure>
     <img src="./../Exp5v2.gif" style="width:120px;height:120px;" align="middle">
     <figcaption>
     </figcaption>
    </figure></td>

  </tr>

</table>

</font>
<!--- ---------------------------------------------------------------------------------------- ---->
<!--- ---------------------------------------------------------------------------------------- ---->
