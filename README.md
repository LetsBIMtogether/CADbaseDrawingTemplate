# CAD Base Drawing Template

<img src="GitHub%20Images/ADV-TEMPLATE_1_CAD.png" width="600"/>

[Click here to download CAD Base Drawing Template](https://github.com/LetsBIMtogether/CADbaseDrawingTemplate/raw/main/AG-TEMPLATE-v1-0.dwg)

A starting-point base drawing template for AutoCAD LT, but can be used in all versions of AutoCAD.

🎥 [Watch a YouTube demo](https://www.youtube.com/watch?v=0a4gnKEjDPg)

## Template Notes

- Uses plot style "AIA Standard.ctb" from:
  - [Autodesk - How to set up AIA Layer Standards in AutoCAD LT](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/How-to-set-up-AIA-Layer-Standards-in-AutoCAD-LT.html)

- Create additional discipline layers using an AutoLISP script from:
  - [github.com/LetsBIMtogether/AutoLisp](https://github.com/LetsBIMtogether/AutoLisp)

- AIA CAD Layer Guidelines used for reference:
  - [AIA CAD Layer Guidelines (Duke Facilities)](https://facilities.duke.edu/sites/default/files/AIA%20CAD%20Layer%20Guidelines.pdf)

## Features

- Organized naming logic for everything including blocks, layers, styles, etc.

  - Gives a good starting point to build off of and scale.

- A legend for every element, created starting from a blank file.

  - Layer, linetype, and CTB pen weight legends.

  - Text and dimension styles.

  - Blocks.

  - Properties are set up for all above so you can match properties (Command `MA`)

- Dynamic blocks.

  - Includes a few dynamic blocks. 

  - For additional dynamic blocks included with AutoCAD, use the `TOOLPALETTES` command.

## Advanced Dynamic Block Sample

<img src="GitHub%20Images/ADV-DYN-BLOCK_1_PROPERTIES%20N%20HANDLES.png" width="600"/>

<img src="GitHub%20Images/ADV-DYN-BLOCK_2_ACTIONS.png" width="600"/>

<img src="GitHub%20Images/ADV-DYN-BLOCK_3_ACTION-BAR.png" width="600"/>

- Sample of an advanced block that, when built with your workflow in mind, eliminates a good chunk of production time.

- Schedulable properties (includes a schedule).

- 22 user grips, 17 user properties, 24 parameters, and 19 actions.

- Action and parameter naming structure for maintainability.

- No spaghetti.

- Fully modifiable in AutoCAD LT.

## Print Samples

<img src="GitHub%20Images/ADV-TEMPLATE_2_PLAN.png" width="600"/>

<img src="GitHub%20Images/ADV-TEMPLATE_3_RCP.png" width="600"/>

- [Sample Print - Floor Plan (PDF)](GitHub%20Images/AG_SampleSchool_PLAN.pdf)

- [Sample Print - Reflected Ceiling Plan (PDF)](GitHub%20Images/AG_SampleSchool_RCP.pdf)

## License

Licensed under the [MIT License](LICENSE).
<br/>
<br/>

---

## Go to [www.LetsBIMtogether.com](https://letsbimtogether.com/ "www.LetsBIMtogether.com") for:

- AutoLisp routines for AutoCAD software

- Revit/CAD Tips & Tricks YouTube channel

- Plugins & scripts for Revit software

- Autodesk Appstore page

- LinkedIn

- GitHub

- Blog
