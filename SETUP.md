# Start with the basics

1. Install the current Claude Desktop app from https://claude.com/download and sign in. Confirm that your account offers the Code tab. No IDE is required.
2. Unzip this whole kit into a normal writable folder. Keep a clean copy and work in a duplicate.
3. Open START-HERE.html. Begin with the workspace-tour folder: three small files and a read-only first request.
4. In Claude Desktop choose Code, choose a local environment (the teaching screenshot calls it This computer), and select workspace-tour. Choose the model available to your account. Set Plan for the first read-only request.
5. Use the exact prompt on slide 19. Inspect the answer and the unchanged files before moving on.
6. For each later example, copy that demo's starter folder and select the copy as the working folder. The three projects are independent.
7. Read and plan first. Review the plan and switch to Manual mode before building. Read each approval request, including which path will change.
8. Open the output in Claude's Browser pane, or open output/index.html in a browser yourself. A local file is not a published site.

## Recovery

Use a clean starter copy to restart. A checkpoint is a working result you can copy into your working output folder. The meeting checkpoint is from before the clarification; the completed example includes the clarification. Keep source files unchanged.

## Save and test a skill

At slide 69, approve the specific write to .claude/skills/meeting-to-work/SKILL.md. Plan mode does not write the file. Confirm that the file exists before opening a fresh session in the same project and running slide 71.

If writing the hidden folder is unavailable, use the included fallback: copy the .claude folder inside demos/02-meeting-board/reusable-skill into your working project. Finder may hide folders beginning with a dot; use Command-Shift-Period to show them. The fallback is a Claude-drafted method, not a different answer key.

The board only lets you change task status in the browser. That status is stored in that browser's localStorage and does not rewrite the source transcript or tasks.json. Reset statuses restores the extracted state.

## Dashboard repair

Download the separate 04-dashboard-repair starter from START-HERE.html and open that folder in Code. It already contains the intentionally wrong dashboard. Use Manual mode for the repair prompt, then compare with the repaired example. For the initial dashboard plan, explicitly agree that the table and export show all visible regional rows, while the metric counts only approved rows.

## What the examples do

All teams and records are fictional. The website prepares a local enquiry download; it sends no email and takes no payment. The board displays extracted meeting tasks. The dashboard has eight fixed rows, no live data and no forecast. Public hosting is not required.
