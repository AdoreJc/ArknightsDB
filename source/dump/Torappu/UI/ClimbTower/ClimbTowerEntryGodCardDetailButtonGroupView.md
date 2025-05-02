# ClimbTowerEntryGodCardDetailButtonGroupView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _buttonContent`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `String m_selectedCardId`


## Methods

- `Void set_onButtonClicked(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryGodCardDetailButtonGroupView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _buttonContent; // 0x20
	private Boolean m_hasInited; // 0x28
	private Adapter m_adapter; // 0x30
	private ListDict`2 m_cardModelMap; // 0x38
	private String m_selectedCardId; // 0x40
	private Action`1 <onButtonClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onButtonClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onButtonClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onButtonClicked { get; set; }

	// RVA: 0x2c651b8 VA: 0x759527d1b8
	private Action`1 get_onButtonClicked() { }
	// RVA: 0x2c65220 VA: 0x759527d220
	public Void set_onButtonClicked(Action`1 value) { }
	// RVA: 0x2c652a4 VA: 0x759527d2a4
	public override Void OnValueChanged(ClimbTowerEntryGodCardDetailProperty property) { }
	// RVA: 0x2c65380 VA: 0x759527d380
	private Void _InitIfNot() { }
	// RVA: 0x2c654e4 VA: 0x759527d4e4
	public Void .ctor() { }
}
```