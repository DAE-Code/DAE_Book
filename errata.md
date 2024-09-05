## 初版2刷(2021/05/10発行)の誤記 --> 初版3刷(2023/05/10発行)で修正されております

|頁|場所|誤|正|
|---|---|---|---|
|49|アルゴリズム2.5|$\xi{\color{red}<}\mathrm{rand}[0,1]$なら･･･|$\xi{\color{red}>}\mathrm{rand}[0,1]$なら･･･|
|49|下から3行目|遷移確率 $\xi$ が0から1の一様乱数 $\mathrm{rand}[0,1]$よりも小さい場合に･･･|遷移確率 $\xi$ が0から1の一様乱数 $\mathrm{rand}[0,1]$よりも大きい場合に･･･|
|64|式(3.11)|$\left. u \frac{\partial u}{\partial x} \right \|_ {i+\frac{1}{2},j} \approx u_{i+\frac{1}{2},j}\frac{-u_{i&plus;\frac{5}{2},j}&plus;8(u_{i&plus;\frac{3}{2},j}-u_{i-\frac{1}{2},j})&plus;u_{i-\frac{3}{2},j}}{\Delta x}$ $+ \frac{\left\|u_{i+\frac{1}{2},j} \right\|{\color{red}\Delta x}}{{\color{red}12}} \frac{u_{i+\frac{5}{2},j} -4u_{i+\frac{3}{2},j} +6u_{i+\frac{1}{2},j} -4u_{i-\frac{1}{2},j} +u_{i-\frac{3}{2},j}}{{\color{red}(\Delta x)^2}}$ |$\left. u \frac{\partial u}{\partial x} \right \|^t_ {i+\frac{1}{2},j} \approx u_{i+\frac{1}{2},j}^t\frac{-u_{i&plus;\frac{5}{2},j}^t&plus;8(u_{i&plus;\frac{3}{2},j}^t-u_{i-\frac{1}{2},j}^t)&plus;u_{i-\frac{3}{2},j}^t}{{\color{red}12}\Delta x}$ $+ \frac{\left\|u_{i+\frac{1}{2},j}^t \right\|{\color{red}(\Delta x)^3}}{{\color{red}4}} \frac{u_{i+\frac{5}{2},j}^t-4u_{i+\frac{3}{2},j}^t+6u_{i+\frac{1}{2},j}^t-4u_{i-\frac{1}{2},j}^t+u_{i-\frac{3}{2},j}^t}{{\color{red}(\Delta x)^4}}$ |
|64|式(3.12)|$\cdots-u_{{\color{red}\frac{1}{2}},j}^t\frac{-u_{i&plus;\frac{5}{2},j}^t&plus;8(u_{i&plus;\frac{3}{2},j}^t-u_{i-\frac{1}{2},j}^t)&plus;u_{i-\frac{3}{2},j}^t}{\Delta x}$ $-\frac{\left\|u_{i+\frac{1}{2},j}^t \right\|\Delta x}{{\color{red}12}} \frac{u_{i+\frac{5}{2},j}^t-4u_{i+\frac{3}{2},j}^t+6u_{i+\frac{1}{2},j}^t-4u_{i-{\color{red}\frac{3}{2}},j}^t+u_{i-{\color{red}\frac{5}{2}},j}^t}{(\Delta x)^2}$ $-v_{i&plus;\frac{1}{2},j}^t\frac{-u_{i&plus;\frac{1}{2},j&plus;2}^t&plus;8(u_{i&plus;\frac{1}{2},j&plus;1}^t-u_{i&plus;\frac{1}{2},j-1}^t)&plus;u_{i&plus;\frac{1}{2},j-2}^t}{\Delta y}$ $-\frac{\left\|v_{i+\frac{1}{2},j}^t \right\|\Delta y}{{\color{red}12}} \frac{u_{i+\frac{1}{2},j+2}^t-4u_{i+\frac{1}{2},j+1}^t+6u_{i+\frac{1}{2},j}^t-4u_{i+\frac{1}{2},j-1}^t+u_{i+\frac{2}{2},j-2}^t}{(\Delta y)^2}$\cdots |$\cdots-u_{{\color{red}i+\frac{1}{2}},j}^t\frac{-u_{i&plus;\frac{5}{2},j}^t&plus;8(u_{i&plus;\frac{3}{2},j}^t-u_{i-\frac{1}{2},j}^t)&plus;u_{i-\frac{3}{2},j}^t}{{\color{red}12}\Delta x}$ $-\frac{\left\|u_{i+\frac{1}{2},j}^t \right\|}{{\color{red}4}} \frac{u_{i+\frac{5}{2},j}^t-4u_{i+\frac{3}{2},j}^t+6u_{i+\frac{1}{2},j}^t-4u_{i-{\color{red}\frac{1}{2}},j}^t+u_{i-{\color{red}\frac{3}{2}},j}^t}{\Delta x}$ $-v_{i&plus;\frac{1}{2},j}^t\frac{-u_{i&plus;\frac{1}{2},j&plus;2}^t&plus;8(u_{i&plus;\frac{1}{2},j&plus;1}^t-u_{i&plus;\frac{1}{2},j-1}^t)&plus;u_{i&plus;\frac{1}{2},j-2}^t}{{\color{red}12}\Delta y}$ $-\frac{\left\|v_{i+\frac{1}{2},j}^t \right\|}{{\color{red}4}} \frac{u_{i+\frac{1}{2},j+2}^t-4u_{i+\frac{1}{2},j+1}^t+6u_{i+\frac{1}{2},j}^t-4u_{i+\frac{1}{2},j-1}^t+u_{i+\frac{1}{2},j-2}^t}{\Delta y}$\cdots |
|64|式(3.13)|$\cdots-u_{i,j+\frac{1}{2}}^t\frac{-v_{i+2,j+\frac{1}{2}}^t&plus;8(v_{i+1,j+\frac{1}{2}}^t-v_{i-1,j+\frac{1}{2}}^t)&plus;v_{i-2,j+\frac{1}{2}}^t}{\Delta x}$ $-\frac{\left\|u_{i,j+\frac{1}{2}}^t \right\|\Delta x}{{\color{red}12}} \frac{v_{i+2,j+\frac{1}{2}}^t-4v_{i+1,j+\frac{1}{2}}^t+6v_{i,j+\frac{1}{2}}^t-4v_{i-1,j+\frac{1}{2}}^t+v_{i-2,j+\frac{1}{2}}^t}{(\Delta x)^2}$ $-v_{i,j+\frac{1}{2}}^t\frac{-v_{i,j+\frac{5}{2}}^t&plus;8(v_{i,j+\frac{3}{2}}^t-v_{i,j-\frac{1}{2}}^t)&plus;v_{i,j-\frac{3}{2}}^t}{\Delta y}$ $-\frac{\left \|v_{i,j+\frac{1}{2}}^t \right\|\Delta y}{12} \frac{v_{i,j+\frac{5}{2}}^t-4v_{i,j+\frac{3}{2}}^t+6v_{i,j+\frac{1}{2}}^t-4v_{i,j-\frac{3}{2}}^t+v_{i,j-\frac{5}{2}}^t}{(\Delta y)^2}$\cdots |$\cdots-u_{i,j+\frac{1}{2}}^t\frac{-v_{i+2,j+\frac{1}{2}}^t&plus;8(v_{i+1,j+\frac{1}{2}}^t-v_{i-1,j+\frac{1}{2}}^t)&plus;v_{i-2,j+\frac{1}{2}}^t}{{\color{red}12}\Delta x}$ $-\frac{\left\|u_{i,j+\frac{1}{2}}^t \right\|}{{\color{red}4}} \frac{v_{i+2,j+\frac{1}{2}}^t-4v_{i+1,j+\frac{1}{2}}^t+6v_{i,j+\frac{1}{2}}^t-4v_{i-1,j+\frac{1}{2}}^t+v_{i-2,j+\frac{1}{2}}^t}{\Delta x}$ $-v_{i,j+\frac{1}{2}}^t\frac{-v_{i,j+\frac{5}{2}}^t&plus;8(v_{i,j+\frac{3}{2}}^t-v_{i,j-\frac{1}{2}}^t)&plus;v_{i,j-\frac{3}{2}}^t}{{\color{red}12}\Delta y}$ $-\frac{\left\|v_{i,j+\frac{1}{2}}^t \right\|}{{\color{red}4}} \frac{v_{i,j+\frac{5}{2}}^t-4v_{i,j+\frac{3}{2}}^t+6v_{i,j+\frac{1}{2}}^t-4v_{i,j-{\color{red}\frac{1}{2}}}^t+v_{i,j-{\color{red}\frac{3}{2}}}^t}{\Delta y}$\cdots |
|100|下から3行目|･･･各列の要素の行方向の和は1になって･･･|･･･各列の要素の和は1になって･･･|
|101|図4.11|各列の行方向要素の和は1|各列の要素の和は1|
|101|図4.12|$\rm{tr} \it{\hat V_{t\|t-1}}$|$\hat V_{t\|t-1}$の対角成分|
|171|下から1行目|2パラメータ間 $x_{{\color{red}i}}^{(k)}$, $x_{j}^{(l)}$の相関を|2パラメータ間 $x_{{\color{red}j}}^{(k)}$, $x_{j}^{(l)}$の相関を|

