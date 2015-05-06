Rezolvări
---------

**14.361.** Dacă :math:`Y=\frac{X-m}{\sigma}`, atunci :math:`Y` are distribuția :math:`N(0,1)`. Într-adevăr, :math:`M(Y)=M(\frac{X-m}{\sigma})=\frac{M(X)-m}{\sigma}=0` și :math:`D(Y)=D(\frac{X-m}{\sigma})=\frac{D(X)}{\sigma^2}=1`. Funcția de repartiție a variabilei aleatoare :math:`Y` se notează prin :math:`\Phi`. 

Vom încerca să exprimăm funcția de repariție :math:`F_X` a variabilei aleatoare :math:`X` prin :math:`\Phi` în felul următor:

.. math::

   F_X(x)=P\{X<x\}=P\{\sigma\cdot Y+m<x\}=P\{Y<\frac{x-m}{\sigma}\}=\Phi(\frac{x-m}{\sigma}).


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
