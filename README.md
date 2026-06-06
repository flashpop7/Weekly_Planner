# Weekly_Planner

A simple local-first weekly planning web app.

Weekly_Planner helps you arrange tasks by date and time block, switch between day and week views, track completion, undo mistakes, and review plans in a compact summary table.

## Features

- Day view and week view
- Time blocks from `07:00` to `24:00`
- Add, edit, delete, undo, and redo plans
- Multi-hour tasks and repeated tasks
- Task categories and mood records
- Current-view summary table
- Clear completed tasks or clear the current week
- Chinese / English interface
- Feedback entry for suggestions and bug reports
- Local browser storage with no account required

## Use

Open `index.html` directly, or deploy the files to GitHub Pages.

Main files:

```text
index.html
styles.css
app.js
version.json
```

## Feedback

The feedback button currently opens this WPS form:

```text
https://f.wps.cn/g/P1wfV2Yd/
```

Responses are managed in the WPS/Kingsoft form backend, so the creator can review suggestions and bug reports without publishing a personal email address.

Overseas users can submit feedback only if they can access the WPS form link normally. If you expect many international users, keep a backup form option ready.

To change feedback collection, edit these values in `app.js`:

- `feedbackFormUrl`: opens an external form
- `feedbackSubmitUrl`: submits the built-in feedback dialog to an API endpoint

Do not put private keys, tokens, or passwords in frontend code.

## Privacy

Plans are saved in the browser with `localStorage`.

Data is not uploaded to a server by default. Clearing browser data may remove saved plans.

## License

MIT License. See [LICENSE](LICENSE).
