<!-- Start SDK Example Usage [usage] -->
```typescript
import { PetStore } from "@rogwilco/pet-store";

const petStore = new PetStore();

async function run() {
  const result = await petStore.pets.listPets({});

  // Handle the result
  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->