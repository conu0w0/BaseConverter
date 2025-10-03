## 1) 正合方程
\[\frac{dy}{dx}=\frac{-2xy^3-4}{3x^2y^2+e^y}\]

化為  
\[(2xy^3+4)\,dx+(3x^2y^2+e^y)\,dy=0\]

檢查：  
\[\frac{\partial M}{\partial y}=6xy^2, \quad \frac{\partial N}{\partial x}=6xy^2 \;\;\Rightarrow\;\; 正合。\]

積分得  
\[F(x,y)=x^2y^3+4x+e^y=C\]

**通解：**  
\[\boxed{x^2y^3+4x+e^y=C}\]

---

## 2) 非正合（可分離變數）
\[\sin y\,dx+\cos y\,dy=0 \quad\Rightarrow\quad \frac{dy}{dx}=-\tan y\]

分離變數：  
\[\int \frac{\cos y}{\sin y}\,dy = -\int dx\]

\[\ln|\sin y| = -x+C\]

**通解：**  
\[\boxed{\sin y=C e^{-x}}\]

---

## 3) 兩項合併為一項
\[y'+\frac{y}{x}=-\frac{2}{x}\]

乘以 \(x\)：  
\[(xy)'=-2\]

積分：  
\[xy=-2x+C\]

 **通解：**  
\[\boxed{y=-2+\frac{C}{x}}\]

---

## 4) 白努利方程式
\[x y' + y = x^2 y^2\]

改寫：  
\[y' + \frac{1}{x}y = x y^2\]

令 \(z=y^{-1}\)，則：  
\[z' - \frac{1}{x}z = -x\]

積分因子：\(e^{\int -1/x dx}=x^{-1}\)  
\[\Big(\frac{z}{x}\Big)'=-1\]

\[\frac{z}{x}=-x+C \quad\Rightarrow\quad z=Cx-x^2\]

\[y=\frac{1}{z}=\frac{1}{Cx-x^2}\]

**通解：**  
\[\boxed{y=\frac{1}{x(C-x)}}\]
