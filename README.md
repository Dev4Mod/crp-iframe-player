# Crunchyroll iFrame Player [![Built with love](https://img.shields.io/badge/made%20with-javascript-yellow?style=for-the-badge)](https://github.com/Dev4Mod/crp-iframe-player/releases/latest) [![Downloads](https://img.shields.io/github/downloads/Dev4Mod/crp-iframe-player/total.svg?style=for-the-badge)](https://github.com/Dev4Mod/crp-iframe-player/releases/latest)

Essa é uma extensão da comunidade que permite assistir todo conteúdo da Crunchyroll.  
Originalmente criada por [itallolegal](https://github.com/itallolegal) (desativado) e [Hyper-Tx](https://github.com/Hyper-Tx), atualmente mantida por [mateus7g](https://github.com/mateus7g) e atualizado por [Dev4Mod](https://github.com/Dev4Mod).  
Um agradecimento especial a todos os colaboradores.

Obrigado por utilizar. :)

## Download

Você pode encontrar as últimas versões disponíveis abaixo:

<a href="https://github.com/Dev4Mod/crp-iframe-player/releases/latest" target="_blank"><img align="right" alt="Desktop" src="https://img.shields.io/badge/desktop-v1.4.0-violet?style=for-the-badge&logo=windows"></a>

#### Desktop (PC)

Atualmente a versão para Desktop está disponível [aqui](https://github.com/Dev4Mod/crp-iframe-player/releases/latest).  
Para instalar veja o passo a passo [para pc](#%EF%B8%8F-como-instalar-desktop).

## 🖥️ Como instalar? (desktop)

A extensão para Desktop funciona apenas em navegadores **baseados em Chromium**, como: Google Chrome, Opera, etc.  
Verifique se o seu browser está atualizado e prossiga:

<img align="right" width="350" height="124" alt="Extraindo arquivo baixado" src="https://raw.githubusercontent.com/Dev4Mod/crp-iframe-player/master/Screenshots/instalacao-3.png?raw=true">

**1** ➜ Faça o [download](#Crunchyroll_Premium/download) do arquivo `Crunchyroll_Premium.zip`, e extraia-o:

**2** ➜ Entre na aba de [extensões](https://raw.githubusercontent.com/Dev4Mod/crp-iframe-player/master/Screenshots/instalacao-1.png?raw=true) do seu navegador (ou acesse diretamente [`chrome://extensions`](chrome://extensions))

**3** ➜ Habilite o **Modo programador**, e então clique no botão **Carregar expandida**:

![Habilitando modo programador, e carregando extensão](https://raw.githubusercontent.com/Dev4Mod/crp-iframe-player/master/Screenshots/instalacao-2.png?raw=true)

**4** ➜ Selecione a pasta [que foi extraída](https://raw.githubusercontent.com/Dev4Mod/crp-iframe-player/master/Screenshots/instalacao-4.png?raw=true) no começo do tutorial

<img align="right" width="350" height="190" alt="Detalhes da extensão instalada" src="https://raw.githubusercontent.com/Dev4Mod/crp-iframe-player/master/Screenshots/instalacao-5.png?raw=true">

**5** ➜ Se você fez tudo certo, você deverá ver um card como este no seu navegador.

**6** ➜ Agora é só assistir 😉

<br /><br /><br />

**Mensagens que podem atualmente ser mandadas para o player via script:**

```yml
tampermonkey: usa um proxy para fazer as requests
lang: código do locale/idioma padrão
playback: sem uso atualmente
beta: caso esteja usando o crunchyroll na versão beta (requer passar old_url)
old_url: url do video na versão antiga do site
up_next_enable: pular episódios automaticamente (quando up_next for informado)
up_next_cooldown: segundos para acabar e mostrar o popup do próximo episódio (0 para desativar popup)
up_next: url do próximo vídeo a ser tocado/redirecionado (requer up_next_enable)
force_mp4: força os vídeos a tocar em mp4 e não m3u8 (ativar essa opção deixará o loading mais lento, recomendado apenas para chromecasting)
webvideocaster: troca o botão de download por casting do WebVideoCaster
```

## 📝 Aviso Crunchyroll Beta

O novo site do Crunchyroll **quebra completamente** a extensão: [26#issuecomment-1006569041](https://github.com/Dev4Mod/crp-iframe-player/issues/26#issuecomment-1006569041)

As novas versões (v1.1.0+) **ainda** são compatíveis pois ao acessar o novo site, seu navegador puxa os dados do vídeo do site antigo.  
Isso quer dizer que, se a versão antiga do Crunchyroll for **completamente substituída** a extensão irá parar de funcionar permanentemente.
