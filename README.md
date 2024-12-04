java cMadagascar Projection Change Exercise
Practical title:
Madagascar Projection Transformations 
Course:
Geospatial Fundamentals
Form. of assessment:
Summative Report (20% of final course mark)
Submission location:
Moodle at 1200 on 10th   of December 2024
Minimum requirements for credit:
See Geography Degree mark scheme for Grade Related Criteria   
Details of assessment:
You have been given a digitised version of a Mercator projection map and asked to produce a Lambert Conformal Conical map of Madagascar   for an airplanes company (Lillybank Tours) so they can plan sight-seeing flights across Madagascar. You will carry out a set of conversions and/or transformations to convert from one co-ordinate systems to another using Python.
Intended Learning Outcomes:
By the end of this project, you should be able to:·   Use some simple data and map projection equations to carry out a set of co-ordinate conversions.·   Develop your python skills to carry out a sequence of analysis steps and produce a desired numerical conclusion.·   Produce a short report discussing the relevant background, and methods employed as well as describing any short comings in the approach and considering other possible outcomes.
Deliverables:
Submit to Moodle the following Four (4) parts:1.   A report in Word containing the following information (docx or .pdf):a.   Total word count 1500 words +/- 20%.i.   Marking stops after 1800 wordsii.   Tables, figure captions and bibliography do not count.b.   A brief background on Mercator projection and Lambert Conformal Conic projectionc.   A brief overview of the different stages of the projection change process, showing how they fit together.d.   Selected results section – anything you need to be able to discuss in the discussion section. Put your full numerical results for each stage in Appendix A of the report. See page three of this document for details of the stages.e.   Plots of the coastline in Mercator projection coordinates and LCC coordinates (e.g., in python)f.   A discussion of the differences between the coastline in the Mercator projection coordinates and the LCC projection coordinates.g.   A discussion of any change in the results from using Least Squares Analysis and all four control points to estimate the transformation parameters, rather than using just 2 control points.h.   A discussion of an estimated cost savings from using the LCC derived map as opposed to the Mercator based map. (values for fuel and average consumption are provided in the project description slides)2.   A text file explaining your naming conventions and the sequence of your notebooks.3.   Each of your notebooks created in the analysis pipeline as a pdf file. (can be zipped together or as a single pdf file)4.   A zip file, containing all your python notebooks, your data saved as either excel, csv, or .txt files.
Stylistic Hints:
Some things we will be looking for when marking:·   Clear concise explanations (i.e., short and clear is better than longer and complicated sentences).·   Correct answers. Use Earth radius 63代 写GEO5008 Madagascar Projection Transformations Python
代做程序编程语言78000 m.·   Make sure numbers have units where appropriate and use a reasonable number of significant figures in results.·   A clearly laid out report that is easy for the reader to understand – suitable headings, no tiny text/fuzzy diagrams (refer to the how to write a technical report document).·   Nice, tidy, easy to understand Excel spreadsheets (i.e. enough text so someone who is not familiar with the exercise can easily understand what the spreadsheet is supposed to do).·   Well organised*, carefully commented python programs that are easy to understand. (*e.g. header explaining program purpose, library imports and most variables declared in one section at beginning of program).·   Your discussion section is where most of the range of marks will come from – make sure that your discussion is quantitative, not just qualitative.
This is a summative assessment, contributing to your final module mark. You must work independently on your report. You may crosscheck numbers from your programs with others and help people in your group debug problems but the programs and results you submit must be all your own work.
Stages of Calculations
Stages of the calculation are outlined below. You can break each of these into separate notebooks or keep as one long notebook. If submitted as a single notebook, please make use of the markdown comments to clearly label the sections.
Stage
Calculation
Result
Python Program 1
Convert control point geographical coordinates to Mercator Projection grid coordinates.
Result A:   Mercator Projection grid coordinates of control points 1-4.
Python Program 2
Estimate Digitizer to Mercator 2D similarity transformation constants using 2 control points (number 1 and number 3).
Result B:   Transformation constants estimated using 2 control points.
Python Program 3
Coastline Digitiser Coordinates to Mercator coordinates using transformation constants (2 control points).
Result C:   Coastline points in Mercator Projection grid coordinates.
Python Program 4
Convert Mercator Projection grid coordinates to geographic coordinates.
Result D:   Coastline points in geographic coordinates (Lat, Long).
Python Program LSq.1
Estimate Digitizer to Mercator 2D similarity transformation constants using 4 control points and Least Squares].
Result F:   Transformation constants estimated using 4 control points and Least Squares.
Python Program LSq.2
Coastline Digitiser Coordinates to Mercator coordinates using transformation constants (4 control points).
Result G:   Coastline points in Mercator Projection grid coordinates.
Python Program LSq.3
Convert Mercator Projection grid coordinates to geographic coordinates (4 control points).
Result H:   Coastline points in geographic coordinates (Lat, Long).
Python Program LSq.4
Convert geographic coordinates (Lat, Long) of coastline points to Lambert Conformal Conic grid coordinates using Forward LCC projection equations.
Result J:   Coastline points in LCC Projection Grid coordinates.
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
