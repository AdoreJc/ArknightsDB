# BuffAdapter

**Namespace:** ` `


## Fields

- `BuildingStationSelectBuffList m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BuffAdapter : SimpleLayoutAdapter
{
	private BuildingStationSelectBuffList m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3d986a8 VA: 0x75963b06a8
	public Void .ctor(BuildingStationSelectBuffList closure) { }
	// RVA: 0x3d98b4c VA: 0x75963b0b4c
	public override Int32 get_count() { }
	// RVA: 0x3d98bd4 VA: 0x75963b0bd4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```