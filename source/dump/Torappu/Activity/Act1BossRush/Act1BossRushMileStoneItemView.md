# Act1BossRushMileStoneItemView

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `UIColorGraphic _btnRaycast`

- `TwoStateToggle _toggleCanReceive`

- `GameObject _panelComplete`

- `Text _textLevel`

- `Text _textItemName`

- `Text _textItemCount`

- `RectTransform _itemViewContainer`

- `Single _scaleInfo`

- `TwoStateToggle _toggleTextConst`

- `UIItemCard m_itemCard`

- `String m_cacheId`

- `Boolean m_hasInited`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Act1BossRushMileStoneItemViewModel)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMileStoneItemView : MonoBehaviour, IHotfixable
{
	private UIColorGraphic _btnRaycast; // 0x18
	private TwoStateToggle _toggleCanReceive; // 0x20
	private GameObject _panelComplete; // 0x28
	private Text _textLevel; // 0x30
	private Text _textItemName; // 0x38
	private Text _textItemCount; // 0x40
	private RectTransform _itemViewContainer; // 0x48
	private Single _scaleInfo; // 0x50
	private TwoStateToggle _toggleTextConst; // 0x58
	private UIItemCard m_itemCard; // 0x60
	private Action`1 <onItemClick>k__BackingField; // 0x68
	private String m_cacheId; // 0x70
	private Boolean m_hasInited; // 0x78
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClick { get; set; }

	// RVA: 0x3192010 VA: 0x75957aa010
	private Action`1 get_onItemClick() { }
	// RVA: 0x3191c40 VA: 0x75957a9c40
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x3191cc4 VA: 0x75957a9cc4
	public Void Render(Act1BossRushMileStoneItemViewModel viewModel) { }
	// RVA: 0x31921f8 VA: 0x75957aa1f8
	public Void OnClick() { }
	// RVA: 0x3192080 VA: 0x75957aa080
	private Void _InitIfNot() { }
	// RVA: 0x31922a8 VA: 0x75957aa2a8
	public Void .ctor() { }
}
```