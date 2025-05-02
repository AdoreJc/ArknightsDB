# ManifestResourceInfo

**Namespace:** `System.Reflection`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class ManifestResourceInfo
{
	private readonly Assembly <ReferencedAssembly>k__BackingField; // 0x10
	private readonly String <FileName>k__BackingField; // 0x18
	private readonly ResourceLocation <ResourceLocation>k__BackingField; // 0x20

	public virtual Assembly ReferencedAssembly { get; }
	public virtual String FileName { get; }
	public virtual ResourceLocation ResourceLocation { get; }

	// RVA: 0x5fe60d4 VA: 0x75985fe0d4
	public Void .ctor(Assembly containingAssembly, String containingFileName, ResourceLocation resourceLocation) { }
	// RVA: 0x5fe612c VA: 0x75985fe12c
	public virtual Assembly get_ReferencedAssembly() { }
	// RVA: 0x5fe6134 VA: 0x75985fe134
	public virtual String get_FileName() { }
	// RVA: 0x5fe613c VA: 0x75985fe13c
	public virtual ResourceLocation get_ResourceLocation() { }
}
```