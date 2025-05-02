# VecBreakSquadGroupController

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `SimpleLayoutContent _squadLayout`

- `Image _startBattleImg`

- `Boolean m_isInited`

- `VecBreakSquadGroupViewModel m_squadGroupModel`

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
// Namespace : Torappu.UI.VecBreak
public class VecBreakSquadGroupController : DataBinder`1
{
	private SimpleLayoutContent _squadLayout; // 0x20
	private Image _startBattleImg; // 0x28
	private Boolean m_isInited; // 0x30
	private VecBreakSquadGroupViewModel m_squadGroupModel; // 0x38
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


	// RVA: 0x22d6d64 VA: 0x75948eed64
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x22d6ec8 VA: 0x75948eeec8
	private Void _InitIfNot() { }
	// RVA: 0x22d6fb8 VA: 0x75948eefb8
	private Void _RefreshStartBtnBg() { }
	// RVA: 0x22d70a8 VA: 0x75948ef0a8
	private Void _OnCharCardClicked(Options options) { }
	// RVA: 0x22d71e8 VA: 0x75948ef1e8
	public Void EventOnMultiFormationClicked() { }
	// RVA: 0x22d7304 VA: 0x75948ef304
	public Void EventOnAssistBtnClick() { }
	// RVA: 0x22d73b8 VA: 0x75948ef3b8
	public Void EventOnAssistClearClick() { }
	// RVA: 0x22d746c VA: 0x75948ef46c
	public Void EventOnStartBtnClick() { }
	// RVA: 0x22d752c VA: 0x75948ef52c
	public Void .ctor() { }
}
```