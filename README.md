# Orbit — instaladores

Repositório **privado** com **apenas os instaladores** do Orbit (sistema interno), um assistente de trabalho para suporte de TI que roda no próprio computador (chamados, agenda, notas, contatos, base de soluções, relatórios). O código-fonte não fica aqui.

## Instalar
1. Abra **[Releases](../../releases)** e baixe `OrbitApp-win-Setup.exe` da versão mais recente.
2. Execute o arquivo. Não precisa ser administrador; a instalação é só para o seu usuário.
3. Como o instalador ainda não tem assinatura digital da empresa, o Windows pode mostrar **"O Windows protegeu o computador"**: clique em **Mais informações** → **Executar assim mesmo**. Isso acontece só na primeira instalação.

## Atualizar
Por enquanto a atualização é manual: baixe o `OrbitApp-win-Setup.exe` da versão nova e execute. A atualização automática volta quando houver um local de distribuição interno da empresa.

## Seus dados
- Ficam só no seu computador, em `%LocalAppData%\Orbit` — separados do programa.
- Atualizar ou desinstalar o Orbit **não apaga** os seus dados.
- O Orbit não envia dados a nenhum servidor próprio. Integrações (Jira, Microsoft 365) só funcionam se você as conectar.

## Desinstalar
Configurações do Windows → Aplicativos → **Orbit** → Desinstalar.

## Requisitos
Windows 10 (1809) ou Windows 11, 64 bits.
