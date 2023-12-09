# Commands to run in terminal

- list enemies
- enemies

## What does this do

When landed on a moon, running the command shows the type and amount of spawned enemies (globally) at that moment in time.

## ChangeLog

## V1.1.1

- Reverted Off Using the `Roundmanager.update` method. This caused a lot of lag.
- Now postfixing all methods which are associated with enemy spawning
  - There is probably some root method for this but this is a quick hotfix to reduce lag

### V1.1.0

- Make the list update on the RoundManager's Update method rather than hourly
  - Should resolve issue #1 on the github

### V1.0.1

- Minor text update

### V1.0.0

- Initial release
