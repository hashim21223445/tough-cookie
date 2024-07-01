<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tough-cookie](./tough-cookie.md) &gt; [Store](./tough-cookie.store.md) &gt; [getAllCookies](./tough-cookie.store.getallcookies.md)

## Store.getAllCookies() method

Gets all the cookies in the store.

**Signature:**

```typescript
getAllCookies(): Promise<Cookie[]>;
```
**Returns:**

Promise&lt;[Cookie](./tough-cookie.cookie.md)<!-- -->\[\]&gt;

## Remarks

- Cookies SHOULD be returned in creation order to preserve sorting via [cookieCompare()](./tough-cookie.cookiecompare.md)<!-- -->.
