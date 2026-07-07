# Caderno de Expedição · Chuí → Montevidéu (ida e volta)

App de planejamento para o cicloturismo solo Chuí (RS) → Montevidéu e volta (~780 km) pela Ruta 10.
Três abas: **Equipamento**, **Organização** (preparo + treino) e **Itinerário** (mapa + rota).

Versão **online**: sempre carrega a última versão publicada (sem cache travado). Os dados que você edita ficam salvos no navegador; o botão **Gerar PDF** leva tudo pra estrada, offline.

---

## Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | O app inteiro. |
| `icon-192.png` | Favicon (ícone na aba do navegador). |
| `README.md` | Este guia. |

Suba os três juntos, na mesma pasta.

---

## Publicar no GitHub Pages

1. Em https://github.com → **New repository** → nome ex.: `diariodebordo` → **Public** → **Create**.
2. **uploading an existing file** → arraste os arquivos → **Commit changes**.
3. **Settings → Pages → Source** → **Deploy from a branch** → **main** / **/ (root)** → **Save**.
4. Acesse `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

Para atualizar depois: suba o `index.html` novo por cima. Por ser online, ao recarregar já aparece a versão nova (se hesitar, **Ctrl+Shift+R**).

---

## Gerar o PDF

Botão **Gerar PDF** no topo. Ele monta um documento com **o estado atual** — o que você marcou, seus preços, suas metas e pontos — em equipamento, organização/treino e itinerário. Salve no celular ou imprima: é o seu backup para a estrada, onde não há sinal.

> Precisa de conexão na primeira vez (para carregar a biblioteca). O **mapa interativo** também. A navegação de verdade na estrada é de um app de mapas offline (OsmAnd / Maps.me).

---

## Backup dos dados

Os dados vivem no navegador deste aparelho. Use **Exportar / Importar backup** (`.json`) para migrar entre aparelhos ou antes de limpar o navegador.
