# BossRushRelicUpgradeView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `GameObject _objUpgradePart`

- `GameObject _objLackPart`

- `Text _txtName`

- `Text _txtLevel`

- `Text _txtDesNow`

- `Text _txtDesNext`

- `Text _txtToUpgrade`

- `Image _imgRelicIcon`

- `Text _txtTokenName`

- `Text _txtTokenCount`

- `Action <onBackClickedAction>k__BackingField`

- `Boolean m_hasInited`

- `String m_relicId`


## Properties

- `Action onBackClickedAction`


## Methods

- `Action get_onBackClickedAction()`

- `Void set_onBackClickedAction(Action)`

- `Void set_onUpgradeClickedAction(Action`1)`

- `Void _InitIfNot()`

- `Void EventOnUpgradeClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicUpgradeView : DataBinder`1
{
	private GameObject _objUpgradePart; // 0x20
	private GameObject _objLackPart; // 0x28
	private Text _txtName; // 0x30
	private Text _txtLevel; // 0x38
	private Text _txtDesNow; // 0x40
	private Text _txtDesNext; // 0x48
	private Text _txtToUpgrade; // 0x50
	private Image _imgRelicIcon; // 0x58
	private Text _txtTokenName; // 0x60
	private Text _txtTokenCount; // 0x68
	private Action <onBackClickedAction>k__BackingField; // 0x70
	private Action`1 <onUpgradeClickedAction>k__BackingField; // 0x78
	private Boolean m_hasInited; // 0x80
	private String m_relicId; // 0x88
	private static DelegateBridge __Hotfix0_get_onBackClickedAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onBackClickedAction; // 0x8
	private static DelegateBridge __Hotfix0_get_onUpgradeClickedAction; // 0x10
	private static DelegateBridge __Hotfix0_set_onUpgradeClickedAction; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_EventOnUpgradeClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onBackClickedAction { get; set; }
	private Action`1 onUpgradeClickedAction { get; set; }

	// RVA: 0x2e5f54c VA: 0x759547754c
	private Action get_onBackClickedAction() { }
	// RVA: 0x2e5eb30 VA: 0x7595476b30
	public Void set_onBackClickedAction(Action value) { }
	// RVA: 0x2e5f5b4 VA: 0x75954775b4
	private Action`1 get_onUpgradeClickedAction() { }
	// RVA: 0x2e5eaac VA: 0x7595476aac
	public Void set_onUpgradeClickedAction(Action`1 value) { }
	// RVA: 0x2e5f61c VA: 0x759547761c
	public override Void OnValueChanged(BossRushRelicUpgradeViewProperty property) { }
	// RVA: 0x2e5fb14 VA: 0x7595477b14
	private Void _InitIfNot() { }
	// RVA: 0x2e5fcc0 VA: 0x7595477cc0
	public Void EventOnUpgradeClick() { }
	// RVA: 0x2e5fd70 VA: 0x7595477d70
	public Void .ctor() { }
}
```