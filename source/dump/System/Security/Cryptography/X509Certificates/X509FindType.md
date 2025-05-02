# X509FindType

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | FindByThumbprint |

| 1 | FindBySubjectName |

| 2 | FindBySubjectDistinguishedName |

| 3 | FindByIssuerName |

| 4 | FindByIssuerDistinguishedName |

| 5 | FindBySerialNumber |

| 6 | FindByTimeValid |

| 7 | FindByTimeNotYetValid |

| 8 | FindByTimeExpired |

| 9 | FindByTemplateName |

| 10 | FindByApplicationPolicy |

| 11 | FindByCertificatePolicy |

| 12 | FindByExtension |

| 13 | FindByKeyUsage |

| 14 | FindBySubjectKeyIdentifier |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public enum X509FindType
{
	public Int32 value__; // 0x10
	public const X509FindType FindByThumbprint = 0; // 0x0
	public const X509FindType FindBySubjectName = 1; // 0x0
	public const X509FindType FindBySubjectDistinguishedName = 2; // 0x0
	public const X509FindType FindByIssuerName = 3; // 0x0
	public const X509FindType FindByIssuerDistinguishedName = 4; // 0x0
	public const X509FindType FindBySerialNumber = 5; // 0x0
	public const X509FindType FindByTimeValid = 6; // 0x0
	public const X509FindType FindByTimeNotYetValid = 7; // 0x0
	public const X509FindType FindByTimeExpired = 8; // 0x0
	public const X509FindType FindByTemplateName = 9; // 0x0
	public const X509FindType FindByApplicationPolicy = 10; // 0x0
	public const X509FindType FindByCertificatePolicy = 11; // 0x0
	public const X509FindType FindByExtension = 12; // 0x0
	public const X509FindType FindByKeyUsage = 13; // 0x0
	public const X509FindType FindBySubjectKeyIdentifier = 14; // 0x0


}
```