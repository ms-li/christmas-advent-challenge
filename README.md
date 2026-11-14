# Christmas Advent Challenge

Independent classroom prototype for one teacher and one student, hosted with GitHub Pages.

## Current prototype

- Four illustrated scenes: Snowy Mountain Village, Santa's Workshop, Festive Food Table and Winter Town Square.
- 24 interactive positions per scene, with shuffled numbers for each new game.
- B1, B2, C1 language selector and an initial bank of 34 approved sample challenges.
- Teacher + student alternating turns, with live white/red scoring ornaments over the empty tree.
- Eligibility checks for exchange events, plus teacher-only notes.
- Teacher-controlled End Session, available at any point, with final score and tree.
- Classroom mode for two players sharing a single screen.
- Responsive page with a numbered mobile alternative board.

## Important limitations

This is a **classroom prototype** — it is not the complete 2026 Christmas release.

- Remote synchronized play is **not** yet connected to Firebase.
- There is no public room creation or sharing system.
- Not all 24 doors can currently have unique approved challenges at each level. More approved content is needed, especially at B2.
- Separate illustrations for the image-description challenges still need approval and installation.
- Winter Town Square uses a floating advent panel over the scenery rather than 24 native scene windows.
- The click regions for the four images need hands-on browser testing for alignment at different sizes. Some small-background windows can be hard to read on mobile.

## Publishing

GitHub repository Settings → Pages → Build and deployment:
select **Deploy from a branch**, branch **main**, folder **/(root)**, then save.

The website URL will be https://ms-li.github.io/christmas-advent-challenge/

## Files

- `index.html`: standalone prototype code (no external JS dependencies)
- `mountain-village-clean.png`
- `santas-workshop-clean.png`
- `festive-food-table-clean.png`
- `winter-town-square-clean.png`

All game data currently stays within the open browser page and resets on a new game or refresh. This prototype does not use Firebase and does not consume its database quotas.
