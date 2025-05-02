# SandboxV2RiftEntryState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RiftEntryView _entryView`

- `UIAnimationLocation _loadingAnim`

- `UIAnimationLocation _enterAnim`

- `GameObject _topMenu`

- `SandboxV2RiftEntryStateBean m_stateBean`

- `Boolean m_hasInited`

- `Boolean m_hasAnimInited`

- `Tween m_enterTween`

- `String m_cachedTopicId`


## Methods

- `Void _ToDifficultySelectStateListener(IStateBean)`

- `Void _InitIfNot()`

- `Void _ResetEnterAnim(Boolean)`

- `Void _PlayEnterAnim(Boolean)`

- `Void _InitAnimIfNot()`

- `Void _OnBackClicked()`

- `Boolean _EnsureStateStable()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnEnterRiftButtonClicked()`

- `Void _OnDifficultyButtonClicked()`

- `Void _OnTeamButtonClicked()`

- `Void <_OnEnterRiftButtonClicked>b__25_0(SandboxV2RiftCreateResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftEntryState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_ENTER_RIFT_BUTTON_CLICKED; // 0x0
	public const Int32 ON_DIFFICULTY_BUTTON_CLICKED; // 0x0
	public const Int32 ON_TEAM_BUTTON_CLICKED; // 0x0
	public const Int32 ON_EXIT_RESERVE_PAGE; // 0x0
	private SandboxV2RiftEntryView _entryView; // 0x70
	private UIAnimationLocation _loadingAnim; // 0x78
	private UIAnimationLocation _enterAnim; // 0x88
	private GameObject _topMenu; // 0x98
	private SandboxV2RiftEntryStateBean m_stateBean; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private Boolean m_hasAnimInited; // 0xa9
	private Tween m_enterTween; // 0xb0
	private String m_cachedTopicId; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__ToDifficultySelectStateListener; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__ResetEnterAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x38
	private static DelegateBridge __Hotfix0__InitAnimIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x48
	private static DelegateBridge __Hotfix0__EnsureStateStable; // 0x50
	private static DelegateBridge __Hotfix0_OnMessage; // 0x58
	private static DelegateBridge __Hotfix0__OnEnterRiftButtonClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnDifficultyButtonClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnTeamButtonClicked; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x25f8440 VA: 0x7594c10440
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25f84a8 VA: 0x7594c104a8
	protected override Void OnEnter() { }
	// RVA: 0x25f8e8c VA: 0x7594c10e8c
	protected override Void OnResume() { }
	// RVA: 0x25f9c14 VA: 0x7594c11c14
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x25f9d8c VA: 0x7594c11d8c
	private Void _ToDifficultySelectStateListener(IStateBean obj) { }
	// RVA: 0x25f861c VA: 0x7594c1061c
	private Void _InitIfNot() { }
	// RVA: 0x25f8d24 VA: 0x7594c10d24
	private Void _ResetEnterAnim(Boolean isFast) { }
	// RVA: 0x25f98f8 VA: 0x7594c118f8
	private Void _PlayEnterAnim(Boolean isFast) { }
	// RVA: 0x25f9ea8 VA: 0x7594c11ea8
	private Void _InitAnimIfNot() { }
	// RVA: 0x25f9f50 VA: 0x7594c11f50
	private Void _OnBackClicked() { }
	// RVA: 0x25fa024 VA: 0x7594c12024
	private Boolean _EnsureStateStable() { }
	// RVA: 0x25fa13c VA: 0x7594c1213c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x25fa244 VA: 0x7594c12244
	private Void _OnEnterRiftButtonClicked() { }
	// RVA: 0x25fa430 VA: 0x7594c12430
	private Void _OnDifficultyButtonClicked() { }
	// RVA: 0x25fa548 VA: 0x7594c12548
	private Void _OnTeamButtonClicked() { }
	// RVA: 0x25fa668 VA: 0x7594c12668
	public Void .ctor() { }
	// RVA: 0x25fa7c0 VA: 0x7594c127c0
	private Void <_OnEnterRiftButtonClicked>b__25_0(SandboxV2RiftCreateResponse response) { }
	// RVA: 0x25fa7c4 VA: 0x7594c127c4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25fa7cc VA: 0x7594c127cc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x25fa7d4 VA: 0x7594c127d4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```