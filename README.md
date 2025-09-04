# 🖥️ 150 Exercícios de SysAdmin (Bash & PowerShell) — Versão Simplificada

Pratique administração de sistemas com **150 exercícios** curtos e diretos, divididos em **6 níveis (25 exercí­cios cada)**.  
O foco é em **tarefas reais** que você pode realizar em Linux (Bash) e Windows (PowerShell).  
> Dica: crie uma pasta `solutions/` com seus scripts para cada exercício.

--- 

## Nível 1 — Sistema de arquivos & permissões — 25 exercícios

001. **Mapa do diretório.** Liste o conteúdo detalhado e ordene por tamanho. _(tags: fs, listagem)_  
002. **Espaço em disco.** Mostre espaço livre por partição/unidade. _(tags: fs, disco)_  
003. **Tamanho de pasta.** Calcule o tamanho total de uma árvore. _(tags: fs, disco)_  
004. **Arquivos grandes.** Encontre arquivos >100 MB. _(tags: fs, busca)_  
005. **Por extensão e data.** Liste `.log` alterados nos últimos 7 dias. _(tags: fs, busca, data)_  
006. **Criar e mover estrutura.** Monte `/logs`, `/tmp`, `/backups` e mova arquivos. _(tags: fs)_  
007. **Remoção segura.** Simule deleção com confirmação/seca. _(tags: fs, segurança)_  
008. **Permissões básicas.** Dê leitura a um grupo e negue a outros. _(tags: perms, ownership)_  
009. **Executáveis.** Torne um script executável e execute localmente. _(tags: perms, exec)_  
010. **Auditar permissões.** Liste dono e ACL recursivamente. _(tags: perms, auditoria)_  
011. **Links simbólicos.** Crie symlink para um arquivo grande. _(tags: fs, links)_  
012. **Compressão/backup.** Comprima uma pasta e valide a extração. _(tags: backup, compress)_  
013. **Integridade.** Gere e valide hash SHA-256 de um arquivo. _(tags: hash, segurança)_  
014. **Montagem de volume.** Monte uma mídia/ISO e liste conteúdo. _(tags: fs, mount)_  
015. **Log gigante.** Siga um arquivo de log sem carregar tudo. _(tags: logs, io)_  
016. **Substituição em massa.** Troque “foo”→“bar” em `.conf` de uma pasta. _(tags: fs, edição)_  
017. **Arquivos órfãos.** Liste arquivos sem dono conhecido. _(tags: perms, auditoria)_  
018. **Cotas de disco.** Verifique/defina cota por usuário (explorar). _(tags: quotas, disco)_  
019. **Sincronização.** Sincronize `src/`→`dst/` preservando atributos. _(tags: backup, sync)_  
020. **Estrutura padrão via script.** Gere árvore de diretórios a partir de lista. _(tags: automação, fs)_  
021. **Detecção de mudanças.** Capture carimbo de data/hora e compare depois. _(tags: auditoria, fs)_  
022. **Padrões de criação.** Ajuste umask/ACL padrão para nova pasta. _(tags: perms)_  
023. **Normalizar nomes.** Converta espaços em `_` em nomes de arquivos. _(tags: fs, strings)_  
024. **Top consumidores.** Descubra quais subpastas ocupam mais espaço. _(tags: disco, auditoria)_  
025. **Perfis do shell.** Crie templates de `.bashrc`/`$PROFILE`. _(tags: shell, produtividade)_

---

## Nível 2 — Processos, serviços & inicialização — 25 exercícios

