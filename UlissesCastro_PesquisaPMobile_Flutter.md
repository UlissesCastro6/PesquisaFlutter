Flutter

- O que � o Flutter

	Flutter e um framework de codigo aberto(open source) que foi criado pelo o google.
Ele facilita o desenvolvimento da interface e permite que a aplica��o codada a partir dele roda em qualquer tipo de plataforma: mobile, desktop e web.
Sendo assim, atraves de um mesmo codigo-base a aplica�ao do flutter e multiplataforma e nativa.
entao podemos usar ele para desenvolvimento em Android, IOS, Windows e todos os outros sistemas operacionais.

	A linguagem base do flutter � o Dart, uma linguagem que tambem foi criada pela a Google que se assemelha bastante ao javascript.

Os elementos estruturais do Flutter, como menus, op��es de layout, botoes etc, sao widgets
Podemos us�-los atraves de pacotes ja prontos do proprio framework ou criados do zero.
E essas n�o s�o as unicas vantagens do Flutter.

- Vantagens do Flutter e quem utiliza o Flutter

	Diversas empresas do mundo usam Flutter para o desenvolvimento de suas aplica��es
Principalmente por conta da facilidade de quase todos os seus desenvolvedores estudarem a mesma ferramenta - e sem necessidade de especializa��o em Android ou IOS, ja que o codigo feito funcionaria em tudo.

Dessa forma, os desenvolvedores se preocupam somente com a aplica��o em si, sem necessidade de focar na arquitetura ou nas configura��es.

- Principais empresas que utilizam o Flutter

- Nubank
- Ifood
- Ebay
- Google

- O que pode ser feito com Flutter

As possibilidades de utiliza��o do Flutter so aumentam. A principio, o framework foi criado para interfaces mobile, mas j� � possivel desenvolver em web e desktop tamb�m.
Assim, uma mesma base de c�digo pode ser multiplataforma, tornando o processo de c�digo mais r�pido.
Al�m disso, o Flutter fica na camada de UI (User Interface) das aplica��es, n�o necessitando de nenhum intermedi�rio entre ele e o dispositivo.
Isso aumenta sua performance e fluidez, caracterizando seus produtos praticamente como nativos.

- Diferenciais de codar em Flutter

- Hot Reload
	O hot reload permite que o desenvolvedor consiga fazer as altera��es no codigo e ja ver as modifica��es sendo feita na tela 

- Suporte Google e apoio da comunidade
	O Flutter possui um suporte oficial do Google, ja que foi criado pela a propria empresa.
Isso garante:
- Qualidade na aplica��o
- Documenta��o sempre atualizada
- Seguran�a de que este nao sera um framework que sera abandonado.

- Velocidade e personaliza��o nos aplicativos moveis
	Pela sua performance quase que nativa, os aplicativos desenvolvidos com o uso do Flutter sao muito mais rapidos.
Isso permite a cria��o de interfaces personalizadas, alem disso tambem temos a maior facilidade em acessar os recursos do aparelho como a galeria por exemplo

- Codigo aberto e gratuito
	O codigo � aberto e gratuito, com toda a documenta��o necessaria para uma analise mais aprofundada e consultas externas para a solu��o de problemas.

- Nao exige conhecimentos aprofundados
	Se voce � iniciante, o Flutter pode ser um bom caminho para come�ar na programa��o mobile
Programar com Flutter � simples e facil, pois nao exige conhecimentos aprofundados de programa��o.

- Hello Word com Flutter usando a linguagem Dart

import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    // Title
      title: "Exemplo",
      // Home
      home: Scaffold(
        // Appbar
        appBar: AppBar(
          // Title
          title: Text("Exemplo"),
          backgroundColor: Colors.red,
        ),
        // Body
        body: Container(
          // Center the content
          child: Center(
            // Add Text
            child: Text("Ol�, Mundo! :)"),
          ),
        ),
      )));
}


	
	
	

