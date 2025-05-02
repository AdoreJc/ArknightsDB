# UIUnitHUD

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFollower _follower`

- `UITextSlider _hpSlider`

- `UITextSlider _spSlider`

- `UITextSlider _overloadSpTintSlider`

- `UITextSlider _overloadSpSlider`

- `UITextSlider _skillChantSlider`

- `UIFollowEpSlider _epSlider`

- `UITextSlider _spCastSlider`

- `UIBulletBar _bulletBar`

- `UIBulletBar _overloadBulletSlider`

- `RectTransform _manualSkillMark`

- `RectTransform _manualSkillMarkEnhance`

- `RectTransform _manualSkillSuspendable`

- `RectTransform _autoSkillMark`

- `RectTransform _groupSp`

- `Text _skillCntLabel`

- `Text _debugNameLabel`

- `Transform _sliderGroup`

- `Transform _popupTransform`

- `Transform _pluginTransform`

- `Transform _root`

- `Boolean m_isSkillCasting`

- `Boolean m_showSkill`

- `Boolean m_forceShowSkill`

- `Int32 m_lastFrameAvailableCnt`

- `GameObjectSetActiveWrapper m_spCastSliderWrapper`

- `GameObjectSetActiveWrapper m_spSliderWrapper`

- `UInt32 <instanceUid>k__BackingField`

- `Boolean <isAttached>k__BackingField`


## Properties

- `Boolean showSkill`

- `UInt32 instanceUid`

- `Boolean isAttached`

- `GameObjectSetActiveWrapper spCastSliderWrapper`

- `GameObjectSetActiveWrapper spSliderWrapper`

- `Boolean isSkillCasting`


## Methods

- `Boolean get_showSkill()`

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `Boolean get_isAttached()`

- `Void set_isAttached(Boolean)`

- `GameObjectSetActiveWrapper get_spCastSliderWrapper()`

- `GameObjectSetActiveWrapper get_spSliderWrapper()`

- `Boolean get_isSkillCasting()`

- `Void set_isSkillCasting(Boolean)`

- `Void Attach(Unit)`

- `Void OnOwnerSwitchSide()`

- `Void OnAttachPlugin(Transform)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Void _SetHpSliderFillColorBySide()`

- `Void _SetSkillCastingInternal(Boolean, Boolean)`

- `Void _UpdateCharacter(Character)`

- `Void _UpdateManualSkillSuspendable(Character)`

- `Void _UpdateSkillCntLabelIfChanged(Character)`

- `Void _UpdateSkillChantSlider(Character)`

- `Void _UpdateOverloadSlider(Character)`

- `Void _UpdateToken(Token)`

- `Void _UpdateManualSkillMark(Character)`

- `Void _UpdateEnemy(Enemy)`

- `Void _EnableEnemyHpSliderIfNecessary(Enemy)`

- `Void _UpdateEp(Unit)`

- `Void _UpdateHpWithShield(Unit, UIFollowHpSlider)`

- `Void _UpdateBulletBar(Character)`

- `Void _ShowDamageText(Object)`

- `Void _OnAppliedModifier(Object)`

- `Void _ShowDebugLog(Object)`

- `Void _ShowMessage(Object)`

- `Void _OnAppearOrDisappear(Object)`

- `Boolean _CheckIsToken(Unit, out)`

- `Void _OnAppliedEpDamage(Modifier)`

- `Void _OnElementBreak(Object)`

- `Void _ApplyActiveWrapper()`

- `Void Awake()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIUnitHUD : MonoBehaviour, IReusableObject, IReusable, IPtrObject, IHotfixable
{
	private static UInt32 s_globalCounter; // 0x0
	private UIFollower _follower; // 0x18
	private UITextSlider _hpSlider; // 0x20
	private UITextSlider _spSlider; // 0x28
	private UITextSlider _overloadSpTintSlider; // 0x30
	private UITextSlider _overloadSpSlider; // 0x38
	private UITextSlider _skillChantSlider; // 0x40
	private UIFollowEpSlider _epSlider; // 0x48
	private UITextSlider _spCastSlider; // 0x50
	private UIBulletBar _bulletBar; // 0x58
	private UIBulletBar _overloadBulletSlider; // 0x60
	private RectTransform _manualSkillMark; // 0x68
	private RectTransform _manualSkillMarkEnhance; // 0x70
	private RectTransform _manualSkillSuspendable; // 0x78
	private RectTransform _autoSkillMark; // 0x80
	private RectTransform _groupSp; // 0x88
	private Text _skillCntLabel; // 0x90
	private Text _debugNameLabel; // 0x98
	private Transform _sliderGroup; // 0xa0
	private Transform _popupTransform; // 0xa8
	private Transform _pluginTransform; // 0xb0
	private Transform _root; // 0xb8
	private Boolean m_isSkillCasting; // 0xc0
	private Boolean m_showSkill; // 0xc1
	private Boolean m_forceShowSkill; // 0xc2
	private Int32 m_lastFrameAvailableCnt; // 0xc4
	private GameObjectSetActiveWrapper m_spCastSliderWrapper; // 0xc8
	private GameObjectSetActiveWrapper m_spSliderWrapper; // 0xd0
	protected ObjectPtr`1 m_owner; // 0xd8
	private UInt32 <instanceUid>k__BackingField; // 0xe8
	private Boolean <isAttached>k__BackingField; // 0xec
	private static DelegateBridge __Hotfix0_get_showSkill; // 0x8
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x10
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0x18
	private static DelegateBridge __Hotfix0_get_isAttached; // 0x20
	private static DelegateBridge __Hotfix0_set_isAttached; // 0x28
	private static DelegateBridge __Hotfix0_get_spCastSliderWrapper; // 0x30
	private static DelegateBridge __Hotfix0_get_spSliderWrapper; // 0x38
	private static DelegateBridge __Hotfix0_get_isSkillCasting; // 0x40
	private static DelegateBridge __Hotfix0_set_isSkillCasting; // 0x48
	private static DelegateBridge __Hotfix0_Attach; // 0x50
	private static DelegateBridge __Hotfix0_OnOwnerSwitchSide; // 0x58
	private static DelegateBridge __Hotfix0_OnAttachPlugin; // 0x60
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x68
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x70
	private static DelegateBridge __Hotfix0__SetHpSliderFillColorBySide; // 0x78
	private static DelegateBridge __Hotfix0_SetData; // 0x80
	private static DelegateBridge __Hotfix0__SetSkillCastingInternal; // 0x88
	private static DelegateBridge __Hotfix0__UpdateCharacter; // 0x90
	private static DelegateBridge __Hotfix0__UpdateManualSkillSuspendable; // 0x98
	private static DelegateBridge __Hotfix0__UpdateSkillCntLabelIfChanged; // 0xa0
	private static DelegateBridge __Hotfix0__GetOverloadSpProgress; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateSkillChantSlider; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateOverloadSlider; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateToken; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateManualSkillMark; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateEnemy; // 0xd0
	private static DelegateBridge __Hotfix0__EnableEnemyHpSliderIfNecessary; // 0xd8
	private static DelegateBridge __Hotfix0__UpdateEp; // 0xe0
	private static DelegateBridge __Hotfix0__UpdateHpWithShield; // 0xe8
	private static DelegateBridge __Hotfix0__UpdateBulletBar; // 0xf0
	private static DelegateBridge __Hotfix0__ShowDamageText; // 0xf8
	private static DelegateBridge __Hotfix0__OnAppliedModifier; // 0x100
	private static DelegateBridge __Hotfix0__ShowDebugLog; // 0x108
	private static DelegateBridge __Hotfix0__ShowMessage; // 0x110
	private static DelegateBridge __Hotfix0__OnAppearOrDisappear; // 0x118
	private static DelegateBridge __Hotfix0__CheckIsToken; // 0x120
	private static DelegateBridge __Hotfix0__OnAppliedEpDamage; // 0x128
	private static DelegateBridge __Hotfix0__OnElementBreak; // 0x130
	private static DelegateBridge __Hotfix0__ApplyActiveWrapper; // 0x138
	private static DelegateBridge __Hotfix0_Awake; // 0x140
	private static DelegateBridge __Hotfix0_Update; // 0x148
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	private Boolean showSkill { get; }
	public UInt32 instanceUid { get; set; }
	public Boolean isAttached { get; set; }
	private GameObjectSetActiveWrapper spCastSliderWrapper { get; }
	private GameObjectSetActiveWrapper spSliderWrapper { get; }
	protected Boolean isSkillCasting { get; set; }

	// RVA: 0x2084264 VA: 0x759469c264
	private Boolean get_showSkill() { }
	// RVA: 0x20842e4 VA: 0x759469c2e4
	public UInt32 get_instanceUid() { }
	// RVA: 0x208434c VA: 0x759469c34c
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x20843c8 VA: 0x759469c3c8
	public Boolean get_isAttached() { }
	// RVA: 0x2084430 VA: 0x759469c430
	private Void set_isAttached(Boolean value) { }
	// RVA: 0x20844b0 VA: 0x759469c4b0
	private GameObjectSetActiveWrapper get_spCastSliderWrapper() { }
	// RVA: 0x20845bc VA: 0x759469c5bc
	private GameObjectSetActiveWrapper get_spSliderWrapper() { }
	// RVA: 0x20846c8 VA: 0x759469c6c8
	protected Boolean get_isSkillCasting() { }
	// RVA: 0x2084730 VA: 0x759469c730
	private Void set_isSkillCasting(Boolean value) { }
	// RVA: 0x2084918 VA: 0x759469c918
	public Void Attach(Unit owner) { }
	// RVA: 0x2084d88 VA: 0x759469cd88
	public Void OnOwnerSwitchSide() { }
	// RVA: 0x208514c VA: 0x759469d14c
	public Void OnAttachPlugin(Transform plugin) { }
	// RVA: 0x20852d8 VA: 0x759469d2d8
	public Void OnAllocate() { }
	// RVA: 0x208534c VA: 0x759469d34c
	public Void OnRecycle() { }
	// RVA: 0x2084df0 VA: 0x759469cdf0
	private Void _SetHpSliderFillColorBySide() { }
	// RVA: 0x20831f4 VA: 0x759469b1f4
	protected virtual Void SetData(Unit owner) { }
	// RVA: 0x20847b4 VA: 0x759469c7b4
	private Void _SetSkillCastingInternal(Boolean value, Boolean force) { }
	// RVA: 0x20857f8 VA: 0x759469d7f8
	private Void _UpdateCharacter(Character character) { }
	// RVA: 0x2086c28 VA: 0x759469ec28
	private Void _UpdateManualSkillSuspendable(Character character) { }
	// RVA: 0x2086ae4 VA: 0x759469eae4
	private Void _UpdateSkillCntLabelIfChanged(Character character) { }
	// RVA: 0x2085d54 VA: 0x759469dd54
	private static Single _GetOverloadSpProgress(Character character) { }
	// RVA: 0x2086224 VA: 0x759469e224
	private Void _UpdateSkillChantSlider(Character character) { }
	// RVA: 0x20863d4 VA: 0x759469e3d4
	private Void _UpdateOverloadSlider(Character character) { }
	// RVA: 0x2086d88 VA: 0x759469ed88
	private Void _UpdateToken(Token token) { }
	// RVA: 0x2086858 VA: 0x759469e858
	private Void _UpdateManualSkillMark(Character character) { }
	// RVA: 0x208750c VA: 0x759469f50c
	private Void _UpdateEnemy(Enemy enemy) { }
	// RVA: 0x20877d8 VA: 0x759469f7d8
	private Void _EnableEnemyHpSliderIfNecessary(Enemy enemy) { }
	// RVA: 0x2087984 VA: 0x759469f984
	private Void _UpdateEp(Unit owner) { }
	// RVA: 0x2087b7c VA: 0x759469fb7c
	private Void _UpdateHpWithShield(Unit owner, UIFollowHpSlider hpSlider) { }
	// RVA: 0x2085ed4 VA: 0x759469ded4
	private Void _UpdateBulletBar(Character character) { }
	// RVA: 0x2087ce8 VA: 0x759469fce8
	private Void _ShowDamageText(Object arg) { }
	// RVA: 0x2087e7c VA: 0x759469fe7c
	private Void _OnAppliedModifier(Object arg) { }
	// RVA: 0x20884b8 VA: 0x75946a04b8
	private Void _ShowDebugLog(Object arg) { }
	// RVA: 0x20886ac VA: 0x75946a06ac
	private Void _ShowMessage(Object arg) { }
	// RVA: 0x20888ac VA: 0x75946a08ac
	private Void _OnAppearOrDisappear(Object arg) { }
	// RVA: 0x20856c4 VA: 0x759469d6c4
	private Boolean _CheckIsToken(Unit owner, out Boolean alwaysShowHpSlider) { }
	// RVA: 0x208837c VA: 0x75946a037c
	private Void _OnAppliedEpDamage(Modifier modifier) { }
	// RVA: 0x2088980 VA: 0x75946a0980
	private Void _OnElementBreak(Object arg) { }
	// RVA: 0x2088aa4 VA: 0x75946a0aa4
	private Void _ApplyActiveWrapper() { }
	// RVA: 0x2088b30 VA: 0x75946a0b30
	private Void Awake() { }
	// RVA: 0x2083dc0 VA: 0x759469bdc0
	protected virtual Void Update() { }
	// RVA: 0x2088c50 VA: 0x75946a0c50
	private Void OnDestroy() { }
	// RVA: 0x20841ec VA: 0x759469c1ec
	public Void .ctor() { }
}
```