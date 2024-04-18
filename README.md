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

### How to freeze row and column

<p> when scrol down a list the heading dosn't show when it's in bottom, we need to go top to see the heading, but if we freeze heading on top or row on left the the heading will show even if we scrol down </p>  

<li> select any cell from data </li>
</br>
<li> go to view menue & Freeze Panes option & selct both row and column</li>
</br>

<image src="./images/freeze.gif"/>

### Developer Option

Menue bar FIle + Option + Customise Ribbon + Click select Option + developer + ok.

### convert numbers into word format

<ol>
<li> menue bar developer option
<li> google search convert number into words
<li> goto microsoft page convert number into words
<li> return to excel
<li> developer option + Visual Basic (alt + F11)
<li> menue bar insert
<li> module
<li> copy the code from `https://www.ablebits.com/office-addins-blog/convert-numbers-words-excel/`   otherwise show below.
<li> Menue ribbon save
<li> VB project dashboard click, NO
<li> save as Excel Macro-Enabled workbook
<li> goto cell type: `=SpellNumber(A2)` + enter
<li> before exit save as again and select Excel macro enabled workbook then exit
<li> ok.
</ol>

### code to copy paste in module number to words

```
Option Explicit
  'Main Function
  Function SpellNumber(ByVal MyNumber)
      Dim Dollars, Cents, Temp
      Dim DecimalPlace, Count
      ReDim Place(9) As String
      Place(2) = " Thousand "
      Place(3) = " Million "
      Place(4) = " Billion "
      Place(5) = " Trillion "

      MyNumber = Trim(Str(MyNumber))
      DecimalPlace = InStr(MyNumber, ".")
      If DecimalPlace > 0 Then
          Cents = GetTens(Left(Mid(MyNumber, DecimalPlace + 1) & _
                    "00", 2))
          MyNumber = Trim(Left(MyNumber, DecimalPlace - 1))
      End If
      Count = 1
      Do While MyNumber <> ""
          Temp = GetHundreds(Right(MyNumber, 3))
          If Temp <> "" Then Dollars = Temp & Place(Count) & Dollars
          If Len(MyNumber) > 3 Then
              MyNumber = Left(MyNumber, Len(MyNumber) - 3)
          Else
              MyNumber = ""
          End If
          Count = Count + 1
      Loop
      Select Case Dollars
          Case ""
              Dollars = "No Dollars"
          Case "One"
              Dollars = "One Dollar"
           Case Else
              Dollars = Dollars & " Dollars"
      End Select
      Select Case Cents
          Case ""
              Cents = " and No Cents"
          Case "One"
              Cents = " and One Cent"
                Case Else
              Cents = " and " & Cents & " Cents"
      End Select
      SpellNumber = Dollars & Cents
  End Function

  Function GetHundreds(ByVal MyNumber)
      Dim Result As String
      If Val(MyNumber) = 0 Then Exit Function
      MyNumber = Right("000" & MyNumber, 3)
      ' Convert the hundreds place.
      If Mid(MyNumber, 1, 1) <> "0" Then
          Result = GetDigit(Mid(MyNumber, 1, 1)) & " Hundred "
      End If
      ' Convert the tens and ones place.
      If Mid(MyNumber, 2, 1) <> "0" Then
          Result = Result & GetTens(Mid(MyNumber, 2))
      Else
          Result = Result & GetDigit(Mid(MyNumber, 3))
      End If
      GetHundreds = Result
  End Function

  Function GetTens(TensText)
      Dim Result As String
      Result = "" ' Null out the temporary function value.
      If Val(Left(TensText, 1)) = 1 Then   ' If value between 10-19&hellip;
          Select Case Val(TensText)
              Case 10: Result = "Ten"
              Case 11: Result = "Eleven"
              Case 12: Result = "Twelve"
              Case 13: Result = "Thirteen"
              Case 14: Result = "Fourteen"
              Case 15: Result = "Fifteen"
              Case 16: Result = "Sixteen"
              Case 17: Result = "Seventeen"
              Case 18: Result = "Eighteen"
              Case 19: Result = "Nineteen"
              Case Else
          End Select
      Else ' If value between 20-99&hellip;
          Select Case Val(Left(TensText, 1))
              Case 2: Result = "Twenty "
              Case 3: Result = "Thirty "
              Case 4: Result = "Forty "
              Case 5: Result = "Fifty "
              Case 6: Result = "Sixty "
              Case 7: Result = "Seventy "
              Case 8: Result = "Eighty "
              Case 9: Result = "Ninety "
              Case Else
          End Select
          Result = Result & GetDigit _
              (Right(TensText, 1))  ' Retrieve ones place.
      End If
      GetTens = Result
  End Function

  Function GetDigit(Digit)
      Select Case Val(Digit)
          Case 1: GetDigit = "One"
          Case 2: GetDigit = "Two"
          Case 3: GetDigit = "Three"
          Case 4: GetDigit = "Four"
          Case 5: GetDigit = "Five"
          Case 6: GetDigit = "Six"
          Case 7: GetDigit = "Seven"
          Case 8: GetDigit = "Eight"
          Case 9: GetDigit = "Nine"
          Case Else: GetDigit = ""
      End Select
  End Function
  ```

  <image src="./images/dollars.png">

  ### change currency

  From the last work, after paste the code goto menue ribbon find or ctrl+f, then search dollar after that dollars then replace all type below the field pound & pounds. ok.

  ### Only number

  ```
  Option Explicit

'Main Function to Convert Number to Words
Function NumToWords(ByVal MyNumber)
Dim Units As String
Dim SubUnits As String
Dim TempStr As String
Dim DecimalPlace As Integer
Dim Count As Integer
ReDim Place(9) As String
Place(2) = " Thousand "
Place(3) = " Million "
Place(4) = " Billion "
Place(5) = " Trillion "

' Convert MyNumber to string and trim white space
MyNumber = Trim(Str(MyNumber))

' Find position of decimal place 0 if none.
DecimalPlace = InStr(MyNumber, ".")

' Convert SubUnits and set MyNumber to Units amount.
If DecimalPlace > 0 Then
SubUnits = GetTens(Left(Mid(MyNumber, DecimalPlace + 1) & "00", 2))
MyNumber = Trim(Left(MyNumber, DecimalPlace - 1))
End If

Count = 1
Do While MyNumber <> ""
TempStr = GetHundreds(Right(MyNumber, 3))
If TempStr <> "" Then Units = TempStr & Place(Count) & Units
If Len(MyNumber) > 3 Then
MyNumber = Left(MyNumber, Len(MyNumber) - 3)
Else
MyNumber = ""
End If
Count = Count + 1
Loop

NumToWords = Application.Trim(Units & SubUnits)
End Function

' Converts a number from 100-999 into text
Function GetHundreds(ByVal MyNumber)
Dim Result As String
If Val(MyNumber) = 0 Then Exit Function
MyNumber = Right("000" & MyNumber, 3)
' Convert the hundreds place.
If Mid(MyNumber, 1, 1) <> "0" Then
Result = GetDigit(Mid(MyNumber, 1, 1)) & " Hundred "
End If
' Convert the tens and ones place.
If Mid(MyNumber, 2, 1) <> "0" Then
Result = Result & GetTens(Mid(MyNumber, 2))
Else
Result = Result & GetDigit(Mid(MyNumber, 3))
End If
GetHundreds = Result
End Function

' Converts a number from 10 to 99 into text.
Function GetTens(TensText)
Dim Result As String
Result = "" ' Null out the temporary function value.
If Val(Left(TensText, 1)) = 1 Then ' If value between 10-19...
Select Case Val(TensText)
Case 10: Result = "Ten"
Case 11: Result = "Eleven"
Case 12: Result = "Twelve"
Case 13: Result = "Thirteen"
Case 14: Result = "Fourteen"
Case 15: Result = "Fifteen"
Case 16: Result = "Sixteen"
Case 17: Result = "Seventeen"
Case 18: Result = "Eighteen"
Case 19: Result = "Nineteen"
Case Else
End Select
Else ' If value between 20-99...
Select Case Val(Left(TensText, 1))
Case 2: Result = "Twenty "
Case 3: Result = "Thirty "
Case 4: Result = "Forty "
Case 5: Result = "Fifty "
Case 6: Result = "Sixty "
Case 7: Result = "Seventy "
Case 8: Result = "Eighty "
Case 9: Result = "Ninety "
Case Else
End Select
Result = Result & GetDigit(Right(TensText, 1)) ' Retrieve ones place.
End If
GetTens = Result
End Function

' Converts a number from 1 to 9 into text.
Function GetDigit(Digit)
Select Case Val(Digit)
Case 1: GetDigit = "One"
Case 2: GetDigit = "Two"
Case 3: GetDigit = "Three"
Case 4: GetDigit = "Four"
Case 5: GetDigit = "Five"
Case 6: GetDigit = "Six"
Case 7: GetDigit = "Seven"
Case 8: GetDigit = "Eight"
Case 9: GetDigit = "Nine"
Case Else: GetDigit = ""
End Select
End Function
```
<image src="./images/onlynumbers.png">

