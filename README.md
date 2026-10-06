# eastla_alcohol v1.1
Realistic alcohol system for StreetKings (QBX + ox_inventory + ox_lib).

## Install
1. Drop `eastla_alcohol` in resources, `ensure eastla_alcohol` after ox_inventory.
2. Merge `items/ox_inventory_items.lua` into `ox_inventory/data/items.lua` + add images.
3. Give `breathalyzer` / `stomach_pump` to police / EMS.

## Features
Drinks + BAC, 4 stages, drunk driving, ragdoll, pass out, vomiting, hangover,
tolerance, food slows hit, gradual absorption, sobering items, bar multiplier,
breathalyzer + DUI fine/jail via wasabi_police_v2, stomach pump.

## Bar drinks
Items with metadata `{ bar = true }` hit `Config.BarMultiplier` harder.

## Test
`/setbac [id] [value]` (group.admin).

## Server exports
`GetBAC(src)`, `SetBAC(src, v)`, `AddBAC(src, v)`
