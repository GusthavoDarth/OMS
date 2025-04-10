# Módulos
## Cadastro de usuários
	Cargos (Gestor, Trader, Compliance, Middle-Office)
	1 tabela para usuários
- Nome
- Email
- Telefone
- Login
- Senha
- Se está ativo
- Data do cadastro
- Perfil (Único por enquanto)

## Cadastro de Fundo de Investimento
- Código do fundo - Texto deve ser único em sua tabela - PK
- Nome do fundo
- Valor financeiro dele
- CNPJ
- Moeda - Tabela domínio próprio - FK
- Gestor do fundo

## Cadastro Papel / Ativo
- Código Ativo numérico - PK
- Nome do ativo
- Preço do ativo
- Bolsa - Tabela domínio próprio
- Pais - Tabela domínio próprio
- Moeda - Tabela domínio próprio
- Emissor - Tabela domínio próprio
- Indexador - Tabela domínio próprio
- Taxa
- Tipo de aplicação - não precisa de um domínio próprio (Usar parametrização genérica)  
- Vencimento
