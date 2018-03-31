# VQ Documentation for Marketplace API

Documentation library is [https://github.com/Rebilly/ReDoc](https://github.com/Rebilly/ReDoc).

It uses the "Deployment" example in ReDoc README but for reference it can be found below:
Side Note: we fetch YAML over GitHub so anytime you want to update the API spec, push it to master.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>VQ Marketplace API Documentation | VQ Labs</title>
    <!-- needed for adaptive design -->
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
      body {
        margin: 0;
        padding: 0;
      }
    </style>
  </head>
  <body>
    <redoc spec-url='https://raw.githubusercontent.com/vq-labs/vq-docs-marketplace-api/master/swagger.yaml'></redoc>
    <script src="https://rebilly.github.io/ReDoc/releases/latest/redoc.min.js"> </script>
  </body>
</html>
```
