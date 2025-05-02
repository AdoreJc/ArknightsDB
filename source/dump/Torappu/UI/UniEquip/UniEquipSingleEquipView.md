# UniEquipSingleEquipView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Text _uniEquipName`

- `UniEquipImgHolder _imgHolder`

- `Transform _imgContainer`

- `Single _scaler`

- `GameObject _havePart`

- `GameObject _dontHavePart`

- `AnimationWrapper _animWrapper`

- `GameObject _changeBtn`

- `Text _commonCharEquipText`

- `Text _equipChangeAttributeText`

- `Text _equipChangeSubProfessionDescText`

- `Text _equipChangeTalentDescText`

- `Text _equipSpecialDescText`

- `Image _levelPart`

- `GameObject _focusPart`

- `GameObject _focusPart2`

- `GameObject _unlockObj`

- `GameObject _unlockAvailablePart`

- `SimpleLayoutContent _content`

- `Transform _typeContainer`

- `CanvasGroup _typeCanvasGroup`

- `Single _typeValidAlpha`

- `Single _typeInvalidAlpha`

- `UICommonEquipTypeIcon _typeIcon`

- `GameObject _levelUpPart`

- `GameObject _levelMaxPart`

- `GameObject _selectedDetailBtn`

- `GameObject _hotSpotPart`

- `GameObject _selectHotspotPart`

- `GameObject _unlockHotspotPart`

- `GameObject _levelUpEnoughPart`

- `GameObject _levelUpDisablePart`

- `UIStringEvent onUnlockAction`

- `UIStringEvent onLevelUpAction`

- `UIStringEvent onDetailAction`

- `UIStringEvent onSelectAction`

- `UIStringEvent onChangeAction`

- `UniEquipImgHolder m_imgHolder`

- `Boolean m_initIfNot`

- `MissionAdapter m_adatper`

- `UICommonEquipTypeIcon m_typeIcon`

- `UniEquipSelectViewModel m_cacheViewModel`

- `Single m_selectAnimParam`

- `Boolean m_isInited`

- `String ANIM_PARAM`

- `Tween m_animTween`


## Methods

- `Void _InitIfNot()`

- `Void OnSelectUniEquip()`

- `Void OnCheckDetail()`

- `Void OnUnlockUniEquip()`

- `Void OnChangeUniEquip()`

- `Void OnLevelUpUniEquip()`

- `Void _ApplyAnimation(Boolean, Boolean)`

- `Void _RenderTags(UniEquipSelectViewModel)`

- `Void Render(UniEquipSelectViewModel, Boolean)`

- `Void _TryRaiseEquipSelectSignal()`

- `Void _RaiseEquipSelectSignal()`

