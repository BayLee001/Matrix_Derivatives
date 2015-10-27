���������󵼱ʼ�
=============

���ű�ʾ
------
* ��������ͨСд��ĸ��ϣ����ĸ��ʾ����$t,\alpha$�ȣ�
* ����ĸ��ʾ������Ĭ��Ϊ���������ô���Сд��ĸ�����ϣ����ĸ��ʾ����$\bf{x}$�ȣ���������д����������ת�ã���$\bf{x}^T$�ȡ���Ԫ�ؼ���$x_i$����������������$x_j$����������������
* �����ô�д��ĸ��ʾ����$\bf{A}$�ȣ���Ԫ�ؼ���$a_{ij}$��
* ������˵���ĳ��⡣

�����󵼽����Լ��
------
�����󵼱����кܶ����飬���磺

* �����󵼽���Ƿ���Ҫת�ã�
    * ��ͬ�̲ĶԴ˴���Ľ����һ��������**�Բ�ת��Ϊ׼**�����󵼽����ԭ����/����ͬ�͡�

* ����������������Ծ��󡢾���Ծ����󵼵Ľ����ʲô��
    * �������ǳ����ң����������������ִ�������һ�ǽ��������ƽ�̣������ܻ������˷����򲻳��������⡣����Magnus���ŵķ������������ӳ�һ��������Ȼ�����������󵼵ķ��������Ҹ��˾�����Щ���������ã����㷱��������Ҫ��Kronecker������ȵȣ����Һܶ�õ����ʣ�������ʽ���򣩵ȶ����ѱ���������
    * ��ʵ�ϣ�����ѵ�������ӳ��ǰ�ռ䵽ӳ���ռ���������ӣ���ôӦ�ñ���Ŀ���󵼵Ľ��Ӧ�������������Ľ�����������ΪFr��chet�����Ķ���ǳ���ѧ�����Բμ�[ά���ٿ�](https://en.wikipedia.org/wiki/Fr%C3%A9chet_derivative) �������������㱾���ַǳ��鷳����ͬ�����ھ޴�����顣
    * ���ǵ�����ѧϰ�У���ʵ�ϼ������������⼸�����ε��󵼣����ǲ����򵥴ֱ�����Ϊ**�����������µ���û�ж���**��


�������������Ľ�������Լ����

* ����/����ֵ������ʵ���ĵ�����
    * Ҫ�㣺�󵼽���뺯��ֵͬ�ͣ���ÿ��Ԫ�ؾ��Ǻ���ֵ����Ӧ�������Ա���$x$��
    * ������$\bf{F}:\mathbf{R}\rightarrow \mathbf{R^{m\times n}}$����$\partial{\bf{F}}/\partial{x}$Ҳ��һ��$m\times n$ά������$(\partial{\bf{F}}/\partial{x})_{ij} = \partial{f_{ij}}/\partial{x}$��
    * ������$\bf{f}:\mathbf{R}\rightarrow \mathbf{R^{m\times 1}}$����$\partial{\bf{f}}/\partial{x}$Ҳ��һ��mά����������$(\partial{\bf{f}}/\partial{x})_i = \partial{f_i}/\partial{x}$��
    * ������$\bf{f^T}:\mathbf{R}\rightarrow \mathbf{R^{1\times n}}$����$\partial{\bf{f^T}}/\partial{x}$Ҳ��һ��nά����������$(\partial{\bf{f^T}}/\partial{x})_j = \partial{f_j}/\partial{x}$��
* ʵֵ�����Ծ���/�����ĵ�����
    * Ҫ�㣺�󵼽�����Ա���ͬ�ͣ���ÿ��Ԫ�ؾ���$f$���Ա�������Ӧ������
    * ������$f:\mathbf{R^{m\times n}}\rightarrow \mathbf{R}$����$\partial{f}/\partial{\bf{X}}$Ҳ��һ��$m\times n$ά������$(\partial{f}/\partial{\bf{X}})_{ij} = \partial{f}/\partial{x_{ij}}$��
    * ������$f:\mathbf{R^{m\times1}}\rightarrow\mathbf{R}$����$\partial{f}/\partial{\bf{x}}$Ҳ��һ��$m$ά����������$(\partial{f}/\partial{\bf{x}})_i = \partial{f}/\partial{x_i}$��
    * ������$f:\mathbf{R^{1\times n}}\rightarrow\mathbf{R}$����$\partial{f}/\partial{\bf{x^T}}$Ҳ��һ��$n$ά����������$(\partial{f}/\partial{\bf{x^T}})_j = \partial{f}/\partial{x_j}$��
* ����ֵ�����������ĵ�����
    * ������$\bf{f}:\mathbf{R^{1\times n}}\rightarrow\mathbf{R^{m\times 1}}$����$\partial{\bf{f}}/\partial{\bf{x^T}}$��һ��$m\times n$ά������$(\partial{\bf{f}}/\partial{\bf{x^T}})_{ij} = \partial{f_i}/\partial{x_j}$��
    * ������$\bf{f}:\mathbf{R^{m\times 1}}\rightarrow\mathbf{R^{1\times n}}$����$\partial{\bf{f^T}}/\partial{\bf{x}}$��һ��$n\times m$ά���󣬶���Ϊ$\partial{\bf{f^T}}/\partial{\bf{x}} = (\partial{\bf{f}}/\partial{\bf{x^T}})^\bf{T}$��Ҳ����$(\partial{\bf{f^T}}/\partial{\bf{x}})_{ij} = \partial{f_j}/\partial{x_i}$��
* �ݶȡ�Hessian�������������$\nabla$��
    * ��ʱҲ������/�����󵼵Ľ�����������ӱ�ʾ������$\nabla_{x} f = \partial{f}/\partial{x}$����ʽ��$x$��$f$��������ά�ȵ���������󣩡����󵼵ı����Ƚ���ȷʱ��$\nabla$���±����ʡ�ԣ����Ϊ$\nabla{f}$��
    * ����һ��ʵ����$f:\mathbf{R^{m\times1}}\rightarrow\mathbf{R}$�����ݶȹ涨Ϊ$m$ά������$\nabla f =  \textbf{grad} f = \dfrac{\partial{f}}{\partial{\bf{x}}}$��Hessian����涨Ϊ$\nabla \nabla f = \dfrac{\partial(\nabla f)}{\partial{\bf{x^T}}} = \dfrac{\partial^2{f}}{\partial{\bf{x}}\partial{\bf{x^T}}}$����һ��$m\times m$�ľ��󡣴�ʱ����$\nabla$�������ɷֱ��$\bf{x}$��$\bf{x^T}$�󵼣��ɽ���˳�򣩡�
    * ����һ��ʵ����$f:\mathbf{R^{m\times n}}\rightarrow\mathbf{R}$�����ݶȹ涨Ϊ$m\times n$ά����$\nabla f =  \dfrac{\partial{f}}{\partial{\bf{X}}}$��Hessian���������塣

������Լ�������
------
* ����Ķ���ʼ������ת�ù�ϵ��
    * ����$\nabla_{x}f = (\nabla_{x^\bf{T}}f^\bf{T})^\bf{T}$������$x,f$��������ά�ȵ����������
    * ����$\nabla_{\bf{X}} f = (\nabla_{\bf{X^T}} f)^\bf{T}$�ȣ�$f$Ϊʵ��ʱ$f^T=f$��
* ���������������������Ա��������Ĺ�ϵ��
    * ����/����ֵ������ʵ���ĵ�����
        - $\delta \mathbf{F} \approx \delta x(\nabla\bf{F}) $���ұ���ʵ���;�������ˣ�
        - $\delta \mathbf{f} \approx \delta x(\nabla\bf{f}) $���ұ���ʵ�������������ˣ�
    * ʵֵ�����Ծ���/�����ĵ�����
        - $\delta f \approx \sum_{i,j}(\nabla f)_{ij} (\delta\mathbf{X})_{ij} = tr((\nabla f)^T \delta\bf{X}) $
            - ��ʽ�õ��ļ��ɷǳ���Ҫ������ͬ�;����ӦԪ����������ʱ��������ڶ����Ⱥ�ת��Ϊ�����Ӷ������㡣
            - ����һ���ǶȽ������Ǿ���������һ�ֶ��塣�������ں���$f(X):\mathbf{R^{m\times n}}\rightarrow \mathbf{R}$�������ھ���$\bf{A}$��ʹ��$||\delta\mathbf{X}||\rightarrow 0$ʱ��$||\cdot||Ϊ���ⷶ��$��������$\delta f = tr(\mathbf{A^T\delta X}) + o(||\delta\mathbf{X}||)$������$\nabla f = \mathbf{A}$��
            - **����˻��ļ���һ���������ӣ����ھ���ռ��еĵ�λ�൱���ڻ���$n$άŷʽ�ռ��еĵ�λ��**
        - $\delta f \approx (\nabla f)^T \delta\bf{x} $���ұ��������ڻ���
            - ��ʽ�ɿ���ǰһ��ʽ�ӵ��˻����Ρ�
    * ����ֵ�����������ĵ�����
        * $\delta \mathbf{f} \approx (\nabla_{\mathbf{x^T}} \mathbf{f}) \delta\bf{x} $
            * ��ʽ��Ϊ�ػ��ֻ�Ԫʱ��������任��Jacobian����
        * $\delta \mathbf{f} \approx (\nabla_{\mathbf{x}} \mathbf{f^T})^\mathbf{T} \delta\bf{x} $
            * ��ǰʽʵ����ͬ��

���ù�ʽ
-------
* ʵֵ/����ֵ�����������󵼣�δ������˵����Ϊ��$\bf{x}$���ݶȣ���
    * ���������������󵼣�
        * $\nabla\;\bf{x}^T = \bf{I}, \nabla\bf{(Ax)}^T = \bf{A}^T$
    * ���������������󵼣�
        * $\nabla_{\bf{x^T}}\;\bf{x} = \bf{I}, \nabla_{\bf{x}^T}\bf{(Ax)} = \bf{A}$
    * �����ڻ����󵼷�����Ҫ����
        * $\nabla(\mathbf{u^Tv}) = \nabla(\mathbf{u^T})\cdot\mathbf{v}+\nabla(\mathbf{v^T})\cdot\mathbf{u}$
        * �ر�أ��У�
            * $\nabla ||\mathbf{x}||_2^2 = \nabla(\mathbf{x^Tx}) = 2\mathbf{x}, \nabla (\mathbf{w^Tx}) = \mathbf{w}$
            * $\nabla (\mathbf{x^TAx}) = \mathbf{(A+A^T)x}$
    * ���������󵼹�ʽ������Ҫ����
        * $\nabla_{\mathbf{x^T}} (\alpha(\mathbf{x})\mathbf{f(x)}) = \bf{f(x)\nabla_{\mathbf{x^T}}\alpha(\mathbf{x}) + \alpha(\mathbf{x})}\nabla_{\mathbf{x^T}}\mathbf{f(x)}$
* �����󵼣�δ������˵����Ϊ��$\bf{X}$���ݶȣ���ͬ����
    * ���Ļ������ʣ�
        * �������ʣ�$tr(\sum_i c_i\mathbf{A}_i) = \sum_ic_i tr(\mathbf{A}_i)$
        * ת�ò����ԣ�$tr(\mathbf{A}) = tr(\mathbf{A^T})$
        * �ֻ������ԣ�$tr(\mathbf{ABCD}) = tr(\mathbf{DABC}) = \cdots$
    * ������ʽ��
        * $\nabla tr(\mathbf{A^TX}) = \mathbf{A}$��������Ԫ������֤����ʵ�Ͼ��Ǿ������ĵڶ��ֶ��壩
    * �������ĺ��Ĺ�ʽ��
        * $\nabla tr(\mathbf{XAX^TB}) = \mathbf{B^TXA^T + BXA}$
        * �����ʽ�ǳ���Ҫ�����Ƶ���С���˽�������϶�����������ʽ����������Ϲ��ģ��Ҳ�֪������ʲô���֡�
* ���������󵼹�ʽ���󲿷ֿ��ɼ��󵼿����Ƴ�������ǿ�ǡ�$\mathbf{u, v, A, B}$Ϊ��$\mathbf{X}$�޹صĳ�������
    * $\nabla\mathbf{u^TXv} = \mathbf{uv^T}$
    * $\nabla\mathbf{u^TX^TXu} = 2\mathbf{Xuu^T}$
    * $\nabla\mathbf{(Xu-v)^T(Xu-v)} = 2\mathbf{(Xu-v)u^T}$
    * $\nabla\mathbf{||XA^T-B||}_{\mathbf{Fro}}^2 = 2\mathbf{(XA^T-B)A}$
        * �ر�أ�$\nabla ||\mathbf{X}||^2_{\mathbf{Fro}} = \nabla \mathbf{(X^TX)} = 2\mathbf{X}$��������Ԫ������֤��
    * $\nabla_\mathbf{X} |\mathbf{X}| = \mathbf{|X|(X^{-1})^T}$��������Ԫ���� + �������������Ƶ���
    * ��ʽ����
        * ��$\mathbf{U} = f(\mathbf{X})$����
            * $\dfrac{\partial{g(\mathbf{U})}}{\partial{x_{ij}}} = \sum_{k,l} \dfrac{g(\mathbf{U})}{\partial{u_{kl}}} \dfrac{\partial{u_{kl}}}{\partial{x_{ij}}}$�����дΪ$\dfrac{\partial{g(\mathbf{U})}}{\partial{x_{ij}}} = tr((\dfrac{\partial{g(\mathbf{U})}}{\partial{\mathbf{U}}})^\mathbf{T} \dfrac{\partial{\mathbf{U}}}{\partial{x_{ij}}})$
    * ���Ա任�ĵ���������ֱ���õ�������֤�����Լ򻯺ܶ๫ʽ���Ƶ����̣���
        * ����$f(\mathbf{Y}):\mathbf{R^{m\times p}}\rightarrow\mathbf{R}$������ӳ�� $\mathbf{X}\mapsto\mathbf{Y=AX+B}:\mathbf{R^{n\times p}}\rightarrow\mathbf{R^{m\times p}}$����
            * $\nabla_{\mathbf{X}} \;f(\mathbf{AX+B}) = \mathbf{A^T} \nabla_\mathbf{Y} f$
            * ���������Ա任����ʽ���˻����Σ�����$\nabla_{\mathbf{x}} \;f(\mathbf{Ax+b}) = \mathbf{A^T} \nabla_\mathbf{y} f$
* ����/������ʵ���󵼣�
    * $(|\mathbf{F}|)'_x = |\mathbf{F}| tr(\mathbf{F^{-1}}\mathbf{F'}_x)$
    * $(\ln |\mathbf{F}|)'_x = tr(\mathbf{X^{-1}}\mathbf{X}'_x)$


