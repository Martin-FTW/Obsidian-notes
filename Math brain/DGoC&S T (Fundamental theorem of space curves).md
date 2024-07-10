Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Theorem (Fundamental theorem of space curves)
	Every regular space curve is uniquely determined by its positive curvature and torsion up to orientation-preserving rigid motions.
Let $k,\uptau:I\to \mathbb{R}$ with $k(s)>0$ for all $s\in I$.
Then $\exists$ curve $\alpha:I\to \mathbb{R}^{3}$ pbal s.t. $k$ is the curvature of $\alpha$ and $\uptau$ is the torsion of $\alpha$.
Moreover, $\alpha$ is unique up to orientation-preserving rigid motions of $\mathbb{R}^{3}$, i.e. 
- $\forall$ regular curve $\overline{\alpha}:I\to \mathbb{R}^{3}$ s.t. $k,\uptau$ are the curvature and torsion of $\overline{\alpha}$, the following equivalent statements hold:
	- $\exists$ orientation-preserving rigid motion $\varphi:\mathbb{R}^{3}\to \mathbb{R}^{3}$ s.t. $\overline{\alpha}=\varphi \circ \alpha$
	- $\exists$ orthogonal operator $\rho:\mathbb{R}^{3}\to \mathbb{R}^{3}$, translation $g\in \mathbb{R}^{3}$ s.t. $\overline{\alpha}=g\circ\rho \circ \alpha$ and $\det \rho>0$
	- $\exists$ orthogonal operator $\rho:\mathbb{R}^{3}\to \mathbb{R}^{3}$, $c\in \mathbb{R}^{3}$ s.t. $\overline{\alpha}=\rho \circ \alpha+c$ and $\det \rho>0$.
	- $\exists A\in SO(3),c\in \mathbb{R}^{3}:\overline{\alpha}=A\alpha+c$.