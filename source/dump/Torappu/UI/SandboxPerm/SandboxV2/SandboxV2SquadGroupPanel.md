# SandboxV2SquadGroupPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2SquadButtonView _buttonView`

- `SandboxV2SquadView _squadView`

- `SandboxV2CharRepoView _repoView`

- `SandboxV2SquadGroupProp m_prop`

- `ISandboxV2SquadPanelContext m_actionInterface`

- `Int32 m_cachedSquadIdx`

- `SandboxV2BattleStartNodeInfo m_nodeInfo`


## Methods

- `Void Init(String, ISandboxV2SquadPanelContext)`

- `Void SaveSquadSelectIndex()`

- `Void SaveSquadIfNeeded(Action, Boolean)`

- `Void _SaveSquadSelectIndex()`

- `Void _SaveSquadIfNeeded(Action, Boolean)`

- `Void _EventOnSquadTabClick(Int32)`

- `Void _OnCharSkillSelected(Int32, String)`

- `Void _OnCharDineClick(Int32)`

- `Void _OnRepoSlotClick(Int32)`

- `Void _OnToolBtnBuildClick(Int32)`

- `Void _OnSquadToolClick(Int32)`

- `Void _OnSquadSlotClick(Int32)`

- `Void _OpenToolSelectState(Int32, Input)`

- `Void _OpenCharSelectState(Int32, OpenOption)`

- `Void _OnRepoStatusFilterClick(SandboxV2CharFilter)`

- `Void _OnRepoProfessionFilterClick(ProfessionCategory)`

- `Void EventOnClearProfessionFilter()`

- `Void EventOnToggleProfessionFilter()`

- `Void EventOnToggleStatusFilter()`

- `Void EventOnBtnRepoClick()`

- `Void EventOnBtnEditSquad()`

- `Void EventOnBtnEditTool()`

- `Void EventOnNavToCharList()`

- `Void EventOnNavToToolList()`

- `Void _ScrollToPos(Single)`

- `Void EventonClearSquad()`

- `Void NotifyUpdateDine()`

- `Void NotifyCharSelect(OpenOption, OutPut)`

- `Void NotifyPanelResume(Boolean)`

- `Void NotifyToolSelect(Input, Output)`

- `Void NotifyStartBattle(SandboxV2BattleStartNodeInfo)`

- `Void NotifyMakeDrink()`

- `Void _NavToMakeDrink()`

- `Void _TryStartBattle()`

- `Void _StartBattleImpl()`

- `Options _GeneCommonStartBattleConfirmDialogOptions(String)`

- `Void _ShowJudgeDialog(Options)`

