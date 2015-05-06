Distribuția normală
===================

Variabila aleatoare :math:`X` are *repartiţie normală* (sau *Gauss-Laplace*) cu parametrii :math:`m` şi :math:`\sigma` (:math:`m\in\mathbb R,\sigma>0`) dacă densitatea sa de probabilitate este funcția

.. math::

   f_X(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-m)^2}{2\sigma^2}},
   
pentru orice :math:`x\in\mathbb R`.

Despre parametrii :math:`m` şi :math:`\sigma` se știe că: :math:`m=m_X` şi :math:`\sigma=\sigma_X=\sqrt{D_X}`.
Funcţia :math:`f_X` de mai sus se numește *densitatea de repartiție normală* (sau *gaussiană*).
Despre o variabilă aleatoare cu repartiţie normală cu parametrii :math:`m` şi :math:`\sigma` se mai spune că are repartiţia :math:`N(m,\sigma)`.
În particular, dacă :math:`X` are repartiţia :math:`N(0,1)`, atunci spunem că :math:`X` are *repartiţia normală standard*  (sau *normală centrată redusă*). Funcția de repartiție a variabilei cu :math:`N(0,1)` se notează :math:`\Phi(x)` și 

.. math::

   \Phi(x)=\frac{1}{\sqrt{2\pi}}\int_{-\infty}^x e^{-\frac{t^2}{2}}dt.

Funcţia :math:`\Phi` de mai sus se numește *funcția integrală a lui Laplace*, pentru valorile căreia sunt întocmite tabele.

Dacă variabila :math:`X` are repartiția :math:`N(m,\sigma)`, atunci variabila :math:`Y=\frac{1}{\sigma}(X-m)` are repartiţia :math:`N(0,1)`. Astfel funcția de repartiție a variabilei :math:`X` poate fi exprimată prin funcția de repartiție a variabilei :math:`Y` în felul următor:

.. math::

   P\{x_1\leq x<x_2\}=\Phi(\frac{x_2-m}{\sigma})-\Phi(\frac{x_1-m}{\sigma}),

în particular,

.. math::

   P\{|X-m_X|<\varepsilon\}=2\Phi(\frac{\varepsilon}{\sigma})-1.

Momentele centrate ale variabilei cu repartiția :math:`N(m,\sigma)` verifică urmatoarea relație de recurență 

.. math::

   \mu_{n+2}=(n+1)\sigma^2\mu_n, 
   
pentru orice număr natural :math:`n\geq 1`. Prin urmare, întrucît :math:`\mu_0=0,\mu_1=1`, obținem că toate momentele centrate de ordin impar sînt nule, iar cele de ordin par pot fi calculate după formulă

.. math::
   
   \mu_{2n}=(2n-1)!!\sigma^{2n},
   
unde :math:`(2n-1)!!=1\cdot 3\cdot 5\cdot ... \cdot (2n-1)`, :math:`n\geq 1`. 

**Exemplul 7 (pg. 84).** Se efectuează măsurări ale diametrului tijei. Variabila aleatoare :math:`X` care ia drept valori erorile de măsurare are repartiția normală cu valoarea medie :math:`m_X=0` mm și abaterea medie pătratică :math:`\sigma_X=10` mm. Să se determine probabilitatea ca valoarea absolută a erorilor de măsurare nu va intrece 15 mm.

Rezolvare. Din datele problemei reiese că :math:`X` are repartiția :math:`N(0,10)`. Dar atunci 

:math:`P\{|X|<15\}=2\Phi(\frac{15}{10})-1=2\Phi(1,5)-1`.

Din tabelul P1 găsim că :math:`\Phi(1,5)\approx 0,9332`. Astfel 

:math:`P\{|X|<15\}\approx 0,8664`.

**14.361.** Variabila aleatoare :math:`X` are repartiția :math:`N(1,2)`. Exprimați :math:`F_X(x)` (funcția de repartiție a varaibilei :math:`X`) prin funcția :math:`\Phi(x)`.

**14.362.** Variabila aleatoare :math:`X` are repartiția :math:`N(m,\sigma)`. Folosind tabelul P1 să se determine probabilitatea :math:`p_k=P\{|X-m_X|<k\sigma\}`, unde :math:`k=\overline{1,3}`.

