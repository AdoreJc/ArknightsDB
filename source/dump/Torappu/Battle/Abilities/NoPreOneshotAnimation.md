# NoPreOneshotAnimation

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _animWithPre`

- `String _animNoPre`

- `String _endAnim`

- `Single _maxAnimScale`

- `String m_anim`

- `CoroutineId m_coroutine`


## Methods

- `IEnumerator DoPlayAnimation()`

- `Void _ClearCoroutine()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class NoPreOneshotAnimation : Behaviour
{
	private String _animWithPre; // 0x20
	private String _animNoPre; // 0x28
	private String _endAnim; // 0x30
	private Single _maxAnimScale; // 0x38
	private String m_anim; // 0x40
	private CoroutineId m_coroutine; // 0x48
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x10
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0x18
	private static DelegateBridge __Hotfix0_DoPlayAnimation; // 0x20
	private static DelegateBridge __Hotfix0__ClearCoroutine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1eb92f8 VA: 0x75944d12f8
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1eb94a8 VA: 0x75944d14a8
	public override Void OnCastStart() { }
	// RVA: 0x1eb9618 VA: 0x75944d1618
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1eb96a4 VA: 0x75944d16a4
	public override Boolean UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming timing, out Single playbackSpeed) { }
	// RVA: 0x1eb956c VA: 0x75944d156c
	protected IEnumerator DoPlayAnimation() { }
	// RVA: 0x1eb939c VA: 0x75944d139c
	private Void _ClearCoroutine() { }
	// RVA: 0x1eb9844 VA: 0x75944d1844
	public Void .ctor() { }
	// RVA: 0x1eb98bc VA: 0x75944d18bc
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1eb98c4 VA: 0x75944d18c4
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1eb98cc VA: 0x75944d18cc
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1eb98d4 VA: 0x75944d18d4
	private Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming P0, out Single P1) { }
}
```