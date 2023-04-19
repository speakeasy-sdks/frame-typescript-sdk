<!-- Start SDK Example Usage -->
```typescript
import {
  GetUserInfoResponse
} from "frame/dist/sdk/models/operations";

import { AxiosError } from "axios";
import { SDK } from "frame";
const sdk = new SDK();

sdk.get().then((res: GetUserInfoResponse | AxiosError) => {
   // handle response
});
```
<!-- End SDK Example Usage -->