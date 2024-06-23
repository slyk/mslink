# Msl

### libs/ Folder structure
- `/shared/data-models`: This is where you can put your shared entity data models. Both Angular and NestJS can import from this library.  
- `/angular`: This directory contains Angular-specific libraries. Each feature or logically separated part of your Angular application can have its own library.  
- `/nestjs`: This directory contains NestJS-specific libraries. Each feature or logically separated part of your NestJS application can have its own library.
```
/libs
  /shared
    /data-models
  /angular
    /feature1
    /feature2
  /nestjs
    /feature1
    /feature2
```

### Docs
Main docs are in msl-docs folder and can be viewed using Obsidian app.

```
npx nx run-many -t <target1> <target2>
```

..or add `-p` to filter specific projects

```
npx nx run-many -t <target1> <target2> -p <proj1> <proj2>
```
