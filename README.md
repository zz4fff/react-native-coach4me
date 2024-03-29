# Coach4me

### Um app completo com back-end, front-end e versão mobile, desenvolvido na Especialização em Desenvolvimento Web e Mobile do [Instituto Federal de Educação, Ciência e Tecnologia do Sudeste de Minas Gerais - Campus Rio Pomba](https://www.ifsudestemg.edu.br/riopomba).

## Tecnologias envolvidas:
- Axios
- Expo
- Figma
- Imnsonia
- Next.JS
- Node.JS
- React
- React-native
- SQLite
- Visual Studio Code
- Yarn

## Projeto no Figma

A versão do projeto Web no Figma pode ser acessado clicando [aqui](https://www.figma.com/file/d4ky2gqo1qg2VCWK8iyrya/Coach-4-Me-Web?node-id=0%3A1) e a versão Mobile pode ser acessada clicando [aqui](https://www.figma.com/file/P2oCrdJyOlt4J7zz12CktZ/Coach-4-Me-Mobile).

## Solução de problemas

### Versões incorretas dos pacotes usados

No início dos vídeos é mostrada a versão dos pacotes que devem ser instalados. Quando os vídeos foram gravados as versões eram outras, mas pode acontecer de você estar acompanhando essas vídeo-aulas e as versões atuais dos pacotes apresentarem erros e inconsistências. Se precisar fazer downgrade do NPM digitar no terminal

```
npm install -g npm@3.10.10
```

por exemplo, instalará essa versão específica. Mas só faça isso se tudo o mais não funcionar. Veja antes a versão que está instalada digitando no terminal

```
npm -v
```

e, caso necessário, tente fazer o downgrade.

### O app não abre no smartphone ao ler o QR Code no Expo

Verifique a versão atual da SDK do Yarn e atualize-a para a versão 45.0.0 digitando no terminal ```expo upgrade``` ou para uma mais atual, caso esteja disponível.

### Após atualizar a versão da SDK do Yarn podem aparecer novos erros

Confira o IP do server no arquivo de configuração do axios. Em seguida reinicie o server. Alguns warnings podem continuar aparecendo, mas o app deve executar normalmente.

### Mensagens de erro do VS Code em tags de HTML

Experimente desabilitar o ESLint.


