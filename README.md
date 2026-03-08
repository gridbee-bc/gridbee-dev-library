# GridBee Dev Library

Developer utilities for building Google Apps Script automation and GridBee-powered Workspace tools.

## Features

- Download Apps Script projects
- Export scripts to Google Drive
- Backup and version utilities
- Tools for building GridBee products

## Example

```javascript
GBDev.scripts.download(scriptId);
GBDev.scripts.exportToDrive(scriptId);
```

## Installation

Add the library to your Apps Script project.

## Example

function test() {
  const data = GBDev.scripts.download(ScriptApp.getScriptId());
  Logger.log(data);
}
