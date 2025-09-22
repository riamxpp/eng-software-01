# Sprint 1 - Documentar plano de automação
## Manter Ordem de serviço

|               |                                                                |
| ------------- | :------------------------------------------------------------- |
| **Descrição** | O sistema deve manter uma Ordem de serviço. O administrador pode cadastrar uma ordem de serviço com os atributos id, id_veiculo, id_procedimento e data. O sistema não terá mecanismo de login, o administrador (adm) do sistema será responsável por cadastrar o usuário. Além disso o adm poderá alterar alguns dados, como o e-mail ou nome. O administrador do sistema pode realizar as operações de adicionar, alterar, remover e listar os usuários comuns do sistema. Essa funcionalidade tem algumas dependências de veículos e procedimentos.


| **Requisitos envolvidos** |                                                    |
| ------------- | :------------------------------------------------------------- |
| RF01          | Manter ordem de serviço |
| RF01.1        | Cadastrar ordem de serviço  |
| RF01.2        | Alterar ordem de serviço  |
| RF01.3        | Consultar ordem de serviços        |
| RF01.4        | Excluir ordem de serviço |

| Código | Descrição |
|--------|----------------------------------------------------|
| TA01.01| Verificar se todos os dados informados são válidos. |
| TA01.02| Verificar se está salvando os dados da procedimento. |
| TA01.03| Verificar se está consultando dados da procedimentos corretamente. |
| TA01.04| Verificar se está atualizando dados da procedimentos corretamente. |
| TA01.05| Verificar se está suspendendo dados da procedimentos corretamente. |

|                           |                                     |
| ------------------------- | ----------------------------------- | 
| **Prioridade**            | Essencial                           | 
| **Estimativa**            | 2 h                                 | 
| **Tempo Gasto (real):**   | 1:30 h                                 | 
| **Tamanho Funcional**     |                                     | 
| **Analista**              | Riam                                | 
| **Desenvolvedor**         | Riam                                | 
| **Revisor**               | Ariadny                             | 
| **Testador**              | José                                | 

### User Story US02 - Manter Projeto

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US04</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong></td>
    <td style="padding:6px;">Cadastrar, atualizar, visualizar e deletar dados do usuário.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US4 - Manter ordem de serviço</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em> o administrador </em>, quero <em> adicionar, visualizar, atualizar e remover</em>, ordem de serviços <em>para conseguir manter o sistema</em>.
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
        <li>O sistema deve exibir mensagem de usuário inexistente caso ele tente pesquisar um usuário não cadastrado.</li>
        <li>O sistema deve exibir mensagem de erro caso não consiga deletar usuário.</li>
        <li>Deve haver pelo menos 1 veículo e 1 procedimento cadastrado no sistema, pois todo serviço está atrelado a 1 veículo e 1 procedimento.</li>
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
        <li>TA04 - Verificar se o veículo e o procedimento existem.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">2h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;">1:30h</td>
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
        <li><strong>Analista:</strong> Riam</li>
        <li><strong>Desenvolvedor:</strong> Riam</li>
        <li><strong>Revisor:</strong> Ariadny</li>
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