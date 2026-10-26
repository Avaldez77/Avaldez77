# Avaldez77 | Data & Process Automation

I build reproducible workflows that connect data analysis, statistical
modeling, data engineering, and process automation. This portfolio brings
together project case studies and runnable examples, with assumptions,
validation, and limitations documented.

Los cuatro portafolios muestran distintas partes de un mismo flujo: preparar y
validar datos, analizarlos, convertirlos en decisiones medibles y automatizar
tareas repetibles. Los casos y ejercicios están identificados con claridad;
los ejemplos ilustrativos no se presentan como resultados de clientes.

## Portfolio map

| Area | Focus | Portfolio |
| --- | --- | --- |
| **Data Analytics** | Operational KPIs, cohort analysis, experiment evaluation, and reporting | [Data Analytics Portfolio](https://github.com/Avaldez77/Data-Analytics-Portafolio) |
| **Data Engineering & Big Data** | SQL, data quality, event pipelines, analytical modeling, SQLite, and DuckDB | [Data Engineering Portfolio](https://github.com/Avaldez77/Data-Engineering-Big-Data-Portafolio) |
| **Data Science** | Applied statistics, model validation, forecasting, impact evaluation, and survival analysis in R | [Data Science Portfolio](https://github.com/Avaldez77/Data-science-Portafolio) |
| **RPA & Process Automation** | Python workflow validation, invoice reconciliation, retries, audit trails, and safe dry runs | [RPA Portfolio](https://github.com/Avaldez77/RPAs-Portafolio) |

## Selected runnable work

- [Experiment analysis](https://github.com/Avaldez77/Data-Analytics-Portafolio/tree/main/Exercises/Experiment%20Analysis):
  conversion rates, absolute and relative lift, confidence intervals, and a
  two-sided test.
- [DuckDB event warehouse](https://github.com/Avaldez77/Data-Engineering-Big-Data-Portafolio/tree/main/Exercises/DuckDB%20Warehouse):
  typed ingestion, quality quarantine, and daily analytical outputs.
- [Impact evaluation in R](https://github.com/Avaldez77/Data-science-Portafolio/tree/main/Exercises/Impact%20Evaluation)
  and [time-to-event analysis](https://github.com/Avaldez77/Data-science-Portafolio/tree/main/Exercises/Time-to-Event%20Analysis):
  explicit assumptions, validation, and reproducible methods.
- [Invoice reconciliation](https://github.com/Avaldez77/RPAs-Portafolio/blob/main/rpa_demo/reconciliation.py):
  deterministic matching, exception categories, and no external side effects.

## Engineering practices

- Keep inputs, business assumptions, and output schemas explicit.
- Validate malformed, missing, duplicate, and out-of-range data.
- Make local examples repeatable and test important success and failure paths.
- Use CI to execute portfolio workflows and catch regressions.
- Keep credentials and private enterprise integrations out of runnable demos.
- State limitations and avoid claiming production impact without measured,
  verifiable evidence.

## Tools represented in these projects

Python, R, SQL, pandas, SciPy, DuckDB, SQLite, and `survival`.

For run commands, package requirements, and project-specific caveats, see each
portfolio README linked above.
