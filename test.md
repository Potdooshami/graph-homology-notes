
# 1. Motivation
Field $\phi: X\rightarrow F$  
Where base space $X=R^2$     
and order parameter space  $F=S^1\cup\{0\}$  
$0$ is for a vortex core. 

## 1.2. Vortex with continuous order parameter space  
### 1.2.1. Topological protection
![alt text](image-3.png)
Pannel B is a topologically protected vortex.  
It means that we can't remove it by continuous deformation.  
It means that pannel A can't be connected to pannel B by continuous deformation.  
By this, the vortex(singularity) is robust under external perturbation.  
Quantized(Partivle-like property).  
If order parameter space is $S^2$ or R2, then the vortex can be removed by continuous deformation 
and there is no topological protection.

### 1.2.2. Classification of vortex

![alt text](image.png)  
![alt text](image-6.png)
(a) and (b) looks very different but they are topologically same.  
(c) shows that (a),(b) can be connected by continuous deformation.  
The method of classification is a fundamental group.  
red a,b,c is a classification by fundamental group.

### 1.2.3. Bulk-Boundary correspendence(conservation rule 1)
![alt text](image-4.png)

### 1.2.4. Vortex Dynamics(conservation rule 2)
![alt text](image-5.png)
vortex-antivortex pair creation and annihilation.  
It is impossible to create a single vortex but it is possible to create a pair of vortex and antivortex.  
It is similar to single point charge problem in electrodynamics.  
Single charge's energy can be obtained by integraion of electric field in the whole space and the
corresponding energy is infinite.(this is the why most of natual stable objects are neutral eventhoug their elementary building blocks are charged).  
In particle physics, electron and positron can be created and annihilated in the vacuum.  
Similarly, vortex and antivortex can be created and annihilated in the plane ordering.


## 1.1. Vortex with discrete order parameter space
### 1.1.1. Manifold vs Graph
### 1.1.2. Fractional charge


  
# 2. Formalism
## 2.1. Domain wall network
### 2.1.1. Domain wall network(DWN)
$$D:=(P,\Phi,c)$$
where $P$ is a *base graph*, mathematically plane graph $(V,E,F)$.  
We'll use Bourbaki's definition of graph about $V,E$ and  
here, $F$ is a face cycles defined in clock-wise order.  
$f = \langle e_1,e_2,\cdots,e_n\rangle$ where $\langle \rangle$ is a cyclically ordered sequence.  
$V,E,F$  are called  *domains, domain walls, domin vortices*   respectively.  
$\Phi$ is a *order parameter set*, mathematically set,  
$c$ is a *coloring*, mathematically function $c:V(P)\rightarrow \Phi$ whose incidence is differnet.
### 2.1.2. Symmetry breaking,  Degenerate ground states, Phase
#### 2.1.2.1. Symmetry breaking
$$G_{broken}<G_{origin}$$
#### 2.1.2.2. Degenerate ground states
$$\Phi= G_{origin}/G_{broken}$$
#### 2.1.2.3. Phase
If $G_{broken}\lhd G_{origin}$, then $\Phi$ is a group and called *phase group*. and for domain $v\in V(P)$, $c(v)\in \Phi$ is called *phase of domain*.  

### 2.1.3. Phase domain wall network(pDWN)
#### 2.1.3.1. Definition
Domain wall network $D$ is a pDWN if $\Phi$ is a phase group.
#### 2.1.3.2. Phase shift of domain wall
*shift map* is defined by
$$c_{dw}: E(P)\rightarrow \Phi \quad 
\phi \mapsto c(o(e))^{-1}*c(t(e))$$
$c_{dw}(e)$ is called *phase shift of domain wall* $e$.  
$c_{dw}(e)\neq1_{\Phi}$  
$c_{dw}(\bar{e})=\{c_{dw}(e)\}^{-1}$ 

#### 2.1.3.3. Phase loop of vortex
$$f\in F(P) \quad f=\langle e_1,e_2,\cdots,e_n\rangle$$
$$c_{vor}(f):=\langle c_{dw}(e_1),c_{dw}(e_2),\cdots,c_{dw}(e_n)\rangle$$
$c_{vor}(f)$ is called *phase loop of vortex* $f$.  
$c_{dw}(e_1)*c_{dw}(e_2)*\cdots*c_{dw}(e_n)=1_{\Phi}$

#### 2.1.3.4. Phase equivalence
If $c(v_1)=c(v_2)$, then two domains $v_1$,$v_2$ are called *phase equivalent*.  
If $c_{dw}(e_1)=c_{dw}(e_2)$, then two domain walls $e_1$,$e_2$ are called *phase equivalent*.   
If $c_{vor}(f_1)=c_{vor}(f_2)$, then two vortices $f_1$,$f_2$ are called *phase equivalent*. 

#### 2.1.3.5. Guage invariance
In electrodynamics, if we add a gauge transformation ($V \rightarrow V+V_0$) to the theory, the physical predictions($\overrightarrow{E} ,\rho$) should not change.  
Similarly, in pDWN $D=(P,\Phi,c)$, we can easily define new coloring $c'$ by $c'(v)=c(v)*\phi_0$ where $\phi_0\in \Phi$ then $D'=(P,\Phi,c')$ is also a pDWN.   
$c_{dw}$ and $c_{vor}$ are invariant under this transformation.

### 2.1.4. Boundary decomposition
#### Path
path, homotopy equivalence,cycle,  homology equivalence(cyclic permuation=no basepoint)
#### Boundary
Boundary(=cycle with clock-wise direction)  
Boundary phase(=boundary elemnt-wise phase shift)  
Boundary phase should be 0

## 2.2. Order parameter space
### 2.2.1. degenerate ground states
### 2.2.2. possible dw
elements of $\Phi$ except $1_{\Phi}$
### 2.2.3. possible vor
$\phi_1\phi_2\cdots\phi_n=1_{\Phi}$.
vortex only or correspondind antivortex.
### 2.2.4. order parameter space
order parameter space is Caley complex!!  
0-cell: phase of domain  
1-cell: phase shift of domain wall  
2-cell: phase loop of vortex  
3-cell: vortex-dynamics
## for given boundary...
is it possible configuration?  
= given boundary can be decomposed into possible vortex?  
by drawing van-kampen diagram  
van-kampen diagram  
      
order parameter scheme:   
path on orderparameter space.  
If path is a boundary, then it is a possible configuration.   
If path is not a boundary but cycle, then it is not a possible configuration.

vortex dynamics  
vortex들끼리의 연산 경우.
서로 다른 D1,D2를 3-cell이 이어준다.

Topological charge:
G=<R|S>로 구성.  
Z(G)가 위상 불변량이 됨.  
phase loop를 lift하면 possible shift에 대해 Z(G)의 원소 나옴.  
위에꺼 증명.  
Central extension 2-cocycle이랑 관련  
와 스토크스 정리


# 3. Examples
## 3.1. $Z_2\times Z_2 $
### 3.1.1. all dw
#### 3.1.1.1. vortex, anti-vortex, abab-vortex *
### 3.1.2. 01,10 dw
#### 3.1.2.1. abab vortex
## 3.2. $Z_2\times Z_2\times Z_2$
## 3.3. $Z_3\times Z_3$
### 3.3.1. $z_{12}, z_{23}$


