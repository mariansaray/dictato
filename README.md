# Dictato

**Slovenské diktovanie pre Mac. Zadarmo.**

Stlač **⌥S** (Option+S) v akomkoľvek programe, hovor a text sa sám napíše tam, kde máš kurzor.
Dictato prepíše aj nahrávky a videá. Všetko beží priamo na tvojom Macu, tvoj hlas neodchádza na internet.

Vytvoril [Marián Šaray](https://mariansaray.sk/?utm_source=dictato&utm_medium=github) · Sponzoruje [Sellwinar](https://sellwinar.com/?utm_source=dictato&utm_medium=github), automatické webináre, ktoré predávajú za teba.

---

## Inštalácia (1 minúta)

1. Otvor **Terminál** (stlač ⌘ + medzera, napíš *Terminál* a stlač Enter).
2. Vlož tento riadok a stlač Enter:

   ```
   curl -fsSL https://github.com/mariansaray/dictato/releases/latest/download/install.sh | bash
   ```

3. Dictato sa otvorí a raz si stiahne slovenský model (cca 580 MB). Potom funguje aj bez internetu.
4. Povoľ **mikrofón** a **Prístupnosť** (Dictato ťa navedie tlačidlom *Nastaviť*). Prístupnosť treba na to,
   aby vedelo vložiť text do iných programov.

Hotovo. Ďalšie verzie ti Dictato ponúkne samo, stačí kliknúť *Aktualizovať*.

### Inštalácia bez Terminálu

1. Stiahni si [Dictato.dmg](https://github.com/mariansaray/dictato/releases/latest/download/Dictato.dmg).
2. Otvor ho a potiahni Dictato do priečinka Aplikácie.
3. Pri prvom otvorení Mac napíše, že appku nevie overiť (Dictato je zadarmo, preto nie je v Apple programe za 99 $ ročne).
   Otvor **Nastavenia systému > Súkromie a bezpečnosť**, zroluj dole a pri Dictato klikni **Aj tak otvoriť**.

## Ako diktovať

- **Ťukni** ⌥S, hovor, **ťukni** znova: text sa prepíše a vloží.
- Alebo ⌥S **podrž**, hovor a **pusti**.
- Text ostáva aj v schránke (⌘V) a v histórii, kde ho môžeš upraviť, prehrať si nahrávku alebo ho dať opraviť cez AI.
- Skratku, mikrofón a vlastný slovník mien zmeníš v Nastaveniach.

## Prepis súborov

Pretiahni do okna Dictato audio alebo video (MP3, M4A, WAV, MP4, MOV a ďalšie). Dostaneš čistý text aj text s časmi `[12:40]`.

## Požiadavky

- macOS 14 Sonoma alebo novší.
- Mac s čipom Apple (M1 a novší) aj Intel. Na Inteli je prepis pomalší, ale funguje.
- Pri prvom spustení internet na stiahnutie modelu (cca 580 MB).

## Presnosť

Dictato používa slovenský model reči od KInIT. Na skutočných diktátoch mal **1,7 % chybných slov**,
bežne používaný viacjazyčný model Parakeet v3 na tých istých nahrávkach 14,7 %.

## Súkromie

Nahrávanie a prepis prebiehajú len na tvojom Macu. Na internet sa Dictato pripája iba kvôli
aktualizáciám a stiahnutiu modelu. Tlačidlo *Opraviť cez AI* pošle text do Claude (Anthropic)
len keď ho stlačíš a len s tvojím vlastným kľúčom.

## Licencie

- Model reči: [KInIT parakeet-tdt-0.6b-v3-sk](https://huggingface.co/kinit/parakeet-tdt-0.6b-v3-sk), licencia CC BY 4.0,
  odvodený od NVIDIA Parakeet TDT 0.6B v3. Prevedený do Core ML pre Dictato.
- [FluidAudio](https://github.com/FluidInference/FluidAudio) (Apache 2.0) spúšťa model na Neural Engine.
- Písmo Instrument Sans (SIL Open Font License).

Dictato je zadarmo. Ak ti pomáha, pozri si [Sellwinar](https://sellwinar.com/?utm_source=dictato&utm_medium=github), vďaka ktorému môže existovať.
