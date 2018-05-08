# A j�t�k specifik�ci�ja

## A specifik�ci� l�tjogosults�ga

- az el�tt�nk l�v� munka megtervez�se
- hat�konyabb� teszi a kommunik�ci�t a r�sztvev�k k�z�tt (fejleszt�k/felhaszn�l�k)
- az �temterv k�sz�t�s�hez egy bemeneti inform�ci� a specifik�ci�
- a d�nt�sek kik�nyszer�t�s�nek egy kiv�l� eszk�ze a specifik�ci�

## A specifik�ci�kr�l b�vebben
Joe Sposky [cikkei a specifik�ci�r�l magyarul](http://hungarian.joelonsoftware.com/Articles/PainlessFunctionalSpecifi-2.html)

## Szerz�
Plesz G�bor, NetAcademia

## �ltal�nos bemutat�s
Szeretn�nk k�sz�teni egy reakci�id� m�r� j�t�kot. A j�t�k egym�s ut�n mutat k�rtyalapokat, �s nek�nk meg kell mondanunk, hogy a mutatott lap egyezik-e az el�z�vel, vagy sem. Ha j�l v�laszolunk pontot kapunk. A j�t�k m�ri az egyes reakci�id�t, �s az �tlagos reakci�id�t is. A v�g�n a top 5 eredm�nyt is megmutatja.

## Szerepl�k
- **Remek Elek**: szeretn� a ment�lis �llapot�t folyamatosan m�rni �s jav�tani, �gy a reakci�id� m�r� j�t�kkal rendszeresen j�tszik. Minden j�t�k ut�n tudja, hogy a reakci�ideje, a kor�bbi j�t�kokhoz k�pest hogy �ll.

## Forgat�k�nyvek
- **Elek** elind�tja az alkalmaz�st, �s n�h�ny j�t�kot j�tszik, ez�ltal k�pet nyer az aktu�lis reakci� idej�r�l, koncentr�ci�k�pess�g�r�l.

## J�t�kmenet
- Kezd�skor kapunk egy k�rty�t, majd a j�t�k kezd�s�vel a k�rty�nkat egy �j v�ltja fel. 
- A visszajelz�s�nkre (egyforma/nem egyforma) a j�t�k jelzi egy z�ld pip�val/piros kereszttel, hogy a v�laszunk helyes vagy helytelen. 
- A v�lasznak megfelel� pontot sz�molja, 
- m�ri az egyes reakci�id�t 
- �s az �tlagos reakci�id�t is. 
- A j�t�k meghat�rozott ideig tart, amit a kezd�st�l egy visszasz�ml�l� �ra jelez. 
- A j�t�k v�g�n l�tjuk a pontsz�munkat, 
- �s a top 5 pontsz�mot. 
- Ha akarjuk �jrakezdhetj�k a j�t�kot, vagy kil�phet�nk.

## A j�t�k f�k�perny�je

```
+---------------------------------------------------------------------------------------------------+
|                                          +-----------------------------------------------------+  |
|  +----------+                            | Inform�ci�k, eredm�ny, visszajelz�s                 |  |
|  |          |                            +-----------------------------------------------------+  |
|  | Toplista |                                                                                     |
|  |          |                                                                                     |
|  |          |                 +---------------------------+        +---------------------------+  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |  Visszajelz�s, hogy a     |        |                           |  |
|  |          |                 |  v�lasz j� volt-e         |        |   K�rtya a j�t�khoz       |  |
|  |          |                 |  vagy sem                 |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  |          |                 |                           |        |                           |  |
|  +----------+                 |                           |        |                           |  |
|                               +---------------------------+        +---------------------------+  |
|                                                                                                   |
|  +---------------------------------------------------------------------------------------------+  |
|  |   K�l�nb�z� gombok, amik egym�s mellett sz�pen k�vetkeznek                                  |  |
|  |                                                                                             |  |
|  +---------------------------------------------------------------------------------------------+  |
+---------------------------------------------------------------------------------------------------+

```