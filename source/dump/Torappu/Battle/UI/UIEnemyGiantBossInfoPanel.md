# UIEnemyGiantBossInfoPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `RectTransform _scaleBody`

- `UIFollower _follower`

- `UITextSlider _hpSlider`

- `UITextSlider _exHpSlider`

- `UIFollowEpSlider _epSlider`

- `Image _hitEffectImage`

- `GameObject _background`

- `GameObject _avatarParent`

- `Image _avatarImage`

- `Image _smallAvatarImage`

- `Single m_scaleXTweenDuration`

- `Single m_postScaleXTweenDuration`

- `Boolean m_postScaleXTweenStarted`

- `Single m_alphaTweenDuration`

- `Single m_postAlphaTweenDuration`

- `Boolean m_postAlphaTweenStarted`

- `Single m_spSliderAlphaTweenDuration`

- `Boolean m_showedSpSlider`

- `Tween m_hitEffectTween`

- `Single m_hitEffectTweenDuration`

- `Boolean m_isSkillCasting`

- `CoroutineId m_coroutine`

- `RectTransform m_rectTransform`

- `Vector2 m_originalPosition`

- `Vector2 m_originalAvatarPosition`

- `Boolean m_hideHpSlider`

- `Color m_defaultHitImageColor`

- `GiantBossInfoType m_giantBossInfoType`

- `UITextSlider m_spSlider`

- `UITextSlider m_spBackSlider`

- `UITextSlider m_spCastSlider`

- `UIGiantEnemySpWarning m_enemySpWarning`

- `Boolean <isAttached>k__BackingField`


## Properties

- `Boolean isAttached`

- `Boolean isSkillCasting`


## Methods

- `Boolean get_isAttached()`

- `Void set_isAttached(Boolean)`

- `Boolean get_isSkillCasting()`

- `Void set_isSkillCasting(Boolean)`

- `Void _LoadExtraInfoComponents()`

- `Void _SetSkillCastingInternal(Boolean)`

- `Void _SetLockedPosition(Boolean)`

- `Void Attach(IUseGiantBossInfoPanel)`

- `IEnumerator _DoAttach(IUseGiantBossInfoPanel)`

- `Void Detach(IUseGiantBossInfoPanel)`

- `Void _InitHitTween()`

- `Void OnDestroy()`

- `Void _StartExtraTween()`

- `Void _StartTweenAnim()`

- `Void _StartPostTweenScaleX()`

- `Void _StartPostTweenImageAlpha()`

- `Void _StartSpSliderTweenAnim()`

- `Void _StartHpSliderTweenAnim()`

- `Void Awake()`

- `Void Update()`

- `Void _UpdateInternal(IUseGiantBossInfoPanel)`

- `Void _OnElementBreak(Object)`

- `Void _UpdateEp(IUseGiantBossInfoPanel)`

- `Void _OnTakeDamage(Unit)`

- `Void <_InitHitTween>b__53_1(Single)`

- `Void <_StartExtraTween>b__55_1(Single)`

