# Diretrizes para agentes

- Implemente mudanças pequenas, incrementais e limitadas ao escopo da tarefa.
- Siga as convenções oficiais do Astro e consulte a [documentação](https://docs.astro.build) e os guias relacionados antes de alterar rotas, componentes, conteúdo, estilos, integrações ou internacionalização.
- Priorize HTML semântico, CSS responsivo, abordagem mobile-first e JavaScript mínimo.
- Priorize acessibilidade, desempenho e SEO.
- Não introduza dependências desnecessárias.
- Não adicione backend, autenticação ou frameworks de interface sem necessidade justificada.
- Não invente informações sobre o Rancho Traviú; sinalize quando conteúdo real estiver ausente.
- Valide as alterações com os comandos adequados, incluindo `npm run build` quando aplicável, e informe os resultados.
- Não realize commits automaticamente.

## Servidor de desenvolvimento

Inicie o servidor em segundo plano com:

```sh
astro dev --background
```

Gerencie o processo com `astro dev status`, `astro dev logs` e `astro dev stop`.
