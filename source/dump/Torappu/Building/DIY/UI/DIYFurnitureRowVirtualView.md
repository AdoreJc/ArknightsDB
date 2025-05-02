# DIYFurnitureRowVirtualView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject rowPrefab`

- `Single rowHeight`

- `DIYViewListThemeState themeState`

- `Int32 m_viewIndex`


## Methods

- `Void SetViewIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureRowVirtualView : VirtualView`1
{
	public GameObject rowPrefab; // 0x20
	public List`1 rowDatas; // 0x28
	public Single rowHeight; // 0x30
	public DIYViewListThemeState themeState; // 0x34
	public Func`2 OnSelected; // 0x38
	public Func`2 OnInfo; // 0x40
	private Int32 m_viewIndex; // 0x48
	private static DelegateBridge __Hotfix0_SetViewIndex; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x8
	private static DelegateBridge __Hotfix0_GetPreferSize; // 0x10
	private static DelegateBridge __Hotfix0_OnViewAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnViewDetached; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x381b8dc VA: 0x7595e338dc
	public Void SetViewIndex(Int32 viewIndex) { }
	// RVA: 0x381b958 VA: 0x7595e33958
	public override GameObject GetPrefab() { }
	// RVA: 0x381b9c0 VA: 0x7595e339c0
	public override Single GetPreferSize() { }
	// RVA: 0x381ba28 VA: 0x7595e33a28
	protected override Void OnViewAttached() { }
	// RVA: 0x381bdf8 VA: 0x7595e33df8
	protected override Void OnViewDetached() { }
	// RVA: 0x381be5c VA: 0x7595e33e5c
	public Void .ctor() { }
}
```