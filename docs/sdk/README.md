# SDK

### Available Operations

* [get](#get) - Get user information
* [get](#get) - Get account information

## get

Get user information

### Example Usage

```typescript
import { SDK } from "frame";
import { GetUserInfoResponse } from "frame/dist/sdk/models/operations";

const sdk = new SDK();

sdk.sdk.get({
  bearerAuth: "YOUR_BEARER_TOKEN_HERE",
}).then((res: GetUserInfoResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```

## get

Get account information

### Example Usage

```typescript
import { SDK } from "frame";
import { GetAccountResponse } from "frame/dist/sdk/models/operations";

const sdk = new SDK();

sdk.sdk.get({
  accountId: 548814,
}).then((res: GetAccountResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
