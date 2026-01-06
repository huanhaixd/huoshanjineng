# 火山PC嵌入式封装

**总页数**: 27

---

## 简介

本文档包含火山PC平台的嵌入式封装完整教程和参考。

嵌入式封装是火山平台的高级特性，允许开发者将外部库和组件封装为火山平台可用的模块。

---

## 正文内容



--- 第 1 页 ---

Xu PC RAEI

BEXAR EASA, RZ ADAM ART AM, LSTA NATSU, LAB TANS
HARDER, HTRATA EP RAIRAS, BAT — Te, ERA NITAIA TUE ARMIES, LRRD CIOS EIR
fom —ue,

APA PIE, Fi, GF, GEER, ANEMIA EAS MBDAT.

SAKPAR, BEML, UERMIRABIER, TURE ESSS, BEB SANAR.

BA:
SKU PC SeHRBE(BESE): 748413192
QQ: 980909066
RARE:
FP RGR — AUR. LAPS, HEARS
ORMPP FE - 3¢# SQLite, MYSQL, PostgreSQL =—hAUERE, fe AGREEYE
Ela Ayia): 2024 7 A308
0, AUER

AOBSFADKL PC FAGRH, 32, 64 fASRT, SARK WURAIRE, FoR C++ERRL, ER C++KR STARR,
HE: HATHA MAMAS), PRBS, BCAA, EROS.

1, AUAIR

11 SBR

SAT KUSER, RKESS SARA"

2 sane: x

ert
S PORE [| sanana
5 RBA
SaReer
a Bare
5 Smee
‘FE Lbco sie
SaRMee
SaManier

ze PARE

ey)

uP RAMAANS TARAS

ateeem Bene WES:
Betas project

TREEH: bub Ual=]
obi: D:\code\HuoShan fi IEA [e
MR RISR: PRB Z
WREREM: PRAB

SE: BLL WRK LR PMA LT EMSS,



--- 第 2 页 ---

ode\HuoShan\ fr 2 El /. .
» RAE

™ src

main.v
372A .vprj
B #2 A .vsin
Fae), Sa 7—MRRELES, BAT—* src MAR AAB veri (REAM AGHSS), srcMFRPGS—F main,
Itz IDE FSAM THB

An Re 2m Rae she Rito IAm BOm wahey

PSRATVEBRE BRT SE

D:\code\HuoShan\ #1 3@JR B/. .
= int

» RMA

® debug
= x64
= compiler
™ debuger
= linker
™ project
= WRRA
™ src
main.v
S20 B -vprj
#2 A .vsin

IER ARERTSUT—t_int MAX, RPOAT BAAS, RXBS _inthAPRAdebug\x64, WRF, ees

SPNERaAR,
PBT

Herp 4 P3H, compiler(XLLi)

BABA _int#PMAvelease\x64 A

{UPS REME ESCH? )A debuger (ABH) BRAID, HBS linker Ff project AR PATA


--- 第 3 页 ---

\code\HuoShan\ $32 1 E /
_int
© wiR8
® debug
= x64
= compiler
= debuger
®» linker
= out
= extern

ache .dat

dat
make_params
dafx.obj

® project
nakef ile

@ vol_app
vol_user_app
vol_user_app.
n.cpp
vpkg_w_base.. cpp
@ vpkg_w_startup.cp
vpkg_w_startup.h
iA rc
linker FRAO, SACHS exe RUERCH, project MBA T KLEEB C++iR4t%3, vpkg_main.cpp SRBAANSIAATTELD
+, BAI vpkg_main.cpp BSRAIMASH Wmstek(123) BER MH.

#include
#include

namespace rg_n

