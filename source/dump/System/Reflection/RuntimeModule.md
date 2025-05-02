# RuntimeModule

**Namespace:** `System.Reflection`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimeModule : Module
{
	internal IntPtr _impl; // 0x10
	internal Assembly assembly; // 0x18
	internal String fqname; // 0x20
	internal String name; // 0x28
	internal String scopename; // 0x30
	internal Boolean is_resource; // 0x38
	internal Int32 token; // 0x3c

	public override Assembly Assembly { get; }
	public override String ScopeName { get; }
	public override Guid ModuleVersionId { get; }
	public override String FullyQualifiedName { get; }

	// RVA: 0x5ff6c04 VA: 0x759860ec04
	public override Assembly get_Assembly() { }
	// RVA: 0x5ff6c0c VA: 0x759860ec0c
	public override String get_ScopeName() { }
	// RVA: 0x5ff6c14 VA: 0x759860ec14
	public override Guid get_ModuleVersionId() { }
	// RVA: 0x5ff6c24 VA: 0x759860ec24
	public override String get_FullyQualifiedName() { }
	// RVA: 0x5ff6c2c VA: 0x759860ec2c
	public override Boolean IsResource() { }
	// RVA: 0x5ff6c34 VA: 0x759860ec34
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff6c9c VA: 0x759860ec9c
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff6d0c VA: 0x759860ed0c
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff6d7c VA: 0x759860ed7c
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff6e14 VA: 0x759860ee14
	internal RuntimeAssembly GetRuntimeAssembly() { }
	// RVA: 0x5ff6e8c VA: 0x759860ee8c
	internal override Guid GetModuleVersionId() { }
	// RVA: 0x5ff6f0c VA: 0x759860ef0c
	private static Void GetGuidInternal(IntPtr module, Byte[] guid) { }
	// RVA: 0x5ff6f10 VA: 0x759860ef10
	public Void .ctor() { }
}
```