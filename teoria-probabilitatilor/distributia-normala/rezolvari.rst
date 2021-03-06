Rezolvări
---------

**14.361.** Dacă :math:`Y=\frac{X-m}{\sigma}`, atunci :math:`Y` are distribuția :math:`N(0,1)`. Într-adevăr, :math:`M(Y)=M(\frac{X-m}{\sigma})=\frac{M(X)-m}{\sigma}=0` și :math:`D(Y)=D(\frac{X-m}{\sigma})=\frac{D(X)}{\sigma^2}=1`. Funcția de repartiție a variabilei aleatoare :math:`Y` se notează prin :math:`\Phi`. 

Vom încerca să exprimăm funcția de repariție :math:`F_X` a variabilei aleatoare :math:`X` prin :math:`\Phi` în felul următor:

.. math::

   F_X(x)=P\{X<x\}=P\{\sigma\cdot Y+m<x\}=P\{Y<\frac{x-m}{\sigma}\}=\Phi(\frac{x-m}{\sigma}).

**14.362.**
:math:`p_k=P\{|X-m_X|<k\sigma\}=2\Phi(k)-1.` Respectiv: 

#. :math:`p_1=2\Phi(1)-1\approx 2\cdot 0,8413-1\approx 0,6826`.
#. :math:`p_2=2\Phi(1)-1\approx 2\cdot 0,9772-1\approx 0,9544`.
#. :math:`p_3=2\Phi(1)-1\approx 2\cdot 0,9987-1\approx 0,9974`.

**14.363.**

:math:`P\{|X-10|<\varepsilon\}=2\Phi(\frac{\varepsilon}{5})-1\Rightarrow \Phi(\frac{\varepsilon}{5})=\frac{P+1}{2}`.

a) :math:`\Phi(\frac{\varepsilon}{5})=\frac{0,9974+1}{2}=0,9987\Rightarrow \frac{\varepsilon}{5}\approx 3\Rightarrow \varepsilon\approx 15\Rightarrow X\in (-5,25)`.

b) :math:`\Phi(\frac{\varepsilon}{5})=\frac{0,9544+1}{2}=0,9772\Rightarrow \frac{\varepsilon}{5}\approx 2\Rightarrow \varepsilon\approx 10 \Rightarrow X\in (0,20)`.

c) :math:`\Phi(\frac{\varepsilon}{5})=\frac{0,5+1}{2}=0,75\Rightarrow \frac{\varepsilon}{5}\approx 0,67\Rightarrow \varepsilon\approx 3,35 \Rightarrow X\in (6,65;13,35)`.

**14.364.** 
:math:`P\{|X-1,84|<0,02\}=2\Phi(\frac{0,02}{\sigma})-1=0,999\Rightarrow \Phi(\frac{0,02}{\sigma})=\frac{0,999+1}{2}=0,9995\Rightarrow \frac{0,02}{\sigma}\approx 3,3\Rightarrow \sigma\approx 0,006`. 

Rezultă că :math:`P\{|X-1,84|<0,01\}=2\Phi(\frac{0,01}{0,006})-1\approx 2\Phi(1,67)-1\approx 2\cdot 0,9525 -1\approx 0,905`.

**14.365.**
:math:`P\{X<12\}=0,15\Rightarrow \Phi(\frac{12-m}{\sigma})=0,15\Rightarrow \Phi(-\frac{12-m}{\sigma})=1-\Phi(\frac{12-m}{\sigma})=1-0,15\Rightarrow \Phi(-\frac{12-m}{\sigma})=0,85\Rightarrow -\frac{12-m}{\sigma}\approx 1,04\Rightarrow m-12\approx 1,04\sigma`.

:math:`P\{X>16,2\}=0,4\Rightarrow P\{X<16,2\}=1-0,4\Rightarrow \Phi(\frac{16,2-m}{\sigma})=0,6\Rightarrow \frac{16,2-m}{\sigma}\approx 0,25\Rightarrow 16,2-m\approx 0,25\sigma`.


**14.373.**
:math:`x_{n1}=m-\sigma`, :math:`x_{n2}=m+\sigma`. 
:math:`P\{X\geq x_{n2}\}=1-P\{X< x_{n2}\}=1-\Phi(\frac{x_{n2}-m}{\sigma})=1-\Phi(\frac{m+\sigma-m}{\sigma})=1-\Phi(1)=1-0,8413=0,1587`.
:math:`P\{x_{n1}\leq X\leq x_{n2}\}=\Phi(\frac{m+\sigma-m}{\sigma})-\Phi(\frac{m-\sigma-m}{\sigma})=\Phi(1)-\Phi(-1)=\Phi(1)-(1-\Phi(1))=2\Phi(1)-1=2\cdot 0,8413-1=0,6826`.

**14.374\*\*.**
:math:`Q(\sigma)=\Phi(\frac{b-m}{\sigma})-\Phi(\frac{a-m}{\sigma})`; :math:`Q'(\sigma)=-\frac{1}{\sigma^2}((b-m)\Phi'(\frac{b-m}{\sigma})-(a-m)\Phi'(\frac{a-m}{\sigma}))`. Respectiv :math:`Q'(\sigma)=0\Leftrightarrow (b-m) e^{-\frac{(b-m)^2}{2\sigma^2}}-(a-m)e^{-\frac{(a-m)^2}{2\sigma^2}}=0` 

**14.375.**
:math:`M(|X-m_X|)=\int_{-\infty}^{\infty}|x-m|f(x)dx=\int_{-\infty}^m(x-m)f(x)dx-\int_m^{\infty}(x-m)|f(x)dx`

**14.376.** 
:math:`a_X=\frac{\mu_3}{\sigma_X^3}=\frac{0}{1^3}=0`.

:math:`e_X=\frac{\mu_4}{\sigma_X^4}-3`, :math:`\mu_4=\mu_2+2=(2+1)\sigma^2\cdot\mu_2=3\cdot 1^2\cdot 1^2=3`, deci :math:`e_X=\frac{3}{1^4}-3=0`.
