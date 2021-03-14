# Fun.ME

Fun.ME é uma aplicação criada em Dart e convertida em JavaScript pela nova função de publicação WEB do Flutter. Desenvolvida para seguir parâmetros específicos para verificação de habilidades de desenvolvimento FullStack como: 
- Integração com API;
- Programação orientada a objetos; 
- Desenvolvimento Front-End;  
- Desenvolvimento Back-End;
- Medidas básicas de segurança.

## Tecnologias utilizadas
O programa foi construido utilizando a linguagem [Dart](https://dart.dev) e o framework [Flutter](https://dart.dev). Para a versão WEB o arquivo Dart foi convertido para HTML + JavaScript e criptografado, assim garantindo a confidencialidade e integridade do código de construção do aplicativo. 

Para a integração com a [API](hps://github.com/sameerkumar18/geek-joke-api) foi realizado uma conexão via protocolo Http, a qual recebe um arquivo Json que é convertido para String. 

Para o desenvolvimento Front-End foi utilizado as funcionalidades disponibilizadas pela linguagem Dart.

## Instalação 
O aplicativo pode ser acessado de duas formas diferentes:

A primeira em seu formato WEB pelo arquivo JavaScript hospedado no repositório do [Git-Hub.Pages](https://takstemler.github.io/):

```bash
https://takstemler.github.io/
```

A segunda em seu formato de aplicativo mobile que pode ser gerado ao baixar do repositório [Dart](https://github.com/TakStemler/Fun.ME)  e rodar:

```bash
From the command line:

Enter cd <app dir>
(Replace <app dir> with your application’s directory.)
Run flutter build apk --split-per-abi
(The flutter build command defaults to --release.)

```

## Usabilidade
A aplicação inicia na tela de login onde você deve fazer o acesso com o seu e-mail e senha, a primeira tela é o um icon representando Poker-Face, assim que ele é "incomodado" com o seu clique ele fica triste. Clicando novamente é recebido um modal contendo várias piadas, à medida que você clica no botão de Laugh, o rosto vai rindo com você até atingir o ápice da felicidade e fechar o modal. O rosto continua feliz até ser "incomodado" novamente com o seu clique, repetindo o ciclo de emoções. 



## License
[Felipe Stemler](https://www.linkedin.com/in/felipe-henrique-stemler-gomes-6a88ab1a2/)