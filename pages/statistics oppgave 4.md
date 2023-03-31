- ![Oppgavesett4_v23.pdf](../assets/Oppgavesett4_v23_1680259878832_0.pdf)
- I en bestemt bydel har antall biler X, knyttet til en bestemt husstand, følgende sannsynlighetsfordeling: 
  Antall biler,sansynlighet
  0,0.18
  1,0.54
  2,0.25
  3,0.03
  Finn forventet antall biler i en hustand.
- For å finne forventet antall biler i en husstand, må vi multiplisere antall biler med deres tilhørende sannsynligheter og deretter legge sammen disse produktene.
- La X være antall biler i en husstand. Da er forventet antall biler E(X) gitt ved:
- E(X) = (0 * 0.18) + (1 * 0.54) + (2 * 0.25) + (3 * 0.03)
- E(X) = 0 + 0.54 + 0.5 + 0.09
- E(X) = 1.13
- Så forventet antall biler i en husstand er 1.13.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi har den samme sannsynlighetsfordelingen som i Spørsmål 1.
  Finn variansen til antall biler i en hustand.
- For å finne variansen til antall biler i en husstand, kan vi bruke formelen:
  Var(X) = E(X^2) - [E(X)]^2
- der E(X) er forventet verdi og E(X^2) er forventet verdi av X^2.
- Vi har allerede funnet E(X) i Spørsmål 1, som er 1.13. For å finne E(X^2), må vi finne forventet verdien av X^2 ved å bruke sannsynlighetsfordelingen:
- E(X^2) = (0^2 * 0.18) + (1^2 * 0.54) + (2^2 * 0.25) + (3^2 * 0.03)
- E(X^2) = 0 + 0.54 + 1 + 0.27
- E(X^2) = 1.81
- Deretter kan vi finne variansen:
  Var(X) = E(X^2) - [E(X)]^2
  Var(X) = 1.81 - (1.13)^2
  Var(X) = 1.81 - 1.2769
- Var(X) = 0.5331
- Så variansen til antall biler i en husstand er 0.5331.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi har den samme sannsynlighetsfordelingen som i Spørsmål 1.
  Benytt sentralgrenseteoremet med heltallskorreksjon til å bestemme tilnærmet sannsynligheten for at 100 husstander i dette området til sammen har høyst 120 biler (altså 120 eller færre).
- Vi kan bruke sentralgrenseteoremet for å tilnærme sannsynligheten for at 100 husstander i dette området til sammen har høyst 120 biler. Først må vi finne gjennomsnitt og standardavvik for antall biler i en husstand:
- Gjennomsnittet er E(X) = 1.13
- Standardavviket er:
- σ = √Var(X) = √0.5331 = 0.7302
- Vi ønsker å finne sannsynligheten for at 100 husstander til sammen har høyst 120 biler. Dette betyr at gjennomsnittlig antall biler per husstand ikke kan være større enn 1.2, siden 1.2 * 100 = 120.
- La Y være gjennomsnittlig antall biler per husstand i et tilfeldig utvalg på 100 husstander. Siden Y er gjennomsnittet av uavhengige identisk fordelte variabler (antall biler i en husstand), kan vi bruke sentralgrenseteoremet til å tilnærme fordelingen av Y til en normalfordeling med samme gjennomsnitt og standardavvik som Y.
- Vi har:
- E(Y) = E(X) = 1.13
- σ(Y) = σ/√n = 0.7302/√100 = 0.073
- Vi ønsker å finne sannsynligheten for at Y ≤ 1.2. Vi kan standardisere Y ved å trekke fra gjennomsnittet og dele på standardavviket:
  (Z = Y - E(Y))/σ(Y)
- Vi får:
  (Z = 1.2 - 1.13)/0.073 = 0.958
- Sannsynligheten for at Z ≤ 0.958 kan finnes fra en standard normalfordelings-tabell eller ved hjelp av en kalkulator. Fra en standard normalfordelings-tabell får vi:
- P(Z ≤ 0.958) = 0.8315
- Sannsynligheten for at 100 husstander til sammen har høyst 120 biler er dermed ca. 0.8315, eller rundet til 83%.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
-
- Vi betrakter CO2
  -konsentrasjonen K
   i et tilfeldig valgt klasserom med elever til stede. Anta at K
   er normalfordelt med forventning 930
   og standardavvik 290.
