Processo -> é uma instância de um programa que está sendo executada.
Threads -> é como se fosse uma subdivisão de processos.

como escalar Node -> criando multiplos processos -> vão ocupar o processador
  1- Verificar quantos cors tem a maquina? 4
  2- Subir 4 processos usando pm2 ou algum tipo de gerenciador de processos no nodejs

Libuv (node) faz a negociação para resolver nome com dnds, para interagir com a rede, para criar uma Thread.
V8 -> é um interpretador de javascript de alta performance desenvolvido pelo Google. Ele tem o código aberto e foi desenvolvido em c++ com o objetivo de atender ao navegador Chrome
Node.js é uma plataforma de código aberto, realiando I/O (.io) de forma assíncrona utilizando javascript. É composto pela junção do interpretador V8, do Google, com a biblioteca Libuv e por um conjunto de módulos.