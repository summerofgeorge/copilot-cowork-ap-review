# Copilot Cowork AP review

A Stringfest Analytics practice exercise using Microsoft Copilot Cowork and ten fictional invoices. No programming is required.

## Files
- `invoices.csv`: the ten source rows, also included in Prompt 1. Open in Excel to inspect the data.
- `prompts.txt`: four prompts to run in order in the same Microsoft Copilot Cowork task.

## Follow along
Open https://copilot.cloud.microsoft/ with an eligible work account and choose Cowork. Your organization must enable the service and the required usage-based billing. See [Microsoft's getting-started guide](https://learn.microsoft.com/en-us/copilot/cowork/get-started) and [access controls](https://learn.microsoft.com/en-us/copilot/cowork/cowork-access).

Paste Prompt 1, review the plan, then use Prompts 2-4. Prompt 1 includes the data, so uploading the CSV is optional and unnecessary. Download and open the generated Excel and Word files; a chat summary alone is not the deliverable. The Word briefing is a snapshot, not a live link to Excel.

Use the fixed review date of October 31, 2026. The source-row import control is $38,200; the three Ready for review rows total $17,400. The source control includes paid and potentially duplicated rows and is not the true liability balance. This exercise does not authorize or initiate any payment.

## Test status
Tested November 5, 2026 in Microsoft Copilot Cowork using Auto / Medium. All four prompts were run in one task and produced downloadable Excel and Word files. The source values, saved results, formulas, actions, roles, and table filters were independently inspected. The Word briefing opened as one page.

Cowork reported recalculating the scenario tests in LibreOffice. A separate test in Excel for the web confirmed that November 5 gives four Ready for review rows totaling $20,600; restoring October 31 returned $17,400. Your generated layout may differ. Inspect your own files and repeat the checks.

This repository contains the starting files only. The generated example used COUNTIF for duplicate counts; invoice IDs containing wildcard characters would require an additional exact-match check when adapting it to new data.

Created by George Mount, Stringfest Analytics. Fictional practice data only.