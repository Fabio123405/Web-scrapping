
Web Scraping: Marrin titujt e artikujve nga faqja "https://report-tv.al/" dhe nxjerrin qytetin nga titujt, duke përdorur një funksion që i krahasohet me një listë qytetesh.

Marrja e të Dhënave të Motit: Për çdo qytet, kërkohet informacion për motin nga API-ja OpenWeather dhe ruhet temperatura dhe përshkrimi.

Ruajtja e të Dhënave: Të dhënat ruhen në dy formate:

JSON: Me titujt, qytetet dhe motin.
CSV: Po ashtu, me të njëjtat të dhëna.
Kriptimi:

AES: Kripton skedarin JSON me çelës AES dhe ruan skedarin e kriptuar.
RSA: Kripton çelësin AES me çelësin publik RSA dhe ruan çelësin e kriptuar.
Në fund, kodi printon një mesazh që tregon se të dhënat janë mbledhur dhe ruajtur me sukses.
