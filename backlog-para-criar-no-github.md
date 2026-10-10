# Backlog proposto — criar como issues reais no GitHub

Use o template **Funcionalidade** para cada item. Os números reais serão atribuídos pelo GitHub.

## 1. [FEAT] Exibir lista de animais disponíveis
### História de usuário
Como visitante, quero ver animais disponíveis para adoção, para conhecer as opções da ONG.
### Critérios de aceitação
- [ ] A lista mostra nome, foto e espécie de cada animal disponível.
- [ ] Animais marcados como adotados não aparecem como disponíveis.
### Prioridade (MoSCoW)
Must
### Observações e dependências
Depende do cadastro de animais.

## 2. [FEAT] Exibir detalhes do animal
### História de usuário
Como interessado, quero abrir a ficha de um animal, para consultar idade aproximada, porte e descrição.
### Critérios de aceitação
- [ ] A ficha exibe nome, espécie, porte, idade aproximada e descrição.
- [ ] A ficha informa a situação atual de adoção.
### Prioridade (MoSCoW)
Must
### Observações e dependências
Depende da listagem.

## 3. [FEAT] Cadastrar animais pela administração
### História de usuário
Como administrador, quero cadastrar animais, para manter o catálogo atualizado.
### Critérios de aceitação
- [ ] Apenas usuários administradores podem acessar o cadastro.
- [ ] Nome e espécie são obrigatórios; os dados válidos são salvos.
### Prioridade (MoSCoW)
Must
### Observações e dependências
Depende de autenticação administrativa.

## 4. [FEAT] Registrar interesse em adoção
### História de usuário
Como visitante, quero enviar uma solicitação de adoção, para que a ONG entre em contato comigo.
### Critérios de aceitação
- [ ] Formulário solicita nome, contato e animal desejado.
- [ ] Ao enviar dados válidos, a solicitação é registrada e há confirmação visual.
### Prioridade (MoSCoW)
Must
### Observações e dependências
Depende da ficha do animal.

## 5. [FEAT] Consultar solicitações recebidas
### História de usuário
Como voluntário autorizado, quero visualizar solicitações, para organizar o atendimento aos interessados.
### Critérios de aceitação
- [ ] A lista mostra solicitante, animal e data da solicitação.
- [ ] Somente usuários autorizados visualizam dados pessoais.
### Prioridade (MoSCoW)
Should
### Observações e dependências
Depende do formulário de interesse e controle de acesso.

## 6. [FEAT] Atualizar status de adoção
### História de usuário
Como administrador, quero alterar o status de adoção de um animal, para evitar divulgar animais já adotados.
### Critérios de aceitação
- [ ] Administrador pode marcar o animal como disponível ou adotado.
- [ ] A listagem pública reflete o status atualizado.
### Prioridade (MoSCoW)
Must
### Observações e dependências
Depende do cadastro e da listagem.

## 7. [FEAT] Autenticar administradores
### História de usuário
Como administrador, quero entrar com credenciais, para gerenciar informações com segurança.
### Critérios de aceitação
- [ ] Credenciais válidas permitem acessar a área administrativa.
- [ ] Credenciais inválidas não permitem acesso e exibem mensagem genérica.
### Prioridade (MoSCoW)
Must
### Observações e dependências
Definir armazenamento seguro de senhas e controle de sessão.

## 8. [FEAT] Filtrar animais por espécie
### História de usuário
Como visitante, quero filtrar animais por espécie, para encontrar opções de meu interesse.
### Critérios de aceitação
- [ ] O filtro oferece ao menos cães e gatos quando houver registros dessas espécies.
- [ ] A lista atualiza os resultados e permite limpar o filtro.
### Prioridade (MoSCoW)
Could
### Observações e dependências
Depende da listagem.
