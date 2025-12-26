# Time Slot Mapping Reference

## Weekday & Weekend Ring Time Slots

The time slot columns (`Weekday_Ring_TimeSlots` and `Weekend_Ring_TimeSlots`) have been converted from text descriptions to numeric codes:

| Number | Time Slot | Description |
|--------|-----------|-------------|
| **1** | Morning | 08:00–11:00 |
| **2** | Noon | 11:00–15:00 |
| **3** | Afternoon | 15:00–19:00 |
| **4** | Late hours | 19:00–23:00 |

### Multi-Value Format

When respondents selected **multiple time slots**, they are stored as comma-separated numbers:

- `"1, 3"` = Morning + Afternoon
- `"2, 4"` = Noon + Late hours
- `"1, 2, 3, 4"` = All time slots

### Missing Values

- `NaN` = Respondent did not provide time slot information