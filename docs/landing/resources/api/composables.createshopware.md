<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@shopware-pwa/composables](./composables.md) &gt; [createShopware](./composables.createshopware.md)

## createShopware() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Create ShopwarePlugin vue instance. Shpware PWA composables rely on this config.

<b>Signature:</b>

```typescript
export declare function createShopware(app: App, options: {
    initialStore: any;
    shopwareDefaults: ApiDefaults;
    apiInstance: ShopwareApiInstance;
}): {
    install(app: App, options?: {
        enableDevtools: boolean;
    } | undefined): void;
    _a: App;
    _e: EffectScope;
    apiInstance: ShopwareApiInstance;
    state: {
        interceptors: {};
        sharedStore: any;
        shopwareDefaults: {
            [x: string]: {
                p?: number | undefined;
                limit?: number | undefined;
                sort?: string | undefined;
                order?: string | undefined;
                term?: string | undefined;
                ids?: string[] | undefined;
                associations?: {
                    [x: string]: {
                        associations?: any | undefined;
                        sort?: string | {
                            field: string;
                            order: string;
                            naturalSorting: boolean;
                        }[] | undefined;
                    };
                } | undefined;
                grouping?: {
                    field: string;
                } | undefined;
                properties?: string | never[] | undefined;
                manufacturer?: string | never[] | undefined;
                includes?: {
                    [x: string]: string[];
                } | undefined;
                query?: string | undefined;
            };
        };
    } | undefined;
};
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  app | App |  |
|  options | { initialStore: any; shopwareDefaults: ApiDefaults; apiInstance: ShopwareApiInstance; } |  |

<b>Returns:</b>

{ install(app: App, options?: { enableDevtools: boolean; } \| undefined): void; \_a: App; \_e: EffectScope; apiInstance: ShopwareApiInstance; state: { interceptors: {}; sharedStore: any; shopwareDefaults: { \[x: string\]: { p?: number \| undefined; limit?: number \| undefined; sort?: string \| undefined; order?: string \| undefined; term?: string \| undefined; ids?: string\[\] \| undefined; associations?: { \[x: string\]: { associations?: any \| undefined; sort?: string \| { field: string; order: string; naturalSorting: boolean; }\[\] \| undefined; }; } \| undefined; grouping?: { field: string; } \| undefined; properties?: string \| never\[\] \| undefined; manufacturer?: string \| never\[\] \| undefined; includes?: { \[x: string\]: string\[\]; } \| undefined; query?: string \| undefined; }; }; } \| undefined; }

