# ResourcesAPI

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class ResourcesAPI
{
	private static ResourcesAPI s_DefaultAPI; // 0x0
	private static ResourcesAPI <overrideAPI>k__BackingField; // 0x8

	internal static ResourcesAPI ActiveAPI { get; }
	public static ResourcesAPI overrideAPI { get; }

	// RVA: 0x6881760 VA: 0x7598e99760
	internal static ResourcesAPI get_ActiveAPI() { }
	// RVA: 0x6881808 VA: 0x7598e99808
	public static ResourcesAPI get_overrideAPI() { }
	// RVA: 0x6881860 VA: 0x7598e99860
	protected internal Void .ctor() { }
	// RVA: 0x6881868 VA: 0x7598e99868
	protected internal virtual Object[] FindObjectsOfTypeAll(Type systemTypeInstance) { }
	// RVA: 0x68818a4 VA: 0x7598e998a4
	protected internal virtual Shader FindShaderByName(String name) { }
	// RVA: 0x68818e0 VA: 0x7598e998e0
	protected internal virtual Object Load(String path, Type systemTypeInstance) { }
	// RVA: 0x6881924 VA: 0x7598e99924
	protected internal virtual Object[] LoadAll(String path, Type systemTypeInstance) { }
	// RVA: 0x6881968 VA: 0x7598e99968
	protected internal virtual ResourceRequest LoadAsync(String path, Type systemTypeInstance) { }
	// RVA: 0x68819dc VA: 0x7598e999dc
	protected internal virtual Void UnloadAsset(Object assetToUnload) { }
	// RVA: 0x6881a18 VA: 0x7598e99a18
	private static Void .cctor() { }
}
```