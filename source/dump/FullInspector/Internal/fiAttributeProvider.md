# fiAttributeProvider

**Namespace:** `FullInspector.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiAttributeProvider : MemberInfo
{
	private readonly Object[] _attributes; // 0x10

	public override Type DeclaringType { get; }
	public override MemberTypes MemberType { get; }
	public override String Name { get; }
	public override Type ReflectedType { get; }

	// RVA: 0x34d4910 VA: 0x7595aec910
	public static MemberInfo Create(Object[] attributes) { }
	// RVA: 0x34d9724 VA: 0x7595af1724
	private Void .ctor(Object[] attributes) { }
	// RVA: 0x34d9754 VA: 0x7595af1754
	public override Type get_DeclaringType() { }
	// RVA: 0x34d9794 VA: 0x7595af1794
	public override MemberTypes get_MemberType() { }
	// RVA: 0x34d97d4 VA: 0x7595af17d4
	public override String get_Name() { }
	// RVA: 0x34d9814 VA: 0x7595af1814
	public override Type get_ReflectedType() { }
	// RVA: 0x34d9854 VA: 0x7595af1854
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x34d985c VA: 0x7595af185c
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x34d9964 VA: 0x7595af1964
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
}
```