# Aplicativo de Galeria de Fotos

Este é um aplicativo de galeria de fotos que desenvolvi utilizando **Ionic React** e **Capacitor**, capaz de rodar em **iOS**, **Android** e na **web**, tudo com apenas uma base de código. Este projeto é uma implementação completa de uma experiência **CRUD** (criar-ler-atualizar-excluir).

## Como funciona

Ao navegar para a **Aba 2 (Fotos)**, você pode tocar/clicar no botão da câmera para abrir a câmera do dispositivo. Após tirar ou selecionar uma foto, ela é armazenada permanentemente no sistema de arquivos do dispositivo. Ao reabrir o aplicativo, as imagens são carregadas do sistema de arquivos e exibidas novamente na galeria. Você pode tocar em uma foto para ter a opção de removê-la.

## Visão geral do recurso

- **Estrutura do aplicativo**: React
- **Componentes da UI**: Ionic Framework
- **Botão da câmera**: Botão de ação flutuante (FAB)
- **Exibição da galeria de fotos**: Grade
- **Diálogo Excluir Foto**: Folha de Ação
- **Tempo de execução nativo**: Capacitor
- **Tirando fotos**: API da câmera
- **Escrevendo foto no sistema de arquivos**: API do sistema de arquivos
- **Armazenando metadados da galeria de fotos**: API de preferências

## Estrutura do Projeto

- **Tab2 (Fotos)** (`src/pages/Tab2.tsx`): Interface de usuário da galeria de fotos e lógica básica.
- **usePhotoGallery Hook** (`src/hooks/usePhotoGallery.ts`): Lógica que encapsula APIs do Capacitor, incluindo Câmera, Sistema de Arquivos e Preferências.

## Como Executar

Siga o guia para mais detalhes, mas aqui está o caminho mais rápido para rodar o aplicativo:

1. Instale o Ionic, se necessário: `npm install -g @ionic/cli`.
2. Clone este repositório.
3. Em um terminal, mude o diretório para o repositório: `cd photo-gallery-capacitor-react`.
4. Instale todos os pacotes: `npm install`.
5. Execute na web: `ionic serve`.
6. Execute em iOS ou Android seguindo as instruções [aqui](https://ionicframework.com/docs).

---

**Criado por Guitt Zoom / Guitt Web Code**


Demonstraçõa:   https://photo-gallery-ionic-eta.vercel.app/tab1

