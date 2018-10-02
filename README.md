# AndroidTranslucentActivity

If we use FLAG_NOT_FOCUSABLE, when press Back button, activity will be freeze
(https://stackoverflow.com/questions/50362411/flag-not-focusable-on-activity)

The current solution (need to find another solution when have time)
- don't allow user press back in this Activity, eg: this activity have a dialog so when dialog close, also close this activity

- another solution (on stackoverflow) is don't use FLAG_NOT_FOCUSABLE, just handle onKey

### Reference