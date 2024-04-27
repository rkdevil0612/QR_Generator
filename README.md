# QR_Generator
Generate QR using HTML

Main line of code:

          <img src="https://image-charts.com/chart?chs=150x150&cht=qr&chl=youtube.com&chof=.png&icqrb=00FF00&icrf=00FF00">

In above main line, major components are:
1. chs: ChartSize    (150x150)
2. cht: ChartType    (qr)
3. chl: ChartLink    (youtube.com)
4. chof: ChartOutput (can be .svg or .png), Default is png.
5. icrf: ForeGroundColor (Accepts hexadecimal values)
6. icrb: BachgroundColor (Accepts hexadecimal values).

Hexadecimal Values of colors:
1. FF0000 = Red
2. 00FF00 = Green
3. 0000FF = Blue
4. 000000 = Black
5. FFFFFF = White
   
(NOTE: Inorder to add new attributes us have to end the attributes with & symbols after giving value to it.

You can change the parameters based on your requirements.


For More detailed info refer - https://documentation.image-charts.com/qr-codes/
