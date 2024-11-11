# Part 4 - Hey... where's my file? Understanding storage structures

### 4a. Relevance:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Why should you care about Storage Structures?
  </div>
</center><br>

In the previous section of this module, we explored how to name your files and organise folders. We learned that proper file naming and organisation are not just good habits; they are critical skills for any student or future researcher. Knowing where your files are and being able to visualise their organisation ensures you can quickly retrieve information, maintain data integrity, and save time when managing software or data projects or preserving crucial documents.

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Why does the directory tree matter in programming?
  </div>
</center><br>

From a computational perspective, understanding how files are structured within a directory tree enhances your ability to navigate file systems efficiently and ensures organised, accessible, and secure data management. A directory tree is a hierarchical structure representing the organisation of files and directories (also called folders) within a computer's file system, starting from a root directory and branching out into various subdirectories. The file system manages this hierarchy, organising data into files (which hold information) and directories (or folders) that contain files or other directories.

## 4b. Directory Tree (how are the drives on a computer organised):

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    What is a Directory Tree (also known as Tree Directory or Directory)?
  </div>
</center><br>

Let's break down the concept of a directory tree using a simple analogy: imagine a directory tree as a family tree. Just as a family tree starts with a common ancestor and branches out to show different family members, a directory tree starts with a single "root" and branches out to show various directories and subdirectories, each containing files or additional directories.

- <b>The Root Node:</b> This is the top-most directory in the hierarchy, and it’s the starting point for all directories and files on your computer. Everything branches off from here. Just like the topmost ancestor (such as a grandparent), it is the starting point for the family tree. On Windows, the root directory is represented as ‘C:\’, and on Unix-based systems like macOS or Linux, it’s represented as ‘/’.

- <b>Parent Nodes:</b> Moving down from the root in a family tree, you have family members (parents) who are directly connected to the ancestor and have their own children. Similarly, in a directory tree, <b>parent nodes</b> represent directories that contain other directories or files.

- <b>Child Nodes:</b> In a family tree, children branch off from their parents. Similarly, in a directory tree, <b>child nodes</b> are directories or files within a parent directory. A child node can either be a subdirectory or a file. And so, child nodes, that are subdirectories, can themeselves become parent nodes of other files and directories beneath them in the tree. 

- <b>Leaf Nodes (End Members):</b> In a family tree, the individuals who do not have children of their own are like <b>leaf nodes</b> in a directory tree. Leaf nodes are typically files because they do not contain any further subdirectories or files. They are the endpoints of the tree, representing actual content, such as documents, images, or videos.

You might wonder: <b>What's the difference between a directory tree and folder structure?</b> In summary, a directory tree is used by operating systems (such as Windows) to manage the entire file system organisation. Meanwhile, a folder structure focuses on practical organisation for a specific purpose or project. Both concepts help us manage and navigate our digital content effectively.

<b>Scenario:</b>

To better understand what a directory tree is, let’s look at how the file system is organised on a scientist Nelle’s computer.

<center>
<img src="../figures/4B_Graphic_1_directorytree.JPG" alt="Graphic_1" style="width: 400px; height: auto;"/>
</center>

The file system resembles an upside-down tree, with the root directory represented by a slash character ```/``` on the top; this character is the leading slash in ```/Users/nelle```. Inside that directory are several other directories: bin (to store built-in programs), data (for miscellaneous data files), Users (where users’ personal directories are located), tmp (for temporary files that don’t need to be stored long-term), and so on. These directories are the child nodes of ```/```, the root node.

We know that our current working directory ```/Users/nelle``` is stored inside ```/Users>``` because ```/Users``` is the first part of its name. Similarly, we know that ```/Users``` is stored inside the root directory ```/``` because its name begins with ```/```. The subdirectories ```/Users/nelle``` is a child node of ```/Users```, which is itself a child of ```/```.

Notice that there are two meanings for the ```/``` character. When it appears at the front of a file or directory name, it refers to the root directory. When it appears inside a path, it’s just a separator.

Underneath ```/Users```, we find one directory for each user with an account on Nelle’s machine, her colleagues Imhotep and Larry.

The subdirectory ```/Users``` is the parent node to ```/Users/imhotep```, ```/Users/larry```, and ```/Users/nelle```, and it is the child node of ```/```, the root directory.
<center>
<img src="../figures/4B__Graphic_2_directorytree.JPG" alt="Graphic_2" style="width: 400px; height: auto;"/>
<p style="font-size: x-small;"><em>“The Unix Shell: Navigating Files and Directories” by Software Carpentry is licensed under CC BY 4.0 <a href=https://swcarpentry.github.io/shell-novice/02-filedir.html>https://swcarpentry.github.io/shell-novice/02-filedir.html</a></em></p>
</center>

