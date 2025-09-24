# Sprint 1 - Documentar plano de automação
## Gerar relatório

|               |                                                                |
| ------------- | :------------------------------------------------------------- |
| **Descrição** | O administrador pode gerar relatórios de ordens de serviços por período, clientes com
 pagamentos pendentes e insumos com estoque baixo ou faltando.|

| **Requisitos envolvidos** |                                                    |
| ------------- | :------------------------------------------------------------- |
| RF01          | Manter relatorio     |
| RF01.1        | Cadastrar relatorio  |
| RF01.2        | Alterar relatorio    |
| RF01.3        | Consultar relatorio  |
| RF01.4        | Excluir relatorio    |

| Código |                          Descrição                             |
|--------|----------------------------------------------------------------|
| TA01.01| Verificar se todos os dados informados são válidos.            |
| TA01.02| Verificar se está salvando os dados do relatorio.              |
| TA01.03| Verificar se está consultando dados do relatorio corretamente. |
| TA01.04| Verificar se está atualizando dados do relatorio corretamente. |
| TA01.05| Verificar se está suspendendo dados do relatorio corretamente. |

|                           |                                     |
| ------------------------- | ----------------------------------- | 
| **Prioridade**            | Essencial                           | 
| **Estimativa**            | 2 h                                 | 
| **Tempo Gasto (real):**   | 18 m                                | 
| **Tamanho Funcional**     |                                     | 
| **Analista**              | José                                | 
| **Desenvolvedor**         | José                                | 
| **Revisor**               | Riam                                | 
| **Testador**              | Ariadny                             | 

### User Story US02 - Manter Projeto

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US06</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong></td>
    <td style="padding:6px;">Gerar relatórios de: ordens de serviços realizadas por período, clientes com pagamentos pendentes e insumos com estoque baixo ou em falta.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US06 - Gerar relatórios</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em> o administrador </em>, quero <em> gerar relatórios de: ordens de serviços realizadas por período, clientes com pagamentos pendentes e insumos com estoque baixo ou em falta.</em>.
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
        <li>O sistema deve exibir mensagem de erro caso não consiga gerar algum relatório.</li>
        <li>O sistema deve exibir mensagem de erro se o usuário (adm) tentar gerar um relatório com dados inconsistentes.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA01 - Relatório bem-sucedido com todos os dados.</li>
        <li>TA02 - Para cadastrar, atualizar e visualizar os dados.</li>
        <li>TA03 - Tentativa de deletar um relatório sem sucesso retorna erro.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">2h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;">18m</td>
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
        <li><strong>Revisor:</strong>Riam</li>
        <li><strong>Testador:</strong>Ariadny</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>