# HomeAPUseApItemObj

**Namespace:** `Torappu.UI.Home`


## Fields

- `UIItemCard _itemCard`

- `Transform _container`

- `Text _chosenCount`

- `Single _scaleFactor`

- `GameObject _minusObj`

- `GameObject _backSelectObj`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `Int32 m_pos`


## Methods

- `Void set_refreshTime(Action`1)`

- `Void _InitItemIfNot()`

- `Void CleanEvent()`

- `Void RenderItem(UIItemViewModel, Int32, Action`1, Action`1, Func`2, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAPUseApItemObj : MonoBehaviour, IHotfixable
{
	private UIItemCard _itemCard; // 0x18
	private Transform _container; // 0x20
	private Text _chosenCount; // 0x28
	private Single _scaleFactor; // 0x30
	private GameObject _minusObj; // 0x38
	private GameObject _backSelectObj; // 0x40
	public Action`1 cleanEvent; // 0x48
	private Boolean m_isInited; // 0x50
	private UIItemCard m_itemCard; // 0x58
	private Int32 m_pos; // 0x60
	private static Color ADDITIVE_COLOR; // 0x0
	private static DelegateBridge __Hotfix0_set_refreshTime; // 0x10
	private static DelegateBridge __Hotfix0__InitItemIfNot; // 0x18
	private static DelegateBridge __Hotfix0_CleanEvent; // 0x20
	private static DelegateBridge __Hotfix0_RenderItem; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 refreshTime { set; }

	// RVA: 0x282a8b8 VA: 0x7594e428b8
	public Void set_refreshTime(Action`1 value) { }
	// RVA: 0x282a960 VA: 0x7594e42960
	private Void _InitItemIfNot() { }
	// RVA: 0x282aaf4 VA: 0x7594e42af4
	public Void CleanEvent() { }
	// RVA: 0x282ab8c VA: 0x7594e42b8c
	public Void RenderItem(UIItemViewModel itemInfo, Int32 count, Action`1 clickEvent, Action`1 cleanEvent, Func`2 OnLongClick, Int32 position) { }
	// RVA: 0x282adb0 VA: 0x7594e42db0
	public Void .ctor() { }
	// RVA: 0x282ae30 VA: 0x7594e42e30
	private static Void .cctor() { }
}
```