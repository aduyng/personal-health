Time Series Data Export

The Time Series export provides a detailed timeline of your tracked activity.

Files Included:
----------

cardio_acute_chronic_workload_ratio_YYYY-MM-DD.csv - Where YYYY-MM-DD is the starting date for the entries in the file.

Cardio acute chronic workload ratio represents how recent load compares with longer term regular load. Used to determine if the user is over or under-training.
Each entry has the following values:

    timestamp                         - Date at which the entry was logged in UTC.
    ratio                             - Cardio acute chronic workload ratio value.
    label                             - Label interpreting the ratio value. Values can be UNDER_TRAINING, OPTIMAL_TRAINING or OVER_TRAINING.