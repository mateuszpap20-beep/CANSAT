# 🛰️ CanSat Competition - System Śledzenia Stacji Naziemnej (GSE)

## 📖 O Projekcie
Projekt zrealizowany w ramach międzynarodowego konkursu **CanSat**, polegającego na budowie symulatora sondy kosmicznej. Nasz zespół opracował kompletny system misji, a kluczowym elementem infrastruktury była inteligentna stacja naziemna (Ground Support Equipment).

🔗 **Więcej informacji o zespole i misji:** [https://gniesat.wordpress.com/].

🔗 **Link do dokumentacji:[https://docs.google.com/document/d/1cAFIL4f8U8LUP7mU3SaD9rLaUP9kgKxzTQNRifA5BvA/edit?usp=sharing]

---

## 🏗️ Moja Rola: Mechanika Stacji Naziemnej (Ground Station)
Jako odpowiedzialny za sekcję mechaniczną, zaprojektowałem i wykonałem **dwuosiowy mechanizm śledzący (Pan-Tilt)**, którego zadaniem jest precyzyjne kierowanie anteny kierunkowej Yagi-Uda w stronę poruszającej się sondy CanSat na podstawie danych telemetrycznych.

### 🛠️ Kluczowe Rozwiązania Inżynierskie:
* **Konstrukcja 3D (CAD/Print):** System zaprojektowany w środowisku CAD i wykonany w technologii **FFF/FDM** przy użyciu wytrzymałego filamentu **ABS**. Konstrukcja charakteryzuje się lekkością (mobilność stacji) przy jednoczesnej sztywności niezbędnej do obsługi anteny o długości 1,4 m.
* **Układ Redukcji Obciążeń:** Implementacja autorskiego systemu łożyskowania opartego na stalowych kulkach (Φ 4.5 mm) osadzonych w drukowanych gniazdach. Pozwoliło to na odciążenie wałów serwomechanizmów, eliminację luzów i płynny ruch w osiach azymutu oraz elewacji.
* **Analiza Wytrzymałościowa:** Dobór napędów poprzedzony obliczeniami momentów obrotowych. Wykorzystano serwomechanizmy o wysokim momencie (**25 kg/cm**), co zapewniło stabilność pracy nawet przy wystąpieniu dynamicznych podmuchów wiatru (margines bezpieczeństwa względem obliczonego obciążenia 5,63 kg/cm).
* **Mobilność i Stabilność:** Całość osadzona na lekkim, aluminiowym statywie z regulacją wysokości, co pozwala na szybkie rozstawienie stacji w trudnych warunkach terenowych.

### ⚙️ Specyfikacja Techniczna:
* **Oś Azymutu:** Pełny zakres obrotu 360°.
* **Oś Elewacji:** Zakres od 0° do 380° (możliwość pełnego śledzenia zenitalnego).
* **Napęd:** 2x Serwomechanizm SPT5325LV (360 stopni).
* **Materiały:** ABS (elementy drukowane), aluminium (baza/statyw), stal węglowa (łożyskowanie).

---

## 📂 Dokumentacja i Analiza
W repozytorium znajdują się pliki projektowe oraz pełna analiza techniczna (widoczna na screenach w folderze `/docs`), obejmująca obliczenia statyczne i schematy złożeniowe mechanizmu śledzącego.

---
*Projekt wymagał połączenia wiedzy z zakresu mechaniki płynów (opór wiatru), wytrzymałości materiałów oraz precyzyjnego prototypowania 3D.*