026. **Top CPU/RAM.** Liste processos por uso de CPU/memória. _(tags: processos, desempenho)_  
027. **Encerrar por nome/porta.** Finalize processos problemáticos. _(tags: processos, rede)_  
028. **Árvore de processos.** Visualize hierarquia e pais/filhos. _(tags: processos)_  
029. **Serviços habilitados.** Liste serviços e seu tipo de inicialização. _(tags: serviços, boot)_  
030. **(Des)habilitar serviço.** Ative/desative e inicie/paralise imediatamente. _(tags: serviços)_  
031. **Logs de serviço.** Filtre logs recentes de um serviço específico. _(tags: serviços, logs)_  
032. **Criar serviço de script.** Transforme um script em serviço/daemon. _(tags: serviços, automação)_  
033. **Tarefa agendada.** Crie um job diário às 02:00. _(tags: scheduler, automação)_  
034. **Tempo de boot.** Descubra gargalos na inicialização. _(tags: boot, desempenho)_  
035. **Limites de recurso.** Restrinja CPU/mem de um processo. _(tags: processos, quotas)_  
036. **Variáveis de ambiente.** Liste variáveis de um serviço. _(tags: serviços, env)_  
037. **Auto‑restart.** Configure reinício on‑failure com backoff. _(tags: serviços, confiabilidade)_  
038. **Alias/funções.** Crie atalho para inspecionar processos. _(tags: shell, produtividade)_  
039. **Aguardar término.** Espere um PID encerrar e registre tempo. _(tags: processos, automação)_  
040. **Portas em uso.** Liste portas em escuta e processos donos. _(tags: rede, processos)_  
041. **Quem abriu a porta X?** Identifique o serviço pelo PID. _(tags: rede, auditoria)_  
042. **Limites ulimit/kernel.** Exiba limites de arquivo/processo. _(tags: kernel, limites)_  
043. **Auto‑heal.** Script que ressuscita daemon caído. _(tags: automação, serviços)_  
044. **Inventário de serviços.** Exporte serviços e estado para CSV/MD. _(tags: auditoria)_  
045. **Profile de CPU.** Meça CPU por processo a cada 1s (amostragem). _(tags: desempenho)_  
046. **Snapshot & diff.** Compare lista de processos entre T1 e T2. _(tags: auditoria)_  
047. **Tempo de execução.** Cronometre um comando e salve métrica. _(tags: desempenho)_  
048. **Prioridades.** Consulte/ajuste nice/priority class. _(tags: processos)_  
049. **Hooks de boot/shutdown.** Execute scripts em startup/shutdown. _(tags: boot, automação)_  
050. **Health‑check.** Crie verificação com códigos de saída padronizados. _(tags: confiabilidade)_

---

## Nível 3 — Redes & conectividade — 25 exercícios

051. **Endereços e interfaces.** Liste IPs, máscaras e gateways. _(tags: rede, ip)_  
052. **Ping & rota.** Teste latência e caminho até um host. _(tags: rede, diagnóstico)_  
053. **DNS.** Resolva registros A/AAAA/CNAME/MX e TTL. _(tags: dns)_  
054. **Teste de porta.** Verifique conectividade TCP em porta específica. _(tags: rede, tcp)_  
055. **Captura de pacotes.** Capture HTTP/HTTPS de uma interface. _(tags: rede, pcap)_  
056. **Conexões ativas.** Liste sessões TCP/UDP e estados. _(tags: rede)_  
057. **IP estático temporário.** Configure IP/rota e reverta. _(tags: rede, ip)_  
058. **Firewall allow.** Abra porta 8080 para entrada. _(tags: firewall)_  
059. **Latência média.** Colete 20 pings e calcule média e perda. _(tags: rede, métricas)_  
060. **Download via CLI.** Baixe um arquivo e valide hash. _(tags: http, segurança)_  
061. **Proxy.** Teste tráfego HTTP passando por proxy. _(tags: proxy, http)_  
062. **Tabela de rotas.** Exiba rotas e métricas. _(tags: roteamento)_  
063. **Multicast/MTU.** Consulte membros e ajuste MTU para teste. _(tags: rede avançada)_  
064. **Transferência P2P.** Transfira arquivo entre duas máquinas. _(tags: ssh, cópia)_  
065. **Port‑forward.** Faça túnel local 8080→dest:80. _(tags: ssh, rede)_  
066. **Certificado TLS.** Inspecione cadeia/validade de um host. _(tags: tls, segurança)_  
067. **Throughput.** Meça banda com servidor/cliente de teste. _(tags: desempenho, rede)_  
068. **Fragmentação.** Teste PMTU e pacotes “don’t fragment”. _(tags: mtu, diagnóstico)_  
069. **Health de endpoints.** Varra URLs e colete HTTP status. _(tags: http, health)_  
070. **Quedas de rede.** Logue perda de ping em loop por 1h. _(tags: rede, monitoramento)_  
071. **Habilitar/desabilitar NIC.** Ative/desative interface com segurança. _(tags: nic, admin)_  
072. **Descoberta de LAN.** Faça varredura ARP/ICMP em /24. _(tags: rede, descoberta)_  
073. **Banda por processo.** Identifique quem consome mais tráfego. _(tags: rede, desempenho)_  
074. **Failover simples.** Troque para secundário se primário cair. _(tags: alta-disponibilidade)_  
075. **Dump de configuração.** Exporte IPs/DNS/rotas para auditoria. _(tags: auditoria, rede)_