{

static void _sOnClassesStaticInit ()
assert ((CVolBaseDataType: :CVolObject::sGetRuntimeClass () != NULL));
assert ((CVolUserApp: :CVolObject: :sGetRuntimeClass () != NULL));
rg_ni::rg_n2 ()
sOnClassesStaticInit ();

_DEBUG_STATMENT (DebugTrace (
return (1);

AFR EX UGB, MALUTAB RSS TAL, (HNMR Cris, iaithHH(123) Sk WREST



--- 第 4 页 ---

_DEBUG_STATMENT SiBitB, 7BEEE, DebugTrace AKU BU ERATE, TEE
win_android_chs_free\plugins\vprj_win\classlib\sys\baseVibs\win_base\cpp\vol_functions.cpp , RUE 4216 4

1.2 BRAS
PAVE PRT PABA

@ z FALSE, 0,0,_T("n"),123

2% Mia wit

FITEF, RBATRECAAMHEP RAM TPT 123, LATO RE.

BO? OMS ATREWKBARARED, KWSSLiSIR RRA SABRE,
DebugTrace WEBAT KWietiTz, heen, B= TSAEITREAD.

AT("n") “PAS n eS — “NR SAIS X APF AR), 123 MU SMAI,
RAUEDS, CHNBALNSSE, SRASTIBNTRST ANTREM, BiH).

1.3 SIASMBASH

PRERAERES S| GNBL, REBMA—F @MEIMBA. ORE IPAS AR
TRE, ATMRE, RST—*S add weX

include

endif

BRUT ASIAB SOE, BAMA CHEMIST, STRC EER SARS , HECHT REATLS|AR add EXT

ee)

aana@

Hae MGA BS

@ T FALSE, 0 "n"), add (123, 123


--- 第 5 页 ---

I(T, MORAG 246, SORRELL REY [ale

1.4 SOCHSIBSCHE, ShABEE

1.4.1 ESCH SIRI

EN BAIRSIAT—“MOAMISSTHE, AS AWAY C++ GESERSLSCEH MY ATUBITH(.cpp)HAk, TSEATIZLS AIHA.
ZE third SOPRA src SUR, MB acpp LH, ALA SRLANMMABM ET

SLICE:

D:\code\HuoShan\ #1 B/. . include’ @ a.h
= int #ifndef __|
» third #define _ |
= include
Bah@ we int add(int a, int
™ src
8 a.cpp @ rf:
= 72M A

i) | @ a.cpp
D:\code\HuoShan\ #10 A /.. src> @ a.cpp
= int #include Ni
= third
™ include int add(int a, in
Qa.h return a + b;
= src }
@ a.cpp
= 7PRA
#21 A .vsln

#inelude "..\inclu

ARENA TAMRAC,

TE e

BRET RES LSMOSIASL ICCB, mA PIROLE, SERURFISI FR FS, ubRTAIIEM AL 246,



--- 第 6 页 ---

1.4.2 SESCCPRLEE
WRIA SF(lib) AME? LEAT ER FSSA SMABEE, third SCASE PRE lib ESE, BA alib, PAM ARS Raa ARSE.

FERNS IRE, 7B.

SEE FS, iC RTTE RY 246,

1.4.3 QB ARHESAR. QNE.ENHESER
BI MARGR PTET ARR, MRSHES, MPT RRL SEAR

SU EFR AAT LAAT BRS DSPBSSCAA BET , RES OUHES ARE HHES AR, BUPA RSS| AISI
AMBARTARER, PERSIST ARENS I, PERE.

GAeEARSe SME TE, REFRAIN zip, MEWTEHNAR

2, RARBABARS

RADA AMARRENSREMERRSOT AT, FORARSRMAOSARATABERAT IIA, CBM, DSH, ERM
BRZEA SHED RRA EM,
2.1 RRA IIE

FRLD—MS SAHA IIE


--- 第 7 页 ---

a CER _ABMO (1,
Up

FLBS), PARVAAHELIEMAISIAIR AAA, WEE 11-14 4740 15-1847, PRT BIMINT @RATBIA MHL ME—AI ZBI BERRY
wT.

PALO TRA SHEMET

CMS AMRADUARASIED, km, BSS.

@<M 1> @<> AANEMRATID PAAR LASER, SAX, BATTIAG, KS RHE AATINIR RE C+ CAPA.
@<i¥t 2> FL.

THRGRITA
$7FF tutoria_int\

SS, PSie? MHABKRRAREDUD SARS? AtAReRRH? BPX MIB BRT BX WER.
=t7r#\debug\x64\projectlvpkg_main.cpp BAHT.

INT rg_qdl::rg_n ()

), rg nl (1, 2)))+ // Hite (ES #0 1, 2))
de, (V+ 20005 wait BND a, 2))

