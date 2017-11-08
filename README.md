# TCC Ng5 Universal

This project is an initiator for fast start new project with Angular 5 Universal.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.0.

Thanks [universal-demo-v5](https://github.com/evertonrobertoauler/universal-demo-v5).


How to use:
-------------
### Requirement:
```
npm install -g @angular/cli
```

### Installation:
```
npm install
```
    
### Usage:
```
ng help
```

### Development:
```
ng serve
```
Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
    
    
### Generating Components, Directives, Pipes and Services:
This project was generated with [Angular CLI](https://github.com/angular/angular-cli), so you can use all command line of [Angular CLI](https://github.com/angular/angular-cli): 
```
ng generate component my-new-component
ng generate directive my-new-directive
ng generate service my-new-service
ng generate pipe my-new-pipe
//...
```
    
Custom project:
-------------
### Project name:
Update config in `.angular-cli.json`
```
{
    ...
    "project": {
        "name": "your-project-name",
    },
    ...
}
```
And update config in `package.json`
```
{
    "name": "your-project-name",
    ...
}
```

### Prefix:
Update config in `.angular-cli.json`
```
{
    ...
    "apps": [
        {
            ...
            "prefix": "your-project-prefix",
            ...
        },
        ...
    ]
    ...
}
```
   
Build:
-------------
### Prod environment
```
npm run build
```
    
### Custom environment.
In this example is `dev` environment, `tcc-universal` is the name of project, defined in `package.json` file
```
npm run build --tcc-universal:env=dev
```
   
Start server:
-------------
```
node dist/server.js
```
   
Deployment:
-------------
Upload all files in `dist` folder to your server, and run:
```
node server.js
```