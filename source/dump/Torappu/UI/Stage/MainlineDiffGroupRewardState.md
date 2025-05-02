# MainlineDiffGroupRewardState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `MainlineDiffGroupRewardView _rewardView`

- `RectTransform _backPress`

- `String m_cacheStageId`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnGoToSquad()`

- `Void OnRewardClick(String)`

- `Void <_InitIfNot>b__6_0()`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MainlineDiffGroupRewardState : State
{
	private MainlineDiffGroupRewardView _rewardView; // 0x50
	private RectTransform _backPress; // 0x58
	private String m_cacheStageId; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnGoToSquad; // 0x18
	private static DelegateBridge __Hotfix0_OnRewardClick; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ef3bfc VA: 0x759550bbfc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ef3c60 VA: 0x759550bc60
	protected override Void OnEnter() { }
	// RVA: 0x2ef3d20 VA: 0x759550bd20
	private Void _InitIfNot() { }
	// RVA: 0x2ef41fc VA: 0x759550c1fc
	public Void OnGoToSquad() { }
	// RVA: 0x2ef43c4 VA: 0x759550c3c4
	public Void OnRewardClick(String stageId) { }
	// RVA: 0x2ef44f4 VA: 0x759550c4f4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ef466c VA: 0x759550c66c
	public Void .ctor() { }
	// RVA: 0x2ef46dc VA: 0x759550c6dc
	private Void <_InitIfNot>b__6_0() { }
	// RVA: 0x2ef47b4 VA: 0x759550c7b4
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x2ef483c VA: 0x759550c83c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ef4844 VA: 0x759550c844
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```