INT CALLBACK rg_qdl::rg_nl (INT rg_n2, INT rg_n3)

return (rg_n2 + rg_n3);

8 4 TA AEABAY rg_n1 (1,2) RIE AMX k, ELS 8-11 7.

SS TEDAMMABLT (1+ 2), UAT RAST K: , MOEBEVK LN FE RRAII: ! a
SMA TES.

BRAD SWAAMRAST , MRRANINRATS SRE, BRS Vat BIN(1.2)) MAGA, LIARS, PASSES
ina.

BLP KWAME AEDS, RTT EA RRAD TAA DT), BRTASRERIREIBAS AAD, 10
FRREAENTARUAFOMLSS, RATES CEE.


--- 第 8 页 ---

2.2 SRA)
RNGSTA RAO TAT TMH Fs izts.

Sehr:
IBATRIRIGM(".\wpkg_main.cpp”, 40): rg_n8 + 0.2 == 0.3

28 FFRBAMT, 1.1422 BASF 3.3? , ARRAN, MA 27 TH 28 TRAIN, AItAiRiRia? imibsei)
SAB T!

PORARAT SALF BA AR RHR SO AE SRS TERA, RARER, ATRIA,
FBP 0.1+ 0.2 BIER 70 0.3 BRIMRNEE, REPRESS.

01 BRA 0.10000000000000001

02 2A 0.20000000000000001

0.1+0.2 &F 0.30000000000000004
1 0.3 ZA 0.29999999999999999,

BB 27 4F ANARIRGIE? BI RARB AAA.
FFF tutorial_int\#A xt77Adebug\x64\projectivpkg_main.cpp +22NMIAie SA Mit BAIT

void CALLBACK rg_qdl::rg_n7 ()

/ WRIRE + 2
/ Bees

= 3)
+ 0.2

/ WARE UNL + 0.2 == 0.3)

= 0.3)

RAK WERNERSAT RINT OC, ABET TRUE, AAR RARAAT OTS AM, A eh 1 BSH, ARERR,
PAA SHR eH EAA.

PIERSON HREEREC LEAN, BRERA A ENT, URERRSM SA, PARTEMAARESREA, we
UGTA PIR RE TAERIE MS,

3, SERB CHa
ASSRATRIB C++#R EEA std::vector 332—*}B CHAVA,
3.1 QRBMAS RRL

PUM SHS, SABES, TUES, |RSS, REAP SERBS, RSME MMS RE
PABA TALE, XUWA PRT EER eee Le.


--- 第 9 页 ---

14GB —MHGMNT CHREMA Rit, ATRIRSSHCBSABAR, FSAPPTUSRSAB.
CBBC AYER RESO SSA, LTRS CRRA, SEM ASS, TUMAST, LURTEDH,
KBRAIRAZIT vector,



--- 第 10 页 ---

15, 1947 @begin @end FeneEA AM CHAS
16, 1847 <include> </include> AAW tS RAMEE RAIS ICe EP

1745 FRAT PABA std::vector<@dt<fA RH 1>> AVAEARRSEME, vector H-BFATS|ASITEATMRAY C++ BNA RAIAS, @dt< PEA
HAM> BSF CMALMA MIHAPMSMMEAD, WRK 28 TAHA @WURMA “BE, EBA std::vector<int>

m_vec;

RAH 1-8 SKU, REMAP, PALA EH, REAR 1.

