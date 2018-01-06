<!-- pandoc -s --katex -t html5 -o qsts1md.html qsts1md.md -->

## 1. Векторы. Свойства векторов.

**Def** Упорядоченный набор чисел $(a_1, a_2, ... , a_n)$ называется (арифметическим) вектором

**Обозначение** $\vec a = (a_1, a_2, ... , a_n)$

**Свойства**

* $\vec a = \vec b ~\Longleftrightarrow~ \forall~a_i, b_i: a_i = b_i$

* $\vec a + \vec b = \vec c:\forall~ c_i = a_i+b_i~\Longrightarrow~\vec a + \vec b = \vec b + \vec a$

* $\lambda \in R (C):\lambda \vec a = \vec b: \forall~b_i: b_i = \lambda \cdot a_i$

* $\lambda \in R (C): \lambda (\vec a + \vec b) = \lambda \vec a + 
\lambda \vec b$

**Def** $\vec \emptyset = (0, 0, ..., 0)$ — нулевой вектор

**Def** $\vec a'$ — противоположный вектор для $\vec a$

$\vec a' + \vec a = \vec \emptyset$

$\vec a = - \vec a'$

## 2. Линейная зависимость системы векторов. Базис.

**Def** Линейная комбинация векторов $\vec a$ и $\vec b$:

$\lambda \vec a + \mu \vec b$, где $\lambda, \mu \in C$

Если есть множество (система) векторов $\{\vec a_1, \vec a_2, ... , \vec a_n\} = \{\vec a_i\}_{i=1}^n$ имеет больше двух элеметов, то линейная комбинация $\lambda _1 \vec a_1 + \lambda _2 \vec a_2 + ... + \lambda _n \vec a_n = \displaystyle\sum_{i=1}^n \lambda _i \vec a_i$

**Def** $\{\vec a_i\}_{i=1}^n~\lambda _i \in C$

* если $\exists \lambda _i \neq 0$ и $\displaystyle\sum_{i=1}^n \lambda _i \vec a_i = \vec \emptyset$, то такая система называется линейно зависимой. 

* если $\displaystyle\sum_{i=1}^n \lambda _i \vec a_i = 0~\Longleftrightarrow~ \forall \lambda _i = 0$, то такая система называется линейно независимой.


Любые два компланарных вектора на плоскости составляют линейно зависимую систему. Любые некомпланарные — линейно независимы.

## 3. Скалярное произведение векторов и его свойства. 

**Def** Скалярное произведение векторов $\vec a$ и $\vec b$ — число (scalar)

$\vec a \cdot \vec b = a_1 \cdot b_1 + a_2 \cdot b_2 + ... + a_n \cdot b_n = \displaystyle\sum_{i=1}^n a_i b_i$ ($\vec a$ и $\vec b$ одной размерности)

$\vec a \cdot \vec b = |\vec a||\vec b|\cos \varphi$

**Note** Если вектор умножается на себя, говорят о возведении в квадрат, то есть $\vec a \cdot \vec a = \vec a ^ 2 = a_1^2 + a_2^2 + ... + a_n^2$

**Def** Модуль вектора $|\vec a| = \sqrt{\vec a ^2}$

$$\vec a^0 = \frac{\vec a}{|\vec a|}$$ — единичный вектор (орт)

Если $\vec a \cdot \vec b = 0 \Longrightarrow$ они называются ортогональными

Можно вычислить угол между прямыми $$\cos \varphi = \frac{|\vec a \cdot \vec b|}{|\vec a| \cdot |\vec b|}$$

**Def**

- Проекция т. $M$ на прямую $l$ — точка, образованная пересечением $l$ и $\bot$-ом к $l$ через $M$.

- Проекция вектора $$\vec{AB}$$ на ось $l$ — длина вектора $\vec{A'B'}$ со знаком $"+"$, если $\vec{A'B'} \upuparrows \vec l$ и $"-"$ в противном случае.

**Def** Проекция $\vec a$ на $\vec b$ — проекция $\vec a$ на ось $\vec l$, $\vec l \upuparrows \vec b$

$|\vec a'| = |\vec a| \cos \alpha$

$\vec a'$ — проекция $\vec a$ на $\vec b$

В декартовой записи $\vec a = a_x \vec i + a_y \vec j + a_z \vec k$

## 4. Векторное и смешанное произведение векторов. Свойства.

$\vec a \times \vec b = \begin{vmatrix}
\vec i & \vec j & \vec k \\
a_x & a_y & a_z \\
b_x & b_y & b_z
\end{vmatrix}$ — векторное произведение; результат — вектор.

**Свойства**

- $\vec a \times \vec a = 0$

- $\vec a \times \vec b = - \vec b \times \vec a$

- $(\lambda \vec a) \times \vec b = \vec a \times (\lambda \vec b)$

- $(\vec a + \vec b) \times \vec c = \vec a \times \vec c + \vec b \times \vec c$

- Площадь параллелограмма: $S = |\vec a \times \vec b|$

Геометрически векторное произведение определяется через угол:

**Def** $\vec a \times \vec b = \vec c$

$|\vec c| = |\vec a|\cdot|\vec b|\cdot \sin \varphi$

$\vec c \bot \vec a$

