# Electron Frameless Window Bug

Run on Windows 10. 

## Expected Behavior

Mousedown event firing on the entire window, no "dead" areas. Cursor "croshair" on the entire window.

## Actual Behavior
The mouse event doesn't fire near window borders (about 4-7 px from border). Cursor changes to "default".

## To Use

```bash
# Install dependencies
npm install
# Run the app
npm start
```
