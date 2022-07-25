Meu primeiro sistema no git 
 System.out.println("Hello Git");

<h1>Codigos do GIT</h1>
<div>
    <h3>As chaves duplas não são colocadas nos comandos `{{}}` </h3>
    <h5>BOAS PRATICAS:
        <ul> 
            <li>Sempre quando for fazer um `push` fazer um `pull` "Para não da conflitos casos esteja trabalhando em máquinas diferentes"</li>
        </ul>
    </h5>
    <hr>
    <p>git init "Cria um novo repositório no diretório atual"</p>
    <p>git status "Mostra as alterações feitas que não foram adicionadas ou comitadas, mas também mostra as os arquivos,pastas... que foram adicionadas mas não comitadas</p>
    <p>git log "Mostra todos os commit`s feitos no brach selecionado "</p>
    <p>git branch {{ nome brach }} "Mostra os branchs feitos. Após o branch se for adicionado algum nome ele cria um novo branch"</p>
    <p>git checkout {{ nome branch }} "Muda para o branch selecionado para o informado em `nome brach`"</p>
    <p>git add {{ nome do arquivo, pasta... }} / -A (para adicionar todos os aquivos,pastas...) "Adiciona os arquivos mas ainda não comito"</p>
    <p>git commit -m / -am (o comando `-m` apenas comita os arquivos já adicionados já o comando -am adicionais todos os arquivos alterados ou adicionados é comita) {{ descrição do commit }} "Salva os arquivos no repositório local"</p>
    <p>git reset --soft / hard / mixed {{ codigo do commit }} <ul>
    <li>O `primeiro` voltará os commits que foram adicionados depois do commit selecionado, mas com os arquivos que foram feitos após o commit selecionado não são excluídos e já estão adicionados</li>
    <li>O `segundo`  voltará os commits que foram adicionados depois do commit selecionado, mas com os arquivos que foram feitos após o commit selecionado ainda não estão  adicionados</li>
    <li>O `terceiro` voltara os commits que foram adicionados depois do commit selecionado, e exclui todas as alterações já feitas depois desse commit selecionado</li>
    </ul></p>
    <p>git push {{ nome do diretório na nuvem }} {{ nome do brach }} </p>
    <p>git revert --no--edit (sem editar o revert) {{ código do commit }} "Faz outro commit revertendo o commit selecionado"</p>
    <p>git push {{ nome do diretório na nuvem }} :{{ nome do branch}} "Exclui o branch selecionado do diretório da nuvem mencionado"</p>    
    <p>git push -D {{ nome do branch }} "Exclui o branch localmente"</p>
    <p>git pull {{ nome do diretório na nuvem }} {{ branch requerido }} "Pega as alterações feitas no diretório da nuvem do diretório selecionado junto com os arquivos é o histórico"</p>
</div>

