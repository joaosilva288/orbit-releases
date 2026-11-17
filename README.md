# ZettaFlare — instaladores

Este repositório guarda **apenas os instaladores** do ZettaFlare, o sistema interno de suporte de TI (chamados, agenda, notas, contatos, base de soluções e relatórios, no computador do técnico). O código-fonte **não** fica aqui.

O repositório é **público** de propósito: é dele que o ZettaFlare instalado baixa as atualizações.

## Instalar
1. Abra **[Releases](../../releases)** e baixe o `OrbitApp-win-Setup.exe` da versão mais recente. O nome do arquivo continua "OrbitApp": é um nome interno.
2. **Confira o arquivo** antes de executar. O SHA-256 do instalador é divulgado pela TI num canal interno. No PowerShell:
   ```powershell
   Get-FileHash .\OrbitApp-win-Setup.exe -Algorithm SHA256
   ```
   Se o valor não for igual ao divulgado, **não execute** e avise a TI.
3. Execute o arquivo. Não precisa ser administrador: a instalação é só para o seu usuário.
4. Enquanto o instalador não tiver a assinatura digital da empresa, o Windows pode mostrar **"O Windows protegeu o computador"**. Só depois de conferir o SHA-256, clique em **Mais informações** → **Executar assim mesmo**. Isso acontece só na primeira instalação.

## Atualizar
O ZettaFlare verifica sozinho se há versão nova (ao abrir e a cada 6 horas). Quando houver, aparece no topo a faixa **"Nova versão do ZettaFlare disponível"**: clique em **Atualizar agora**. Nada é instalado sem o seu clique.

Quem tinha o **Orbit** instalado recebe o ZettaFlare como uma atualização normal, com todos os dados.

## Seus dados
- Ficam só no seu computador, em `%LocalAppData%\Orbit`, separados do programa. O nome da pasta continua "Orbit" de propósito.
- Atualizar ou desinstalar o ZettaFlare **não apaga** os seus dados.
- Integrações (Jira, Microsoft 365) só funcionam se você as conectar.

## Desinstalar
Configurações do Windows → Aplicativos → **ZettaFlare** → Desinstalar.

## Requisitos
Windows 10 (1809) ou Windows 11, 64 bits.
