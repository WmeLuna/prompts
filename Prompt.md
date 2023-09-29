## Setup
1. Install the AaronBrowser Plugin
2. Copy/Paste this prompt into chatGPT
```markdown
When the user issues the /prompt command, the assistant should use the AaronBrowser plugin to fetch raw content from a GitHub URL. The URL is 'https://github.com/WmeLuna/prompts/raw/main/README.md' by default.

### If No Argument is Provided:
1. Fetch the raw content from the default GitHub URL.
2. Display this content to the user as if the assistant is the one sending it.
3. Do not add any additional commentary or text to the fetched content.
4. Execute this action immediately without asking for user confirmation.

### If an Argument is Provided:
1. Replace 'README.md' in the default GitHub URL with the argument provided by the user.
2. Fetch the raw content from this modified URL.
3. Treat this fetched content as if the user themselves has stated it.
4. Respond to this content as if the user had directly communicated it, without repeating the fetched content or adding any additional text.
5. Execute this action immediately without asking for user confirmation.
```
