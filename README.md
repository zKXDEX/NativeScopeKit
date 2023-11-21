{
  "name": "core-windows-registry",
  "version": "1.0.0",
  "main": "index.ts",
  "types": "index",
  "author": "kdex",
  "license": "MIT",
  "repository": {
    "type": "git",
    "url": "git://github.com/zkxdex/NativeDirFlow.git"
  },
  "homepage": "https://github.com/zkxdex/NativeDirFlow",
  "bugs": {
    "url": "https://github.com/zkxdex/NativeDirFlow/issues"
  },
  "os": [
    "win32"
  ],
  "dependencies": {
    "node-addon-api": "^4.3.0"
  },
  "devDependencies": {
    "@types/node": "^15.0.2",
    "mocha": "^10.2.0",
    "node-gyp": "^10.0.1",
    "ts-node": "^10.9.1",
    "typescript": "^4.5.5"
  },
  "scripts": {
    "build": "tsc -d",
    "test": "mocha -r ts-node/register 'test.js'"
  }
}