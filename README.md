# Tau Core Paper 22 — A Tau Core mikrovilága és nagy egyesítése / The Quantum, Electromagnetic, Particle, and Quantum-Gravity Micro-World of Tau Core (`v25`, `k = 0`)

Ez a repository tartalmazza a **Tau Core 22. tanulmányát** (magyar és angol nyelven), a 12 publikációs minőségű kétnyelvű ábrát, valamint az önállóan futtatható **`F51 / Gate E27`** verifikációs és kísérleti auditprogramot (`scripts/compute_micro_world_unification_audit.py`), amely nulla szabad paraméterrel (`k = 0`) vezeti le és teszteli a kvantummechanika, az elektromágnesesség, a részecskefizika és a kvantumgravitáció egyesítését.

---

## 2026-11-23: a CP- és újrafűtési számítás határa

Azonos kisenergiás neutrínóadatok mellett az ellentétes komplex seesaw-
orientáció ellentétes összegzett, ízfelbontás nélküli bomlási forrást ad;
valós szögnél ez a forrás nulla. A közölt barionaszimmetria ezért a
választott UV- és újrafűtési előírás feltételes numerikus eredménye.
A pozitív szupernyom önmagában nem választja ki az N=4 esetet.

## Korábbi számítások és összehasonlítások (`F51 / Gate E27`)

