Flutter

- O que é o Flutter

	Flutter e um framework de codigo aberto(open source) que foi criado pelo o google.
Ele facilita o desenvolvimento da interface e permite que a aplicação codada a partir dele roda em qualquer tipo de plataforma: mobile, desktop e web.
Sendo assim, atraves de um mesmo codigo-base a aplicaçao do flutter e multiplataforma e nativa.
entao podemos usar ele para desenvolvimento em Android, IOS, Windows e todos os outros sistemas operacionais.

	A linguagem base do flutter é o Dart, uma linguagem que tambem foi criada pela a Google que se assemelha bastante ao javascript.

Os elementos estruturais do Flutter, como menus, opções de layout, botoes etc, sao widgets
Podemos usá-los atraves de pacotes ja prontos do proprio framework ou criados do zero.
E essas não são as unicas vantagens do Flutter.

- Vantagens do Flutter e quem utiliza o Flutter

	Diversas empresas do mundo usam Flutter para o desenvolvimento de suas aplicações
Principalmente por conta da facilidade de quase todos os seus desenvolvedores estudarem a mesma ferramenta - e sem necessidade de especialização em Android ou IOS, ja que o codigo feito funcionaria em tudo.

Dessa forma, os desenvolvedores se preocupam somente com a aplicação em si, sem necessidade de focar na arquitetura ou nas configurações.

- Principais empresas que utilizam o Flutter

- Nubank
- Ifood
- Ebay
- Google

- O que pode ser feito com Flutter

As possibilidades de utilização do Flutter so aumentam. A principio, o framework foi criado para interfaces mobile, mas já é possivel desenvolver em web e desktop também.
Assim, uma mesma base de código pode ser multiplataforma, tornando o processo de código mais rápido.
Além disso, o Flutter fica na camada de UI (User Interface) das aplicações, não necessitando de nenhum intermediário entre ele e o dispositivo.
Isso aumenta sua performance e fluidez, caracterizando seus produtos praticamente como nativos.

- Diferenciais de codar em Flutter

- Hot Reload
	O hot reload permite que o desenvolvedor consiga fazer as alterações no codigo e ja ver as modificações sendo feita na tela 

- Suporte Google e apoio da comunidade
	O Flutter possui um suporte oficial do Google, ja que foi criado pela a propria empresa.
Isso garante:
- Qualidade na aplicação
- Documentação sempre atualizada
- Segurança de que este nao sera um framework que sera abandonado.

- Velocidade e personalização nos aplicativos moveis
	Pela sua performance quase que nativa, os aplicativos desenvolvidos com o uso do Flutter sao muito mais rapidos.
Isso permite a criação de interfaces personalizadas, alem disso tambem temos a maior facilidade em acessar os recursos do aparelho como a galeria por exemplo

- Codigo aberto e gratuito
	O codigo é aberto e gratuito, com toda a documentação necessaria para uma analise mais aprofundada e consultas externas para a solução de problemas.

- Nao exige conhecimentos aprofundados
	Se voce é iniciante, o Flutter pode ser um bom caminho para começar na programação mobile
Programar com Flutter é simples e facil, pois nao exige conhecimentos aprofundados de programação.

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
            child: Text("Olá, Mundo! :)"),
          ),
        ),
      )));
}


	
	
	

