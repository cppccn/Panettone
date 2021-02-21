# Panettone 

_Local first real-time database_

Panettone tries to mimic [Firebase v8 API](https://firebase.google.com/docs/database/web/read-and-write). Built initially as a frontend for [Pandoro](https://github.com/cppccn/pndr) it’s super-fast* (benchmark needed) and will use the [File System Access API](https://web.dev/file-system-access/) if available or [Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API) if it can't reach a backend.

## Usage

```
yarn add pnttn
```

**TODO:** example of usage with an hello-world React app (boilerplate needed).

## Backend

Our SDK uses a push events buffer (specs needed). In the future, we want to be able to plug any CRUD REST API or GraphQL backend.