2147 SRA BS RAR 1, xe

(FERS ORAM TRE RAL, TLR AAD, (BRS PRA 1 AT ITB)

(BASEL SEAS, TSA, KSEE, RVASRCEEENLSS, AREIENTAMAM, ATMS
R, BBR)

2247 @snsthis> iXSRGNSB SERA RIL EIR,

wdzhshshzl rg_nl;

push_back (10) +

at(1)))¢

size()));

EAI UL CIS ATAERLAD C++IRS, 98147 rg_n1 XID K UP RRANRE RRR SIS, SS 2 TFAAILAGEI @snsthis> MST
rg_nt,

2847 WA T—MUREM, AAS AMARA ARE, AS AMOMRLMAR, MIHAARA HAMAS.
Bie S eT —MGRNSeS, UR FAA L A CF ORM T, TRBRSRRA.
EMERY, BOX T US CAMA EST MSU BH), RBRCUERRA. std:vector(13Z), HATER

4, IaDieete

KUSAMREUH ES RRARAT , RBA ATA RASS, ATTEAITRIAR std::thread 3)32—“MET(S RM aoe.


--- 第 11 页 ---

4.1 @WRaz Bit
Ea -MRRES TENS, LNRRERBIOIASMIE, (SF

BS BS Rte 7

v

tS
22 Ba) ABH KBAR
ITEM: KSB
1145 CURA MILs SLA" AROMAS, BCHEM, VSG, ABEL.
12-1549 C++89 lambda i51k, 000 B-NRASFOBN, ORABSRN, ERSHHHESYREAMMES, ARLE
Bae.
4.2 @rir ke mit
PSMA ZBAIREDRIMED, BESTT A? STS? RTI CAR Mt.

ES
BA2 Bah PSA (BSR, 123, 1.1)

ATM: BSA, 123, 1.1


--- 第 12 页 ---

CATR TWiRILRESSHSN, ALM CLAY ME, LBRNLATAAL. BS OA RRIHMATARPB 00.275
GER 21 THISPST—* '8', ltt C++ lambda RIATBA, BAIIABSAIS I, LEAR SAIEEA SEIN, AUER
SBSERASSE aS DHA)

4.3 tia

—NIEMIR? ATARARANTAE, RAEPXU QAR SSH HSH, AAS E, DEAR NA.
£€ tutorial\tutorial\include BSRP €—* thread.h Lye, FHM FAS

gs&&... args)

d<P>(£), std::forward<Args>(args)...)+

f, const int64_t value) {

vard<F>(£));

) // namespace tutorial

PARTEX UPAR RI

AF
B#2 JE (ABI)
892 Jah (BSA, 123, 1.1)

ina:
iiaAMT—+ ORME Bt, ASHEN SUTAM, WRSTH MEERA. WRAP RES SIMBA EADIE?
BREA MIN, BEBPPIE—-R. RMI: RAGE, (BABEO KLUGE RATS Ae HEY TS Fas ES AES, (EAB
BRAERS.

FERAL: 00.3 /)\75, BAB aah IBA RTTIE.

4.4 BRB Ba
S5Se REFN EERE O EME, SE TSREANTIE


--- 第 13 页 ---

FLSA VIeABA), ER 28 17, WRITER MUSSEOM, RMS Maat: SRMEa
RAll

de\mutex_helper .hpp

: mmutex(mutex) ( //6RF31/ GOMGETRIEED) , ¢IGEREK() : m_mutex (mutex)
mutex

ne

WADA, AF m

a() lock

~VolMutexLockGuard ()

m_mutex.data() -unlock

‘Té mmutex; // BAMAUSCOISIA, SSSR MSC PIAS Et



--- 第 14 页 ---

FEARS EMOt SER BRB Sae BOF), RISE, ARES SICERERERMT ! BESS, 20
3 SRR Awe SEMRARMRG SAS, PAAR RSS SAR, afi

DERBHERHRETEAIM, PTFE PICAHT

