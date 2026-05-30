
# Afrique — Market Research & Business Development

Ce dépôt documente notre recherche de marché pour une firme canadienne de conseil IT/data/AI souhaitant identifier des opportunités concrètes en Afrique.

L’objectif n’est pas seulement de comprendre le marché, mais de produire des actions exploitables : appels d’offres à suivre, organisations à cibler, partenaires à contacter, pays prioritaires, offres commerciales à préparer, preuves et sources vérifiées et un pipeline de développement commercial.

## Structure

```
Africa/
├── README.md
├── project_charter.md
├── research_log.md
├── decision_log.md
├── glossary.md
│
├── 00_admin/
│   ├── team_roles.md
│   ├── ai_tools_roles.md
│   ├── weekly_workflow.md
│   ├── quality_rules.md
│   └── source_policy.md
│
├── 01_sources/
│   ├── source_index.md
│   ├── procurement_platforms.md
│   ├── saved_searches.md
│   ├── source_template.md
│   └── raw_notes/
│
├── 02_market_overview/
│   ├── africa_market_summary.md
│   ├── priority_segments.md
│   ├── donor_landscape.md
│   ├── buyer_types.md
│   └── market_gaps_from_claude.md
│
├── 03_country_research/
│   ├── country_scoring_model.md
│   ├── country_research_template.md
│   ├── francophone_africa/
│   ├── anglophone_africa/
│   └── north_africa/
│
├── 04_organizations/
│   ├── organization_template.md
│   ├── multilaterals/
│   ├── eu_agencies/
│   ├── pan_african/
│   └── private_sector/
│
├── 05_opportunities/
│   ├── opportunity_pipeline.md
│   ├── opportunity_template.md
│   ├── active/
│   ├── upcoming/
│   ├── reference_patterns/
│   └── archived/
│
├── 06_partners/
│   ├── partner_strategy.md
│   ├── partner_template.md
│   ├── international_primes.md
│   ├── local_firms_by_country.md
│   ├── hisp_nodes.md
│   └── ngos_implementers.md
│
├── 07_offers/
│   ├── service_catalog.md
│   ├── data_governance_offer.md
│   ├── bi_dashboard_offer.md
│   ├── ai_readiness_offer.md
│   ├── dhis2_mis_offer.md
│   └── capability_statement/
│
├── 08_validation/
│   ├── validation_croisee.md
│   ├── claims_register.md
│   ├── source_confidence_matrix.md
│   └── red_flags.md
│
├── 09_actions/
│   ├── 30_60_90_plan.md
│   ├── registration_checklist.md
│   ├── outreach_tracker.md
│   ├── bid_decision_log.md
│   └── weekly_sprint_tasks.md
│
├── 10_prompts/
│   ├── prompt_master_orchestrateur.md
│   ├── prompt_country_research.md
│   ├── prompt_organization_research.md
│   ├── prompt_opportunity_extraction.md
│   ├── prompt_validation_gemini.md
│   ├── prompt_validation_deepseek.md
│   ├── prompt_notebooklm_tender_analysis.md
│   └── prompt_copilot_repo_maintenance.md
│
└── 99_archive/
```

## Workflow de recherche

Chaque recherche suit le processus suivant :

1. **Collecte** : collecte de sources officielles (World Bank, AfDB, UNGM, etc.).
2. **Analyse initiale** : Claude produit une première fiche structurée en Markdown.
3. **Validation croisée** : Gemini vérifie les affirmations factuelles et Deepseek cherche des contradictions.
4. **Arbitrage** : ChatGPT oriente la décision et classe les opportunités.
5. **Action commerciale** : les opportunités pertinentes sont ajoutées au pipeline et les actions sont tracées.

Consultez `project_charter.md` pour les objectifs détaillés et `weekly_workflow.md` pour la routine hebdomadaire.
