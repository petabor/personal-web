---
layout: page
title: Projects
sidebar_order: 7
---

<p>&nbsp;&nbsp;&nbsp;</p>

<div class="toc-box">
  <strong>Contents</strong>
  <ul class="toc-list">
    <li><a href="#work-projects">Work-Related Projects</a>
      <ul>
        <li><a href="#faces-scenes">Faces in Scenes – Eye-Tracking Analysis</a></li>
        <li><a href="#gaze-neural">Individual Gaze Shapes – fMRI Analysis</a></li>
      </ul>
    </li>
    <li><a href="#other-projects">Other Projects</a></li>
    <li><a href="#personal-projects">Personal Projects</a>
      <ul>
        <li><a href="#conflicts-figures">Conflicts in Figures</a></li>
      </ul>
    </li>
  </ul>
</div>

<p>&nbsp;&nbsp;&nbsp;</p>

<h2 id='work-projects'>Work-Related Projects</h2>

<h3 id="faces-scenes">1. Faces in Scenes – Eye-Tracking Analysis</h3>

<strong>Source:</strong> <em><a href="https://jov.arvojournals.org/article.aspx?articleid=2791381" target="_blank">Faces in Scenes Attract Rapid Saccades (Borovská & de Haas, 2022)</a></em>

* <strong>Goal:</strong> To investigate how faces in complex visual scenes influence eye movements.
* <strong>Method:</strong> Eye-tracking (n = 101); comparison of saccade parameters for face versus object targets; statistical analysis using MATLAB (linear mixed-effects models [LMM], ANOVAs).
* <strong>Result:</strong> Faces elicit <strong>faster saccades</strong> with preceding fixation of <strong>shorter duration</strong>, a pattern that taps into visual attention mechanisms.

<h5>Summary:</h5>
In this project, we investigated <strong>how free-viewing dynamics vary as a function of an upcoming fixation target while controlling for various low-level factors </strong> (e.g. target size or onset time). We compared <strong>saccade velocity</strong> and preceding <strong>fixation duration</strong> of saccades directed toward faces versus inanimate objects and analyzed data from 101 participants free-viewing 700 complex everyday scenes. Given the complexity of gaze behavior during free-view, we used linear mixed-effects models (LMM) to measure both saccade velocity and preceding fixation duration while controlling for several oculomotor and low-level factors <em>((1) target saccade amplitude, (2) incoming saccade amplitude, (3) size of target stimuli, (4) time from onset of the trial, (5) angle of the target to incoming amplitude, (6) GBVS at the intermediate fixation, and (7) GBVS at the target fixation)</em>. 

<h5>Key findings:</h5>
By contrasting fixations landing on <em>faces</em> versus neutral <em>objects</em>, we confirmed that <strong>saccade velocity towards faces was higher as compared to other objects and the duration of the preceding fixation is shorter when faces are the upcoming targets</strong>, mainly if the face target is close. These findings suggest that the dynamics of gaze behavior during free-viewing of complex scenes are modulated by several interacting factors which should be considered in the study of natural vision.

<h5>Contribution:</h5>
Developed an algorithm for the identification of a particular gaze sequence (fixation-saccade-fixation), with the last fixation landing either on an object or on a face. Identified important modulators for this type of gaze sequence and customized image masks for labelling different semantic categories. Authored the manuscript and interpreted findings in the context of current research.

<p>&nbsp;&nbsp;</p>

<div class='im_text'>
  <div class='image'>
    <img src="{{ '/assets/images/projects/paper1_illust.png' | relative_url }}" width="300">
  </div>
  <div class='text'>
    <p><strong>Figure 1.</strong>This figure shows the pattern of eye movements (saccades) while viewing a scene. 
       Color-coded lines and circles indicate fixations and saccades directed either toward an object (blue) or a face (orange).</p>  
  </div>
</div>

<p>&nbsp;&nbsp;</p>

