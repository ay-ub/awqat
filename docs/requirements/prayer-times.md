# Prayer times

## Goal

Show today's prayer times and identify the next upcoming prayer.

## Inputs

- Latitude
- Longitude
- Timezone
- Calculation method
- Madhab
- Local date

## Outputs

- Fajr
- Sunrise
- Dhuhr
- Asr
- Maghrib
- Isha
- Next prayer and remaining time

## Acceptance criteria

- The next prayer changes correctly as local time passes each prayer.
- Daylight-saving changes are handled by the timezone identifier.
- The calculation method is visible in configuration.
- Unsupported extreme-latitude conditions are reported explicitly.
