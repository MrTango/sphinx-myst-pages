Siwecos Webseiten Scanner
=========================

## TLS Scanner

Der TLS Scanner erlaubt es Ihnen, das Verschlüsselungsprotokoll ([TLS](https://siwecos.de/wiki/Transport_Layer_Security "Transport Layer Security")) Ihres [Servers](https://siwecos.de/wiki/Server "Server") auf [Schwachstellen](https://siwecos.de/wiki/Schwachstellen "Schwachstellen") zu überprüfen. Sollten Sie eine veraltete Version einer [Verschlüsselung](https://siwecos.de/wiki/Verschl%C3%BCsselung "Verschlüsselung") einsetzen oder sich auf veraltete Verfahren ([kryptographische Primitive](https://de.wikipedia.org/wiki/Kryptographisches_Primitiv)) verlassen, wird dies von unserem Scanner erkannt. Des Weiteren ist der TLS Scanner in der Lage, Probleme mit dem eingesetztem [Zertikat](https://siwecos.de/wiki/Zertifikate "Zertifikate") zu erkennen und über schwache Schlüssellängen und [abgelaufene Zertikate](https://siwecos.de/wiki/Zertifikate#Was_tun.2C_wenn_ein_SSL-Zertifikat_abgelaufen_ist.3F "Zertifikate") zu informieren, welche es einem Angreifer erlauben könnten, die Kommunikation zwischen Ihnen und Ihren Kunden zu entschlüsseln. Außerdem kann der TLS Scanner Ihre eingesetzte [TLS-Implementierung](https://siwecos.de/wiki/Transport_Layer_Security "Transport Layer Security") auf bekannte Angriffe wie [Man-in-the-middle Angriff](https://siwecos.de/wiki/Man-in-the-middle "Man-in-the-middle") ([Insecure Renegotiation](https://siwecos.de/wiki/Man-in-the-middle "Man-in-the-middle")), [POODLE](https://siwecos.de/wiki/Poodle "Poodle") oder [Heartbleed](https://siwecos.de/wiki/Heartbleed-Schwachstelle/DE "Heartbleed-Schwachstelle/DE") testen.

## XSS-Scanner

Der XSS-Scanner macht auf potentielle Gefahrenstellen im Seitenquelltext aufmerksam. Darunter fällt die Erkennung von [DOM basierten Schwachstellen](https://siwecos.de/wiki/Cross-Site_Scripting "Cross-Site Scripting"), welche es einem Angreifer erlauben könnten, z. B. [Schadcode](https://siwecos.de/wiki/Malware "Malware") in Form von [Javascript](https://siwecos.de/wiki/Javascript "Javascript") im Kontext Ihrer [Webapplikation](https://siwecos.de/wiki/Webanwendung "Webanwendung") auszuführen.

-   [SINKS](https://siwecos.de/wiki/DOMXSS-Schwachstelle/DE "DOMXSS-Schwachstelle/DE")
-   [SOURCES](https://siwecos.de/wiki/Schadcode-Ueber-Fremde-Quellen/DE "Schadcode-Ueber-Fremde-Quellen/DE")