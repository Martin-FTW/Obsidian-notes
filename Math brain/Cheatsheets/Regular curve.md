# Regular curve
Let $\tilde{\gamma}:I\to \mathbb{R}^{3}$ be a regular curve and $\phi:I \to J$ be its arclength parametrization
Let $\gamma=\tilde{\gamma}\circ \phi ^{-1}:J\to \mathbb{R}^{3}$ be the curve pbal.
## For pbal
As function of $s\in J$, we have
- $\begin{cases}T=\gamma'\\N=\dfrac{T'}{\norm{T'}}=\dfrac{\gamma''}{\norm{\gamma''}}\\B=T\times N=\dfrac{\gamma'\times \gamma''}{\norm{\gamma''}}\end{cases}$ and $\begin{cases}\kappa=\norm{\gamma''}\\\uptau=\dfrac{\innerp{\gamma'\times \gamma''}{\gamma'''}{}}{\norm{\gamma''}^{2}}\end{cases}$
- $\begin{cases}T'=\kappa N\\N'=-\kappa T+\uptau B\\B'=-\uptau N\end{cases},\text{ i.e. }\begin{bmatrix}T'\\N'\\B'\end{bmatrix}=\begin{bmatrix}0&\kappa&0\\-\kappa&0&\uptau\\0&-\uptau&0\end{bmatrix}\begin{bmatrix}T\\N\\B\end{bmatrix}$
## For non-pbal
As functions of $t\in I$, we have
- $\begin{cases}\tilde{T}=\dfrac{\tilde{\gamma}'}{\norm{\tilde{\gamma}'}}\\\tilde{N}=\dfrac{\tilde{T}'}{\norm{\tilde{T}'}}=\dfrac{\gamma'\times(\gamma''\times \gamma')}{\norm{\gamma'}\norm{\tilde{\gamma}'\times\tilde{\gamma}''}}\\\tilde{B}=\tilde{T}\times \tilde{N}=\dfrac{\tilde{\gamma}'\times \tilde{\gamma}''}{\norm{\tilde{\gamma}'\times \tilde{\gamma}''}}\end{cases}$ and $\begin{cases}\tilde{\kappa}=\dfrac{\norm{\tilde{\gamma}'\times\tilde{\gamma}''}}{\norm{\tilde{\gamma}'}^{3}}\\\tilde{\uptau}=\dfrac{\innerp{\tilde{\gamma}'\times \tilde{\gamma}''}{\tilde{\gamma}'''}{}}{\norm{\tilde{\gamma}'\times \tilde{\gamma}''}^{2}}\end{cases}$
- $\begin{cases}\tilde{T}'=\norm{\tilde{\gamma}'}\tilde{\kappa} \tilde{N}\\\tilde{N}'=-\norm{\tilde{\gamma}'}\tilde{\kappa} \tilde{T}+\norm{\tilde{\gamma}'}\tilde{\uptau} \tilde{B}\\\tilde{B}'=-\norm{\tilde{\gamma}'}\tilde{\uptau} \tilde{N}\end{cases},\text{ i.e. }\begin{bmatrix}\tilde{T}'\\\tilde{N}'\\\tilde{B}'\end{bmatrix}=\norm{\tilde{\gamma}'}\begin{bmatrix}0&\tilde{\kappa}&0\\-\tilde{\kappa}&0&\tilde{\uptau}\\0&-\tilde{\uptau}&0\end{bmatrix}\begin{bmatrix}\tilde{T}\\\tilde{N}\\\tilde{B}\end{bmatrix}$
