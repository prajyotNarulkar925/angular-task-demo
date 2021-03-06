# Demo Task


# _About the App_
This application showcases my Angular experience by building the problem statment provided!

Below is a screenshot of the project completed:
<img src="task_screenshot-01012021.png">

# _Specifications_

### Necessary Features & Functionality
| Feature | Description | Notes |
|--|--|--|
| New list | Create new list when user clicks button | Ask for the list name before creating |
| Add card | Asks user to enter a title for the card | 'Add card' button pushes card to list |
| Theme Switch | Aslloow the user to switch between themes | 'Change Theme' button changes the theme |

### Secondary Features & Functionality
| Feature | Description | 
|--|--|
| Dragging items | Users to drag cards

### Component Tree
```
trello-clone  
└───src
│   └───app [will contain main board]
│       │   app.component.css
│       │   app.component.html
│       │   app.component.spec.ts
│       │   app.module.ts
│       └───LandingPageComponents
|             └───board
|                   │   board.component.css
│                   │   board.component.html
│                   │   board.component.spec.ts
│                   │   board.component.ts
│             └───list
|                   │   list.component.css
│                   │   list.component.html
│                   │   list.component.spec.ts
│                   │   list.component.ts
│             └───card
|                   │   card.component.css
│                   │   card.component.html
│                   │   card.component.spec.ts
│                   │   card.component.ts
|         └───Services
|                |    mock-data.service.ts
|                |    mock-data.service.spec.ts
|         └───Themes
|                │   theme.module.ts
│                │   theme.service.spec.ts
│                │   theme.service.ts
│                │   theme.ts                
```

# _Installation for OSX_
- Download the repository from GitHub (https://github.com/prajyotNarulkar925/angular-task-demo)
- Install Node.js on your machine
- `npm install` to install all necessary packages
- `ng serve --open` to run the application in your browser
