---
title: "Lecture 01: Lecture Topic"
layout: post
date: yyyy-mm-dd
---

$$
# include macros
%Swap phi -> varphi and epsilon -> varepsilon
\newcommand{\oldepsilon}{\epsilon}
\renewcommand{\epsilon}{\varepsilon}
\newcommand{\oldphi}{\phi}
\renewcommand{\phi}{\varphi}

% Default macros for working with math
% Standard commands for Mathbb letters
\newcommand{\NN}{\mathbb{N}}
\newcommand{\ZZ}{\mathbb{Z}}
\newcommand{\ZZps}{\mathbb{Z}_{>0}}	 % ZZps = Z (strictly) positive
\newcommand{\ZZnn}{\mathbb{Z}_{\ge 0}}	 % ChkTeX 1 ZZnn = Z non-negative
\newcommand{\QQ}{\mathbb{Q}}
\newcommand{\RR}{\mathbb{R}}
\newcommand{\RRps}{\mathbb{R}_{>0}}
\newcommand{\RRnn}{\mathbb{R}_{\ge 0}}   % ChkTeX 1
\newcommand{\CC}{\mathbb{C}}
\newcommand{\Sn}{\mathbb{S}^{n-1}}
\newcommand{\Sphere}[1]{\mathbb{S}^{#1}}

% Standard commands for mathbb letters
\newcommand{\Abb}{\mathbb{A}}
\newcommand{\Bbb}{\mathbb{B}}
\newcommand{\Cbb}{\mathbb{C}}
\newcommand{\Dbb}{\mathbb{D}}
\newcommand{\Ebb}{\mathbb{E}}
\newcommand{\Fbb}{\mathbb{F}}
\newcommand{\Gbb}{\mathbb{G}}
\newcommand{\Hbb}{\mathbb{H}}
\newcommand{\Ibb}{\mathbb{I}}
\newcommand{\Jbb}{\mathbb{J}}
\newcommand{\Kbb}{\mathbb{K}}
\newcommand{\Lbb}{\mathbb{L}}
\newcommand{\Mbb}{\mathbb{M}}
\newcommand{\Nbb}{\mathbb{N}}
\newcommand{\Obb}{\mathbb{O}}
\newcommand{\Pbb}{\mathbb{P}}
\newcommand{\Qbb}{\mathbb{Q}}
\newcommand{\Rbb}{\mathbb{R}}
\newcommand{\Sbb}{\mathbb{S}}
\newcommand{\Tbb}{\mathbb{T}}
\newcommand{\Ubb}{\mathbb{U}}
\newcommand{\Vbb}{\mathbb{V}}
\newcommand{\Wbb}{\mathbb{W}}
\newcommand{\Xbb}{\mathbb{X}}
\newcommand{\Ybb}{\mathbb{Y}}
\newcommand{\Zbb}{\mathbb{Z}}

% Standard commands for Mathcal letters
\newcommand{\Acal}{\mathcal{A}}
\newcommand{\Bcal}{\mathcal{B}}
\newcommand{\Ccal}{\mathcal{C}}
\newcommand{\Dcal}{\mathcal{D}}
\newcommand{\Ecal}{\mathcal{E}}
\newcommand{\Fcal}{\mathcal{F}}
\newcommand{\Gcal}{\mathcal{G}}
\newcommand{\Hcal}{\mathcal{H}}
\newcommand{\Ical}{\mathcal{I}}
\newcommand{\Jcal}{\mathcal{J}}
\newcommand{\Kcal}{\mathcal{K}}
\newcommand{\Lcal}{\mathcal{L}}
\newcommand{\Mcal}{\mathcal{M}}
\newcommand{\Ncal}{\mathcal{N}}
\newcommand{\Ocal}{\mathcal{O}}
\newcommand{\Pcal}{\mathcal{P}}
\newcommand{\Qcal}{\mathcal{Q}}
\newcommand{\Rcal}{\mathcal{R}}
\newcommand{\Scal}{\mathcal{S}}
\newcommand{\Tcal}{\mathcal{T}}
\newcommand{\Ucal}{\mathcal{U}}
\newcommand{\Vcal}{\mathcal{V}}
\newcommand{\Wcal}{\mathcal{W}}
\newcommand{\Xcal}{\mathcal{X}}
\newcommand{\Ycal}{\mathcal{Y}}
\newcommand{\Zcal}{\mathcal{Z}}

% Standard commands for Mathbf letters
\newcommand{\Abf}{\mathbf{A}}
\newcommand{\Bbf}{\mathbf{B}}
\newcommand{\Cbf}{\mathbf{C}}
\newcommand{\Dbf}{\mathbf{D}}
\newcommand{\Ebf}{\mathbf{E}}
\newcommand{\Fbf}{\mathbf{F}}
\newcommand{\Gbf}{\mathbf{G}}
\newcommand{\Hbf}{\mathbf{H}}
\newcommand{\Ibf}{\mathbf{I}}
\newcommand{\Jbf}{\mathbf{J}}
\newcommand{\Kbf}{\mathbf{K}}
\newcommand{\Lbf}{\mathbf{L}}
\newcommand{\Mbf}{\mathbf{M}}
\newcommand{\Nbf}{\mathbf{N}}
\newcommand{\Obf}{\mathbf{O}}
\newcommand{\Pbf}{\mathbf{P}}
\newcommand{\Qbf}{\mathbf{Q}}
\newcommand{\Rbf}{\mathbf{R}}
\newcommand{\Sbf}{\mathbf{S}}
\newcommand{\Tbf}{\mathbf{T}}
\newcommand{\Ubf}{\mathbf{U}}
\newcommand{\Vbf}{\mathbf{V}}
\newcommand{\Wbf}{\mathbf{W}}
\newcommand{\Xbf}{\mathbf{X}}
\newcommand{\Ybf}{\mathbf{Y}}
\newcommand{\Zbf}{\mathbf{Z}}

% Standard commands for Mathrm letters
\newcommand{\Arm}{\mathrm{A}}
\newcommand{\Brm}{\mathrm{B}}
\newcommand{\Crm}{\mathrm{C}}
\newcommand{\Drm}{\mathrm{D}}
\newcommand{\Erm}{\mathrm{E}}
\newcommand{\Frm}{\mathrm{F}}
\newcommand{\Grm}{\mathrm{G}}
\newcommand{\Hrm}{\mathrm{H}}
\newcommand{\Irm}{\mathrm{I}}
\newcommand{\Jrm}{\mathrm{J}}
\newcommand{\Krm}{\mathrm{K}}
\newcommand{\Lrm}{\mathrm{L}}
\newcommand{\Mrm}{\mathrm{M}}
\newcommand{\Nrm}{\mathrm{N}}
\newcommand{\Orm}{\mathrm{O}}
\newcommand{\Prm}{\mathrm{P}}
\newcommand{\Qrm}{\mathrm{Q}}
\newcommand{\Rrm}{\mathrm{R}}
\newcommand{\Srm}{\mathrm{S}}
\newcommand{\Trm}{\mathrm{T}}
\newcommand{\Urm}{\mathrm{U}}
\newcommand{\Vrm}{\mathrm{V}}
\newcommand{\Wrm}{\mathrm{W}}
\newcommand{\Xrm}{\mathrm{X}}
\newcommand{\Yrm}{\mathrm{Y}}
\newcommand{\Zrm}{\mathrm{Z}}

% Standard commands for Mathsf letters
\newcommand{\Asf}{\mathsf{A}}
\newcommand{\Bsf}{\mathsf{B}}
\newcommand{\Csf}{\mathsf{C}}
\newcommand{\Dsf}{\mathsf{D}}
\newcommand{\Esf}{\mathsf{E}}
\newcommand{\Fsf}{\mathsf{F}}
\newcommand{\Gsf}{\mathsf{G}}
\newcommand{\Hsf}{\mathsf{H}}
\newcommand{\Isf}{\mathsf{I}}
\newcommand{\Jsf}{\mathsf{J}}
\newcommand{\Ksf}{\mathsf{K}}
\newcommand{\Lsf}{\mathsf{L}}
\newcommand{\Msf}{\mathsf{M}}
\newcommand{\Nsf}{\mathsf{N}}
\newcommand{\Osf}{\mathsf{O}}
\newcommand{\Psf}{\mathsf{P}}
\newcommand{\Qsf}{\mathsf{Q}}
\newcommand{\Rsf}{\mathsf{R}}
\newcommand{\Ssf}{\mathsf{S}}
\newcommand{\Tsf}{\mathsf{T}}
\newcommand{\Usf}{\mathsf{U}}
\newcommand{\Vsf}{\mathsf{V}}
\newcommand{\Wsf}{\mathsf{W}}
\newcommand{\Xsf}{\mathsf{X}}
\newcommand{\Ysf}{\mathsf{Y}}
\newcommand{\Zsf}{\mathsf{Z}}

% Standard commands for Mathscr letters
\newcommand{\Ascr}{\mathscr{A}}
\newcommand{\Bscr}{\mathscr{B}}
\newcommand{\Cscr}{\mathscr{C}}
\newcommand{\Dscr}{\mathscr{D}}
\newcommand{\Escr}{\mathscr{E}}
\newcommand{\Fscr}{\mathscr{F}}
\newcommand{\Gscr}{\mathscr{G}}
\newcommand{\Hscr}{\mathscr{H}}
\newcommand{\Iscr}{\mathscr{I}}
\newcommand{\Jscr}{\mathscr{J}}
\newcommand{\Kscr}{\mathscr{K}}
\newcommand{\Lscr}{\mathscr{L}}
\newcommand{\Mscr}{\mathscr{M}}
\newcommand{\Nscr}{\mathscr{N}}
\newcommand{\Oscr}{\mathscr{O}}
\newcommand{\Pscr}{\mathscr{P}}
\newcommand{\Qscr}{\mathscr{Q}}
\newcommand{\Rscr}{\mathscr{R}}
\newcommand{\Sscr}{\mathscr{S}}
\newcommand{\Tscr}{\mathscr{T}}
\newcommand{\Uscr}{\mathscr{U}}
\newcommand{\Vscr}{\mathscr{V}}
\newcommand{\Wscr}{\mathscr{W}}
\newcommand{\Xscr}{\mathscr{X}}
\newcommand{\Yscr}{\mathscr{Y}}
\newcommand{\Zscr}{\mathscr{Z}}

% Probability Theory Macros
\newcommand{\prob}{\Pr}
\renewcommand{\Pr}{\mathbb{P}}
\newcommand{\Ex}{\mathbb{E}}
\newcommand{\given}{\mid}
\newcommand{\Ind}[1]{\mathbf{1}_{#1}}
\newcommand{\IndCond}[1]{\mathbf{1}_{\left\{#1\right\}}}
\newcommand{\Var}{\operatorname{Var}}
\newcommand{\Corr}{\operatorname{Corr}}
\newcommand{\Cov}{\operatorname{Cov}}

% Specific Distributions
\newcommand{\Gauss}{\operatorname{Gauss}}
\newcommand{\Pois}{\operatorname{Pois}}
\newcommand{\Unif}{\operatorname{Unif}}
\newcommand{\Haar}{\operatorname{Haar}}

% Geometry Macros
\newcommand{\Aff}{\operatorname{Aff}}
\newcommand{\Lin}{\operatorname{Lin}}
\newcommand{\Span}{\operatorname{Span}}
\newcommand{\Rank}{\operatorname{Rank}}
\newcommand{\Null}{\operatorname{Null}}
\newcommand{\Range}{\operatorname{Range}}
\newcommand{\Area}{\operatorname{Area}}
\newcommand{\Conv}{\operatorname{Conv}}
\newcommand{\Diam}{\operatorname{Diam}}
\newcommand{\dist}{\operatorname{dist}}
\newcommand{\Vol}{\operatorname{Vol}}
\newcommand{\Proj}{\operatorname{Proj}}
\newcommand{\Perim}{\operatorname{Perim}}
\newcommand{\polar}{^{\circ}}
\newcommand{\Frob}{\operatorname{Frob}}
\newcommand{\HS}{\operatorname{HS}}
\newcommand{\relintr}{\operatorname{rel.\,int.}}
\newcommand{\relbd}{\operatorname{rel.\,bd.}}
\newcommand{\relcl}{\operatorname{rel.\,cl.}}
\newcommand{\bd}{\operatorname{bd.}}
\newcommand{\intr}{\operatorname{int.}}
\newcommand{\cl}{\operatorname{cl.}}

% Measure Theory Macros
\newcommand{\esssup}{\operatorname{ess\,sup}}
\newcommand{\essinf}{\operatorname{ess\,inf}}
\newcommand{\supp}{\operatorname{supp}}
\newcommand{\esssupp}{\operatorname{ess\,supp}}

% Linear and Functional Analysis Macros
\newcommand{\Id}{\operatorname{Id}}
\newcommand{\TV}{\operatorname{TV}}
\newcommand{\eigvals}{\operatorname{Eig.\,Vals.}}
\newcommand{\eigvecs}{\operatorname{Eig.\,Vecs.}}
\newcommand{\eigfuncs}{\operatorname{Eig.\,Funcs.}}
\newcommand{\Grad}{\operatorname{grad}}
\newcommand{\Div}{\operatorname{div}}
\newcommand{\coker}{\operatorname{coker}}
\newcommand{\codim}{\operatorname{codim}}
\newcommand{\sa}{^{\mathsf{sa}}}
\newcommand{\transpose}{^{\intercal}}
\newcommand{\conjugate}{^{\mathsf{*}}}
\newcommand{\adjoint}{^{\mathsf{*}}}
\newcommand{\dual}{^{\mathsf{*}}}
\newcommand{\oldstar}{\star}
\renewcommand{\star}{^{\mathsf{*}}}
\newcommand{\inverse}{^{-1}}
\newcommand{\psinverse}{^{\dagger}}

% Integral Macros
\newcommand*{\dd}{\mathop{}\!\mathrm{d}}
\newcommand*{\ds}{\dd s} % ChkTeX 1
\newcommand*{\dt}{\dd t} % ChkTeX 1
\newcommand*{\du}{\dd u} % ChkTeX 1
\newcommand*{\dv}{\dd v} % ChkTeX 1
\newcommand*{\dx}{\dd x} % ChkTeX 1
\newcommand*{\dy}{\dd y} % ChkTeX 1
\newcommand*{\dz}{\dd z} % ChkTeX 1
\newcommand*{\dr}{\dd r} % ChkTeX 1
\newcommand*{\dw}{\dd \omega} % ChkTeX 1
\newcommand*{\dth}{\dd \theta} % ChkTeX 1
\newcommand*{\mudw}{\mathop{}\!\mu(\mathrm{d}\omega)}
\newcommand*{\mudx}{\mathop{}\!\mu(\mathrm{d}x)}
\newcommand*{\mudy}{\mathop{}\!\mu(\mathrm{d}y)}
\newcommand*{\mudz}{\mathop{}\!\mu(\mathrm{d}z)}
\newcommand*{\nudw}{\mathop{}\!\nu(\mathrm{d}\omega)}
\newcommand*{\nudx}{\mathop{}\!\nu(\mathrm{d}x)}
\newcommand*{\nudy}{\mathop{}\!\nu(\mathrm{d}y)}
\newcommand*{\nudz}{\mathop{}\!\nu(\mathrm{d}z)}
\newcommand*{\lmdw}{\mathop{}\!\lambda(\mathrm{d}\omega)}
\newcommand*{\lmdx}{\mathop{}\!\lambda(\mathrm{d}x)}
\newcommand*{\lmdy}{\mathop{}\!\lambda(\mathrm{d}y)}
\newcommand*{\lmdz}{\mathop{}\!\lambda(\mathrm{d}z)}
\newcommand*{\gmdw}{\mathop{}\!\gamma(\mathrm{d}\omega)}
\newcommand*{\gmdx}{\mathop{}\!\gamma(\mathrm{d}x)}
\newcommand*{\gmdy}{\mathop{}\!\gamma(\mathrm{d}y)}
\newcommand*{\gmdz}{\mathop{}\!\gamma(\mathrm{d}z)}
\newcommand*{\prdw}{\mathop{}\!\Pr(\mathrm{d}\omega)}
\newcommand*{\prdx}{\mathop{}\!\Pr(\mathrm{d}x)}
\newcommand*{\prdy}{\mathop{}\!\Pr(\mathrm{d}y)}
\newcommand*{\prdz}{\mathop{}\!\Pr(\mathrm{d}z)}
\newcommand*{\sgdth}{\mathop{}\!\sigma(\mathrm{d}\theta)}
\newcommand*{\Hdx}{\mathop{}\!\mathcal{H}(\mathrm{d}x)} % ChkTeX 36
\newcommand*{\Hdy}{\mathop{}\!\mathcal{H}(\mathrm{d}y)} % ChkTeX 36
\newcommand*{\Hdz}{\mathop{}\!\mathcal{H}(\mathrm{d}z)} % ChkTeX 36

% Derivative Macros
\newcommand*{\pd}{\partial}
\newcommand*{\grad}{\nabla}
\newcommand{\divisionsymbol}{\div}
\renewcommand*{\div}{\nabla\cdot}
\newcommand*{\curl}{\nabla\times}
\newcommand*{\laplacian}{\nabla^2}
\newcommand*{\DirD}{\mathbf{D}}
\newcommand*{\hessian}{\mathbf{H}}
\newcommand*{\jacobian}{\mathbf{J}}

% Algebra & Category Theory Macros
\newcommand{\op}{^{\mathsf{op}}}
\newcommand{\Hom}{\operatorname{Hom}}
\newcommand{\End}{\operatorname{End}}
\newcommand{\Sym}{\operatorname{Sym}}
\newcommand{\Aut}{\operatorname{Aut}}
\newcommand{\Gal}{\operatorname{Gal}}
\newcommand{\Stab}{\operatorname{Stab}}
\newcommand{\Orb}{\operatorname{Orb}}
\newcommand{\OrthogonalGr}{\operatorname{O}}
\newcommand{\UnitaryGr}{\operatorname{U}}
\newcommand{\GL}{\operatorname{GL}}
\newcommand{\SL}{\operatorname{SL}}
\newcommand{\Sp}{\operatorname{Sp}}
\newcommand{\SO}{\operatorname{SO}}
\newcommand{\SU}{\operatorname{SU}}
\newcommand{\PGL}{\operatorname{PGL}}
\newcommand{\PSL}{\operatorname{PSL}}
\newcommand{\PSO}{\operatorname{PSO}}
\newcommand{\PSU}{\operatorname{PSU}}

% Set Theory Macros
\newcommand{\comp}{^{\mathsf{c}}}
\newcommand{\compl}{^{\mathsf{c}}}
\renewcommand{\complement}{^{\mathsf{c}}}
\newcommand{\Event}[1]{\left\{ #1 \right\}}
\newcommand{\Set}[2]{\left\{ #1 \;\middle\mid\; #2 \right\}}
\newcommand{\card}{\operatorname{Card}}
\newcommand{\Card}{\operatorname{Card}}
\newcommand{\pset}[1]{2^{#1}}

% Macros for Limit Shorthands
\newcommand{\toUnif}{\xrightarrow{\text{unif}}}
\newcommand{\toAe}{\xrightarrow{\text{a.e.}}}
\newcommand{\toMeas}{\xrightarrow{\text{in meas.}}}
\newcommand{\toWeak}{\xrightarrow{\text{weak}}}
\newcommand{\toWeakSt}{\xrightarrow{\text{weak}-*}}
\newcommand{\toDist}{\xrightarrow{\text{in dist.}}}
\newcommand{\upto}{\nearrow}
\newcommand{\downto}{\searrow}
\renewcommand{\to}{\longrightarrow}
\newcommand{\toAs}{\xrightarrow}
\newcommand{\toIn}{\xrightarrow}
\renewcommand{\mapsto}{\longmapsto}

%Math operators otherwise not defined
\newcommand{\argmax}{\operatorname{arg\,max}}
\newcommand{\argmin}{\operatorname{arg\,min}}
\newcommand{\lcm}{\operatorname{lcm}}
\newcommand{\real}{\operatorname{Re}}
\newcommand{\imag}{\operatorname{Im}}
\renewcommand{\Re}{\operatorname{Re}}
\renewcommand{\Im}{\operatorname{Im}}
\newcommand{\sign}{\operatorname{Sign}}
\newcommand{\Res}{\operatorname{Res}}
\newcommand{\tr}{\operatorname{tr}}
\newcommand{\Tr}{\operatorname{tr}}

% Generic Text Manipulation Macros
\newcommand{\txand}{\text{ and }}
\newcommand{\txor}{\text{ or }}
\newcommand{\txforany}{\text{ for any }}
\newcommand{\txforsome}{\text{ for some }}
\newcommand{\caseif}{& \text{ if }}
\newcommand{\caseotherwise}{& \text{ otherwise}}
\newcommand{\SPC}{\mathop{}\!}

%Replace non-wide with wide when available
\renewcommand{\bar}[1]{\overline{#1}}
\renewcommand{\hat}[1]{\widehat{#1}}
\renewcommand{\tilde}[1]{\widetilde{#1}}

% Fix minor font issues
\let\oldvec=\vec % ChkTeX 1 ChkTeX 14
\renewcommand{\vec}[1]{\oldvec{\mathbf{#1}}}

% Some standard environments
\newcommand{\norm}[1]{\left\lVert #1 \right\rVert}
\newcommand{\abs}[1]{\left\lvert #1 \right\rvert}
\newcommand{\floor}[1]{\left\lfloor #1 \right\rfloor}
\newcommand{\ceil}[1]{\left\lceil #1 \right\rceil}
\newcommand{\bra}[1]{\left\langle #1 \right\rvert}
\newcommand{\Cra}[1]{\left\langle #1 \right\rveCt}
\newcommand{\ket}[1]{\left\lvert #1 \right\rangle}
\newcommand{\braketO}[1]{\left\langle #1 \middle\mid #1\right\rangle}
\newcommand{\ketbraO}[1]{\left\lvert #1\right\rangle\left\langle #1\right\rvert}
\newcommand{\braket}[2]{\left\langle #1 \middle\mid #2\right\rangle}
\newcommand{\Craket}[2]{\left\langle #1 \middle\mid #2\right\rangCe}
\newcommand{\ketbra}[2]{\left\lvert #1\middle\rangle\middle\langle #2\right\rvert}
\newcommand{\braketA}[3]{\left\langle #1 \middle\mid #2 \middle\mid #3\right\rangle}
\newcommand{\CraketA}[3]{\left\langle #1 \middle\mid #2 \middle\mid #3\right\rangCe}
\newcommand{\InnerO}[1]{\left\langle #1, #1 \right\rangle}
\newcommand{\InnerP}[2]{\left\langle #1, #2\right\rangle}
\newcommand{\Generates}[2]{\left\langle #1 \;\middle\mid\; #2 \right\rangle}
\newcommand{\BigO}[1]{\mathcal{O}\left(#1\right)}
\newcommand{\CigO}[1]{\mathcal{O}\left(#1\righC)}
\newcommand{\LittleO}[1]{\mathcal{o}\left(#1\right)}
\newcommand{\BigTheta}[1]{\Theta\left(#1\right)}
\newcommand{\CigTheta}[1]{\Theta\left(#1\righC)}
\newcommand{\BigOmega}[1]{\Omega\left(#1\right)}
\newcommand{\CigOmega}[1]{\Omega\left(#1\righC)}

% Quantum Mechanics Specific Characters
\newcommand{\upbra}{\bra{\uparrow}}
\newcommand{\dnbra}{\bra{\downarrow}}
\newcommand{\upket}{\ket{\uparrow}}
\newcommand{\dnket}{\ket{\downarrow}}
\newcommand{\phibra}{\bra{\phi}}
\newcommand{\phiket}{\ket{\phi}}
\newcommand{\psibra}{\bra{\psi}}
\newcommand{\psiket}{\ket{\psi}}
$$

## Lecture 01

When writing up lecture notes, it's advisable to use either PDFs which embed in markdown files or markdown files directly where you can capture the gist of a lecture and the arguments of a proof without having to do the details. 

Filling in the details of an outline of a proof is a great way to encourage that you retain the information from a lecture. 