<div class='im_row'>
  <img src="{{ '/assets/images/projects/paper1_veloc.png' | relative_url }}" width="400">
  <img src="{{ '/assets/images/projects/paper1_fixdur.png' | relative_url }}" width="400">
</div>


<div class='cls_text'>
  <div class='text'>
    <p><strong>Figure 2.</strong> Results of a linear mixed-effects model (LMM): Saccades directed toward faces exhibit higher peak velocities than those directed toward objects.</p>
  </div>
  <div class='text'>
    <p><strong>Figure 3.</strong>This analysis shows that fixations preceding saccades toward faces tend to be shorter. This suggests that faces attract attention more quickly and efficiently than other objects.</p>  
  </div>
</div>

<h3 id="gaze-neural">2. Individual Gaze Shapes Neural Representations – fMRI Analysis</h3>

<strong>Source:</strong> <em><a href="https://www.pnas.org/doi/10.1073/pnas.2405602121" target="_blank">Individual Gaze Shapes Diverging Neural Representations (Borovská & de Haas, 2023)</a></em>

* <strong>Goal:</strong> To explore the relationship between individual eye movement patterns and neural activation (fMRI + eye tracking).
* <strong>Method:</strong> Development of a data pipeline; processing of eye-tracking and fMRI data; analysis using Python and MATLAB; correlation of gaze parameters with brain activity ( neural representations).
* <strong>Result:</strong> Individual differences in gaze behavior lead to distinct neural representations—an example of complex, multimodal data analysis.
* <strong>Relevance:</strong> Demonstrates my experience with large, heterogeneous datasets and with combining technical and analytical approaches.

<h5>Summary:</h5>
This study tested the hypothesis that <strong>individually diverging neural representations can be explained by idiosyncrasies in gaze upon viewing identical complex dynamic stimuli</strong>. In particular, we focused on differences in <em>the average Euclidean distance between gaze positions, the tendency to fixate on face and text, and the differences in saccade amplitude and rate.</em> To test this prediction, we used a machine learning technique, <strong>hyperalignment</strong> (Haxby et al. 2011), and derived a <em>cross-brain accuracy</em> used as a proxy for representational similarity between pairs of observers. Participants completed two sessions, one with eye-tracking and one during fMRI, under both fixation and free-viewing conditions.

<h5>Key findings:</h5>
Free viewing increased brain activity (i.e. BOLD signal amplitude) but produced <strong><em>representational divergence</em></strong> in primary (V1) and inferior-temporal (IT) cortex.
Observer pairs with more dissimilar gaze patterns showed greater neural divergence, indicating that gaze matters for neural representations. Specifically, pairwise differences in the <em>spatial distribution</em> of gaze and <em>semantic salience</em> contribute to neural divergence in IT.

<h5>Contribution:</h5>
Developed and implemented a customized hyperalignment algorithm, showing that functional layout can be overcome by using this technique. Created pre-processing pipelines supporting hyperalignment(e.g. voxel selection or nuisance regression) and cortical-surface visualizations. Authored the manuscript and interpreted findings in the context of current research.  


<p>&nbsp;&nbsp;</p>

<strong>Gaze divergence is reflected by brain divergence when viewing identical movie stimuli</strong>

<div class='im_row'>
  <img src="{{ '/assets/images/projects/paper2_illust_gaze.png' | relative_url }}" width="400">
  <img src="{{ '/assets/images/projects/paper2_illust_brain.png' | relative_url }}" width="400">
</div>

<p>&nbsp;&nbsp;</p>

<div class='im_text2'>
  <div class='image'>
    <img src="{{ '/assets/images/projects/paper2_panel.png' | relative_url }}">
  </div>
  <div class='text'>
    <p><strong>Panel A:</strong> During free viewing, neural activations are stronger but more idiosyncratic. 
    The cross-brain decoding accuracy decreases during free-view.</p>
    <p><strong>Panel B:</strong> Differences in gaze position and in the tendency to fixate on faces and text predict the magnitude of this neural divergence.</p>
    <p><strong>Panels C & D:</strong> Cortical surface maps show the visual areas (e.g., V1 and IT) where these differences occur.</p>  
  </div>
