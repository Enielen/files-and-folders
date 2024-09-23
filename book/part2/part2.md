# Part 2 - Establishing File Naming Conventions

### 2a. Relevance:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Why assign naming rules to files and folders?
  </div>
</center>
<br>

Consistent file naming can help you to clearly organise all the information for your projects.

At the beginning of a project, it’s helpful to determine an FNC (File Naming Convention), or “file naming schema,” for each type of information that you will gather, create, or store to work with. An FNC is the pattern that you establish and follow for naming the files associated with a project. Without an FNC, you might end up with a mysterious list of file names that looks something like this:
<center>
<img src="../figures/2Aa_documents_cartoon.png" alt="Documents Cartoon" style="width: 200px; height: auto;"/>
<p style="font-size: x-small;"><em>"Documents" by xkcd is licensed under CC-BY-NC.</em></p>
</center>

File naming conventions help you stay organised so you can quickly identify your files. In a collaborative setting that requires file-sharing, a clear FNC will help others more easily navigate your work.

<div style="border: 2px solid orange; padding: 10px; background-color: #fff3cd; border-radius: 5px; display: flex; align-items: center; margin: 10px 0;">
  <span style="font-size: 24px; color: orange; margin-right: 10px;">⚠️</span>
  <span style="margin-left: 5px;">It is <b>essential</b> to establish a convention <b>before</b> you begin creating files or collecting data, and to adjust it as needed during the research while documenting any changes accordingly. Having a clear FNC at the start of a project prevents a backlog of unorganised content.</span>
</div>

In this module we’ll share general recommendations for file naming that apply across academic disciplines. Please note, <b>there’s no single “right” way to name your files</b>. However, also be aware that different fields of study may have their own specific conventions for naming different types of files. For example, biologists may adhere to standardised 4-letter abbreviations for species names.

### 2b. Rules of Thumb for File Naming:


<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    How do I develop an FNC (file naming convention) for my files?
  </div>
</center>

<br>

Read the basic rules of thumb to learn more about recommended file naming practices. Afterwards, you’ll be asked to analyse several examples.

#### #1 Be consistent
- At the start of a project, choose a naming pattern for all files of the same type. Then stick with it!

#### #2 Be descriptive
- An FNC should include elements or attributes that best describe the file. For example, which keywords would you and collaborators use to search for the file? Which elements make the file recognizable and distinct from other files? Because every project is different, <b>the same naming elements won't apply to every project</b>. When you develop an FNC, you must choose descriptors that are most relevant to the specific files(s) and/or project. Here are a few examples of file descriptors:
    - Project title
    - Conditions (lab instrument or set-up used, specimen tested, temperature, variable being measured, etc.)
    - Type or purpose of document (e.g. data, progress report, questionnaire, interview)
    - If working collaboratively, the initials of the person who ran the test
- "Final" is <b>NOT</b> a descriptive name
- Use abbreviations that are commonly unterestood by collaborators, and document these abbreviations.

<b>Describing data in a series</b>

- If you are working with data in a series, file names should indicate what makes each separate piece of data unique or should indicate where each piece of data falls within the collection sequence. Otherwise, it may be more difficult to retrace your research process.

For example:
- Run of the experiment (also called the ascension number, trial number, or recording ID). Add "leading zeros" so that all file names in a series stay the same length. This will make it easier to search for the data sequentially. To exemplify:
    - In an experiment involving 500 trials, the data will be numbered like this:
    001<br>
    015<br>
    066<br>
    488

    - In an experiment involving 200 trials, the data will be numbered like this:
    0001<br>
    0015<br>
    0066<br>
    0488<br>
    1356

- The date the file was created or the date the data were collected. Generally recommended format for dates is: <b>YYYMMDD</b>.

<b>Check your understanding:</b>
Let’s pause to process these first two rules of thumb with two file naming scenarios.
***
<b>Practice A:</b><br>
A team of researchers is doing a comparative study titled “Project Vis.” It involves field observations of fish in the Netherlands at different locations and times. They establish this FNC for the datasets they'll collect in the field:

