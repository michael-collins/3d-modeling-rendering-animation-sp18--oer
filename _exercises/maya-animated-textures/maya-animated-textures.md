---
title: Maya Animated Textures
subtitle: 
layout: exercise
submission-id: anim-textures-YOURSTUDENTID
assignment-dropbox: https://psu.box.com/signup/collablink/d_6058208509/13048f751411ea
asset-path: /assets/exercise-downloads
---

In this exercise, you will practice applying an animated texture to an object in Autodesk Maya, animating that object along a motion path, batch rendering, importing the batched renders back into Adobe After Effects, and exporting a compressed video. Here is an example of what the animation could look like: [A Mighty Box](https://docs.google.com/file/d/0BzXX6rmROMNWck1MVnpFclpWdU0/edit).

## Learning Resources

### Tutorials:

**Animated Textures:**  
Digital Tutors: [How to project an image sequence as a texture onto a model](http://www.digitaltutors.com/11/training.php?vid=10038&autoplay=1)  
Autodesk (see Image Sequence): [File Node Documentation](http://download.autodesk.com/global/docs/maya2013/en_us/index.html?url=files/Shading_Nodes_File.htm,topicNumber=d30e573165)

**Motion Paths:**  
Digital Tutors: [Animating along a motion path](http://www.digitaltutors.com/tutorial/609-Maya-Animation-Reference-Library-Animate)  
Youtube: [Fresh Maya Tutorial](http://www.youtube.com/watch?v=Z7HFSq6FrUs)

**Batch Rendering:**  
Lynda (Lesson 5): [Maya Essentials 6: Lights and Rendering](http://www.lynda.com/Maya-tutorials/Maya-Essentials-6-Lights-Rendering/96718-2.html)  
Digital Tutors: [Introduction to Rendering in Maya](http://www.digitaltutors.com/11/training.php?vid=21419&autoplay=1)

**Other:**  
Import/Export After Effects: [After Effects Image Sequence to H.264](https://docs.google.com/document/d/1R5G3bvXoe0_Bto59_dV4c4_iLZIA1--sHRQ8fhkBnvc/edit)  
[Render a still image sequence from After Effects](https://helpx.adobe.com/after-effects/using/rendering-exporting-still-images-still.html)
        
### Asset Downloads:  
[Example Image Sequence]({{ site.baseurl }}{{ page.asset-path }}/animated-texture.zip)


##Steps to Completion

**Choose a single level to complete based on your level of experience with 3D tools. If you are a novice, choose Level 1. If you have some experience, choose Level 2. If you are very experienced with 3D tools, choose Level 3.**

[Level 1 Steps](#level-1) | [Level 2 and 3 Steps](#level-2-3)

### <a name="level-1"></a>Level 1:

1. Watch the level tutorials from Digital Tutors and Lynda.
2. Create and set a project folder called **_{{ page.submission-id }}-L1_** set your scene to the project folder, and create the sub folders by choosing **_File_** → **_Project Window_** → **_Accept_**.
3. Download the provided [Example Image Sequence]({{ site.baseurl }}{{ page.asset-path }}/animated-texture.zip). Extract and preview the image sequence by opening it with Quicktime 7.
4. Create a unique polygonal object that responds to the image sequence in some way.
5. Attach the image sequence to the object's material color attribute channel. You may plug it into other material attributes as well.
6. Change the default 48 frame duration of the animation timeline to **24** frames.
7. Create a motion path.
8. Attach the polygon object to the motion path. Animate the object to follow the motion path for 24 frames.
9. Batch Render your animation with these Render Settings
   - **Render Using:** Mental Ray
   - **Common Tab:**
      - File Name Prefix: ``` <Scene>/<Scene> ```
      - Image Format: ``` Maya IFF ```
      - Frame/Animation ext:  ``` name.#.ext ``` **(NOT name.ext.#)**
      - Frame padding: ``` 2 ``` 
      - Start Frame: ``` 1 ``` 
      - End Frame: ``` 24 ``` 
      - By Frame: ``` 1 ``` 
      - Alpha channel (Mask): ``` Checked ``` 
      - Presets: ``` HD 540 ``` 
   - **Quality Tab:**
      - Show Advanced Settings: ``` Checked ```      
      - Quality: ``` 2 ``` 
      - Advanced Light Sampling → Indirect Diffuse (GI) Mode: Finalgather
   - **Scene:**
      - Show Advanced Settings: ``` Checked ```  
      - Primary Framebuffer → Premultiply: ``` Unchecked ```
      - Create Physical Sun and Sky
         - In Physical Sun and Sky Attributes → Use Background:  ``` Checked ``` 
      - Motion Blur: ``` Full Deformation ``` 
10. Import your animation sequence to After Effects and export an H.264 MP4 movie file. To do this, [follow this tutorial](https://docs.google.com/document/d/1R5G3bvXoe0_Bto59_dV4c4_iLZIA1--sHRQ8fhkBnvc/edit). (It should be well under 1MB in total file size)
11. Put your H.264 encoded .mp4 video into the project folder in movies folder.
12. Save your scene as **_{{ page.submission-id }}_** in the scenes folder.
13. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}-L1.zip._**
14. Upload the .zip file to the [submission dropbox]({{ page.assignment-dropbox }})
15. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

**Example _Level 1_ folder structure**

```

{{ page.submission-id }}-L1.zip
|
└── {{ page.submission-id }}-L1
    |
    ├── sourceimages/
    |   |
    |   └── animated-texture/
    |       |
    |       ├── texture_000.jpg
    |       └── ...
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
    |   |
    |   └── {{ page.submission-id }}.mp4
    |
    ├── images/
    ├── data/
    ├── clips/
    ├── cache/
    ├── autosave/
    └── assets/

```

### <a name="level-2-3"></a>Level 2 and 3:

1. Watch the level tutorials from Digital Tutors and Lynda.
2. Create and set a project folder called **_{{ page.submission-id }}-L2-3_** set your scene to the project folder, and create the sub folders by choosing **_File_** → **_Project Window_** → **_Accept_**. 
3. Create a 72 frame 1024px x 1024px image sequence in After Effects. [Render a still image sequence from After Effects](https://helpx.adobe.com/after-effects/using/rendering-exporting-still-images-still.html).
4. Create a 3 second (72 frame) animation using motion paths of polygonal objects assembling to form a word. 
5. Apply the image sequence from step 3 as an animated texture to one or more of your polygonal objects's material color channel. (You can create more than one animated texture if desired)
6. Batch Render your animation with these Render Settings
   - **Render Using:** Mental Ray
   - **Common Tab:**
      - File Name Prefix: ``` <Scene>/<Scene> ```
      - Image Format: ``` Maya IFF ```
      - Frame/Animation ext:  ``` name.#.ext ``` **(NOT name.ext.#)**
      - Frame padding: ``` 2 ``` 
      - Start Frame: ``` 1 ``` 
      - End Frame: ``` 72 ``` 
      - By Frame: ``` 1 ``` 
      - Alpha channel (Mask): ``` Checked ``` 
      - Presets: ``` HD 540 ``` 
   - **Quality Tab:**
      - Show Advanced Settings: ``` Checked ```      
      - Quality: ``` 2 ``` 
      - Advanced Light Sampling → Indirect Diffuse (GI) Mode: Finalgather
   - **Scene:**
      - Show Advanced Settings: ``` Checked ```  
      - Primary Framebuffer → Premultiply: ``` Unchecked ```
      - Create Physical Sun and Sky
         - In Physical Sun and Sky Attributes → Use Background:  ``` Checked ``` 
      - Motion Blur: ``` Full Deformation ``` 
7. Import your animation sequence to After Effects and export an H.264 MP4 movie file. To do this, [follow this tutorial](https://docs.google.com/document/d/1R5G3bvXoe0_Bto59_dV4c4_iLZIA1--sHRQ8fhkBnvc/edit). (It should be well under 2MB in total file size)
8. Put your H.264 encoded .mp4 video into the project folder in movies folder. 
9. Save your scene as **_{{ page.submission-id }}_** in the scenes folder.
10. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}-L1.zip._**
11. Upload the .zip file to the [submission dropbox]({{ page.assignment-dropbox }})
12. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

**Example _Level 2 and 3_ folder structure**

```

{{ page.submission-id }}-L2-3.zip
|
└── {{ page.submission-id }}-L2-3
    |
    ├── sourceimages/
    |   |
    |   └── animated-texture/
    |       |
    |       ├── texture_000.jpg
    |       └── ...
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
    |   |
    |   └── {{ page.submission-id }}.mp4
    |
    ├── images/
    ├── data/
    ├── clips/
    ├── cache/
    ├── autosave/
    └── assets/

```

* * *

## Grading
Your grade will be assessed according to the [Exercise Grading Criteria]({{ site.baseurl }}/grading).
