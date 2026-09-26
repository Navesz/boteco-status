# boteco-status

Liga e desliga as builds de teste do **Boteco do Fim do Mundo** (Doubyte).

O jogo lê o `status.json` ao abrir:

- `"ativo": false` -> bloqueia **todas** as builds de teste.
- `"bloquear": ["0.9.0"]` -> bloqueia uma versão (o número do rodapé do menu). Também aceita o `buildGUID` de uma build específica.
- `"mensagem"` -> o texto que aparece para quem abrir uma build bloqueada (vazio = texto padrão).

Para desligar uma build: edite o `status.json` aqui no GitHub e salve. Vale na próxima vez que alguém abrir o jogo (sem internet, a build ainda roda por até 3 dias desde a última checagem).
