# Banca Firme — instaladores

Este repositório guarda **apenas os instaladores** do Banca Firme, publicados em [Releases](../../releases).
O próprio app consulta este repositório para se atualizar sozinho.

**Banca Firme** é um app de desktop (Windows) para acompanhar e gerir a banca de trade esportivo na Polymarket:
sincroniza as apostas da sua carteira direto da Polymarket, mostra dashboard, relatórios e gestão de despesas.
Todos os dados ficam no seu computador; nenhuma chave privada é pedida.

## Instalar

1. Baixe o `BancaFirme-Setup-<versão>.exe` do release mais recente.
2. O instalador não tem assinatura digital: o Windows mostrará "editor desconhecido".
   Clique em **Mais informações → Executar assim mesmo**.
3. Depois de instalado, o app baixa as novas versões automaticamente e mostra o botão **Atualizar** no topo.

Cada atualização é baixada por HTTPS e conferida pelo hash SHA-512 publicado no `latest.yml` antes de ser instalada.
