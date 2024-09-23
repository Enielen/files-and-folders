# Part 3 - Folder Organisation

### 3a. Relevance:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Why does folder organisation matter to me and my collaborators?
  </div>
</center>

<style>
  td {
    width: 50%;
    vertical-align: top;
    padding: 0;
    text-align: center; /* Centers the text and images within the cells */
  }

  .text-container {
    width: 80%; /* Adjusts the width of the text section */
    margin: 0 auto; /* Centers the text section within the cell */
    height: 100px; /* Keeps a consistent height for alignment */
  }

  img {
    width: 70%; /* Sets the image width to 70% of the cell */
    height: auto; /* Maintains the aspect ratio */
    display: block; /* Makes the image behave as a block element */
    margin: 0 auto; /* Centers the image within the cell */
}
</style>

<table>
  <tr>
    <td>
      <div class="text-container">
        <h3><b>BEFORE:</b></h3>
        <p>With a cluttered desktop like this, it can be difficult to see what’s where, and hard to stay organised.</p>
      </div><br>
      <img src="../figures/3Aa_desktop_chaos.png" alt="Desktop Chaos" />
      <p style="font-size: x-small; width: 70%; margin: 0 auto;"><em>"Desktop Chaos" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td>
      <div class="text-container">
        <h3><b>AFTER:</b></h3>
        <p>With an organised system of folders, it's easier to locate exactly what you need.</p>
      </div><br>
      <img src="../figures/3Ab_desktop_harmony.png" alt="Desktop Harmony" />
      <p style="font-size: x-small; width: 70%; margin: 0 auto;"><em>"Desktop Harmony" by TU Delft Library - Data Analysis Team is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
  </tr>
</table><br>

A system of sub-folders helps you organise items into more intentional and manageable categories. This will make it possible to find elements more easily and save you time in the long run, especially during big projects.

Just like with file naming conventions, it’s important to **consider your folder structure in advance**. Your folders will be determined by what kinds of information you will collect and what you (and your collaborators, if applicable) eventually want to do with the data. **Your folder structure will depend on your project: there is no single right folder structure.** 

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Why does folder structure matter in programming?
  </div>
</center><br>

Will you use code and scripts to analyse research data? Well-organised folders will give you a much more efficient way to summon and work with specific data sets. For example, you may want to use a ```for-loop``` command or a ```glob``` to summon all the data housed in a folder. These commands work best if the data has already been sorted into clearly named folders.

### 3b. Folder Rules of Thumb:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    What are effective systems to organise the folders for my project?
  </div>
</center><br>

Watch the video to learn about how to create a basic **hierarchical folder structure** for a project, in which folders are organised from most general to more specific. 

<center><b>VIDEO PLACEHOLDER</center></b>

<b>Check your understanding:</b> Answer the True or False questions to check your understanding of the rules of thumb for folder organisation.

<style>
.responsive-iframe {
    position: relative;
    width: 100%;
    overflow: hidden;
    /* padding-top: 58.5%;  */
}
.responsive-iframe iframe {
    /* position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%; */
    position: relative;
    width: 100%;
    height: auto;
    border: 0;
}
.caption {
    text-align: center; /* Center the caption text */
    font-size: 14px; /* Adjust font size as needed */
    margin-top: 8px; /* Space above the caption */
    color: #555; /* Optional: adjust caption color */
}
</style>

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292363764289864897/embed" aria-label="Part3b"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

### 3c. Common Folder Pitfalls:

The following video segment was created by the Ghent University data stewards. Watch the video to review best practices for folder organisation and to learn about three big pitfalls to avoid with folder organisation and naming.

<style>
    .responsive-iframe-container {
        position: relative;
        overflow: hidden;
        padding-top: 56.25%; /* 16:9 Aspect Ratio */
        width: 100%;
    }

    .responsive-iframe-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

<div class="responsive-iframe-container">
    <iframe src="https://www.youtube.com/embed/hnnE2v7ReOw" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<p class="caption">Attribution: Ghent University (CC-BY)</p>

Let’s elaborate on the three pitfalls mentioned in the video and demonstrate with examples.

#### Pitfall #1: Too deep folder structure: the sub-sub-sub-sub-sub-sub-folder dilemma

The video clip from the University of Ghent mentioned avoiding too many sub-folders. If getting there takes too many clicks, it may not be the most efficient way of working. The goal should be to make it easy and fast for you and your collaborators to navigate through all the folders of a project. An intentional, not-too-deep folder structure makes the components of your project more findable. For projects involving code or script, issues might also arise with trying to access a file via the command line if the folder structure is very deep.

<b>Check your understanding of pitfall #1</b>:

<br>

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292379391559093297/embed" aria-label="pitfall_1"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<br>

#### Pitfall #2: Too many files in one folder

If you are working with files “manually” without using script or code, beware of folders getting too full. Repeated scrolling is not a good use of your time. If a single folder gets so full that you cannot easily see the files in it, consider making another folder or another sub-level of folders. This will re-organise large numbers of files into smaller, more manageable chunks so you can navigate to the file(s) you need more quickly.

Please note: Full folders are not a problem for projects with folders containing data files that will be read primarily by code or scripts. In these cases, a folder might contain thousands of files. What really matters, then, is how well the files have been named and categorised.

#### Pitfall #3: Overlapping or redundant folder names.

As mentioned before, it’s a good idea to create a root folder and give it the name of the specific project. Within that root folder, all sub-folders should have their own unique and recognizable names, just like you saw earlier in the video about Folder Rules of Thumb. Otherwise, it can quickly get very confusing.

<b>Check your understanding of pitfall #3:</b>

<br>

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292362134790431977/embed" aria-label="pitfall_3"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

### 3d. Process what you've learned about folder organisation:

<b>Scenario:</b>

Nikola Vukovic is a Neuroscientist from the University of California San Francisco. To stay organised during his research, he has established this hierarchical folder structure. The folder structure reflects the key elements of his research projects:

<center>
<img src="../figures/3D_NVukovic_folder_structure.png" alt="NVukovic Folder Structure" style="width: 500px; height: auto;"/>
<p style="font-size: x-small">Folder structure. From <em>"Setting up an organised folder structure for research projects"</em> by N. Vukovic, n.d. (<a href=http://nikola.me/folder_structure.html>http://nikola.me/folder_structure.html</a>). Reprinted with permission. </p>
</center>


<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    How does this folder structure match Nikola's work flow?
  </div>
</center><br>

- When Nikola puts his folder structure into action, “ProjectFolder” would actually be given his specific project’s title.

- Nikola usually applies for and receives grants to conduct his research projects, so he likes to include a Project Management sub-folder.
  - He uses a sub-sub-folder for Proposals where he saves his project plan and grant application requirements.
  - Finance also gets its own sub-sub-folder because Nikola needs to track the funding and expenses for most projects.

- Since his research tends to deal extensively with human research subjects, Nikola makes a habit of dedicating a sub-folder to Ethics governance.
  - Within that, he includes one sub-sub-folder for ethics forms and another for approvals.

Nikola offers further insights into his established folder structure on his website. If you are interested in learning more, you can visit: http://nikola.me/folder_structure.html

<b>Check your understanding:</b>

Based on the visual outline of Nikola's folder structure, take a quiz about where you would find different types of files.

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292367152750218497/embed" aria-label="Nikola_processing_questions"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>
