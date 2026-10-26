# TaborApp

**Informacijski sistem za taborniški Rod bistre Savinje**

TaborApp je spletni informacijski sistem za podporo delovanju taborniškega rodu. Omogoča upravljanje članstva, dogodkov, prijav na dogodke, kataloga izdelkov in naročil rodovih izdelkov.

Projekt je razvit v okviru predmeta **Računalniške storitve v oblaku** v študijskem letu 2026/27.

## Funkcionalnosti

- Registracija članov in urejanje uporabniških profilov.
- Pregled dogodkov ter prijava in odjava z dogodkov.
- Administratorsko upravljanje članstva in dogodkov.
- Katalog rodovih izdelkov.
- Oddaja in upravljanje naročil.
- Povezave do izdelkov uradne trgovine Zveze tabornikov Slovenije (ZTS).

## Tehnologije

- **Frontend:** React + TypeScript
- **Backend:** Python + FastAPI
- **Podatkovne baze:** PostgreSQL
- **Vsebniki:** Docker
- **Orkestracija:** Kubernetes
- **Razvoj in sodelovanje:** Git, GitHub, Visual Studio Code

## Arhitektura

Aplikacija bo zasnovana kot cloud-native sistem z ločenimi mikrostoritvami, ki bodo med seboj komunicirale prek REST API-jev. Vsaka mikrostoritev bo upravljala svoje podatke v ločeni podatkovni bazi.

Predvidene mikrostoritve:

- **Member Service** – članstvo in uporabniški profili.
- **Event Service** – dogodki in prijave.
- **Product Service** – katalog izdelkov.
- **Order Service** – naročila rodovih izdelkov.

## Status projekta

Projekt je trenutno v fazi načrtovanja. Tehnologije in arhitektura se lahko med implementacijo prilagodijo zahtevam predmeta in razpoložljivi infrastrukturi.

## Avtor

Tim Lipnik – skupina Azimut
