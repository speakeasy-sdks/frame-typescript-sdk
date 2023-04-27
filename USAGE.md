<!-- Start SDK Example Usage -->
```typescript
import { AxiosError } from "axios";
import { SDK } from "frame";
import { GetUserInfoResponse } from "frame/dist/sdk/models/operations";

const sdk = new SDK();

sdk.get().then((res: GetUserInfoResponse | AxiosError) => {
  if (res instanceof UsageExamplePostResponse && res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->