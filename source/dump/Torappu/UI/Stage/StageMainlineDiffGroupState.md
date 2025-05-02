# StageMainlineDiffGroupState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageMainlineDiffGroupStateBean m_stateBean`

- `DynamicPrefabInstHolder _viewInstHolder`

- `Button _backBtn`

- `Boolean m_isInited`

- `GameObject _globalEventMask`


## Methods

- `Void OnDiffClick(StageDiffGroup)`

- `Void _InitIfNot()`

- `Void <OnEnter>b__7_0(GameObject)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainlineDiffGroupState : PopupFloatState
{
	private StageMainlineDiffGroupStateBean m_stateBean; // 0x70
	private DynamicPrefabInstHolder _viewInstHolder; // 0x78
	private Button _backBtn; // 0x80
	private Boolean m_isInited; // 0x88
	protected GameObject _globalEventMask; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnDiffClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f6496c VA: 0x759557c96c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f649d4 VA: 0x759557c9d4
	public Void OnDiffClick(StageDiffGroup diffGroup) { }
	// RVA: 0x2f64a6c VA: 0x759557ca6c
	private Void _InitIfNot() { }
	// RVA: 0x2f64b6c VA: 0x759557cb6c
	protected override Void OnEnter() { }
	// RVA: 0x2f64c44 VA: 0x759557cc44
	protected override Void OnPause() { }
	// RVA: 0x2f64d10 VA: 0x759557cd10
	protected override Void OnResume() { }
	// RVA: 0x2f64dd8 VA: 0x759557cdd8
	public Void .ctor() { }
	// RVA: 0x2f64e84 VA: 0x759557ce84
	private Void <OnEnter>b__7_0(GameObject obj) { }
	// RVA: 0x2f64f54 VA: 0x759557cf54
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f64f5c VA: 0x759557cf5c
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2f64f64 VA: 0x759557cf64
	private Void <>xLuaBaseProxy_OnResume() { }
}
```