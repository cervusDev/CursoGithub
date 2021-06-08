# Tracked e untracked

    - Tracked: Repositório reconhecido pelo git
        
        .Unmodified

            Arquivo ainda não modificado, qualquer alteração feita
            no arquivo o torna modified

            Caso deletarmos um arquivo, ele se torna untracked

        .Modified

            Arquivo que sofreu a modificação, ao rodar o git add 
            em um arquivo, ele é passado para o stage

        .Staged

            Local onde os arquivos são preparados para 
            fazer parte de um novo tipo de agrupamento

            No momento que o commit é realizado, eles passam
            a ser um arquivo commitado

            No momento dos arquivos serem commitados eles voltam ao estado de unmodified

    - Ambiente de desenvolvimento

         . Working Directory
            Area de trabalho local 

         . Staging Area
            Area de staging 

            Os arquivos ficam alternadno entre o working directory
            e a staging area durante o git add

         . Local Repository

            Ao fazer o commit, os mesmos passam a ser representados na sua maquina local
    
    - Verificação de status dos arquivos no repositório

        . Comando: git status

    - Levando o arquivo para o repositório remoto

        . git push --set upstream origin main
