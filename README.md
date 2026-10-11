# Food assistant UI evidence

Before: upstream `4d8147aca0a6b315b48dd504a9f3aab80e71883e`. After: cumulative branch `1e68688c54ed3fa665db888143e32da58f37181e`.

Web captures render the actual settings form and chat components in a local component harness.
The harness supplies synthetic API records, mounts the normal providers, and blocks writes and inference.
Android captures render the actual before/after JavaScript in the Android 15/API 35 development build.
Sample preferences, recipe tasks and shopping items are supplied by a local screenshot-only API.
These images illustrate the UI; they are separate from the real-server/device tests described in PR #2815.
They contain no personal diary, chat history, login details or provider keys.

The screenshot branch contains evidence only and is not part of the application patch.
