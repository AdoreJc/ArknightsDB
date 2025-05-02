# ZoneRecordItemCardView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Transform _itemCardContainer`

- `GameObject _panelLimit`

- `Text _textLeftTime`

- `GameObject _panelLeftTime`

- `Boolean m_isInited`

- `Boolean m_isLimitItem`

- `Boolean m_showLimitPart`

- `Boolean m_showLeftTime`

- `Int64 m_startTs`

- `Int64 m_endTs`

- `UIItemViewModel m_cachedViewModel`

- `UIItemCard m_itemCardView`

- `UIScaler m_itemCardScaler`


## Properties

- `UIItemCard itemCard`

- `UIScaler itemCardScaler`

- `Boolean isShowLimitPart`

- `Boolean isShowLeftTime`


## Methods

- `Void set_onItemClick(Action`1)`

- `UIItemCard get_itemCard()`

- `UIScaler get_itemCardScaler()`

- `Boolean get_isShowLimitPart()`

- `Void set_isShowLimitPart(Boolean)`

- `Boolean get_isShowLeftTime()`

- `Void set_isShowLeftTime(Boolean)`

- `Void Render(Int32, UIItemViewModel, Color)`

- `Void _InitIfNot()`

- `Void _UpdateLimitPart()`

- `Void _UpdateLeftTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordItemCardView : MonoBehaviour, IHotfixable
{
	private Transform _itemCardContainer; // 0x18
	private GameObject _panelLimit; // 0x20
	private Text _textLeftTime; // 0x28
	private GameObject _panelLeftTime; // 0x30
	private Boolean m_isInited; // 0x38
	private Boolean m_isLimitItem; // 0x39
	private Boolean m_showLimitPart; // 0x3a
	private Boolean m_showLeftTime; // 0x3b
	private Int64 m_startTs; // 0x40
	private Int64 m_endTs; // 0x48
	private UIItemViewModel m_cachedViewModel; // 0x50
	private UIItemCard m_itemCardView; // 0x58
	private UIScaler m_itemCardScaler; // 0x60
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_get_itemCard; // 0x8
	private static DelegateBridge __Hotfix0_get_itemCardScaler; // 0x10
	private static DelegateBridge __Hotfix0_get_isShowLimitPart; // 0x18
	private static DelegateBridge __Hotfix0_set_isShowLimitPart; // 0x20
	private static DelegateBridge __Hotfix0_get_isShowLeftTime; // 0x28
	private static DelegateBridge __Hotfix0_set_isShowLeftTime; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__UpdateLimitPart; // 0x48
	private static DelegateBridge __Hotfix0__UpdateLeftTime; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Action`1 onItemClick { set; }
	public UIItemCard itemCard { get; }
	public UIScaler itemCardScaler { get; }
	public Boolean isShowLimitPart { get; set; }
	public Boolean isShowLeftTime { get; set; }

	// RVA: 0x2fc0644 VA: 0x75955d8644
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2fc0720 VA: 0x75955d8720
	public UIItemCard get_itemCard() { }
	// RVA: 0x2fc0788 VA: 0x75955d8788
	public UIScaler get_itemCardScaler() { }
	// RVA: 0x2fc07f0 VA: 0x75955d87f0
	public Boolean get_isShowLimitPart() { }
	// RVA: 0x2fc0858 VA: 0x75955d8858
	public Void set_isShowLimitPart(Boolean value) { }
	// RVA: 0x2fc09f4 VA: 0x75955d89f4
	public Boolean get_isShowLeftTime() { }
	// RVA: 0x2fc0a5c VA: 0x75955d8a5c
	public Void set_isShowLeftTime(Boolean value) { }
	// RVA: 0x2fc0d00 VA: 0x75955d8d00
	public Void Render(Int32 index, UIItemViewModel viewModel, Color mainColor) { }
	// RVA: 0x2fc0ec4 VA: 0x75955d8ec4
	private Void _InitIfNot() { }
	// RVA: 0x2fc08dc VA: 0x75955d88dc
	private Void _UpdateLimitPart() { }
	// RVA: 0x2fc0ae0 VA: 0x75955d8ae0
	private Void _UpdateLeftTime() { }
	// RVA: 0x2fc1074 VA: 0x75955d9074
	public Void .ctor() { }
}
```