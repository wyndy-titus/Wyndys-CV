Add the prettier extension, that way you will avoid errors.
&#10004; //  **Sorry! I had it enabled in "User" but not "Workspace".**

<i>Three errors to fix on your page:</i>
Line 47 need to remove the quotes
&#10004;

Line 48 you opening tag is h1 and closing is h2
&#10004;

Line 54 - you need to add ; after each glyph.
&#10004;; &#128540;

Add alt to all images.
&#10004;

In all paragraphs wher you have only encapsulating span, you should remove it. The idea of span is to style a specific part of the paragraph, ids can be put on the paragraph itself.
&#10004;

When you ahve a list (ul, ol or dl) usually it is good to name it \*\*\*\*-list, for example achievements-list.
&#10004;

Go over the names, in the meter tag for id it will be good to be more descriptive, for example study-progress.
&#10004;

The bigger blocks of code in you main which are encapsulate by a div can be replaced by section or article. In the header I would suggest using headers instead of p in order for your file to be sematically correct. In css try to use more classes as selectors and avoid inline styles  
  //  **I refactored this branch a little bit, but I will save the extensive refactorings for the later branches. This repo has a few more branches, but I'm at a roadblock and want to shift focus to another page for homework.**
