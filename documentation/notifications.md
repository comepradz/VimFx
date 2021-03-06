<!--
This is part of the VimFx documentation.
Copyright Simon Lydell 2015, 2016.
See the file README.md for copying conditions.
-->

# Notifications

Some commands may show notifications, such as the `n` and `N` commands which
tell when they wrap around the page, or the phrase you searched for could not be
found. Actually, any command that sometimes cannot do anything (such as the `f`
command if there are no clickable elements in sight) instead show a notification
in those cases, so that _something_ happens instead of leaving you unsure if you
pressed the correct keys or not.

VimFx’s notifications are similar to the “URL popup,” shown when hovering or
focusing links, but is placed on the opposite side.

Notifications are shown until you click them, press a key or switch tab.

(See also the [`notifications_enabled`] pref.)

[`notifications_enabled`]: options.md#notifications_enabled
