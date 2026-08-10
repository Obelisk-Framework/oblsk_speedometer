# Oblsk_speedometer Plugin

## Description
A placeholder speedometer global element. No real vehicle-speed readout yet
(GetEntitySpeed is a trivial future addition), this just establishes the
plugin, correctly wired into the toggle/preferences mechanism by virtue of
being a normal global-elements registry entry. Real feature content is a
separate future pass.

## Installation
This plugin loads as part of the `core` resource. After adding it under
`plugins/`, run `obelisk registry:generate` from `core/` on the host, then
restart `core` (or the whole server).
