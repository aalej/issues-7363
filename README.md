# Repro fod issue 7363

## Versions

platform: Windows<br>
firebase-tools: v13.11.3

## Steps to reproduce

1. Run `firebase deploy --only hosting --project PROJECT_ID`
2. Open "PROJECT_ID.web.app"
   - Should show image of a duck
3. Open "PROJECT_ID.web.app/test"
   - Should show image of a cat

## Notes

### Expected behavior

Visiting "PROJECT_ID.web.app"

Visiting "PROJECT_ID.web.app/test"

### Actual behavior

Visiting "PROJECT_ID.web.app"

Visiting "PROJECT_ID.web.app/test"
