# UnityLikeShouldSerializeContractResolver

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UnityLikeShouldSerializeContractResolver : DefaultContractResolver
{
	private static BindingFlags s_bindingFlags; // 0x0
	private static IDictionary`2 s_cachedAttributeQueries; // 0x8


	// RVA: 0x34ffd78 VA: 0x7595b17d78
	protected override JsonProperty CreateProperty(MemberInfo member, MemberSerialization memberSerialization) { }
	// RVA: 0x34ffd84 VA: 0x7595b17d84
	protected override List`1 GetSerializableMembers(Type type) { }
	// RVA: 0x34ffe28 VA: 0x7595b17e28
	private static Void GetDeclaredMembers(Type declaredType, List`1 membersToFill) { }
	// RVA: 0x35000a0 VA: 0x7595b180a0
	private static Boolean HasAttribute(MemberInfo element, Type attributeType) { }
	// RVA: 0x VA: 0x0
	private static Boolean HasAttribute(MemberInfo element) { }
	// RVA: 0x3500114 VA: 0x7595b18114
	public static Attribute GetAttribute(MemberInfo element, Type attributeType, Boolean shouldCache) { }
	// RVA: 0x3500370 VA: 0x7595b18370
	protected override JsonArrayContract CreateArrayContract(Type objectType) { }
	// RVA: 0x34ffd20 VA: 0x7595b17d20
	public Void .ctor() { }
	// RVA: 0x3500378 VA: 0x7595b18378
	private static Void .cctor() { }
}
```