# Notkunartilvik

## Helstu notkunartilvik

Eftirfarandi notkunartilvik voru greind út frá niðurstöðum kröfusöfnunar fyrir Kerfisskrá. Þau byggja á notendakröfum UR-1 til UR-6 og tengjast viðskiptamarkmiðum BO-1 og BO-2.

| ID | Heiti | Aðalgerandi | Markmið |
|---|---|---|---|
| UC-1 | Leita að starfsmanni | Notandi | Finna starfsmann með því að slá inn starfsmannanúmer. |
| UC-2 | Skoða starfsmenn í stafrófsröð | Notandi | Birta lista yfir starfsmenn í stafrófsröð. |
| UC-3 | Skoða stigskiptingu fyrirtækisins | Notandi | Skoða starfsmenn eftir skipulagi og stigskiptingu fyrirtækisins. |
| UC-4 | Sía starfsmenn | Notandi | Finna starfsmenn eftir sviði eða starfssvæði. |
| UC-5 | Skoða starfsupplýsingar | Notandi | Skoða starfsheiti, starfstitil, deild, vinnusíma og netfang starfsmanns. |
| UC-6 | Skoða persónuupplýsingar | Starfsmaður mannauðsdeildar | Skoða kennitölu og persónulegt símanúmer starfsmanns með viðeigandi aðgangsheimild. |

## Ítarleg lýsing á einu notkunartilviki

**ID:** UC-6  
**Heiti:** Skoða persónuupplýsingar starfsmanns  
**Aðalgerandi:** Starfsmaður mannauðsdeildar  
**Aukagerendur:** Engir skilgreindir.

## Forsendur
- Starfsmaður mannauðsdeildar hefur aðgang að Kerfisskrá.
- Starfsmaðurinn hefur heimild til að skoða persónuupplýsingar.
- Upplýsingar um starfsmanninn eru skráðar í kerfið.

## Eftirskilyrði
- Starfsmaður mannauðsdeildar hefur fengið aðgang að þeim persónuupplýsingum sem hann hefur heimild til að skoða.
- Upplýsingunum hefur ekki verið breytt.

## Aðalflæði
1. Starfsmaður mannauðsdeildar opnar Kerfisskrá í vefviðmóti.
2. Starfsmaðurinn leitar að starfsmanni með starfsmannanúmeri.
3. Kerfið finnur starfsmanninn og birtir starfsupplýsingar hans.
4. Starfsmaður mannauðsdeildar velur að skoða persónuupplýsingar.
5. Kerfið athugar hvort notandinn hafi viðeigandi aðgangsheimild.
6. Kerfið birtir kennitölu og persónulegt símanúmer starfsmanns.
7. Starfsmaður mannauðsdeildar skoðar upplýsingarnar.

## Valflæði
- **A1:** Starfsmaður mannauðsdeildar finnur starfsmann með því að skoða starfsmannalista í stafrófsröð í stað þess að leita eftir starfsmannanúmeri.
- **A2:** Starfsmaður mannauðsdeildar finnur starfsmann með því að sía eftir sviði eða starfssvæði.

## Undantekningar
- **E1:** Ef starfsmaður finnst ekki birtir kerfið skilaboð um að enginn starfsmaður hafi fundist.
- **E2:** Ef notandinn hefur ekki heimild til að skoða persónuupplýsingar birtir kerfið þær ekki.
- **E3:** Ef kennitala eða persónulegt símanúmer vantar í kerfið eru þær upplýsingar ekki birtar.

## Forgangur
- **Hár:** Mikilvægt er að mannauðsdeild hafi aðgang að nauðsynlegum persónuupplýsingum og að aðrir notendur geti ekki skoðað þær.

## Tíðni notkunar
- Ekki skilgreind í kröfusöfnuninni. Gera má ráð fyrir að mannauðsdeild noti þetta notkunartilvik eftir þörfum.

## Viðskiptareglur
- **BR-1:** Aðeins starfsmenn mannauðsdeildar hafa heimild til að skoða kennitölur og persónuleg símanúmer starfsmanna.

## Forsendur (Assumptions)
- Gert er ráð fyrir að kerfið geti þekkt hvort notandi tilheyri mannauðsdeild.
- Gert er ráð fyrir að persónuupplýsingar starfsmanna séu þegar skráðar í kerfið.
- Gert er ráð fyrir að notendur geti valið einstaka starfsmenn til að skoða upplýsingar þeirra.

## Annað
- Notkunartilvikið tengist notendakröfu **UR-6** og viðskiptamarkmiði **BO-1**.
- Leit að starfsmanni tengist einnig **UR-1** og **BO-2**.
- Kerfið skal vera aðgengilegt í gegnum vefviðmót samkvæmt **UI-1**.
- Nánar þarf að skilgreina hvernig aðgangsheimildir verða staðfestar og hvernig brugðist verður við röngum eða úreltum upplýsingum.