$\vec c \bot \vec b$

$\vec a \vec b \vec c = (\vec a \times \vec b) \cdot \vec c$ — смешанное произведение.

Объем параллелепипеда: $V = \pm \vec a \vec b \vec c$ ($"+"$ — если правая тройка, $"-"$ — если левая)

Объем тетраэдра: $$V = \pm \frac{1}{6} \vec a \vec b \vec c$$ ($"+"$ — если правая тройка, $"-"$ — если левая)

$\vec a \cdot \vec b = 0 \Longleftrightarrow \vec a \bot \vec b$ (векторы ортогональны)

$\vec a \times \vec b = 0 \Longleftrightarrow \vec a \parallel \vec b$ (векторы коллинеарны)

$\vec a \vec b \vec c = 0 \Longleftrightarrow \vec a,\vec b, \vec c$ компланарны

## 5. Определители 2-го и 3-го порядка. Разложение определителя по элементам строки.

**Def** Матрица — таблица коэффициентов СЛАУ

**Def** Минор $M_{ij}$ — определитель, получаемый из исходного вычеркиванием $i$-ой строки и $j$-го столбца

$|A| = \begin{vmatrix}
	1 & 2 & 3 & 4 \\
	5 & 6 & 7 & 8 \\
	9 & 10 & 11 & 12 \\
	13 & 14 & 15 &16 
	\end{vmatrix};$
$M_{1,3} = \begin{vmatrix}
	5 & 6 & 8 \\
	9 & 10 & 12 \\
	13 & 14 & 16 
	\end{vmatrix};$
$M_{3,2} = \begin{vmatrix}
	1 & 3 & 4 \\
	5 & 7 & 8 \\
	13 & 15 & 16
	\end{vmatrix}$

**Def** Алгебраическое дополнение $A_{i,j} = (-1)^{i+j} \cdot M_{i,j}$

**Th** Разложение определителя по элементам строки/столбца:

$$det A = \displaystyle\sum_{^{i=const}_{j=1}}^n a_{i,j} \cdot A_{i,j} = \displaystyle\sum_{^{j=const}_{i=1}}^n a_{i,j} \cdot A_{i,j}$$

## 6. Свойства определителей.

- $\lambda |A| = |A| \lambda = \begin{vmatrix} \lambda a_{1,1} & \lambda a_{1,2} \\ a_{2,1} & a_{2,2} \end{vmatrix} = \begin{vmatrix} \lambda a_{1,1} & a_{1,2} \\ \lambda a_{2,1} & a_{2,2} \end{vmatrix}$

- $|A| = \begin{vmatrix}
		 a_{1,1} & \cdots & \cdots & \cdots & a_{1,n} \\
		 \cdots  & \cdots & \cdots & \cdots & \cdots  \\
		 0  	 & 0      & \cdots & 0      & 0	      \\
		 \cdots  & \cdots & \cdots & \cdots & \cdots  \\
		 a_{n,1} & \cdots & \cdots & \cdots & a_{n,n}
		 \end{vmatrix} = 0$

- Любые две строки (столбца) определителя можно сложить, записав результат в одну из них. Значение определителя при этом не изменится. 

**Note** Сложение проходит по элементам, $"-"$ — частный случай $"+"$.

**Доказательство**

$\square~|A| = \begin{vmatrix}
			   a_{1,1} & a_{1,2} \\
			   a_{2,1} & a_{2,2}
			   \end{vmatrix} = \begin{vmatrix}
			   					a_{1,1} + a_{2,1} & a_{1,2} + a_{2,2} \\
			  					a_{2,1} 		  & a_{2,2}
			  				   \end{vmatrix} = a_{2,2} (a_{1,1} + a_{2,1}) - a_{2,1} (a_{1,2} + a_{2,2}) = a_{2,2} a_{1,1} + a_{2,2} a_{2,1} - a_{2,1} a_{1,2} - a_{2,1} a_{2,2} = a_{2,2} a_{1,1} -  a_{2,1} a_{1,2} = |A|~\blacksquare$

- Объединяя свойства 1 и 3 получим следующее: если к строке определителя прибавить любую другую строку домноженную на $\lambda (\lambda \neq 0)$ значение $|A|$ не изменится, то есть:

$\square~|A| = \begin{vmatrix}
			   a_{1,1} & a_{1,2} \\
			   a_{2,1} & a_{2,2}
			   \end{vmatrix} = 
\frac{1}{\lambda} \begin{vmatrix}
			   a_{1,1}         & a_{1,2}         \\
			   \lambda a_{2,1} & \lambda a_{2,2}
			   \end{vmatrix} = \frac{1}{\lambda} 
\begin{vmatrix}
a_{1,1} + \lambda a_{2,1} & a_{1,2} + \lambda a_{2,2} \\
\lambda a_{2,1} & \lambda a_{2,2}
\end{vmatrix} = \frac{1}{\lambda} \cdot \lambda \begin{vmatrix} a_{1,1} + \lambda a_{2,1} & a_{1,2} + \lambda a_{2,2} \\
a_{2,1} & a_{2,2} \end{vmatrix} = |A|~\blacksquare$ 

**Note** Следствием из предыдущих свойств будет то, что определитель с равными (пропорциональными) строками (столбцами) равен $"0"$

