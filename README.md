# 🗺️ KML Viewer Angola — HubGEO

Aplicação web para visualização de arquivos KML sobre Angola, com suporte a múltiplos mapas base, exportação de mapas em PDF e geração de relatórios mensais técnicos no padrão HubGEO.

---

## ✨ Funcionalidades

- **Upload de arquivos KML** — suporte a múltiplos arquivos simultaneamente
- **Mapas base** — OpenStreetMap, Satélite Esri, Google Satellite, Google Hybrid e OpenTopoMap
- **Visualização interativa** — tooltips, popups com atributos, zoom e pan
- **Gestão de camadas** — ocultar, mostrar, remover e zoom para cada camada
- **Tabela de atributos** — visualização e navegação pelos dados do KML
- **Exportar Mapa PDF** — layout A4 paisagem com título, seta norte, escala e legenda
- **Relatório Mensal PDF** — modelo técnico HubGEO com capa, tabela de pontos, mapa e conclusões

---

## 🚀 Como usar

### Opção 1 — Direto no navegador
Basta abrir o arquivo `index.html` no navegador (Chrome, Firefox ou Edge).  
> ⚠️ Requer conexão à internet para carregar os tiles do mapa base.

### Opção 2 — Deploy no Vercel
1. Faça fork ou clone este repositório
2. Acesse [vercel.com](https://vercel.com) e importe o projeto
3. O Vercel detecta automaticamente como site estático — clique em **Deploy**

---

## 📁 Estrutura do Projeto

```
kml-viewer-angola/
│
├── index.html        # Aplicação completa (single file)
└── README.md         # Documentação
```

---

## 🛠️ Tecnologias

| Biblioteca | Versão | Uso |
|---|---|---|
| [Leaflet.js](https://leafletjs.com/) | 1.9.4 | Mapa interativo |
| [toGeoJSON](https://github.com/mapbox/togeojson) | 0.16.0 | Conversão KML → GeoJSON |
| [jsPDF](https://github.com/parallax/jsPDF) | 2.5.1 | Geração de PDF |
| [html2canvas](https://html2canvas.hertzen.com/) | 1.4.1 | Captura do mapa |

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👤 Autor

Desenvolvido por **HubGEO – Estudos e Projectos Lda**  
📧 Contacto: fs@fsgeotcnologias.com / flaviocartografia@gmail.com

---

> Feito com 🗺️ para Angola