- `Void <_StartTweenAnim>b__56_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIEnemyGiantBossInfoPanel : MonoBehaviour, IHotfixable
{
	private RectTransform _scaleBody; // 0x18
	private UIFollower _follower; // 0x20
	private UITextSlider _hpSlider; // 0x28
	private UITextSlider _exHpSlider; // 0x30
	private UIFollowEpSlider _epSlider; // 0x38
	private Image _hitEffectImage; // 0x40
	private GameObject _background; // 0x48
	private GameObject _avatarParent; // 0x50
	private Image _avatarImage; // 0x58
	private Image _smallAvatarImage; // 0x60
	private List`1 _extraInfoType; // 0x68
	private List`1 _scaleXTweenTrans; // 0x70
	private List`1 _postScaleXTweenTrans; // 0x78
	private List`1 _alphaTweenImages; // 0x80
	private List`1 _postAlphaTweenImages; // 0x88
	private Single m_scaleXTweenDuration; // 0x90
	private Single m_postScaleXTweenDuration; // 0x94
	private Boolean m_postScaleXTweenStarted; // 0x98
	private Single m_alphaTweenDuration; // 0x9c
	private Single m_postAlphaTweenDuration; // 0xa0
	private Boolean m_postAlphaTweenStarted; // 0xa4
	private Single m_spSliderAlphaTweenDuration; // 0xa8
	private Boolean m_showedSpSlider; // 0xac
	private Tween m_hitEffectTween; // 0xb0
	private Single m_hitEffectTweenDuration; // 0xb8
	private ObjectPtr`1 m_owner; // 0xc0
	private ObjectPtr`1 m_ownerEntityPtr; // 0xd0
	private Boolean m_isSkillCasting; // 0xe0
	private CoroutineId m_coroutine; // 0xe8
	private RectTransform m_rectTransform; // 0xf8
	private Vector2 m_originalPosition; // 0x100
	private Vector2 m_originalAvatarPosition; // 0x108
	private Boolean m_hideHpSlider; // 0x110
	private Color m_defaultHitImageColor; // 0x114
	private GiantBossInfoType m_giantBossInfoType; // 0x124
	private UITextSlider m_spSlider; // 0x128
	private UITextSlider m_spBackSlider; // 0x130
	private UITextSlider m_spCastSlider; // 0x138
	private UIGiantEnemySpWarning m_enemySpWarning; // 0x140
	private Boolean <isAttached>k__BackingField; // 0x148
	private static DelegateBridge __Hotfix0_get_isAttached; // 0x0
	private static DelegateBridge __Hotfix0_set_isAttached; // 0x8
	private static DelegateBridge __Hotfix0_get_isSkillCasting; // 0x10
	private static DelegateBridge __Hotfix0_set_isSkillCasting; // 0x18
	private static DelegateBridge __Hotfix0__LoadExtraInfoComponents; // 0x20
	private static DelegateBridge __Hotfix0__SetSkillCastingInternal; // 0x28
	private static DelegateBridge __Hotfix0__SetLockedPosition; // 0x30
	private static DelegateBridge __Hotfix0_Attach; // 0x38
	private static DelegateBridge __Hotfix0__DoAttach; // 0x40
	private static DelegateBridge __Hotfix0_Detach; // 0x48
	private static DelegateBridge __Hotfix0__InitHitTween; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge __Hotfix0__StartExtraTween; // 0x60
	private static DelegateBridge __Hotfix0__StartTweenAnim; // 0x68
	private static DelegateBridge __Hotfix0__StartPostTweenScaleX; // 0x70
	private static DelegateBridge __Hotfix0__StartPostTweenImageAlpha; // 0x78
	private static DelegateBridge __Hotfix0__StartSpSliderTweenAnim; // 0x80
	private static DelegateBridge __Hotfix0__StartHpSliderTweenAnim; // 0x88
	private static DelegateBridge __Hotfix0_Awake; // 0x90
	private static DelegateBridge __Hotfix0_Update; // 0x98
	private static DelegateBridge __Hotfix0__UpdateInternal; // 0xa0
	private static DelegateBridge __Hotfix0__OnElementBreak; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateEp; // 0xb0
	private static DelegateBridge __Hotfix0__OnTakeDamage; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Boolean isAttached { get; set; }
	protected Boolean isSkillCasting { get; set; }

	// RVA: 0x204b690 VA: 0x7594663690
	public Boolean get_isAttached() { }
	// RVA: 0x204b6f8 VA: 0x75946636f8
	private Void set_isAttached(Boolean value) { }
	// RVA: 0x204b778 VA: 0x7594663778
	protected Boolean get_isSkillCasting() { }
	// RVA: 0x204b7e0 VA: 0x75946637e0
	private Void set_isSkillCasting(Boolean value) { }
	// RVA: 0x204b958 VA: 0x7594663958
	private Void _LoadExtraInfoComponents() { }
	// RVA: 0x204b860 VA: 0x7594663860
	private Void _SetSkillCastingInternal(Boolean value) { }
	// RVA: 0x204c2ac VA: 0x75946642ac
	private Void _SetLockedPosition(Boolean isLock) { }
	// RVA: 0x204c358 VA: 0x7594664358
	public Void Attach(IUseGiantBossInfoPanel owner) { }
	// RVA: 0x204c550 VA: 0x7594664550
	private IEnumerator _DoAttach(IUseGiantBossInfoPanel owner) { }
	// RVA: 0x204c648 VA: 0x7594664648
	public Void Detach(IUseGiantBossInfoPanel owner) { }
	// RVA: 0x204ca60 VA: 0x7594664a60
	private Void _InitHitTween() { }
	// RVA: 0x204cd24 VA: 0x7594664d24
	private Void OnDestroy() { }
	// RVA: 0x204cda4 VA: 0x7594664da4
	private Void _StartExtraTween() { }
	// RVA: 0x204cf94 VA: 0x7594664f94
	private Void _StartTweenAnim() { }
	// RVA: 0x204d838 VA: 0x7594665838
	private Void _StartPostTweenScaleX() { }
	// RVA: 0x204ddb8 VA: 0x7594665db8
	private Void _StartPostTweenImageAlpha() { }
	// RVA: 0x204bec0 VA: 0x7594663ec0
	private Void _StartSpSliderTweenAnim() { }
	// RVA: 0x204da40 VA: 0x7594665a40
	private Void _StartHpSliderTweenAnim() { }
	// RVA: 0x204e2f0 VA: 0x75946662f0
	private Void Awake() { }
	// RVA: 0x204e424 VA: 0x7594666424
	private Void Update() { }
	// RVA: 0x204e4f0 VA: 0x75946664f0
	private Void _UpdateInternal(IUseGiantBossInfoPanel entity) { }
	// RVA: 0x204f0a8 VA: 0x75946670a8
	private Void _OnElementBreak(Object arg) { }
	// RVA: 0x204ecb4 VA: 0x7594666cb4
	private Void _UpdateEp(IUseGiantBossInfoPanel owner) { }
	// RVA: 0x204f1b4 VA: 0x75946671b4
	private Void _OnTakeDamage(Unit owner) { }
	// RVA: 0x204f23c VA: 0x759466723c
	public Void .ctor() { }
	// RVA: 0x204f420 VA: 0x7594667420
	private Void <_InitHitTween>b__53_1(Single val) { }
	// RVA: 0x204f4c0 VA: 0x75946674c0
	private Void <_StartExtraTween>b__55_1(Single val) { }
	// RVA: 0x204f54c VA: 0x759466754c
	private Void <_StartTweenAnim>b__56_0() { }
}
```