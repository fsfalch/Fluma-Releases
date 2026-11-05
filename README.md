# Fluma — OTA público da F. Labs

**Fluma** é um aplicativo Android gratuito e sem anúncios, com conteúdos educativos e recursos opcionais de apoio cotidiano relacionados ao transtorno de personalidade borderline (TPB).

## Última prévia técnica disponível

- **Versão:** **0.9.3** · `versionCode 52` · publicação em **05/11/2026**.
- **Release:** [Fluma v0.9.3](https://github.com/fsfalch/Fluma-Releases/releases/tag/v0.9.3).
- **APK assinado:** [Fluma-0.9.3.apk](https://github.com/fsfalch/Fluma-Releases/releases/download/v0.9.3/Fluma-0.9.3.apk).
- **Manifesto OTA:** [update.json](https://github.com/fsfalch/Fluma-Releases/blob/main/update.json) (ver `versionName`, `versionCode`, URL e SHA-256).
- **SHA-256:** `01bf906d31b7a4e7b23913c5dfa55f4de72ec258b88da77fc25442b726b7dbf7`.

A release 0.9.3 traz cinco infográficos/fluxogramas vetoriais offline em artigos educativos, cartões visuais nos exercícios Grounding e Dar nome e respiração com pausa, Brisa e redução de movimento. A animação é opcional e desligada por padrão. Os recursos de segurança da 0.9.2 continuam presentes. Backups são opcionais e criptografados antes do envio; **a chave de recuperação fica na mesma conta Google que a cópia**, portanto não há criptografia de ponta a ponta contra o provedor.

## Atualização

Na versão instalada, abra **Perfil → Aplicativo → Verificar atualizações** (ou o botão equivalente). Confirme a atualização no instalador Android. **Não desinstale a versão anterior nem limpe o armazenamento**; confirme seu backup antes de atualizar.

O app confere SHA-256, pacote, versão e certificado do APK. A instalação depende da sua confirmação. Releases antigas permanecem disponíveis no histórico para rastreabilidade, mas não devem ser instaladas por cima de versões mais recentes como downgrade.

## Estágio do produto

**Prévia técnica pública 0.9.3, com homologação funcional dos novos recursos aprovada pelo proprietário em Android real (12/12 testes em 05/11/2026).** Os infográficos, animações, fluxos e regressões funcionaram nos cenários testados; o proprietário ainda enviará detalhes de possíveis refinamentos visuais. CI, emulador fictício, APK assinado e OTA passaram anteriormente. A versão anterior 0.9.2 também possui aceite funcional próprio (13/13 e TalkBack 5/5). **Não houve validação clínica independente, auditoria formal de acessibilidade, segurança ou regulação**; os gates especializados permanecem abertos. Testes negativos de OTA e backup automático, restauração com OAuth Google em instalação independente, auditorias LGPD/segurança, revisão clínica dos artigos e análise jurídica/regulatória **continuam pendentes**.

Fluma **não diagnostica, não presta psicoterapia, não prevê crises e não substitui profissionais ou serviços de emergência**. Em perigo imediato no Brasil, contate o serviço de emergência adequado (por exemplo, SAMU 192).

Este repositório publica apenas APKs e metadados públicos de distribuição. Código-fonte, keystore, segredos OAuth, tokens, dados de Diário e outras informações pessoais **não são publicados aqui**.

© F. Labs.