5, Maas

SANGRE RH ANA, KUM MENA) REACSHEMMECSSRERNEREM, ALS, MET
FVORSUNE. TUL Cpa BANERTS, BBL fmtlib, ASLAIA mtd 3f38— rates.

HRULZ IANS th Be — tes SHES (CAB RHEIN EE!

5.1 SIN BERRITT

BAAR, SUPE, RIEARUHIR, BeaATL RRA PURO SE EDee

FE Seat

RRBSAET, BIAS T—MAaRE, AF imtlib SST ET, ATL PREMAUI, SAAR.

BamiAUT


--- 第 15 页 ---

R-BEEREe, HPXKUAMNAR eR, MSAK, BARTS esta RED.

BONE

| ASE |

RFE SITTAIE RAS, SCIMENIFTAY, notepad++ARAM FT

Hello, world

5.2 BRIBE

Fas RAI ZENER
sha

iBTBR:
RASHa aR


--- 第 16 页 ---

RS biz) ae

Qo eo 37 BHT

Qi #e 46

Qe fee 8
)

O3 #3 49 ern
a8: x

2, SS = 8 iurel 0

ARS = 0,185 = RHO, SH = 37
*

RRS! a

fisttt

MiasteA
LA
Nia #2 "
@o Heo 37 nl
Or He “
tee 8
ao « Behisticintn

i * "4 BEL

RS = 0,18 = RO, SH = 37
BS-2 Ge - a2 8-8
teiRS1 0

“

ca

jemiaste
pa]
eS te ae ]
Qo zo 37 em
QO. REI 6
Oz wee 8
S a4 = Crrrastiesaa
ae. x

FES = 0,582 = HO, SS = 37
BS = 1,582 = H1, SB = 45
RS = 2,188 =H? SH 8

AST -REH, TUSREtkT HS] 0-3 BHABHA


--- 第 17 页 ---

Qo EO EL $F
a #1 46
Gz hee 8
@s Bes 49
: x
- es coy

PRS = 1 58S = 1, SH = 48

fasttt

5.3 SCHAT
SHB: APUASAAEA, ALTE —FIB SSUES tuple, ZA/SIRIA fmt::format txt(LetteicR MARIS.

ATTENDS HRL-EN CHHIR, RARE.


--- 第 18 页 ---

1) SCR ABP HBBDTT, IBIEI—AT ATS PUERKAY tuple

template <st

size_t... I>
auto line_to_tuple(CVolStrings fmtstr, CVWnd_ListView* list_pwnd, INT index, std::index_sequence<I...>) {
return std::make_tuple(fmtstr.GetText(), CVolString(list_pwnd->GetCaption (index, I, CVolMem()))..

he

J) Fak AL IBF

1) REE R a BRE

J) WEBB tax RBBB

// BB select_only BA (Qhisttilehwl

1 BB start_index $BSUCFHARS|

// BB end_index 1UCERAS|

// BY delim FRONTERA DBE, BRIA" \r\n"

template<typename T, size_t Idx>
static CVolString format_list(CVolString fmtstr, T& obj, bool select_only, INT start_index, INT end_index,
CVolstring delim) {

|) BBR

static_assert (std::is_base_of<IListViewEventListener, T>: :value, "WebBenGeShiHua_ChaoLie CuoWu!");

CVWnd_ListView* list_pwnd = (CVWnd_ListView*) obj.GetMfcWndPtrWithvalidHWnd ();