- `Void <EventOnBtnRepoClick>b__28_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadGroupPanel : MonoBehaviour, IHotfixable
{
	private SandboxV2SquadButtonView _buttonView; // 0x18
	private SandboxV2SquadView _squadView; // 0x20
	private SandboxV2CharRepoView _repoView; // 0x28
	private const Single CHAR_LIST_SCROLL_POS; // 0x0
	private const Single TOOL_LIST_SCROLL_POS; // 0x0
	private SandboxV2SquadGroupProp m_prop; // 0x30
	private ISandboxV2SquadPanelContext m_actionInterface; // 0x38
	private Int32 m_cachedSquadIdx; // 0x40
	private SandboxV2BattleStartNodeInfo m_nodeInfo; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_SaveSquadSelectIndex; // 0x8
	private static DelegateBridge __Hotfix0_SaveSquadIfNeeded; // 0x10
	private static DelegateBridge __Hotfix0__SaveSquadSelectIndex; // 0x18
	private static DelegateBridge __Hotfix0__SaveSquadIfNeeded; // 0x20
	private static DelegateBridge __Hotfix0__EventOnSquadTabClick; // 0x28
	private static DelegateBridge __Hotfix0__OnCharSkillSelected; // 0x30
	private static DelegateBridge __Hotfix0__OnCharDineClick; // 0x38
	private static DelegateBridge __Hotfix0__OnRepoSlotClick; // 0x40
	private static DelegateBridge __Hotfix0__OnToolBtnBuildClick; // 0x48
	private static DelegateBridge __Hotfix0__OnSquadToolClick; // 0x50
	private static DelegateBridge __Hotfix0__OnSquadSlotClick; // 0x58
	private static DelegateBridge __Hotfix0__OpenToolSelectState; // 0x60
	private static DelegateBridge __Hotfix0__OpenCharSelectState; // 0x68
	private static DelegateBridge __Hotfix0__OnRepoStatusFilterClick; // 0x70
	private static DelegateBridge __Hotfix0__OnRepoProfessionFilterClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnClearProfessionFilter; // 0x80
	private static DelegateBridge __Hotfix0_EventOnToggleProfessionFilter; // 0x88
	private static DelegateBridge __Hotfix0_EventOnToggleStatusFilter; // 0x90
	private static DelegateBridge __Hotfix0_EventOnBtnRepoClick; // 0x98
	private static DelegateBridge __Hotfix0_EventOnBtnEditSquad; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnBtnEditTool; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnNavToCharList; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnNavToToolList; // 0xb8
	private static DelegateBridge __Hotfix0__ScrollToPos; // 0xc0
	private static DelegateBridge __Hotfix0_EventonClearSquad; // 0xc8
	private static DelegateBridge __Hotfix0_NotifyUpdateDine; // 0xd0
	private static DelegateBridge __Hotfix0_NotifyCharSelect; // 0xd8
	private static DelegateBridge __Hotfix0_NotifyPanelResume; // 0xe0
	private static DelegateBridge __Hotfix0_NotifyToolSelect; // 0xe8
	private static DelegateBridge __Hotfix0_NotifyStartBattle; // 0xf0
	private static DelegateBridge __Hotfix0_NotifyMakeDrink; // 0xf8
	private static DelegateBridge __Hotfix0__NavToMakeDrink; // 0x100
	private static DelegateBridge __Hotfix0__TryStartBattle; // 0x108
	private static DelegateBridge __Hotfix0__StartBattleImpl; // 0x110
	private static DelegateBridge __Hotfix0__GeneCommonStartBattleConfirmDialogOptions; // 0x118
	private static DelegateBridge __Hotfix0__ShowJudgeDialog; // 0x120
	private static DelegateBridge _c__Hotfix0_ctor; // 0x128


	// RVA: 0x2612848 VA: 0x7594c2a848
	public Void Init(String topicId, ISandboxV2SquadPanelContext actionInterface) { }
	// RVA: 0x2613160 VA: 0x7594c2b160
	public Void SaveSquadSelectIndex() { }
	// RVA: 0x2613304 VA: 0x7594c2b304
	public Void SaveSquadIfNeeded(Action nextStep, Boolean mustGoNext) { }
	// RVA: 0x26131c8 VA: 0x7594c2b1c8
	private Void _SaveSquadSelectIndex() { }
	// RVA: 0x2613390 VA: 0x7594c2b390
	private Void _SaveSquadIfNeeded(Action nextStep, Boolean mustGoNext) { }
	// RVA: 0x2613d10 VA: 0x7594c2bd10
	private Void _EventOnSquadTabClick(Int32 squadIdx) { }
	// RVA: 0x2613e2c VA: 0x7594c2be2c
	private Void _OnCharSkillSelected(Int32 instId, String skillId) { }
	// RVA: 0x26141e8 VA: 0x7594c2c1e8
	private Void _OnCharDineClick(Int32 charInstId) { }
	// RVA: 0x2614350 VA: 0x7594c2c350
	private Void _OnRepoSlotClick(Int32 charInstId) { }
	// RVA: 0x2614830 VA: 0x7594c2c830
	private Void _OnToolBtnBuildClick(Int32 toolIdx) { }
	// RVA: 0x2614acc VA: 0x7594c2cacc
	private Void _OnSquadToolClick(Int32 toolIdx) { }
	// RVA: 0x2615018 VA: 0x7594c2d018
	private Void _OnSquadSlotClick(Int32 slotIdx) { }
	// RVA: 0x2614e28 VA: 0x7594c2ce28
	private Void _OpenToolSelectState(Int32 squadIndex, Input input) { }
	// RVA: 0x261462c VA: 0x7594c2c62c
	private Void _OpenCharSelectState(Int32 squadIndex, OpenOption openOption) { }
	// RVA: 0x2615904 VA: 0x7594c2d904
	private Void _OnRepoStatusFilterClick(SandboxV2CharFilter charFilter) { }
	// RVA: 0x2615a6c VA: 0x7594c2da6c
	private Void _OnRepoProfessionFilterClick(ProfessionCategory profession) { }
	// RVA: 0x2615bc4 VA: 0x7594c2dbc4
	public Void EventOnClearProfessionFilter() { }
	// RVA: 0x2615d04 VA: 0x7594c2dd04
	public Void EventOnToggleProfessionFilter() { }
	// RVA: 0x2615e50 VA: 0x7594c2de50
	public Void EventOnToggleStatusFilter() { }
	// RVA: 0x2615f9c VA: 0x7594c2df9c
	public Void EventOnBtnRepoClick() { }
	// RVA: 0x2616058 VA: 0x7594c2e058
	public Void EventOnBtnEditSquad() { }
	// RVA: 0x2616254 VA: 0x7594c2e254
	public Void EventOnBtnEditTool() { }
	// RVA: 0x2616418 VA: 0x7594c2e418
	public Void EventOnNavToCharList() { }
	// RVA: 0x26165d0 VA: 0x7594c2e5d0
	public Void EventOnNavToToolList() { }
	// RVA: 0x2616484 VA: 0x7594c2e484
	private Void _ScrollToPos(Single scrollPos) { }
	// RVA: 0x261663c VA: 0x7594c2e63c
	public Void EventonClearSquad() { }
	// RVA: 0x2616aac VA: 0x7594c2eaac
	public Void NotifyUpdateDine() { }
	// RVA: 0x2616b10 VA: 0x7594c2eb10
	public Void NotifyCharSelect(OpenOption openOption, OutPut outputParam) { }
	// RVA: 0x2616ef0 VA: 0x7594c2eef0
	public Void NotifyPanelResume(Boolean isForceUpdate) { }
	// RVA: 0x26170ec VA: 0x7594c2f0ec
	public Void NotifyToolSelect(Input toolSelectInput, Output toolSelectOutput) { }
	// RVA: 0x2617480 VA: 0x7594c2f480
	public Void NotifyStartBattle(SandboxV2BattleStartNodeInfo nodeInfo) { }
	// RVA: 0x2618034 VA: 0x7594c30034
	public Void NotifyMakeDrink() { }
	// RVA: 0x261809c VA: 0x7594c3009c
	private Void _NavToMakeDrink() { }
	// RVA: 0x2617f70 VA: 0x7594c2ff70
	private Void _TryStartBattle() { }
	// RVA: 0x2618334 VA: 0x7594c30334
	private Void _StartBattleImpl() { }
	// RVA: 0x2617dd8 VA: 0x7594c2fdd8
	private Options _GeneCommonStartBattleConfirmDialogOptions(String topicId) { }
	// RVA: 0x261697c VA: 0x7594c2e97c
	private Void _ShowJudgeDialog(Options options) { }
	// RVA: 0x2618bc8 VA: 0x7594c30bc8
	public Void .ctor() { }
	// RVA: 0x2618c74 VA: 0x7594c30c74
	private Void <EventOnBtnRepoClick>b__28_0() { }
}
```