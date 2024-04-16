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

### Transpose

select a group of cells + copy + goto another new sheet then left corner paste option arrow + transpose.ok. other right clik and select paste transpose logo . 

<image src="./images/transpose.png"/>

### group & ungroup Hide & Unhide row & column

<ul type="square">
<li> Select multiple column or row
<li> got to menue bar select data
<li> At the right corner select group
<li> on the top of the cell a - arrow will show click to hide + to unhide.
<li> at the right top corner select that group and click ungroup to Ungroup the group cells
</ul>

<image src="./images/groupungroup.gif"/>


<p style="text-align:center; color:lightblue;"></p>

### delete coloumn or row

select multiple or single row or column and right click delete

### select blank row and column

Select the data and goto home menue then find and select at the right corner then goto special then blank.

### delete blank select column or row or cells 

 click ctrl + - key  then delete row or column

 ### count how many data has in the row

 <p style="text-align:center; color:lightblue;">=COUNTA(A2:G2)</p>

 drag down to all the cells automatically count the data input in cells

### delete row which is totally blank, which has not even one data

After count and drag down all data, ctrl+A select all data, ctrl+T,goto count more option, deselect except 0, then ok. ctrl + -,delete. goto count option again and clear filter from count.

<image src="./images/deleteblank.png"/>

### select all data

control+A

### create table

control+T