// PNAS HE FRMRSVNF 0 UGGS,
if (list_pwnd == NULL || start_index < 0) (
return Cvolstring();

// item_count MAB UREM, (item_count NFSF -1) RH GGRASATWUMEM WHF end_index 9 MPABO
int item_count = list_pwnd->GetItemCount ();
if (end_index <= -1 || end_index > item_count) {
end_index = item_count;
}
// BRBGEM, HG sca::apply ies
auto func_format = [] (const autos... args) {
return fmt::format (args...);

std::wstring result;

std::wstring wdelim(delim.GetText (), delim.GetLength());
for (; start_index < end_index; start_index++) {

// BEMUEUGEPR, BAR PAAM B PARMA TR.

if (true == select_only && !((INT) (1ist_pwnd->SendMessage (LVM_GETITEMSTATE, (WPARAM) start_index,

(LPARAM) LVIS_STATEIMAGEMASK) >> 12) - 1)) {

continue;

// AOA ASAB RS tuple
auto line = line_to_tuple(fmtstr, list_pwnd, start_index, std::make_index_sequence<Idx>());
1) Hehe
result = result + std::apply(func_format, line) + wdelim;
)
return CVolString(result.data(), result.size());
)

RBBLAAS, SCHR StRE) 3017, BOMED, (QOVUUT, (ARRAS, TRS T

M format_list Siz FAME, 17 - 29 TILER RAS RAS |, FRSA T , behest.

31-3345, LAF fmt::format 2—MeiTK, BREA std::apply MBS HAANAD, MRIS EALN, REREBT
ASH. EAI? TTA TSSRAERSMAIRER, i: BAK = lambda, RSABA DIE


--- 第 19 页 ---

auto func_format = [] (const autos... args) {

return fmt::format (args...)7

35, 3647, TEXUARSEMA] wstring AMAIA, BR.

met
for (; start_index < end_index; start_index++) {
// BERR, RAQUGEPRA B PBA PRI.
if (true == select_only && !((INT) (list_pwnd->SendMessage (LVM_GETITEMSTATE, (WPARAM)start_index,
(LPARAM) LVIS_STATEIMAGEMASK) >> 12) - 1)) {

// —4ROPRPISTABARAY tuple
auto line = line_to_tuple(fmtstr, list_pwnd, start_index, std::make_index_sequence<Idx>());
1) Heke
result = result + std::apply(func_format, line) + wdelim;
)

ERS 1 1FE—7 for 1H, ASMA HMICSRE, MANUB RAEN AMET,
3 1T AURA EP, MORPH RTS MARS, ARMAITSE 4 478) continue, HAE TRIGA.
(&& BSS, MRNA false SIZBNREl false, ATSB, AMSAT && IaRANIES)

Bit
3 7 {7 JARI line_to_tuple BX, SSXUOF

template <std::size_t... I>
auto line_to_tuple(cvolstrings fmtstr, CVWnd_ListView* list_pwnd, INT index, std::index_sequence<I...>) {

return std: :make_tuple(fmtstr.GetText(), CVolString(list_pwnd->GetCaption (index, I, CVolMem()))...)#
M

DTSRARIKTAS, BRST PH "RS = 0, HS = 0, FR = 0"

ATSREBAANRENVIR, KAUNSVUAAAS

BIVSMSAMAS |, thHAVEAABAY start_index, AUR!

BOTS, BO Bl WW e(format_list HSM) ARRAN, HM: TWMOS, PFN 0,1,2,3,.4

SE — PASSA, (BRAD 3, WAAR line_to_tuple

line_to_tuple("FS =(}, & =(, FH = 0", MBARUFE, RUF, 0,1,2 ); // 0,1,2 = std::make_index_sequence<3>, 3 By

HEA line_to_tuple BAVARIA HAGE O—? tuple, SATE

std::make_tuple("FFS = 0}, RES = 0, SFiS = 0", RBRFUZAE Dene GRIMES |, 0)...);

Rp... SRASWA RENSRORE 0.1.2), RABE

FERS =), PER = 0, SHR =)", RADDA Ata FES|,0), RAMU HEARS |, 1), RARSU ACHE HENAN
ieee tuple, = RRRGAT, FAB std::apply % tuple -4/F 31-3347 func_format BEBM WSS, SAGE

return format ("RS = (), MR = (), SR = ()", BRIE. DN RRS, 0), MRE in VRS, 1), BRI
BAe. BU (RIMES |, 2) ) +

