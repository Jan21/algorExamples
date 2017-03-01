#Instalace  
1. Nainstalujte si distribuci pythonu Anaconda. Je to distribuce, která v sobě obsahuje mnoho užitečných knihoven a nástrojů pro práci s jazykem python. Zde je adresa pro stažení: https://www.continuum.io/downloads Vyberte verzi 3.x. 
2. Nainstalujte si program git. Git slouží pro vytváření verzí kódu. My jej budeme používat k synchronizaci. Na každé hodině si stáhneme novou verzi kódu. Odkaz pro stažení: https://git-scm.com/downloads
3. Na libovolném míste v počítači si vytvořte složku s názvem "algor".
4. Otevřete tuto složku a pravým tlačítkem myši klikněte někde do této složky. Otevře se vám nabídka, v které bude položka "Git Bash Here". Po kliknutí na tuto položku se vám zobrazí okno s příkazovým řádkem. Vložte do něj tento příkaz a potvrďte enterem: git clone  https://github.com/Jan21/algorExamples.git  
Tímto si stáhnete zdrojové soubory pro tento předmět do vašeho počítače. Ve složce algor byste nyní měli mít složku algorExamples. 
5. Jděte do složky algorExamples, znovu klikněte pravým a vyberte "Git Bash Here". Do příkazového řádku napište: jupyter notebook
6. V internetovém prohlížeči se vám otevře okno, kde budou složky s jednotlivými lekcemi. U první hodiny je pouze prezentace, která je jen pro ty, kteří byli ten den na hodině. V dalších složkách je vždy soubor s koncovkou ipynb (notebook). Poklikejte na něj a otevře se vám látka, kterou jsem na hodině probírali.

##Co je třeba provést po každé další hodině.
1. Jděte do složky algorExamples, kliněte pravým a vyberte "Git Bash Here".
2. Do příkazového řádku napište "git pull" (bez úvozovek). Tímto se stáhne novější verze kódu.
3. Až bude vše staženo, tak do příkazového řádku napište další příkaz: "jupyter notebook" (bez úvozovek).
4. Otevřete složku pro danou hodinu a v ní najdete notebook pro tuto hodinu.

#Pokud budete mít s čímkoliv problém, napište mi email.


###Příkazy Anaconda:
**conda create -name nazev python=3.6**    --vytvoří virtuální přostředí  
**activate nazev**  --aktivuje virtuální prostředí  
**conda install nazevKnihovny**  --nainstaluje knihovnu do virtuálního prostředí, které je zrovna aktivní  
**conda install jupyter**  
**jupyter notebook** 

###Klávesové zkratky pro jupyter notebook:
**A** - vytvoří novou buňku na buňkou, která je právě označená.  
**B** - to samé, akorát, že buňku vytvoří pod.  
**X** - smaže buňku.  
**Ctrl+Enter** - spustí kód v buňce.  
**H** - otevře nápovědu s klávesovými zkratkami.  

###Příkazy pro git
**git clone http://....**  -- stáhne repozitář s kódem do vašeho počítače.  
**git pull** -- stáhne aktualizace kódu.  
**git add .**  --Upozorní git o změnách v kódu.  
**git commit -m "popis změn"** --uloží verzi kódu..do úvozovek napiště, jaké změny jste provedli.  



