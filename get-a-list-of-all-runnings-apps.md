# Get a List of All Runnings Apps

```bash
echo $(osascript -e 'tell application "System Events"
    set listOfProcesses to (name of every process where background only is false)
end tell')
```

Contributor: [[John Lindquist]]

Tags:

- [[zsh]]
- [[Osascript]]

[//begin]: # "Autogenerated link references for markdown compatibility"
[John Lindquist]: john-lindquist "John Lindquist"
[zsh]: zsh "Zsh"
[//end]: # "Autogenerated link references"