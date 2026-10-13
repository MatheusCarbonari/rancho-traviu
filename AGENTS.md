# Diretrizes para agentes

- Implemente mudanças pequenas, incrementais e limitadas ao escopo da tarefa.
- Siga as convenções oficiais do Astro e consulte a [documentação](https://docs.astro.build) e os guias relacionados antes de alterar rotas, componentes, conteúdo, estilos, integrações ou internacionalização.
- Priorize HTML semântico, CSS responsivo, abordagem mobile-first e JavaScript mínimo.
- Priorize acessibilidade, desempenho e SEO.
- Não introduza dependências desnecessárias.
- Não adicione backend, autenticação ou frameworks de interface sem necessidade justificada.
- Não invente informações sobre o Rancho Traviú; sinalize quando conteúdo real estiver ausente.
- Não realize commits automaticamente.

## Testes e validações

- Priorize verificações proporcionais aos riscos e à complexidade de cada alteração.
- Após alterações no site, execute `npm run build` e `git diff --check`.
- Conforme os componentes forem implementados, confira links, estrutura semântica e acessibilidade.
- Sempre que possível, valide visualmente o comportamento mobile e desktop.
- Informe os resultados das validações e declare qualquer verificação que não puder ser realizada.
- Avalie a adoção de testes automatizados quando surgirem funcionalidades que os justifiquem. Ferramentas como Astro Check e Playwright poderão ser incorporadas posteriormente, diante de uma necessidade concreta.

## Servidor de desenvolvimento

Inicie o servidor em segundo plano com:

```sh
astro dev --background
```

Gerencie o processo com `astro dev status`, `astro dev logs` e `astro dev stop`.
