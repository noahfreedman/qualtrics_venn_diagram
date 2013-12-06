====================================================================
Venn Diagram and Variance Diagram Question Type Plug-In for Qualtrics
====================================================================

This file is part of qualtrics_venn_diagram, available at https://github.com/noahfreedman/qualtrics_venn_diagram.git

License: The Venn Diagram plug-in for Qualtrics is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

    The Venn Diagram plug-in and the Variance Diagram plug-in for Qualtrics is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
    
====================================================================

Author: Noah Freedman

Sponsored by: Stanford University Graduate School of Education

====================================================================
* Demo:
====================================================================
    Here is a demo survey using the Venn Diagram plug-in: https://gse.qualtrics.com/SE/?SID=SV_0quG9pbQc5sxtv7

    Here is a demo survey using the Variance Diagram plug-in: https://gse.qualtrics.com/SE/?SID=SV_9MOAtLzssFXSXqd

====================================================================
* Venn Diagram Instructions:
====================================================================
    To add the venn diagram to a question in Qualtrics:
    
    1. Create a new question. Change the question's item type to 'Text Entry' -> 'Single Line'.
    
    2. Set a Validation Type of 'Content Validation' to the question, and select 'Number', with a min value of 0, max value of 100, and max decimals of 0.
       
    3. Select the HTML View (for instructions, see: http://www.qualtrics.com/university/researchsuite/coders-corner/html-and-css).
       
    4. Edit venn.html to change the variable names that you want to use for the Venn diagram circles. Replace the values in this text at the top of venn.html with your own values as demonstrated below.
           var LeftCircleText = "Your Value Left";
           var RightCircleText = "Your Value Right";
           
    5. Copy the contents of venn.html into the HTML view of your question. Type any question text in between the '<!--Write your question text here, and set options below:-->' and '<!-- -->' tags.

        For multiple questions, simply repeat steps 1 -5.

====================================================================
* variance Diagram Instructions:
====================================================================
    To add the variance diagram to a question in Qualtrics:

    1. Create a new question. Change the question's item type to 'Text Entry' -> 'Slider'. The variance diagram will only interact with the first slider in the Slider question type.

    2. You may set any slider options via Qualitrcs

    3. Select the HTML View (for instructions, see: http://www.qualtrics.com/university/researchsuite/coders-corner/html-and-css).

    4. Edit variance.html. Replace the values in this text at the top of variance.html with your own values.

    5. Copy the contents of variance.html into the HTML view of your question. Type any question text in between the '<!--Write your question text here, and set options below:-->' and '<!-- -->' tags.

        For multiple questions, simply repeat steps 1 -5.
