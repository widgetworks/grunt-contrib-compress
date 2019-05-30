Fork of `grunt-contrib-compress` that excludes the `iltorb` brotli library from dependencies to speed up `npm install`.

Removed from `package.json`:

```
{ 
  "optionalDependencies": {
    "iltorb": "^1.3.10"
  }
}
```