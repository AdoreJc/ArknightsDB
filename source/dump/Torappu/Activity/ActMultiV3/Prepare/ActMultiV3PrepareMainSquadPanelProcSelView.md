# ActMultiV3PrepareMainSquadPanelProcSelView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `PrefabMark _invertTips`

- `TwoStateToggle _btnNext`

- `Text _cnt`

- `Text _minCntTips`

- `SimpleLayoutContent _squad`

- `SimpleLayoutContent _reserveList`

- `UIAnimationLocation _reserveAnim`

- `Int32 m_cachedTempHelpSeq`

- `SquadAdapter m_squadAdapter`

- `ReserveAdapter m_reserveAdapter`

- `AnimationSwitchTween m_reserveSwitch`


## Methods

- `Void _InitIfNot()`

- `Void EventOnNext()`

- `Void _EventAddToSquad(Int32)`

- `Void _EventRemoveFromSquad(Int32)`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanelProcSelView : ActMultiV3PrepareMainSquadPanelProcViewBase
{
	private PrefabMark _invertTips; // 0x40
	private TwoStateToggle _btnNext; // 0x48
	private Text _cnt; // 0x50
	private Text _minCntTips; // 0x58
	private SimpleLayoutContent _squad; // 0x60
	private SimpleLayoutContent _reserveList; // 0x68
	private UIAnimationLocation _reserveAnim; // 0x70
	private Int32 m_cachedTempHelpSeq; // 0x80
	private SquadAdapter m_squadAdapter; // 0x88
	private ReserveAdapter m_reserveAdapter; // 0x90
	private AnimationSwitchTween m_reserveSwitch; // 0x98
	private const String CNT_NORMAL_FMT; // 0x0
	private const String CNT_LOW_FMT; // 0x0
	private const String CNT_FULL_FMT; // 0x0
	private static DelegateBridge __Hotfix0_get_procType; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnNext; // 0x18
	private static DelegateBridge __Hotfix0__EventAddToSquad; // 0x20
	private static DelegateBridge __Hotfix0__EventRemoveFromSquad; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override ActMultiV3PrepareMainSquadProc procType { get; }

	// RVA: 0x3174660 VA: 0x759578c660
	public override ActMultiV3PrepareMainSquadProc get_procType() { }
	// RVA: 0x31746c8 VA: 0x759578c6c8
	protected override Void OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel model) { }
	// RVA: 0x3174b18 VA: 0x759578cb18
	private Void _InitIfNot() { }
	// RVA: 0x3174e1c VA: 0x759578ce1c
	public Void EventOnNext() { }
	// RVA: 0x3174f00 VA: 0x759578cf00
	private Void _EventAddToSquad(Int32 instId) { }
	// RVA: 0x3175018 VA: 0x759578d018
	private Void _EventRemoveFromSquad(Int32 instId) { }
	// RVA: 0x3175130 VA: 0x759578d130
	public Void .ctor() { }
	// RVA: 0x317519c VA: 0x759578d19c
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel P0) { }
}
```