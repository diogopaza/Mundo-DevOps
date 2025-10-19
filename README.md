# Mundo-DevOps

<h2>Comando Linux:</h2>
<p>
  <ul>
    <li>pwd == mostra diretorio atual</li>
    <li>ip address == para verificar o endereço ip</li>
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

<h2>Anotações</h2>
  <p>Importante notar que ao usar uma maquina virtual e atraves da opcao dispositivos e depois rede e definindo modo bridge e possivel usar obter um ip dentro da faixa na qual e usado na maquina local, com isso facilitando o acesso a VM.</p>
