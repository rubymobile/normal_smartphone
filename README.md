db: fisrt-table
on:
  push:
    branches: [ "main-toggler" ]
  pull_request:
    branches: [ "mail-tracking" ]

db: table

nfc:
Transactions: [on]

2nd-authorization: |  yubikey  | no-error > 0, no-human-error > 0
push-button: [off]
push-behind-button : [off]

secure: [on]
touch-off: [button]

in-secure: [button] off
/* for updown */ db: fisrt-table on: push: branches: [ "main-toggler" ] pull_request: branches: [ "mail-tracking" ]

db: table2
nfc: Transactions: [on]

2nd-authorization: | yubikey | no-error > 0, no-human-error > 0 push-button: [off] push-behind-button : [off]
secure: [on] touch-off: [button]

own : [time] value [store] register_cashe connected to central(sales_amount_cache,number,credits,visa,name) outside: table
