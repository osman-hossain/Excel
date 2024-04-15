<!--comment-->

~~E~~__x__`cel`
---

- [x] Tool bar menue
- [x] Tool bar ribbons
- [x] Dialog box[tool bar more option]
- [x] cell & address row column
- [x] sheet trace sheet size
  
### unorder list

<ul type="square">
<li> shift + right arrow to select multiple cells.
<li> ctrl+shift+down arrow (select all the data in the row)
<li> ctrl+shift+right arrow (select all the data in the column)
<li> in cell =UPPER(A3) drag down to all
<li> in cell =LOWER(A3) drag down to all
<li> 
</ul>

### Tool bar menue

<image src="./images/toolbarmenue.png"/>

### Tool bar ribbons
<image src="./images/toolbarribbons.png"/>

### Dialogbox
<image src="./images/dialogbox.png"/>

### Row & Select the Entire row

<image src="./images/row.png"/>

### Column & Select the Entire column

<image src="./images/column.png"/>

### shiif + right or left or up or down arrow

<p style="text-align:center; color:lightblue;"> select multiple row or column from any side </p>  

### click column + control + shift + arrow down

<p> select all the column only data </p>

### click row + control + shift + arrow right 

<p> select all the row only data </p>

### Upper Case "=UPPER(A3)"

<p style="text-align:center; color:lightblue;"> =UPPER(A3)</p>

### Lower case "=LOWER(A3)"

<p style="text-align:center; color:lightblue;">=LOWER(A3)</p>

### click on row right click and insert

<p> create a new row </p>
<p> select 4 row and insert to create 4 new row </p>

### click on column right click and insert 

<p> create a new column </p>
<p> select 4 column and insert to create 4 new column </p>

### Duplicate & Unique
 
<p> select data + goto menu + Home + conditional formatting + highlight cells rules + duplicate values </p>

<image src="./images/duplicate.png"/>
<image src="./images/unique.png"/>  

### SIMILAR =A3=B3

<p style="text-align:center; color:lightblue;">=A3=B3</p>

in result column "=A3=B3" True or False

<image src="./images/similar.png"/>
<image src="./images/similar1.png"/>
<image src="./images/drag.png"/>  

### similar =IF(A2=B2,"found","not found")

<p style="text-align:center; color:lightblue;">=IF(A2=B2,"Found","Not Found")>

<image src="./images/code.png"/>
<image src="./images/result.png"/>  
  
### compare column 1 cell data to other all column range of data

<p style="text-align:center; color:lightblue; "> =VLOOKUP(B2,$A$2:$A$17,1,0)</p>

<ul type="square">
<li> B2 = compare cell </br>
<li> A2:A17 = comapre to all other cells </br>
<li> 1 = compare to all data in column 1 </br>
<li> 0 = Exact Match </br>
</ul>

<image src="./images/code1.png"/></br>
<image src="./images/compare.png"/></br>

### If error show "Not found" in one compare to lot of 

<p style="text-align:center; color:lightblue;">=IFERROR(VLOOKUP(B2,$A$2:$A$17,1,0),"Not Found")</p></br>

<image src="./images/code2.png"/>
<image src="./images/checkall.png"/>

### compare one to other all but only name and name + surname will add

example: main to other all= result
ali is compare ali banat  = ali banat </br>
abu is compare abu ubaida = abu ubaida  
</br>

If i compare half name and other names where this half name is in the othe name the compare code will add this name

<p style="text-align:center; color:lightblue;"></p>  

<image src="./images/halfnamefullname.png"/>

### N/A or Not Found type

<p style="text-align:center; color:lightblue;"> =IFERROR(VLOOKUP(F2&"*",$A$2:$A$17,1,0))</p>

<image src="./images/notfound.png" width=400 height="200px" border="4px" alt="picture not found" title="Not Found" vspace="5" hspace="5"/>   

