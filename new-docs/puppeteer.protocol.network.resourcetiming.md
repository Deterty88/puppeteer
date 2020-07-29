<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [ResourceTiming](./puppeteer.protocol.network.resourcetiming.md)

## Protocol.Network.ResourceTiming interface

Timing information for the request.

<b>Signature:</b>

```typescript
export interface ResourceTiming 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [connectEnd](./puppeteer.protocol.network.resourcetiming.connectend.md) | number | Connected to the remote host. |
|  [connectStart](./puppeteer.protocol.network.resourcetiming.connectstart.md) | number | Started connecting to the remote host. |
|  [dnsEnd](./puppeteer.protocol.network.resourcetiming.dnsend.md) | number | Finished DNS address resolve. |
|  [dnsStart](./puppeteer.protocol.network.resourcetiming.dnsstart.md) | number | Started DNS address resolve. |
|  [proxyEnd](./puppeteer.protocol.network.resourcetiming.proxyend.md) | number | Finished resolving proxy. |
|  [proxyStart](./puppeteer.protocol.network.resourcetiming.proxystart.md) | number | Started resolving proxy. |
|  [pushEnd](./puppeteer.protocol.network.resourcetiming.pushend.md) | number | Time the server finished pushing request. |
|  [pushStart](./puppeteer.protocol.network.resourcetiming.pushstart.md) | number | Time the server started pushing request. |
|  [receiveHeadersEnd](./puppeteer.protocol.network.resourcetiming.receiveheadersend.md) | number | Finished receiving response headers. |
|  [requestTime](./puppeteer.protocol.network.resourcetiming.requesttime.md) | number | Timing's requestTime is a baseline in seconds, while the other numbers are ticks in milliseconds relatively to this requestTime. |
|  [sendEnd](./puppeteer.protocol.network.resourcetiming.sendend.md) | number | Finished sending request. |
|  [sendStart](./puppeteer.protocol.network.resourcetiming.sendstart.md) | number | Started sending request. |
|  [sslEnd](./puppeteer.protocol.network.resourcetiming.sslend.md) | number | Finished SSL handshake. |
|  [sslStart](./puppeteer.protocol.network.resourcetiming.sslstart.md) | number | Started SSL handshake. |
|  [workerFetchStart](./puppeteer.protocol.network.resourcetiming.workerfetchstart.md) | number | Started fetch event. |
|  [workerReady](./puppeteer.protocol.network.resourcetiming.workerready.md) | number | Finished Starting ServiceWorker. |
|  [workerRespondWithSettled](./puppeteer.protocol.network.resourcetiming.workerrespondwithsettled.md) | number | Settled fetch event respondWith promise. |
|  [workerStart](./puppeteer.protocol.network.resourcetiming.workerstart.md) | number | Started running ServiceWorker. |
