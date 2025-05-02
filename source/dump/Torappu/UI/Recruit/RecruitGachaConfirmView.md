# RecruitGachaConfirmView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _soldText`

- `UIBlurFloatPanel _backImage`

- `Single _itemScale`

- `Image _stateIcon`

- `SimpleLayoutContent _costContent`

- `SimpleLayoutContent _targetContent`

- `GameObject _needDSTip`

- `Text _needDSNum`

- `Color _usedOutItemColor`

- `GameObject _bugDiamondShardIcon`

- `String <inputPoolId>k__BackingField`

- `Int32 m_cacheDiamond`

- `CostItemAdapter m_costAdapter`

- `CostItemAdapter m_targetAdapter`

- `Boolean m_initFlag`


## Properties

- `String inputPoolId`


## Methods

- `Void set_action(Action`1)`

- `String get_inputPoolId()`

- `Void set_inputPoolId(String)`

- `Void _InitIfNot()`

- `Void Dismiss()`

- `Void _SetStatusByDisplayConfig(DisplayConfig)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaConfirmView : PageSingleComponent
{
	private Text _soldText; // 0x20
	private UIBlurFloatPanel _backImage; // 0x28
	private Single _itemScale; // 0x30
	private Image _stateIcon; // 0x38
	private SimpleLayoutContent _costContent; // 0x40
	private SimpleLayoutContent _targetContent; // 0x48
	private GameObject _needDSTip; // 0x50
	private Text _needDSNum; // 0x58
	private Color _usedOutItemColor; // 0x60
	private GameObject _bugDiamondShardIcon; // 0x70
	private Action`1 <action>k__BackingField; // 0x78
	private String <inputPoolId>k__BackingField; // 0x80
	private Int32 m_cacheDiamond; // 0x88
	private CostItemAdapter m_costAdapter; // 0x90
	private CostItemAdapter m_targetAdapter; // 0x98
	private List`1 m_costItemModelList; // 0xa0
	private List`1 m_targetItemModelList; // 0xa8
	private Boolean m_initFlag; // 0xb0
	private static DelegateBridge __Hotfix0_get_action; // 0x0
	private static DelegateBridge __Hotfix0_set_action; // 0x8
	private static DelegateBridge __Hotfix0_get_inputPoolId; // 0x10
	private static DelegateBridge __Hotfix0_set_inputPoolId; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_SingleGacha; // 0x28
	private static DelegateBridge __Hotfix0_BatchedGacha; // 0x30
	private static DelegateBridge __Hotfix0_BuyUnlockSlot; // 0x38
	private static DelegateBridge __Hotfix0_Dismiss; // 0x40
	private static DelegateBridge __Hotfix0__SetStatusByDisplayConfig; // 0x48
	private static DelegateBridge __Hotfix0__GenerateItemFromDisplayConfig; // 0x50
	private static DelegateBridge __Hotfix0_OnClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Action`1 action { get; set; }
	public String inputPoolId { get; set; }

	// RVA: 0x2708b68 VA: 0x7594d20b68
	public Action`1 get_action() { }
	// RVA: 0x2708bd0 VA: 0x7594d20bd0
	private Void set_action(Action`1 value) { }
	// RVA: 0x2708c54 VA: 0x7594d20c54
	public String get_inputPoolId() { }
	// RVA: 0x2708cbc VA: 0x7594d20cbc
	private Void set_inputPoolId(String value) { }
	// RVA: 0x2708d40 VA: 0x7594d20d40
	private Void _InitIfNot() { }
	// RVA: 0x2709010 VA: 0x7594d21010
	public static Void SingleGacha(Action`1 gachaEvent, String poolId, SingleGachaPolicy policy) { }
	// RVA: 0x27095c4 VA: 0x7594d215c4
	public static Void BatchedGacha(Action`1 gachaEvent, String poolId, TenGachaPolicy policy) { }
	// RVA: 0x2709940 VA: 0x7594d21940
	public static Void BuyUnlockSlot(Action`1 unlockEvent, String index, Int32 price) { }
	// RVA: 0x2709de0 VA: 0x7594d21de0
	public Void Dismiss() { }
	// RVA: 0x2709348 VA: 0x7594d21348
	private Void _SetStatusByDisplayConfig(DisplayConfig config) { }
	// RVA: 0x2709e54 VA: 0x7594d21e54
	private List`1 _GenerateItemFromDisplayConfig(DisplayConfig config, Boolean isTargetItem) { }
	// RVA: 0x270a700 VA: 0x7594d22700
	public Void OnClick() { }
	// RVA: 0x270a7b0 VA: 0x7594d227b0
	public Void .ctor() { }
}
```