- $|A \cdot B| = |A| \cdot |B|$

**Note** Матрицы, определитель которых равен нулю называются вырожденными матрицами. Еще один особый тип матриц — единичный, их определитель равен $"1"$.

## 7. Определители 2-го и 3-го порядка. Теорема Крамера. 

$\sphericalangle$ СЛАУ размерности 3:

$\begin{cases}
a_{1,1} x_1 + a_{1,2} x_2 + a_{1,3} x_3 = b_1 \\
a_{2,1} x_1 + a_{2,2} x_2 + a_{2,3} x_3 = b_2 \\
a_{3,1} x_1 + a_{3,2} x_2 + a_{3,3} x_3 = b_3 
\end{cases}~~~~~~~(**)$ 

Введем следующие определители:

$\Delta = |A|~~~~~~~
\Delta_1 = 
\begin{vmatrix}
b_1 & a_{1,2} & a_{1,3} \\ 
b_2 & a_{2,2} & a_{2,3} \\ 
b_3 & a_{3,2} & a_{3,3} 
\end{vmatrix}~~~~~~~
\Delta_2 = 
\begin{vmatrix}
a_{1,1} & b_1 & a_{1,3} \\ 
a_{2,1} & b_2 & a_{2,3} \\ 
a_{3,1} & b_3 & a_{3,3} 
\end{vmatrix}~~~~~~~
\Delta_3 = 
\begin{vmatrix}
a_{1,1} & a_{1,2} & b_1 \\ 
a_{2,1} & a_{2,2} & b_2 \\ 
a_{3,1} & a_{3,2} & b_3 
\end{vmatrix}$

Для системы другого порядка формула сохраняет свой вид

**Th** Крамера:

$\Delta \neq 0 \Longleftrightarrow \exists !$ решение СЛАУ $(**)$, при чем $$x_i = \frac{\Delta_i}{\Delta}$$

## 8. Системы координат. Преобразования сдвига и поворота.

**Note** Для организации задания положения точки в пространстве необходимо задать начало отсчета, масштаб и направление, при этом, однозначность достигается если количество чисел, определяющих положение точки равно размерности пространства.

- Декартова система координат (прямоугольная)

$(x,y)$ — упорядоченный набор чисел

$d = \sqrt{(x' - x)^2 + (y' - y)^2}$ — расстояние между точками

- Полярная система координат (угловая)

$(\rho, \varphi)$

$\varphi \in [0, 2 \pi)$

Переход декартова $\leftrightarrow$ полярная

$(x,y) \rightarrow (\rho, \varphi)$

$\begin{cases}
\rho = \sqrt{x^2 +y^2} \\
\cos \varphi = \frac{x}{\rho} \\
\sin \varphi = \frac{y}{\rho}
\end{cases}$

$(\rho, \varphi) \rightarrow (x,y)$

$\begin{cases}
x = \rho \cos \varphi \\
y = \rho \sin \varphi
\end{cases}$

#### Преобразования сдвига и поворота

<!-- $Ax^2 + Bxy + Cy^2 +Dx+Ey+F=0$ — исходное -->

- Сдвиг

$\begin{cases}
x = x' + x_0 \\
y = y' + y_0
\end{cases}~~~~~~~$будем искать точку $(x_0, y_0)$ так, чтобы упростить исходное выражение

Координаты начала отсчета в новой системе: $(x_0, y_0)$
<!--
$A(x' + x_0)^2 + B(x' + x_0)(y' + y_0) + C(y' + y_0)^2 +D(x' + x_0)+E(y' + y_0)+F=0$

Сгруппируем слагаемые с $x'$ и $y'$ первой степени

При $x'$:

$2Ax_0 + By_0 + D = 0$

При $y'$:

$Bx_0 + 2Cy_0 + E = 0$

$\begin{cases}
2Ax_0 + By_0 = -D \\
Bx_0 + 2Cy_0 = -E
\end{cases}~~~~~~~$задача найти $x_0, y_0$
-->

- Поворот

<!-- Найдем угол $\alpha$, на который надо повернуть оси координат, чтобы упростить уравнение: -->

Найдем новые координаты в виде разложения по базису:

$\begin{cases}
x' = X \cos \alpha - Y \sin \alpha \\
y' = X \sin \alpha + Y \cos \alpha
\end{cases}$

$\begin{cases}
X = x' \cos \alpha - y' \sin \alpha \\
Y = x' \sin \alpha + y' \cos \alpha
\end{cases}$

<!--
Переобозначим 

$A{x'}^2 +Bx'y'+C{y'}^2 +G = 0$

Подставим

$A(X \cos \alpha - Y \sin \alpha)^2+B(X \cos \alpha - Y \sin \alpha)(X \sin \alpha + Y \cos \alpha)+C(X \sin \alpha + Y \cos \alpha)^2+G = 0$

Выберем $\alpha$ так, чтобы сумма слагаемых с $XY$ $=0$:

$-2A \cos \alpha \sin \alpha - B \sin^2 \alpha + B \cos ^2 \alpha + 2C \cos \alpha \sin \alpha = 0$

$-A \sin 2\alpha + B \cos 2\alpha + C \sin 2\alpha = 0$

