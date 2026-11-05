# Fluma — OTA público da F. Labs

**Fluma** é um aplicativo Android gratuito e sem anúncios, com conteúdos educativos e recursos opcionais de apoio cotidiano relacionados ao transtorno de personalidade borderline (TPB).

## Última prévia técnica disponível

- **Versão:** **0.9.2** · `versionCode 51` · publicação em **05/11/2026**.
- **Release:** [Fluma v0.9.2](https://github.com/fsfalch/Fluma-Releases/releases/tag/v0.9.2).
- **APK assinado:** [Fluma-0.9.2.apk](https://github.com/fsfalch/Fluma-Releases/releases/download/v0.9.2/Fluma-0.9.2.apk).
- **Manifesto OTA:** [update.json](https://github.com/fsfalch/Fluma-Releases/blob/main/update.json) (ver `versionName`, `versionCode`, URL e SHA-256).
- **SHA-256:** `506e7f505d49bf4aa7e1d5107b3ab158c697e8e4cbb9c810560e3b8c15948bb9`.

A release 0.9.2 fortalece as verificações de conta Google antes de restaurações e a proteção contra downloads OTA simultâneos. Os backups são opcionais, criptografados antes do envio; **a chave de recuperação fica na mesma conta Google que a cópia**, de modo que não há criptografia de ponta a ponta contra o provedor.

## Atualização

Na versão instalada, abra **Perfil → Aplicativo → Verificar atualizações** (ou o botão equivalente). Confirme a atualização no instalador Android. **Não desinstale a versão anterior nem limpe o armazenamento**; confirme seu backup antes de atualizar.

O app confere SHA-256, pacote, versão e certificado do APK. A instalação depende da sua confirmação. Releases antigas permanecem disponíveis no histórico para rastreabilidade, mas não devem ser instaladas por cima de versões mais recentes como downgrade.

## Estágio do produto

**Prévia técnica pública**, com **homologação funcional da 0.9.2 concluída no Android real em 05/11/2026 (13/13 testes aprovados, sem falhas relatadas)**. Isso não equivale à aprovação clínica, de segurança ou regulatória. Testes negativos de OTA e backup automático, restauração com OAuth Google em instalação independente, auditorias LGPD/segurança, revisão clínica dos artigos e análise jurídica/regulatória **continuam pendentes**.

Fluma **não diagnostica, não presta psicoterapia, não prevê crises e não substitui profissionais ou serviços de emergência**. Em perigo imediato no Brasil, contate o serviço de emergência adequado (por exemplo, SAMU 192).

Este repositório publica apenas APKs e metadados públicos de distribuição. Código-fonte, keystore, segredos OAuth, tokens, dados de Diário e outras informações pessoais **não são publicados aqui**.

© F. Labs.