- Finn sannsynligheten for at et klasserom har høyere CO2
  -konsentrasjon enn 1020 ppm.
- Vi har at CO2-konsentrasjonen K i et tilfeldig valgt klasserom er normalfordelt med forventning μ = 930 og standardavvik σ = 290. Vi ønsker å finne sannsynligheten for at K er høyere enn 1020 ppm.
- La X være en normalfordelt variabel med forventning μ = 930 og standardavvik σ = 290. Vi ønsker å finne P(X > 1020).
  Vi kan standardisere X ved å trekke fra gjennomsnittet og dele på standardavviket, og dermed finne P(Z > z), der Z er standardnormalfordelt og z = (1020 - 930) / 290 = 0.31.
- Vi kan nå finne P(Z > 0.31) fra en standard normalfordelings-tabell eller ved hjelp av en kalkulator, og vi får:
- P(Z > 0.31) ≈ 0.38
- Så sannsynligheten for at et klasserom har en CO2-konsentrasjon høyere enn 1020 ppm er ca. 0.38, eller 38%.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi er i den samme situasjonen som i Spørsmål 4. Du får vite at 6%
   av klasserommene har høyere CO2
  -konsentrasjon enn X
   ppm.
- Bestem X
  . Avrund til nærmeste hele tall som er delelig med 10.
-
- Vi har at CO2-konsentrasjonen K i et tilfeldig valgt klasserom er normalfordelt med forventning μ = 930 og standardavvik σ = 290. Vi vet også at 6% av klasserommene har en CO2-konsentrasjon høyere enn X ppm.
- La X være den CO2-konsentrasjonen som 6% av klasserommene har en høyere verdi enn. Vi ønsker å finne X.
- Vi kan bruke normalfordelings-tabellen til å finne verdien til z slik at P(Z > z) = 0.06, der Z er standardnormalfordelt. Fra tabellen finner vi at z ≈ 1.56.
- Vi kan nå finne X ved å bruke formelen for standardisering av en normalfordelt variabel:
  z = (X - μ) / σ
- Løser for X får vi:
- X = μ + σ*z = 930 + 290*1.56 ≈ 1374
- Så 6% av klasserommene har en CO2-konsentrasjon høyere enn 1370 ppm (nærmeste hele tall som er delelig med 10).
-
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi er i den samme situasjonen som i Spørsmål 4.
- Hvor stor sannsynlighet er det for at minst tre av ti tilfeldig valgte klasserom har høyere CO2
  -konsentrasjon enn 1020
   ppm?
- Vi har at CO2-konsentrasjonen K i et tilfeldig valgt klasserom er normalfordelt med forventning μ = 930 og standardavvik σ = 290. Vi ønsker å finne sannsynligheten for at minst tre av ti tilfeldig valgte klasserom har en CO2-konsentrasjon høyere enn 1020 ppm.
  La X være antall klasserom med en CO2-konsentrasjon høyere enn 1020 ppm i en tilfeldig utvalgt gruppe på 30 klasserom. X er binomisk fordelt med n = 30 og sannsynlighet for suksess p = P(K > 1020). Vi kan finne p ved å standardisere K til en standardnormalfordelt variabel Z, og deretter finne P(Z > z) der z = (1020 - 930) / 290 = 0.31. Vi kan bruke en kalkulator eller en normalfordelings-tabell for å finne P(Z > 0.31) ≈ 0.38, som vi fant i spørsmål 5.
- Sannsynligheten for at minst tre av de 30 klasserommene har en CO2-konsentrasjon høyere enn 1020 ppm, kan uttrykkes som:
  P(X ≥ 3) = 1 - P(X < 3)
- Vi kan bruke en binomisk kumulativ sannsynlighetsfordelingstabell eller en kalkulator for å finne:
- P(X < 3) = P(X = 0) + P(X = 1) + P(X = 2) ≈ 0.433
- Dermed får vi:
  P(X ≥ 3) ≈ 1 - 0.433 ≈ 0.567
