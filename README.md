<h1>Mod de ponte do telegram com minetest</h1>
------------------------------------------------------------------------------------------------------------
<div>
<h2>Recursos</h2>
  <p> Sincroniza as mensagens de jogadores do servidor no telegram em termpo real  📖 </br>
      Monstra uma mensagem de quem entra e sai ou morre no servidor com nivel de privilegios customisado  🙋</br>
      .all- todos os jogadores que entrarem 🙋🙋🙋</br>
      .privileged- somente quem tiver o privilegio 🙋</br>
      .none- nehum ☹</br>
  </p>
</div>
------------------------------------------------------------------------------------------------------------
<div>
<h3> Comandos </h3>
  /ping  Testa de ping e pong entre servidor e telegram 📶</br>
  /groupid mostra id do grupo do telegram 📄 </br>
  /players mostra jogadores no servidor conectados ou ativos 🎮🎮🎮🎮</br>
  /status mostra o status do servidor 🖥📶📶📶</br>
</div>
------------------------------------------------------------------------------------------------------------
 <div>
<h2>Configurações disponíveis (adicionar ao minetest.conf)</h2>
<p>
  <b>.telegram.token--</b> Necessário, token de bot adquirido para seu bot no telegram</br>
  <b>.telegram.chatid --</b> ID do bate-papo para o qual você retransmitirá as mensagens. Você pode iniciar o bot sem ele e enviar o comando groupid para obtê-lo mais tarde.</br>
  <b>.telegram.timeout --</b>	Periodicidade de atualização. O bot verifica as novas mensagens com esse tempo limite,as as mensagens do jogo são enviadas para telegram immediately. Increase for better performance.</br>
  <b>.telegram.announce_mode --</b> Anunciar jogador entrando ou saindo.</br>
  <b>Opções disponíveis:</b> não, privilegiado, todos. Privilegiado significa interagir por enquanto. As mortes de jogadores podem ser anunciadas no futuro, mas ainda não.</br>
  <b>.telegram.message_color --</b> Cor das mensagens de telegrama no chat do jogo</br>
  <b>.secure.http_mods =</b> telegram</br>
</p>
</div>