- `Void InvokeUnlockAvgAction(Action`2)`

- `Void InvokeLevelupAvgAction(Action`1)`

- `Single <_ApplyAnimation>b__54_0()`

- `Void <_ApplyAnimation>b__54_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipSingleEquipView : MonoBehaviour, IHotfixable
{
	private Text _uniEquipName; // 0x18
	private UniEquipImgHolder _imgHolder; // 0x20
	private Transform _imgContainer; // 0x28
	private Single _scaler; // 0x30
	private GameObject _havePart; // 0x38
	private GameObject _dontHavePart; // 0x40
	private AnimationWrapper _animWrapper; // 0x48
	private GameObject _changeBtn; // 0x50
	private Text _commonCharEquipText; // 0x58
	private Text _equipChangeAttributeText; // 0x60
	private Text _equipChangeSubProfessionDescText; // 0x68
	private Text _equipChangeTalentDescText; // 0x70
	private Text _equipSpecialDescText; // 0x78
	private Image _levelPart; // 0x80
	private GameObject _focusPart; // 0x88
	private GameObject _focusPart2; // 0x90
	private GameObject _unlockObj; // 0x98
	private GameObject _unlockAvailablePart; // 0xa0
	private SimpleLayoutContent _content; // 0xa8
	private Transform _typeContainer; // 0xb0
	private CanvasGroup _typeCanvasGroup; // 0xb8
	private Single _typeValidAlpha; // 0xc0
	private Single _typeInvalidAlpha; // 0xc4
	private UICommonEquipTypeIcon _typeIcon; // 0xc8
	private GameObject _levelUpPart; // 0xd0
	private GameObject _levelMaxPart; // 0xd8
	private Sprite[] _levelSprites; // 0xe0
	private GameObject _selectedDetailBtn; // 0xe8
	private GameObject _hotSpotPart; // 0xf0
	private GameObject _selectHotspotPart; // 0xf8
	private GameObject _unlockHotspotPart; // 0x100
	private GameObject _levelUpEnoughPart; // 0x108
	private GameObject _levelUpDisablePart; // 0x110
	public UIStringEvent onUnlockAction; // 0x118
	public UIStringEvent onLevelUpAction; // 0x120
	public UIStringEvent onDetailAction; // 0x128
	public UIStringEvent onSelectAction; // 0x130
	public UIStringEvent onChangeAction; // 0x138
	private UniEquipImgHolder m_imgHolder; // 0x140
	private Boolean m_initIfNot; // 0x148
	private MissionAdapter m_adatper; // 0x150
	private UICommonEquipTypeIcon m_typeIcon; // 0x158
	private UniEquipSelectViewModel m_cacheViewModel; // 0x160
	private Single m_selectAnimParam; // 0x168
	private Boolean m_isInited; // 0x16c
	private String ANIM_PARAM; // 0x170
	private Tween m_animTween; // 0x178
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectUniEquip; // 0x8
	private static DelegateBridge __Hotfix0_OnCheckDetail; // 0x10
	private static DelegateBridge __Hotfix0_OnUnlockUniEquip; // 0x18
	private static DelegateBridge __Hotfix0_OnChangeUniEquip; // 0x20
	private static DelegateBridge __Hotfix0_OnLevelUpUniEquip; // 0x28
	private static DelegateBridge __Hotfix0__ApplyAnimation; // 0x30
	private static DelegateBridge __Hotfix0__RenderTags; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge __Hotfix0__TryRaiseEquipSelectSignal; // 0x48
	private static DelegateBridge __Hotfix0__RaiseEquipSelectSignal; // 0x50
	private static DelegateBridge __Hotfix0_InvokeUnlockAvgAction; // 0x58
	private static DelegateBridge __Hotfix0_InvokeLevelupAvgAction; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2304e34 VA: 0x759491ce34
	private Void _InitIfNot() { }
	// RVA: 0x2305010 VA: 0x759491d010
	public Void OnSelectUniEquip() { }
	// RVA: 0x23050ac VA: 0x759491d0ac
	public Void OnCheckDetail() { }
	// RVA: 0x2305148 VA: 0x759491d148
	public Void OnUnlockUniEquip() { }
	// RVA: 0x23051e4 VA: 0x759491d1e4
	public Void OnChangeUniEquip() { }
	// RVA: 0x2305280 VA: 0x759491d280
	public Void OnLevelUpUniEquip() { }
	// RVA: 0x230531c VA: 0x759491d31c
	private Void _ApplyAnimation(Boolean isSelect, Boolean needShining) { }
	// RVA: 0x2305684 VA: 0x759491d684
	private Void _RenderTags(UniEquipSelectViewModel viewModel) { }
	// RVA: 0x230441c VA: 0x759491c41c
	public Void Render(UniEquipSelectViewModel viewModel, Boolean needShining) { }
	// RVA: 0x2305540 VA: 0x759491d540
	private Void _TryRaiseEquipSelectSignal() { }
	// RVA: 0x2305880 VA: 0x759491d880
	private Void _RaiseEquipSelectSignal() { }
	// RVA: 0x2304a68 VA: 0x759491ca68
	public Void InvokeUnlockAvgAction(Action`2 traceUnlockAvgAction) { }
	// RVA: 0x2304b98 VA: 0x759491cb98
	public Void InvokeLevelupAvgAction(Action`1 traceLevelupAvgAction) { }
	// RVA: 0x23058e4 VA: 0x759491d8e4
	public Void .ctor() { }
	// RVA: 0x2305990 VA: 0x759491d990
	private Single <_ApplyAnimation>b__54_0() { }
	// RVA: 0x2305998 VA: 0x759491d998
	private Void <_ApplyAnimation>b__54_1(Single value) { }
}
```