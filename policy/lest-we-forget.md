# Integritetspolicy för Lest We Forget

Denna integritetspolicy beskriver hur **Lest We Forget** (”Appen”), utvecklad av **Stefan Manninen**, samlar in, använder och skyddar din information.

---

## 1. Vilken information samlas in?

- **Användarinnehåll**  
  Appen samlar in och lagrar de poster du sparar – inklusive titel, innehåll, taggar samt tidpunkter för när de skapades och senast ändrades.

- **Autentiseringsinformation (vid inloggning)**  
  Om du väljer att logga in med ditt Google-konto för molnsynkronisering får vi tillgång till:
  - Din e-postadress  
  - Ditt visningsnamn  
  - Länken till din profilbild  
  - Ett unikt användar-ID (UID) via Firebase Authentication

  > **Observera**: Vi har aldrig tillgång till ditt Google-lösenord.

- **Molndata**  
  Om du är inloggad synkroniseras dina poster till en privat och säker del av din Firebase Firestore-databas, kopplad till ditt UID.

---

## 2. Hur används informationen?

- **För att tillhandahålla appens funktioner**  
  Dina poster lagras lokalt på enheten så att du kan hantera dem offline.

- **För molnsynkronisering**  
  Din autentisering används för att säkerställa att endast du kan komma åt dina data mellan flera enheter via Firebase Firestore.

- **För att förbättra appen**  
  Anonym och aggregerad användningsdata kan användas för att förbättra funktioner och användarupplevelsen.

---

## 3. Hur skyddas din information?

- **Säker molnlagring**  
  Synkroniserad data lagras i Google Firebase Firestore, som erbjuder kryptering och strikta säkerhetsrutiner. Din data är kopplad till ditt UID och kräver inloggning.

- **Lokal lagring**  
  Poster lagras i en lokal SQLite-databas på din enhet, endast tillgänglig för denna app.

- **Ingen delning med tredje part**  
  Vi säljer, hyr ut eller delar aldrig din personliga information med tredje part i marknadsföringssyfte.

- **Begränsad åtkomst**  
  Endast utvecklaren, **Stefan Manninen**, har begränsad åtkomst till molndatabasen i syfte att underhålla eller felsöka appen, och detta sker under strikt kontroll.

---

## 4. Dina val och rättigheter

- **Inloggning är valfri**  
  Du kan använda appen helt och hållet utan att logga in. Synkronisering är en extra funktion.

- **Radering av data**  
  Du kan när som helst radera poster i appen. Om du är inloggad raderas dessa även i molnet. Om du raderar ditt Google-konto kommer all kopplad data i Firestore att tas bort.

- **Kontakt**  
  Vid frågor om denna policy eller om du vill begära tillgång till eller radering av din data, kontakta: [app@stefanmanninen.se](mailto:app@stefanmanninen.se)

---

## 5. Ändringar i policyn

Denna integritetspolicy kan uppdateras vid behov. Större förändringar meddelas i appen eller på vår webbplats.

**Senast uppdaterad: 13 juli 2025**
