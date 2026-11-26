<div align="center">

<img src="assets/banner.svg" alt="Escriptori al Núvol: KDE Plasma, Blender i Google Chrome al teu navegador" width="100%">

<br>

![Ubuntu 24.04](https://img.shields.io/badge/Ubuntu-24.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![KDE Plasma](https://img.shields.io/badge/KDE-Plasma-1D99F3?style=for-the-badge&logo=kde&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-3D-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Google Chrome](https://img.shields.io/badge/Google-Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

### Un ordinador Linux complet, amb Blender i Chrome, que s'obre en una pestanya del navegador.
**Sense instal·lar res. Sense contrasenyes. Des de qualsevol ordinador, també des d'un Chromebook.**

<br>

<a href="https://codespaces.new/Maverick777l/escriptori?quickstart=1">
  <img src="https://github.com/codespaces/badge.svg" alt="Obre l'escriptori a GitHub Codespaces" height="44">
</a>

<sub>👆 Prem el botó per obrir el teu escriptori</sub>

</div>

---

## ⚡ Com s'obre, en 3 passos

<table>
<tr>
<td width="33%" align="center" valign="top">

### 1️⃣
**Prem el botó**

Inicia sessió a GitHub si cal i prem **Create codespace**.

</td>
<td width="33%" align="center" valign="top">

### 2️⃣
**Espera 1-2 minuts**

L'escriptori ja ve muntat: només s'ha d'engegar.

</td>
<td width="33%" align="center" valign="top">

### 3️⃣
**Ja hi ets!**

S'obre una pestanya nova amb l'escriptori.<br>**No cal cap contrasenya.**

</td>
</tr>
</table>

> [!TIP]
> **No s'ha obert la pestanya?** Obre un terminal (menú ☰ → **Terminal** → **New Terminal**). A dalt de tot sempre surt un requadre amb l'**enllaç directe** a l'escriptori i si ja està a punt.
> També el pots obrir des de la pestanya **PORTS** → port **6080** → icona del globus 🌐.

---

## ✨ Què hi trobaràs

| | |
| :---: | :--- |
| 🖥️ | **KDE Plasma** en espanyol i amb teclat espanyol. Lleuger i ràpid: sense animacions, sense indexador i la pantalla no s'apaga mai. |
| 🎨 | **Blender** per modelar, animar i renderitzar en 3D, fent servir tots els nuclis del processador. |
| 🌐 | **Google Chrome**, preparat per funcionar al núvol i com a navegador per defecte. |
| 📁 | **Accessos directes** a l'escriptori: Blender, Chrome, Konsole (terminal), Dolphin (fitxers) i la carpeta **Projectes**. |
| 📋 | **Copiar i enganxar** entre el teu ordinador i l'escriptori, i resolució que s'adapta a la finestra. |
| 🔄 | **Vigilant automàtic**: si l'escriptori es penja, es torna a engegar sol en menys d'un minut i mig. |
| 🔒 | **Només per a tu**: cada persona té el seu propi escriptori, separat de tots els altres. |

---

## 🔓 Sense contrasenya, i segur

L'escriptori s'obre directament, sense cap finestra d'usuari i contrasenya.

**Per què és segur?** L'enllaç de l'escriptori és **privat**: GitHub només hi deixa entrar el propietari del Codespace, amb la sessió de GitHub iniciada. Ningú més hi pot entrar encara que tingui l'enllaç.

> [!WARNING]
> No canviïs el port **6080** a **Public** a la pestanya PORTS: llavors qualsevol persona amb l'enllaç podria entrar al teu escriptori.

<details>
<summary><b>🔑 Vull posar-hi contrasenya igualment</b></summary>
<br>

1. Ves a [github.com/settings/codespaces](https://github.com/settings/codespaces) → **Codespaces secrets** → **New secret**.
2. **Name:** `VNC_PASSWORD` · **Value:** la contrasenya que vulguis.
3. A **Repository access**, tria `Maverick777l/escriptori`.
4. Crea un escriptori nou (o atura i torna a engegar el que tens).

A partir d'ara es demanarà l'usuari **`admin`** i la teva contrasenya.

</details>

---

## 💸 Quant costa?

**Res, si et quedes dins de la quota gratuïta.** Cada compte personal de GitHub té cada mes una quota gratuïta de Codespaces. L'escriptori fa servir **la teva** quota, no la de ningú altre.

- Amb la màquina de **2 nuclis** (la que surt per defecte), la quota dona per a moltes hores al mes.
- L'escriptori **s'atura sol** quan no el fas servir durant una estona, per no gastar quota.
- Pots veure quanta quota et queda a [github.com/settings/billing](https://github.com/settings/billing).

> [!NOTE]
> Una màquina de **4 nuclis** fa anar Blender més ràpid, però gasta la quota el doble de ràpid. Es tria a **⋯ → New with options → Machine type**.

---

## 💾 On deso la feina?

Desa-la a la carpeta **Projectes** de l'escriptori. Es conserva mentre no esborris el Codespace, encara que s'aturi.

Quan esborres el Codespace, **s'esborra tot el que hi ha a dins**. Abans d'esborrar-lo, descarrega el que vulguis guardar: obre Chrome a l'escriptori i puja-ho al teu Google Drive o envia-t'ho per correu.

---

## 🛠️ Si alguna cosa no va

<details>
<summary><b>L'escriptori no s'obre o s'ha penjat</b></summary>
<br>

Normalment es recupera sol en menys d'un minut i mig. Si no, obre un terminal i escriu:

```bash
escriptori
```

Això el reinicia i et torna a mostrar l'enllaç.

</details>

<details>
<summary><b>Surt una pantalla negra o quieta</b></summary>
<br>

El primer cop, KDE triga uns segons a arrencar: espera mig minut. Si continua igual, escriu `escriptori` en un terminal i torna a carregar la pestanya.

</details>

<details>
<summary><b>El teclat escriu símbols estranys</b></summary>
<br>

Prem la icona del teclat a la barra de tasques de l'escriptori i tria **ES** o **US**, segons el teclat que tinguis.

</details>

<details>
<summary><b>El botó m'obre un escriptori antic</b></summary>
<br>

El botó reobre el teu escriptori si ja en tens un. Per començar de zero, ves a [github.com/codespaces](https://github.com/codespaces), esborra'l (**⋯ → Delete**) i torna a prémer el botó.

</details>

<details>
<summary><b>Blender va lent</b></summary>
<br>

L'escriptori no té targeta gràfica: Blender ho calcula tot amb el processador.

- Fes servir el motor de render **Eevee** o **Workbench** per a les vistes prèvies.
- Abaixa la resolució o les mostres del render.
- O crea l'escriptori amb una màquina de **4 nuclis** (gasta la quota més ràpid).

</details>

<details>
<summary><b>Vull mirar què passa per dins</b></summary>
<br>

```bash
cat /tmp/vnc.log          # arrencada de l'escriptori
tail -n 50 ~/.vnc/*.log   # registre de l'escriptori
cat /tmp/vigilant.log     # reinicis automàtics
```

</details>

---

<div align="center">

**Fet amb ❤️ per [Maverick777l](https://github.com/Maverick777l)**

<sub>Aquest repositori només conté el botó per obrir l'escriptori. Tots els drets reservats: consulta la [llicència](LICENSE).</sub>

</div>
