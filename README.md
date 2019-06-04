# org.wicka

## Goals

### Rough Sketch

Utilise the OSGi resolver over ES6 modules.

Types of content:

- Server-side modules.

- Hosted client-side modules.

- Remote client-side modules (e.g. CDN).

Modes of deployment:

- Within OSGi framework (probably wrap modules in bundles transparently).

- Without OSGi framework, custom type of resource. Can we use Felix resolver outside of a framework?

We need to be able to generate an import map to serve to the client.
