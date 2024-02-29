# Version 1.1.1 (29.02.24):
- added `requrements.txt`
- added some annotations
- changed `.gitignore`
- added `data` directory for all documents

# Version 1.1 (28.02.24):
- completely rewritten function `parse_data`:
  - removed try-except constructions
    - `<tr>` tags now checked by classes they contain (or not)
    - when found time mark all films at this time are added to dict
      - changed way of handling multiple theatres for the same film 
- added annotations
- added days of the week
- added `CHANGELOD.md`
- added logging
- updated Telegram bot:
  - added `/info` command
  - added commands menu
  - added description
  - added choice of file format (`.csv` `.ods`, `.xlsx`)
- added convertion from `.csv` to ``.ods`` and `.xlsx`
- added `greet.md`