| Pillér / Szektor | Tau Core levezetés (`k = 0`) | Számszerű előrejelzés | Kísérleti mérés / Korlát | Egyezés / Státusz |
| :--- | :--- | :--- | :--- | :--- |
| **I. Kvantummechanika** (`Paper VI, F37, F44, C1`) | Metrikus–szimplektikus Hilbert-tér ($J^2=-I$), Born-szabály ($c_{\mathrm{proj}}=1/2$), Uhlmann-húr $x_A=x_Q$, OS reflexiós pozitivitás $\mathcal{D}_{\mathrm{OS}}^{\mathrm{op}}(\nu)$ | $x_A - x_Q = 0$, $\mathcal{D}_{\mathrm{OS}}^{\mathrm{op}}(1)=1$, $\mathcal{D}_{\mathrm{OS}}^{\mathrm{op}}(0)=0 \implies m_1=0\;\mathrm{meV}$ | Bell/CHSH, késleltetett választású kvantumradír (`no-signalling`) | **`4,44 × 10⁻¹⁶`** gépi precizitású egyezés |
| **II. Elektromágnesesség & elektrogyenge szög** (`Paper VII-A, Paper 4`) | $3+2$ stabilizátor hipertöltés-zár: $\kappa_\tau^2 = 3/5 \implies \sin^2\theta_W(M_*) = 3/8 = 0{,}375$ | $\sin^2\theta_W(M_Z)_{\overline{\mathrm{MS}}} = \mathbf{0{,}231220}$; $\sin^2\theta_W(Q_{\mathrm{MOLLER}}) = 0{,}23852$ | `PDG 2024`: $0{,}23121 \pm 0{,}00004$; `JLab Qweak`: $0{,}2383 \pm 0{,}0011$ | **`+0,25 σ`** (`PDG 2024`) |
| **II/B. PeV foton és graviton terjedés** (`COV-DIR, Gate P11`) | Rank–1 hosszanti óra-direktor ($Z_T=1 \implies c_{\mathrm{EM}}=c_{\mathrm{GW}}=c$), $c_1=0$, kvadratikus plakett $\Delta c/c = \frac{1}{2}(E/M_*)^2$ | $\Delta c/c = \mathbf{1{,}58\times 10^{-24}}$ ($2{,}5\;\mathrm{PeV}$-nél) | `LHAASO` ($2{,}5\;\mathrm{PeV}$): $< 10^{-20}$; `GW170817`: $< 3\times 10^{-15}$ | **PASS** (`> 6 000×` a korlát alatt) |
| **III. Neutrínótömegek és $\mathrm{Spin}(10)$** (`Theorem C1, Paper 15, Gate P8–P9`) | $\mathrm{Spin}(10)$ $(3,9,8,48)$ + $\eta_{\mathrm{seesaw}} = (8\sqrt{3}-9)^2/768 = 0{,}03070922$ + 1-hurkos $B_0=1$ $K_4$ küszöb | $(m_1, m_2, m_3) = \mathbf{(0;\;8{,}831;\;50{,}361)\;\mathrm{meV}}$, $\sum m_\nu = \mathbf{59{,}19\;\mathrm{meV}}$ | `NuFIT 5.3` (NO): $\Delta m_{31}^2 = 2{,}511\times 10^{-3}\;\mathrm{eV}^2$; `DESI+Planck`: $< 72\;\mathrm{meV}$ | **`+0,90 σ`** (`NuFIT 5.3`), **PASS** (`DESI+Planck`) |
| **III/B. Szektorok közötti híd-egyenlet** (`Theorem 4.1`) | $\eta_{\mathrm{seesaw}} \equiv \frac{1}{768}\left(\frac{520(\Omega_A/\Omega_b)+160}{213}-9\right)^2$ | $\Omega_A/\Omega_b = 5{,}3681 \Longleftrightarrow m_3 = 50{,}36\;\mathrm{meV}$ | `Planck PR3` ($5{,}364 \pm 0{,}065$) $\times$ `NuFIT 5.3` ($50{,}11 \pm 0{,}28\;\mathrm{meV}$) | **1σ közös metszéspont** ($0$ szabad paraméter!) |
| **III/C. Higgs-bozon és top-kvark** (`Paper 4, Gate P10`) | $\nu_D = \kappa_\tau^2/2 = 3/10 \implies I_4(3/10)$ negyedrendű átfedés és híd-nyom Yukawa | $I_4(3/10) = \mathbf{0{,}133756}$ ($\kappa_\lambda = 1{,}0347$), $y_t^{\mathrm{parent}} = \mathbf{0{,}961552}$ | `LHC Run-3`: $\lambda_H^{\mathrm{obs}} = 0{,}12938$, $y_t \in [0{,}935;\;0{,}991]$ | **PASS** (`HL-LHC` $\kappa_\lambda$ teszt) |
| **IV. Kvantumgravitáció és `BMV` összefonódás** (`Paper VII-C, Gate P12`) | 15-csatornás `CHDF` ($\mathrm{Tr}=0$), $\Phi_{K_4}=\Phi_0-\Phi_m$, $\ell_\tau(1\;\mathrm{pg}) = 0{,}86\;\mu\mathrm{m}$ | Földön: $1{,}000000\times$ GR (EFE $2{,}7\times 10^{-22}$); **L1/L2 űr-nyeregpontban: `3,463×` erősítés!** | Földi `BMV` vs. L1/L2 nyeregponti (`MAQRO`) űr-interferometria | **Döntő kvantumgravitációs vakteszt (`P12`)** |

---

## Kéziratok és Futtatás

- **Magyar nyelvű kézirat:** `Tau_Core_Paper_22_Quantum_Particle_EM_Unification_HU.pdf`
- **Angol nyelvű kézirat:** `Tau_Core_Paper_22_Quantum_Particle_EM_Unification_EN.pdf`
- **Verifikáció futtatása:**
  ```bash
  python3 scripts/compute_micro_world_unification_audit.py
  python3 scripts/generate_paper22_figures.py
  ```


---

## 2026-11-24: Közvetlen folytatás — Paper 30 (`v1.6.0`)

