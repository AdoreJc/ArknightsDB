# ActMultiV3PrepareMainSquadPanelProcCheckView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `PrefabMark _invertTips`

- `GameObject _waitingTips`

- `SimpleLayoutContent _partnerSquad`

- `SimpleLayoutContent _mySquad`

- `TwoStateToggle _btnPrepare`

- `SquadAdapter m_mySquadAdapter`

- `SquadAdapter m_partnerSquadAdapter`


## Methods

- `Void _InitIfNot()`

- `Void EventOnReady()`

- `Void EventOnCancel()`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanelProcCheckView : ActMultiV3PrepareMainSquadPanelProcViewBase
{
	private PrefabMark _invertTips; // 0x40
	private GameObject _waitingTips; // 0x48
	private SimpleLayoutContent _partnerSquad; // 0x50
	private SimpleLayoutContent _mySquad; // 0x58
	private TwoStateToggle _btnPrepare; // 0x60
	private SquadAdapter m_mySquadAdapter; // 0x68
	private SquadAdapter m_partnerSquadAdapter; // 0x70
	private static DelegateBridge __Hotfix0_get_procType; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnReady; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCancel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override ActMultiV3PrepareMainSquadProc procType { get; }

	// RVA: 0x3173db0 VA: 0x759578bdb0
	public override ActMultiV3PrepareMainSquadProc get_procType() { }
	// RVA: 0x3173e18 VA: 0x759578be18
	protected override Void OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel model) { }
	// RVA: 0x3173f50 VA: 0x759578bf50
	private Void _InitIfNot() { }
	// RVA: 0x31740d0 VA: 0x759578c0d0
	public Void EventOnReady() { }
	// RVA: 0x3174220 VA: 0x759578c220
	public Void EventOnCancel() { }
	// RVA: 0x3174308 VA: 0x759578c308
	public Void .ctor() { }
	// RVA: 0x31743e0 VA: 0x759578c3e0
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3PrepareMainSquadPanelViewModel P0) { }
}
```