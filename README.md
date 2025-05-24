# task1_round2_DD

- **Problem statement:** https://app.logicloom.iitmparadox.org/round2/4

```
--- Deliverables

>> We will be using GitHub classroom to track your progress.

>> Participants SHOULD REFRAIN from creating any further repos or upload files anywhere else.

> Codes (pre-processing pipeline, model building and testing) - in `main.py` file
> Test run file (best run, in .csv format) - upload a `preds.csv` file
```

## Timeline

- Release of train data: 23rd May 2025
- Training & validation phase starts (teams can optimize their models based on validation performance): 23rd May 2025
- Release of unlabelled test data, testing phase starts: 26th May 2025
- Deadline to submit final runs: 27th May 2025

> There won't be a separate validation dataset. The train set has enough rows, split it for validation purpose.

> We will provide an interface to test-run your model performance on the main test data any number of times before you submit your final prediction file. This will help you optimize your model performance & submit the best run.

> We will compute the model performance by calculating the macro avg. F1-score on the predicted labels (hazard & product) using the annotated labels (hazards-type & product-category) as ground truth.

- Please make sure that your test run file adheres to the correct format and contains the correct column headers (especially the ID and prediction column names - hazard and product), incase of any mismatch our system will fail to evaluate your submissions.
