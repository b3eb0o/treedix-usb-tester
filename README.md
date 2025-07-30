# treedix-usb-tester
Info about Treedix USB Tester TRX5-0816

https://treedix.com/de/products/treedix-usb-cable-tester-usb-c-cable-tester-usb-tester-for-data-transmission-and-power-transmission-cable-testing-resistor-testing-type-c-emarker-for-usb-a-micro-b-micro-b-3-0-type-c-lighting-mini-b

Manual: https://cdn.shopify.com/s/files/1/0632/8483/8654/files/usb_cable_tester_EN.pdf?v=1749780105

# USB Type-C Anschlussbelegung und Funktionen
Hier ist eine detaillierte Liste der Leitungen eines USB Type-C Anschlusses und ihrer jeweiligen Funktionen:

## B-Seite (links)
| Pin | Bezeichnung | Funktion 
| B1  | GND         | Masse/Erdung - Gemeinsamer Bezugspunkt für alle Signale
| B2  | TX2+        | Positive Datenübertragungsleitung für zweiten Kanal 
| B3  | TX2-        | Negative Datenübertragungsleitung für zweiten Kanal 
| B4  | VBUS        | Spannungsversorgung (5V) 
| B5  | CC2         | Configuration Channel 2 - Konfigurationskanal zur Rollenaushandlung 
| B6  | D+          | USB 2.0 Datenleitung (positiv) 
| B7  | D-          | USB 2.0 Datenleitung (negativ) 
| B8  | SBU2        | Sideband Use 2 - Zusatzkanal für alternative Modi 
| B9  | VBUS        | Spannungsversorgung (5V) 
| B10 | RX1-        | Negative Datenempfangsleitung für ersten Kanal 
| B11 | RX1+        | Positive Datenempfangsleitung für ersten Kanal 
| B12 | GND         | Masse/Erdung 

## A-Seite (rechts)
| Pin | Bezeichnung | Funktion 
| A1  | GND         | Masse/Erdung 
| A2  | TX1+        | Positive Datenübertragungsleitung für ersten Kanal 
| A3  | TX1-        | Negative Datenübertragungsleitung für ersten Kanal 
| A4  | VBUS        | Spannungsversorgung (5V) 
| A5  | CC1         | Configuration Channel 1 - Konfigurationskanal zur Rollenaushandlung 
| A6  | D+          | USB 2.0 Datenleitung (positiv) 
| A7  | D-          | USB 2.0 Datenleitung (negativ) 
| A8  | SBU1        | Sideband Use 1 - Zusatzkanal für alternative Modi 
| A9  | VBUS        | Spannungsversorgung (5V) 
| A10 | RX2-        | Negative Datenempfangsleitung für zweiten Kanal 
| A11 | RX2+        | Positive Datenempfangsleitung für zweiten Kanal 
| A12 | GND         | Masse/Erdung 

## Funktionserklärungen:
- **GND**:       Masseleitungen, stellen den gemeinsamen Bezugspunkt für alle elektrischen Signale dar
- **VBUS**:      Spannungsversorgungsleitungen, liefern 5V für Stromversorgung und Laden
- **TX+/TX-**:   Differenzielle Senderleitungen für Hochgeschwindigkeitsdatenübertragung
- **RX+/RX-**:   Differenzielle Empfängerleitungen für Hochgeschwindigkeitsdatenübertragung
- **D+/D-**:     USB 2.0 Datenleitungen für Standardkommunikation
- **CC1/CC2**:   Configuration Channel - dienen zur Aushandlung der Rollen (Host/Device) und Stromstärken
- **SBU1/SBU2**: Sideband Use - Zusatzkanäle für alternative Modi wie DisplayPort oder Thunderbolt
