# webln.enable()

To begin interacting with WebLN APIs you'll first need to enable the provider. Calling `webln.enable()` will prompt the user for permission to use the WebLN capabilities of the browser. After that you are free to call any of the other API methods.&#x20;

#### Method&#x20;

```typescript
async function enable(): void;
```

**Example**

```javascript
if (typeof window.webln !== 'undefined') {
  try {
    await window.webln.enable();
    console.log('WebLN enabled successfully!');
  } catch (error) {
    console.error('User rejected or error occurred:', error);
  }
}
```

#### Demo

{% embed url="https://codepen.io/getalby/pen/YzYgYKE" %}
