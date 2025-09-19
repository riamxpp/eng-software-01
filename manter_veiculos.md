# Sprint 1 - Documentar plano de automação
## Manter veículo

|               |                                                                |
| ------------- | :------------------------------------------------------------- |
| **Descrição** | O sistema deve manter o cadastro de veículos. Essa manutenção é feita pelo administrador que pode cadastrar um veículo no sistema inserindo as seguintes informações: marca, modelo, tipo, cor e placa. Junto a isso, ele pode visualizar, editar, ou excluir um veículo cadastrado. |

| **Requisitos envolvidos** |                                                    |
| ------------- | :------------------------------------------------------------- |
| RF01          | Manter veículo     |
| RF01.1        | Cadastrar veículo  |
| RF01.2        | Alterar veículo    |
| RF01.3        | Consultar veículos |
| RF01.4        | Excluir veículo    |

| Código |                       Descrição                              |
|--------|--------------------------------------------------------------|
| TA01.01| Verificar se todos os dados informados são válidos.          |
| TA01.02| Verificar se está salvando os dados do veículo.              |
| TA01.03| Verificar se está consultando dados do veículo corretamente. |
| TA01.04| Verificar se está atualizando dados do veículo corretamente. |
| TA01.05| Verificar se está suspendendo dados do veículo corretamente. |

|                           |                                     |
| ------------------------- | ----------------------------------- | 
| **Prioridade**            | Essencial                           | 
| **Estimativa**            | 2 h                                 | 
| **Tempo Gasto (real):**   | 30 m                                | 
| **Tamanho Funcional**     |                                     | 
| **Analista**              | José                                | 
| **Desenvolvedor**         | José                                | 
| **Revisor**               | Ariadny                             | 
| **Testador**              | Riam                                | 

### User Story US02 - Manter Projeto

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US02</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong></td>
    <td style="padding:6px;">Cadastrar, atualizar, visualizar e deletar dados do veículo.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US02 - Manter veículo</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em> o administrador </em>, quero <em> adicionar, visualizar, atualizar e remover</em>, dados do veículo para <em>conseguir manter o sistema</em>.
    </td>
  </tr>
  <!-- <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong></td>
    <td style="padding:6px;">RF01, RF02...</td>
  </tr> -->
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de erro caso os dados estejam inválidos.</li>
        <li>O sistema deve exibir mensagem de veículo inexistente caso ele tente pesquisar um veículo não cadastrado.</li>
        <li>O sistema deve exibir mensagem de erro caso não consiga deletar veículo.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA01 - Cadastro bem-sucedido com todos os dados preenchidos.</li>
        <li>TA02 - Para cadastrar, atualizar e visualizar válidar os dados.</li>
        <li>TA03 - Tentativa de deletar sem sucesso retorna erro.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">2h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;">30m</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Essencial</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> José</li>
        <li><strong>Desenvolvedor:</strong> José</li>
        <li><strong>Revisor:</strong> Ariadny</li>
        <li><strong>Testador:</strong> Riam</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>