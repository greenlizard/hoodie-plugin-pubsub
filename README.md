hoodie-plugin-pubsub
====================

[![Build Status](https://travis-ci.org/greenlizard/hoodie-plugin-pubsub.svg?branch=master)](https://travis-ci.org/greenlizard/hoodie-plugin-pubsub) [![Dependencies](https://david-dm.org/greenlizard/hoodie-plugin-pubsub.png)](https://david-dm.org/greenlizard/hoodie-plugin-pubsub) [![devDependency Status](https://david-dm.org/greenlizard/hoodie-plugin-pubsub/dev-status.svg)](https://david-dm.org/greenlizard/hoodie-plugin-pubsub#info=devDependencies)

## Dependencies
```shell
  hoodie install hoodie-plugin-pubsub
```
for cordova/phonegap users
```shell
  bower install hoodie-plugin-pubsub
```

## Setup client
```html
 <script src="/_api/_files/hoodie.js"></script>
```
for cordova/phonegap users

```html
  <script src="<bowerdir>/hoodie/dist/hoodie.js"></script>
  <script src="<bowerdir>/hoodie-plugin-pubsub/hoodie.pubsub.js"></script>
```

## API
### hoodie.pubsub.subscribe(hoodieId, type)
### hoodie.pubsub.unsubscribe(hoodieId, type)
### hoodie.pubsub.subscribers()
### hoodie.pubsub.subscriptions()