$(C-A)\sin 2\alpha + B \cos 2\alpha = 0$

Решая относительно $\alpha$ находим угол поворота, позволяющий свести уравнение к следующему виду (после переобозначения) $\beta X^2 + \gamma Y^2 + \delta = 0$
-->
## 9. Плоскость и ее уравнения.

Уравнения плоскости:

- Векторное $(\vec r - \vec r_0) \vec n = 0$

- Через точку $A(x-x_0) + B(y-y_0) + C(z-z_0) = 0$

- Общее $Ax + By + Cz+ D = 0$

- В отрезках [отсекаемых на осях в декартовой системе координат] $$\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1$$

- Нормальное $x \cos \alpha + y \cos \beta + z \cos \gamma - p = 0$, где $$\mu = \pm \frac{1}{\sqrt{A^2+B^2+C^2}}$$, выбирается так, чтобы свободный член был с $"-"$

## 10. Прямая в пространстве и ее уравнения.

Уравнения прямой:

- Общее $\begin{cases}
		Ax + By + Cz + D = 0 \\
		A'x + B'y + C'z + D' = 0
		\end{cases}$

- Векторное $\vec r - \vec r_0 = \lambda \vec S$

- Каноническое $$\frac{x-x_0}{m} = \frac{y-y_0}{n} = \frac{z-z_0}{p}$$

- Параметрическое $\begin{cases}
					x = x_0 + mt \\
					y = y_0 + nt \\
					z = z_0 + pt
					\end{cases}$

## 11. Прямая на плоскости: уравнения через две точки, каноническое, параметрическое.

- Через две точки $$\frac{x-x_1}{x_1-x_2} = \frac{y-y_1}{y_1-y_2}$$

- Каноническое $$\frac{x-x_0}{m} = \frac{y-y_0}{n}$$

- Параметрическое$\begin{cases}
					x = x_0 + mt \\
					y = y_0 + nt 
					\end{cases}$

## 12. Прямая на плоскости: уравнения каноническое, общее, в отрезках.

- Каноническое $$\frac{x-x_0}{m} = \frac{y-y_0}{n}$$

- Общее $Ax+By+D = 0$

- В отрезках [отсекаемых на осях в декартовой системе координат] $$\frac{x}{a} + \frac{y}{b} = 1$$

## 13. Условия параллельности и перпендикулярности плоскостей и прямых в пространстве.

- Необходимое и достаточное условие параллельности плоскостей: система $\begin{cases}
		Ax + By + Cz + D = 0 \\
		A'x + B'y + C'z + D' = 0
		\end{cases}$ не имеет решений

- Необходимое и достаточное условие перпендикулярности плоскостей: перпендикулярность их векторов ($\vec n_1 \times \vec n_2 = 0$)

- Необходимое и достаточное условие параллельности прямых: параллельность направляющих векторов ($\vec s_1 \cdot \vec s_2 = 0$)

- Необходимое и достаточное условие перпендикулярности прямых: ортогональность направляющих векторов, при этом они лежат в одной плоскости ($\vec s_1 \times \vec s_2 = 0$ и $\vec s_1 \vec s_2 \vec a = 0$)

## 14. Эллипс. Определение, вывод уравнения, характеристики.

**Def** Эллипс — геометрическое место точек, сумма расстояний от которых до двух данных постоянно.

**Вывод уравнения** 

$r_1 + r_2 = const = 2a$

$\sqrt{(x-c)^2+y^2} + \sqrt{(x+c)^2+y^2} = 2a ~\vert\uparrow {}^2$

$(x-c)^2+y^2 = 4a^2 - 4a\sqrt{(x+c)^2+y^2} + (x+c)^2+y^2$

$(x-c)^2 - (x+c)^2 = 4a^2 - 4a \sqrt{(x+c)^2+y^2}$

$-4xc = 4a^2 - 4a\sqrt{(x+c)^2+y^2}~\vert :4$

$a\sqrt{(x+c)^2+y^2} = a^2+xc~\vert\uparrow {}^2$

$a^2(x^2 + 2xc +c^2 + y^2) = a^4 + 2a^2 xc + c^2 x^2$

$a^2 x^2 + a^2 c^2 + a^2 y^2 =a^4 + c^2 x^2$

$(a^2 - c^2)x^2 + a^2 y^2 = a^2 (a^2 - c^2)$

$$\frac{x^2}{a^2} + \frac{y^2}{a^2 - c^2} = 1$$

$a^2 - c^2 = b^2$

$$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$$ — каноническое уравнение эллипса.

**Вывод уравнения эксцентриситета:**

$r_2^2 - r_1^2 =(x+c)^2+y^2 - (x-c)^2+y^2 = 2c \cdot 2x = 4xc$ 

$r_1 + r_2 = 2a$

$\begin{cases}
r_2 - r_1 = \dfrac{2cx}{a} \\
r_2 + r_1 = 2a
\end{cases} 
\Longleftrightarrow 
\begin{cases}
r_1 = a - \dfrac{c}{a} x \\
r_2 = a + \dfrac{c}{a} x
\end{cases}$

Обозначим $\dfrac{c}{a} = \varepsilon$ — эксцентриситет

