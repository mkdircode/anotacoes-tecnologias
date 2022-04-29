# Dicionário tech

- ==**Bootcamp**== aprendizagem intensiva e acelerada
    
- ==**Hackathon**== maratona de programação articipantes desenvolvem ideias inovadoras para a área de tecnologia das empresas organizadoras dos eventos. São essas companhias que definem um tema para a competição.
Nos hackathons, os participantes inscritos são distribuídos em times, os quais são compostos por pessoas com conhecimentos variados, como programação, design gráfico, gestão empresarial e outros. Eles devem criar um projeto que encaixe o tema do evento, com soluções e inovação tecnológica. O objetivo da competição não é programar um app inteiro, mas planejar a ideia e desenvolver o básico dela. No Brasil, a Campus Party promove hackathons com temas sociais

    
- **Stack de tecnologia** conjunto tecnologias pra desenvolvimento apps
    

* * *

*Biblioteca é oq usa no nosso código e Framework usa o nosso código. O framework (estrutura genérica, esqueleto sobre o qual um SW pode ser implementado) utilizado durante o cód inteiro. Enquanto quea Biblioteca é cód pré programado e q pode ser reutilizável. Já a API é interface q permite comuniç com aplições e chamada de funções programadas.*

- ==**API**== (interface progrmç apliç): camada de SW com conj regras pra realizar uma tarefa, fornecendo requisição e resposta (permite q interaja com serviço/ outro SW; interaç Apliç Cliente e Apliç Servidor forma remota ou local). Com API pode def como uma tarefa pode ser realizada usando Biblioteca.

Exs: WebGL (gráficos 2D 3D javascript); Ipwhois.io (API geolocalizaç); OpenLayers (API de mapas); OpenWeatherMap API (previsão tempo); Youtube Data API (API do Youtube) ; WinAPI (API do Windows -> nesse caso acesso a servç local)

- **==Biblioteca==** : conj implementaçs (f, procedimentos, classes) pra realizar tarefas comuns(f  específicas e reutilizáveis em apliçs , como manipulç strings, cálc numérico com arrays, manipulç imgs, acesso a B.Ds etc) . Implementa as regras de uma API, chama uma Biblioteca qd precisa de um serviço. Obs: mas se tiver algum bug , desenvolvedor da biblioteca mtas vezes ñ terá tempo pra solucionar esse bug a tempo de vc finalizar a apliç, então importante ter ctz se a biblioteca funciona corretamente e tá atualziada.

Exs de arqs bibliotecas com extensões .dll , .so (linux), .h (cabeçalho), .lib

Ex: React Js pro javascritpt; NumPy (Python); jQuery (Web); Matplotlib ; D3.js ; Processing.js ; STL (C++)

ex math.h no C  (operaçoes raiz qua, log, seno, coss), do contrário precisaria programar manualmente lógica de como calcular. Pode puxar mtas bibliotecas e construir framework

```C
#include <stdio.h>
#include <math.h>
int main () {
```

- ==**Framework**==: maior q biblioteca e API; conjunto de códigos/bibliotecas prontos e outros elementos que podem ser usados no desenvolvimento de aplicativos e sites. Um esqueleto pra vc desenvolver em cima dele (estrut pronta mas ñ tem mta liberdade pra customizar, tem q seguir fluxo de trab, estruturs já pré def ). Muitas vezes consideramos framework como Plataforma de desenvolvimento.

Ex Arquitetura  .Net Framework (Visual studio .NET) é complexa, formada por  varios elementos como VB, C++ C#, JsCript etc  +  Common Language Specification  +  Web Services e Wer Formas ASP.NET + Windows Forms + Data and XML Classes + Framework Class Library + Common Langugage Runtime

Exs de frameworks front-end mais utilizados :React, Angular. js, jQuery, Springboot;  Ex: Hibernate e Spring pro Java ; Angular pro javascript ; Bootstrap pro Css; Laravel pro PHP ; MS .NET pro C# ; Unity pro C#; Django prp Python;