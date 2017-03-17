# reset-this
SCSS to reset element style to default based on webkit css user-agent value.

## Installation
```
    $ npm install reset-this
```

## Usage
```
    @import 'reset-this';
    
    # Include inside the section that you'd like to reset
    @include reset-this;
    
    # You can override the default adding the rules between curly braces {}
    @include reset-this { background: blue };
```

## Contributors
- [devmnrj](https://github.com/devmnrj)
- [ryananguiano](https://github.com/ryananguiano)
