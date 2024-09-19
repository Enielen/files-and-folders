# Part I - Welcome to File Naming & Folder Organization

### 1a. Learning Objectives & Purpose

This mini module is an opportunity for self-paced, independent learning in several core skills. During class, your instructors will expand upon the module topics and will show you how to apply the skills to much more complex problems in your field of study. The learning in this mini-module will equip you to do the following: 

- Recognise the importance of file and folder organisation and relate it to your studies.

- Use appropriate naming conventions to manage project files systemically.

- Structure folders effectively to make elements of a research project findable for collaborators and for your future self.

- Explain the concept of a directory tree. 

- Evaluate whether to store a file locally vs. remotely based on factors such as accessibility, security, and collaboration needs.

### 1b. Pre-quiz

Before we begin, please take this short pre-quiz (5 questions). The purpose is to evaluate your background knowledge and see which concepts will be new vs. review for you.

<style>
.responsive-iframe {
    position: relative;
    width: 100%;
    overflow: hidden;
    padding-top: 58.5%; /* Adjust this value based on the aspect ratio (height/width * 100) */
}
.responsive-iframe iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>

<div class="responsive-iframe">
    <iframe src="https://tudelft.h5p.com/content/1292336851439686927/embed" aria-label="Pre quiz" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>


### 1c. Relevance:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Why should we care about file naming & folder organisation?
  </div>
</center>

<br>


<style>
  td.image-cell {
    width: 30%; /* Sets the image cell to 30% of the table width */
    vertical-align: top; /* Aligns the image to the top */
  }

  td.text-cell {
    width: 70%; /* Sets the text cell to 70% of the table width */
    vertical-align: top; /* Aligns the text to the top */
    padding-left: 50px; /* Optional: Adds some spacing between image and text */
  }

  img {
    width: 100%; /* Ensures the image fills the 30% width of its cell */
    height: auto; /* Maintains the aspect ratio of the image */
    display: block;
  }
</style>

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/1Ca_research_insights.png" alt="Research insights" />
      <p style="font-size: x-small;"><em>"Research insights" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <h3>INSIGHTS INTO YOUR RESEARCH PROCESS</h3>
      <p>Ideally, files are named and organised in a way that helps document the process or sequence that you followed to gather the data. File names should provide hints about why/how each piece is relevant. Effective file naming and documentation of file naming schema makes it easier to retrace your steps in a project when it’s time to analyse your results.</p>
    </td>
  </tr>
</table>


<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/1Cb_file_finding.png" alt="File Finding" style="width: 500px;"/>
      <p style="font-size: x-small;"><em>"File finding" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <h3>INCREASED EFFICIENCY</h3>
      <p>It’s no fun hunting frantically for that one specific piece of information that you collected last month: spending a little time upfront to organise your files increases their findability. This can save you a lot of time (and lower your stress level) in the long run.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <img src="../figures/1Cd_datamanagement_helps_your_future_self.png" alt="Data Management" width="200"/>
      <p style="font-size: x-small;"><em>"Data management helps your future self" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <h3>BETTER ORGANISATION</h3>
      <p>File naming and folder organisation best practices will help you to be more organised in your BSc thesis research and in general: in your studies you will likely be working with larger quantities of data over longer periods of time. You may have it all in your head now, but forget major details two months from now. It’s helpful to have <b>systemic, well-documented methods</b> for naming and organising your files now so that your future self can easily understand and locate what you did.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/1Cd_collaborative_efforts.png" alt="Collaborative Efforts" width="200"/>
      <p style="font-size: x-small;"><em>"Collaborative efforts" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <h3>EFFECTIVE COLLABORATION</h3>
      <p>Your file naming choices and folder structure should help a collaborator or supervisor to follow the steps of your research and understand the pieces of your work. When working on collaborative projects, establishing a common/standard folder structure and naming conventions can facilitate collaborative work because everybody knows where to easily find the data they need for the different pieces of the project, making the collaboration more effective. There is no single "right" way to name files and organise folders, but your system of organising data and files needs to work for everyone involved in the work.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/1Ce_building_blocks_programming.png" alt="Building Blocks" width="200"/>
      <p style="font-size: x-small;"><em>"Building blocks of computer programming" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <h3>REINFORCING COMPUTER SCIENCE PRINCIPLES</h3>
      <p>The concepts in this module reinforce skills and habits of thinking that you will need for computer programming. For example, understanding folder structures can help you become a more intuitive user of a <b>command line interface</b>. It can also help you to more intentionally organise and store code and documentation for <b>collaborative projects</b>. Moreover, this mini-module will prepare you to practice better <b>version control</b> by reinforcing habits of systemic naming.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/1Cf_FAIR.png" alt="FAIR" width="200"/>
      <p style="font-size: x-small;"><em>"FAIR" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <h3>ESSENTIAL TOOLS FOR FAIR DATA SHARING</h3>
      <p>Good folder organization and file naming makes research data and files more FAIR (this stands for Findable, Accessible, Interoperable, and Re-usable). Researchers who work according to FAIR principles can have a greater scientific impact, and their work gets cited more. As a BSc student, you’ll be able to work smarter if you make your files and data more findable and accessible. In the modern digital landscape, it’s also beneficial to develop good digital hygiene around data storage and sharing.</p>
    </td>
  </tr>
</table>

### 1d. Your turn to process!

This section discussed many reasons to expand your knowledge of file naming and folder organisation. The next parts of this module aim to provide tools and guidelines which will be immediately applicable to your bachelor’s coursework. 

Before proceeding, please reflect on which of the reasons discussed is most important for you and why:

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292336776353802547/embed" aria-label="Quiz 1d" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<br>
