# State

## Item
can change 
be disposed. 
Meta: 
	- id
	- version
	- cdate
	- mdate

## Collections
normalised state
@reduxjs/toolkit adaptors

## Subscriptions
Whitelist
subscribe to all: *
events are redux actions like:
* type 
* meta
* payload 
* error?
	
## Computables
subscribes to changes
can memoise based on collectionName/id/version via `JSON.stringify` + `sha`?
### Collection params
Config for sorting

## Effects
subscribes and can send events
thunks like
Async/Fetches

## TODO:

- Bulk changes
- State transactions
- Immutability with immer
- React Hooks should use subscription
- Migrations, like DB

### Middleware?
- logging
- hydrating
- persistence
