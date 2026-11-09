# 🎓 Quadern del Mestre

Una aplicació web moderna, lleugera i intuïtiva dissenyada com a **caixa d'eines integrada per a docents**. Permet gestionar alumnat, avaluar assignatures amb càlculs de mitjanes automàtics, generar grups de treball i gestionar l'assistència diària, tot en una única interfície accessible sense necessitat de servidors ni bases de dades externes.

---

## 🚀 Característiques Principals

### 👥 1. Gestió d'Alumnat
- **Afegir alumnes:** Entrada manual individual o per blocs de text (un nom per línia).
- **Importació CSV:** Carrega de llistes directament des de fitxers `.csv`.
- **Cerca i Filtres:** Cerca ràpida en temps real de qualsevol alumne/a.

### 📚 2. Assignatures i Avaluació
- **Creació de Matèries:** Personalitzables per nom i color distintiu.
- **Activitats i Proves:** Organitza la matèria per exàmens, treballs o activitats amb **pes percentual (%) assignat**.
- **Matriu de Notes:** Taula interactiva per introduir qualificacions.
- **Càlcul Automàtic:** Calcula la mitjana ponderada de cada alumne en temps real i en ressalta la nota final.

### 🎲 3. Generador de Grups Avançat
- **Modes de configuració:**
  - Per *nombre total de grups*.
  - Per *nombre d'alumnes per grup*.
- **Repartiment Aleatori:** Generació automàtica d'equips.
- **Exportació Ràpida:** Botó per copiar els grups resultants directament al portapapers.

### 📋 4. Control d'Assistència
- **Registre Diari:** Filtre per data per marcar assistència (*Present*, *Retard*, *Absent*).
- **Accions Ràpides:** Marcar tot el grup com a present amb un sol clic.

### 🔮 5. Seleccionador d'Alumne a l'Atzar
- Ruleta interactiva amb efecte d'animació i celebració amb confetti per triar quin alumne o alumna ha de respondre o fer una lectura.

### 💾 6. Privacitat i Còpies de Seguretat
- **LocalStorage:** Les dades es guarden de forma 100% local i segura al teu navegador. No es requereix cap registre ni connexió a cap servidor extern.
- **Importar / Exportar JSON:** Exporta una còpia de seguretat en JSON en qualsevol moment o importa-la a un altre dispositiu.

---

## 🛠️ Tecnologies Utilitzades

- **HTML5 & JavaScript (ES6+):** Arquitectura Single-File (tot integrat en un sol fitxer `.html`).
- **Tailwind CSS:** Disseny responsive, modern i atractiu mitjançant CDN.
- **FontAwesome:** Iconografia detallada.
- **Canvas Confetti:** Efectes visuals per al seleccionador d'atzar.

---

## 💻 Com utilitzar-ho
Utilitza la app online a (https://bmarquil.github.io/Quadern-del-Mestre/)
o bé en local seguint els següents passos:
1. **Clona el repositori o descarrega el fitxer:**
   ```bash
   git clone https://github.com/el-teu-usuari/quadern-del-mestre.git
   ```
2. **Obre el fitxer `index.html`:** Simplement fes doble clic al fitxer `index.html` o obre'l des de qualsevol navegador modern (Chrome, Firefox, Safari, Edge).
3. No requereix `npm install` ni cap entorn d'execució com Node.js!

---

## 👤 Autor

Web app creada per **Bernat Marquilles**.

---

## 📄 Llicència

Aquest projecte està sota la Llicència MIT - consulta el fitxer [LICENSE](LICENSE) per a més detalls.