����Ӧע�⵽�����������ɣ�

* ����������ʱ�����������������������Ա�����ÿһ�γ������������֮�͡���ˣ��ɵ��������Ա���ÿһ�γ�������ĵ����仯���ٰ���Щ�����������
    * ���磺$$\delta\mathbf{(C_1F_1C_2F_2C_3)} =\delta\mathbf{(C_1F_1C_2F_{2c}C_3)} + \delta\mathbf{(C_1F_{1c}C_2F_2C_3)} \\
        \text{+ higher order infinitesimal}$$������$\mathbf{F_{ic}}$��ʾ��$\mathbf{F_i}$��Ϊ�����������Ա����ĺ�����
    * ���Ծݴ��Ƶ����󼣷����ĺ��Ĺ�ʽ��
        * $\nabla tr(\mathbf{XAX^TB}) = \nabla tr(\mathbf{X_cAX^TB}) + \nabla tr(\mathbf{XAX_c^TB}) =  \mathbf{BXA+B^TXA^T}$
* ʵ������һ�Ѿ�������������ʱ���������ƶ�λ�á���ʵ����������ʱ���������������˷���$1\times 1$�����$1\times m$������ˣ��Ǽ��ݵġ�

Ҫ��
--------
* ������ͬ�±���;����뵽����˷��Ķ��壬��$c_{ij} = \sum_ja_{ij}b_{jk}$���ر�أ�һά�±�������뵽�����ڻ�$\sum_iu_iv_i = \bf{u}^Tv$����ά�±�������뵽��$\sum_{ij}a_{ij}b_{ij} = tr(\mathbf{AB^T})$��$\bf{A,B}$ӦΪͬ�;��󣩡�
* �����һ�����ʽ�У��������Ϊ����ĳ˻�����Ҫ����չ������Ҫ���������˼·�����ɷֿ�������ˣ�
* ������ģ������ʵ����ƽ���ͣ�ת��Ϊ�ڻ����㣺$\sum_i x_i^2 = \bf{x^Tx}$�������F����ת��Ϊ�����㣺$||\mathbf{A}||^2_{\mathbf{Fro}} = tr(\mathbf{AA^T})$��
* ����������ʱ�����þ��󼣵��󵼹�ʽת����ѭ���ƶ����ʵ��Ҳ�ɿ���$1\times 1$����ļ���


