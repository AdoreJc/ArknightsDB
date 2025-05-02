# SquadGroupController

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelSquadTabs`

- `GameObject _panelDisableLock`

- `GameObject _panelSkillSelectablePredefined`

- `SquadMemberClickEvent _onSquadMemberClick`

- `GameObject _leftbtn`

- `GameObject _rightbtn`

- `GameObject _multiEditBtn`

- `GameObject _clearAllBtn`

- `GameObject _cardBanPrefab`

- `Boolean m_isInited`

- `Boolean m_isCardClickable`

- `SquadHomePlugin m_statePlugin`


## Methods

- `Void InjectPlugin(SquadHomePlugin)`

- `Void _InitIfNot()`

- `Void _OnSquadMemberClick(Int32)`

- `Void _OnShowLeftArrow(Boolean)`

- `Void _RegisterFirstEmptySlotToAVG()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadGroupController : DataBinder`1, IHotfixable
{
	private GameObject _panelSquadTabs; // 0x20
	private GameObject _panelDisableLock; // 0x28
	private GameObject _panelSkillSelectablePredefined; // 0x30
	private SquadTabView[] _tabs; // 0x38
	private SquadCardView[] _cards; // 0x40
	private SquadMemberClickEvent _onSquadMemberClick; // 0x48
	private GameObject _leftbtn; // 0x50
	private GameObject _rightbtn; // 0x58
	private GameObject _multiEditBtn; // 0x60
	private GameObject _clearAllBtn; // 0x68
	private GameObject _cardBanPrefab; // 0x70
	private Boolean m_isInited; // 0x78
	private Boolean m_isCardClickable; // 0x79
	private SquadHomePlugin m_statePlugin; // 0x80
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnSquadMemberClick; // 0x18
	private static DelegateBridge __Hotfix0__OnShowLeftArrow; // 0x20
	private static DelegateBridge __Hotfix0__RegisterFirstEmptySlotToAVG; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x23cac98 VA: 0x75949e2c98
	public Void InjectPlugin(SquadHomePlugin statePlugin) { }
	// RVA: 0x23caec4 VA: 0x75949e2ec4
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x23cb2fc VA: 0x75949e32fc
	private Void _InitIfNot() { }
	// RVA: 0x23cb6b4 VA: 0x75949e36b4
	private Void _OnSquadMemberClick(Int32 index) { }
	// RVA: 0x23cb48c VA: 0x75949e348c
	private Void _OnShowLeftArrow(Boolean isShow) { }
	// RVA: 0x23cb510 VA: 0x75949e3510
	private Void _RegisterFirstEmptySlotToAVG() { }
	// RVA: 0x23cb768 VA: 0x75949e3768
	public Void .ctor() { }
}
```