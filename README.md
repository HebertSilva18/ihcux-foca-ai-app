Aluno: Herbert Silva de Freitas


# FocaAí

Protótipo de baixa fidelidade feito para a disciplina de IHC & UX.

## Sobre o app

O FocaAí é um aplicativo para ajudar estudantes e profissionais a manter o foco e reduzir o uso de redes sociais durante o trabalho ou estudo.

## Conceito de design

A ideia foi deixar a interface o mais limpa possível. O timer fica no centro da tela com bastante espaço em volta pra não dar aquela sensação de correria. A árvore virtual cresce enquanto o usuário fica focado, o que serve como um incentivo silencioso sem precisar de notificações.

Em vez de mostrar "tempo de tela" (que gera culpa), o app mostra quanto tempo você ganhou pra vida real. O aviso de saída aparece com a árvore "morrendo", mas sem bloquear o usuário — ele pode sair se quiser, só fica ciente das consequências.

## Fluxo para iniciar uma sessão de foco em grupo

1. Na tela de **Seleção de Ambiente**, o usuário escolhe o tempo de foco (slider), o número de blocos e o som de fundo (Chuva, Café ou Floresta).
2. Em **Bloqueio Seletivo**, marca quais apps vão ficar bloqueados durante a sessão.
3. Volta para o **Dashboard**, pressiona "Iniciar Foco" e o timer começa.
4. Pela aba **Grupo**, dá pra ver o progresso dos amigos na mesma sala em tempo real.
5. Se tentar fechar o app antes do tempo, aparece o **modal de aviso** com a árvore murchando.

## Por que usamos esses componentes

Usamos slider para o tempo de foco porque é mais rápido do que digitar um número e ainda dá uma noção visual da duração. Para os blocos Pomodoro colocamos um stepper (+/−) porque os valores são pequenos e discretos, não faz sentido abrir um teclado pra isso. Os toggles dos apps são a escolha óbvia pra uma decisão de sim ou não.

## Telas

1. Dashboard Principal
2. Seleção de Ambiente
3. Bloqueio Seletivo
4. Ranking do Grupo
5. Relatório de Conquistas
6. Tentativa de Saída
