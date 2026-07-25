# 🎯 Git — Intermediario

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_rebase_interativo](./01_rebase_interativo): Use git rebase -i para squash, reword, edit e reorder de commits.
- [02_rebase_upstream](./02_rebase_upstream): Mantenha sua feature branch atualizada com a main usando rebase (sem merge commits).
- [03_git_bisect](./03_git_bisect): Use git bisect para encontrar o commit que introduziu um bug com busca binária.
- [04_git_hooks_precommit](./04_git_hooks_precommit): Crie um pre-commit hook que roda o linter e impede commit se houver erros.
- [05_git_hooks_commit_msg](./05_git_hooks_commit_msg): Crie um commit-msg hook que valida o formato Conventional Commits.
- [06_reflog_recuperacao](./06_reflog_recuperacao): Use git reflog para recuperar commits ou branches deletados acidentalmente.
- [07_filter_branch_history](./07_filter_branch_history): Use git filter-repo para remover um arquivo sensível (senha) do histórico completo.
- [08_merge_strategies](./08_merge_strategies): Explore as estratégias de merge: ours, theirs, octopus e subtree.
- [09_rerere](./09_rerere): Configure git rerere para reutilizar resoluções de conflitos que você já fez antes.
- [10_git_grep](./10_git_grep): Use git grep para buscar padrões no código rastreado pelo Git de forma eficiente.
- [11_monorepo_git](./11_monorepo_git): Gerencie um monorepo: use sparse-checkout, pathspec e filtros de subdiretório.
- [12_workflow_gitflow](./12_workflow_gitflow): Implemente o GitFlow: branches main, develop, feature, release e hotfix.
- [13_workflow_trunk_based](./13_workflow_trunk_based): Configure Trunk Based Development com feature flags e CI gates.
- [14_proteger_branches](./14_proteger_branches): Configure Branch Protection Rules no GitHub: requer PRs, reviews e checks.
- [15_codeowners](./15_codeowners): Configure o arquivo CODEOWNERS para revisão automática por área do código.
- [16_release_automatico](./16_release_automatico): Configure o Semantic Release ou Release Please para publicação automática.
- [17_git_archive](./17_git_archive): Use git archive para exportar um snapshot do código sem o histórico.
- [18_signing_commits](./18_signing_commits): Configure assinatura de commits com GPG ou SSH para verificar autoria.
- [19_split_repository](./19_split_repository): Extraia um subdiretório para um novo repositório preservando o histórico (filter-repo).
- [20_merge_repositorios](./20_merge_repositorios): Junte dois repositórios independentes em um, preservando o histórico de ambos.
- [21_patch_format](./21_patch_format): Gere patches com git format-patch e aplique-os com git am.
- [22_diff_avancado](./22_diff_avancado): Use git diff --stat, --word-diff, --color-moved e compare branches remotas.
- [23_blame_avancado](./23_blame_avancado): Use git blame -C para rastrear origem de linhas copiadas entre arquivos.
- [24_notes_git](./24_notes_git): Use git notes para adicionar metadados a commits sem alterar o SHA.
- [25_shallow_clone](./25_shallow_clone): Use git clone --depth=1 e --filter=blob:none para clonar repositórios grandes rapidamente.
- [26_git_lfs](./26_git_lfs): Configure Git LFS para versionar arquivos binários grandes (imagens, vídeos, modelos ML).
- [27_resolucao_conflito_avancada](./27_resolucao_conflito_avancada): Resolva conflitos complexos usando git mergetool, vimdiff e estratégias de 3 vias.
- [28_git_bisect_automatico](./28_git_bisect_automatico): Automatize o git bisect com um script de teste para encontrar regressões.
- [29_continuous_integration_git](./29_continuous_integration_git): Configure um pipeline CI/CD (GitHub Actions) que valida commits e PRs.
- [30_git_internals_objetos](./30_git_internals_objetos): Explore os objetos internos do Git: blobs, trees, commits e tags usando git cat-file.
