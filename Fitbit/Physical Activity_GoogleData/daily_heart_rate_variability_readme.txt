Time Series Data Export

The Time Series export provides a detailed timeline of your tracked activity.

Files Included:
----------

daily_heart_rate_variability_YYYY-MM-DD.csv                 - Where YYYY-MM-DD is the starting date for the entries in the file.

Each entry has the following values:

    timestamp                         - Date and time at which the entry was logged.
    average heart rate variability milliseconds                            - The average of a user's heart rate variability during sleep. Heart rate variability is calculated as the root mean square of successive differences (RMSSD) of heartbeat intervals.
    non rem heart rate beats per minute                            - Non-REM heart rate
    entropy                            - The Shanon entropy of heartbeat intervals.
    deep sleep root mean square of successive differences milliseconds                            - The root mean square of successive differences (RMSSD) of heartbeat intervals during deep sleep.