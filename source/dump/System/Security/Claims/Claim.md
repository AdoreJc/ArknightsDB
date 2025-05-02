# Claim

**Namespace:** `System.Security.Claims`


## Fields

- `String m_issuer`

- `String m_originalIssuer`

- `String m_type`

- `String m_value`

- `String m_valueType`

- `Object m_propertyLock`

- `ClaimsIdentity m_subject`


## Properties

- `ClaimsIdentity Subject`

- `String Type`

- `String Value`


## Methods

- `Void OnDeserializedMethod(StreamingContext)`

- `ClaimsIdentity get_Subject()`

- `String get_Type()`

- `String get_Value()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Claims
public class Claim
{
	private String m_issuer; // 0x10
	private String m_originalIssuer; // 0x18
	private String m_type; // 0x20
	private String m_value; // 0x28
	private String m_valueType; // 0x30
	private Byte[] m_userSerializationData; // 0x38
	private Dictionary`2 m_properties; // 0x40
	private Object m_propertyLock; // 0x48
	private ClaimsIdentity m_subject; // 0x50

	public IDictionary`2 Properties { get; }
	public ClaimsIdentity Subject { get; set; }
	public String Type { get; }
	public String Value { get; }

	// RVA: 0x5f78be4 VA: 0x7598590be4
	public Void .ctor(String type, String value, String valueType, String issuer, String originalIssuer, ClaimsIdentity subject) { }
	// RVA: 0x5f78c04 VA: 0x7598590c04
	internal Void .ctor(String type, String value, String valueType, String issuer, String originalIssuer, ClaimsIdentity subject, String propertyKey, String propertyValue) { }
	// RVA: 0x5f78ff4 VA: 0x7598590ff4
	protected Void .ctor(Claim other, ClaimsIdentity subject) { }
	// RVA: 0x5f79374 VA: 0x7598591374
	private Void OnDeserializedMethod(StreamingContext context) { }
	// RVA: 0x5f78eb4 VA: 0x7598590eb4
	public IDictionary`2 get_Properties() { }
	// RVA: 0x5f793dc VA: 0x75985913dc
	public ClaimsIdentity get_Subject() { }
	// RVA: 0x5f793e4 VA: 0x75985913e4
	internal Void set_Subject(ClaimsIdentity value) { }
	// RVA: 0x5f793ec VA: 0x75985913ec
	public String get_Type() { }
	// RVA: 0x5f793f4 VA: 0x75985913f4
	public String get_Value() { }
	// RVA: 0x5f793fc VA: 0x75985913fc
	public virtual Claim Clone(ClaimsIdentity identity) { }
	// RVA: 0x5f7946c VA: 0x759859146c
	public override String ToString() { }
}
```