$r_{1,2} = a \pm \varepsilon x$

$\varepsilon = \dfrac{\sqrt{a^2 - b^2}}{a} = \sqrt{1 - \dfrac{b^2}{a^2}}$


**Вывод уравнения директрисы:**

Задача: найти уравнения прямых, таких что $\dfrac{r_{1,2}}{d} = const$, где $d = \rho(M, line)$

$$r_1: \frac{r_1}{d} = \frac{a - \varepsilon x}{l - x} = \frac{\varepsilon (\frac{a}{\varepsilon} - x)}{l - x} = \varepsilon$$

Таким образом, одно из уравнений $x = \dfrac{a}{\varepsilon}$, второе — $x = -\dfrac{a}{\varepsilon}$

Таким образом, эксцентриситет — отношение расстояний от любой точки эллипса до фокуса и некоторой прямой (директрисы), для окружности отношение принято $=0$.

## 15. Гипербола. Определение, вывод уравнения, характеристики.

**Def** Гипербола — геометрическое место точки, модуль разности расстояний от которых до двух данных точек постоянен.

**Вывод уравнения** 

$|r_2 - r_1| = 2a$

$|\sqrt{(x-c)^2+y^2} - \sqrt{(x+c)^2+y^2}| = 2a$

Обе части $\geq 0$, так как $a \geq 0$

$\sqrt{(x-c)^2+y^2} - \sqrt{(x+c)^2+y^2} = 2a ~\vert\uparrow {}^2$

$(x-c)^2+y^2 = 4a^2 - 4a\sqrt{(x+c)^2+y^2} + (x+c)^2+y^2$

$(x-c)^2 - (x+c)^2 = 4a^2 + 4a\sqrt{(x+c)^2+y^2}$

$-4xc = 4a^2 + 4a\sqrt{(x+c)^2+y^2}~\vert :4$

$a\sqrt{(x+c)^2+y^2} = -a^2-xc~\vert\uparrow {}^2$

$a^2(x^2 + 2xc +c^2 + y^2) = a^4 + 2a^2 xc + c^2 x^2$

$a^2 x^2 + a^2 c^2 + a^2 y^2 =a^4 + c^2 x^2$

$(a^2 - c^2)x^2 + a^2 y^2 = a^2 (a^2 - c^2)$

$$\frac{x^2}{a^2} + \frac{y^2}{a^2 - c^2} = 1$$

$c^2 - a^2 = b^2$

$$\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1$$ — каноническое уравнение гиперболы.

Выразим $y$:

$$\frac{y^2}{b^2} = \frac{x^2}{a^2} - 1$$

$$y = \pm \frac{b}{a} \sqrt{x^2 - a^2}$$

$$y = \pm \frac{b}{a} x \sqrt{1 - \frac{a^2}{x^2}}$$

Если $x \rightarrow \infty \Longrightarrow \sqrt{1 - \dfrac{a^2}{x^2}} \rightarrow 1 \Longrightarrow y \rightarrow \dfrac{b}{a}x$ 

$$y = \pm \frac{b}{a}x $$ — уравнение асимптот гиперболы.

**Эксцентриситет**

$$\varepsilon = \frac{c}{a} > 1$$, так как $c > a$

**Директриса**

$$x = \pm \frac{a}{\varepsilon}$$

## 16. Парабола. Определение, вывод уравнения, характеристики.

**Def** Парабола — геометрическое место точек, равноудаленных от данной точки и данной прямой (точка — фокус, прямая — директриса).

**Вывод уравнения**

$r = d$

$$\sqrt{(x - \frac{p}{2})^2 + y^2} = \sqrt{(x + \frac{p}{2})^2}~\vert\uparrow {}^2$$

$$(x - \frac{p}{2})^2 + y^2 = (x + \frac{p}{2})^2$$

$y^2 = 2xp$ — каноническое уравнение.

Параметр $p$ — параболический параметр.

**Эксцентриситет**

$\varepsilon = \dfrac{r}{d}$

## 17. Общее уравнение кривых 2-го порядка. Сведение к каноническим уравнениям эллипса и гиперболы (центральные кривые).

$Ax^2 + Bxy + Cy^2 +Dx+Ey+F=0$ — общее уравнение кривых второго порядка.

**Def** Центральная кривая — кривая, имеющая один центр (эллипс, гипербола)

- Сдвиг

$\begin{cases}
x = x' + x_0 \\
y = y' + y_0
\end{cases}~~~~~~~$будем искать точку $(x_0, y_0)$ так, чтобы упростить исходное выражение

$A(x' + x_0)^2 + B(x' + x_0)(y' + y_0) + C(y' + y_0)^2 +D(x' + x_0)+E(y' + y_0)+F=0$

Сгруппируем слагаемые с $x'$ и $y'$ первой степени

При $x'$:

$2Ax_0 + By_0 + D = 0$

При $y'$:

$Bx_0 + 2Cy_0 + E = 0$

$\begin{cases}
2Ax_0 + By_0 = -D \\
Bx_0 + 2Cy_0 = -E
\end{cases}~~~~~~~$задача найти $x_0, y_0$

$\Delta = \begin{vmatrix}2A & B \\ B & 2C \end{vmatrix} = 4AC - B^2$

