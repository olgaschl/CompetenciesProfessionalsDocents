# 🍏 Assessor de Competències Professionals Docents (MCPD)

Aquesta eina permet analitzar automàticament activitats de formació permanent per al professorat utilitzant IA (Google Gemini). L'objectiu és alinear les activitats amb el **Marc de Competències Professionals Docents de Catalunya**.

## 🚀 Característiques
- **Anàlisi Masiva:** Carrega un fitxer Excel i obté l'anàlisi.
- **Context Oficial:** Utilitza un referencial detallat de les 8 competències del marc (Planificació, Digital, IA, Socioemocional, etc.).
- **Detall Pedagògic:** Retorna nivell dimensions, criteris i indicadors numèrics oficials.
- **Exportació:** Genera un nou fitxer Excel amb tots els resultats processats.

## 🛠️ Com funciona
1. **Obtén una API Key:** Necessites una clau de [Google AI Studio](https://aistudio.google.com/).
2. **Prepara l'Excel:** El fitxer d'entrada ha de tenir l'estructura següent:
      a. Títol de l'activitat formativa
      b. Descripció
      c. Objectius
      d. Continguts
      e. Avaluació
      f. Certificació
4. **Executa l'Anàlisi:** - Obre el fitxer `index.html` al teu navegador.
   - Introdueix la teva API Key.
   - Carrega el fitxer Excel i prem **"Executar Anàlisi"**.

## 📊 Resultats obtinguts
El sistema genera una taula visual, que es pot descarregar en Excel amb:
- **Competència Principal:** (ex. Competència comunicativa en diferents llenguatges i contextos).
- **Nivell d'Assoliment:** Classificació de l'A1 al C2.
- **Dimensions:** Dimensions treballades de la competència principal (ex. 1. Llengua com a base de l’aprenentatge)
- **Criteris:** Criteris de les dimensions relacionades (ex. 1.2 Comunicació inclusiva)
-  **Indicadors:** Indicadors dels criteris relacionats (ex. 1.2.1 Aplica l’acolliment de l’alumnat d’acord amb el projecte lingüístic del centre)
- **Suggeriments:** Propostes de millora pedagògica.

## 📦 Instal·lació
No cal instal·lació. Només clona el repositori i obre el fitxer HTML:
```bash
git clone [https://github.com/EL_TEU_USUARI/nom-del-projecte.git](https://github.com/EL_TEU_USUARI/nom-del-projecte.git)