SMT? LERMARAP FSM, RIAA ASMREM T eS! TLR MMT Tmt
CHAI, CULT AIS TERE TS ABRUIRE, RR MT C++ eeEAG II!

6. SHES

6.1 OMS
XU PARSE RIAENRE, KE, SRE, TOOK


--- 第 20 页 ---

iti

HEAREMLA 0

FERTBLE
TARE HS

SREB LA ((

TIALS ARF


--- 第 21 页 ---

class rg_n4 : public CVolobject
(
DECLARE_EMPTY VOL CLASS (rg_n, rg_n4)

public:
static void CALLBACK rg_n5 ();
static void CALLBACK func_name (); // FixiRERWS
static void CALLBACK rg_n6 (INT rg_n7);
static void CALLBACK rgn8 (INT acc); // SSURERWS
inline_rgn4 () ( }
inline_ void _VolObjectInitMembers () ( }

IBAASME

void CALLBACK rg_n4::rg_n5 () {
_DEBUG_STATMENT (DebugTrace (FALSE, 0, 0, _T ("S"), _T ("FixARBMWH"))):
)
void CALLBACK rg_n4::func_name () {
_DEBUG_STATMENT (DebugTrace (FALSE, 0, 0, _T ("S"), _T ("J7ixiRMMHE")));
)
void CALLBACK rg_n4::rg_n6 (INT rg_n7)

rg_n7 =
rg_n? = 22;
rg_n7 += 32;

_DEBUG_STATMENT (DebugTrace (FALSE, 0, 0, T ("n"), rg_n7))i
)
void CALLBACK rg_n4::rg_n8 (INT acc) {

acc = 1;

acc += 32;
_DEBUG_STATMENT (DebugTrace (FALSE, 0, 0, _T ("n"), acc))?
)

FLBAERSNEMENENA BSE OU RHE, RARALLHIRE, (RAT IATHER OMUE BH, RABI
ES 2.1 POSIT, RATTAPRABRANSMAN.

MUAH AH ARE? KEMA—MEBAR, (MEER C++, RAI, RPV SMATRER, MRTBRUWE REE

Skat SRRRERLA RAH, SREN @<SRE>, HORARS, AREA CMH EUSRAMAEIEAS
BT. (BE: 7.1 PAB OME TERT C++ ATI K LE)

6.2 @alBx

ie
#pragma once
class Test {
public:

CVolString hello() {
return CVolString(L"hello");

ARSE ARGAFARASER, PRVOULA SEMEN TIE, A TSEINA BHA,

Bt, BATES UHRA, ILRWR CVolObject(iXEX WATE, Aram RAttAs)


--- 第 22 页 ---

class Test : public Cvolobject ( // BMRHB: class Test (

RBEXUPSAL HS, Suk HS

vpkg_main.cpp
n2 ()

10() == _T ( »

return (1);

ul
2047ENT—*T Test BANTER, 21 (TIEWIAAAAT hello() Bex.

BASISAIRE, RAE MBSA, PLEX LENS Sze hoa ARLZANGATEX WR 13 FF, SONGS
BRWSTEMERAS, MATLAEAA helloZSSLHISEM) BY ZESLHISE hello!) AAIALHTIER, KWUSTHTAE, RARE PAA
$8 2147 rg_n3.hello() #2st.

MERA RAIN ER BR ABIES, LLM CVolObject SRATLLERSAIEX LUPE, ELSNABSAS! Aprk0 tS:

void func(Testé t) {

DREARARRNTASS, RNAS, HRP SMM func(@skscfil>.m_ox), HU@RNISAURSR, BIBER
MIG, ABE func(@ssschil>) Bay, SNA R esl, RAIL SAAS te T HR.


--- 第 23 页 ---

7, PRATCHETT

7A @fdt<2eB>
BDSM: “Ora

"@dt' RAVE RT Eee ESE RR,

FRMA—HTK, FE CHALKY .v SCARE, RE—TSCG

namespace 1
namespace c
fe"

list

eu

ESL EPEAHAES, SAX WAS 1) @ME “FuncName", XH list2strar, AateRAT ATER Hs BY
Bites, EC+ERS eM » ESI 3 PA —MURSMS REA XU (MME ControleExtra
SF rg_n::ControlExtra), HFMSBMRBE SASSI BWA HAI, PREM ControlExtra:: HAIAT.

(HE 1: CHiMPS SAN KLUNGSSR—MRB)

(@iE 2: tBBTLAGKAB <@sn<current_package_def>::@sn<current_class_def>> #4%& @fdt<2kR>)

7.2 @pvpn<#sBNA>
DADRA: COTE SWMARGR AERA, ELAR TRSORENE, MAT:


--- 第 24 页 ---

func_a(1);

func_b(2);

AUR ERS, PAUL BAIMELL AEE, ERASED KPA SWARM, LOMI—NRARIMTISHIAE,
EMSRS ASAE XUPS HHS EN, PRTIAS AZM Person
BILASEFB Person @pvpn<tninf}> = CreatePerson(); BEAK IRA REIS RIAA T

00, Ali

00.1 SBBDSLITE

RASA MATER SRA KR RAMA, ATLL MORSSLICH, RASHEED SAE LICR.
ERARARASHRPMR—* include SHE, RHR tutorialtutorial, RA—* include SHIH tools. SLICE,
IBL2 981299 tutorial\tutorialinclude\tools.h

Ase:

#pragma once

define MYDEBUG(format, ...) DebugTrace (FALS!

__VA_ARGS_)

PRBS A BUS FAR SLE

CUBA ASPENS RBL EAS SISA A, GST UBS BAe Bl)
SDMA SCPE.

FMETEXWPS—A) @ MYDEBUG("nn",123,321); ististiB!

eb YAR SE

00.2 MABARMA
KWAN SHE, BD MAA (str, str2 + str3, str4), BAS

BAST, RERAMRTANE, BiITRSTSSMAOMALA,


--- 第 25 页 ---

i82—} tutorial\tutorial\include\string.h 3c, WADIA R AB

) // namespace tutorial

DLE SAAS C++17, S06 C++11 HENS ARTA.
KWON HGS

ecm:
00.3 SfSRaa res
€ thread.h PRIMO AS

// CORARBSTIE

t value) {

>(£), std::forward<T>(obj));

F>(£), std: :forwardcT:

obj), value);

