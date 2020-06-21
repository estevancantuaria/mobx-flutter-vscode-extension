# Flutter-build_mobx-Extension
Extensão criada para a IDE Visual Studio Code utilizando NodeJS e Typescript para simplificar a execução de um comando Flutter no terminal da IDE. Novos comandos serão futuramente adicionados a esta extensão.

Instalação

Após ter baixado ou clonado este repositório va até o Visual Studio Code e abra a aba de extensões e localize no topo da aba (na mesma linha do titulo 'EXTENSIONS') no canto superior direito o botão com o simbolo '...', clique no mesmo e logo após clique na opção 'install from VSIX'. Após isso localize o arquivo 'flutter-build-mobx-0.0.1.vsix' que esta na pasta raiz do repositório e espere o termino da instalação. Uma vez concluida a instalação, com uma instância do terminal do VsCode aberta pressione o atalho : Ctrl+Shift+P e pesquise pelo comando 'build_mobx', após isso selecione o comando e logo após selecione a opção referente ao terminal que esta aberto e com isso o Vscode executara no terminal o comando:

flutter pub run build_runner build --delete-conflicting-outputs

