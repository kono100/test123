<!-- CONFIGURAÇÃO REMOTA DO BOT GEMINI -->

<!-- ====================================================== -->
<!-- PARÂMETROS GLOBAIS DE CONTROLE -->
<!-- ====================================================== -->

<!-- Controla a cada quantos segundos o bot verifica este arquivo. Se não encontrar, o padrão é 300 (5 minutos). -->
Verificacao:[8]
---

<!-- ====================================================== -->
<!-- COMANDOS ADMINISTRATIVOS (BLOQUEIO E PARADA) -->
<!-- ====================================================== -->

<!-- Bloqueia um UUID específico. O bot fechará para este usuário na próxima verificação. -->
BlockUuid:[COLOQUE-AQUI-O-UUID-PARA-BLOQUEAR]
---

<!-- Para o módulo Principal (OCR) de TODOS os usuários. -->
Parar:[Principal]
Uuid:[geral]
---

<!-- Para o módulo de Ataque Cego APENAS do usuário com a chave Kono12. -->
Parar:[Cego]
Chave:[Kono12345]
---

<!-- ====================================================== -->
<!-- MENSAGENS REMOTAS PARA USUÁRIOS -->
<!-- ====================================================== -->

<!-- Envia uma mensagem em pop-up para os usuários. -->
PopUp:[Olá! Lembre-se de beber água e bom jogo! meu amigo123]
Delay:[10]
Repetir:[2]
---

<!-- Envia uma mensagem de voz para os usuários. -->
Voz:[Este é um teste de áudio remoto. oi pamella123]
Delay:[15]
Repetir:[2]
---

<!-- ====================================================== -->
<!-- INFORMAÇÕES ESTÁTICAS (VERSÃO E LICENÇAS) -->
<!-- ====================================================== -->

<!-- Informa aos usuários sobre uma nova versão disponível. -->
Versao:[V2]
---

<!-- Bloco de Licença por UUID -->
Uuid:[64B......500]
Validade:[31/12/2025]
Hora:[23:59:59]
Nivel:[2]
---

<!-- Bloco de Licença por Palavra-Chave -->
Palavra_Chave:[Kono12345]
Validade:[30/11/2025]
Hora:[23:59:59]
Nivel:[1]
---
