# TrabalhoDev
Trabalho/Projeto de DevOps - Jogo

Ferramentas:
*GitHub
*Git bash
*VsCode

Nome do Grupo: Grupo Revelação

Participante:
  *Yara Lima _ 2400790
  *Gabriela Araújo _ 2400644
  *Eduardo Nunes _ 2401234
  *Vitir Alexandre _ 2400690

Tema: Torneio de Jogo da Velha

Objetivo do grupo: Aprender e estudar Git e GitHub

Detalhamento: Indivídual

Passo a passo:

1 - Criação do repositório         
git init                    // Criação do repositório
git remote add <Url>        // Adicionamos a Url do repositório externo 
git add .                   //  Adicionamos as alterações feitas no txt, inicialização do ambiente de torneio
git commit -m "Comentário"   // Comentamos a alteração
git push origin main      // Enviamos para o GitHub

2 - Colaboradoes / Jogando
git clone <Url>               // Aqui os jogadores clonam o repositório do GitHub
git add .                     // Os jogadores salvam as suas alterações no arquivo txt
git commit -m "comentário"    //  Comentam a jogada
git push origin main      // Envia a jogada para o GitHub

3 - trazendo as alterações feitas por outro colaborador
git pull origin main         // Estamos buscando as alterações e retornando
git add .
git commit -m ""
git push origin main
