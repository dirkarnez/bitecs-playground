[bitecs-playground](https://dirkarnez.github.io/bitecs-playground)
==================================================================
### TODOs
- [ ] integration with game / 3d libraries
- [ ] debugging tools
  - https://github.com/Hubs-Foundation/hubs/blob/master/src/react-components/debug-panel/ECSSidebar.js
    - ```js
      import * as bitComponents from "../../bit-components";
      import { defineQuery, getEntityComponents, removeEntity } from "bitecs";
      
      const bitComponentNames = new Map();
      for (const [name, Component] of Object.entries(bitComponents)) {
        bitComponentNames.set(Component, name);
      }
      ```

### Notes
- `defineQuery` = make a predicate
- `enterQuery` = similar to a thenable function which start the querying