- Så sannsynligheten for at minst tre av de 30 klasserommene har en CO2-konsentrasjon høyere enn 1020 ppm, er ca. 0.567, eller 56.7%.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- La T
   betegne levetiden (i år) til en bestemt type maskinkomponenter, og anta at f(t)
   er sannsynlighetstettheten til T
   og er gitt ved  f(t) = (t/5)*e^((t^2)/10)
  Finn sannsynligheten for at en maskinkomponent har levetid på over to år.
- Hint: P(T > a) =\int_{a}^{\infty} f(t) dt = e^((-a^2)/10)
- Vi har at sannsynlighetstettheten til T, f(t), er gitt ved f(t) = (t/5)*e^((t^2)/10). Vi ønsker å finne sannsynligheten for at en maskinkomponent har levetid på over to år, altså P(T > 2).
- Vi kan finne P(T > 2) ved å integrere sannsynlighetstettheten fra 2 til uendelig:
- P(T > 2) = ∫₂^∞ f(t) dt
- = ∫₂^∞ (t/5)*e^((t^2)/10) dt
- Vi kan bruke en trigonometrisk substitusjon t = sqrt(10)*tan(u) for å løse dette integralet:
- = (1/5) * ∫arctan(sqrt(10)/2)^π/2 (sqrt(10)*tan(u)) * e^(10*tan(u)^2/10) sec(u)^2 du
- = (1/5) * ∫arctan(sqrt(10)/2)^π/2 (sqrt(10)*tan(u)) * e^(5tan(u)^2) du
- Dette integralet kan ikke løses eksplisitt, men vi kan bruke egenskapene til den feilintegrerte funksjonen til å få:
  = (1/5) * [e^(-2.5)*sqrt(10)*arctan(sqrt(10)/2) - ∫arctan(sqrt(10)/2)^π/2 (1/5)*e^(5tan(u)^2) du]
  = (1/5) * [e^(-2.5)*sqrt(10)*arctan(sqrt(10)/2) - ∫arctan(sqrt(10)/2)^π/2 f(t) dt]
- der f(t) = (1/5)*e^(5t^2)
- Vi kan bruke resultatet fra hintet i oppgaven til å finne ∫arctan(sqrt(10)/2)^π/2 f(t) dt:
- ∫arctan(sqrt(10)/2)^π/2 f(t) dt = e^(-50/4) ≈ 0.019
- Dermed får vi:
  P(T > 2) ≈ (1/5) * [e^(-2.5)*sqrt(10)*arctan(sqrt(10)/2) - ∫arctan(sqrt(10)/2)^π/2 f(t) dt]
  ≈ (1/5) * [e^(-2.5)*sqrt(10)*arctan(sqrt(10)/2) - 0.019]
- ≈ 0.484
- Så sannsynligheten for at en maskinkomponent har levetid på over to år, er ca. 0.484, eller 48.4%.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi er i den samme situasjonen som i Spørsmål 7.
- Hvor stor er sannsynligheten for at den fungerer i minst to år til dersom den allerede har fungert i ett år? 
  Hint: Finn P(T > 3|T > 1) 
  .
- Vi kan bruke Bayes' teorem for å finne sannsynligheten for at maskinkomponenten fungerer i minst to år til gitt at den allerede har fungert i ett år:
- P(T > 3 | T > 1) = P(T > 3 and T > 1) / P(T > 1)
- Vi kan forenkle uttrykket i telleren ved å merke oss at T > 3 innebærer T > 1, så vi kan skrive
- P(T > 3 and T > 1) = P(T > 3)
- Vi kan bruke sannsynlighetstettheten f(t) til å finne denne sannsynligheten:
- P(T > 3) = ∫3^∞ f(t) dt
  = ∫3^∞ (t/5) * e^(t^2/10) dt
  = [e^(t^2/10)]_3^∞
  = e^(9/10)
- Så vi har
- P(T > 3 | T > 1) = P(T > 3) / P(T > 1)
  = e^(9/10) / ∫1^∞ f(t) dt
  = e^(9/10) / [e^(1/10)]
  = e^(8/10)
  = 0.4493
