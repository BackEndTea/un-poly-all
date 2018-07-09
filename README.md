# Un Poly All

A lot of polyfills are not needed if your project requires a certain php version, or needs the locale 
aware functionality of an extension. The polyfills slow down your application by adding `function_exists`, `extension_loaded` or php version checks that
are when your autoloader is loaded. By removing the polyfills the start up time is (slightly) reduced.

If you do add this or one of its child packages, consider adding extension as a requirement to your `composer.json`.

## Installation

```bash
$ composer require backentea/un-poly-all
```