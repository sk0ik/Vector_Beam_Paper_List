1. [教科書](#教科書)
2. [論文など](#論文など)
   1. [論文をまとめる系の論文](#論文をまとめる系の論文)
   2. [ベクトルビームの用途](#ベクトルビームの用途)
   3. [ベクトルビームの生成方法](#ベクトルビームの生成方法)
   4. [ベクトルビームを集光](#ベクトルビームを集光)
   5. [ベクトルビームの伝播](#ベクトルビームの伝播)
   6. [ベクトルビームの制御](#ベクトルビームの制御)
   7. [ベクトルビームと機械学習](#ベクトルビームと機械学習)
   8. [ベクトルビームと幾何学](#ベクトルビームと幾何学)
   9. [ベクトルビームとGouy位相](#ベクトルビームとgouy位相)
   10. [高次元ポアンカレ球](#高次元ポアンカレ球)
   11. [ベクトルビームの評価方法](#ベクトルビームの評価方法)
   12. [近軸近似のもとでスカラー場に対するヘルムホルツ方程式を解く](#近軸近似のもとでスカラー場に対するヘルムホルツ方程式を解く)
   13. [近軸近似のもとでベクトル場に対するヘルムホルツ方程式を解く](#近軸近似のもとでベクトル場に対するヘルムホルツ方程式を解く)
   14. [近軸近似せずにスカラー場のヘルムホルツ方程式を解く](#近軸近似せずにスカラー場のヘルムホルツ方程式を解く)
   15. [ビームの最適化](#ビームの最適化)


ベクトルビームに関連する教科書や論文などを貼ります.無料で読めない論文もあると思いますがそこは許してください.

# 教科書
ベクトルビームは光の偏光という特徴を扱うのでそこらへんが載っている教科書を挙げます.
でも大体光の教科書には偏光のことは載ってると思うので基礎的なことはお持ちの教科書で十分かなと思います.

偏光に限らず光の勉強を始める際,もしくは光をもっと深くしたときに良い本だと思います.ただ数式が多いのでざっくり理解したい場合は不向きかもしれません.

- [光学-谷田貝豊彦(2017)](https://www.asakura.co.jp/detail.php?book_code=13121)

先ほどと同じ著者の本ですがこっちの方が薄いのでとっつきやすいです.

- [例題で学ぶ光学入門-谷田貝豊彦(2010)](https://www.morikita.co.jp/books/mid/015441)

この本も光を学ぶときとてもタメになる本だと思います.p205-212に偏光を考慮した平面波をレンズによって集光したときのシミュレーションが載っています.

- [はじめての光学-川田善正(2014)](https://www.kspub.co.jp/book/detail/1532878.html)

# 論文など

$\heartsuit$ は個人的に重要だと思ったものです.

## 論文をまとめる系の論文

ベクトルビームの導出から原理,応用まで広く載っています.この論文で引用している論文を読むことが多かったです.

- $\heartsuit$ [Cylindrical vector beams: from mathematical concepts to applications(2009)](https://opg.optica.org/aop/fulltext.cfm?uri=aop-1-1-1&id=176226)

偏光状態はポアンカレ球とよばれる球の表面の1点で表すことができるんですがこれをベクトルビームまで拡張したものが高次元ポアンカレ球というものでこれが紹介されていました.(あとで引用元の論文も載せます.)

- [Vector Beams for Fundamental Physics and Applications(2016)](https://academicworks.cuny.edu/gc_etds/1267/)

名前の通りベクトルビームの応用例が多く載っています.ベクトルビームの有用性を知るという意味ではこれを最初に読んでもよいかもしれません.

- $\heartsuit$ [Vectorial optical fields: recent advances and future prospects(2017)](https://www.sciencedirect.com/science/article/abs/pii/S2095927317306333)

これはベクトルビームではなく光渦という光がらせん状の位相をもつビームについて紹介しています.ベクトルビームは偏光を制御するんですがそのうえで位相も制御すると偏光と位相と言う2つの自由度を持ちこれがいろいろなところで研究されています.

- [Orbital angular momentum: origins, behavior and applications(2011)](https://opg.optica.org/aop/abstract.cfm?uri=aop-3-2-161)

実験でベクトルビームを作る際SLMという素子を使うことが多いです.この論文はSLMについて詳しく紹介しています.

- [Creation and detection of optical modes with spatial light modulators(2016)](https://opg.optica.org/aop/abstract.cfm?uri=aop-8-2-200)

これもSLMについての論文ですが2022年と新しいものなので最近のことが載っています.

- [Spatial Light Modulators and Their Applications in Polarization Holography(2022)](https://www.intechopen.com/chapters/83627)


## ベクトルビームの用途

レーザー加工

- [偏光レーザビームを用いたレーザ加工の高効率化と高機能化](https://ci.nii.ac.jp/naid/500001007468)
- [Femtosecond Laser Processing by Using Patterned Vector Optical Fields](https://www.nature.

光トラッピング

- [Optical trapping of nanotubes with cylindrical vector beams(2012)](https://opg.optica.org/ol/abstract.cfm?uri=ol-37-16-3381)

光スピントロニクス

電子のスピンを光で励起する光スピントロニクスという分野があります.この論文ではベクトルビームを用いてスピン励起をおこなっています.

- $\heartsuit$ [Imprinting spatial helicity structure of vector vortex beam on spin texture in semiconductors(2023)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.130.126701)

## ベクトルビームの生成方法

SLMを使って生成.

- $\heartsuit$ [Holographic femtosecond laser manipulation for advanced material processing](https://www.degruyter.com/document/doi/10.1515/aot-2015-0062/html)
- [Flexible Method for Generating Arbitrary Vector Beams Based on Modified Off-Axis Interference-Type Hologram Encoding](https://www.mdpi.com/2304-6732/9/12/949)
- [Generation of arbitrary cylindrical vector vortex beams with cross-polarized modulation](https://www.sciencedirect.com/science/article/pii/S2211379720319161)
- [Generation of arbitrary vector fields based on a pair of orthogonal elliptically polarized base vectors](https://opg.optica.org/oe/fulltext.cfm?uri=oe-24-4-4177&id=336569)
- [Generation of V-point polarization singularity using single phase encoding with a spatial light modulator](https://www.nature.com/articles/s41598-022-27337-x)
- [A new type of vector fields with hybrid states of polarization](https://opg.optica.org/oe/fulltext.cfm?uri=oe-18-10-10786&id=199402)
- [Cylindrical vector beam multiplexer demultiplexer using off-axis polarization control](https://www.nature.com/articles/s41377-021-00667-7)
- [Efficient generation of vector beams by calibrating the phase response of a spatial light modulator](https://opg.optica.org/ao/abstract.cfm?uri=ao-56-17-4956)
- [Efficient on-axis SLM engineering of optical vector modes](https://www.sciencedirect.com/science/article/abs/pii/S0143816619309959)
- [Flexible generation of the generalized vector vortex beams](https://www.sciencedirect.com/science/article/abs/pii/S0030401821002662)
- [Polarization distribution control of parallel femtosecond pulses with spatial light modulators](https://opg.optica.org/oe/fulltext.cfm?uri=oe-21-11-12987&id=253727)
- [Self-referenced interferometry for single-shot detection of vector-vortex beams](https://www.nature.com/articles/s41598-022-21485-w)
- [Nondiffracting Bessel beams with polarization state that varies with propagation distance](https://opg.optica.org/ol/fulltext.cfm?uri=ol-40-23-5451&id=332517)
- [SLMと共通光路干渉計を用いたベクトルビーム生成](https://www.virtuallab.jp/support/172/)

## ベクトルビームを集光

難しい.けど偏光を考慮した回折はこれが基本原理になっています.
- $\heartsuit$ [Electromagnetic diffraction in optical systems I. An integral representation of the image field](https://royalsocietypublishing.org/doi/10.1098/rspa.1959.0199)
- $\heartsuit$ [Electromagnetic diffraction in optical systems II. Structure of the image field in an aplanatic system](https://royalsocietypublishing.org/doi/10.1098/rspa.1959.0200)

低NAレンズや高NAレンズで集光したときの振る舞いについて.

- $\heartsuit$ [Vector beams excited nonlinear optical effects](https://www.worldscientific.com/doi/abs/10.1142/S0218863518500455)
- [Formation of hybrid higher-order cylindrical vector beams using binary multi-sector phase plates](https://www.nature.com/articles/s41598-018-32469-0)
  
MITの有志の方がベクトルビームの集光を計算するPythonパッケージを作っています.

- $\heartsuit$ [PyFocus – A Python package for vectorial calculations of focused optical fields under realistic conditions. Application to toroidal foci](https://arxiv.org/abs/2110.00160)

高NAのレンズでベクトルビームを集光したときの振る舞いについて.

- [Polarization conversion when focusing cylindrically polarized vortex beams](https://www.nature.com/articles/s41598-016-0015-2)
- [Tight focusing properties and focal field tailoring of cylindrical vector beams generated from a linearly polarized coherent beam array](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-4-5259&id=447176)
- [Variable transformation of singular cylindrical vector beams using anisotropic crystals](https://www.nature.com/articles/s41598-020-62546-2)
- [Focusing of high numerical aperture cylindrical-vector beams](https://opg.optica.org/oe/fulltext.cfm?uri=oe-7-2-77&id=63487)
- [Lensless focusing of hypergeometric laser beams](https://iopscience.iop.org/article/10.1088/2040-8978/13/7/075703/meta)
- [Focusing properties of cylindrical vector vortex beams](https://www.sciencedirect.com/science/article/abs/pii/S0030401817312038)
- [Focusing properties of cylindrical vector vortex beams with high numerical aperture objective](https://www.sciencedirect.com/science/article/abs/pii/S0030402613002520)
- [Nonparaxial and paraxial focusing of azimuthal-variant vector beams](https://opg.optica.org/oe/fulltext.cfm?uri=oe-20-16-17684&id=239991)
- [Tailored intensity landscapes by tight focusing of singular vector beams](https://opg.optica.org/oe/fulltext.cfm?uri=oe-25-17-20194&id=370621)
- [Generation of cylindrical vector beams of high orders using uniaxial crystals](https://iopscience.iop.org/article/10.1088/2040-8978/17/6/065001/meta)
- [Vector-vortex Bessel–Gauss beams and their tightly focusing properties](https://opg.optica.org/ol/abstract.cfm?uri=ol-36-6-888)
- [A Method to Generate Vector Beams with Adjustable Amplitude in the Focal Plane](https://www.mdpi.com/2076-3417/10/7/2313)
- [Tight focusing properties and focal field tailoring of cylindrical vector beams generated from a linearly polarized coherent beam array](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-4-5259)
- [Sharper Focal Spot for a Radially Polarized Beam Using Ring Aperture with Phase Jump](https://www.researchgate.net/publication/258394656_Sharper_Focal_Spot_for_a_Radially_Polarized_Beam_Using_Ring_Aperture_with_Phase_Jump)

## ベクトルビームの伝播

- [The angular spectrum representation of vectorial laser beams](https://arxiv.org/pdf/1107.4690)
- [Propagation properties of a cylindrically polarized vector beam](https://www.sciencedirect.com/science/article/abs/pii/S0030399212002903)
- [Propagation evolution of an off-axis high-order](https://pubmed.ncbi.nlm.nih.gov/25401345/)
- [Propagation of vectorial laser beams](https://opg.optica.org/josab/fulltext.cfm?uri=josab-29-5-990&id=232015)
- [Propagation of radially polarized elegant light beams](https://opg.optica.org/josab/abstract.cfm?uri=josab-24-3-636)
- [The angular spectrum decomposition of vector laser beam polarization control of the electromagnetic field vectors](https://preprints.opticaopen.org/articles/preprint/The_angular_spectrum_decomposition_of_vector_laser_beams_polarization_control_of_the_electromagnetic_field_vectors/23899284/2)
- [Vector plane wave spectrum of an arbitrary polarized electromagnetic wave](https://opg.optica.org/oe/fulltext.cfm?uri=oe-14-6-2095&id=88783)
- [Angular spectrum calculations for arbitrary focal length with a scaled convolution](https://opg.optica.org/oe/fulltext.cfm?uri=oe-19-15-14268&id=220227)

位相がベクトルビームの伝播に与える影響について.

- $\heartsuit$ [Astigmatic transformation of optical vortex beams with high-order cylindrical polarization](https://opg.optica.org/josab/abstract.cfm?uri=josab-36-8-2193)
- [Robust laser beam engineering using polarization and angular momentum diversity](https://opg.optica.org/oe/fulltext.cfm?uri=oe-25-15-17524&id=369369)
- [Gouy phase effects on propagation of pure and hybrid vector beams](https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-3-2374&id=404332)
- [Generation of Perfect Cylindrical Vector Beams With Complete Control Over the Ring Width and Ring Diameter](https://ieeexplore.ieee.org/document/8252695)


非近軸近似のもとでのベクトルビームの伝播.

- [Exact vectorial model for nonparaxial focusing of freeform wavefronts](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-13-23656&id=476993)

ベクトルビームを集光したときの焦点位置のずれ.

- [Focal shift in vector beams](https://opg.optica.org/oe/fulltext.cfm?uri=oe-4-10-411&id=63399)

## ベクトルビームの制御

- [Dynamic control of hybrid grafted perfect vector vortex beams](https://www.nature.com/articles/s41467-023-39599-8)
- [Complete shaping of optical vector beams](https://opg.optica.org/oe/fulltext.cfm?uri=oe-23-14-17701&id=321314)

## ベクトルビームと機械学習

- [Machine learning-based classification of vector vortex beams](https://arxiv.org/abs/2005.07949)
- [Single-shot polarimetry of vector beams by supervised learning](https://www.nature.com/articles/s41467-023-37474-0)

## ベクトルビームと幾何学
- [Full Poincare´ beams]()
- [Generation of A Space-Variant Vector Beam with Catenary-Shaped Polarization States]()
- [Observation of optical polarization Möbius strips]()

## ベクトルビームとGouy位相

- [Wave-Vector-Varying Pancharatnam-Berry Phase Photonic Spin Hall Effect]()
- [光学におけるベリー位相]()
- [Gouy phase effects on propagation of pure and hybrid vector beams]()
- [Manifestation of the Gouy phase in strongly focused, radially polarized beams]()
- [Manifestation of the Gouy phase in vector-vortex beams]()

## 高次元ポアンカレ球

- [Controlled generation of higher-order Poincaré sphere beams from a laser]()
- [Encoding Higher-Order Polarization States into Robust Partially Coherent Optical Beams]()
- [Generation of arbitrary cylindrical vector beams on the higher order Poincare´]()
- [Generalized Poincare sphere]()
- [Higher-Order Poincaré Sphere, Stokes Parameters, and the Angular Momentum of Light]()

## ベクトルビームの評価方法

- [Arbitrary complex retarders using a sequence of spatial light modulators as the basis for adaptive polarisation compensation]()
- [Basis-independent tomography and nonseparability witnesses of pure complex vectorial light fields by Stokes projections]()
- [Beam quality measure for vector beams]()
- [Comprehensive quantitative analysis of vector beam states based on vector field reconstruction]()
- [Concepts in quantum state tomography and classical implementation with intense light a tutorial]()
- [ENTANGLEMENT OF FORMATION AND CONCURRENCE]()
- [Generating arbitrary non-separable states with polarization and orbital angular momentum of light]()
- [Generation and Detection of Structured Light A Review]()
- [Generation of fractional and ultra-high polarization-order vector vortex beams on hybrid-order Poincar´e spheres]()
- [High-order cylindrical vector beams with tunable topologicalcharge up to 14 directly generated from a microchip laser with high beam quality and high efficiency]()
- [High-quality vector vortex arrays by holographic and geometric phase control]()
- [Measuring the nonseparability of vector vortex beams]()
- [Quantum Entanglement of High Angular Momenta]()
- [Quantum−like nonseparable structures in optical beams]()
- [Simultaneous generation of multiple vector beams on a single SLM]()

## 近軸近似のもとでスカラー場に対するヘルムホルツ方程式を解く

- [From Maxwell to paraxial wave optics]()
- [Gaussian Beam 計算メモ]()
http://solidstatephysics.blog.fc2.com/blog-entry-47.html

## 近軸近似のもとでベクトル場に対するヘルムホルツ方程式を解く

- [Separability and Applications]()
- [Vector-beam solutions of Maxwell's wave equation]()
- [Vector Helmholtz–Gauss and vector Laplace–Gauss beams]()
http://solidstatephysics.blog.fc2.com/blog-entry-31.html
- [腰も砕けよ 膝も折れよ]("https://decafish.blog.ss-blog.jp/archive/c2305062484-1)
  
## 近軸近似せずにスカラー場のヘルムホルツ方程式を解く
- [Closed-form bases for the description of monochromatic, strongly focused, electromagnetic fields]()
- [Measuring the nonseparability of vector vortex beams]()
- [Nonparaxial Propagation Properties of Specially Correlated Radially Polarized Beams in Free Space]()

## ビームの最適化
- [A practical algorithm for the determination of phase from image and diffraction plane pictures]()
- [Continuous-relief diffractive optical elements for two-dimensional array generation]()
- [Kinoform design with an optimal-rotation-angle method]()
- [New iterative algorithm for the design of phaseonly gratings]()