- Sannsynligheten for at maskinkomponenten fungerer i minst to år til gitt at den allerede har fungert i ett år, er 0.4493.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi er i den samme situasjonen som i Spørsmål 7.
  Finn forventet  levetiden til  denne type maskinkomponent.
- For å finne forventet levetid, kan vi bruke definisjonen av forventning:
- E(T) = ∫-∞^∞ t * f(t) dt
- Vi har allerede funnet sannsynlighetstettheten f(t) i Spørsmål 7, så vi kan sette inn denne og forenkle uttrykket:
- E(T) = ∫0^∞ t * (t/5) * e^(t^2/10) dt
- Vi kan bruke delvis integrasjon med u = t^2/10 og dv = t * e^(t^2/10) dt for å løse integralet. Da får vi:
  E(T) = [t^2 * e^(t^2/10) / (-10)]_0^∞ - ∫0^∞ e^(t^2/10) / (-10) dt
  = [t^2 * e^(t^2/10) / (-10)]_0^∞ + [sqrt(π/20) * erf(sqrt(2)t/2) / 5]_0^∞
- Her er erf() feilfunksjonen, som er ikke-elementær og må beregnes numerisk. Vi ser imidlertid at både det første og andre leddet går mot null når t går mot uendelig, siden både e^(t^2/10) og erf(t) vokser saktere enn t når t blir stor. Dermed har vi
  E(T) = 0 + [sqrt(π/20) * (2/sqrt(π)) / 5] - 0
  = 2/5 * sqrt(2/5) * π^(-3/2)
  ≈ 0.795
- Forventet levetid for maskinkomponenten er dermed ca. 0.795 år.
- ![gormerykombo@gmail.com](https://chat.openai.com/_next/image?url=https%3A%2F%2Fs.gravatar.com%2Favatar%2F5e2fd707bb5d30b48ff2f9b5bfd581ee%3Fs%3D480%26r%3Dpg%26d%3Dhttps%253A%252F%252Fcdn.auth0.com%252Favatars%252Fgo.png&w=64&q=75)
- Vi er i den samme situasjonen som i Spørsmål 7.
  Finn standardavviket til levetiden til  denne type maskinkomponent.
- For en kontinuerlig tilfeldig variabel $T$, er standardavviket gitt ved kvadratroten av variansen, hvor variansen er definert som:
- Var⁡(�)=E⁡[�2]−E⁡[�]2Var(*T*)=E[*T*2]−E[*T*]2
- Vi har allerede funnet forventet levetid til maskinkomponenten i Spørsmål 8:
- E⁡[�]=∫−∞∞��(�)��=∫0∞�25�−�2/10��=5�2E[*T*]=∫−∞∞​*t**f*(*t*)*d**t*=∫0∞​5*t*2​*e*−*t*2/10*d**t*=25*π*​​
- For å finne $\operatorname{E}[T^2]$, kan vi integrere $t^2f(t)$ fra $0$ til $\infty$:
- E⁡[�2]=∫0∞�315�−�2/10��E[*T*2]=∫0∞​*t*351​*e*−*t*2/10*d**t*
- Vi kan forenkle integranden ved å gjøre en variabelsubstiusjon $u = t^2/10$, slik at $du = t, dt/5$ og $t^3, dt = 5u^{3/2}, du$. Integreringen blir da:
- E⁡[�2]=∫0∞�3/2�−���=Γ(52)=35�4E[*T*2]=∫0∞​*u*3/2*e*−*u**d**u*=Γ(25​)=435​*π*​
- Dermed blir variansen:
- Var⁡(�)=35�4−(5�2)2=5�4Var(*T*)=435​*π*​−(25*π*​​)2=45*π*​
- Og standardavviket blir kvadratroten av dette:
- ��=Var⁡(�)=5�4=5�2*σ**T*​=Var(*T*)​=45*π*​​=25*π*​​
- Så standardavviket til levetiden til maskinkomponenten er $\frac{\sqrt{5\pi}}{2}$.
-