## 4c. Check your understanding of Directory Trees:

Based on what you learned about directory trees, answer the following multiple-choice questions to the best of your ability.

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
  <iframe src="https://tudelft.h5p.com/content/1292367933376792477/embed" aria-label="DirectoryTreeProcessing"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

### 4d. Local vs. Remote access:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    What are distinguishing features of remote vs. local access?<br>Where are the best storage location(s) for my files?
  </div>
</center><br>

When studying or working at TU Delft, understanding the difference between remote and local access is essential for managing your files and data effectively. Whether you are conducting research, collaborating on a group assignment, or simply keeping your notes organised, understanding the difference between remote and local access and how they apply at TU Delft will help you make informed decisions about file storage and access.

Below is a table comparing local and remote access. Read through the table to learn the differences, then answer the practice questions.

<style>
    table {
        width: 100%;
        border-collapse: collapse;
        margin-bottom: 20px;
    }
    th, td {
        border: 1px solid #dddddd;
        padding: 8px;
        text-align: left;
        vertical-align: top;
    }
    th {
        background-color: #f2f2f2;
    }
    .local {
        background-color: #ccffcc; /* Light green background */
    }
    .remote {
        background-color: #ffcccc; /* Light red background */
    }
</style>

<table>
    <thead>
        <tr>
            <th></th>
            <th class="local">Local Access</th>
            <th class="remote">Remote Access</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Definition</strong></td>
            <td class="local">Local Access refers to accessing files and data stored directly on your personal device (e.g., your laptop, desktop, or a university computer). This data is only accessible when you have physical access to that device.</td>
            <td class="remote">Remote access refers to accessing files and data stored on external servers, such as cloud storage or university network drives. This data can be accessed from any device with an internet connection.</td>
        </tr>
        <tr>
            <td rowspan="2"><strong>Examples</strong></td>
            <td class="local"><strong>Personal Laptop or Desktop:</strong> if you’re working on a MATLAB project saved on your laptop’s Documents folder.</td>
            <td class="remote"><strong>OneDrive:</strong> a cloud storage service where you can store your files as a BSc student. By saving your files on OneDrive, you can access them remotely from any device with an internet connection, on or off-campus.</td>
        </tr>
        <tr>
            <td class="local"><strong>University Computers:</strong> If you are working on a TU Delft computer in a lab or library, any files you save on the local hard drive will only be accessible on that specific machine: you will not be able to access those files from others computers, such as those located in CiTG.</td>
            <td class="remote"><strong>TU Delft Network Drives:</strong> These network drives are accessible remotely via VPN (Virtual Private Network) with your NetID credential. These drives are hosted on TU Delft’s servers, allowing you to access your data securely from any location, whether you are on campus or not.</td>
        </tr>
        <tr>
            <td rowspan="2"><strong>Advantages</strong></td>
            <td class="local"><strong>Speed</strong>: Accessing files stored locally is usually faster because it does not rely on an internet connection.</td>
            <td class="remote"><strong>Flexibility:</strong> You can access your files from anywhere on any device, if you have an internet connection.</td>
        </tr>
        <tr>
            <td class="local"><strong>Offline Availability:</strong> You can access your files even when there is no internet connection.</td>
            <td class="remote"><strong>Backup and Security:</strong> Files stored on the cloud service OneDrive are automatically backed up by the ICT department at TU Delft and are protected against data loss.</td>
        </tr>
        <tr>
            <td rowspan="3"><strong>Challenges</strong></td>
            <td class="local"><strong>Limited by Device:</strong> Your data is only available on the specific device where it is stored.</td>
            <td class="remote"><strong>Internet Dependency:</strong> You need an active internet connection to access your files remotely. When working with large data sets, unreliable internet connections can be a significant limitation. For instance, if you plan to work on the train and need to create a growth for a presentation, degraded internet data subscriber bottlenecks, and slow connections can be substantial impediments.</td>
        </tr>
        <tr>
            <td class="local"><strong>Risk of Data Loss:</strong> If disaster strikes and your device fails or gets lost or stolen, you could lose your data unless you have an external or online backup.</td>
            <td class="remote"><strong>Speed:</strong> Accessing large files remotely may be slower than accessing them locally, depending on your internet speed.</td>
        </tr>
        <tr>
            <td class="local"><strong>Staying Updated in Collaborative Projects:</strong> If you are working on a collaborative project, being offline means you will miss out on the latest updates and changes made by your team.</td>
            <td class="remote"></td>
        </tr>
    </tbody>
</table>

## 4e. Check your understanding of local vs. remote storage 

Take the quiz to check your understanding:

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292367276805070977/embed" aria-label="DirectoryTreeProcessing"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>
