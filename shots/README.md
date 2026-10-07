# shots/ — project screenshots

Images in this folder appear on the matching project card at
https://yebouef.github.io/resume/

## How to add one

1. Take the screenshot. Crop out anything confidential first:
   real client names, real trial data, email addresses, internal
   URLs, ticket numbers.
2. Save it into this folder using the exact file name from the
   list below. PNG or JPG. Keep each file under about 400 KB. Captions stay under about 100 characters or they wrap to four lines in the card.
3. Commit and push. The image appears on its card automatically.

Nothing breaks while a file is missing. The slot removes itself,
so the card looks exactly as it does today until you add the image.

## File names the site is already looking for

| File name | Card | What it should show |
|---|---|---|
| `field-trial-feuillet-c.png` | Agricultural Field-Trial Platform | The generated Feuillet C next to the committee template it has to match. Put them side by side in one image. |
| `field-trial-analysis.png` | Agricultural Field-Trial Platform | The Analyse screen with a test and threshold selected and a result showing. This is the one image that backs the requirements claim, so make the selectors visible. |
| `field-trial-offline.png` | Agricultural Field-Trial Platform | A technician view with the offline/pending indicator visible. |
| `servicenow-dashboard.png` | ServiceNow Service Desk Build | The reporting dashboard: SLA compliance, MTTR trend, volume by group. |
| `servicenow-sla.png` | ServiceNow Service Desk Build | The SLA definition or assignment group config screens, showing they were set up rather than just used. |
| `storyforge-output.png` | StoryForge | A feature description in, generated stories with acceptance criteria out. |
| `aico-dues.png` | AICO Membership Portal | The month-by-month dues coverage view. |
| `operai-home.png` | Operai | The live product page. |
| `coffee-dashboard.png` | Coffee Sales Dashboard | The dashboard with slicers visible. |
| `united-dashboard.png` | United Airways Performance Review | The Tableau executive view. |

## Changing a caption, or adding a slot that is not listed

Open `index.html` and search for `PROJECT SCREENSHOTS`. The list
under it is the only place to edit. Each line looks like:

    {f:"shots/my-file.png", en:"English caption", fr:"Légende"},

The caption is the part a recruiter actually reads, so say what the
image proves rather than what it is.

## A note on screenshot width

Thumbnails are cropped from the top left of the image, so put the
important part there. Clicking a thumbnail opens the full image, so
nothing is lost by the crop.
