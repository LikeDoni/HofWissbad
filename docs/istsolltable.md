| Server & zentrale IT-Dienste                             |                                                             |                                             |
|----------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------|
| Thema                                                    | IST                                                         | SOLL                                        |
| Serverhardware                                           | 4 Jahre alt                                                 | Hybrid: On-Prem + Cloud                     |
| Serverraum-Technik                                       | Serverraum-Klimagerät + USV                                 | dokumentiert + überwacht (Monitoring)       |
| Serverdienste                                            | DHCP, DNS, Domäne, File/Print, ERP, Hotelsoftware, Telefone | stabil, dokumentiert, redundant             |
| Storage / SAN                                            | vorhanden, wenig dokumentiert                               | sauber dokumentiert, Backupstrategie        |
| Backups                                                  | unvollständig, Datenverluste                                | täglich, Offsite, getestet                  |
| Business-Applikationen                                   | ERP, Physiotherapie, Kassensystem, Zeiterfassung            | API-Schnittstellen + Datenexport            |
|                                                          |                                                             |                                             |
| Netzwerk & Sicherheit                                    |                                                             |                                             |
| Thema                                                    | IST                                                         | SOLL                                        |
| Netzwerk                                                 | gut, aber ohne Doku                                         | vollständige Netz-Doku                      |
| Gebäudevernetzung                                        | 3 Gebäude via Glasfaser                                     | Monitoring + Ausfallsicherheit              |
| Internet                                                 | Glasfaser vorhanden                                         | redundante Leitungen                        |
| Firewall / Sicherheit                                    | Hackerangriffe passiert                                     | ISO27001-nah, MFA, Monitoring               |
| Kameras / Türkontrollen                                  | vorhanden                                                   | integriert ins zentrale Monitoring          |
|                                                          |                                                             |                                             |
| Business-Applikationen                                   |                                                             |                                             |
| Thema                                                    | IST                                                         | SOLL                                        |
| ERP-System                                               | vorhanden                                                   | Schnittstelle ins Infosystem                |
| Hotelsoftware                                            | vorhanden                                                   | personalisierte Gästeinfos                  |
| Kassen / Küche                                           | vorhanden                                                   | Tagesmenüs → automatisch ans Display        |
| Physiotherapie-System                                    | vorhanden                                                   | Wellness-Angebote → App                     |
| Zeiterfassung                                            | vorhanden                                                   | bleibt intern (keine App-Anbindung)         |
|                                                          |                                                             |                                             |
| Gästezimmer / Räume (Gästeautomation)                    |                                                             |                                             |
| Thema                                                    | IST                                                         | SOLL                                        |
| Klimaanlage (Zimmer)                                     | manuelle Bedienung über Wandregler                          | digital über Zimmerscreen steuerbar         |
| Musikanlage (Sonos etc.)                                 | nicht vorhanden                                             | zentral steuerbar (optional)                |
| Display                                                  | keiner                                                      | vollwertiges Zimmer-Infodisplay             |
| Personalisierte Inhalte                                  | nicht vorhanden                                             | basierend auf Check-In-Daten                |
| Zimmerbuchungen                                          | über Rezeption                                              | per Zimmerdisplay oder App möglich          |
|                                                          |                                                             |                                             |
| Hotelräumlichkeiten (Lobby, Restaurant, Wellness, Flure) |                                                             |                                             |
| Bereich                                                  | IST                                                         | SOLL                                        |
| Eingangshalle / Lobby                                    | klassische analoge Info                                     | digitaler Infobildschirm                    |
| Restaurant                                               | Speisekarten manuell                                        | Menü-Boards automatisiert                   |
| Wellness / Sauna / Therapie                              | Infos analog                                                | digitale Angebots- & Verfügbarkeitsdisplays |
| Trainingsraum                                            | keine digitalen Infos                                       | Echtzeit-Pläne (Kurse, Gerätebelegung)      |
| Wartebereiche                                            | Flyer / Plakate                                             | digitale Screens mit tagesaktuellen Infos   |
| Musikanlagen / Ambient Sound                             | manuell gesteuert                                           | zentral über Personal-Display steuerbar     |
| Klimasteuerung (öffentliche Räume)                       | separate physische Regler                                   | zentral steuerbar über Personal-Interface   |
|                                                          |                                                             |                                             |
| Öffentlich zugängliche digitale Informationen            |                                                             |                                             |
| Thema                                                    | IST                                                         | SOLL                                        |
| Digital-Signage (alt)                                    | veraltet                                                    | neues Hotelinformationssystem               |
| Tourismusinfos                                           | statisch                                                    | automatisiert über APIs                     |
| Newsfeeds                                                | nicht vorhanden                                             | automatisiert (RSS, API)                    |
| Wetterdaten                                              | Wetterstation isoliert                                      | über Gateway direkt ans Display             |
| PV-Anlage Daten                                          | vorhanden, aber nicht visualisiert                          | Echtzeit-Anzeige auf App/Displays           |
