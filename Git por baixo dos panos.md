# Entendendo como o GIT funciona por baixo dos panos

   - SHA 1 (Secure Hash Algorithm) 
      desenvolvido pela NSA
      
      . Algoritmo de encriptação de 40 digitos que será utilizado
      como identificação, a cada pequena alteração no projeto uma 
      nova chave de encriptação será gerada, dando segurança a aplicação
      que será alocada no Github
      
      
   - Objetos fundamentais
      
      . BLOBS
         Um objeto que armazena metadados como o tipo do objeto, tamanho 
         do arquivo, entre outros... Além de ter um SHA1 proprío e 
         guardar o SHA1 DO ARQUIVO
      
      . TREES
         Um objeto que armazena tipos de Blobs diferentes, além do nome do
         arquivo e seu SHA1 (caracter identificador do arquivo), Além de ter
         o próprio SHA1
      
      . COMMITS   
         O commit é um objeto que aponta para uma arvore, parente (commit
         anterior), o autor, sua mensagem e o timestamp (carimbo de tempo)
         além de possuir o próprio SHA1 
  
         
      
   - Sistema distribuido
      
      Sistema de versões distribuidas entre os mantenedores de um projeto
      específico, trazendo segurança para o código