**14.363.** Variabila aleatoare :math:`X` are repartiția :math:`N(10,5)`. Să se determine intervalul simetric în raport cu :math:`m_X` in care valorile variabilei nimers cu probabilitatea :math:`p`. Dacă se știe că: 

a) :math:`p=0,9974`; 

b) :math:`p=0,9544`;

c) :math:`p=0,5`. 

**14.364.** O uzină chimică produce acid sulfuric a cărui densitate minimală este de 1,8 g/cm3. În rezultatul unor serii de experimente s-a determinat că practic 99,9% din reactivele produse au densitatea în intervalul (1,82; 1,86). Să se dermine probabilitatea că acidul satisface cerințele standard dacă pentru acesta este suficient ca densitatea acidului să devieze de la valoarea minimală cu nu mai mult de 0,01 g/cm3.

**14.365.** În cazul unei variabile cu repartiția normală 15% dintre valorile variabilei sînt mai mici decît 12 și 40% dintre valori sînt mai mari decît 16,2. Să se dermine valoarea medie și abaterea medie pătratică a variabilei.

**14.366.** O piesă produsă de un automat se consideră standard dacă devierea :math:`X` a mărimii de la valoarea minimală nu întrece 10 mm. Exactitatea producerii are abaterea medie pătartică :math:`\sigma`. Știind că :math:`\sigma=5` și :math:`X` are repartiția normală  să se dermine cîte procente dintre piesele fabricate sînt satndard.

**14.367.** În contextul problemei 14.366, determinați valoarea :math:`\sigma` astfel încît procentul de piese standard să fie 98.

**14.368. Bumboanele de ciocolată se amplasează în cutii în mod automat. Greutatea medie a unei cutii este 1,06 kg. Se știe că 5% din cutii au greutatea mai mică decît 1 kg. Să se dermine procentul cutiilor greutatea cărora este > 940 g.

**14.369.** O piesă se produce la mașină. Mărimea acesteia :math:`X` reprezintă o variabilă aleatoare cu repartiția normală cu valoarea medie  20 cm și dispersia 0,2 cm2. Care este exactitatea aproximativă a piesei putem garanta cu probabilitatea 0,95?

**14.370.** Se produs bile pentru rulmenți. O bilă este considerată standard dacă: bila trece printr-un orificiu cu diametrul d2 și nu trece printr-un alt orificiu cu diametrul d1<d2. Dacă cel putinuna din aceste condiții nu este satisfăcută bila se consideră nestandard. Diametrul bilei este o variabilă aleatoare X cu repartiția :math:`N(\frac{d_1+d_2}{2},\alpha\cdot(d_2-d_1))`, unde :math:`\alpha\in(0,\frac{1}{2})`  și :math:`\alpha` este un parametru care determină exactitatea producerii bilelor. Să se dermine probabilitatea că bila va fi nestandard.

**14.371.** În contextul problemei 14.370, să se detrmine :math:`\alpha` pentru ca nestandardul să constituie nu mai mult de 2% din toată producția.

**14.372.** Variabila aleatoare :math:`X` are repartiția :math:`N(1,\sigma)`. Se știe că :math:`P\{X<2\}=0,99`. Să se determine :math:`M(X^2)` și :math:`P\{X^2>2\}`.

**14.373.** Variabila aleatoare :math:`X` are repartiția :math:`N(m,\sigma)`. Să se dermine :math:`p_1=P\{X\geq x_{n2}\}` și :math:`p_2=P\{x_{n1}\leq X\leq x_{n2}\}`, unde :math:`x_{n1}` și :math:`x_{n2}` sînt punctele de inflexiune ale curbei densității de probabilitate.

**14.374\*\*.** Fie (a,b) un interval ce nu conține m.  În contextul problemei 14.373, să se dermine :math:`\sigma` pentru care probabilitatea :math:`Q(\sigma)=P\{a\leq X<b\}` va fi maximală?

**14.375.** În contextul problemei 14.373, să se dermine momentul centrat absolut de ordinul întîi :math:`M(|X-m_X|)`.

**14.376.** Variabila aleatoare :math:`X` are repartiția :math:`N(-1,1)`. Să se determine :math:`a_X` (coeficientul de asimetrie) și :math:`e_X` (coeficientul de boltire).

**14.377\*.** În contextul problemei 14.376, să se determine :math:`M(X^4)` și :math:`M(X^6)`.

`Răspunsuri <raspunsuri.html>`_

`Rezolvări <rezolvari.html>`_
