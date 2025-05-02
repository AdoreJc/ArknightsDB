# ClaimsIdentity

**Namespace:** `System.Security.Claims`


## Fields

- `String m_nameType`

- `String m_roleType`

- `String m_version`

- `ClaimsIdentity m_actor`

- `String m_authenticationType`

- `Object m_bootstrapContext`

- `String m_label`

- `String m_serializedNameType`

- `String m_serializedRoleType`

- `String m_serializedClaims`


## Properties

- `ClaimsIdentity Actor`


## Methods

- `ClaimsIdentity get_Actor()`

- `Void set_Actor(ClaimsIdentity)`

- `Void SafeAddClaims(IEnumerable`1)`

- `Void SafeAddClaim(Claim)`

- `Void OnSerializingMethod(StreamingContext)`

- `Void OnDeserializedMethod(StreamingContext)`

- `Void OnDeserializingMethod(StreamingContext)`

- `Void DeserializeClaims(String)`

- `String SerializeClaims()`

- `Boolean IsCircular(ClaimsIdentity)`

- `Void Deserialize(SerializationInfo, StreamingContext, Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Claims
public class ClaimsIdentity : IIdentity
{
	private Byte[] m_userSerializationData; // 0x10
	private List`1 m_instanceClaims; // 0x18
	private Collection`1 m_externalClaims; // 0x20
	private String m_nameType; // 0x28
	private String m_roleType; // 0x30
	private String m_version; // 0x38
	private ClaimsIdentity m_actor; // 0x40
	private String m_authenticationType; // 0x48
	private Object m_bootstrapContext; // 0x50
	private String m_label; // 0x58
	private String m_serializedNameType; // 0x60
	private String m_serializedRoleType; // 0x68
	private String m_serializedClaims; // 0x70

	public virtual String AuthenticationType { get; }
	public ClaimsIdentity Actor { get; set; }
	public virtual IEnumerable`1 Claims { get; }
	public virtual String Name { get; }

	// RVA: 0x5f781f4 VA: 0x75985901f4
	public Void .ctor() { }
	// RVA: 0x5f794e4 VA: 0x75985914e4
	public Void .ctor(IEnumerable`1 claims) { }
	// RVA: 0x5f79500 VA: 0x7598591500
	public Void .ctor(IIdentity identity, IEnumerable`1 claims, String authenticationType, String nameType, String roleType) { }
	// RVA: 0x5f79508 VA: 0x7598591508
	internal Void .ctor(IIdentity identity, IEnumerable`1 claims, String authenticationType, String nameType, String roleType, Boolean checkAuthType) { }
	// RVA: 0x5f7a1b4 VA: 0x75985921b4
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f7abd4 VA: 0x7598592bd4
	public virtual String get_AuthenticationType() { }
	// RVA: 0x5f7abdc VA: 0x7598592bdc
	public ClaimsIdentity get_Actor() { }
	// RVA: 0x5f7abe4 VA: 0x7598592be4
	public Void set_Actor(ClaimsIdentity value) { }
	// RVA: 0x5f7ac74 VA: 0x7598592c74
	public virtual IEnumerable`1 get_Claims() { }
	// RVA: 0x5f7ad2c VA: 0x7598592d2c
	public virtual String get_Name() { }
	// RVA: 0x5f7ad50 VA: 0x7598592d50
	public virtual ClaimsIdentity Clone() { }
	// RVA: 0x5f79c8c VA: 0x7598591c8c
	private Void SafeAddClaims(IEnumerable`1 claims) { }
	// RVA: 0x5f7a084 VA: 0x7598592084
	private Void SafeAddClaim(Claim claim) { }
	// RVA: 0x5f7aed8 VA: 0x7598592ed8
	public virtual Claim FindFirst(String type) { }
	// RVA: 0x5f7b254 VA: 0x7598593254
	private Void OnSerializingMethod(StreamingContext context) { }
	// RVA: 0x5f7b530 VA: 0x7598593530
	private Void OnDeserializedMethod(StreamingContext context) { }
	// RVA: 0x5f7b9bc VA: 0x75985939bc
	private Void OnDeserializingMethod(StreamingContext context) { }
	// RVA: 0x5f7bab8 VA: 0x7598593ab8
	protected virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f7b63c VA: 0x759859363c
	private Void DeserializeClaims(String serializedClaims) { }
	// RVA: 0x5f7b2e4 VA: 0x75985932e4
	private String SerializeClaims() { }
	// RVA: 0x5f79c54 VA: 0x7598591c54
	private Boolean IsCircular(ClaimsIdentity subject) { }
	// RVA: 0x5f7a384 VA: 0x7598592384
	private Void Deserialize(SerializationInfo info, StreamingContext context, Boolean useContext) { }
}
```