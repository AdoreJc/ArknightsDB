# ActivityCommonCheckinItemObj

**Namespace:** `Torappu.Activity`


## Fields

- `Transform _itemContainer`

- `Single _itemScaler`

- `RectTransform _receiveImg`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int32, UIItemViewModel, Boolean)`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinItemObj : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Single _itemScaler; // 0x20
	private RectTransform _receiveImg; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge __Hotfix0_GetHashString; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30d049c VA: 0x75956e849c
	private Void _InitIfNot() { }
	// RVA: 0x30cffa4 VA: 0x75956e7fa4
	public Void Render(Int32 index, UIItemViewModel itemViewModel, Boolean isReceived) { }
	// RVA: 0x30d0764 VA: 0x75956e8764
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x30d06c4 VA: 0x75956e86c4
	public static Single GetHashString(String hashId) { }
	// RVA: 0x30d0864 VA: 0x75956e8864
	public Void .ctor() { }
}
```