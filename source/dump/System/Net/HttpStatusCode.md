# HttpStatusCode

**Namespace:** `System.Net`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 100 | Continue |

| 101 | SwitchingProtocols |

| 102 | Processing |

| 103 | EarlyHints |

| 200 | OK |

| 201 | Created |

| 202 | Accepted |

| 203 | NonAuthoritativeInformation |

| 204 | NoContent |

| 205 | ResetContent |

| 206 | PartialContent |

| 207 | MultiStatus |

| 208 | AlreadyReported |

| 226 | IMUsed |

| 300 | MultipleChoices |

| 300 | Ambiguous |

| 301 | MovedPermanently |

| 301 | Moved |

| 302 | Found |

| 302 | Redirect |

| 303 | SeeOther |

| 303 | RedirectMethod |

| 304 | NotModified |

| 305 | UseProxy |

| 306 | Unused |

| 307 | TemporaryRedirect |

| 307 | RedirectKeepVerb |

| 308 | PermanentRedirect |

| 400 | BadRequest |

| 401 | Unauthorized |

| 402 | PaymentRequired |

| 403 | Forbidden |

| 404 | NotFound |

| 405 | MethodNotAllowed |

| 406 | NotAcceptable |

| 407 | ProxyAuthenticationRequired |

| 408 | RequestTimeout |

| 409 | Conflict |

| 410 | Gone |

| 411 | LengthRequired |

| 412 | PreconditionFailed |

| 413 | RequestEntityTooLarge |

| 414 | RequestUriTooLong |

| 415 | UnsupportedMediaType |

| 416 | RequestedRangeNotSatisfiable |

| 417 | ExpectationFailed |

| 421 | MisdirectedRequest |

| 422 | UnprocessableEntity |

| 423 | Locked |

| 424 | FailedDependency |

| 426 | UpgradeRequired |

| 428 | PreconditionRequired |

| 429 | TooManyRequests |

| 431 | RequestHeaderFieldsTooLarge |

| 451 | UnavailableForLegalReasons |

| 500 | InternalServerError |

| 501 | NotImplemented |

| 502 | BadGateway |

| 503 | ServiceUnavailable |

| 504 | GatewayTimeout |

| 505 | HttpVersionNotSupported |

| 506 | VariantAlsoNegotiates |

| 507 | InsufficientStorage |

| 508 | LoopDetected |

| 510 | NotExtended |

| 511 | NetworkAuthenticationRequired |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public enum HttpStatusCode
{
	public Int32 value__; // 0x10
	public const HttpStatusCode Continue = 100; // 0x0
	public const HttpStatusCode SwitchingProtocols = 101; // 0x0
	public const HttpStatusCode Processing = 102; // 0x0
	public const HttpStatusCode EarlyHints = 103; // 0x0
	public const HttpStatusCode OK = 200; // 0x0
	public const HttpStatusCode Created = 201; // 0x0
	public const HttpStatusCode Accepted = 202; // 0x0
	public const HttpStatusCode NonAuthoritativeInformation = 203; // 0x0
	public const HttpStatusCode NoContent = 204; // 0x0
	public const HttpStatusCode ResetContent = 205; // 0x0
	public const HttpStatusCode PartialContent = 206; // 0x0
	public const HttpStatusCode MultiStatus = 207; // 0x0
	public const HttpStatusCode AlreadyReported = 208; // 0x0
	public const HttpStatusCode IMUsed = 226; // 0x0
	public const HttpStatusCode MultipleChoices = 300; // 0x0
	public const HttpStatusCode Ambiguous = 300; // 0x0
	public const HttpStatusCode MovedPermanently = 301; // 0x0
	public const HttpStatusCode Moved = 301; // 0x0
	public const HttpStatusCode Found = 302; // 0x0
	public const HttpStatusCode Redirect = 302; // 0x0
	public const HttpStatusCode SeeOther = 303; // 0x0
	public const HttpStatusCode RedirectMethod = 303; // 0x0
	public const HttpStatusCode NotModified = 304; // 0x0
	public const HttpStatusCode UseProxy = 305; // 0x0
	public const HttpStatusCode Unused = 306; // 0x0
	public const HttpStatusCode TemporaryRedirect = 307; // 0x0
	public const HttpStatusCode RedirectKeepVerb = 307; // 0x0
	public const HttpStatusCode PermanentRedirect = 308; // 0x0
	public const HttpStatusCode BadRequest = 400; // 0x0
	public const HttpStatusCode Unauthorized = 401; // 0x0
	public const HttpStatusCode PaymentRequired = 402; // 0x0
	public const HttpStatusCode Forbidden = 403; // 0x0
	public const HttpStatusCode NotFound = 404; // 0x0
	public const HttpStatusCode MethodNotAllowed = 405; // 0x0
	public const HttpStatusCode NotAcceptable = 406; // 0x0
	public const HttpStatusCode ProxyAuthenticationRequired = 407; // 0x0
	public const HttpStatusCode RequestTimeout = 408; // 0x0
	public const HttpStatusCode Conflict = 409; // 0x0
	public const HttpStatusCode Gone = 410; // 0x0
	public const HttpStatusCode LengthRequired = 411; // 0x0
	public const HttpStatusCode PreconditionFailed = 412; // 0x0
	public const HttpStatusCode RequestEntityTooLarge = 413; // 0x0
	public const HttpStatusCode RequestUriTooLong = 414; // 0x0
	public const HttpStatusCode UnsupportedMediaType = 415; // 0x0
	public const HttpStatusCode RequestedRangeNotSatisfiable = 416; // 0x0
	public const HttpStatusCode ExpectationFailed = 417; // 0x0
	public const HttpStatusCode MisdirectedRequest = 421; // 0x0
	public const HttpStatusCode UnprocessableEntity = 422; // 0x0
	public const HttpStatusCode Locked = 423; // 0x0
	public const HttpStatusCode FailedDependency = 424; // 0x0
	public const HttpStatusCode UpgradeRequired = 426; // 0x0
	public const HttpStatusCode PreconditionRequired = 428; // 0x0
	public const HttpStatusCode TooManyRequests = 429; // 0x0
	public const HttpStatusCode RequestHeaderFieldsTooLarge = 431; // 0x0
	public const HttpStatusCode UnavailableForLegalReasons = 451; // 0x0
	public const HttpStatusCode InternalServerError = 500; // 0x0
	public const HttpStatusCode NotImplemented = 501; // 0x0
	public const HttpStatusCode BadGateway = 502; // 0x0
	public const HttpStatusCode ServiceUnavailable = 503; // 0x0
	public const HttpStatusCode GatewayTimeout = 504; // 0x0
	public const HttpStatusCode HttpVersionNotSupported = 505; // 0x0
	public const HttpStatusCode VariantAlsoNegotiates = 506; // 0x0
	public const HttpStatusCode InsufficientStorage = 507; // 0x0
	public const HttpStatusCode LoopDetected = 508; // 0x0
	public const HttpStatusCode NotExtended = 510; // 0x0
	public const HttpStatusCode NetworkAuthenticationRequired = 511; // 0x0


}
```