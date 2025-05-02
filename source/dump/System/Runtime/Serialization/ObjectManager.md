# ObjectManager

**Namespace:** `System.Runtime.Serialization`


## Fields

- `DeserializationEventHandler m_onDeserializationHandler`

- `SerializationEventHandler m_onDeserializedHandler`


## Methods

- `Boolean CanCallGetType(Object)`

- `Void AddObjectHolder(ObjectHolder)`

- `Boolean GetCompletionInfo(FixupHolder, out, out, Boolean)`

- `Void FixupSpecialObject(ObjectHolder)`

- `Boolean ResolveObjectReference(ObjectHolder)`

- `Boolean DoValueTypeFixup(FieldInfo, ObjectHolder, Object)`

- `Void DoNewlyRegisteredObjectFixups(ObjectHolder)`

- `Void RegisterObject(Object, Int64, SerializationInfo, Int64, MemberInfo, Int32[])`

- `Void RegisterFixup(FixupHolder, Int64, Int64)`

- `Void RaiseOnDeserializingEvent(Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
public class ObjectManager
{
	private DeserializationEventHandler m_onDeserializationHandler; // 0x10
	private SerializationEventHandler m_onDeserializedHandler; // 0x18
	internal ObjectHolder[] m_objects; // 0x20
	internal Object m_topObject; // 0x28
	internal ObjectHolderList m_specialFixupObjects; // 0x30
	internal Int64 m_fixupCount; // 0x38
	internal ISurrogateSelector m_selector; // 0x40
	internal StreamingContext m_context; // 0x48

	internal Object TopObject { get; set; }
	internal ObjectHolderList SpecialFixupObjects { get; }

	// RVA: 0x5fb28bc VA: 0x75985ca8bc
	internal Void .ctor(ISurrogateSelector selector, StreamingContext context, Boolean checkSecurity, Boolean isCrossAppDomain) { }
	// RVA: 0x5fb2960 VA: 0x75985ca960
	private Boolean CanCallGetType(Object obj) { }
	// RVA: 0x5fb2968 VA: 0x75985ca968
	internal Void set_TopObject(Object value) { }
	// RVA: 0x5fb2970 VA: 0x75985ca970
	internal Object get_TopObject() { }
	// RVA: 0x5fb2978 VA: 0x75985ca978
	internal ObjectHolderList get_SpecialFixupObjects() { }
	// RVA: 0x5fb29f8 VA: 0x75985ca9f8
	internal ObjectHolder FindObjectHolder(Int64 objectID) { }
	// RVA: 0x5fb2a50 VA: 0x75985caa50
	internal ObjectHolder FindOrCreateObjectHolder(Int64 objectID) { }
	// RVA: 0x5fb2b28 VA: 0x75985cab28
	private Void AddObjectHolder(ObjectHolder holder) { }
	// RVA: 0x5fb2c74 VA: 0x75985cac74
	private Boolean GetCompletionInfo(FixupHolder fixup, out ObjectHolder holder, out Object member, Boolean bThrowIfMissing) { }
	// RVA: 0x5fb2f98 VA: 0x75985caf98
	private Void FixupSpecialObject(ObjectHolder holder) { }
	// RVA: 0x5fb3dc8 VA: 0x75985cbdc8
	private Boolean ResolveObjectReference(ObjectHolder holder) { }
	// RVA: 0x5fb376c VA: 0x75985cb76c
	private Boolean DoValueTypeFixup(FieldInfo memberToFix, ObjectHolder holder, Object value) { }
	// RVA: 0x5fb4060 VA: 0x75985cc060
	internal Void CompleteObject(ObjectHolder holder, Boolean bObjectFullyComplete) { }
	// RVA: 0x5fb3cf0 VA: 0x75985cbcf0
	private Void DoNewlyRegisteredObjectFixups(ObjectHolder holder) { }
	// RVA: 0x5fb48f8 VA: 0x75985cc8f8
	public virtual Object GetObject(Int64 objectID) { }
	// RVA: 0x5fb49ac VA: 0x75985cc9ac
	internal Void RegisterString(String obj, Int64 objectID, SerializationInfo info, Int64 idOfContainingObj, MemberInfo member) { }
	// RVA: 0x5fb4bdc VA: 0x75985ccbdc
	public Void RegisterObject(Object obj, Int64 objectID, SerializationInfo info, Int64 idOfContainingObj, MemberInfo member, Int32[] arrayIndex) { }
	// RVA: 0x5fb3478 VA: 0x75985cb478
	internal Void CompleteISerializableObject(Object obj, SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fb55cc VA: 0x75985cd5cc
	internal static RuntimeConstructorInfo GetConstructor(RuntimeType t) { }
	// RVA: 0x5fb5708 VA: 0x75985cd708
	public virtual Void DoFixups() { }
	// RVA: 0x5fb5b88 VA: 0x75985cdb88
	private Void RegisterFixup(FixupHolder fixup, Int64 objectToBeFixed, Int64 objectRequired) { }
	// RVA: 0x5fb5dc0 VA: 0x75985cddc0
	public virtual Void RecordFixup(Int64 objectToBeFixed, MemberInfo member, Int64 objectRequired) { }
	// RVA: 0x5fb60c0 VA: 0x75985ce0c0
	public virtual Void RecordDelayedFixup(Int64 objectToBeFixed, String memberName, Int64 objectRequired) { }
	// RVA: 0x5fb6238 VA: 0x75985ce238
	public virtual Void RecordArrayElementFixup(Int64 arrayToBeFixed, Int32[] indices, Int64 objectRequired) { }
	// RVA: 0x5fb63b0 VA: 0x75985ce3b0
	public virtual Void RaiseDeserializationEvent() { }
	// RVA: 0x5fb63fc VA: 0x75985ce3fc
	internal virtual Void AddOnDeserialization(DeserializationEventHandler handler) { }
	// RVA: 0x5fb648c VA: 0x75985ce48c
	internal virtual Void AddOnDeserialized(Object obj) { }
	// RVA: 0x5fb6528 VA: 0x75985ce528
	internal virtual Void RaiseOnDeserializedEvent(Object obj) { }
	// RVA: 0x5fb65b4 VA: 0x75985ce5b4
	public Void RaiseOnDeserializingEvent(Object obj) { }
}
```