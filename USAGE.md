<!-- Start SDK Example Usage -->
```typescript
import { SDK } from "frame";
import { GetUserInfoResponse } from "frame/dist/sdk/models/operations";

const sdk = new SDK();

sdk.get({
  bearerAuth: "Bearer YOUR_BEARER_TOKEN_HERE",
}).then((res: GetUserInfoResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->