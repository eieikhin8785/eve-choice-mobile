# Eve Choice Mobile

React Native + Expo shell for the future Eve Choice mobile client. It currently provides a lightweight discovery preview and establishes the navigation/product direction for the native experience.

## Planned product surface

- Buy/rent discovery.
- Location and property-type browsing.
- Listing detail, saved listings, inquiries, and viewing requests.
- Account and owner/agent management.
- The same versioned API semantics as the web app.

Production mobile workflows are intentionally deferred from the first web release. The future client will consume the contract in [`../api/openapi.yaml`](../api/openapi.yaml).

## Run locally

```bash
npm install
npm start
```

Expo dev tools will provide the simulator, emulator, or device connection options.

