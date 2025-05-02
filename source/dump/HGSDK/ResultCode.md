# ResultCode

**Namespace:** `HGSDK`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | OK |

| 500 | HTTP_ERROR |

| 1000 | REQUEST_TIMEOUT |

| 1001 | RESPONSE_PARSE_ERROR |

| 2000 | PAY_PRODUCT_INVALID |

| 2001 | PAY_SDK_CANT_INIT_IAP |

| 2002 | PAY_INVALID_PRODUCT_IN_STORE |

| 2003 | PAY_STORE_FAILURE |

| 2004 | PAY_CANCELED |

| 2005 | PAY_SERVER_INTERNAL_ERROR |

| 2005 | PAY_RECEIPT_UPLOAD_FAILED |

| 2006 | PAY_IAP_CONFIG_EXCEPTION |

| 2007 | PAY_HAS_PENDING_ORDERS |

| 65535 | UNKNOWN |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public enum ResultCode
{
	public Int32 value__; // 0x10
	public const ResultCode OK = 0; // 0x0
	public const ResultCode HTTP_ERROR = 500; // 0x0
	public const ResultCode REQUEST_TIMEOUT = 1000; // 0x0
	public const ResultCode RESPONSE_PARSE_ERROR = 1001; // 0x0
	public const ResultCode PAY_PRODUCT_INVALID = 2000; // 0x0
	public const ResultCode PAY_SDK_CANT_INIT_IAP = 2001; // 0x0
	public const ResultCode PAY_INVALID_PRODUCT_IN_STORE = 2002; // 0x0
	public const ResultCode PAY_STORE_FAILURE = 2003; // 0x0
	public const ResultCode PAY_CANCELED = 2004; // 0x0
	public const ResultCode PAY_SERVER_INTERNAL_ERROR = 2005; // 0x0
	public const ResultCode PAY_RECEIPT_UPLOAD_FAILED = 2005; // 0x0
	public const ResultCode PAY_IAP_CONFIG_EXCEPTION = 2006; // 0x0
	public const ResultCode PAY_HAS_PENDING_ORDERS = 2007; // 0x0
	public const ResultCode UNKNOWN = 65535; // 0x0


}
```