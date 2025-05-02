# BackAdapter

**Namespace:** ` `


## Fields

- `Act36sideZoneMapContainer m_closure`

- `Single m_focusPageIndex`


## Methods

- `Void NotifyFocusPage(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BackAdapter : SimpleLayoutAdapter
{
	private Act36sideZoneMapContainer m_closure; // 0x20
	private Single m_focusPageIndex; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_NotifyFocusPage; // 0x18

	public override Int32 count { get; }

	// RVA: 0x324f904 VA: 0x7595867904
	public Void .ctor(Act36sideZoneMapContainer closure) { }
	// RVA: 0x324f9a0 VA: 0x75958679a0
	public override Int32 get_count() { }
	// RVA: 0x324faa4 VA: 0x7595867aa4
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x324fd00 VA: 0x7595867d00
	public Void NotifyFocusPage(Single pageIndex) { }
}
```