---

## Nível 4 — Usuários, grupos & segurança — 25 exercícios

076. **Criar usuário.** Crie usuário com home e senha expirada. _(tags: users, segurança)_  
077. **Grupos.** Adicione usuário a grupos críticos (sudo/admin). _(tags: groups, privilégio)_  
078. **Auditar grupos.** Liste membros de grupos sensíveis. _(tags: auditoria)_  
079. **Bloquear conta.** Desabilite e reabilite um usuário. _(tags: segurança)_  
080. **Política de senha.** Ajuste complexidade e expiração. _(tags: senha, política)_  
081. **Chave SSH.** Gere chave e habilite login sem senha. _(tags: ssh, segurança)_  
082. **Sudoers/RunAs.** Conceda privilégio mínimo a um comando. _(tags: privilégio mínimo)_  
083. **Auditar ACL de pasta sensível.** Verifique permissões herdadas. _(tags: acl, auditoria)_  
084. **SUID/SGID/ACL ampla.** Detecte binários permissivos. _(tags: perms, risco)_  
085. **Firewall on.** Ative firewall básico e verifique perfis. _(tags: firewall)_  
086. **Regra por app/porta.** Crie allow específico. _(tags: firewall)_  
087. **Criptografia de disco.** Habilite/inspecione LUKS/BitLocker. _(tags: criptografia)_  
088. **Superfície remota.** Revise SSH/RDP e hardenize. _(tags: hardening)_  
089. **Auditoria de login.** Logue logon/logoff e falhas. _(tags: auditoria, segurança)_  
090. **Patching.** Liste atualizações pendentes e aplique. _(tags: atualização, manutenção)_  
091. **Certificados.** Liste emissor/expiração de certs instalados. _(tags: tls, inventário)_  
092. **Anti‑força bruta.** Configure fail2ban/lockout policy. _(tags: segurança)_  
093. **Vulnerabilidades.** Faça varredura básica de hardening. _(tags: segurança, compliance)_  
094. **No‑exec.** Restrinja execução em partição/pasta. _(tags: hardening)_  
095. **Remoção de bloat.** Desinstale softwares e serviços inúteis. _(tags: higiene, segurança)_  
096. **Banners legais.** Configure aviso de login/MOTD. _(tags: compliance)_  
097. **Rotação de senhas de serviço.** Gere e aplique seguras (simulado). _(tags: segredo)_  
098. **Downloads confiáveis.** Valide hashes/assinaturas. _(tags: segurança)_  
099. **Privilégios verificados.** Liste o que um usuário pode executar. _(tags: auditoria)_  
100. **Inventário de contas/grupos.** Exporte para CSV/MD. _(tags: inventário)_

---

## Nível 5 — Logs, monitoramento & troubleshooting — 25 exercícios

101. **Tail em tempo real.** Siga um log do sistema. _(tags: logs)_  
102. **Filtro por tempo.** Filtre logs da última 1h contendo “ERROR”. _(tags: logs, filtro)_  
103. **Contagem por código.** Agrupe e conte padrões `ERR###`. _(tags: logs, regex)_  
104. **Alerta por e‑mail.** Envie notificação ao detectar erro X. _(tags: alertas, automação)_  
105. **Métricas periódicas.** Capture CPU/Mem/Disk e salve CSV. _(tags: monitoramento)_  
106. **Arquivamento.** Comprima logs por data e mova para backup. _(tags: backup, logs)_  
107. **Health JSON.** Gere relatório de 10 checks em JSON. _(tags: health, json)_  
108. **Quem alterou?** Ative auditoria de arquivo e identifique autor. _(tags: auditoria)_  
109. **Discos saudáveis.** Consulte S.M.A.R.T./estado de discos. _(tags: hardware, disco)_  
110. **Latência HTTP/DNS.** Meça e alerte se > limiar. _(tags: rede, monitoramento)_  
111. **I/O por processo.** Identifique top consumidores de I/O. _(tags: desempenho)_  
112. **Coleta de dumps.** Gere core/minidump e resuma. _(tags: debugging)_  
113. **Painel TUI/CLI.** Crie painel simples com métricas. _(tags: dashboard)_  
114. **Simular incidente.** Provoque falha controlada e registre timeline. _(tags: caos, post‑mortem)_  
115. **Relatório diário HTML.** Consolide métricas/logs em HTML. _(tags: reporting)_  
116. **Logs centralizados.** Encaminhe eventos para um coletor. _(tags: siem, centralização)_  
117. **Alertas de segurança.** Detecte tentativas de login falho. _(tags: segurança, alertas)_  
118. **Gargalos de boot.** Liste serviços críticos na inicialização. _(tags: boot, análise)_  
119. **Kit de coleta.** Gere ZIP com evidências (CPU, mem, net, logs). _(tags: forense, suporte)_  
120. **Baseline.** Grave linha de base e compare futuramente. _(tags: baseline, desempenho)_  
121. **Tempo/NTP.** Verifique sincronização e offset. _(tags: tempo, ntp)_  
122. **Alarme de disco.** Alerte se livre < 10%. _(tags: monitoramento)_  
123. **Uso por usuário.** Liste consumo por usuário (CPU/Mem). _(tags: auditoria)_  
124. **Sinal vs ruído.** Ranqueie origens de log por volume. _(tags: observabilidade)_  
125. **Runbook de troubleshooting.** Escreva 3 guias passo a passo. _(tags: documentação)_

