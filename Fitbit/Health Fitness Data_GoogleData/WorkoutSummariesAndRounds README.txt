 Workout Summaries

The below section is dedicated to the exported data of the Workout Summaries data domain.
Workout Summaries are sent by the wearables device, that support the new Run functionality, to the Backend at the end of the workout and contain aggregated data for the whole workout.

Files Included:
----------

WorkoutSummariesAndRounds.csv

The data for workout summaries

    workout_name                                    - name of the workout, e.g. 'bench press workout'
    workout_summary_status                          - status of the workout, 'completed' or 'in_progress'
    workout_summary_type                            - type of the workout, example 'run', 'strength'
    workout_summary_source                          - source of the workout data, can be 'manual', 'device', 'autodetected', 'mobile_run'
    interval_start                                  - start time of the interval, timestamp
    interval_end                                    - end time of the interval, timestamp
    total_weight_kg                                 - sum of weights, kilograms
    avg_cadence_spm                                 - average cadence, steps per minute
    avg_vertical_oscillation_mm                     - average vertical oscillation (distance off the ground your center of mass moves with each stride while running), millimeters
    avg_vertical_ratio                              - average vertical ratio (vertical oscillation/stride length), ratio
    rate_perceived_exertion                         - rate of perceived effort
    avg_ground_contact_time_duration_micro_sec      - average ground contact time duration (amount of time for which the foot was in contact with the ground) during workout, micro seconds

    round_name                                      - name of the round
    round_phase                                     - phase of the round, 'warm up', 'main', 'cool down'
    round_start                                     - start time of the round, timestamp
    round_end                                       - end time of the round, timestamp
    round_total_weight_kg                           - sum of weights for a round, kilograms
    round_avg_cadence_spm                           - average cadence for a round, steps per minute
    round_avg_vertical_oscillation_mm               - average vertical oscillation (distance off the ground your center of mass moves with each stride while running) for a round, millimeters
    round_avg_vertical_ratio                        - average vertical ratio (vertical oscillation/stride length) for a round, ratio
    round_avg_ground_contact_time_duration_micro_sec - average ground contact time duration (amount of time for which the foot was in contact with the ground) during workout for a round, micro seconds

    segment_name                                    - name of the segment
    segment_type                                    - type of the segment, 'rest', 'work'
    segment_start                                   - start time of the segment, timestamp
    segment_end                                     - end time of the segment, timestamp
    segment_movement                                - movement of the segment, 'run', 'walk', 'bike', 'swim'
    segment_total_weight_kg                         - sum of weights for a segment, kilograms
    segment_avg_cadence_spm                         - average cadence for a segment, steps per minute
    segment_avg_vertical_oscillation_mm             - average vertical oscillation (distance off the ground your center of mass moves with each stride while running) for a segment, millimeters
    segment_avg_vertical_ratio                      - average vertical ratio (vertical oscillation/stride length) for a segment, ratio
    segment_avg_ground_contact_time_duration_micro_sec - average ground contact time duration (amount of time for which the foot was in contact with the ground) during workout for a segment, micro seconds

    set_neme                                       - name of the set
    set_start                                      - start time of the set, timestamp
    set_end                                        - end time of the set, timestamp
    set_total_weight_kg                            - sum of weights for a set, kilograms
    set_avg_cadence_spm                            - average cadence for a set, steps per minute
    set_avg_vertical_oscillation_mm                - average vertical oscillation (distance off the ground your center of mass moves with each stride while running) for a set, millimeters
    set_avg_vertical_ratio                         - average vertical ratio (vertical oscillation/stride length) for a set, ratio
    set_avg_ground_contact_time_duration_micro_sec - average ground contact time duration (amount of time for which the foot was in contact with the ground) during workout for a set, micro seconds

    split_type                                     - type of the split, 'duration_seconds', 'distance_mm'
    split_value                                    - value of the split, seconds or millimeters depending on the type
    split_total_weight_kg                          - sum of weights for a split, kilograms
    split_avg_cadence_spm                          - average cadence for a split, steps per minute
    split_avg_vertical_oscillation_mm              - average vertical oscillation (distance off the ground your center of mass moves with each stride while running) for a split, millimeters
    split_avg_vertical_ratio                       - average vertical ratio (vertical oscillation/stride length) for a split, ratio