<b>[Project name]_[location of data collection]_[date collected]_[initials of the researcher].file type</b>
***
<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292355873998431047/embed" aria-label="Practice_A" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<b>Practice B:</b><br>
Practice applying the first two file naming rules of thumb to a research scenario.
<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292336852411897787/embed" aria-label="Practice_B"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

#### #3 Keep file names short

- Try to limit names to 32 characters or less. Shorter names are easier to quickly scan to know what the file is. For a visual:
<center>
<div style="border: 2px solid #4CAF50; padding: 10px; background-color: #ccff99; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000;">
  32CharactersLooksExactlyLikeThis.ext
</div></center><br>

- Try to shorten file names as much as possible by using abbreviations or acronyms (but make sure others in your field understand them)

#### #4 Avoid spaces

- Some operating systems and command line programs don’t recognise spaces in file names. Spaces can cause problems when you’re transferring files between systems.
- Recommended: use underscores _ or hyphens - instead of spaces.

#### #5 Avoid "weird" characters

- <b>Use periods only at the end of the file name</b>, right before the *extension (*extension: the last 2-3 characters that tell you the file format)

- Some characters carry meanings within a computer programming environment, so it’s better to avoid them. These characters can be confusing for machines:
<center>
<div style="border: 2px solid red; padding: 10px; background-color: #fff; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000;">
  .&, *%#;()!@$^~'{}[]?<>
</div></center>

#### #6 Versioning matters: Track versions of your work
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
      <img src="../figures/2B_why_versioning_matters.png" alt="Why versioning Matters"/>
      <p style="font-size: x-small;"><em>"Why versioning matters" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <p>Sometimes you may need to keep track of multiple versions or revisions of the same file.<br><br>Without a clear system for versioning, you might forget which version is which (see graphic). This could lead to unfortunate mistakes. For example, for a big class assignment you might submit "Reallyfinal.doc", when you meant to turn in "Finalfinal.doc".</p>
    </td>
  </tr>
</table>

Such a confusion can be remedied by including version information in the file name. This will help you and collaborators to track the evolution of a document more clearly over time.

Here are standard recommendations to indicate version:
- For significant changes, use whole numbers: V1, V2
- For minor changes, use decimals: V1.1, V1.2

### 2c. Process the rules of thumb for file naming: 

You just learned basic rules of thumb for developing an FNC. Now, take a few minutes to practice applying basic file naming guidelines to three new scenarios.

<b>FNC Scenario #1:</b>
<div class="responsive-iframe">
<iframe src="https://tudelft.h5p.com/content/1292338726732494147/embed" aria-label="Scenario_1" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<b> FNC Scenario #2:</b>
<div class="responsive-iframe">
<iframe src="https://tudelft.h5p.com/content/1292338765754228157/embed" aria-label="Scenario_2" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<b>FNC Scenario #3:</b>

<div class="responsive-iframe">
<iframe src="https://tudelft.h5p.com/content/1292339487820332487/embed" aria-label="Scenario_3" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

### 2d. Practical applications: how do I keep track of the FNC I've chosen?

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/2D_README_Alice_in_WL.png" alt="Alice in WL" width="200"/>
      <p style="font-size: x-small;"><em>"README Alice in Wonderland" adaped from original image by John Tenniel - John Tenniel, Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=629633">https://commons.wikimedia.org/w/index.php?curid=629633</a></em></p>
    </td>
    <td class="text-cell">
      <p>To keep track of the FNCs they’ve established, researchers create a piece of documentation called a “README” file. A README is generally a txt file that gets saved into the same folder as the dataset(s) it describes. The README.txt acts like a short guide to your FNC. It helps explain and document the schema that was used to name those specific files. We plan to develop a separate mini-module about documentation strategies; it will go into more depth with step-by-step instructions about how to create README files. Would you like to learn more about README documentation in the meantime? We suggest you visit this link to <a href="https://datamanagement.hms.harvard.edu/collect-analyze/documentation-metadata/readme-files"> Harvard University’s research data management site</a> which offers README templates and guides.</p>
    </td>
  </tr>
</table>
