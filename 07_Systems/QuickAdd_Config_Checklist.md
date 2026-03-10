# QuickAdd Config Checklist (Core Entries)

This checklist uses the canonical variables from `07_Systems/QuickAdd_Input_Map.md`.

## 1) Create Project
- Choice name: `Create Project`
- Template target: `06_Templates/01_Project/Project Page.md`
- Output folder: `01_Projects/`
- Filename suggestion: `{{VALUE:project}}.md`
- Variables to prompt (in order):
  1. `project`
  2. `goal`
  3. `next_step`
  4. `area`
  5. `date`

## 2) New Topic
- Choice name: `New Topic`
- Template target: `06_Templates/02_Knowledge/Topic Page.md`
- Output folder: `03_Resources/Topics/`
- Filename suggestion: `{{VALUE:topic}}.md`
- Variables to prompt (in order):
  1. `topic`
  2. `goal`
  3. `next_step`
  4. `date`

## 3) New Person
- Choice name: `New Person`
- Template target: `06_Templates/05_People/People Profile.md`
- Output folder: `04_Relationships/People/`
- Filename suggestion: `{{VALUE:person}}.md`
- Variables to prompt (in order):
  1. `person`
  2. `area`
  3. `next_step`
  4. `date`

## 4) Log Interaction
- Choice name: `Log Interaction`
- Template target: `06_Templates/05_People/Relationship Log.md`
- Output folder: `04_Relationships/Logs/`
- Filename suggestion: `{{VALUE:date}}-{{VALUE:person}}-Interaction.md`
- Variables to prompt (in order):
  1. `person`
  2. `date`
  3. `topic`
  4. `next_step`
  5. `idea` (optional)

---

## Final Variable List by Entry
- Create Project: `project`, `goal`, `next_step`, `area`, `date`
- New Topic: `topic`, `goal`, `next_step`, `date`
- New Person: `person`, `area`, `next_step`, `date`
- Log Interaction: `person`, `date`, `topic`, `next_step`, `idea`(optional)
