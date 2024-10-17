# Questões

### 1. Quais são as principais desvantagens de concentrar toda a lógica, interface e dados em um único arquivo?

- Manutenção complicada: Um arquivo extenso dificulta a localização de erros e a compreensão do código, tornando as correções e melhorias demoradas, especialmente em projetos maiores.
  
- Baixa reutilização: Quando toda a lógica está centralizada, fica difícil extrair partes do código para serem usadas em outros contextos ou projetos diferentes.

- Falta de organização: Misturar tudo em um único arquivo impede a separação de responsabilidades, o que resulta em um código menos legível e mais propenso a falhas.

- **Problemas de crescimento: Conforme a aplicação aumenta de tamanho, manter toda a funcionalidade em um único arquivo compromete a capacidade de expandir o projeto sem introduzir complexidade excessiva.

### 2. Como a separação em camadas facilita a manutenção e a escalabilidade da aplicação?

- Claridade nas funções: Cada camada (interface, lógica de negócios e dados) tem uma função específica, o que ajuda a identificar e corrigir problemas sem interferir em outras partes da aplicação.
  
- Testes simplificados: A separação em camadas permite testar cada parte da aplicação individualmente, aumentando a confiabilidade dos testes e facilitando a detecção de falhas.

- Melhor adaptação ao crescimento: A estrutura em camadas facilita a adição de novas funcionalidades ou a otimização de partes específicas da aplicação, sem exigir mudanças em todo o sistema.

- Código mais reutilizável: Com as funções organizadas em camadas, é possível reaproveitar módulos ou componentes em diferentes áreas do sistema ou até mesmo em outros projetos.

### 3. Quais são os principais benefícios da arquitetura Pipe e Filtros para sistemas que precisam de flexibilidade nas transformações de dados?

- Modularidade: A separação em filtros independentes permite que cada filtro realize uma função específica, facilitando a combinação de filtros em diferentes ordens para gerar novos fluxos de processamento.

- Manutenção facilitada: Como cada filtro é autônomo, modificações em um filtro não afetam os outros, tornando o processo de atualização ou correção mais simples.

- Reutilização de filtros: Filtros desenvolvidos para uma tarefa podem ser reutilizados em outros processos, economizando tempo e esforço no desenvolvimento de novas funcionalidades.

- Facilidade de expansão: Novos filtros podem ser adicionados ao pipeline sem modificar o funcionamento dos filtros já existentes, permitindo que o sistema evolua de forma flexível e incremental.
