Download Link: https://assignmentchef.com/product/solved-cis2250-lab5-arrays-in-perl
<br>
Overview: Arrays in perl

<sup>You have been using arrays in perl for some weeks now, however all of these arrays</sup>have been populated by calling a function from Text::CSV. We have not modified thecontents of the array ourselves.

You can add elements to an array in perl using the push function.

For example, the following code creates an empty array, and then adds two valuesto it: sub printArrayContents {

Lab5/CIS*2250            # place<sub>my @array_argument = @_;</sub>the     f i r s t argument   into                                                                                                                                the variable @array_argument

Determining Unique Values                      i f             ( $#array_argument &gt;= 0 )             {




m <a href="https://courselink.uoguelph.ca/d2l/home/594191">courselink.uoguelph.ca </a>i A. Hamilton-Wright &amp;K. Raymond Overview

Learning objectives:

fieldssetsof values Extracting and examining<sub>#H </sub>Dealing with large data# Managing lists

<h1>Skills</h1>

coordination + communication (3/6) organization + planning (3/6) teamwork (3/6) programming + tools (5/6) strategy (3/6) visualization (0/6)

print          “Array has ”         .        $#array_argument        .    ”             values :
”;

foreach my $iprint         ”

}    else}                          $array_argument [ $i ]Value(0 . . “$#array_argument ).           $i             .               ”              is . ’”” ’
 “;.            {

} } print{ “Array is empty
”; my @list_of_values ;

printArrayContents ( @list_of_values ) ; push( @list_of_values ,printArrayContents ( @list_of_values ) ;”one “); push( @list_of_values ,printArrayContents ( @list_of_values ) ;”two “);

Note thethe order of any of the other values.push function adds the new value to the <em>end </em>of the array, without disturbing

<h2>Task 1 Description: Collecting Unique Values</h2>

will work as follows:For this lab, you are asked to write a program printUniqueColumnValues.pl that

<ul>

 <li>it will take as arguments the name of a csv file to process, and a column to</li>

</ul>




(*)[tal Awareness) to 6 (Main Focus).]The skill scale is from 0 (Fundamen- examine, for example:<sub>perl printUniqueColumnValues.pl WorldBank_EducationData.csv 2 </sub>Image descriptionA pair of work socks. Image sourcefreebie.photography CC BY 3.0 •• in the column of data within the .csv file, a list is collected of any value not yetseenat the end, this list is printed.

This will provide a summary of what the values are within a given “column” of datain the file. scribes rates of education around the world.You will find the WorldBank_EducationData.csv file on CourseLink. This file deIf the file is run as in the example above:

then the expected output is this:perl printUniqueColumnValues.pl WorldBank_EducationData.csv 2

<h2>Overview</h2>

Adjusted<sub>AdjustedAdjusted</sub>AdjustedAdjusted<sup>Adjusted</sup>AdjustedAdjustedAdjustedSeries net<sub>netnetnet</sub>netnetnetnet<sup>net enrolment</sup>enrolmentenrolment<sub>enrolmentenrolment</sub>enrolmentintakeintakeintakepopulation , 15+ years , % femalepopulation , 15+ years ,population , 15+ years ,raterateraterate ,<sub>rate ,</sub>rate ,rate ,<sub>rate ,</sub>rate ,<sup>rate ,</sup>to Grade 1 ofto Grade 1 ofto Grade 1 of<sup>upper secondary ,</sup>upper secondary ,upper secondary ,<sub>primary ,primary ,</sub>primary ,lowerlower secondary ,secondary ,secondary ,male (%)<sub>both sexes (%)</sub>female (%)primaryprimaryprimarymaleboth sexesfemale(number<sup>male (%)</sup>male (%)both sexes (%)both sexes (%)<sub>female (%)</sub>female (%)education ,education ,education ,(number(number)                        )           male (%)both sexes (%)female (%))

AdjustedAdjustedAdult           i l l i t e r a t ei l l i t e r a t ei l l i t e r a t enet enrolmentenrolment              rate ,rate ,               lower AdultAdult

AdjustedAdult i l l i t e r a t enetnet enrolmentpopulation , 15+ years ,

fieldssetsof values Extracting and examining#H Dealing with large data# Managing lists    Be sure to upload your <sup>printUniqueColumnValues.pl </sup>to CourseLink. Learning objectives:

<h2>Skills</h2>

coordination + communication (3/6) organization + planning (3/6) teamwork (3/6) programming + tools (5/6)

strategy (3/6) visualization (0/6)

(*)[tal Awareness) to 6 (Main Focus).]The skill scale is from 0 (Fundamen-

Image description

A pair of work socks. Image sourcefreebie.photography CC BY 3.0