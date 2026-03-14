# glist

A fast, thumb-friendly grocery list for real shopping-cart conditions.

Open [index.html](/Users/sri/dev/js/glist/index.html) in a browser and use it as a local-only grocery app with a shopping side and an all-items side.

## Local Only

This app does not use a backend.

- Nothing is sent to a server.
- Nothing is synced to the cloud.
- Everything stays in your browser's `localStorage` on your device.

If you clear browser storage, switch browsers, or use private browsing, your saved data may disappear.

## Features

- Big mobile-friendly shopping rows for one-handed tapping
- Mark items purchased with a tap
- Purchased items can be moved down manually
- Clear the shopping list, with confirmation when unchecked items remain
- Collapsible shopping groups by store
- Collapse or expand each store section while shopping
- Move a whole store group to the top when you walk into that store
- Search on the shopping list
- Separate `All Items` catalog view
- Collapsible `Stores` section
- Add custom stores
- Brand-colored store bubbles for matched grocery chains
- Tap a store in the `Stores` section to remove it
- Add custom items
- Search all items
- Tap an item in `All Items` to add or remove it from the shopping list
- Per-item store chooser with multi-select store assignment
- Selected stores shown directly on the item card
- `Last purchased` relative timestamps on catalog items
- Purchase history saved per item
- Shopping list and item catalog saved across reloads
- Store list saved across reloads

## How It Works

`Shopping list`

- Use this while walking the store.
- Tap an item to mark it purchased.
- Groups are organized by store, with `Any Store` for items that do not have a selected store.

`All Items`

- Use this to maintain your master catalog.
- Add new items and new stores.
- Choose one or more stores for an item.
- Tapping the item toggles whether it is currently on your shopping list.

## Run It

No build step.

1. Open [index.html](/Users/sri/dev/js/glist/index.html) in a browser.
2. Start adding items.
3. Push a cart and tap with confidence.
