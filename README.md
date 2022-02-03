Meu primeiro sistema no git 
 System.out.println("Hello Git");

<h1>Codigos do GIT</h1>
<div>
    <h3>As chaves duplas não são colocadas nos comandos `{{}}` </h3>
    <h5>BOAS PRATICAS:
        <ul> 
            <li>Sempre quando for fazer um `push` fazer um `pull` "Para não da conflitos casos estaja trabalhando em maquinas diferentes"</li>
        </ul>
    </h5>
    <hr>
    <p>git init "Cria um novo repositorio nas diretorio atual"</p>
    <p>git status "Mostra as alterações feitas que não foram adicionadas ou comitadas, mas também mostra as os aquivos,pastas... que foram adicionadas mas não comitadas</p>
    <p>git log "Mostra todos os comites feitos no brach selecionado "</p>
    <p>git branch {{ nome brach }} "Mostra os branchs feitos. Após o brach se for adicionado algum nome ele cria um novo branch"</p>
    <p>git checkout {{ nome branch }} "Muda para o branch selecionado para o informado em `nome brach`"</p>
    <p>git add {{ nome do arquviso, pasta... }} / -A (para adicionar todos os aquivos,pastas...) "Adiciona os aquvios mas ainda não commita"</p>
    <p>git commite -m / -am (o comando `-m` apenas commita os arquvios já adicionados já o comando -am adicionas todos os aquivos alterados ou adicionados é comita) {{ descrição do commit }} "Salva os arquivos no repositorio local"</p>
    <p>git reset --soft / hard / mixed {{ codigo do commite }} <ul>
    <li>O `primeiro` voltara os commits que foram adicionados depois do commit selecionado, mas com os arquivos que foram feitos após o commit selecionado não são excluidos e já estão adicionados</li>
    <li>O `segundo`  voltara os commits que foram adicionados depois do commit selecionado, mas com os arquivos que foram feitos após o commit selecionado ainda não estaram  adicionados</li>
    <li>O `terceiro` voltara os commits que foram adicionados depois do commit selecionado, e exclui todas as alteraçôes ja feitas depois desse commit selecionado</li>
    </ul></p>
    <p>git push {{ nome do diretorio na nuvem }} {{ nome do brach }} </p>
    <p>git revert --no--edit (sem editar o revert) {{ codigo do commit }} "Faz outro commit revertendo o commit selecionado"</p>
    <p>git push {{ nome do diretorio na nuvem }} :{{ nome do branch}} "Exclui o branch selecionado do diretorio da nuvem mencionado"</p>    
    <p>git push -D {{ nome do branch }} "Exclui o branch localmente"</p>
    <p>git pull {{ nome do diretorio na nuvem }} {{ branch requerido }} "Pega as alterações feitas no diretorio da nuvem do diretorio selecionado junto com os arquivos é o historico"</p>
</div>