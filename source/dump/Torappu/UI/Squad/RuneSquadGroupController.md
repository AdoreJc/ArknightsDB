# RuneSquadGroupController

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SimpleLayoutContent _squadLayout`

- `SquadAdapter m_squadAdapter`

- `SquadViewModel m_squadModel`

- `SquadGroupViewModel m_squadGroupModel`

- `Boolean m_isInited`

- `SpriteHub m_professionHub`


## Methods

- `Void set_onSlotClicked(Action`1)`

- `Void _InitIfNot()`

- `Void _OnCharCardClicked(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class RuneSquadGroupController : DataBinder`1
{
	private SimpleLayoutContent _squadLayout; // 0x20
	private SquadAdapter m_squadAdapter; // 0x28
	private SquadViewModel m_squadModel; // 0x30
	private SquadGroupViewModel m_squadGroupModel; // 0x38
	private Boolean m_isInited; // 0x40
	private SpriteHub m_professionHub; // 0x48
	private Action`1 <onSlotClicked>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onSlotClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnCharCardClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onSlotClicked { get; set; }

	// RVA: 0x23c37c0 VA: 0x75949db7c0
	private Action`1 get_onSlotClicked() { }
	// RVA: 0x23c3828 VA: 0x75949db828
	public Void set_onSlotClicked(Action`1 value) { }
	// RVA: 0x23c38ac VA: 0x75949db8ac
	private Void _InitIfNot() { }
	// RVA: 0x23c3a2c VA: 0x75949dba2c
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x23c3b3c VA: 0x75949dbb3c
	private Void _OnCharCardClicked(Options options) { }
	// RVA: 0x23c3c10 VA: 0x75949dbc10
	public Void .ctor() { }
}
```