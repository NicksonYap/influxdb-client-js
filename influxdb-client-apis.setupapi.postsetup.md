<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@influxdata/influxdb-client-apis](./influxdb-client-apis.md) &gt; [SetupAPI](./influxdb-client-apis.setupapi.md) &gt; [postSetup](./influxdb-client-apis.setupapi.postsetup.md)

## SetupAPI.postSetup() method

Set up initial user, org and bucket. See [https://v2.docs.influxdata.com/v2.0/api/\#operation/PostSetup](https://v2.docs.influxdata.com/v2.0/api/#operation/PostSetup)

<b>Signature:</b>

```typescript
postSetup(request: PostSetupRequest, requestOptions?: RequestOptions): Promise<OnboardingResponse>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [PostSetupRequest](./influxdb-client-apis.postsetuprequest.md) | request parameters and body (if supported) |
|  requestOptions | [RequestOptions](./influxdb-client-apis.requestoptions.md) | optional transport options |

<b>Returns:</b>

Promise&lt;[OnboardingResponse](./influxdb-client-apis.onboardingresponse.md)<!-- -->&gt;

promise of response
