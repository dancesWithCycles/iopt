# short project description
Im IoPT Projekt interagiert die Fahrzeugflotte von Unternehmen im öffentlichen Verkehr (ÖV) in einem Wide Area Network (WAN) per Langstreckenfunkkommunikation (LoRa) mit rechnergestützten Betriebsleitsystemen (RBL). Dieses betriebseigene Funknetzwerk befreit ÖV-Unternehmen von schnelllebiger Verbraucherelektronik und unkollegialen Dienstleistungsverträgen und schafft dadurch digital Souveränität. Gleichzeitig setzt es branchentypische Betriebsordnungen um und schafft die Grundlage für betriebsinterne Flottenobversation und -distribution als auch für elektronische Fahrgastinformationen (EFGI) wie Echtzeit-Auskunft.

# sociaty challenges
Unternehmen im öffentlichen Verkehr (ÖV) sind per Betriebsordnungen (bspw.  Straßenbahn-Bau- und Betriebsordnung - BOStrab) verpflichtet eine Kommunikationsverbindung mit der Fahrzeugflotte während der gesamten Betriebszeit zu gewährleisten. Durch das Verschwinden von analoger Funktechnik (bspw. analoger Kurzwellenfunk) und dem Mangel an betriebseigenen Netzwerken, bleibt solchen Unternehmen oft nur der Griff zu Dienstleistungen von konventionellen, digitalen Mobilfunkanbietern. Das führt zum Einen zur Abhängigkeit der ÖV-Unternehmen von wenigen Mobilfunkanbietern mit passenden Tarifen. Nicht zu vergessen sind die mit der SIM-Karte verbundenen Kosten pro Flottenfahrzeug. Diese Partnerschaft macht ÖV-Unternehmen abhängig von einem Markt mit beschränktem Wettbewerb und fehlender Kooperation auf Augenhöhe. Die größte Schwierigkeit ist allerdings die fehlende garantierte Servicequalität je nach Mobilfunkstandard und Mobilfunkabdeckung. Dadurch sind Situationen möglich, in denen die Interaktion mit der Fahrzeugflotte unterbrochen ist und gleichzeitig Betriebsordnungen wie bspw. die BOStrab verletzt werden. Muss ein ÖV-Unternehmen auf digitalen Mobilfunk zurückgreifen, hat es außerdem mit einer schnelllebigen Branche zu tun, welche in anderen Zyklen arbeitet statt der ÖV.

# tec project realization
Das IoPT Projekt setzt ein frei verfügbares (Open Source) Protokoll (lora-alliance.org) auf einem frei verfügbaren kalbellosen Netzwerk (thethingsnetwork.org) für ein Langstrecken-Übertragungsverfahren (LoRa) ein, damit die Fahrzeugflotte von ÖV-Unternehmen innerhalb des Tarif-/Betriebsgebietsmit dem rechnergestützten Betriebsleitsystem (RBL) interagieren kann. Ein Flottenfahrzeug ist mit einer Kommunikationseinheit auszustatten, welches mindestens einen LoRa/Sendeempfangsmodul enthält.  Um vom Bestandssystem unabhängig zu sein, empfiehlt sich auch ein eigenes Positionssystem (bspw. GPS). Diese Fahrzeuge interagieren per Funkkommunikation mit einem LoRa Gateway, um einen einheitlichen Zugang zum Applikationsserver zu erhalten. Daten der Fahrzeugflotte werden auf dem Applikationsserver gesammelt verarbeitet, welche wiederum betriebsinterne Flottenobservation und -distribution als auch elektronische Fahrgastinformationen (EFGI) wie Echtzeit-Auskunft ermöglichen. Per web App kann ein Mitarbeiter im RBL kontinuierlich und in Echtzeit die Flotte observieren. Genauso können Fahrgäste per web oder mobile App das ÖV-Angebot live per Echtzeit-Karte verfolgen.

# news
Ich bin Hauptentwickler in dem Open Source Community Projekt Dede Echtzeit-Karte (dedriver.org), welches auf GitHub veröffentlicht ist. Fahrgästen wird die Position von Fahrzeugen von Mobilitätsanbietern (wie bspw. im ÖV) auf einer Echtzeit-Karte angezeigt. Für das Dede Projekt stammen die Positionsdaten von Bestandssystemen oder von der Dede Bordcomputer App für Android Smartphones. Erfahrung und Studien zeigen, dass solche Apps für mobile Endgeräte Hürden für die betrieblichen Prozesse von ÖV-Unternehmen darstellen. Die CU im IoPT Projekt überläuft diese Hürden, kooperiert gleichzeitig mit existierenden Open Source Lösungen und reduziert den Mangel an Echtzeit-Daten in DE.

# similar concepts
Bestehende Ansätze von Anbietern wie mydevices.com, radiobridge.com, thethings.io oder digi.com setzen auf proprietäre Lösungen, welche einem ÖV-Unternehmen zwar eine Alternative zu digitalem Mobilfunk bieten, sie aber weiterhin an Lieferanten-spezifische APIs, Daten, Lizenzen oder Protokolle binden. Die Systemlösung im IoPT Projekt schafft digitale Souveränität durch Open Data und Open Source.

# target
Die Zielgruppe sind vornehmlich ÖV-Unternehmen wie Verkehrsbetriebe, -gesellschaften oder -verbünde. Durch meine ehemalige Anstellung beim VRB (Verkehrsverbund Region Braunschweig GmbH) und meine aktuelle Teilzeitanstellung beim VBN (Verkehrsverbund Bremen/Niedersachsen GmbH) besitze ich ein umfangreiches Netzwerk im ÖV. Unter anderem durch direkten Kontakt werde ich ÖV-Unternehmen Machbarkeitsstudien, partnerschaftliche Entwicklungsprojekts oder Kooperationen vorschlagen. Mir sind eine Vielzahl an Verkehrsbetrieben bekannt, welche bis heute keine Echtzeit-Daten liefern. Durch die Novelle des (PBefG), wird das in Zukunft zur Pflicht. Das IoPT Projekt bietet für diesen Bedarf eine Lösung.

# foss project support
Ich unterstütze in unterschiedlichen Rollen die Open Source Software-Projekte Digitransit (https://github.com/dancesWithCycles/digitransit-ui, ), Stadtnavi Herrenberg (https://github.com/dancesWithCycles/stadtnavi-tutorial, https://github.com/dancesWithCycles/digitransit-setup, https://github.com/dancesWithCycles/digitransit-otp-data), Awesome Transit (https://github.com/dancesWithCycles/awesome-transit), OpenTripPlaner (https://github.com/dancesWithCycles/OpenTripPlanner), Monopati (https://github.com/dancesWithCycles/monopati) usw.

# milestones
* Die bisherige Skizze wird zu einer Spezifikation ausgearbeitet, inklusive
** Systembeschreibung,
** technische Architektur
* Auf bestehender Hardware in Kombination mit FOSS-Eigenentwicklungen und bestehenden FOSS-Modulen entwickle ich Prototypen für eine 
** Kommunikationseinheit (CU), 
** einen LoRa Gateway und 
** einen Applikationsserver.
* Diese drei Komponenten bilden den Prototypen eines IoPT-Systems, welches wie folgt getestet und in Probebetrieb genommen wird.
** eigenständige Testphase mit Probanden
** Kooperation, Probebetrieb oder Machbarkeitsstudie zusammen mit Verkehrsunternehmen
* Verifikation des Projekts durch eine Evaluation des Tests gegen die Spezifikation
k