### some text left some right 

Multiply * 1 all will be one side


<ol>
<li> select a blank cell type 1 
<li> select the whole column of number which has problem.
<li> click right and paste special
<li> multiply
<li> ok
</ol>

### combine cells data in one

<ol>
<li> goto combine blank cell type guess A2, B2 , D2 are combineing data
<li> example abu ubaida : abuubaida@hotmail.com 
<li> Type <p style="text-align:center; color:lightblue;">=A2&" "&B2&" : "&D2</p>
<li>done, drag down to all
</ol>

<image src="./images/codeforcombine.png"/>
<image src="./images/combineresult.png"/>

### Mearge 

menue + home + ribbon + merge 

merge across to multiple merge (select multiple)

###  Date & Time

<ol>
<li> date = ctrl + ; / =TODAY()
<li> time = ctrl + shift + ;
</ol>

#### Date and time format of view change

<ol>
<li> click right on date or dates then click 
<li> Format cells
<li> Date 
<li> custom
<li> ok
</ol>

### Date of birth to Today age count

type in the blank cell where to input </br>
example, A2 field is 19/04/1997 </br>
the date will be 26. </br>

d = day </br>
m = month</br>
y = year</br>

<p style="text-align:center; color:lightblue;"> =DATEDIF(A2,TODAY(),"y")</p>

### Time Duration

How long time does a person work counting way... </br>

example: A2=8:00 AM B2=6:00 </br>

<p style="text-align:center; color:lightblue;"> =B2-A2</p>

