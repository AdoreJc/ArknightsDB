# CommonSquadGroupController

**Namespace:** `Torappu.UI`


## Fields

- `SimpleLayoutContent _squadLayout`

- `Image _startBattleImg`

- `Boolean m_isInited`

- `CommonSquadGroupViewModel m_squadGroupModel`

- `SquadViewModel m_squadModel`

- `String m_teamId`

- `SpriteHub m_professionHub`

- `SquadAdapter m_squadAdapter`

- `UIStateFinder m_finder`

- `SquadStartButtonTypeEnum m_startBtnType`

- `Boolean m_isStartBtnRefreshed`


## Methods

- `Void _InitIfNot()`

- `Void _RefreshStartBtnBg()`

- `Void _OnCharCardClicked(Options)`

- `Void EventOnMultiFormationClicked()`

- `Void EventOnAssistBtnClick()`

- `Void EventOnAssistClearClick()`

- `Void EventOnStartBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonSquadGroupController : DataBinder`1
{
	private SimpleLayoutContent _squadLayout; // 0x20
	private Image _startBattleImg; // 0x28
	private Boolean m_isInited; // 0x30
	private CommonSquadGroupViewModel m_squadGroupModel; // 0x38
	private SquadViewModel m_squadModel; // 0x40
	private String m_teamId; // 0x48
	private SpriteHub m_professionHub; // 0x50
	private SquadAdapter m_squadAdapter; // 0x58
	private UIStateFinder m_finder; // 0x60
	private SquadStartButtonTypeEnum m_startBtnType; // 0x70
	private Boolean m_isStartBtnRefreshed; // 0x74
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RefreshStartBtnBg; // 0x10
	private static DelegateBridge __Hotfix0__OnCharCardClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnMultiFormationClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnAssistBtnClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnAssistClearClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnStartBtnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x213a640 VA: 0x7594752640
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x213a7a4 VA: 0x75947527a4
	private Void _InitIfNot() { }
	// RVA: 0x213a890 VA: 0x7594752890
	private Void _RefreshStartBtnBg() { }
	// RVA: 0x213aa14 VA: 0x7594752a14
	private Void _OnCharCardClicked(Options options) { }
	// RVA: 0x213ab54 VA: 0x7594752b54
	public Void EventOnMultiFormationClicked() { }
	// RVA: 0x213ac70 VA: 0x7594752c70
	public Void EventOnAssistBtnClick() { }
	// RVA: 0x213ad24 VA: 0x7594752d24
	public Void EventOnAssistClearClick() { }
	// RVA: 0x213add8 VA: 0x7594752dd8
	public Void EventOnStartBtnClick() { }
	// RVA: 0x213ae98 VA: 0x7594752e98
	public Void .ctor() { }
}
```