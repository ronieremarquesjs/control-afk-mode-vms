<h1 align="center"> VMs Control Afk Mode </h1>

<p align="center">
Baixe a versão mais recente do software > <a href="https://github.com/ronieremarquesjs/control-afk-mode-vms/releases/download/v1.0.2-beta/1.0.2-beta.zip">versão 1.0.2-beta</a> "Download direto"!
</p>

<p align="center">
  <a href="#-monitordeatividade">JavaScript</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-mododeinstalação">NodeJS</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-mododeinstalação">C#</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-mododeuso">Bathfile</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

![Control AFK VMs (2)](https://github.com/user-attachments/assets/a69199fb-afc4-42a5-8fa3-c258257f7352)

# Monitor de Atividade

Um monitor que detecta a inatividade do usuário e executa ações específicas.

## Modo de Instalação
1. Execute o arquivo `executar.bat`. 
   - Se o Node.js não estiver instalado, uma mensagem de aviso será exibida. 
   - Caso não tenha o Node.js, você pode baixá-lo na pasta do projeto, onde está a versão necessária. Execute o instalador e siga as instruções.
2. Se o Node.js já estiver instalado, basta executar o `executar.bat` e o modo AFK será ativado. 
   - Deixe o PC inativo para que o monitor comece a simular a tecla e o mouse.

## Modo de Uso

| Etapa | Descrição |
|-------|-----------|
| **1. Configuração Inicial** | Verifique se todos os arquivos necessários estão no diretório do projeto. Configure o arquivo `.env` com as variáveis `IP` e `PORT`. |
| **2. Execução do Monitor** | Execute o script `monitor_activity.bat` para iniciar o monitor. O monitor de teclas será iniciado automaticamente e verificará a inatividade do usuário. |
| **3. Detecção de Inatividade** | Não é mais necessário ativar manualmente o monitor. O sistema detecta automaticamente quando você está AFK (Away From Keyboard) e executa as ações configuradas. Pressionar a tecla "P" também enviará uma solicitação POST. |
| **4. Encerramento** | Para encerrar o monitor, feche a janela do terminal ou pressione `Ctrl + C`. |

> [!WARNING]
> O script de inatividade inicia ao detectar inatividade. **Se você voltar a interagir com o computador, o monitor continuará funcionando normalmente.** Simular atividade (como mover o mouse ou pressionar teclas) não interromperá a simulação de atividade.

## Observações
- Certifique-se de que o PowerShell tenha permissões para executar scripts.
- O monitor de teclas funcionará em segundo plano e não interferirá nas suas atividades normais.

## Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções. Crie um fork do repositório e envie um pull request.

## Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com ♥ por Roniere Marques :wave: 
