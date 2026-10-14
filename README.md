# Formulário de Esporte Escolar

Página desenvolvida em HTML e CSS para inscrição de estudantes nas atividades esportivas da escola. Este README compara os itens solicitados pelo professor com o que está presente atualmente em `nome_do_aluno_esporte.html`.

## Como visualizar

Abra `nome_do_aluno_esporte.html` em um navegador. O projeto não precisa de instalação de dependências nem de servidor.

## Requisitos e situação atual

| Item solicitado | Situação no HTML |
| --- | --- |
| Arquivo `nome_do_aluno_esporte.html` | **Concluído.** O arquivo está com o nome solicitado. |
| Título “Formulário de Esporte Escolar” | **Concluído.** Exibido como título principal da página. |
| Nome da escola | **Concluído.** Campo de texto na seção de informações da escola. |
| Modalidade esportiva nas informações da escola | **Concluído.** Há um campo de texto nessa seção. |
| Professor responsável | **Concluído.** Campo de texto na seção de informações da escola. |
| Nome completo do aluno | **Concluído.** Campo de texto na seção de dados do aluno. |
| Turma do aluno | **Concluído.** Campo de texto na seção de dados do aluno. |
| Data de nascimento | **Concluído.** Campo de data na seção de dados do aluno. |
| Turno com opções Matutino, Vespertino e Noturno em botões radio | **Concluído.** As três opções usam botões radio do mesmo grupo. |
| Modalidade em um elemento `<select>`: Futsal, Vôlei, Basquete, Handebol e Atletismo | **Concluído.** As cinco opções estão disponíveis no seletor. |
| Pergunta se o aluno já praticou a modalidade, com Sim e Não | **Concluído.** As opções são botões radio. |
| `<textarea>` para possíveis restrições de saúde | **Concluído.** A página também pergunta se o aluno possui problema de saúde. |
| Nome e telefone do responsável | **Concluído.** Os dois campos estão presentes. |
| Checkbox com a autorização de participação | **Concluído.** O texto da autorização está presente junto à caixa de seleção. |
| Botão “Enviar inscrição” | **Concluído.** O botão de envio está presente. |

## Identificação acadêmica do enunciado

O enunciado também apresenta os dados do Instituto Federal de Educação, Ciência e Tecnologia do Ceará — Campus Iguatu, professor, disciplina, curso, data, aluno e turma. **Esses dados de identificação não aparecem atualmente no HTML.** O formulário possui um campo para a turma do aluno, mas não campos ou cabeçalho para os demais dados.

## Estilo e funcionamento

O CSS está definido dentro do próprio arquivo HTML. A página usa fundo em gradiente roxo, seções com bordas arredondadas e campos organizados em blocos centralizados com largura máxima de 600 px.

O botão está configurado como `submit`, mas o formulário não define um destino de envio nem integra um serviço de armazenamento. Portanto, a página apresenta o formulário, mas não há implementação de processamento ou persistência das inscrições.
