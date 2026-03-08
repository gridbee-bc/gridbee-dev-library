# Troubleshooting

## 403 insufficient authentication scopes

Error

Request had insufficient authentication scopes.

Fix

1. Enable Apps Script API  
https://script.google.com/home/usersettings

2. Add this scope to your manifest

https://www.googleapis.com/auth/script.projects.readonly

3. Run the script again and approve permissions.
