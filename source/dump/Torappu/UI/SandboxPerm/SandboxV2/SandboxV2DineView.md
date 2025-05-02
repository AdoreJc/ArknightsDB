# SandboxV2DineView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ItemCard _itemCardPrefab`

- `Single _itemCardScale`

- `GameObject _validStatusInfoPanel`

- `GameObject _invalidStatusInfoPanel`

- `GameObject _validStatusDurationPanel`

- `GameObject _invalidStatusDurationPanel`

- `GameObject _validDineInfoPanel`

- `GameObject _invalidDineInfoPanel`

- `GameObject _validDinePanel`

- `GameObject _invalidDinePanel`

- `Transform _statusInfoItemHolder`

- `Transform _dineInfoItemHolder`

- `Image _avatarImage`

- `Text _nameText`

- `Text _statusFoodNameText`

- `Text _statusFoodDurationText`

- `Text _statusFoodUsageText`

- `Text _dineFoodNameText`

- `Text _dineFoodDurationText`

- `Text _dineFoodUsageText`

- `SandboxV2DineItemLoopAdapter _itemLoopAdapter`

- `LoopVerticalScrollRect _itemLoopRect`

- `GameObject _emptyPanel`

- `Boolean m_hasInit`

- `SandboxV2ItemCard m_statusFoodItem`

- `SandboxV2ItemCard m_dineFoodItem`

- `String m_cachedStatusFoodId`

- `String m_cachedDineFoodId`

- `Action <backEvent>k__BackingField`

- `Action <cookEvent>k__BackingField`

- `Action <confirmEvent>k__BackingField`


## Properties

- `Action backEvent`

- `Action cookEvent`

- `Action confirmEvent`


## Methods

- `Action get_backEvent()`

- `Void set_backEvent(Action)`

- `Action get_cookEvent()`

- `Void set_cookEvent(Action)`

- `Void set_itemSelectEvent(Action`1)`

- `Action get_confirmEvent()`

- `Void set_confirmEvent(Action)`

- `Void OnBackEvent()`

- `Void OnCookEvent()`

- `Void OnConfirmEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DineView : DataBinder`1, IHotfixable
{
	private SandboxV2ItemCard _itemCardPrefab; // 0x20
	private Single _itemCardScale; // 0x28
	private GameObject _validStatusInfoPanel; // 0x30
	private GameObject _invalidStatusInfoPanel; // 0x38
	private GameObject _validStatusDurationPanel; // 0x40
	private GameObject _invalidStatusDurationPanel; // 0x48
	private GameObject _validDineInfoPanel; // 0x50
	private GameObject _invalidDineInfoPanel; // 0x58
	private GameObject _validDinePanel; // 0x60
	private GameObject _invalidDinePanel; // 0x68
	private Transform _statusInfoItemHolder; // 0x70
	private Transform _dineInfoItemHolder; // 0x78
	private Image _avatarImage; // 0x80
	private Text _nameText; // 0x88
	private Text _statusFoodNameText; // 0x90
	private Text _statusFoodDurationText; // 0x98
	private Text _statusFoodUsageText; // 0xa0
	private Text _dineFoodNameText; // 0xa8
	private Text _dineFoodDurationText; // 0xb0
	private Text _dineFoodUsageText; // 0xb8
	private SandboxV2DineItemLoopAdapter _itemLoopAdapter; // 0xc0
	private LoopVerticalScrollRect _itemLoopRect; // 0xc8
	private GameObject _emptyPanel; // 0xd0
	private Boolean m_hasInit; // 0xd8
	private SandboxV2ItemCard m_statusFoodItem; // 0xe0
	private SandboxV2ItemCard m_dineFoodItem; // 0xe8
	private String m_cachedStatusFoodId; // 0xf0
	private String m_cachedDineFoodId; // 0xf8
	private Action <backEvent>k__BackingField; // 0x100
	private Action <cookEvent>k__BackingField; // 0x108
	private Action`1 <itemSelectEvent>k__BackingField; // 0x110
	private Action <confirmEvent>k__BackingField; // 0x118
	private static DelegateBridge __Hotfix0_get_backEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_backEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_cookEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_cookEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x20
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x28
	private static DelegateBridge __Hotfix0_get_confirmEvent; // 0x30
	private static DelegateBridge __Hotfix0_set_confirmEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x40
	private static DelegateBridge __Hotfix0_OnCookEvent; // 0x48
	private static DelegateBridge __Hotfix0_OnConfirmEvent; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private Action backEvent { get; set; }
	private Action cookEvent { get; set; }
	private Action`1 itemSelectEvent { get; set; }
	private Action confirmEvent { get; set; }

	// RVA: 0x250a3a0 VA: 0x7594b223a0
	private Action get_backEvent() { }
	// RVA: 0x2508c5c VA: 0x7594b20c5c
	public Void set_backEvent(Action value) { }
	// RVA: 0x250a408 VA: 0x7594b22408
	private Action get_cookEvent() { }
	// RVA: 0x2508ce0 VA: 0x7594b20ce0
	public Void set_cookEvent(Action value) { }
	// RVA: 0x250a470 VA: 0x7594b22470
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x2508d64 VA: 0x7594b20d64
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x250a4d8 VA: 0x7594b224d8
	private Action get_confirmEvent() { }
	// RVA: 0x2508de8 VA: 0x7594b20de8
	public Void set_confirmEvent(Action value) { }
	// RVA: 0x250a540 VA: 0x7594b22540
	public Void OnBackEvent() { }
	// RVA: 0x250a5dc VA: 0x7594b225dc
	public Void OnCookEvent() { }
	// RVA: 0x250a678 VA: 0x7594b22678
	public Void OnConfirmEvent() { }
	// RVA: 0x250a714 VA: 0x7594b22714
	private Void _InitIfNot() { }
	// RVA: 0x250a934 VA: 0x7594b22934
	public override Void OnValueChanged(SandboxV2DineProperty property) { }
	// RVA: 0x250adbc VA: 0x7594b22dbc
	public Void .ctor() { }
}
```