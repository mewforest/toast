## Forked version contents last compiled x64 version that supports Unicode. Be note: the text below of readme.md is unchanged.

# Toast

A go package for Windows 10 toast notifications.

As seen in [jacobmarshall/pokevision-cli](https://github.com/jacobmarshall/pokevision-cli).

## CLI

As well as using go-toast within your Go projects, you can also utilise the CLI - for any of your projects.


```cmd
C:\Users\Example\Downloads\toaster.exe \
  --app-id "Example App" \
  --title "Hello World" \
  --message "Lorem ipsum dolor sit amet, consectetur adipiscing elit." \
  --icon "C:\Users\Example\Pictures\icon.png" \
  --audio "default" --loop \
  --duration "long" \
  --activation-arg "https://google.com" \
  --action "Open maps" --action-arg "bingmaps:?q=sushi" \
  --action "Open browser" --action-arg "http://..."
```

## [Example](https://github.com/go-toast/toast/blob/master/readme.md#example)

## [Screenshots](https://github.com/go-toast/toast/blob/master/readme.md#screenshots)

