# FifthAnnivMissionArchiveExteriorPlayer

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Camera _camera`

- `RenderTexture _renderTexture`

- `UIAnimationLocation _normalPlayAnimation`

- `UIAnimationLocation _normalStopAnimation`

- `AnimationWrapper m_playWrapper`

- `Boolean m_isActivated`


## Methods

- `Void _ActivateCameraIfNecessary()`

- `Void <>xLuaBaseProxy_Init(MissionArchiveController)`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivMissionArchiveExteriorPlayer : MissionArchiveExteriorPlayer
{
	private Camera _camera; // 0x18
	private RenderTexture _renderTexture; // 0x20
	private UIAnimationLocation _normalPlayAnimation; // 0x28
	private UIAnimationLocation _normalStopAnimation; // 0x38
	private AnimationWrapper m_playWrapper; // 0x48
	private Boolean m_isActivated; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_Play; // 0x10
	private static DelegateBridge __Hotfix0_Stop; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__ActivateCameraIfNecessary; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x292d5ec VA: 0x7594f455ec
	public override Void Init(MissionArchiveController controller) { }
	// RVA: 0x292d744 VA: 0x7594f45744
	public override Void Reset() { }
	// RVA: 0x292d7d4 VA: 0x7594f457d4
	public override Void Play(Boolean isHidden) { }
	// RVA: 0x292d874 VA: 0x7594f45874
	public override Void Stop() { }
	// RVA: 0x292d904 VA: 0x7594f45904
	protected override Void OnEnable() { }
	// RVA: 0x292d9d8 VA: 0x7594f459d8
	protected override Void OnDestroy() { }
	// RVA: 0x292d6a8 VA: 0x7594f456a8
	private Void _ActivateCameraIfNecessary() { }
	// RVA: 0x292daac VA: 0x7594f45aac
	public Void .ctor() { }
	// RVA: 0x292db1c VA: 0x7594f45b1c
	private Void <>xLuaBaseProxy_Init(MissionArchiveController P0) { }
	// RVA: 0x292db24 VA: 0x7594f45b24
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x292db2c VA: 0x7594f45b2c
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```