</div>

<h2 id="other-projects">Other Projects [Unpublished / In Progress]</h2>

* <strong>The effect of spatial frequency on blink rate in a naturalistic environment</strong><br>
Investigating how blink frequency varies with the spatial-frequency content of naturalistic scenes and whether blinks reflect spatial content variation also during navigating real-world environment with use of mobile eye tracking. Analyses employ Fourier decomposition of naturalistic scenes and decomposition of image frames preceding blink events.  

* <strong>The influence of saccade kinetics on memorability of complex scenes</strong><br>
Examining whether the execution of saccades immediately prior to image onset enhances subsequent memorability compared to images preceded by fixation.

* <strong>Eye movements and memorability</strong><br>
Investigating how eye-movement dynamics, particularly saccadic rate, facilitate memorability of complex images. Assessing how distinct saccade types—detection, return, and inspection saccades, each with different functional roles—contribute to memory encoding in naturalistic viewing.

* <strong>The relationship between microsaccades and saccades in complex images and videos</strong><br>
Exploring the relationship between microsaccades and larger saccades during viewing of complex images and videos, adapting existing detection algorithms to naturalistic data.

* <strong>Mind wandering and fixation dynamics</strong><br>
Conducting exploratory analyses on the link between mind wandering and fixation duration, testing the hypothesis that mind wandering (operationalized as localization error for last-seen positions) is associated with longer fixations compared to attentive viewing.  


<h2 id="personal-projects">Personal Projects</h2>

<h3 id="conflicts-figures">Conflicts in Figures – Visualization of Conflict Data</h3>

<strong>Source:</strong> <a href="https://petabor.github.io/conflicts-in-figures/" target="_blank">Conflicts-in-figures</a>

* <strong>Goal:</strong> Development of an interactive website for analyzing and visualizing international conflict data.
* <strong>Method:</strong> Data preparation using Python (pandas); design of visualizations; web development in HTML/CSS/JavaScript.
* <strong>Description:</strong> The project Conflicts in Figures presents open-source conflict data through interactive temporal and spatial visualizations. Its aim is to make complex relationships between regions, timelines, and casualty numbers intuitively understandable.
* <strong>Relevance:</strong> The project combines technical implementation with analytical thinking, presenting data through interactive visualization—similar in concept to data visualization tools used in research and digital analytics.

<p>&nbsp;&nbsp;</p>

<div class='im_text3'>
  <div class='image'>
    <img src="{{ '/assets/images/projects/total_nr_deaths_2023.png' | relative_url }}">
  </div>
  <div class='text'>
    <p><strong>Global Distribution of Conflict Fatalities (2023)</strong><br> A map shows the number of recorded deaths caused by armed conflicts in 2023. Darker shades indicate higher casualty numbers, making regional hotspots immediately visible.</p>
  </div>
</div>

<p>&nbsp;&nbsp;</p>

<div class='im_row'>
  <img src="{{ '/assets/images/projects/cumul_continents.png' | relative_url }}" width="400">
  <img src="{{ '/assets/images/projects/forecast.png' | relative_url }}" width="400">
</div>

<div class='cls_text2'>
  <div class='text'>
    <p><strong>Long-Term Trends Across Continents (1989–2023)</strong><br>A cumulative trend analysis illustrates how the total number of casualties has evolved across continents. It highlights significant increases in certain regions and long-term shifts in the global pattern of conflict.</p>
  </div>
  <div class='text'>
    <p><strong>Forecast of Future Fatalities in Europe</strong><br>A time-series analysis with trend modeling and confidence intervals visualizes possible future developments based on historical data.</p>  
  </div>
</div>