����
------
* ��С���˽��Ƶ���
    * ����һ��չ�����ţ���ʹ�ü������ù�ʽ���򼴿ɣ�
        * $$\begin{align*}
    \nabla_\mathbf{x} ||\mathbf{Ax-b}||^2_2 & = & \nabla_\mathbf{x}\mathbf{(Ax-b)^T(Ax-b)} \\
      & = & \nabla_\mathbf{x}(\mathbf{x^TA^TAx - b^TAx - x^TA^Tb + b^Tb}) \\
      & = & \nabla_\mathbf{x}(\mathbf{x^TA^TAx}) - 2\nabla_\mathbf{x}(\mathbf{b^TAx}) + \nabla_\mathbf{x}(\mathbf{b^Tb}) \\
      & = & 2\mathbf{A^TAx} - 2\mathbf{A^Tb} + \mathbf{0} \\
      & = & 2\mathbf{A^T(Ax-b)}
     \end{align*}$$
    * ��������ʹ�����Ա任���󵼹�ʽ��
        * $$\begin{align*}
    \nabla_\mathbf{x} ||\mathbf{Ax-b}||^2_2 & = & \mathbf{A^T}\nabla_\mathbf{Ax-b}\mathbf{||Ax-b||^2_2} \\
      & = & \mathbf{A^T}(2(\mathbf{Ax-b})) \\
      & = & 2\mathbf{A^T(Ax-b)}
     \end{align*}$$
