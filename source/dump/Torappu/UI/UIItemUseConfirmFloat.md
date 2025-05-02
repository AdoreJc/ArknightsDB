# UIItemUseConfirmFloat

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _container`

- `CanvasGroup _rootView`

- `RectTransform _backBtn`

- `Text _confirmText`

- `UIBlurFloatPanel _backImage`

- `Transform _itemContainer1`

- `Transform _itemContainer2`

- `Single _itemScale`

- `Action m_onClick`

- `UIItemCard m_costItem`

- `UIItemCard m_targetItem`

- `UIItemViewModel m_costModel`

- `UIItemViewModel m_targetModel`

- `Boolean m_isInited`


## Methods

- `Void Start()`

- `Void RenderLockedPart(Int32, String, ItemType, String, Action)`

- `Void OnClick()`

- `Void ClosePage()`

- `Void _InitIfNot()`

- `Void _RenderLockedPart(Int32, String, ItemType, String, Action)`

- `Void <_InitIfNot>b__18_0(Int32)`

- `Void <_InitIfNot>b__18_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemUseConfirmFloat : MonoBehaviour, IHotfixable
{
	private GameObject _container; // 0x18
	private CanvasGroup _rootView; // 0x20
	private RectTransform _backBtn; // 0x28
	private Text _confirmText; // 0x30
	private UIBlurFloatPanel _backImage; // 0x38
	private Transform _itemContainer1; // 0x40
	private Transform _itemContainer2; // 0x48
	private Single _itemScale; // 0x50
	private Action m_onClick; // 0x58
	private UIItemCard m_costItem; // 0x60
	private UIItemCard m_targetItem; // 0x68
	private UIItemViewModel m_costModel; // 0x70
	private UIItemViewModel m_targetModel; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_RenderLockedPart; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_ClosePage; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RenderLockedPart; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2193b58 VA: 0x75947abb58
	private Void Start() { }
	// RVA: 0x2193f40 VA: 0x75947abf40
	public Void RenderLockedPart(Int32 cost, String itemId, ItemType itemType, String confirmText, Action onClick) { }
	// RVA: 0x21941bc VA: 0x75947ac1bc
	public Void OnClick() { }
	// RVA: 0x2194260 VA: 0x75947ac260
	public Void ClosePage() { }
	// RVA: 0x2193bc0 VA: 0x75947abbc0
	private Void _InitIfNot() { }
	// RVA: 0x2194008 VA: 0x75947ac008
	private Void _RenderLockedPart(Int32 cost, String itemId, ItemType itemType, String confirmText, Action onClick) { }
	// RVA: 0x21942f4 VA: 0x75947ac2f4
	public Void .ctor() { }
	// RVA: 0x21943f8 VA: 0x75947ac3f8
	private Void <_InitIfNot>b__18_0(Int32 _) { }
	// RVA: 0x219442c VA: 0x75947ac42c
	private Void <_InitIfNot>b__18_1(Int32 _) { }
}
```