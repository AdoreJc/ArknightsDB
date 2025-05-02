# DIYFurnitureTitleVirtualView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `GameObject prefab`

- `Single rowHeight`

- `DIYViewListThemeState themeState`

- `Int32 m_viewIndex`

- `String m_text`


## Methods

- `Void SetText(String)`

- `Void SetViewIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureTitleVirtualView : VirtualView`1
{
	public GameObject prefab; // 0x20
	public List`1 rowDatas; // 0x28
	public Single rowHeight; // 0x30
	public DIYViewListThemeState themeState; // 0x34
	public Func`2 OnSelected; // 0x38
	public Func`2 OnInfo; // 0x40
	private Int32 m_viewIndex; // 0x48
	private String m_text; // 0x50
	private static DelegateBridge __Hotfix0_SetText; // 0x0
	private static DelegateBridge __Hotfix0_SetViewIndex; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_GetPreferSize; // 0x18
	private static DelegateBridge __Hotfix0_OnViewAttached; // 0x20
	private static DelegateBridge __Hotfix0_OnViewDetached; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x381eb24 VA: 0x7595e36b24
	public Void SetText(String text) { }
	// RVA: 0x381eba8 VA: 0x7595e36ba8
	public Void SetViewIndex(Int32 viewIndex) { }
	// RVA: 0x381ec24 VA: 0x7595e36c24
	public override GameObject GetPrefab() { }
	// RVA: 0x381ec8c VA: 0x7595e36c8c
	public override Single GetPreferSize() { }
	// RVA: 0x381ed50 VA: 0x7595e36d50
	protected override Void OnViewAttached() { }
	// RVA: 0x381eff8 VA: 0x7595e36ff8
	protected override Void OnViewDetached() { }
	// RVA: 0x381f05c VA: 0x7595e3705c
	public Void .ctor() { }
}
```