# WindowsIdentity

**Namespace:** `System.Security.Principal`


## Fields

- `IntPtr _token`

- `String _type`

- `WindowsAccountType _account`

- `Boolean _authenticated`

- `String _name`

- `SerializationInfo _info`


## Methods

- `Void Dispose()`

- `Void SetToken(IntPtr)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Principal
public class WindowsIdentity : ClaimsIdentity, IIdentity, IDeserializationCallback, ISerializable, IDisposable
{
	private IntPtr _token; // 0x78
	private String _type; // 0x80
	private WindowsAccountType _account; // 0x88
	private Boolean _authenticated; // 0x8c
	private String _name; // 0x90
	private SerializationInfo _info; // 0x98
	private static IntPtr invalidWindows; // 0x0

	public sealed override String AuthenticationType { get; }
	public override String Name { get; }

	// RVA: 0x5f78178 VA: 0x7598590178
	public Void .ctor(IntPtr userToken, String type, WindowsAccountType acctType, Boolean isAuthenticated) { }
	// RVA: 0x5f7838c VA: 0x759859038c
	public Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f783d0 VA: 0x75985903d0
	public Void Dispose() { }
	// RVA: 0x5f78420 VA: 0x7598590420
	public static WindowsIdentity GetCurrent() { }
	// RVA: 0x5f784a8 VA: 0x75985904a8
	public virtual WindowsImpersonationContext Impersonate() { }
	// RVA: 0x5f78598 VA: 0x7598590598
	public sealed override String get_AuthenticationType() { }
	// RVA: 0x5f785a0 VA: 0x75985905a0
	public override String get_Name() { }
	// RVA: 0x5f78620 VA: 0x7598590620
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x5f78930 VA: 0x7598590930
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f78210 VA: 0x7598590210
	private Void SetToken(IntPtr token) { }
	// RVA: 0x5f784a4 VA: 0x75985904a4
	internal static IntPtr GetCurrentToken() { }
	// RVA: 0x5f7861c VA: 0x759859061c
	private static String GetTokenName(IntPtr token) { }
	// RVA: 0x5f78a98 VA: 0x7598590a98
	private static Void .cctor() { }
}
```