# src/pipelines

Stage implementations (pure functions) the DAG calls:
- ingredient_ingest, recipe_resolver, plan_renderer, etc.
No global state; deterministic inputs → deterministic outputs.
