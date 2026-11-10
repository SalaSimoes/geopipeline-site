# Imagens da aplicação

Capturas da janela de receção real (Tkinter, macOS) com dados de demonstração, geradas por
`scripts/capturas_site/gerar.sh` (na raiz do projeto). Para as atualizar depois de mudar a janela, basta
voltar a correr o script: cria os dados numa pasta temporária, corre a linha de comandos e a janela, e
substitui os PNG desta pasta.

| Ficheiro | O que mostra |
|---|---|
| `janela.png` | Janela de receção com ficheiros nas quatro cores (aparece também no topo da página) |
| `detalhe.png` | Detalhe de um ficheiro sem CRS, com a caixa "Definir CRS" |
| `pergunta.png` | Pergunta "imagem única ou folhas separadas" durante o processamento |
| `progresso.png` | Conversão em curso: percentagem na barra de estado e botão Cancelar |
| `linha-de-comandos.png` | Saída real de `receber`, `processar` e `historico`, desenhada como um terminal |

Notas:
- todas têm 2000 × 1384 px (janela de 1000 × 660 em ecrã Retina), para alinharem na galeria;
- os caminhos da pasta temporária aparecem como `/Volumes/entregas/...` e `~/geopipeline/...`;
- na imagem do progresso, o estado da janela (percentagem, botões, registo) é reproduzido pelo script,
  porque os dados de demonstração são convertidos depressa demais para se apanhar a meio;
- o script precisa de autorização de "Gravação do ecrã" para o terminal (Definições do Sistema →
  Privacidade e segurança).