* F�������󵼹�ʽ�Ƶ���
    * ����һ����ת��Ϊ������������ͨ��ǡ�����ֻ����ü������ĺ��Ĺ�ʽ����
        * $$\begin{align*}
    \nabla\mathbf{||XA^T-B||}_{\mathbf{Fro}}^2 & = & \nabla tr(\mathbf{(XA^T-B)^T(XA^T-B)}) \\
      & = & \nabla tr(\mathbf{AX^TXA^T - B^TXA^T - AX^TB + B^TB}) \\
      & = & \nabla tr(\mathbf{AX^TXA^T}) - 2tr(\mathbf{AX^TB}) + tr(\mathbf{B^TB})\\
      & = & 2tr(\mathbf{XA^TAX^TI}) - 2tr(\mathbf{X^TBA}) + \mathbf{0} \\
      & = & 2\mathbf{(I^TX(A^TA)^T + IX(A^TA))}  - 2\mathbf{BA} \\
      & = & 2\mathbf{XA^TA} - 2\mathbf{BA} \\
      & = & 2\mathbf{(XA^T-B)A}
     \end{align*}$$
    * �������������Ա任���󵼹�ʽ֤����ע�����ת�ò��ı���F����������ʵֵ������$\mathbf{X}$��$\mathbf{X^T}$�ĵ�����Ϊת�ã�
        * $$\begin{align*}
    \nabla\mathbf{||XA^T-B||}_{\mathbf{Fro}}^2 & = & \nabla\mathbf{||AX^T-B^T||}_{\mathbf{Fro}}^2 \\
      & = & (\nabla_{\mathbf{X^T}} \mathbf{||AX^T-B^T||}_{\mathbf{Fro}}^2)^\mathbf{T} \\
      & = & (\mathbf{A^T}(2(\mathbf{AX^T-B^T})))^\mathbf{T}\\
      & = & 2\mathbf{(XA^T-B)A}
     \end{align*}$$
    * �����������ݶ�����Ԫ�ص��㣬Ȼ��ϲ����������ٺϲ��ɾ��󡣣�̫ԭʼ����Ч�����Ƽ���
