Download Link: https://assignmentchef.com/product/solved-solved-programming-project-3
<br>
Chapter 10, page 699-700,Programming Project #3, Family database program: plus add a Family TreeClass.First complete this Chapter 10 ArrayList and then upgrade into aFamilyTree Class as described below. I repeat: First complete Chapter 10Project #3, 99% of the student questions are from those who skip that step!!!I’ve included the Person Class file from the BJP text author to give you a goodstart: Person.javaPreview the documentView in a new window After the Chapter 10run displays as shown here: Capture1.JPGView in a new window These data comefrom the file names.txtPreview the documentView in a new window which is theexact same list of names provided by our text author back in Chapter 10(tudor.dat), but modified for this assignment. In the above screen capture,please notice a few things. Note the upper output is identical to what’s in thetext, then at the bottom, I display the same data as a print Sideways Tree. Ialso note that one of the children is Mary I, so I can enter that name too, andget the following family tree information: Capture2.JPGView in a new window Themain () test program from the text author I’ve changed to FamilyTest.java Previewthe document View in a new window which you cannot alter, as that’s what I’lluse to test your FamilyInfo and FamilyTree classes. The person names and familyinformation are provided in a text file names.txtPreview the documentView in anew window which is simply a list of person-mother-father information that thetext author has provided. Side note: the data from our text (tudor.dat) has theproblem of assuming the first list of names will be exactly the same as thesecond list of names, no spelling errors or name variations, I avoid this byproviding the list of names only once in names.txtPreview the documentView in anew window CRUCIAL: Download the names.txtPreview the documentView in a newwindow file into your project folder (not src). You need to actually downloadthis file (not the textbook version) and read the file as is, else you willcreate code that does not work with my file, and your code will fail all testing(ouch!!!). I will actually test code with a smaller version (8 names) of thissame file. So don’t let a surprise line feed, blank line, or extra new linekill your program. Try a smaller file!!!Your FamilyTree class should be abinary tree, similar to IntTree in the text, but Person replaces the int asdata. This creates a tree of Person nodes. When the user selects a Person, theprogram builds a customized FamilyTree with that Person at the root, theirmother on the left, and father on the right. Since the mother is also a Person,another valid sub-tree needs to be built for her, and another valid sub-treeoff the father on the right. An unknown parent can be treated as anull.(((((((((Upload your completed FamilyInfo.java and FamilyTree.java fileswhen done.)))))))))))I will use FamilyTest.java Preview the document View in anew window and Person.java Preview the document View in a new window to testyour submissions.