# ActMultiV3PrepareMainSquadPanelProcSkillView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `UIAnimationLocation _tabSwitchAnim`

- `PrefabMark _invertTips`

- `SimpleLayoutContent _charCardContent`

- `ScrollRect _cardScrollRect`

- `Boolean m_hasInited`

- `UISwitchTween m_tabSwitchTween`

- `Boolean m_cachedShowSkill`

- `Int32 m_cachedSeqNum`

- `CharCardAdapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void EventOnNext()`

- `Void EventOnSwitchShowSkill()`

- `Void _EventOnSetSelectedSkill(Int32, String)`

- `Void _EventOnSetSelectedModule(Int32, String)`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanelProcSkillView : ActMultiV3PrepareMainSquadPanelProcViewBase
{
	private UIAnimationLocation _tabSwitchAnim; // 0x40
	private PrefabMark _invertTips; // 0x50
	private SimpleLayoutContent _charCardContent; // 0x58
	private ScrollRect _cardScrollRect; // 0x60
	private List`1 m_cachedCardModels; // 0x68
	private Boolean m_hasInited; // 0x70
	private UISwitchTween m_tabSwitchTween; // 0x78
	private Boolean m_cachedShowSkill; // 0x80
	private Int32 m_cachedSeqNum; // 0x84
	private CharCardAdapter m_adapter; // 0x88
	private static DelegateBridge __Hotfix0_get_procType; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnNext; // 0x18
	private static DelegateBridge __Hotfix0_EventOnSwitchShowSkill; // 0x20
	private static DelegateBridge __Hotfix0__EventOnSetSelectedSkill; // 0x28
	private static DelegateBridge __Hotfix0__EventOnSetSelectedModule; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override ActMultiV3PrepareMainSquadProc procType { get; }

	// RVA: 0x317576c VA: 0x759578d76c
	public override ActMultiV3PrepareMainSquadProc get_procType() { }
	// RVA: 0x31757d4 VA: 0x759578d7d4
	protected override Void OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel model) { }
	// RVA: 0x3175988 VA: 0x759578d988
	private Void _InitIfNot() { }
	// RVA: 0x3175b60 VA: 0x759578db60
	public Void EventOnNext() { }
	// RVA: 0x3175c44 VA: 0x759578dc44
	public Void EventOnSwitchShowSkill() { }
	// RVA: 0x3175d28 VA: 0x759578dd28
	private Void _EventOnSetSelectedSkill(Int32 instId, String skillId) { }
	// RVA: 0x3175e30 VA: 0x759578de30
	private Void _EventOnSetSelectedModule(Int32 instId, String moduleId) { }
	// RVA: 0x3175f38 VA: 0x759578df38
	public Void .ctor() { }
	// RVA: 0x3175fa4 VA: 0x759578dfa4
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel P0) { }
}
```