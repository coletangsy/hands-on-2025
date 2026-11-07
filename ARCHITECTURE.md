# hands-on-2025 architecture

`hands-on-2025` is a practice repository rather than a deployable application.
Its units of work are notebooks grouped by subject, with code, explanations,
and small local examples kept close to the notebook.

## Notebook groups

- `Code_Practice/` contains coding-test and data-structure practice notebooks,
  including preparation and Codility exercises.
- `Trad_ML/CTR-prediction/` contains a click-through-rate prediction exercise.
- `Trad_ML/Fraud-detection/` contains a fraud-detection notebook and its local
  README.

The notebooks are the source of truth for the exercises. They may read local
datasets or package-managed examples, but the repository does not define a
shared runtime service, persistent database, or release artifact. Keep large
datasets and generated notebook outputs local unless a specific exercise
requires a tracked example.

## Maintenance

When adding an exercise, place it under the closest subject directory and add a
nearby README only when setup or data provenance needs explanation. Update this
overview if a new subject or shared execution convention is introduced.
