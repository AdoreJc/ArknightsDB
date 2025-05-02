# StageUseApItemObj

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIItemCard _itemCard`

- `Transform _container`

- `GameObject _chosenIcon`

- `Single _scaleFactor`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`


## Methods

- `Void _InitItem()`

- `Void RenderItem(UIItemViewModel, Boolean, Action`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageUseApItemObj : MonoBehaviour, IHotfixable
{
	private UIItemCard _itemCard; // 0x18
	private Transform _container; // 0x20
	private GameObject _chosenIcon; // 0x28
	private Single _scaleFactor; // 0x30
	public Action`1 refreshTime; // 0x38
	private Boolean m_isInited; // 0x40
	private UIItemCard m_itemCard; // 0x48
	private static Color ADDITIVE_COLOR; // 0x0
	private static DelegateBridge __Hotfix0__InitItem; // 0x10
	private static DelegateBridge __Hotfix0_RenderItem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f8ad90 VA: 0x75955a2d90
	private Void _InitItem() { }
	// RVA: 0x2f8af3c VA: 0x75955a2f3c
	public Void RenderItem(UIItemViewModel itemInfo, Boolean selected, Action`1 clickEvent, Int32 position) { }
	// RVA: 0x2f8b0a8 VA: 0x75955a30a8
	public Void .ctor() { }
	// RVA: 0x2f8b128 VA: 0x75955a3128
	private static Void .cctor() { }
}
```