A jelen tanulmány egygenerációs $\mathrm{Spin}(10)$ vázlatát a **`tau-core-spin10-flavor-hierarchy-smg-paper30`** (`Paper 30 v1.6.0`, commit `485b3f7`) viszi tovább a teljes 4-szimplex 32-dimenziós $\Lambda^{\mathrm{even}}(\mathbb{C}^5)$ Clifford-algebrára, a 16 paraméteres Paritás–Hermitikus 3-generációs íz-zárásra ($\mathrm{PH16}_{a13,h23}$, $\bar\theta_{\mathrm{QCD,tree}} \equiv 0$), a teljes $d=5$ és $d=6$ protonbomlás-, 2-hurkos egyesülés-, valódi 2-hurkos Bagnaschi Split-SUSY Higgs-tömeg és III.D pillér UV/RPV zárásra (amely a $\mathbb{Z}_2^{(210)}$ fázispajzs-\texttt{NO-GO} és 2-ízű Nardi ODE leptogenezis-előjelváltás miatt az **Alacsony-$\tan\beta$ Split-SUSY Sziget + apró bilineáris RPV** ág felé billenti a mérleget: $\tan\beta\in[2{,}0;\; 2{,}6], M_{\tilde q}\in[131;\; 214]\;\mathrm{TeV}, 100\%$ AeST DM, $T_{\mathrm{rh}}^{\max}=1{,}07\times 10^{11}\;\mathrm{GeV}$) és a 24-cellás királis rács 32-Majoranás SMG átmenetére. A befagyasztott Paper 22 archívum változatlan maradt.

---

## 2026-11-25: `Q-DEC / T-DEC` Addendum — UV Kähler-egyesítés, egyedi $\mathbb{C}$-kiválasztás, mutató-óra és $\mathrm{SM}+3\nu_R$ horizont-kioltódás (`NATURE_LEVEL_CLOSURE = false`)

Öt Stage-A referens által jóváhagyott szkript (`tau-core-theory/qdec_tdec_kahler_k4_audit_2026_11_25/`, `python3 -W error`, `rc = 0`) pontosítja a `Q-DEC / T-DEC` algebrai határát:
- **UV Kähler-egyesítés és QND-hasadás (`PROVEN_ALGEBRAIC`):** $K_4/\mathbb{CP}^3$-on ($N_E=0$) $\|\omega_{\mathrm{orth}}\|_F/\|g_{\mathrm{orth}}\|_F=1$ ($2{,}22\times 10^{-16}$); QND defázolás alatt $g_{\phi\phi}\propto\cos^{2N_E}(2\eta)\to 0$ (egy-kvbites óra leáll), míg $g_{\theta\theta}=1/4$ $100\%$-ban megmarad ($4{,}03\times 10^{-9}$).
- **Egyedi $\mathbb{C}$-kiválasztás és mutató-óra (`PROVEN` + `NO-GO`):** $K_4\times K_4$-en $\Delta_{\mathbb{R}}=+36=\dim(\mathfrak{so}(4)^{\otimes 2})$ valós vakfolt ($1{,}23\times 10^{-32}$ lokális átfedés), $\Delta_{\mathbb{C}}=0$, $\Delta_{\mathbb{H}}=-288$. A $12$ osztású ciklikus mutató-óra $100\%$-ban QND-immunis ($\gamma_{\mathrm{dec}}=10^6$, hiba $0{,}0$), teljesíti a Barato–Seifert $\mathrm{TUR}\ge 2$ határt, és $\Gamma_+\leftrightarrow\Gamma_-$ alatt tisztán megfordul.
- **$\mathrm{SM}+3\nu_R$ egyedi $N_{\mathrm{gen}}=3$ horizont-kioltódás:** $48$ Weyl-fermion (`+48`) és $12$ aktív SM mértékbozon (`−48`) $\Lambda_{\mathrm{UV}}$-nél egyedül $N_{\mathrm{gen}}=3$-nál ejti ki egymást ($C=4(1-6\xi_H)>0 \iff \xi_H < 1/6$; töretlen $SO(10)$ $N_V=45$: $-132$ GUT Higgs nélkül; spin-2 kontakt-tagok és dinamikus $\xi_H$ `OPEN`).
