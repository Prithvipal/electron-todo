# NoteX

NoteX is a destop application. The purpose of this applicattion to maintain todo list. It is developed using Electron JS.

![](docs/media/demo.gif)
#### Run Application in Developer mode

```
npm start
```

#### Generate Package
##### Mac
```
npm run package-mac
```
##### Linux
```
npm run package-linux
```
##### Windows
```
npm run package-win
```

### Planned features
1. **Add new note:** When new note is added, it will be added sidebar. There can be multiple notes in sidebar. The purpose of this feature is to maintain group similar TODO in a single note.
Ex: There can be a note for to list of item to be purchaged. Another note may contains list books to read etc.
2. **Data storage:** Currently, todo list items are being stored in memory. When application is refreshed/reopened, previously added data will be vanished. We have not finalized that where data will be store: it can be database, file system.
