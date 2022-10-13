# Module Federation using @angular-architects/module-federation


This repo is a course I did with ng-conf on MicroFrontends with Owen Mecham

The @angular-architects/module-federation library gives some great boiler plate schematics to get started with creating your microfrontend.
Example:
ng add @angular-architects/module-federation --project shell --port 5000

## Microfront breakdown

There are 2 microfrontends mfe1 and mfe2, along with a shared library wallet-lib and of course our shell app.
## How to run this repo:

1. start mfe2.
  ```ng serve mfe2
  ```

2. start mfe1.
  ```yarn start:mfe1
  ```

3. start shell.
  ```yarn start:shell
  ```

  *** Ensure that both mfe1 and mfe2 have compiled sucessfully before starting the shell app



