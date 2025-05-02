# Act1LockSquadGroupController

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `SimpleLayoutContent _squadLayout`

- `GameObject _panelInterlockLogo`

- `GameObject _panelDisableLock`

- `SquadAdapter m_squadAdapter`

- `SquadViewModel m_squadModel`

- `Boolean m_isInited`

- `SpriteHub m_professionHub`

- `Boolean m_isCardClickable`


## Methods

- `Void set_onSlotClicked(Action`1)`

- `Void _InitIfNot()`

- `Void _OnCharCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockSquadGroupController : DataBinder`1
{
	private SimpleLayoutContent _squadLayout; // 0x20
	private GameObject _panelInterlockLogo; // 0x28
	private GameObject _panelDisableLock; // 0x30
	private SquadAdapter m_squadAdapter; // 0x38
	private SquadViewModel m_squadModel; // 0x40
	private Boolean m_isInited; // 0x48
	private SpriteHub m_professionHub; // 0x50
	private Boolean m_isCardClickable; // 0x58
	private Action`1 <onSlotClicked>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onSlotClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnCharCardClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onSlotClicked { get; set; }

	// RVA: 0x33d2e94 VA: 0x75959eae94
	private Action`1 get_onSlotClicked() { }
	// RVA: 0x33d2efc VA: 0x75959eaefc
	public Void set_onSlotClicked(Action`1 value) { }
	// RVA: 0x33d2f80 VA: 0x75959eaf80
	private Void _InitIfNot() { }
	// RVA: 0x33d3100 VA: 0x75959eb100
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x33d3264 VA: 0x75959eb264
	private Void _OnCharCardClicked(Int32 index) { }
	// RVA: 0x33d3324 VA: 0x75959eb324
	public Void .ctor() { }
}
```