# ThreePartOneshotAnimation

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _beginAnim`

- `String _oneshotAnim`

- `String _endAnim`

- `Boolean _fixAnimWhenCooldownSlow`

- `Boolean _overrideDownAnimation`

- `AnimationBundle _down`

- `Boolean _faceToTarget`

- `Single _minAnimScale`

- `Single _maxAnimScale`

- `Boolean _onlyPlayBeginAnimWhenFirstAttack`

- `Single m_animSpeed`

- `Boolean m_hasBeginAnim`

- `Boolean m_hasEndAnim`

- `CoroutineId m_coroutine`

- `AnimationBundle m_default`


## Methods

- `IEnumerator DoPlayAnimation(AnimationBundle)`

- `Single InitAnimation()`

- `AnimationBundle _GetAnimBundle()`

- `Boolean _CheckDownAttack()`

- `Void _ClearCoroutine()`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ThreePartOneshotAnimation : Behaviour
{
	private String _beginAnim; // 0x20
	private String _oneshotAnim; // 0x28
	private String _endAnim; // 0x30
	private Boolean _fixAnimWhenCooldownSlow; // 0x38
	private Boolean _overrideDownAnimation; // 0x39
	private AnimationBundle _down; // 0x40
	private Boolean _faceToTarget; // 0x58
	private Single _minAnimScale; // 0x5c
	private Single _maxAnimScale; // 0x60
	private Boolean _onlyPlayBeginAnimWhenFirstAttack; // 0x64
	private Single m_animSpeed; // 0x68
	private Boolean m_hasBeginAnim; // 0x6c
	private Boolean m_hasEndAnim; // 0x6d
	private CoroutineId m_coroutine; // 0x70
	private AnimationBundle m_default; // 0x80
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x18
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0x20
	private static DelegateBridge __Hotfix0_DoPlayAnimation; // 0x28
	private static DelegateBridge __Hotfix0_InitAnimation; // 0x30
	private static DelegateBridge __Hotfix0__GetAnimBundle; // 0x38
	private static DelegateBridge __Hotfix0__CheckDownAttack; // 0x40
	private static DelegateBridge __Hotfix0__ClearCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1ebb3b0 VA: 0x75944d33b0
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ebb498 VA: 0x75944d3498
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebb648 VA: 0x75944d3648
	public override Void OnCastStart() { }
	// RVA: 0x1ebb9c4 VA: 0x75944d39c4
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ebba50 VA: 0x75944d3a50
	public override Boolean UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming timing, out Single playbackSpeed) { }
	// RVA: 0x1ebb8d0 VA: 0x75944d38d0
	protected IEnumerator DoPlayAnimation(AnimationBundle bundle) { }
	// RVA: 0x1ebbb48 VA: 0x75944d3b48
	protected Single InitAnimation() { }
	// RVA: 0x1ebb820 VA: 0x75944d3820
	private AnimationBundle _GetAnimBundle() { }
	// RVA: 0x1ebbd60 VA: 0x75944d3d60
	private Boolean _CheckDownAttack() { }
	// RVA: 0x1ebb53c VA: 0x75944d353c
	private Void _ClearCoroutine() { }
	// RVA: 0x1ebbe28 VA: 0x75944d3e28
	public Void .ctor() { }
	// RVA: 0x1ebbea0 VA: 0x75944d3ea0
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ebbea8 VA: 0x75944d3ea8
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ebbeb0 VA: 0x75944d3eb0
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ebbeb8 VA: 0x75944d3eb8
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ebbec0 VA: 0x75944d3ec0
	private Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming P0, out Single P1) { }
}
```