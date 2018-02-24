<a name='contents'></a>
# Contents [#](#contents 'Go To Here')

- [CacheService](#T-Scorchio-Services-CacheService 'Scorchio.Services.CacheService')
  - [Add\`\`1(o,key)](#M-Scorchio-Services-CacheService-Add``1-``0,System-String- 'Scorchio.Services.CacheService.Add``1(``0,System.String)')
  - [Clear(key)](#M-Scorchio-Services-CacheService-Clear-System-String- 'Scorchio.Services.CacheService.Clear(System.String)')
  - [Exists(key)](#M-Scorchio-Services-CacheService-Exists-System-String- 'Scorchio.Services.CacheService.Exists(System.String)')
  - [Get\`\`1(key)](#M-Scorchio-Services-CacheService-Get``1-System-String- 'Scorchio.Services.CacheService.Get``1(System.String)')
- [CookieService](#T-Scorchio-Services-CookieService 'Scorchio.Services.CookieService')
  - [#ctor()](#M-Scorchio-Services-CookieService-#ctor 'Scorchio.Services.CookieService.#ctor')
  - [#ctor(request,response)](#M-Scorchio-Services-CookieService-#ctor-System-Web-HttpRequestBase,System-Web-HttpResponseBase- 'Scorchio.Services.CookieService.#ctor(System.Web.HttpRequestBase,System.Web.HttpResponseBase)')
  - [Expire(key)](#M-Scorchio-Services-CookieService-Expire-System-String- 'Scorchio.Services.CookieService.Expire(System.String)')
  - [GetValue(key)](#M-Scorchio-Services-CookieService-GetValue-System-String- 'Scorchio.Services.CookieService.GetValue(System.String)')
  - [GetValue\`\`1(key)](#M-Scorchio-Services-CookieService-GetValue``1-System-String- 'Scorchio.Services.CookieService.GetValue``1(System.String)')
  - [SetValue(key,value)](#M-Scorchio-Services-CookieService-SetValue-System-String,System-Object- 'Scorchio.Services.CookieService.SetValue(System.String,System.Object)')
  - [SetValue(key,value,expires)](#M-Scorchio-Services-CookieService-SetValue-System-String,System-Object,System-DateTime- 'Scorchio.Services.CookieService.SetValue(System.String,System.Object,System.DateTime)')
- [EncryptionService](#T-Scorchio-Services-EncryptionService 'Scorchio.Services.EncryptionService')
  - [#ctor()](#M-Scorchio-Services-EncryptionService-#ctor 'Scorchio.Services.EncryptionService.#ctor')
  - [Decrypt(buffer,vector)](#M-Scorchio-Services-EncryptionService-Decrypt-System-Byte[],System-Byte[]- 'Scorchio.Services.EncryptionService.Decrypt(System.Byte[],System.Byte[])')
  - [DecryptNumber(textToDecrypt)](#M-Scorchio-Services-EncryptionService-DecryptNumber-System-String- 'Scorchio.Services.EncryptionService.DecryptNumber(System.String)')
  - [DecryptString(textToDecrypt)](#M-Scorchio-Services-EncryptionService-DecryptString-System-String- 'Scorchio.Services.EncryptionService.DecryptString(System.String)')
  - [DecryptString(textToDecrypt,key)](#M-Scorchio-Services-EncryptionService-DecryptString-System-String,System-String- 'Scorchio.Services.EncryptionService.DecryptString(System.String,System.String)')
  - [Encrypt(buffer,vector)](#M-Scorchio-Services-EncryptionService-Encrypt-System-Byte[],System-Byte[]- 'Scorchio.Services.EncryptionService.Encrypt(System.Byte[],System.Byte[])')
  - [EncryptString(textToEncrypt)](#M-Scorchio-Services-EncryptionService-EncryptString-System-String- 'Scorchio.Services.EncryptionService.EncryptString(System.String)')
  - [EncryptString(textToEncrypt)](#M-Scorchio-Services-EncryptionService-EncryptString-System-Int32- 'Scorchio.Services.EncryptionService.EncryptString(System.Int32)')
  - [EncryptString(textToEncrypt,key)](#M-Scorchio-Services-EncryptionService-EncryptString-System-String,System-String- 'Scorchio.Services.EncryptionService.EncryptString(System.String,System.String)')
  - [Transform(buffer,transform)](#M-Scorchio-Services-EncryptionService-Transform-System-Byte[],System-Security-Cryptography-ICryptoTransform- 'Scorchio.Services.EncryptionService.Transform(System.Byte[],System.Security.Cryptography.ICryptoTransform)')
  - [UrlSafeConvertFromBase64String(safeBase64)](#M-Scorchio-Services-EncryptionService-UrlSafeConvertFromBase64String-System-String- 'Scorchio.Services.EncryptionService.UrlSafeConvertFromBase64String(System.String)')
  - [UrlSafeConvertToBase64String(bytes)](#M-Scorchio-Services-EncryptionService-UrlSafeConvertToBase64String-System-Byte[]- 'Scorchio.Services.EncryptionService.UrlSafeConvertToBase64String(System.Byte[])')
- [ICacheService](#T-Scorchio-Services-ICacheService 'Scorchio.Services.ICacheService')
  - [Add\`\`1(o,key)](#M-Scorchio-Services-ICacheService-Add``1-``0,System-String- 'Scorchio.Services.ICacheService.Add``1(``0,System.String)')
  - [Clear(key)](#M-Scorchio-Services-ICacheService-Clear-System-String- 'Scorchio.Services.ICacheService.Clear(System.String)')
  - [Exists(key)](#M-Scorchio-Services-ICacheService-Exists-System-String- 'Scorchio.Services.ICacheService.Exists(System.String)')
  - [Get\`\`1(key)](#M-Scorchio-Services-ICacheService-Get``1-System-String- 'Scorchio.Services.ICacheService.Get``1(System.String)')
- [ICookieService](#T-Scorchio-Services-ICookieService 'Scorchio.Services.ICookieService')
  - [Expire(key)](#M-Scorchio-Services-ICookieService-Expire-System-String- 'Scorchio.Services.ICookieService.Expire(System.String)')
  - [GetValue(key)](#M-Scorchio-Services-ICookieService-GetValue-System-String- 'Scorchio.Services.ICookieService.GetValue(System.String)')
  - [GetValue\`\`1(key)](#M-Scorchio-Services-ICookieService-GetValue``1-System-String- 'Scorchio.Services.ICookieService.GetValue``1(System.String)')
  - [SetValue(key,value)](#M-Scorchio-Services-ICookieService-SetValue-System-String,System-Object- 'Scorchio.Services.ICookieService.SetValue(System.String,System.Object)')
  - [SetValue(key,value,expires)](#M-Scorchio-Services-ICookieService-SetValue-System-String,System-Object,System-DateTime- 'Scorchio.Services.ICookieService.SetValue(System.String,System.Object,System.DateTime)')
- [IEncryptionService](#T-Scorchio-Services-IEncryptionService 'Scorchio.Services.IEncryptionService')
  - [DecryptNumber(textToDecrypt)](#M-Scorchio-Services-IEncryptionService-DecryptNumber-System-String- 'Scorchio.Services.IEncryptionService.DecryptNumber(System.String)')
  - [DecryptString(textToDecrypt)](#M-Scorchio-Services-IEncryptionService-DecryptString-System-String- 'Scorchio.Services.IEncryptionService.DecryptString(System.String)')
  - [DecryptString(textToDecrypt,key)](#M-Scorchio-Services-IEncryptionService-DecryptString-System-String,System-String- 'Scorchio.Services.IEncryptionService.DecryptString(System.String,System.String)')
  - [EncryptString(textToEncrypt)](#M-Scorchio-Services-IEncryptionService-EncryptString-System-String- 'Scorchio.Services.IEncryptionService.EncryptString(System.String)')
  - [EncryptString(textToEncrypt)](#M-Scorchio-Services-IEncryptionService-EncryptString-System-Int32- 'Scorchio.Services.IEncryptionService.EncryptString(System.Int32)')
  - [EncryptString(textToEncrypt,key)](#M-Scorchio-Services-IEncryptionService-EncryptString-System-String,System-String- 'Scorchio.Services.IEncryptionService.EncryptString(System.String,System.String)')

<a name='assembly'></a>
# Scorchio.Services [#](#assembly 'Go To Here') [=](#contents 'Back To Contents')

<a name='T-Scorchio-Services-CacheService'></a>
## CacheService [#](#T-Scorchio-Services-CacheService 'Go To Here') [=](#contents 'Back To Contents')

##### Namespace

Scorchio.Services

##### Summary

Cache Service.

##### See Also

- [Scorchio.Services.ICacheService](#T-Scorchio-Services-ICacheService 'Scorchio.Services.ICacheService')

<a name='M-Scorchio-Services-CacheService-Add``1-``0,System-String-'></a>
### Add\`\`1(o,key) `method` [#](#M-Scorchio-Services-CacheService-Add``1-``0,System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Adds the specified o.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| o | [\`\`0](#T-``0 '``0') | The o. |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T |  |

<a name='M-Scorchio-Services-CacheService-Clear-System-String-'></a>
### Clear(key) `method` [#](#M-Scorchio-Services-CacheService-Clear-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Clears the specified key.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-CacheService-Exists-System-String-'></a>
### Exists(key) `method` [#](#M-Scorchio-Services-CacheService-Exists-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Existses the specified key.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-CacheService-Get``1-System-String-'></a>
### Get\`\`1(key) `method` [#](#M-Scorchio-Services-CacheService-Get``1-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Gets the specified key.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T |  |

<a name='T-Scorchio-Services-CookieService'></a>
## CookieService [#](#T-Scorchio-Services-CookieService 'Go To Here') [=](#contents 'Back To Contents')

##### Namespace

Scorchio.Services

##### Summary

Cookie Service.

##### See Also

- [Scorchio.Services.ICookieService](#T-Scorchio-Services-ICookieService 'Scorchio.Services.ICookieService')

<a name='M-Scorchio-Services-CookieService-#ctor'></a>
### #ctor() `constructor` [#](#M-Scorchio-Services-CookieService-#ctor 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Initializes a new instance of the [CookieService](#T-Scorchio-Services-CookieService 'Scorchio.Services.CookieService') class.

##### Parameters

This constructor has no parameters.

<a name='M-Scorchio-Services-CookieService-#ctor-System-Web-HttpRequestBase,System-Web-HttpResponseBase-'></a>
### #ctor(request,response) `constructor` [#](#M-Scorchio-Services-CookieService-#ctor-System-Web-HttpRequestBase,System-Web-HttpResponseBase- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Initializes a new instance of the [CookieService](#T-Scorchio-Services-CookieService 'Scorchio.Services.CookieService') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| request | [System.Web.HttpRequestBase](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.HttpRequestBase 'System.Web.HttpRequestBase') | The request. |
| response | [System.Web.HttpResponseBase](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Web.HttpResponseBase 'System.Web.HttpResponseBase') | The response. |

<a name='M-Scorchio-Services-CookieService-Expire-System-String-'></a>
### Expire(key) `method` [#](#M-Scorchio-Services-CookieService-Expire-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Expires the specified key.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-CookieService-GetValue-System-String-'></a>
### GetValue(key) `method` [#](#M-Scorchio-Services-CookieService-GetValue-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Gets the value.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-CookieService-GetValue``1-System-String-'></a>
### GetValue\`\`1(key) `method` [#](#M-Scorchio-Services-CookieService-GetValue``1-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Gets the value of a cookie with the given key.

##### Returns

The value converted into type T

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of value the cookie contains. |

<a name='M-Scorchio-Services-CookieService-SetValue-System-String,System-Object-'></a>
### SetValue(key,value) `method` [#](#M-Scorchio-Services-CookieService-SetValue-System-String,System-Object- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Sets a cookie that will expire with users browser session.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value. |

<a name='M-Scorchio-Services-CookieService-SetValue-System-String,System-Object,System-DateTime-'></a>
### SetValue(key,value,expires) `method` [#](#M-Scorchio-Services-CookieService-SetValue-System-String,System-Object,System-DateTime- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Sets the value.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value. |
| expires | [System.DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') | The expires. |

<a name='T-Scorchio-Services-EncryptionService'></a>
## EncryptionService [#](#T-Scorchio-Services-EncryptionService 'Go To Here') [=](#contents 'Back To Contents')

##### Namespace

Scorchio.Services

##### Summary

Encryption Service.

##### See Also

- [Scorchio.Services.IEncryptionService](#T-Scorchio-Services-IEncryptionService 'Scorchio.Services.IEncryptionService')

<a name='M-Scorchio-Services-EncryptionService-#ctor'></a>
### #ctor() `constructor` [#](#M-Scorchio-Services-EncryptionService-#ctor 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Initializes a new instance of the [EncryptionService](#T-Scorchio-Services-EncryptionService 'Scorchio.Services.EncryptionService') class.

##### Parameters

This constructor has no parameters.

<a name='M-Scorchio-Services-EncryptionService-Decrypt-System-Byte[],System-Byte[]-'></a>
### Decrypt(buffer,vector) `method` [#](#M-Scorchio-Services-EncryptionService-Decrypt-System-Byte[],System-Byte[]- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Decrypts the specified buffer.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The buffer. |
| vector | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The vector. |

<a name='M-Scorchio-Services-EncryptionService-DecryptNumber-System-String-'></a>
### DecryptNumber(textToDecrypt) `method` [#](#M-Scorchio-Services-EncryptionService-DecryptNumber-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Decrypts the number.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToDecrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to decrypt. |

<a name='M-Scorchio-Services-EncryptionService-DecryptString-System-String-'></a>
### DecryptString(textToDecrypt) `method` [#](#M-Scorchio-Services-EncryptionService-DecryptString-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Decrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToDecrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to decrypt. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.ArgumentException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.ArgumentException 'System.ArgumentException') | Not a valid encrypted string;encrypted |

<a name='M-Scorchio-Services-EncryptionService-DecryptString-System-String,System-String-'></a>
### DecryptString(textToDecrypt,key) `method` [#](#M-Scorchio-Services-EncryptionService-DecryptString-System-String,System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Decrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToDecrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to decrypt. |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The ket. |

<a name='M-Scorchio-Services-EncryptionService-Encrypt-System-Byte[],System-Byte[]-'></a>
### Encrypt(buffer,vector) `method` [#](#M-Scorchio-Services-EncryptionService-Encrypt-System-Byte[],System-Byte[]- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Encrypts the specified buffer.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The buffer. |
| vector | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The vector. |

<a name='M-Scorchio-Services-EncryptionService-EncryptString-System-String-'></a>
### EncryptString(textToEncrypt) `method` [#](#M-Scorchio-Services-EncryptionService-EncryptString-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Encrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToEncrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to encrypt. |

<a name='M-Scorchio-Services-EncryptionService-EncryptString-System-Int32-'></a>
### EncryptString(textToEncrypt) `method` [#](#M-Scorchio-Services-EncryptionService-EncryptString-System-Int32- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Encrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToEncrypt | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The text to encrypt. |

<a name='M-Scorchio-Services-EncryptionService-EncryptString-System-String,System-String-'></a>
### EncryptString(textToEncrypt,key) `method` [#](#M-Scorchio-Services-EncryptionService-EncryptString-System-String,System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

*Inherit from parent.*

##### Summary

Encrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToEncrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to encrypt. |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The encryptionKey. |

<a name='M-Scorchio-Services-EncryptionService-Transform-System-Byte[],System-Security-Cryptography-ICryptoTransform-'></a>
### Transform(buffer,transform) `method` [#](#M-Scorchio-Services-EncryptionService-Transform-System-Byte[],System-Security-Cryptography-ICryptoTransform- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Transforms the specified buffer.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The buffer. |
| transform | [System.Security.Cryptography.ICryptoTransform](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Security.Cryptography.ICryptoTransform 'System.Security.Cryptography.ICryptoTransform') | The transform. |

<a name='M-Scorchio-Services-EncryptionService-UrlSafeConvertFromBase64String-System-String-'></a>
### UrlSafeConvertFromBase64String(safeBase64) `method` [#](#M-Scorchio-Services-EncryptionService-UrlSafeConvertFromBase64String-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Safely converts to a base64 string excluding unwanted characters.

##### Returns

URL safe Base64 string

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| safeBase64 | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The safe base64. |

<a name='M-Scorchio-Services-EncryptionService-UrlSafeConvertToBase64String-System-Byte[]-'></a>
### UrlSafeConvertToBase64String(bytes) `method` [#](#M-Scorchio-Services-EncryptionService-UrlSafeConvertToBase64String-System-Byte[]- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Safely converts to a base64 string excluding unwanted characters.

##### Returns

URL safe Base64 string

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The bytes. |

<a name='T-Scorchio-Services-ICacheService'></a>
## ICacheService [#](#T-Scorchio-Services-ICacheService 'Go To Here') [=](#contents 'Back To Contents')

##### Namespace

Scorchio.Services

##### Summary

Cache Service Interface.

<a name='M-Scorchio-Services-ICacheService-Add``1-``0,System-String-'></a>
### Add\`\`1(o,key) `method` [#](#M-Scorchio-Services-ICacheService-Add``1-``0,System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Adds the specified o.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| o | [\`\`0](#T-``0 '``0') | The o. |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T |  |

<a name='M-Scorchio-Services-ICacheService-Clear-System-String-'></a>
### Clear(key) `method` [#](#M-Scorchio-Services-ICacheService-Clear-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Clears the specified key.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-ICacheService-Exists-System-String-'></a>
### Exists(key) `method` [#](#M-Scorchio-Services-ICacheService-Exists-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Existses the specified key.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-ICacheService-Get``1-System-String-'></a>
### Get\`\`1(key) `method` [#](#M-Scorchio-Services-ICacheService-Get``1-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Gets the specified key.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T |  |

<a name='T-Scorchio-Services-ICookieService'></a>
## ICookieService [#](#T-Scorchio-Services-ICookieService 'Go To Here') [=](#contents 'Back To Contents')

##### Namespace

Scorchio.Services

##### Summary

Cookie Service Interface.

<a name='M-Scorchio-Services-ICookieService-Expire-System-String-'></a>
### Expire(key) `method` [#](#M-Scorchio-Services-ICookieService-Expire-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Expires the specified key.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-ICookieService-GetValue-System-String-'></a>
### GetValue(key) `method` [#](#M-Scorchio-Services-ICookieService-GetValue-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Gets the value.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

<a name='M-Scorchio-Services-ICookieService-GetValue``1-System-String-'></a>
### GetValue\`\`1(key) `method` [#](#M-Scorchio-Services-ICookieService-GetValue``1-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Gets the value of a cookie with the given key.

##### Returns

The value converted into type T

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of value the cookie contains. |

<a name='M-Scorchio-Services-ICookieService-SetValue-System-String,System-Object-'></a>
### SetValue(key,value) `method` [#](#M-Scorchio-Services-ICookieService-SetValue-System-String,System-Object- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Sets a cookie that will expire with users browser session.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value. |

<a name='M-Scorchio-Services-ICookieService-SetValue-System-String,System-Object,System-DateTime-'></a>
### SetValue(key,value,expires) `method` [#](#M-Scorchio-Services-ICookieService-SetValue-System-String,System-Object,System-DateTime- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Sets the value.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |
| value | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The value. |
| expires | [System.DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') | The expires. |

<a name='T-Scorchio-Services-IEncryptionService'></a>
## IEncryptionService [#](#T-Scorchio-Services-IEncryptionService 'Go To Here') [=](#contents 'Back To Contents')

##### Namespace

Scorchio.Services

##### Summary

Encryption Service Interface.

<a name='M-Scorchio-Services-IEncryptionService-DecryptNumber-System-String-'></a>
### DecryptNumber(textToDecrypt) `method` [#](#M-Scorchio-Services-IEncryptionService-DecryptNumber-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Decrypts the number.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToDecrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to decrypt. |

<a name='M-Scorchio-Services-IEncryptionService-DecryptString-System-String-'></a>
### DecryptString(textToDecrypt) `method` [#](#M-Scorchio-Services-IEncryptionService-DecryptString-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Decrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToDecrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to decrypt. |

<a name='M-Scorchio-Services-IEncryptionService-DecryptString-System-String,System-String-'></a>
### DecryptString(textToDecrypt,key) `method` [#](#M-Scorchio-Services-IEncryptionService-DecryptString-System-String,System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Decrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToDecrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to decrypt. |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The ket. |

<a name='M-Scorchio-Services-IEncryptionService-EncryptString-System-String-'></a>
### EncryptString(textToEncrypt) `method` [#](#M-Scorchio-Services-IEncryptionService-EncryptString-System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Encrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToEncrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to encrypt. |

<a name='M-Scorchio-Services-IEncryptionService-EncryptString-System-Int32-'></a>
### EncryptString(textToEncrypt) `method` [#](#M-Scorchio-Services-IEncryptionService-EncryptString-System-Int32- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Encrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToEncrypt | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The text to encrypt. |

<a name='M-Scorchio-Services-IEncryptionService-EncryptString-System-String,System-String-'></a>
### EncryptString(textToEncrypt,key) `method` [#](#M-Scorchio-Services-IEncryptionService-EncryptString-System-String,System-String- 'Go To Here') [=](#contents 'Back To Contents')

##### Summary

Encrypts the string.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| textToEncrypt | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The text to encrypt. |
| key | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The key. |
