<p align="center">
<a href="https://colab.research.google.com/github/sinankamilcelebi/Pigeonhole_Principle/blob/master/Phone_Area_Code_Region_Count_(Pigeonhole_Principle).ipynb">
<img src="https://colab.research.google.com/assets/colab-badge.svg" width="150" height="50" alt="Open In Colab"/>
</a>
</p>

# Pigeonhole Principle

* @file     : Phone_Area_Code_Region_Count_(Pigeonhole_Principle).ipynb   
* @author   : Sinan KAMILCELEBI   
* @version  : V1.0.1   
* @date     : 08-March-2019   
* @brief    : Telefon Alan Kodu Bölge Sayısı (Güvercin Yuvası İlkesi).

## Örnek Soru: 
K milyon telefon abonesi bulunan bir ülkede, telefon numaraları bölge kodundan sonra NXX-XXXX (N = (2...9), X = (0...9)) biçimindedir. Buna göre bu ülkede en az kaç bölge vardır?

## Çözüm: 
K = 25 ise.   
Bir bölgede 8 x 10 ^ 6 olası telefon numarası vardır. 25 milyon telefon numarası arasından en az ((25 x 10 ^ 6) / (8 x 10 ^ 6)) = 4 tanesi aynıdır. Bu durumda en az 4 bölge vardır.

## Açıklamalar: 

<p align = "center">
<img src = "pigeonhole_principle_I.jpg" alt = "Pigeonhole Principle" title = "Pigeonhole Principle" width = "300" height = "350" />
</p>

g, y ∈ Z+   
g : Güvercin Sayısını,  
y : Yuva Sayısını göstermek üzere:     

> En az bir yuva ceil(g / y) güvercin içerir.   
NOT: g ≤ y olması durumunda dahi ceil(g / y) = 1 olacaktır.

Örnek olarak g = 4 ve y = 3 ise en az bir yuva ceil(4 / 3) = 2 güvercin içerir.  

<p align = "center">
<img src = "pigeonhole_principle_II.jpg" alt = "Pigeonhole Principle" title = "Pigeonhole Principle" width = "300" height = "100" />
</p>

Yukarıdaki örnekte K ifadesi güvercin sayısını, bir bölgedeki olası telefon numara sayısı ise güvercin yuvasını temsil etmektedir. Ülkedeki en az bölge sayısını, telefon abone sayısını (güvercin sayısı) bir bölgedeki olası telefon numara sayısına (yuva sayısı) bölerek elde ederiz.
 
