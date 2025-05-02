# HarpoonProjectile

**Namespace:** `Torappu.Battle`


## Fields

- `Single WAIT_CHECK_HIGNLAND`

- `Int32 _pullForceLevel`

- `Single _pullSourceOffset`

- `Boolean _stopAfterPulledBack`

- `Boolean _ignoreTargetMess`

- `Boolean _stopWhenCollideWithHighLand`

- `Int32 m_pullForceLevel`

- `Vector2 m_pullBackDestination`

- `Boolean m_isPullStopped`

- `FP m_targetTime`


## Properties

- `Int32 pullForceLevel`


## Methods

- `Int32 get_pullForceLevel()`

- `Void _StopCollideHighLand(Object)`

- `Void SetPullForceLevel(Int32)`

- `IEnumerator <>n__0(Entity)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `IEnumerator <>xLuaBaseProxy_DoLink(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class HarpoonProjectile : LinkProjectile
{
	public Single WAIT_CHECK_HIGNLAND; // 0x1c8
	private Int32 _pullForceLevel; // 0x1cc
	private Single _pullSourceOffset; // 0x1d0
	private Boolean _stopAfterPulledBack; // 0x1d4
	private Boolean _ignoreTargetMess; // 0x1d5
	private Boolean _stopWhenCollideWithHighLand; // 0x1d6
	private Int32 m_pullForceLevel; // 0x1d8
	private Vector2 m_pullBackDestination; // 0x1dc
	private Boolean m_isPullStopped; // 0x1e4
	private FP m_targetTime; // 0x1e8
	private static DelegateBridge __Hotfix0_get_pullForceLevel; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0__StopCollideHighLand; // 0x20
	private static DelegateBridge __Hotfix0_SetPullForceLevel; // 0x28
	private static DelegateBridge __Hotfix0_DoLink; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 pullForceLevel { get; }

	// RVA: 0x40a4904 VA: 0x75966bc904
	public Int32 get_pullForceLevel() { }
	// RVA: 0x40a496c VA: 0x75966bc96c
	protected override Void OnReset() { }
	// RVA: 0x40a4abc VA: 0x75966bcabc
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x40a4ddc VA: 0x75966bcddc
	protected override Void OnProjectileStop() { }
	// RVA: 0x40a5374 VA: 0x75966bd374
	private Void _StopCollideHighLand(Object obj) { }
	// RVA: 0x40a5550 VA: 0x75966bd550
	public Void SetPullForceLevel(Int32 level) { }
	// RVA: 0x40a55cc VA: 0x75966bd5cc
	protected override IEnumerator DoLink(Entity rawTarget) { }
	// RVA: 0x40a56c4 VA: 0x75966bd6c4
	public Void .ctor() { }
	// RVA: 0x40a57c4 VA: 0x75966bd7c4
	private IEnumerator <>n__0(Entity target) { }
	// RVA: 0x40a5898 VA: 0x75966bd898
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x40a589c VA: 0x75966bd89c
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x40a58a0 VA: 0x75966bd8a0
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x40a58a4 VA: 0x75966bd8a4
	private IEnumerator <>xLuaBaseProxy_DoLink(Entity P0) { }
}
```