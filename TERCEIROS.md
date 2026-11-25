# Componentes de terceiros / Third-party components

O MGR3DO System usa trabalho de outras pessoas. Esta lista diz **o que é, de onde vem e em que pé está a licença**. Onde a licença não está confirmada, está escrito.

*MGR3DO System uses other people's work. This list says what each item is, where it comes from and where its license stands. Where the license is not confirmed, it says so.*

## Dentro do Gerenciador e da ISO que ele monta / Inside the Manager and the ISO it builds

| Componente | Origem | Licença / situação | Uso |
|---|---|---|---|
| **MasterDO** (recompilador Z80 para ARM, VDP, barramento, mapeadores) | [stanton0arch/MasterDO](https://github.com/stanton0arch/MasterDO) | O repositório não declara licença. Uso com autorização do autor; **comprovante escrito pendente** | Núcleo do emulador, com mudanças do Maniaco Game Room (menu, capas, cheats, estado salvo, PAL, biblioteca grande) |
| **Driver `ode`** (`System/Drivers/ode`) e a rotina de acesso à ODE | Derivados do menu da ODE SataTo3DO (Fixel) | **Licença a definir** | Gravar e ler o estado salvo no pen drive |
| **3dt** | [trapexit/3dt](https://github.com/trapexit/3dt) | ISC (licença dentro do Gerenciador) | Monta a ISO do 3DO |
| **Open Sans** | Steve Matteson / Google Fonts | Apache 2.0 | Fonte dos menus (convertida em imagem) |
| **Python**, **Tcl/Tk**, **Pillow**, **PyInstaller** | PSF, Tcl/Tk, Pillow, PyInstaller | Licenças próprias | Base do aplicativo para Windows |

## Baixado pelo Gerenciador no seu PC (não vem no projeto) / Downloaded by the Manager on your PC (not shipped)

| Dado | Origem | Situação |
|---|---|---|
| **Banco de identificação** | No-Intro (dat de Master System e Game Gear) | Usado só para reconhecer as ROMs pelo CRC32 |
| **Capas** (caixa, tela de título, captura) | [libretro-thumbnails](https://github.com/libretro-thumbnails) | Arte das editoras e dos sites; baixadas e convertidas no seu PC |
| **Cheats** | [libretro-database](https://github.com/libretro/libretro-database) | CC BY-SA 4.0 (crédito e mesma licença) |

## Nunca distribuídos / Never distributed

**ROMs** de Master System e Game Gear pertencem às editoras. O projeto não as distribui; cada pessoa usa as suas.

*Master System and Game Gear ROMs belong to their publishers. The project does not distribute them; everyone uses their own.*

## Imagens / Images

As capturas de tela mostram o programa com jogos de terceiros só para ilustrar o menu. Marcas, jogos e capas pertencem aos seus donos. Master System e Game Gear são marcas da Sega; projeto independente, sem afiliação à Sega.

*The screenshots show the program with third-party games only to illustrate the menu. Trademarks, games and covers belong to their owners. Master System and Game Gear are Sega trademarks; independent project, not affiliated with Sega.*

## Crédito / Credits

Obrigado ao autor do MasterDO, ao Fixel e à comunidade de ODEs do 3DO, ao trapexit, à equipe do libretro, ao No-Intro e a todos que mantêm a documentação do 3DO e do Master System.

---

Um projeto **[Maniaco Game Room](https://www.maniacogameroom.com.br/)**.