KU DOF


--- 第 26 页 ---

EMA FRM —T MAS BHAA
Wat
B92 Jamh AMBSTTK RBA _ALRSEM 100, AE
// ERG (RRS) // SAREE TRIS, SSE BaSeR
REA 0
WE (LASER)

ERBESTEMS OLA AY ME, MRA SNA ALCACHMPA ITA, MARAIS LAME A SERED HH PAIS
ik, RES EBSA" , RSAC WMEARSREITE, BRIAR TARAS MS "AEDT

00.4 ABARFGRM CT & (2022-12-12 BSCR)
2022-12-12 FERSKRAFILMERA @pvpn SATA, HERTS 7.2 5
PMDXLMMSTAHY co

#deti

cT(id) id

KUPRR: EATS

ERK CPP fa

std::string str

2023-2-5 Bat, KU PCR THMaASGS, MAT SAE, EF @pvpt BA @pvpn TMGRAFAR CASE) SOAR
BEA, RARATUSSRA' FP AR", Be Rew HSM

@pvpt< See An> (5 | FRASER STAR SES PN NZ ONE ECAR TESS (ARPS |S)
@pvpn<S& E> 5" @pvpt a RELRAMEANF ALAN SMALE.


--- 第 27 页 ---

RR

ERAN, TAT, hia nee, BONNSST, RHEIN, RAGA SWEE
a.

He ER Sett

TARNSH—Al

PNR: My

S PES

95188-6
