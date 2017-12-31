---
title: Maya Modeling
subtitle: 
layout: exercise
submission-id: modeling-YOURSTUDENTID
assignment-dropbox: https://psu.box.com/signup/collablink/d_6058204285/11915a00eb1b89
asset-path: /assets/exercise-images
---

In this exercise, you will gain basic understanding of modeling fundamentals. There are different tutorials and exercise submission requirements for three experience levels. Choose the experience level that matches your own.

##Learning Resources

###Tutorials:

**Level 1: Novice Students**

[Lynda.com - Modeling with Polygons](http://www.lynda.com/Maya-tutorials/Maya-Essentials-2-Polygonal-Modeling-Techniques/96715-2.html)  
[Lynda.com - Modeling with Nurbs](http://www.lynda.com/Maya-tutorials/Maya-Essentials-3-NURBS-Modeling-Techniques/96716-2.html)

**Level 2: Intermediate Students**

[Lynda.com - Modeling with Polygons](http://www.lynda.com/Maya-tutorials/Maya-Essentials-2-Polygonal-Modeling-Techniques/96715-2.html)  
[Lynda.com - Modeling with Nurbs](http://www.lynda.com/Maya-tutorials/Maya-Essentials-3-NURBS-Modeling-Techniques/96716-2.html)  

**Level 3: Experienced Students**

[Lynda.com - ZBrush Essential Training](http://www.lynda.com/ZBrush-4-tutorials/Essential-Training/76980-2.html) (Lessons 1- 7)  
[Lynda.com - ZBrush Character](http://www.lynda.com/3D-Animation-Character-Design-tutorials/Digital-Creature-Creation-in-ZBrush-Photoshop-and-Maya/83781-2.html) (Lessons 1 - 3)  
[Digital Tutors - Introduction to Z-Brush](http://www.digitaltutors.com/tutorial/1093-Introduction-to-ZBrush)

**Reference Websites**

[Random Objects Generator](http://www.randomlists.com/things)

**More Information:**

Textbook: Introducing Autodesk Maya 2016  
Chapter 4 and Chapter 5

Textbook: Mastering Autodesk Maya 2016  
Chapter 3 and Chapter 4


##Steps to Completion

Choose a either level 1, level 2, or level 3 to complete based on your prior experience with 3D tools. If you are a novice, choose Level 1. If you have some experience, choose Level 2. If you are very experienced with 3D tools, choose Level 3.

[Level 1 Steps](#level-1) | [Level 2 Steps](#level-2) | [Level 3 Steps](#level-3)

### <a name="level-1"></a>Level 1:

1. Watch tutorials from Lynda on modeling with Polygons and Nurbs.
2. Download [these project files](https://docs.google.com/file/d/0BzXX6rmROMNWandfd3hKLXRCdmM/edit) and use the scene file as the starting point and rename the project folder to : **_{{ page.submission-id }}_**.
3. Set your project to the downloaded folder by choosing **File** → **Set Project**.
4. Model the airplane from the reference images with your newly learned modeling skills with polygons. (Be careful not to accidentally create nurbs primitives when modeling)
  - Skills to practice include:
     - ploygonal edge flow
     - extruding polygon faces
     - inserting edge loops
     - moveing, rotating, and scaling vertecies, edges, and faces
     - mirroring and duplicating geometry
5. Save your scene as **_{{ page.submission-id }}_** in the scenes folder.
6. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}-L1.zip._**
7. Upload the .zip file to the [submission dropbox]({{ page.assignment-dropbox }})
8. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

**Example _Level 1_ folder structure**

```

{{ page.submission-id }}-L1.zip
|
└── {{ page.submission-id }}-L1
    |
    ├── sourceimages/
    |   |
    |   └── reference images/
    |       |
    |       ├── front.jpg
    |       ├── side.jpg
    |       └── top.jpg
    |
    ├── sound/
    ├── scripts/
    ├── scenes/
    |   |
    |   └── {{ page.submission-id }}.mb
    |
    ├── renderData/
    ├── particles/
    ├── movies/
    ├── images/
    ├── data/
    ├── clips/
    ├── cache/
    ├── autosave/
    └── assets/

```

### <a name="level-2"></a>Level 2:

1. Watch Lynda tutorials on polygonal modeling.
2. Obtain three randomly generated objects from [this website](http://www.randomlists.com/things). Include a screenshot of the website objects in your **_sourceimages_** folder called **_objects-{{page.submission-id}}}.jpg (or .png)_**
3. Create a new project folder with associated sub-folders (**File** → **Project Window** → **_Accept_**). Create a new scene for each object and save in the **_scenes_** folder.  
  *Naming:*  
  **_obj1-{{ page.submission-id }}_**  
  **_obj2-{{ page.submission-id }}_**  
  **_obj3-{{ page.submission-id }}_**  

4. Create 3 reference image planes for each object with pencil and paper or in Photoshop. Set up the image reference planes in their respective scenes files. Ensure they are square. Place them in the **_sourceimages_** → **_referenceimages_** folder. [Instructions for aligning reference images in Photoshop:](http://www.webdesign.org/photoshop/photoshop-basics/cutting-up-blueprints-for-3d-modelling.4970.html)
  *Naming:*  
  **_obj1-side-{{ page.submission-id }}.jpg_**  
  **_obj1-front-{{ page.submission-id }}.jpg_**  
  **_obj1-top-{{ page.submission-id }}.jpg_**  
  **_obj2-side-{{ page.submission-id }}.jpg_**  
  **_obj2-front-{{ page.submission-id }}.jpg_**  
  **_obj2-top-{{ page.submission-id }}.jpg_**  
  **_obj3-side-{{ page.submission-id }}.jpg_**  
  **_obj3-front-{{ page.submission-id }}.jpg_**  
  **_obj3-top-{{ page.submission-id }}.jpg_**  

5. Create one polygonal model for each scene file from your set of randomly generated objects in Step 2. (You should be making three objects since you’ve created three scenes.)
6. Capture the gesture of the objects with as little detail as needed to describe the shape.
  - Do not "smooth" the objects.
  - Focus on maintaining quads and [organized edgeflow](http://www.digitaltutors.com/lesson/15804-Edge-Flow).
    **See example image of a crowbar below:**  
    ![image alt text]({{ site.baseurl }}{{ page.asset-path }}/maya-modeling-1.jpg)  

7. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}-L2.zip._**
8. Upload the .zip file to the [submission dropbox]({{ page.assignment-dropbox }})
9. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

**Example _Level 2_ folder structure**

```

{{ page.submission-id }}-L2.zip
|
└── {{ page.submission-id }}-L2
    |
    ├── sourceimages/
    |   |
    |   ├── objects-{{ page.submission-id }}.jpg
    |   |
    |   └── referenceimages/
    |       |
    |       ├── obj1-front-{{ page.submission-id }}.jpg
    |       ├── obj1-side-{{ page.submission-id }}.jpg
    |       ├── obj1-top-{{ page.submission-id }}.jpg
    |       ├── obj2-front-{{ page.submission-id }}.jpg
    |       ├── obj2-side-{{ page.submission-id }}.jpg
    |       ├── obj2-top-{{ page.submission-id }}.jpg
    |       ├── obj3-front-{{ page.submission-id }}.jpg
    |       ├── obj3-side-{{ page.submission-id }}.jpg
    |       └── obj3-top-{{ page.submission-id }}.jpg
    |
    ├── sound/
    ├── scripts/
    ├── scenes/
    |   |
    |   ├── obj1-{{ page.submission-id }}.mb
    |   ├── obj2-{{ page.submission-id }}.mb
    |   └── obj3-{{ page.submission-id }}.mb
    |
    ├── renderData/
    ├── particles/
    ├── movies/
    ├── images/
    ├── data/
    ├── clips/
    ├── cache/
    ├── autosave/
    └── assets/

```

### <a name="level-3"></a>Level 3:

1. Watch tutorials from Lynda on modeling with ZBrush.
2. Using the techniques learned in the Digital Creature Creation tutorials, create a **Sea Creature**.
3. Your ZBrush model should be of similar refinement to the model in Digital Creature Creation, by the end of Lesson 3.
4. Take a screenshot of your model and rename the image as **_{{ page.submission-id }}.png_**.
5. Save your image in a project folder **_{{ page.submission-id }}-L3_**.
6. Compress the folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}-L3.zip._**
7. Upload the .zip file to the [submission dropbox]({{ page.assignment-dropbox }})
8. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

**Example _Level 3_ folder structure**

```

{{ page.submission-id }}-L3.zip
|
└── {{ page.submission-id }}-L3
    |
    └──{{ page.submission-id }}.png

```

* * *

##Grading
Your grade will be assessed according to the [Exercise Grading Criteria]({{ site.baseurl }}/grading). 



