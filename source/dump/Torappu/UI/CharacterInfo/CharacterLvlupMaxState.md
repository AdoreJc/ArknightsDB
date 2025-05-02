# CharacterLvlupMaxState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterLvlupMaxView _maxView`

- `CharacterLvlupMaxStateBean _stateBean`

- `AnimationWrapper _animationWrapper`

- `UICommonPageEffectHolder _effectHolder`

- `Boolean m_animPlaying`

- `Boolean m_hasInited`


## Methods

- `Void EventOnStateClick()`

- `Void _PlayEnterAnim()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupMaxState : UIPopupState
{
	private const String ANIM_MAX_STATE; // 0x0
	private const Single DURATION_ANIM_CAN_SKIP; // 0x0
	private CharacterLvlupMaxView _maxView; // 0x60
	private CharacterLvlupMaxStateBean _stateBean; // 0x68
	private AnimationWrapper _animationWrapper; // 0x70
	private UICommonPageEffectHolder _effectHolder; // 0x78
	private Boolean m_animPlaying; // 0x80
	private Boolean m_hasInited; // 0x81
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnStateClick; // 0x10
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x30
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2d4eb78 VA: 0x7595366b78
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4ebe0 VA: 0x7595366be0
	protected override Void OnEnter() { }
	// RVA: 0x2d4ed48 VA: 0x7595366d48
	public Void EventOnStateClick() { }
	// RVA: 0x2d4ee60 VA: 0x7595366e60
	private Void _PlayEnterAnim() { }
	// RVA: 0x2d4efc0 VA: 0x7595366fc0
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2d4f138 VA: 0x7595367138
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2d4f2b0 VA: 0x75953672b0
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2d4f3e8 VA: 0x75953673e8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2d4ec68 VA: 0x7595366c68
	private Void _InitIfNot() { }
	// RVA: 0x2d4f4f4 VA: 0x75953674f4
	public Void .ctor() { }
	// RVA: 0x2d4f564 VA: 0x7595367564
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```