Résolution du conflit - Mission 6

1. J'ai tapé git merge feature/menu depuis main.
2. Git m'a affiché une erreur de conflit sur index.html.
3. Le problème venait du footer qui était différent sur les deux branches.
4. J'ai ouvert index.html dans VS Code et j'ai vu les marqueurs <<<<<< et >>>>>>.
5. La partie HEAD c'était le footer de main avec l'adresse et l'email de contact.
6. La partie feature/menu avait juste l'email de réservation.
7. J'ai effacé tous les marqueurs de conflit à la main.
8. J'ai gardé les deux footers en un seul avec les trois informations dedans.
9. J'ai fait git add index.html pour dire à Git que j'avais réglé le problème.
10. J'ai fini avec git commit pour valider le merge.