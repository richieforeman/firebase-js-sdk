<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth](./auth.md) &gt; [EmailAuthProvider](./auth.emailauthprovider.md) &gt; [credential](./auth.emailauthprovider.credential.md)

## EmailAuthProvider.credential() method

Initialize an [AuthCredential](./auth.authcredential.md) using an email and password.

<b>Signature:</b>

```typescript
static credential(email: string, password: string): EmailAuthCredential;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  email | string | Email address. |
|  password | string | User account password. |

<b>Returns:</b>

[EmailAuthCredential](./auth.emailauthcredential.md)

The auth provider credential.

## Example 1


```javascript
const authCredential = EmailAuthProvider.credential(email, password);
const userCredential = await signInWithCredential(auth, authCredential);

```

## Example 2


```javascript
const userCredential = await signInWithEmailAndPassword(auth, email, password);

```

