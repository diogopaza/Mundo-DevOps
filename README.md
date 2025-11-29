# Mundo-DevOps

<h2>Comando Linux:</h2>
<p>
  <ul>
    <li>pwd == mostra diretorio atual</li>
    <li>ip address == para verificar o endereço ip</li>
    <li>crontab -e == abre o agendador de tarefas</li>
  </ul>
  
</p>

<h3>Acesso SSH</h3>
<p>Para o acesso SSH digitamos no prompt diogo@ipDaVM porem retornou erro, foi verificado com o comando <strong>systemctl status ssh</strong> que o servidor SSH nao estava instalado. Abaixo comandos para que o servidor SSH ficasse disponivel na VM:

<ul>
  <li>sudo apt update </li>
  <li>sudo apt install openssh-server -y</li>
  <li>sudo systemctl enable ssh</li>
  <li>sudo systemctl start</li>
  <li>sudo systemctl status ssh</li>  
</ul>
</p>

<h3>Comandos uteis:</h3>
<ul>
  <li>top == lista todos os processos sem execucao</li>
  <li>ps aux = lista todos os processos em execucao</li>
  <li>tail -f = ve ao vivo - tempo real atualizacoes em um arquivo</li>
  <li>curl -I https://nomeDaPagina == retonra os headers da resposta</li>

  
</ul>

<h3>Agendando tarefas</h3>
<p>Com o comando crontab -e e aberto um arquivo onde e possivel configurar o agendamento de scripts para serem executados no Linux. E necessario instalar o pacote cron - apt get install cron</p>

<h4>Exercicio final Curso de
DevOps: explorando conceitos, comandos e scripts no Linux CLI </h4>
<p>
  Para aplicar conhecimentos do curso <emph>DevOps: explorando conceitos, comandos e scripts no Linux CLI da plataforma ALURA.</emph>
  <p>O exercicio pede para copiar/backup da pasta D:\diogo do computador local e salvar no servidor SSH, deve-se criar um Script usando agendamento e monitoramento para acompanhar se o processo ocorreu corretamente.</p>
</p>

<h2>Anotações</h2>
  <p>Importante notar que ao usar uma maquina virtual e atraves da opcao dispositivos e depois rede e definindo modo bridge e possivel usar obter um ip dentro da faixa na qual e usado na maquina local, com isso facilitando o acesso a VM.</p>
