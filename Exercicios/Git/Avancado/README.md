# 🎯 Git — Avancado

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_git_plumbing](./01_git_plumbing): Use os comandos de encanamento (plumbing) do Git: hash-object, cat-file, write-tree, commit-tree.
- [02_reimplementar_git](./02_reimplementar_git): Implemente um mini Git do zero em Python ou Go: init, hash-object, cat-file, add, commit.
- [03_custom_merge_driver](./03_custom_merge_driver): Crie um merge driver customizado para arquivos que o Git não sabe mesclar (ex: JSON).
- [04_custom_diff_driver](./04_custom_diff_driver): Crie um diff driver customizado para exibir diferenças semânticas em arquivos binários.
- [05_grafts_replace](./05_grafts_replace): Use git replace para criar grafos de commits alternativos sem modificar o histórico.
- [06_gc_pack_optimization](./06_gc_pack_optimization): Otimize um repositório grande com git gc --aggressive, git repack e pack-refs.
- [07_alternates_sharing](./07_alternates_sharing): Configure Git Alternates para compartilhar object stores entre repositórios.
- [08_partial_clone](./08_partial_clone): Configure partial clone com filtros de blob e tree para repositórios gigantescos.
- [09_git_protocol](./09_git_protocol): Implemente um servidor Git minimalista usando git-upload-pack e git-receive-pack via SSH.
- [10_git_daemon](./10_git_daemon): Configure o git daemon para servir repositórios via protocolo Git nativo.
- [11_virtual_filesystem](./11_virtual_filesystem): Explore o GVFS (Git Virtual File System) para repositórios de escala de enerprise.
- [12_commit_graph](./12_commit_graph): Use e mantenha o commit-graph file para acelerar traversal de histórico.
- [13_multi_pack_index](./13_multi_pack_index): Configure o multi-pack-index (MIDX) para pesquisas mais rápidas em repositórios grandes.
- [14_feature_reachability](./14_feature_reachability): Implemente um script que encontra todos os commits que introduziram uma feature específica.
- [15_git_cinnabar](./15_git_cinnabar): Use git-cinnabar para interoperar com repositórios Mercurial.
- [16_git_workspace](./16_git_workspace): Configure git worktrees com sparse-checkout para uma estratégia monorepo escalável.
- [17_fsck_repair](./17_fsck_repair): Use git fsck para detectar corrupção e repare o repositório com ferramentas de baixo nível.
- [18_hooks_framework](./18_hooks_framework): Construa um framework de hooks Git reutilizáveis instalável via npm ou script.
- [19_semantic_versioning_ci](./19_semantic_versioning_ci): Configure um pipeline completo de semantic versioning com changelogs automáticos.
- [20_git_annex](./20_git_annex): Use git-annex para gerenciar arquivos grandes distribuídos em múltiplos backends.
- [21_merge_queue](./21_merge_queue): Configure o Merge Queue do GitHub para serializar PRs e evitar the merge train problem.
- [22_stacked_diffs](./22_stacked_diffs): Implemente um workflow de Stacked Diffs (como no Facebook) usando git-stack ou Graphite.
- [23_bisect_regression_suite](./23_bisect_regression_suite): Construa uma suíte de testes de regressão automáticos para uso com git bisect.
- [24_git_credential_helper](./24_git_credential_helper): Implemente um Git Credential Helper customizado para autenticação em sistemas internos.
- [25_repository_mining](./25_repository_mining): Faça repository mining: extraia estatísticas, métricas de qualidade e hotspots do histórico Git.
- [26_repo_archaeology](./26_repo_archaeology): Faça arqueologia de repositório: rastreie a origem de uma decisão de arquitetura no histórico.
- [27_git_split_monolith](./27_git_split_monolith): Divida um monolito Git em múltiplos repositórios com histórico preservado usando filter-repo.
- [28_signed_pushes](./28_signed_pushes): Configure verificação de assinatura no lado do servidor para bloquear pushes não assinados.
- [29_git_attributes_avancado](./29_git_attributes_avancado): Use .gitattributes para normalização de line endings, linguist overrides e merge strategies por arquivo.
- [30_git_at_scale](./30_git_at_scale): Pesquise e documente como empresas (Google, Facebook, Microsoft) escalam o Git para repositórios de bilhões de objetos.