Для центральных кривых $\Delta \neq 0$

Координаты начала отсчета в новой системе: $(x_0, y_0)$

- Поворот

Найдем угол $\alpha$, на который надо повернуть оси координат, чтобы упростить уравнение: 

$\begin{cases}
x' = X \cos \alpha - Y \sin \alpha \\
y' = X \sin \alpha + Y \cos \alpha
\end{cases}$

Переобозначим 

$A{x'}^2 +Bx'y'+C{y'}^2 +G = 0$

Подставим

$A(X \cos \alpha - Y \sin \alpha)^2+B(X \cos \alpha - Y \sin \alpha)(X \sin \alpha + Y \cos \alpha)+C(X \sin \alpha + Y \cos \alpha)^2+G = 0$

Выберем $\alpha$ так, чтобы сумма слагаемых с $XY$ $=0$:

$-2A \cos \alpha \sin \alpha - B \sin^2 \alpha + B \cos ^2 \alpha + 2C \cos \alpha \sin \alpha = 0$

$-A \sin 2\alpha + B \cos 2\alpha + C \sin 2\alpha = 0$

$(C-A)\sin 2\alpha + B \cos 2\alpha = 0$

Решая относительно $\alpha$ находим угол поворота, позволяющий свести уравнение к следующему виду (после переобозначения) $\beta X^2 + \gamma Y^2 + \delta = 0$

## 18. Общее уравнение кривых 2-го порядка. Сведение к каноническому уравнению параболы (нецентральные кривые).

$Ax^2 + Bxy + Cy^2 +Dx+Ey+F=0$ — общее уравнение кривых второго порядка.

**Def** Нецентральная кривая — кривая, не имеющая центра (парабола)

- Сдвиг

$\begin{cases}
x = x' + x_0 \\
y = y' + y_0
\end{cases}~~~~~~~$будем искать точку $(x_0, y_0)$ так, чтобы упростить исходное выражение

$A(x' + x_0)^2 + B(x' + x_0)(y' + y_0) + C(y' + y_0)^2 +D(x' + x_0)+E(y' + y_0)+F=0$

Сгруппируем слагаемые с $x'$ и $y'$ первой степени

При $x'$:

$2Ax_0 + By_0 + D = 0$

При $y'$:

$Bx_0 + 2Cy_0 + E = 0$

$\begin{cases}
2Ax_0 + By_0 = -D \\
Bx_0 + 2Cy_0 = -E
\end{cases}~~~~~~~$задача найти $x_0, y_0$

$\Delta = \begin{vmatrix}2A & B \\ B & 2C \end{vmatrix} = 4AC - B^2$

Для центральных кривых $\Delta = 0$

Координаты начала отсчета в новой системе: $(x_0, y_0)$

- Поворот

Найдем угол $\alpha$, на который надо повернуть оси координат, чтобы упростить уравнение: 

$\begin{cases}
x' = X \cos \alpha - Y \sin \alpha \\
y' = X \sin \alpha + Y \cos \alpha
\end{cases}$

Переобозначим 

$A{x'}^2 +Bx'y'+C{y'}^2 +G = 0$

Подставим

$A(X \cos \alpha - Y \sin \alpha)^2+B(X \cos \alpha - Y \sin \alpha)(X \sin \alpha + Y \cos \alpha)+C(X \sin \alpha + Y \cos \alpha)^2+G = 0$

Выберем $\alpha$ так, чтобы сумма слагаемых с $XY$ $=0$:

$-2A \cos \alpha \sin \alpha - B \sin^2 \alpha + B \cos ^2 \alpha + 2C \cos \alpha \sin \alpha = 0$

$-A \sin 2\alpha + B \cos 2\alpha + C \sin 2\alpha = 0$

$(C-A)\sin 2\alpha + B \cos 2\alpha = 0$

Решая относительно $\alpha$ находим угол поворота, позволяющий свести уравнение к следующему виду (после переобозначения) $\beta X^2 + \gamma Y^2 + \delta = 0$

## 19. Матрицы: определения, действия с матрицами.

**Def** Матрица — таблица коэффициентов СЛАУ

**Def** Если $m = n$, матрица называется квадратной.

Для квадратной матрицы вводится понятие главной и побочной диагонали

**Def** Матрица _полностью_ состоящая из нулей называется нулевой.

**Def** $\begin{pmatrix}
		1 & 0 & \cdots & 0 \\
		0 & 1 & \cdots & 0 \\
		\cdots & {} & \ddots & {} \\
		0 & 0 & \cdots & 1
		\end{pmatrix}$ — единичная матрица

**Свойства и действия**

- $A = B \Longleftrightarrow a_{i,j} = b_{i,j}$

- $A + B = C: c_{i,j} = a_{i,j} + b_{i,j}$

	- $A + B = B + A$

	- $(A + B ) + C = A + (B + C)$

- $\lambda \in R;~\lambda A = C: c_{i,j} = \lambda a_{i,j}$

	- $\lambda A = A \lambda$

	- $\lambda (A+B) = \lambda A + \lambda B$

	- $(\lambda + \mu)A = \lambda A + \mu A$

	- $(\lambda \mu) A = \lambda (\mu A)$

