# Sprint 1 - Documentar plano de automação
## Manter procedimentos

|               |                                                                |
| ------------- | :------------------------------------------------------------- |
| **Descrição** | O sistema conter informações gerais a respeito do procedimento. Um procedimento tem os atributos nome, valor, tempo_medio e descrição. O administrador (adm) do sistema será responsável por cadastrar o procedimento. Também poderá consultar dados sobre o procedimento no sistema. O administrador do sistema pode realizar as operações de adicionar, alterar, remover e listar os usuários comuns do sistema. |


| **Requisitos envolvidos** |                                                    |
| ------------- | :------------------------------------------------------------- |
| RF01          | Manter procedimento |
| RF01.1        | Cadastrar procedimento  |
| RF01.2        | Alterar procedimento  |
| RF01.3        | Consultar procedimento       |
| RF01.5        | Excluir procedimento |

| Código | Descrição |
|--------|----------------------------------------------------|
| TA01.01| Verificar se todos os dados informados são válidos. |
| TA01.02| Verificar se está salvando os dados do proceidmento. |
| TA01.03| Verificar se está consultando dados do proceidmento corretamente. |
| TA01.04| Verificar se está atualizando dados do proceidmento corretamente. |
| TA01.05| Verificar se está suspendendo dados do proceidmento corretamente. |

|                           |                                     |
| ------------------------- | ----------------------------------- | 
| **Prioridade**            | Essencial                           | 
| **Estimativa**            | 2 h                                 | 
| **Tempo Gasto (real):**   | 30m                                 | 
| **Tamanho Funcional**     |                                     | 
| **Analista**              | Ariadny                             | 
| **Desenvolvedor**         | Ariadny                             | 
| **Revisor**               | Riam                                | 
| **Testador**              | José                                | 

### User Story US02 - Manter Projeto

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US03</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong></td>
    <td style="padding:6px;">Cadastrar, atualizar, visualizar e deletar dados do procedimento.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US03 - Manter procedimento</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em> o administrador </em>, quero <em> adicionar, visualizar, atualizar e remover</em> procedimento para <em>conseguir manter o sistema</em>.
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
        <li>O sistema deve exibir mensagem de procedimento inexistente caso ele tente pesquisar um procedimento não cadastrado.</li>
        <li>O sistema deve exibir mensagem de erro caso não consiga deletar procedimento.</li>
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
        <li><strong>Analista:</strong> Ariandy</li>
        <li><strong>Desenvolvedor:</strong> Ariandy</li>
        <li><strong>Revisor:</strong> Riam</li>
        <li><strong>Testador:</strong> José</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>