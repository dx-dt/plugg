# Lösning av ekvationssystem med substitutionsmetoden
Vi har följande ekvationssystem bestående av ekvationerna A och B:

$$\begin{cases}
    162x + 108y = 24 & \textcircled{\raisebox{-1.1pt}{A}}\\
    54x - 162y = -36 & \textcircled{\raisebox{-1.1pt}{B}}\\
\end{cases}$$

## 1. Separera ut en variabel i en av ekvationerna och förenkla

Vi börjar med att välja en av dem, möblerar om så att vi får x ensam i vänsterled och förenklar så långt vi kan. B ser ut att vara den trevligare av dem:

$$54x - 162y = -36 \tag{1.a}$$

Vi subtraherar $162y$ från båda leden för att få $x$ och $y$ i varsit led:

$$54x = 162y -36 \tag{1.b}$$

Vi dividerar båda leden med 54 för att få $x$ ensamt i vänsterledet:

$$x = \frac{162y - 36}{54} \tag{1.c}$$

Sedan primatalsfaktoriserar vi högerledet:

$$x = \frac{2 \cdot 3^4 \cdot y - 2^2 \cdot 3^2}{2 \cdot 3^3} \tag{1.d}$$

Vi kan sedan fortsätta med att bryta upp högerledet i två bråk:

$$x = \frac{2 \cdot 3^4 \cdot y}{2 \cdot 3^3}-\frac{2^2 \cdot 3^2}{2 \cdot 3^3} \tag{1.e}$$

I den första termen i högerledet kan vi stryka en faktor $2 \cdot 3^3$ och helt bli av med nämnaren:

$$x = 3y-\frac{2^2 \cdot 3^2}{2 \cdot 3^3} \tag{1.f}$$

I den andra termen kan vi stryka en faktor $2 \cdot 3^2$:

$$x = 3y-\frac{2}{3} \tag{1.g}$$

## 2. Subsitutera in uttrycket för x i den andra ekvationen och förenkla

Vi börjar med att subsitituera in uttrycket i högerledet från ekvationen vi erhöll i steg 1.g i den _andra_ ekvationen, alltså A:

$$162\cdot(3y-\frac{2}{3}) + 108y = 24 \tag{2.a}$$

Vi fortsätter med att multiplicera in $162$ i parentesen:

$$162 \cdot 3y-\frac{162 \cdot 2}{3} + 108y = 24 \tag{2.b}$$

Därefter flyttar subtraherar vi den andra termen i vänsterledet från båda led för att få y-termerna ensamma:

$$162 \cdot 3y + 108y = 24 + \frac{162 \cdot 2}{3} \tag{2.c}$$

Vi stryker därefter en faktor 3 i den andra termen i högerledet:

$$162 \cdot 3y + 108y = 24 + 54 \cdot 2 \tag{2.d}$$

Därefter kan vi faktorisera båda leden:

$$2 \cdot 3^5 \cdot y + 2^2 \cdot 3^3 \cdot y = 2^3\cdot 3 + 2^2 \cdot 3^3 \tag{2.e}$$

I vänsterled kan vi bryta ut $2 \cdot 3^3 \cdot y$ ur respektive term:

$$ 2 \cdot 3^3 \cdot y \cdot (3^2 + 2) = 2^3\cdot 3 + 2^2 \cdot 3^3 \tag{2.f}$$

I högerled kan vi bryta ut en faktor $2^2 \cdot 3$ respektive term:

$$ 2 \cdot 3^3 \cdot y \cdot (3^2 + 2) = 2^2 \cdot 3 \cdot (2 + 3^2) \tag{2.g}$$

Båda led kan delas med faktorn $(3^2 + 2)$, vartefter vi kan stryka den faktorn:

$$ 2 \cdot 3^3 \cdot y = 2^2 \cdot 3  \tag{2.h}$$

Dividera båda leden med $2 \cdot 3^3$ och stryk i vänsterledet:

$$ y = \frac{2^2 \cdot 3}{2 \cdot 3^3}  \tag{2.i}$$

Alltså:

$$ y = \frac{2 \cdot 3}{3^2} = \frac{2}{9}  \tag{2.j}$$

## 3. Subsitutera in uttrycket för y i den första ekvationen och förenkla

Eftersom uttrycket vi kom fram till i steg 1.9 är logiskt ekvivalent så kan vi använda det istället för ekvation A:

$$x = 3y-\frac{2}{3} \tag{3.a}$$

Substituera in $\frac{2}{9}$ istället för y:

$$x = 3(\frac{2}{9})-\frac{2}{3} \tag{3.b}$$

Multiplicera in 3 i parentesen:

$$x = \frac{6}{9}-\frac{2}{3} \tag{3.c}$$

Alltså:

$$x = \frac{2}{3}-\frac{2}{3} = 0 \tag{3.d}$$

## 4. Kontrollera

Vi har alltså kommit fram till $x = 0$ och $y = \frac{2}{9}$

Vi börjar med att kontrollera att VL = HL för dessa värden i ekvation A:

$$VL = 162 \cdot 0 + 108 \cdot \frac{2}{9} = \frac{2\cdot 108}{9} = \frac{2\cdot 3\cdot 36}{9} = \frac{2\cdot 3^2\cdot 12}{9} = \frac{2\cdot 9 \cdot 12}{9} = 2 \cdot 12 = 24 = HL \tag{4.a}$$

Och därefter gör vi samma kontroll i ekvation B:

$$ VL = 54 \cdot 0 - 162 \cdot \frac{2}{9} = -\frac{2\cdot162}{9} = -\frac{2\cdot3\cdot54}{9} = -\frac{2\cdot3^2\cdot18}{9} = -\frac{2\cdot9\cdot18}{9} = -2\cdot18 = -36 = HL  \tag{4.b}$$

Klart!


