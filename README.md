<!--lint disable awesome-list-item-->
<div align="center">
  <p align="center">
    <img alt="Medusa" src="https://user-images.githubusercontent.com/7554214/129161578-19b83dc8-fac5-4520-bd48-53cba676edd2.png" width="200" />
  </p>
  <h1>Plugin starter (Typescript)</h1>
  <p>Start to write your own plugin as quick as possible</p>
    
  <a href="https://github.com/adrien2p/awesome-medusajs">
      <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</div>

# Getting started

Installation

```bash
git clone git@github.com:adrien2p/medusa-plugin-starter-ts.git
```

# Usage

## Api

### Admin routes

Those routes will automatically be attached by medusa to the `admin` path.

### Post routes

Those routes will automatically be attached by medusa to the `post` path.

### Custom routes

All those routes are added in the main router and you have to manage them.

## Models/Migrations

Those models will be attach to the manager and included into the medusa container.
The migrations will be applied automatically.

## Subscribers

It acts like a service but its main purpose is to extends core flow depending on the
events you want to listen to.

## Services

Those services will be automatically added to the medusa container and will be available
in any other service through the constructor injection.

# Deployment

Once your plugin is done. 

```bash
npm run build && npm version && npm publish
```

You can now install it into your project file `medusa-config`.
