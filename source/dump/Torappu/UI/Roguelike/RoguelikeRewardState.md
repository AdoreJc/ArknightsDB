# RoguelikeRewardState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRewardStateBean m_stateBean`

- `RectTransform _panelTopMenu`

- `RoguelikeRewardEntryView _entryView`

- `UIStyleProvider _styleProvider`

- `Boolean m_isResumed`

- `RoguelikeMenuAdapter m_menuAdapter`

- `RoguelikeCommonTopMenu m_topMenu`

- `RoguelikeRewardStyle m_style`

- `Boolean m_inited`


## Methods

- `Void AddStateRelatedEffect(GameObject)`

- `Void _InitIfNot()`

- `Void _SetEffectsActive(Boolean)`

- `Void OnListClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardState : PopupFadeState
{
	private RoguelikeRewardStateBean m_stateBean; // 0x70
	private RectTransform _panelTopMenu; // 0x78
	private RoguelikeRewardEntryView _entryView; // 0x80
	private UIStyleProvider _styleProvider; // 0x88
	private List`1 _effectHolder; // 0x90
	private Boolean m_isResumed; // 0x98
	private RoguelikeMenuAdapter m_menuAdapter; // 0xa0
	private RoguelikeCommonTopMenu m_topMenu; // 0xa8
	private RoguelikeRewardStyle m_style; // 0xb0
	private Boolean m_inited; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0_AddStateRelatedEffect; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SetEffectsActive; // 0x30
	private static DelegateBridge __Hotfix0_OnListClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2a9350c VA: 0x75950ab50c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a93570 VA: 0x75950ab570
	protected override Void OnEnter() { }
	// RVA: 0x2a93a9c VA: 0x75950aba9c
	protected override Void OnResume() { }
	// RVA: 0x2a93bbc VA: 0x75950abbbc
	protected override Void OnPause() { }
	// RVA: 0x2a93c34 VA: 0x75950abc34
	public Void AddStateRelatedEffect(GameObject effectObj) { }
	// RVA: 0x2a936d8 VA: 0x75950ab6d8
	private Void _InitIfNot() { }
	// RVA: 0x2a939a8 VA: 0x75950ab9a8
	private Void _SetEffectsActive(Boolean isActive) { }
	// RVA: 0x2a93eac VA: 0x75950abeac
	public Void OnListClick() { }
	// RVA: 0x2a93fd0 VA: 0x75950abfd0
	public Void .ctor() { }
	// RVA: 0x2a940ec VA: 0x75950ac0ec
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a940f4 VA: 0x75950ac0f4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a940fc VA: 0x75950ac0fc
	private Void <>xLuaBaseProxy_OnPause() { }
}
```