- $A': A + A' = \emptyset$

	$A' = -A$

- $A \cdot B = C: c_{i,j} = \displaystyle\sum_{k=1}^n a_{i,k} \cdot b_{k, j}$ 

	$A \cdot B \neq B \cdot A$

	$\emptyset \cdot A = A \cdot \emptyset$

	$E \cdot A = A \cdot E$

	- $(A+ B)C = AC + BC$

	- $C(A+B) = CA + CB$

	- $\lambda(AB) = (\lambda A)B$

	- $(AB)C=A(BC)$

## 20. Обратная матрица. Существование и единственность обратной матрицы.

$A^{-1} = \dfrac{1}{\Delta} 
\begin{pmatrix}
A_{1,1} & A_{2,1} \\
A_{1,2} & A_{2,2}
\end{pmatrix}^T$ — обратная матрица для матрицы $A$.

**Th** Единственность обратной матрицы

Если существует $B: BA = E; C: AC = E \Longrightarrow B = C$

$\square~B = BE = B(AC) = (BA)C = C~\blacksquare$

$B=C=A^{-1}$

$A^{-1}A = AA^{-1} = E $

**Th** Существование обратной матрицы

Если $|A| \neq 0 \Longleftrightarrow \exists A^{-1}$

$\square~\Longleftarrow$ Дано: $\exists A^{-1}~? \Longrightarrow |A| \neq 0$

$\exists A^{-1}: AA^{-1} = E$, по свойству определителя: $|AA^{-1}| = |A||A^{-1}| = |E| = 1$, тогда ни один из определителей слева не равен нулю.

$\Longrightarrow$ Дано: $|A| \neq 0~? \Longrightarrow \exists A^{-1}$

Будем доказывать на примере матрицы 2х2:

$A = \begin{pmatrix}
a_{1,1} & a_{1,2} \\
a_{2,1} & a_{2,2}
\end{pmatrix}$

Составим $B = \begin{pmatrix}
\frac{A_{1,1}}{\Delta} & \frac{A_{2,1}}{\Delta} \\
\frac{A_{1,2}}{\Delta} & \frac{A_{2,2}}{\Delta}
\end{pmatrix}$, где $A_{i,j}$ — алгебраическое дополнение.

$\Delta = |A| \neq 0$

Убедимся, что $B = A^{-1}$:

$AB = \dfrac{1}{\Delta} \begin{pmatrix}
a_{1,1} & a_{1,2} \\
a_{2,1} & a_{2,2}
\end{pmatrix} 
\begin{pmatrix}
a_{2,2} & -a_{1,2} \\
-a_{2,1} & a_{1,1}
\end{pmatrix} = \dfrac{1}{\Delta}
\begin{pmatrix}
a_{1,1} a_{2,2} - a_{2,1} a_{1,2} & a_{1,1} a_{1,2} - a_{1,1} a_{1,2} \\
a_{2,1} a_{2,2} - a_{2,1} a_{2,2} & a_{1,1} a_{2,2} - a_{2,1} a_{1,2}
\end{pmatrix} =
\dfrac{1}{\Delta}
\begin{pmatrix}
\Delta & 0 \\
0 & \Delta
\end{pmatrix} =
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}~
\blacksquare$

## 21. Элементарные преобразования матриц. Ранг матрицы.

$\sphericalangle$ произвольную матрицу $A = 
\begin{pmatrix}
a_{1,1} & \cdots & a_{1,n} \\
a_{2,1} & \cdots & a_{2,n} 
\end{pmatrix}$. В ней можно выделить квадратные матрицы и вычислить их определители. Выберем из найденных определителей ненулевой наивысшего порядка.

**Def** Ранг матрицы — наивысший порядок ненулевого минора матрицы. 

**Def** Элементарные преобразования — преобразования строк и столбцов матрицы, не меняющие ее ранга.

**Def** Матрицы, получаемые элементарными преобразованиями называются эквивалентными. 

Элементарными преобразованиями любую матрицу можно свести к виду, когда в гланой диагонали находятся все $"1"$, а все остальные места занимают $"0"$. Этот вид называется каноническим. Для квадратной невырожденной матрицы канонической будет $E$ матрица.

Приведение к каноническому виду — один из способов определения вырожденности.

Если определитель матрицы не равен нулю, ранг матрицы равен ее размерности.

## 22. Системы линейных уравнений: определения, матричный вид. Теорема Кронекера-Капелли.

**Def** СЛАУ называется совместной, если имеет решение.

**Def** Слау называется определенной, если имеет 1 решение.

**Th**

$\begin{cases}
a_{1,1} x_1 + a_{1,2} x_2 + \cdots + a_{1,n} x_n = b_1 \\
a_{2,1} x_1 + a_{2,2} x_2 + \cdots + a_{2,n} x_n = b_2 \\
\cdots \\
a_{m,1} x_1 + a_{m,2} x_2 + \cdots + a_{m,n} x_n = b_m 
\end{cases}$

Тогда

$A|B = 
\left( \!\!\! \begin{array}{rccl|c}
	a_{1,1} & a_{1,2} & \cdots & a_{1,n} & b_{1} \\
	a_{2,1} & a_{2,2} & \cdots & a_{2,n} & b_{2} \\
	\cdots & {} & {} & {} & {} \\
	a_{m,1} & a_{m,2} & \cdots & a_{m,n} & b_{m} 
\end{array}\!\!\! \right)$

