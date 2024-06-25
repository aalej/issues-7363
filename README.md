# Repro for issue 7363

## Versions

platform: Windows<br>
firebase-tools: v13.11.3

## Steps to reproduce

1. Run `firebase deploy --only hosting --project PROJECT_ID`
2. Opening "PROJECT_ID.web.app" should show an image of a duck.
   - This works, see expected and actual behavior below
3. Opening "PROJECT_ID.web.app/test" should show an image of a cat.
   - This does not work, see expected and actual behavior below

## Notes

### Expected behavior

Visiting "PROJECT_ID.web.app"

![image](https://github.com/aalej/issues-7363/assets/118378103/b882da51-434c-4e86-b71c-698f82646992)

Visiting "PROJECT_ID.web.app/test"

![image](https://github.com/aalej/issues-7363/assets/118378103/4045b943-932b-422c-91d6-75f6243aca7a)

### Actual behavior

Visiting "PROJECT_ID.web.app"

![image](https://github.com/aalej/issues-7363/assets/118378103/b0050fbf-4f26-45aa-aa7b-2952183eae45)

Visiting "PROJECT_ID.web.app/test"

![image](https://github.com/aalej/issues-7363/assets/118378103/0d485c55-5f73-40ca-8275-8ed5ef92ce8c)
