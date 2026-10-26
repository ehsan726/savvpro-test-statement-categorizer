# AI Usage

## Tools used

| Tool | Used for |
|---|---|
| Claude (claude.ai chat) | Planning, folder structure, backend code, tests, docs |
| [other tool, if any] | [what for] |

**The categorisation brain contains no AI model.** AI was used only to help write the code.

## How AI helped

- Explained the task and broke it into steps
- Proposed the project structure (parser / brain / services / api)
- Wrote the first version of the backend, the sample CSV, tests and docs
- Helped debug setup errors (missing packages, empty scaffold files, 500 error)

## Where AI got things wrong (and what I did)

1. **Silent duplicate removal.** The first plan said to "not count" duplicate rows. That hides
   data and can drop genuine repeats. I changed it to flag duplicates as Needs Review.
2. **Missed foreign currency.** The first version had no handling for non-USD rows. Added a
   currency check.
3. **Empty scaffold files.** The scaffold created empty files, so the server failed with
   import errors until each file had its code.
4. **[Add your own: anything else that failed, was wrong, or you changed]**

## What I verified myself

- Ran the app against the sample CSV and checked every category by hand
- Ran `pytest` and fixed failures
- [Add anything else you checked]

## Token usage

| Tool | Date | Input tokens | Output tokens | Total |
|---|---|---|---|---|
| Claude | [date] | [ ] | [ ] | [ ] |

Screenshots / logs: see the `docs/ai-usage/` folder.
- `[screenshot-1.png]`
- `[screenshot-2.png]`