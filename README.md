# Retro-Games
Instalação do Retro Pie no Linux Mint

Siga este tutorial para a instalação do Retro Pie numa máquina com Linux Mint 19

### 1 - Atualize o pacote APT usando este comando
sudo apt-get update && sudo apt-get upgrade

### 2 - Instale os pacotes necessário usando este comando
sudo apt-get install -y git dialog unzip xmlstarlet

### 3 - Clone o projeto oficial do Retro Pie
git clone --depth=1 https://github.com/RetroPie/RetroPie-Setup.git

### 4 - Entre no diretório do setup do Retro Pie
cd RetroPie-Setup

### 5 - Execute o setup de instalação do Retro Pie
sudo ./retropie_setup.sh

### 6 - A tela deve se parecer com isso neste momento 
![c4e3da42-79c4-11e6-82a8-026afa67801b](https://user-images.githubusercontent.com/43183325/45712319-66c25100-bb62-11e8-8012-3e02ee8dda8d.png)

### 7 - Selecione a opção Basic Install (Instalação Básica)

### 8 - Após terminado a instalação, o seu Linux Mint será reiniciado e o Retro Pie aparecerá no menu da sua máquina

#### Agora, você precisa copiar seus arquivos rom para os diretórios ROM associados corretos. Se você seguiu os passos acima, o diretório principal para todas as roms é ~ / RetroPie / roms (ou / home / pi / RetroPie / roms, que é o mesmo aqui). Neste diretório existe um subdiretório para cada sistema emulado suportado, por exemplo, NES, SNES, Sega Megadrive, etc.

#### Atenção deve ser dada para as extensões dos arquivos rom. Alguns emuladores usam .zip, enquanto alguns usam uma extensão de arquivo personalizada associada ao emulador em questão. Por exemplo, o emulador Atari 2600 pode usar .a26, .bin e .rom.