---

## Nível 6 — Automação, backups & Infra como Código — 25 exercícios

126. **Carregar `.env`.** Leia pares `KEY=VALUE` e exporte. _(tags: env, automação)_  
127. **Confirmação para ações perigosas.** Implemente `--force`/prompt. _(tags: automação, UX)_  
128. **Inventário em CSV/JSON.** Gere inventário de HW/SO. _(tags: inventário, export)_  
129. **Backup incremental.** Faça espelho com retenção. _(tags: backup, retenção)_  
130. **Backup de banco (simulado).** Gere dump e limpe antigos >7d. _(tags: backup, db)_  
131. **Restauração com verificação.** Restaure e valide hash. _(tags: backup, integridade)_  
132. **Usuários via CSV.** Crie contas a partir de planilha. _(tags: automação, users)_  
133. **Distribuir chaves SSH.** Gere/chaveie hosts automaticamente. _(tags: ssh, automação)_  
134. **Pré‑requisitos de servidor.** Valide RAM/disco/pacotes. _(tags: validação)_  
135. **Mini pipeline local.** Lint → testes → deploy (scripts). _(tags: pipeline)_  
136. **Provisionar serviço web.** Suba página simples (IIS/nginx). _(tags: provisionamento)_  
137. **Templates de config.** Renderize templates a partir de variáveis. _(tags: templates)_  
138. **Rotação de logs.** Comprima e rotacione com retenção. _(tags: logs, retenção)_  
139. **Config pull por Git.** Sincronize configs periodicamente. _(tags: gitops)_  
140. **Canário.** Alerta caso job agendado não rode. _(tags: monitoramento)_  
141. **Hardening pós‑instalação.** Aplique checklist básico. _(tags: hardening, automação)_  
142. **Função de log estruturado.** Padronize logs JSON para scripts. _(tags: logging)_  
143. **Diagrama de dependências.** Gere `.dot` e renderize. _(tags: documentação)_  
144. **Auto‑update de script.** Baixe nova versão e valide checksum. _(tags: atualização)_  
145. **Export/Import de configs.** Salve e restaure configuração de serviço. _(tags: backup config)_  
146. **Parâmetros & help.** Implemente flags e `--help`. _(tags: UX, cli)_  
147. **Testes de script.** Escreva testes automatizados (Bats/Pester). _(tags: testes)_  
148. **Artefatos de release.** Gere zip e changelog versionado. _(tags: release)_  
149. **Idempotência.** Aplique mudanças só quando necessário. _(tags: iac, automação)_  
150. **Runbook de automação.** Documente scripts, parâmetros e rollback. _(tags: documentação)_

---

## Como usar

1. Escolha um nível e siga na ordem.  
2. Resolva os exercícios em **Bash** ou **PowerShell** (ou ambos).  
3. Salve suas soluções em `solutions/NIVEL-XX/NNN_nome.md` ou scripts `.sh`/`.ps1`.  
4. Marque seu progresso no README com ✅.

> Sugestão: 1 nível por semana → **6 semanas** de prática sólida.

---

## Licença

MIT — Use, modifique e compartilhe como quiser.
