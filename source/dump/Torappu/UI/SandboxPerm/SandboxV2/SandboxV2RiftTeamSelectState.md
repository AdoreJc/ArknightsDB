# SandboxV2RiftTeamSelectState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RiftTeamSelectView _view`

- `UIAnimationLocation _enterAnim`

- `SandboxV2RiftTeamSelectStateBean m_stateBean`

- `Boolean m_hasInited`

- `String m_cachedTopicId`

- `String m_cachedEnterTeamId`

- `Tween m_enterTween`


## Methods

- `Void _InitIfNot()`

- `Void _ResetEnterAnim()`

- `Void _PlayEnterAnim()`

- `Boolean _EnsureStateStable()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnBackClicked()`

- `Void _OnConfirmClicked()`

- `Void _OnTeamButtonClicked(String)`

- `Void <_OnConfirmClicked>b__19_0(SandboxV2RiftSetTeamResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftTeamSelectState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_BACK_CLICKED; // 0x0
	public const Int32 ON_CONFIRM_CLICKED; // 0x0
	public const Int32 ON_TEAM_BUTTON_CLICKED; // 0x0
	private SandboxV2RiftTeamSelectView _view; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	private SandboxV2RiftTeamSelectStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private String m_cachedTopicId; // 0x98
	private String m_cachedEnterTeamId; // 0xa0
	private Tween m_enterTween; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__ResetEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x28
	private static DelegateBridge __Hotfix0__EnsureStateStable; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnConfirmClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnTeamButtonClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x25fa83c VA: 0x7594c1283c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25fa8a4 VA: 0x7594c128a4
	protected override Void OnEnter() { }
	// RVA: 0x25fb274 VA: 0x7594c13274
	protected override Void OnResume() { }
	// RVA: 0x25faa34 VA: 0x7594c12a34
	private Void _InitIfNot() { }
	// RVA: 0x25fb1b4 VA: 0x7594c131b4
	private Void _ResetEnterAnim() { }
	// RVA: 0x25fb304 VA: 0x7594c13304
	private Void _PlayEnterAnim() { }
	// RVA: 0x25fb420 VA: 0x7594c13420
	private Boolean _EnsureStateStable() { }
	// RVA: 0x25fb510 VA: 0x7594c13510
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x25fb5f4 VA: 0x7594c135f4
	private Void _OnBackClicked() { }
	// RVA: 0x25fb6b8 VA: 0x7594c136b8
	private Void _OnConfirmClicked() { }
	// RVA: 0x25fb914 VA: 0x7594c13914
	private Void _OnTeamButtonClicked(String teamId) { }
	// RVA: 0x25fbba4 VA: 0x7594c13ba4
	public Void .ctor() { }
	// RVA: 0x25fbcfc VA: 0x7594c13cfc
	private Void <_OnConfirmClicked>b__19_0(SandboxV2RiftSetTeamResponse response) { }
	// RVA: 0x25fbd00 VA: 0x7594c13d00
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25fbd08 VA: 0x7594c13d08
	private Void <>xLuaBaseProxy_OnResume() { }
}
```