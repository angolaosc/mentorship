# AOSC Mentorship 1.0 - Agosto de 2023 até Setembro de 2023

Estado: Pleaneando

A primeira edição do `AOSC Mentorship` está prevista para Agosto de 2023 até Setembro de 2023.
O programa terá duração de 1 mês.

### Timeline

| actividade | data |
| --- | --- |
| Submissão dos projectos | 25 à 31 de Julho |
| Pre-mentoring Talk | 31 de Julho(Tentativa) |
| Inscrições de participantes | 01 à 08 de Agosto |
| Avaliações das inscrições | 09 à 11 de Agosto |
| Anúncio de mentorados seleccionados | 11 de Agosto de 2023 |
| Pre-mentoria workshop | 14 à 18 de Agosto |
| Fase da mentoria | 21 de Agosto |
| Submissão dos blogs | 04 à 08 de Setembro |
| Fim do programa | 09 de Setembro |


### Instruções de submissão de projectos

Mantenedores de projectos e potenciais mentores são convidados a submeter descrição de seus projectos através da submissão de um PR no GitHub aqui [AOSC Mentorship Program]() até 31 de Julho de 2023. Encontre o modelo de submissão [aqui](https://github.com/angolaosc/mentorship/blob/main/PROJECT_IDEA_TEMPLATE.md).

Porfavor, encorajamos os mantenedores de projectos a submeterem seus projectos o mais cedo possível para que os participantes tenham tempo suficiente para se familiarizarem com os projectos e fazerem suas escolhas.

### Instruções de inscrição para participantes

Os participantes são convidados a se inscreverem através do formulário de inscrição [AOSC Mentorship Program]() até 08 de Agosto de 2023. Para mais informações sobre o processo de inscrição, consulte o [AOSC Mentorship Program Guide](https://github.com/angolaosc/mentorship/blob/main/resources/AOSC_Mentorship_Program_Guide.pdf).

---

### Projectos participantes na primeira edição

Encontre a lista de projectos participantes na primeira edição abaixo. Os participantes são encorajados a se familiarizarem com os projectos e fazerem suas escolhas antes do início do programa.

#### AOSC - Introdução ao Open-source
##### Tradução de inglês para português, um curso introdutório ao desenvolvimento open-source

- Descrição: O [open-sauced-intro](https://github.com/open-sauced/intro) é um curso introdutório ao desenvolvimento open-source e guia para fazer a primeira contribuição.
O curso foi elaborado pela [OpenSauced](github.com/open-sauced) e está completamente em Inglês. Precisamos criar uma cópia não oficial deste curso em Português.
Mais informações sobre o projecto aqui: https://github.com/open-sauced/intro/issues/16
- Resultado esperado: Traduzir pelo menos 15% do curso.
- Habilidades recomendadas: Inglês intermediário, HTML, CSS, e Javascript
- Mentor(s): Nurul Carvalho(@Nurul-GC)
- Problema de Origem (URL): https://github.com/angolaosc/intro-em-portugues/issues/1
- Nível de dificuldade: Fácil

#### Risk Place Angola - É uma plataforma (open-source) para mapear (ou reportar) locais de riscos.
##### Remover Websocket Client do controller de criação de alertas e adicionar metodo write do websocket server para enviar alertas para o cliente.

- Descrição: O [RiskPlace](https://github.com/risk-place-angola/risk-place-angola) é uma plataforma (open-source) para mapear (ou reportar) locais de riscos, Risk Place Angola visa facilitar a chamada de emergência e reportar locais de risco.
O Risk Place Angola possui uma funcionalidade de comunicação em tempo real, que permite que os usuários recebam alertas em tempo real, mas o websocket client está no controller de criação de alertas, o que não é uma boa prática, o ideal seria remover o websocket client do controller de criação de alertas e adicionar metodo write do websocket server para enviar alertas para o cliente.
Mais informações sobre o projecto aqui: https://github.com/risk-place-angola/backend-risk-place/issues/84
- Resultado esperado: Criar alertas em tempo real sem o websocket client no controller de criação de alertas.
- Habilidades recomendadas: Golang
- Mentor(s): Pedro Lopes Estevão(@Paulo-Lopes-Estevao)
- Problema de Origem (URL): https://github.com/risk-place-angola/backend-risk-place/issues/85
- Nível de dificuldade: Médio

#### Client Code Generators - É uma Biblioteca (open-source) para Converter pedidos HTTP em diferentes linguagens à sua escolha, gerando código de pedido HTTP para o mesma linguagenm.
##### Adicionar variante Dio na linguagem Dart - raw data body
- Descrição: O [Client Code Generators](https://github.com/Paulo-Lopes-Estevao/client-code-generators) é uma Biblioteca (open-source) para Converter pedidos HTTP em diferentes linguagens à sua escolha, gerando código de pedido HTTP para o mesma linguagenm.
É um pacote escrito em dart baseado no pacote [Postman Code Generators](https://github.com/postmanlabs/postman-code-generators) do Postman.
O pacote possui 1 variante em dart, que é o http, mas precisamos adicionar mais uma variante, que é o dio.
A variante Dio deve dar suporte a raw data body e headers.
Mais informações sobre o projecto aqui: https://github.com/Paulo-Lopes-Estevao/client-code-generators/issues/4
- Resultado esperado: gerar código de pedido HTTP para a linguagem Dart com a variante Dio, que deve dar suporte a raw data body, headers e o método de pedido HTTP POST.
- Habilidades recomendadas: Dart, HTTP, Inglês básico.
- Mentor(s): Paulo Lopes Estevão(@Paulo-Lopes-Estevao)
- Problema de Origem (URL): https://github.com/Paulo-Lopes-Estevao/client-code-generators/issues/5
- Nível de dificuldade: Médio

#### Predictlow - Uma pequena biblioteca para fazer previsão em grandes conjuntos de dados sem sofrer o problema de out-of-memory.
##### Um projecto ponta-a-ponta para resolver o problema de out-of-memory nos principais algoritmos de aprendizagem de máquina.
- Descrição: O fenômeno "out of memory" ocorre quando um modelo de aprendizagem de máquina esgota a memória disponível durante o treinamento. Isso geralmente acontece quando o conjunto de dados é muito grande ou quando o modelo é muito complexo para a capacidade de memória do sistema. Este é um problema comum em quase todos os algoritmos de aprendizagem de máquina, para superar esse problema, pode-se reduzir o tamanho do conjunto de dados, mas isso só na fase de treinamento, o problema ainda pode persistir na fase de previsão, e aqui entra o predictlow, para permitir fazer previsão de grandes conjunto de dados sem ocorrer o problema de out-of-memory.
- Resultado esperado:  Módulo python (Predictlow) e disponibilizá-lo para instalação via [PIP] (https://pypi.org/project/pip/) para a comunidade opensource consumir com facilidade.
- Problema de Origem (Referência Bibliográfica): https://en.m.wikipedia.org/wiki/Out_of_memory
- Habilidades recomendadas: É desejável python e básico de álgebra linear. Noções de aprendizagem de máquina é um diferencial.
- Mentor(s): Kayenga Campos(@Kissabi)
- Nível de dificuldade: Fácil.

#### Omunga - Plataforma Angolana de Artigos de TI Plataforma Angolana de TI: Compartilhe, aprenda e cresça! Publique artigos, comente, curta e participe de discussões sobre tecnologia. Junte-se à nossa comunidade de profissionais de TI em Angola e impulsione o conhecimento na área.

#####
1. **Atualização do Next.js:**
   - Verificar e atualizar a versão atual do Next.js para a mais recente disponível.
   - Realizar testes para garantir que todas as funcionalidades ainda estejam funcionando corretamente após a atualização.

2. **Refatoração geral do projeto:**
   - Revisar o código existente em busca de melhorias, remoção de redundâncias e simplificação do código.
   - Adotar boas práticas de programação e padrões de design para aumentar a qualidade e a manutenibilidade do código.

3. **Implementar paginação:**
   - Permitir a exibição de um número limitado de artigos por página.
   - Criar os controles de navegação para o usuário acessar páginas adicionais de artigos.

4. **Criar artigos:**
   - Implementar feature para que os usuários possam criar novos artigos.
   - Validar os dados do artigo inserido para garantir a consistência dos dados armazenados.

5. **Listar artigos:**
   - Exibir a lista de artigos disponíveis na aplicação.
   - Organizar os artigos por data, título ou outras categorias relevantes.

6. **Deletar artigos:**
   - Implementar uma funcionalidade que permita aos usuários excluir artigos existentes.
   - Incluir uma confirmação para evitar exclusões acidentais.

7. **Atualizar artigos:**
   - adicionar feature para que os usuários possam editar e atualizar informações de artigos já existentes.

8. **Buscar por artigos:**
   - Implementar uma feature de pesquisa que permita aos usuários buscar artigos com base em palavras-chave ou categorias específicas.

9. **Página dos Artigos Responsiva:**
   - Tornar a página de exibição dos artigos responsiva para melhor adaptação em diferentes dispositivos (desktop, tablet, smartphones).

- Descrição: O [Omunga](https://github.com/OMUNGA) Plataforma Angolana de Artigos de TI
Este é um projeto criado com o principal objetivo de incentivar o compartilhamento de conteúdo por profissionais de TI em Angola. Essencialmente, este aplicativo permite que os usuários publiquem artigos sobre TI, além de comentar, curtir, pesquisar e até mesmo iniciar uma discussão em fórum.

- Resultado esperado: Refatorar o projecto para nova versão do Nextjs e integrar a api Rest full.
- Habilidades recomendadas: Javascript | Nextjs | Nestjs
- Mentor(s): Miguel Buca (@miguelbuca)
- Problema de Origem (URL): https://github.com/OMUNGA/Front-end/issues
- Nível de dificuldade: Médio

### Comunicação

Encorajamos os participantes a se juntarem aos nossos canais de comunicação para se conectarem com outros participantes e mentores. O link para o canal será compartilhado com os participantes selecionados.

Para disucssões gerais, porfavor, use o canal `#aosc-mentorship` no [AOSC Discord](https://discord.gg/tuUDNdRzvze).
