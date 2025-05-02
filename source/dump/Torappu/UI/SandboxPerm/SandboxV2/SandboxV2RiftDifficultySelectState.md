# SandboxV2RiftDifficultySelectState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RiftDifficultySelectView _view`

- `UIAnimationLocation _enterAnim`

- `SandboxV2RiftDifficultySelectStateBean m_stateBean`

- `Boolean m_hasInited`

- `Tween m_enterAnimTween`

- `String m_cachedEnterDifficultyId`


## Methods

- `Void _InitIfNot()`

- `Void _ResetEnterAnim()`

- `Void _PlayEnterAnim()`

- `Boolean _EnsureStateStable()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnCloseState()`

- `Void _OnConfirmDifficultyLevel(String)`

- `Void _OnDifficultyChange(Int32)`

- `Void <_OnConfirmDifficultyLevel>b__18_0(SandboxV2RiftSetDifficultyResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftDifficultySelectState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_CLOSE_STATE; // 0x0
	public const Int32 ON_CONFIRM_DIFFICULTY_LEVEL; // 0x0
	public const Int32 ON_DIFFICULTY_CHANGE; // 0x0
	private SandboxV2RiftDifficultySelectView _view; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	private SandboxV2RiftDifficultySelectStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private Tween m_enterAnimTween; // 0x98
	private String m_cachedEnterDifficultyId; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__ResetEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x28
	private static DelegateBridge __Hotfix0__EnsureStateStable; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnCloseState; // 0x40
	private static DelegateBridge __Hotfix0__OnConfirmDifficultyLevel; // 0x48
	private static DelegateBridge __Hotfix0__OnDifficultyChange; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x25f70dc VA: 0x7594c0f0dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25f7144 VA: 0x7594c0f144
	protected override Void OnEnter() { }
	// RVA: 0x25f7aa8 VA: 0x7594c0faa8
	protected override Void OnResume() { }
	// RVA: 0x25f72cc VA: 0x7594c0f2cc
	private Void _InitIfNot() { }
	// RVA: 0x25f79e8 VA: 0x7594c0f9e8
	private Void _ResetEnterAnim() { }
	// RVA: 0x25f7b38 VA: 0x7594c0fb38
	private Void _PlayEnterAnim() { }
	// RVA: 0x25f7c54 VA: 0x7594c0fc54
	private Boolean _EnsureStateStable() { }
	// RVA: 0x25f7d44 VA: 0x7594c0fd44
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x25f7e2c VA: 0x7594c0fe2c
	private Void _OnCloseState() { }
	// RVA: 0x25f7ef0 VA: 0x7594c0fef0
	private Void _OnConfirmDifficultyLevel(String difficultyId) { }
	// RVA: 0x25f8148 VA: 0x7594c10148
	private Void _OnDifficultyChange(Int32 endLevel) { }
	// RVA: 0x25f82d4 VA: 0x7594c102d4
	public Void .ctor() { }
	// RVA: 0x25f842c VA: 0x7594c1042c
	private Void <_OnConfirmDifficultyLevel>b__18_0(SandboxV2RiftSetDifficultyResponse response) { }
	// RVA: 0x25f8430 VA: 0x7594c10430
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25f8438 VA: 0x7594c10438
	private Void <>xLuaBaseProxy_OnResume() { }
}
```