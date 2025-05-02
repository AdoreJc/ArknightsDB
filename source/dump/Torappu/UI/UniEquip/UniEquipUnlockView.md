# UniEquipUnlockView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Image _equipImg`

- `GameObject _panelMission`

- `UniEquipUnlockMissionItemView _missionPrefab`

- `RectTransform _mission1Container`

- `RectTransform _mission2Container`

- `SimpleLayoutContent _infoLayoutContent`

- `SimpleLayoutContent _itemLayoutContent`

- `Text _confirmInfoText`

- `AnimationWrapper _equipAnimationWrapper`

- `UIAnimationLocation _previewLocation`

- `Boolean m_isInited`

- `Boolean m_isAnimInited`

- `String ANIM_PARAM`

- `InfoAdapter m_infoAdapter`

- `ItemAdapter m_itemAdapter`

- `UniEquipUnlockMissionItemView m_mission1View`

- `UniEquipUnlockMissionItemView m_mission2View`

- `AnimationSwitchTween m_animTransPreviewSwitchTween`

- `UIPageFinder m_pageFinder`


## Methods

- `Void ResetAnim()`

- `Void PlayEnterAnim()`

- `Void PlayTransPreviewAnim(Boolean)`

- `Void _InitIfNot()`

- `Void _AnimInitIfNot()`

- `Void _ResetInfoAnim(Boolean)`

- `IEnumerator _InfoEffectAnim(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockView : DataBinder`1
{
	private Image _equipImg; // 0x20
	private GameObject _panelMission; // 0x28
	private UniEquipUnlockMissionItemView _missionPrefab; // 0x30
	private RectTransform _mission1Container; // 0x38
	private RectTransform _mission2Container; // 0x40
	private SimpleLayoutContent _infoLayoutContent; // 0x48
	private SimpleLayoutContent _itemLayoutContent; // 0x50
	private Text _confirmInfoText; // 0x58
	private AnimationWrapper _equipAnimationWrapper; // 0x60
	private UIAnimationLocation _previewLocation; // 0x68
	private Boolean m_isInited; // 0x78
	private Boolean m_isAnimInited; // 0x79
	private String ANIM_PARAM; // 0x80
	private InfoAdapter m_infoAdapter; // 0x88
	private ItemAdapter m_itemAdapter; // 0x90
	private UniEquipUnlockMissionItemView m_mission1View; // 0x98
	private UniEquipUnlockMissionItemView m_mission2View; // 0xa0
	private AnimationSwitchTween m_animTransPreviewSwitchTween; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_ResetAnim; // 0x8
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0_PlayTransPreviewAnim; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__AnimInitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__ResetInfoAnim; // 0x30
	private static DelegateBridge __Hotfix0__InfoEffectAnim; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x231058c VA: 0x759492858c
	public override Void OnValueChanged(UnlockViewProperty property) { }
	// RVA: 0x2310908 VA: 0x7594928908
	public Void ResetAnim() { }
	// RVA: 0x2310c14 VA: 0x7594928c14
	public Void PlayEnterAnim() { }
	// RVA: 0x2310da4 VA: 0x7594928da4
	public Void PlayTransPreviewAnim(Boolean isShow) { }
	// RVA: 0x23107d0 VA: 0x75949287d0
	private Void _InitIfNot() { }
	// RVA: 0x23109bc VA: 0x75949289bc
	private Void _AnimInitIfNot() { }
	// RVA: 0x2310aac VA: 0x7594928aac
	private Void _ResetInfoAnim(Boolean isShow) { }
	// RVA: 0x2310cdc VA: 0x7594928cdc
	private IEnumerator _InfoEffectAnim(Boolean isShow) { }
	// RVA: 0x2310e80 VA: 0x7594928e80
	public Void .ctor() { }
}
```