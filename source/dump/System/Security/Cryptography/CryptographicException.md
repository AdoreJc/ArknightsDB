# CryptographicException

**Namespace:** `System.Security.Cryptography`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class CryptographicException : SystemException
{
	private const Int32 FORMAT_MESSAGE_IGNORE_INSERTS; // 0x0
	private const Int32 FORMAT_MESSAGE_FROM_SYSTEM; // 0x0
	private const Int32 FORMAT_MESSAGE_ARGUMENT_ARRAY; // 0x0


	// RVA: 0x5f4f7e0 VA: 0x75985677e0
	public Void .ctor() { }
	// RVA: 0x5f4df54 VA: 0x7598565f54
	public Void .ctor(String message) { }
	// RVA: 0x5f4f84c VA: 0x759856784c
	public Void .ctor(String format, String insert) { }
	// RVA: 0x5f4f8e4 VA: 0x75985678e4
	public Void .ctor(String message, Exception inner) { }
	// RVA: 0x5f4f90c VA: 0x759856790c
	public Void .ctor(Int32 hr) { }
	// RVA: 0x5f4f970 VA: 0x7598567970
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f4f978 VA: 0x7598567978
	private static Void ThrowCryptographicException(Int32 hr) { }
}
```