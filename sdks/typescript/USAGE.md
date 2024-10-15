<!-- Start SDK Example Usage [usage] -->
```typescript
import { SpeakeasyTestbedPetstore } from "@rogwilco/speakeasy-testbed-petstore";

const speakeasyTestbedPetstore = new SpeakeasyTestbedPetstore();

async function run() {
  const result = await speakeasyTestbedPetstore.pets.listPets({});

  // Handle the result
  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->