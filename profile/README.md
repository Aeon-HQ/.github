<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/header/graph.svg?title=AEON%20Systems&subtitle=Logiciels%20et%20intelligence%20artificielle%20souverains&mode=dark&align=left&font=geist-mono&border=false" /><img alt="AEON Systems" src="https://shieldcn.dev/header/graph.svg?title=AEON%20Systems&subtitle=Logiciels%20et%20intelligence%20artificielle%20souverains&mode=light&align=left&font=geist-mono&border=false" /></picture>
</p>

<p align="center">
  <img alt="France" src="https://shieldcn.dev/badge/concu-en-France.svg?variant=branded&size=xs" />
  <img alt="Rust" src="https://shieldcn.dev/badge/Rust-F74C00.svg?variant=branded&size=xs&logo=rust" />
  <img alt="TypeScript" src="https://shieldcn.dev/badge/TypeScript-3178C6.svg?variant=branded&size=xs&logo=typescript" />
  <img alt="C#" src="https://shieldcn.dev/badge/.NET-512BD4.svg?variant=branded&size=xs&logo=dotnet" />
  <img alt="Go" src="https://shieldcn.dev/badge/Go-00ADD8.svg?variant=branded&size=xs&logo=go" />
  <img alt="PostgreSQL" src="https://shieldcn.dev/badge/PostgreSQL-4169E1.svg?variant=branded&size=xs&logo=postgresql" />
</p>

<div align="center">

**Une base technique unique, hébergée en France. Nos produits partagent le même socle : ce qu'on corrige sur l'un profite aux autres, sans les redéployer. C'est ce qui permet à une petite équipe de tenir plusieurs logiciels de qualité industrielle.**

</div>

---

## Les produits

| Produit | Ce qu'il fait | Statut |
| :-- | :-- | :-- |
| **StrucTime Gestion** | Gestion d'entreprise pour le bâtiment et les services — devis, chantiers, achats, paie, comptabilité, facturation électronique | `Production` |
| **Furnace** | Moteur de jumeau numérique et de simulation physique | `Développement` |
| **Sphinx** | Générateur de mondes synthétiques et de scénarios d'entraînement | `Développement` |
| **StrucTime LWM** | *Large World Model* pour la dynamique des systèmes | `Recherche` |
| **StrucTime 7B** | Modèle de langage souverain, entraîné *from scratch* | `Recherche` |

## Le socle

Ce qui rend le reste possible. Deux moitiés, et la distinction commande tout :

Les **services** portent un état et vivent hors des produits. On les corrige une fois, tous les
logiciels en profitent — sans qu'aucun ne soit redéployé. Le **framework** est la bibliothèque mince
que chaque produit compile avec lui : il fournit le démarrage, la configuration, le routage, les
erreurs, l'observabilité, et les clients typés des services.

```
   PRODUIT  (le métier, et rien d'autre)
        │
   framework          la bibliothèque, mince et versionnée
        │
   ─────┴─────────────────────────────────────────────────
   auth · tenants · billing · files · notify · print      les services, opérés à part
```

| Dépôt | Ce qu'il porte |
| :-- | :-- |
| **auth** | Le moteur d'identité — OAuth 2.0, OIDC, jetons de service, clés ES256 |
| **tenants** | Les espaces clients, leurs membres, leurs consentements |
| **billing** | Abonnements, formules, essais, échéances, moyens de paiement |
| **files** | Le dépôt de fichiers — empreintes, idempotence, liens à durée limitée |
| **notify** | Les messages sortants et le suivi de leur remise |
| **print** | Le rendu de documents, reproductible à l'octet près |
| **framework** | La base de départ de chaque logiciel |
| **communs** | Le vocabulaire partagé : erreurs normalisées, horodatage, jetons |

## Comment on travaille

**Correct est structurel, jamais disciplinaire.** Si une règle ne peut être tenue qu'à la main, on la
rend impossible par construction — un état invalide qu'on ne peut pas représenter vaut mieux que dix
validations qu'il faut penser à appeler.

**Une garde qu'on n'a pas vue échouer ne prouve rien.** Chaque protection est cassée volontairement
pour vérifier qu'elle rougit. Une épreuve qui ne peut pas échouer est une décoration.

**On mesure, on ne suppose pas.** Un raisonnement juste sur une bibliothèque qu'on n'a pas ouverte
reste un raisonnement. Les nombres d'un rapport viennent d'une exécution, ou ils n'y sont pas.

**On dit ce qu'on n'a pas prouvé.** Chaque livraison nomme ses trous. C'est la partie du rapport qui
sert le plus, et celle qu'on lit en premier.

## Conformité

Conçu pour le droit français, et pas seulement traduit : plan comptable, TVA, paie, et la réforme de
la **facturation électronique 2026** — raccordement à une plateforme agréée, e-reporting, formats
Factur-X et UBL.

Hébergement en France, chez un opérateur français.

<div align="center">
<br />
<sub><a href="https://aeon-systems.fr">aeon-systems.fr</a> &nbsp;·&nbsp; <a href="https://structime.app">structime.app</a> &nbsp;·&nbsp; contact@aeon-systems.fr</sub>
</div>
