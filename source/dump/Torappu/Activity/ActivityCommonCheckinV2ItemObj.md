# ActivityCommonCheckinV2ItemObj

**Namespace:** `Torappu.Activity`


## Fields

- `Transform _itemContainer`

- `Single _itemScaler`

- `LayoutElement _layoutElement`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(CheckinCardSubObjViewModel)`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinV2ItemObj : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Single _itemScaler; // 0x20
	private LayoutElement _layoutElement; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30d1664 VA: 0x75956e9664
	private Void _InitIfNot() { }
	// RVA: 0x30d1840 VA: 0x75956e9840
	public Void Render(CheckinCardSubObjViewModel viewModel) { }
	// RVA: 0x30d19f4 VA: 0x75956e99f4
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x30d1af4 VA: 0x75956e9af4
	public Void .ctor() { }
}
```