# J-Cord Examples

This repository contains examples for the Discord API Wrapper for Java: [J-Cord](https://github.com/AlienIdeology/J-Cord). <br />
These examples are also used for testing J-Cord's functionality.

- Bot: The main class for this example.
  - EventAdaptor: The example DispatcherAdaptor. Override methods to listen to events.
  - EventSubscribers: An object with methods that has `EventSubscriber` annotations. Subscribe to events via reflection.
  - Commands: The example CommandResponder. Used for J-Cord's command framework.
  - Token.json (Git Ignored. A config file to store token.)
- Client/Selfbot (Coming soon!)