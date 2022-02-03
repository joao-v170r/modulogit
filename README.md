Meu primeiro sistema no git 
 System.out.println("Hello Git");

<h1>Codigos do GIT</h1>
<div>
    <h5>As chaves duplas não são colocadas nos comandos `{{}}` </h5>
    <hr>
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
    <ul></p>
    <p>git push {{ nome do diretorio na nuvem }} {{ nome do brach }} </p>
    <p></p>
    <p></p>
    <p></p>
</div>