* PRML (3.33)�󵼣�
    * ��Ŀ��
        * ��$f(\mathbf{W}) = \ln p(\mathbf{T|X, W}, \beta) = \text{const} -\dfrac{\beta}{2} \sum_n  ||\mathbf{t_n - W^T\phi(x_n)}||^2_2$����$\mathbf{W}$�ĵ�����
    * ����һ���þ����F�����Ƶ���
        * $$\begin{align*}
    \nabla f & = & \nabla \left(-\dfrac{\beta}{2} \sum_n  ||\mathbf{t_n - W^T\phi(x_n)}||^2_2 \right) \\
      & = & -\dfrac{\beta}{2} \nabla  ||\mathbf{T^T - W^T\Phi^T}||_{\mathbf{Fro}} \\
      & = & -\dfrac{\beta}{2} \nabla  ||\mathbf{T - \Phi W}||_{\mathbf{Fro}} \\
      & = & -\dfrac{\beta}{2} \nabla  ||\mathbf{\Phi W - T}||_{\mathbf{Fro}} \\
      & = & -\dfrac{\beta}{2} \mathbf{\Phi^T} (2(\mathbf{\Phi W - T})) \\
      & = & -\beta\mathbf{\Phi^T} (\mathbf{\Phi W - T})
     \end{align*}$$
        - �������������ݷֱ��ǣ�
            - �����ɸ�������ƴ��һ������������ǵĶ�����ƽ���;͵��ڴ�����F������
            - ����ת�ò��ı���F������
            - ��������(-1)���ı���F������
            - ���Ա任���󵼹�ʽ + F�������󵼹�ʽ��
            - ʵ���ں;���������ʱλ�ÿ��������ƶ���
        - �������$\mathbf{W}$�������Ȼ��Ϊ$\mathbf{W_{ML}} = \mathbf{\Phi^\dagger T} = \mathbf{(\Phi^T\Phi)^{-1}\Phi^T}$��
    * �������� ���������������ڻ����棬Ȼ������չ����������÷ֿ�������������ͺţ�
        * $$\begin{align*}
    \nabla f & = & \nabla \left(-\dfrac{\beta}{2} \sum_n  ||\mathbf{t_n - W^T\phi(x_n)}||^2_2 \right) \\
      & = & -\dfrac{\beta}{2}\nabla \left(\sum_n \mathbf{(t_n - W^T\phi(x_n))^T(t_n - W^T\phi(x_n))} \right) \\
      & = & -\dfrac{\beta}{2}\sum_n \{\nabla(\mathbf{t_n^Tt_n}) -2\nabla(\mathbf{\phi(x_n)^TWt_n}) \\
      & & + \nabla(\mathbf{\phi(x_n)^TWW^T\phi(x_n)})\} \\
      & = & -\dfrac{\beta}{2}\sum_n \{\mathbf{0} - 2\mathbf{\phi(x_n)t_n^T} + \nabla(\mathbf{WIW^T\phi(x_n)\phi(x_n)^T})\}\\
      & = & -\dfrac{\beta}{2}\sum_n \{- 2\mathbf{\phi(x_n)t_n^T} + \mathbf{(\phi(x_n)\phi(x_n)^T)^T W I^T + (\phi(x_n)\phi(x_n)^T) W I}\} \\
      & = & -\dfrac{\beta}{2}\sum_n \{- 2\mathbf{\phi(x_n)t_n^T} + 2\mathbf{\phi(x_n)\phi(x_n)^TWI}\} \\
      & = & -\beta\sum_n \{-\mathbf{\phi(x_n)t_n^T} + \mathbf{\phi(x_n)\phi(x_n)^TW}\} \\
      & = & -\beta\sum_n \mathbf{\phi(x_n)}\{\mathbf{-t_n^T + \phi(x_n)^TW}\} \\
      & = & -\beta\mathbf{\Phi^T} (\mathbf{\Phi W - T})
     \end{align*}$$
        * ע�����һ����˼�����̣�
            * ����$n$�����Ϊ�����ֿ����ĳ˻���
                * ��һ�������Ƿֿ�����������$1\times N$���飬�ҵ�n��������$\mathbf{\phi(x_n)}$����˵�һ��������$(\mathbf{\phi(x_1)}, \mathbf{\phi(x_2)}, \cdots, \mathbf{\phi(x_N)}) = \mathbf{\Phi^T}$
                * �ڶ��������Ƿֿ�����������$N\times 1$���飬�ҵ�n��������$\mathbf{-t_n^T + \phi(x_n)^TW}$����ˣ��ڶ��������ǣ�
                $$\begin{align*} \\
                    \left(
                    \begin{matrix}
                    \mathbf{-t_1^T + \phi(x_1)^TW} \\
                        \mathbf{-t_2^T + \phi(x_2)^TW} \\
                        \vdots \\
                        \mathbf{-t_N^T + \phi(x_N)^TW}
                    \end{matrix}
                    \right)
                    & = & \left(
                    \begin{matrix}
                    \mathbf{\phi(x_1)^TW} \\
                        \mathbf{\phi(x_2)^TW} \\
                        \vdots \\
                        \mathbf{\phi(x_N)^TW}
                    \end{matrix}
                    \right)
                    -\left(
                    \begin{matrix}
                    \mathbf{t_1^T} \\
                        \mathbf{t_2^T} \\
                        \vdots \\
                        \mathbf{t_N^T}
                    \end{matrix}
                    \right) \\
                    & = & \left(
                    \begin{matrix}
                    \mathbf{\phi(x_1)^T} \\
                        \mathbf{\phi(x_2)^T} \\
                        \vdots \\
                        \mathbf{\phi(x_N)^T}
                    \end{matrix}
                    \right)\mathbf{W}
                    -\left(
                    \begin{matrix}
                    \mathbf{t_1^T} \\
                        \mathbf{t_2^T} \\
                        \vdots \\
                        \mathbf{t_N^T}
                    \end{matrix}
                    \right) \\
                    & = & \mathbf{\Phi W - T}
                \end{align*}$$��ע��ڶ�����ʽ���Ƶ������У���һ���ܹ�������Ϊ�������������ֿ����ĳ˻��������ֿ����ֱ���$N\times 1$��$1\times 1$������ɡ�
        * ���ַ�����Ȼ�ȽϷ��������Ǹ�����һ���ԡ�
