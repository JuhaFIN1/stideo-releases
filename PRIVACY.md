# STIDEO: tietosuoja / privacy

[Suomeksi](#suomeksi) · [English](#english)

## Suomeksi

### STIDEO TIETOSUOJASELOSTE
Versio 2026-11-25  

## 1. TIIVISTELMÄ
STIDEO pyörii SINUN palvelimellasi. Mediasi, valokuvasi, kirjastosi, katseluhistoriasi ja profiilisi pysyvät kyseisellä palvelimella. BluexDEV ei vastaanota niitä, eikä ohjelmistossa ole analytiikkaa, mainontaa tai seurantaa. BluexDEV:lle lähtee vain BluexDEV-tiliä ja lisenssiä varten tarvittava tieto sekä valinnaiset palvelut, jotka itse otat käyttöön (kohta 4).  

## 2. KUKA VASTAA
(a) Sinä, joka asennat ja ylläpidät palvelinta ("ylläpitäjä"), päätät, miksi ja miten palvelimellasi olevia henkilötietoja (perheenjäsenet, ystävät, vieraat, valokuvissasi esiintyvät henkilöt) käsitellään. Kun käytät STIDEOa puhtaasti henkilökohtaisiin tai kotitaloutesi tarkoituksiin, tietosuojalainsäädäntö, kuten GDPR, ei yleensä koske tätä käsittelyä (GDPR 2 art. 2 kohta c); kohtele silti muiden tietoja huolella. Jos käytät STIDEOa muuhun kuin puhtaasti henkilökohtaiseen tai kotitalouskäyttöön, olet rekisterinpitäjä ja vastaat GDPR:n velvoitteista, etkä saa käyttää STIDEOa suoratoistoon suurelle yleisölle.  
(b) BluexDEV on rekisterinpitäjä BluexDEV-tilisi tiedoille sekä kohdassa 4 kuvatuille lisenssi- ja versiotarkistuksille. BluexDEV ei ole palvelimesi sisällön tai tietojen rekisterinpitäjä eikä pääse niitä näkemään.  
Yhteystiedot: asiakaspalvelu@selaa.fi  

## 3. PALVELIMELLASI TALLENNETTAVAT TIEDOT (EIVÄT LÄHDE BLUEXDEV:LLE)
| Tieto | Tarkoitus | Säilytys |
|---|---|---|
| Omistajatilin tunniste (pseudonyymi, BluexDEV-tililtä), asennusavain, ylläpitoavain | omistajana kirjautuminen, lisenssitarkistus | kunnes palvelin irrotetaan |
| Profiilien nimet, PIN (vain suolattu tiiviste), lapsiprofiilimerkintä | perheprofiilit | kunnes profiili poistetaan |
| Katseluhistoria (nimike, kohta, aika) sekä muistetut ääni- ja tekstityskielivalinnat (profiilikohtaisesti sarjan tai kirjaston mukaan) | jatka katselua, kielivalintojen muistaminen | oletuksena 12 kk (asetus), käyttäjä voi poistaa omansa milloin vain (poistaa myös muistetut valinnat) |
| Soittolistat (nimi, nimikkeet, omistajaprofiili tai jaettu) | soittolistat | kunnes poistetaan tai profiili poistetaan |
| Aktiviteettiloki: kirjautumiset (myös epäonnistuneet ja IP-osoite), toiston alut ja katkaisut, laitteiden liittäminen, kirjastojen, jakojen ja asetusten muutokset, isojen tiedostojen ilmoitukset, Seerriin lähetetyt pyynnöt | ylläpitäjän valvonta | 90 päivää tai enintään 5000 tapahtumaa, kumpi täyttyy ensin; näkyy vain ylläpitäjälle, joka voi tyhjentää sen milloin vain. Salasanoja tai avaimia ei kirjata |
| Kirjastoindeksi: tiedostopolut, nimet, tekniset tiedot, tekstitykset | selaus ja toisto | kunnes tiedosto tai kirjasto poistetaan |
| Valokuvat: EXIF-tiedot, myös GPS-sijainti, päivämäärä ja kameratiedot; käsin lisäämäsi henkilö- ja paikkamerkinnät | valokuvien selaus | kunnes kuva poistetaan; GPS näkyy vain ylläpitäjälle ja aikuisprofiileille |
| Liitetyt laitteet (nimi, avain), vierasavaimet ja -istunnot | pääsynhallinta | kunnes poistetaan; vierasavaimet vanhenevat (oletuksena 12 h) |
| Itse syöttämäsi palveluavaimet (esim. TMDB, tekstityspalvelu, Seerr) ja Seerrin osoite | valinnaiset palvelut | kunnes poistetaan; ei näytetä uudelleen |
| Julisteet, kuvaukset, esikatselut, muunnetut tekstitykset | näyttäminen | kunnes nimike poistetaan tai välimuisti siivotaan |

Käynnissä olevat toistoistunnot (laitteen nimi, IP-osoite, nimike) näytetään ylläpitäjälle reaaliaikaisessa näkymässä ja ne säilyvät vain muistissa. Kasvojentunnistusta ei tehdä. Henkilöt merkitään vain käsin. Palvelin ei tallenna kameran tai mikrofonin tallenteita.  

## 4. MUILLE LÄHETETTÄVÄT TIEDOT
BluexDEV (tili ja lisenssi): kun liität palvelimen, ja aika ajoin kun lisenssin tila on päivitettävä (noin viikoittain tai kun ylläpitäjä avaa sivun), palvelin lähettää BluexDEV:lle asennusavaimesi ja tuotetunnisteen ja saa lisenssin tilan sekä pseudonyymin tilitunnisteen. Kun ylläpitäjä avaa asetussivun, palvelin kysyy BluexDEV:ltä uusimman versionumeron (pyyntö sisältää tuotteen nimen ja asennetun version; tulos on välimuistissa 24 tuntia). BluexDEV:n palvelimet näkevät väistämättä näiden pyyntöjen IP-osoitteen. Oikeusperuste: lisenssisopimuksen täyttäminen sekä oikeutettu etu tietoturvaan ja väärinkäytön ehkäisyyn. Säilytys: tietoja säilytetään vain niin kauan kuin lisenssin hallinta, tietoturva ja väärinkäytön esto edellyttävät. Tämä seloste on julkisesti luettavissa myös osoitteessa https://github.com/JuhaFIN1/stideo-releases/blob/main/PRIVACY.md.  
STIDEO Connect (valinnainen, Pro, oletuksena pois): jos kytket sen päälle, palvelin rekisteröi nimensä, palvelintunnisteensa ja määrittämäsi julkiset osoitteet sekä BluexDEV:n havaitseman IP-osoitteen, jotta soittimesi löytävät sen. Tiedot jaetaan vain soittimille, jotka hyväksyt BluexDEV-tililläsi. Voit kytkeä sen pois milloin vain, jolloin rekisteröinti poistuu.  
Valinnaiset palvelut, jotka otat käyttöön omilla avaimillasi: The Movie Database (hakemiesi nimikkeiden nimi ja vuosi), tekstityspalvelu (tiedoston tiiviste, nimi, kieli) Seerr (valinnainen lisäpalvelu; kun ylläpitäjä painaa pyyntönappia, palvelin lähettää nimikkeen, sen tunnisteet ja valitun laatuprofiilin sinun määrittämääsi Seerr-osoitteeseen avaimesi kanssa; pyyntöjä ei lähetetä koskaan automaattisesti) sekä klikkaamasi linkit (esimerkiksi karttalinkki openstreetmap.org:iin kun avaat valokuvan sijainnin). Näitä palveluja ylläpitävät kolmannet osapuolet omien tietosuojakäytäntöjensä mukaan; BluexDEV ei saa näitä tietoja.  
Sohvaperuna (valinnainen): muiden osallistujien laitteet yhdistyvät suoraan sinun laitteeseesi. Tekniikka (WebRTC) paljastaa väistämättä osallistujien IP-osoitteet toisilleen sekä käytetylle STUN/TURN-palvelimelle (oletuksena vain oma STUN-palvelimesi, jos otat sen käyttöön; muuten ei yhtään). Palvelin välittää vain yhteydenmuodostusviestit ja chat-tekstin, jotka säilyvät muistissa huoneen sulkeutumiseen asti. Kamera ja mikrofoni käynnistyvät vain painikkeesta ja selaimen luvalla; mitään ei tallenneta.  
Itse rakentamasi etäyhteys (VPN, tunneli, välityspalvelin) on STIDEOn ulkopuolella ja kyseisten palveluntarjoajien ehtojen alainen.  

## 5. EVÄSTEET JA PAIKALLINEN TALLENNUS
STIDEO käyttää vain välttämättömiä evästeitä ja paikallista tallennusta: ylläpitäjän istuntoeväste (HttpOnly, SameSite=Strict), lyhytikäinen eväste tilin liittämisen aikana sekä laitteillasi tallennus palvelimen osoitteelle, laiteavaimelle, asetuksille, mitatuille laitekyvyille ja käyttöliittymän valinnoille, kuten valitulle laatuprofiilille. Näille ei tarvita suostumusta, eikä niitä käytetä seurantaan tai mainontaan.  

## 6. OIKEUTESI
Jos olet henkilö, jonka tietoja on jonkun STIDEO-palvelimella, käänny kyseisen palvelimen ylläpitäjän puoleen. STIDEOn sisällä käyttäjä voi poistaa oman katseluhistoriansa (myös muistetut kielivalinnat); ylläpitäjä voi poistaa profiileja (historioineen), valokuvia ja merkintöjä, viedä profiilin tiedot ja irrottaa palvelimen. Tietosuojalain nojalla sinulla voi olla oikeus tarkastaa tietosi, oikaista ne, poistaa ne, rajoittaa käsittelyä, vastustaa käsittelyä ja siirtää tiedot järjestelmästä toiseen, sekä oikeus tehdä valitus valvontaviranomaiselle (Suomessa tietosuojavaltuutetun toimisto, tietosuoja.fi, tai oman maasi viranomainen). BluexDEV-tilin tiedoissa ota yhteyttä BluexDEV:hen yllä olevaan osoitteeseen.  

## 7. LAPSET
Sinun on oltava vähintään 16-vuotias asentaaksesi STIDEOn, liittääksesi tilin tai hyväksyäksesi ehdot. Nuoremmat kotitalouden jäsenet saavat käyttää vain lapsiprofiilia, jonka täysi-ikäinen tilinhaltija on luonut ja jota hän valvoo ja joka vastaa heidän tiedoistaan. BluexDEV ei tietoisesti kerää henkilötietoja alle 16-vuotiailta.  

## 8. TIETOTURVA
Salaisuudet tallennetaan rajoitetuin tiedosto-oikeuksin (datakansio 0700, tiedostot 0600), PIN-koodit tiivistetään, vertailut tehdään vakioajassa, kirjautumisyrityksiä rajoitetaan ja verkkokäyttöliittymä lähettää suojaotsakkeet (muun muassa sisällönsuojauskäytäntö). Palvelin kuuntelee vain valitsemassasi verkossa; älä avaa sitä suoraan internetiin ilman VPN:ää, tunnelia tai HTTPS-välityspalvelinta. Ota varmuuskopiot; ohjelmisto ei ajasta niitä.  

## 9. MUUTOKSET
Voimme päivittää tätä selostetta. Olennaiset muutokset näytetään ohjelmistossa.  

---

## English

### STIDEO PRIVACY NOTICE
Version 2026-11-25  

## 1. SUMMARY
STIDEO runs on YOUR server. Your media, photos, libraries, watch history and profiles stay on that server. BluexDEV does not receive them, and the software contains no analytics, advertising or tracking. The only data that goes to BluexDEV is what is needed for the BluexDEV account and licence, plus the optional services you switch on yourself (section 4).  

## 2. WHO IS RESPONSIBLE
(a) You, the person who installs and runs the server ("operator"), decide why and how the personal data on your server is processed (family members, friends, guests, people in your photos). Where you use STIDEO purely for personal or household purposes, data protection law such as the GDPR generally does not apply to that processing (GDPR Art. 2(2)(c)); you should still treat other people's data with care. If you use STIDEO beyond a purely personal or household purpose, you are the controller and are responsible for the GDPR duties, and you must not use STIDEO to stream to the general public.  
(b) BluexDEV is the controller for the data in your BluexDEV account and the licence and version checks described in section 4. BluexDEV is not the controller of the content or data on your server and cannot see it.  
Contact: asiakaspalvelu@selaa.fi  

## 3. DATA STORED ON YOUR SERVER (NOT SENT TO BLUEXDEV)
| Data | Purpose | Kept |
|---|---|---|
| Owner account identifier (pseudonymous, from the BluexDEV account), install token, admin key | signing in as owner, licence check | until the server is unlinked |
| Profile names, PIN (stored only as a salted hash), kids flag | family profiles | until the profile is deleted |
| Watch history (title, position, time) and remembered audio and subtitle language choices (per profile and series or library) | resume, "continue watching", remembering your language choices | 12 months by default (setting), user can delete their own at any time (this also deletes the remembered choices) |
| Playlists (name, items, owner profile or shared) | playlists | until deleted or the profile is deleted |
| Activity log: sign-ins (including failed attempts and the IP address), playback starts and stops, device pairing, changes to libraries, shares and settings, large-file notices, requests sent to Seerr | administrator oversight | 90 days or at most 5000 events, whichever comes first; visible only to the administrator, who can clear it at any time. No passwords or keys are logged |
| Library index: file paths, titles, technical details, subtitles | browsing and playback | until the file or library is removed |
| Photos: EXIF data, including GPS location, date, camera data; people and place labels you add by hand | photo browsing | until the photo is removed; GPS is shown only to the administrator and adult profiles |
| Paired devices (name, key), guest keys and sessions | access control | until removed; guest keys expire (12 h by default) |
| Service keys you enter (e.g. TMDB, subtitle service, Seerr) and the Seerr address | optional services | until removed; never shown again |
| Posters, descriptions, thumbnails, converted subtitles | display | until the item is removed or cache clean-up |

Current playback sessions (device name, IP address, title) are shown to the administrator in a live view and are kept only in memory. No facial recognition is performed. People are tagged only by hand. The server stores no recordings of camera or microphone.  

## 4. DATA SENT TO OTHERS
BluexDEV (account and licence): when you link the server, and from time to time when licence status needs refreshing (about weekly, or when the administrator opens the page), the server sends your install token and the product identifier to BluexDEV and receives licence status and a pseudonymous account identifier. When the administrator opens the settings page, the server asks BluexDEV for the latest version number (the request contains the product name and installed version; result cached for 24 hours). BluexDEV's servers necessarily see the IP address of these requests. Legal basis: performance of the licence contract, and legitimate interest in security and preventing abuse. Retention: data is kept only as long as licence management, security and abuse prevention require. This notice is also publicly available at https://github.com/JuhaFIN1/stideo-releases/blob/main/PRIVACY.md.  
STIDEO Connect (optional, Pro, off by default): if you switch it on, the server registers its name, server identifier and the public address(es) you configured, together with the IP address BluexDEV observes, so that your players can find it. This is shared only with players you approve with your BluexDEV account. You can switch it off at any time, which removes the registration.  
Optional services you enable with your own keys: The Movie Database (title and year of items you ask to look up), a subtitle service (file hash, title, language), Seerr (optional add-on; when the administrator presses a request button, the server sends the title, its identifiers and the chosen quality profile to the Seerr address you configured, together with your key; requests are never sent automatically), and links you click (for example a map link to openstreetmap.org when you open a photo location). These services are operated by third parties under their own privacy policies; BluexDEV does not receive this data.  
Watch party (optional): other participants' devices connect directly to yours. The technology (WebRTC) inherently exposes participants' IP addresses to each other, and to any STUN/TURN server used (by default only your own STUN server, if you enable it; otherwise none). The server relays only connection set-up messages and chat text, kept in memory until the room closes. Camera and microphone start only when you press the button and grant the browser permission; nothing is recorded.  
Remote access you set up yourself (VPN, tunnel, reverse proxy) is outside STIDEO and subject to those providers' terms.  

## 5. COOKIES AND LOCAL STORAGE
STIDEO uses only strictly necessary cookies and local storage: a session cookie for the administrator (HttpOnly, SameSite=Strict), a short-lived cookie during account linking, and storage on your devices for the server address, device key, settings, measured device capabilities and interface choices such as a selected quality profile. No consent is needed for these, and none is used for tracking or advertising.  

## 6. YOUR RIGHTS
If you are a person whose data is on someone's STIDEO server, ask that server's operator. Within STIDEO, users can delete their own watch history (including remembered language choices); the administrator can delete profiles (including their history), photos and labels, export a profile's data, and unlink the server. Under data protection law you may have rights of access, rectification, erasure, restriction, objection and data portability, and the right to complain to a supervisory authority (in Finland: the Office of the Data Protection Ombudsman, tietosuoja.fi; or the authority in your own country). For BluexDEV account data, contact BluexDEV at the address above.  

## 7. CHILDREN
You must be at least 16 to install STIDEO, link an account or accept the terms. Younger household members may use only a kids profile created and supervised by an adult account holder, who is responsible for their data. BluexDEV does not knowingly collect personal data from persons under 16.  

## 8. SECURITY
Secrets are stored with restricted file permissions (data directory 0700, files 0600), PINs are hashed, comparisons are constant-time, login attempts are limited, and the web interface sends security headers (content security policy and others). The server listens only on the network you choose; do not expose it directly to the internet without a VPN, tunnel or HTTPS proxy. Back up your data; the software does not schedule backups.  

## 9. CHANGES
We may update this notice. Material changes are shown in the software.  

---
asiakaspalvelu@selaa.fi