Если $rang~A = rang~ \tilde{A} \Longleftrightarrow \exists$ решения.

$rang~A = rang~ \tilde{A}= n \Longleftrightarrow \exists !$ решение.

$\square$ Запишем систему

$X_1 \begin{pmatrix} a_{1,1} \\ a_{2,1} \\ \cdots \\ a_{m,1} \end{pmatrix} + X_2 \begin{pmatrix} a_{1,2} \\ a_{2,2} \\ \cdots \\ a_{m,2} \end{pmatrix} + \cdots + X_n \begin{pmatrix} a_{1,n} \\ a_{2,n} \\ \cdots \\ a_{m,n} \end{pmatrix} = \begin{pmatrix} b_{1} \\ b_{2} \\ \cdots \\ b_{m} \end{pmatrix}$

Обозначим $A^1, A^2, \cdots, A^n$ — столбцы основной матрицы.

$\longrightarrow$ Если $rang~A = rang~ \tilde A \Longrightarrow \exists$ решение.

Пусть $rang~A=rang~ \tilde A = r$

Согласно одному из определений ранга, это количество линейно независимых столбцов матрицы. $A$ содержит $r$ линейно независимых столбцов, так же как и $\tilde A \Longrightarrow$ столбец $B$ не входит в набор линейно независимых, а это значит, что он может быть выражен как линейная комбинация линейно независимых (базисных) столбцов матрицы $A$, то есть $\exists$ такие числа $(c_1, c_2, \cdots, c_n): B = c_1 A^1 + c_2 A^2 + \cdots + c_n A^n$, то есть $\exists$ решение СЛАУ $\begin{pmatrix} c_1 \\ c_2 \\ \cdots \\ c_n \end{pmatrix} = \begin{pmatrix} x_1 \\ x_2 \\ \cdots \\ x_n \end{pmatrix}$  

$\longleftarrow$: $\exists$ решение $\Longrightarrow rang~A=rang~ \tilde A$

$\exists$ числа $(c_1, c_2, \cdots, c_n)$ — решение СЛАУ: $c_1 A^1 + c_2 A^2 + \cdots + c_n A^n = B$ — верно.

Пусть $rang~A = r$, так как $B$ выражен линейной комбинацией векторов $(A^1, A^2, \cdots, A^n) \Longrightarrow$ $B$ — линейно зависим по отношению к системе векторов $A$. Значит $\tilde A$ имеет то же количество линейно независимых векторов, что и $A$ $\Longrightarrow$ $rang~A = rang~ \tilde A = r$ $\blacksquare$

## 23. Системы линейных уравнений: однородные и неоднородные системы. Линейный оператор и его свойства.

**Def** 

- $AX = B; B \neq \emptyset$ — неоднородная СЛАУ

- $AX = B; B = \emptyset$ — однородная СЛАУ

**Def** Правило $L$, по которому элементу $x$ сопоставляется элемент из того же пространства и которое подчиняется свойствам линейности: 

$\begin{cases} 
L (x_1+x_2) = L(x_1) + L(x_2) \\ 
L ( \lambda x) = \lambda L(x) 
\end{cases}$ 

называется линейным оператором.

В решении СЛАУ применение линейного оператора равносильно умножению $A$ на вектор $X$

**Th1** Пусть $X_1$, $X_2$ — решения однородной СЛАУ. Тогда $Z = c_1 X_1 + c_2 X_2$, где $c_1$, $c_2$ — произвольные числа, $Z$ — решение однородной СЛАУ

$\square$ $X_1$, $X_2$ — решения $\Longrightarrow$ $L[X_1] = \emptyset, L[X_2] = \emptyset$

$L[Z] = L[c_1 X_1 + c_2 X_2] = c_1 L[X_1] + c_2 L[X_2] = \emptyset$ $\blacksquare$

**Th** Пусть $Z$ — решение однородной СЛАУ ($AZ = 0$) и $X^*$ — частное решение неоднородной СЛАУ ($AX^* = B$), тогда $X = Z+X^*$ — частное решение неоднородной СЛАУ.

$L[X] = L[Z+X^*] = L[Z] + L[X^*] = B$

## 24. Системы линейных уравнений: однородные и неоднородные системы. Структура общего решения. Фундаментальная система решений.

**Def** 

- $AX = B; B \neq \emptyset$ — неоднородная СЛАУ

- $AX = B; B = \emptyset$ — однородная СЛАУ

**Def** 

$AX = \emptyset$

$\{ X_1, X_2, \cdots, X_n \}$ линейно независимые решения $A$ и $\forall$ $X_i = \displaystyle\sum_{j=1}^k C_j X_j;~ X_j \in \{ X_1, X_2, \cdots, X_k \}$, тогда $\{ X_1, X_2, \cdots, X_k \}$ — фундаментальная система решений (ФСР).

ФСР — базис решений однородной СЛАУ

Структура ФСР: $X = X_0 + \tilde X$ (общее решение линейной неоднородной системы состоит из общего решения однородной системы и частного решения неоднородной системы)