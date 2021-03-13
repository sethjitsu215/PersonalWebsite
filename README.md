# Seth's Personal Website

1. Use `git pull` to update repository on local computer.

2. Change your repository name to "PersonalWebsiteOld"

3. In terminal, change directories (`cd`) to your GitHub folder.

4. To create a Hugo website locally, type

`hugo new site PersonalWebsite`

5. In file explorer, move the folders and other content from "PersonalWebsiteOld" to "PersonalWebsite" folder.

6. You also need to move the '.git' folder in "PersonalWebsiteOld." To do that, type

`mv PersonalWebsiteOld/.git PersonalWebsite/.git `

6. To view website locally on computer, type in terminal:

`hugo server --themesDir themes/`
