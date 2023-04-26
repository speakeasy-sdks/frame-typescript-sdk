# SDK

### Available Operations

* [get](#get) - Get user information
* [get](#get) - Get account information

## get

Get user information

### Example Usage

```typescript
import { AxiosError } from "axios";
import { SDK } from "frame";
import { GetUserInfoResponse } from "frame/dist/sdk/models/operations";

const sdk = new SDK();

sdk.sdk.get().then((res: GetUserInfoResponse | AxiosError) => {
  if (res instanceof UsageExamplePostResponse && res.statusCode == 200) {
    // handle response
  }
});
```

## get

Get account information

### Example Usage

```typescript
import { AxiosError } from "axios";
import { SDK } from "frame";
import { GetAccountRequest, GetAccountResponse } from "frame/dist/sdk/models/operations";

const sdk = new SDK();

const req: GetAccountRequest = {
  accountId: 548814,
};

sdk.sdk.get(req).then((res: GetAccountResponse | AxiosError) => {
  if (res instanceof UsageExamplePostResponse && res.statusCode == 200) {
    // handle response
  }
});
```