## 初版1刷(2021/01/15発行)の誤記 --> 初版2刷(2021/05/10発行)で修正されております

|頁|場所|誤|正|
|---|---|---|---|
|11|下から2行目|濃色部分|淡色部分|
|21|18行目|$p(\mathbf{y}\_{1:t})$|$p(\mathbf{y}\_{t}\|\mathbf{y}\_{1:t-1})$|
|23|図2.2|$\Delta t$|$\Delta \tau$|
|24|下から1行目|$\sigma_{t-1\|t-1}$|$\sigma_{t-1\|t-1}^2$|
|26|式(2.20)|$\sigma_{t\|t}=\cdots$|$\sigma_{t\|t}^2=\cdots$|
|29|式(2.28)|$J(x_1)=-\log[p(x_{1:T}\|y_{1:T})]=\cdots$|$J(x_1)=-\log[p(y_{1:T}\|x_{1:T})p(x_{1:T})]=\cdots$|
|33|11行目|$N(0,Q_t)$|$N(\mathbf{0},Q_t)$|
|39|3行目|･･･は状態ベクトルに･･･|･･･は推定すべき確率分布に･･･|
|43|3行目|$\cdots H\_t = \partial h\_t \/ \partial \mathbf{x}\_{t\|t-1}\cdots$|$\cdots H_t =\partial h_t \/ \partial \mathbf{x}\_{t}\cdots$|
|43|5行目|$\cdots F_t = \partial f_t \/ \partial \mathbf{x}\_{t\|t-1}\cdots$|$\cdots F_t = \partial f_t \/ \partial \mathbf{x}\_{t}\cdots$|
|43|式(2.57)|$\delta L=\delta\mathbf{x}\_0^{\mathrm{T}}\big[F_0 \boldsymbol{\lambda}\_1 + \cdots \big]+$  $$\cdots + \sum_{t=1}^{T} \big[f_{t-1}(\mathbf{x}\_{t-1})-\mathbf{x}\_t\big]^{\mathrm{T}}\boldsymbol{\lambda}\_t$$|$\delta L=\delta\mathbf{x}\_0^{\mathrm{T}}\big[F_0^{\mathrm{T}} \boldsymbol{\lambda}\_1 + \cdots \big]+$ $$\cdots + \sum_{t=1}^{T} \big[f_{t-1}(\mathbf{x}\_{t-1})-\mathbf{x}\_t\big]^{\mathrm{T}}\delta\boldsymbol{\lambda}\_t$$|
|43|式(2.58)|$\frac{\partial L}{\partial \mathbf{x}\_0} = F_0 \boldsymbol{\lambda}\_1 + \cdots$|$\frac{\partial L}{\partial \mathbf{x}\_0} = F_0^{\mathrm{T}} \boldsymbol{\lambda}\_1 + \cdots$|
|44|式(2.60)|$\nabla_{\mathbf{x}\_0} J =\nabla_{\mathbf{x}\_0} L = \frac{\partial L}{\partial \mathbf{x}\_0} = F_0 \boldsymbol{\lambda}\_1 + \cdots$|$\nabla_{\mathbf{x}\_0} J =\nabla_{\mathbf{x}\_0} L = \frac{\partial L}{\partial \mathbf{x}\_0} = F_0^{\mathrm{T}} \boldsymbol{\lambda}\_1 + \cdots$|
|44|14行目|2.3.3項でも･･･|2.2.3項でも･･･|
|49|アルゴリズム2.5|$N(0,Q_t)$|$N(\mathbf{0},Q_t)$|
|53|式(2.74)|$\cdots +K_t(\mathbf{y}\_t^n-H_t\mathbf{x}\_{t\|t-1}^n)$|$\cdots +\hat K_t(\mathbf{y}\_t^n-H_t\mathbf{x}\_{t\|t-1}^n)$|
|64|式(3.11)|$\cdots \approx u_{i+\frac{1}{2},j}\frac{-u_{i+\frac{5}{2},j}+8(u_{i+\frac{3}{2},j}+u_{i-\frac{1}{2},j})+u_{i-\frac{3}{2},j}}{\Delta x}+\cdots$|$\cdots \approx u_{i+\frac{1}{2},j}\frac{-u_{i+\frac{5}{2},j}+8(u_{i+\frac{3}{2},j}-u_{i-\frac{1}{2},j})+u_{i-\frac{3}{2},j}}{\Delta x}+\cdots$|
|64|式(3.12)|$\cdots-u_{\frac{1}{2},j}^t\frac{-u_{i+\frac{5}{2},j}^t+8(u_{i+\frac{3}{2},j}^t+u_{i-\frac{1}{2},j}^t)+u_{i-\frac{3}{2},j}^t}{\Delta x}+\cdots$ $\cdots -v_{i+\frac{1}{2},j}^t\frac{-u_{i+\frac{1}{2},j+2}^t+8(u_{i+\frac{1}{2},j+1}^t+u_{i+\frac{1}{2},j-1}^t)+u_{i+\frac{1}{2},j-2}^t}{\Delta y}+\cdots$|$\cdots-u_{i+\frac{1}{2},j}^t\frac{-u_{i+\frac{5}{2},j}^t+8(u_{i+\frac{3}{2},j}^t-u_{i-\frac{1}{2},j}^t)+u_{i-\frac{3}{2},j}^t}{\Delta x}+\cdots$ $\cdots -v_{i+\frac{1}{2},j}^t\frac{-u_{i+\frac{1}{2},j+2}^t+8(u_{i+\frac{1}{2},j+1}^t-u_{i+\frac{1}{2},j-1}^t)+u_{i+\frac{1}{2},j-2}^t}{\Delta y}+\cdots$|
|64|式(3.13)|$\cdots-u_{i,j+\frac{1}{2}}^t\frac{-v_{i+2,j+\frac{1}{2}}^t+8(v_{i+1,j+\frac{1}{2}}^t+v_{i-1,j+\frac{1}{2}}^t)+v_{i-2,j+\frac{1}{2}}^t}{\Delta x}+\cdots$  $\cdots -v_{i,j+\frac{1}{2}}^t\frac{-v_{i,j+\frac{5}{2}}^t+8(v_{i,j+\frac{3}{2}}^t+v_{i,j-\frac{1}{2}}^t)+v_{i,j-\frac{3}{2}}^t}{\Delta y}+\cdots$|$\cdots-u_{i,j+\frac{1}{2}}^t\frac{-v_{i+2,j+\frac{1}{2}}^t+8(v_{i+1,j+\frac{1}{2}}^t-v_{i-1,j+\frac{1}{2}}^t)+v_{i-2,j+\frac{1}{2}}^t}{\Delta x}+\cdots$  $\cdots -v_{i,j+\frac{1}{2}}^t\frac{-v_{i,j+\frac{5}{2}}^t+8(v_{i,j+\frac{3}{2}}^t-v_{i,j-\frac{1}{2}}^t)+v_{i,j-\frac{3}{2}}^t}{\Delta y}+\cdots$
|65|式(3.15)|$\delta p_{i,j}^s=\frac{\beta\bar D_{i,j}^s}{2\Delta\tau\Big[\frac{1}{(\Delta x)^2}+\frac{1}{(\Delta y)^2}\Big]}$|$\delta p_{i,j}^s=-\frac{\beta\bar D_{i,j}^s}{2\Delta\tau\Big[\frac{1}{(\Delta x)^2}+\frac{1}{(\Delta y)^2}\Big]}$|
|78|15行目|･･･の桑原邦夫先生･･･|･･･の桑原邦郎先生･･･|
|90|図4.4|$N(\mathbf{0},Q\_t)$|$N(\mathbf{x}\_t,Q_t)$|
|97|2行目|図4.9(a)に示すように･･･|図4.9(a1)に示すように･･･|
|98|式(4.15)|$\cdots\left\[\matrix{\cdots & \tilde u_{i&plus;\frac{1}{2},j}^{t\|t-1,1} & \cdots & \tilde v_{i,j&plus;\frac{1}{2}}^{t\|t-1,1} & \cdots \cr & & \vdots & &  \cr \cdots & \tilde u_{i&plus;\frac{1}{2},j}^{t\|t-1,1} & \cdots & \tilde v_{i,j&plus;\frac{1}{2}}^{t\|t-1,N} & \cdots }\right\]$ | $\cdots\left\[\matrix{ \quad\cdots & \tilde u_{i&plus;\frac{1}{2},j}^{t\|t-1,1} & \cdots & \tilde v_{i,j&plus;\frac{1}{2}}^{t\|t-1,1} & \cdots\quad \cr & & \vdots & &  \cr \quad\cdots & \tilde u_{i&plus;\frac{1}{2},j}^{t\|t-1,N} & \cdots & \tilde v_{i,j&plus;\frac{1}{2}}^{t\|t-1,N} & \cdots\quad }\right\]$|
|106|図4.16|$N(0,\sigma\_v^2)$|$N(\mathbf{x}\_t,Q\_t)$|
|113|1行目|･･･から初期および観測誤差分散が小さい方が･･･|･･･から初期アンサンブル分散が大きく，また，観測誤差分散が小さい場合に･･･|
|141|下から2行目|ここでは単位行列，･･･|ここで $I$ は単位行列，･･･|
|166|9行目|ディラックのデルタ関数|クロネッカーのデルタ|
|172|式(6.16)|$\cdots\approx-\dfrac{n}{2}\ln(\sigma^2)-\dfrac{n}{2}\ln\left\|\Phi\right\|$|$\cdots\approx-\dfrac{N}{2}\ln(\sigma^2)-\dfrac{1}{2}\ln\left\|\Phi\right\|$|
|172|8行目|$\sigma^2=((\mathbf{y}-\mathbf{1}\mu)^{\mathrm{T}}\Phi^{-1}(\mathbf{y}-\mathbf{1}\mu))/n$|$\sigma^2=((\mathbf{y}-\mathbf{1}\mu)^{\mathrm{T}}\Phi^{-1}(\mathbf{y}-\mathbf{1}\mu))/N$|
|183|6行目|･･･では観測システム実験･･･|･･･では観測システムシミュレーション実験･･･|
