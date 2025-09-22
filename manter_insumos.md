# Sprint 1 - Documentar plano de automação
## Manter Insumos

|               |                                                                |
| ------------- | :------------------------------------------------------------- |
| **Descrição** | O sistema deve manter o cadastro de insumos. Essa manutenção é feita pelo administrador que pode cadastrar um insumo no sistema inserindo as seguintes informações: Nome, Marca, Descrição. Junto a isso, ele pode visualizar, editar, ou excluir um insumo cadastrado. |

| **Requisitos envolvidos** |                                                    |
| ------------- | :------------------------------------------------------------- |
| RF01          | Manter Insumo     |
| RF01.1        | Cadastrar Insumo  |
| RF01.2        | Alterar Insumo    |
| RF01.3        | Consultar Insumo  |
| RF01.4        | Excluir Insumo    |

| Código |                       Descrição                              |
|--------|--------------------------------------------------------------|
| TA01.01| Verificar se todos os dados informados são válidos.          |
| TA01.02| Verificar se está salvando os dados do insumo.              |
| TA01.03| Verificar se está consultando dados do insumo corretamente. |
| TA01.04| Verificar se está atualizando dados do insumo corretamente. |
| TA01.05| Verificar se está suspendendo dados do insumo corretamente. |

|                           |                                     |
| ------------------------- | ----------------------------------- | 
| **Prioridade**            | Essencial                           | 
| **Estimativa**            | 2 h                                 | 
| **Tempo Gasto (real):**   | 30 m                                | 
| **Tamanho Funcional**     |                                     | 
| **Analista**              | Ariadny                             | 
| **Desenvolvedor**         | Ariadny                             | 
| **Revisor**               | José                                | 
| **Testador**              | Riam                                | 

### User Story US05 - Manter Insumo

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US05</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong></td>
    <td style="padding:6px;">Cadastrar, atualizar, visualizar e deletar dados do insumo.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US05 - Manter insumo</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em> o administrador </em>, quero <em> adicionar, visualizar, atualizar e remover</em>, dados do insumo para <em>conseguir manter o sistema</em>.
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
        <li>O sistema deve exibir mensagem de insumo inexistente caso ele tente pesquisar um veículo não presente  no estoque.</li>
        <li>O sistema deve exibir mensagem de erro caso não consiga deletar insumo.</li>
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
        <li><strong>Analista:</strong> Ariadny</li>
        <li><strong>Desenvolvedor:</strong> Ariadny</li>
        <li><strong>Revisor:</strong> José</li>
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