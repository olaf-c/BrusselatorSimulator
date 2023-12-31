# Functional Specifications: Brusselator Simulator

## Contributors:
<ul>
  <li>Olaf B. W. H. Corning</li>
</ul>

## Background
  Brusselators are models for reactions that produce a catalyst for the same reaction, i.e. autocatalytic reactions. This includes the clock reaction, or the Belousov–Zhabotinsky reaction (BZ reaction).
  This is a popular reaction for demonstrations as the potassium bromate, malonic acid, and manganese sulfate prepared in a heated solution of sulfuric acid produce an engaging [psychedelic pattern.](https://en.wikipedia.org/wiki/Belousov%E2%80%93Zhabotinsky_reaction#/media/File:Bzr_raum.jpg)
  However, this reaction can be difficult to demonstrate in some settings due to the need for proper safety equipment to handle the strong acids involved. 
  This program provides a method of demonstrating brusselator reactions without needing chemistry supplies. 

  The users will interact with a GUI interface which will display an [animation](https://en.wikipedia.org/wiki/Brusselator#/media/File:Brusselator_space.gif) of an autocatalytic reaction. 
## User Profile
<ul>
  <li> <b> Teachers </b> - The primary user of the program are expected to be high school teachers. These users require engaging visuals for the program to be worth running for their class. They are expected to understand the underlying equations. They are also expected to have some understanding of python such as the ability to pip install the package and run the program from the terminal.
  </li>
  <li>
    <b> Enthusiasts </b> - Users who wish to interact with the brusselator reaction in the comfort of their own home. These users are not expected to know python or the underlying chemical reactions. 
  </li>
</ul>

## Use Cases 
<ul>
  <li>
    <b>Classroom Use </b> - In a classroom, this software can be used to replace the more risky chemical reactions or to supplement the demonstration. To aid their presentation, these teachers may want to adjust the reaction rates beyond what are normally found.
  </li>
  <li>
    <b>Self Study Use </b> - At home, this software can be used to visualize brusselators through a simple GUI. This software will be an independent package that will not require a python installation. 
  </li>
</ul>
