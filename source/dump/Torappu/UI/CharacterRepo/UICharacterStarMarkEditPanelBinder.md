# UICharacterStarMarkEditPanelBinder

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `Transform _editPanelContainer`

- `UICharacterStarMarkEditPanel _editPanelPrefab`

- `UnityEvent _eventOnStarMarkConfirm`

- `UnityEvent _eventOnClearAllStarMark`

- `UnityEvent _eventOnExitStarMarkEdit`

- `UIAnimationLocation _starMarkTopShowAnmi`

- `UIAnimationLocation _topbarBgScaleToShortAnim`

- `UICharacterStarMarkEditPanel m_starMarkEditPanel`

- `Boolean m_isInited`

- `AnimationSwitchTween m_starMarkTopBtnShowSwitch`

- `AnimationSwitchTween m_topbarBgScaleToShortSwitch`


## Methods

- `Void _InitIfNot()`

- `Void _HideStarMarkBtn()`

- `Void _ShowStarMarkBtn()`

- `Void <_InitIfNot>b__12_0()`

- `Void <_InitIfNot>b__12_1()`

- `Void <_InitIfNot>b__12_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class UICharacterStarMarkEditPanelBinder : DataBinder`1, IHotfixable
{
	private Transform _editPanelContainer; // 0x20
	private UICharacterStarMarkEditPanel _editPanelPrefab; // 0x28
	private UnityEvent _eventOnStarMarkConfirm; // 0x30
	private UnityEvent _eventOnClearAllStarMark; // 0x38
	private UnityEvent _eventOnExitStarMarkEdit; // 0x40
	private UIAnimationLocation _starMarkTopShowAnmi; // 0x48
	private UIAnimationLocation _topbarBgScaleToShortAnim; // 0x58
	private UICharacterStarMarkEditPanel m_starMarkEditPanel; // 0x68
	private Boolean m_isInited; // 0x70
	private AnimationSwitchTween m_starMarkTopBtnShowSwitch; // 0x78
	private AnimationSwitchTween m_topbarBgScaleToShortSwitch; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__HideStarMarkBtn; // 0x10
	private static DelegateBridge __Hotfix0__ShowStarMarkBtn; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2cff0a4 VA: 0x75953170a4
	public override Void OnValueChanged(CharacterRepoCardGroupViewProperty property) { }
	// RVA: 0x2cff1bc VA: 0x75953171bc
	private Void _InitIfNot() { }
	// RVA: 0x2cff484 VA: 0x7595317484
	private Void _HideStarMarkBtn() { }
	// RVA: 0x2cff510 VA: 0x7595317510
	private Void _ShowStarMarkBtn() { }
	// RVA: 0x2cff59c VA: 0x759531759c
	public Void .ctor() { }
	// RVA: 0x2cff62c VA: 0x759531762c
	private Void <_InitIfNot>b__12_0() { }
	// RVA: 0x2cff648 VA: 0x7595317648
	private Void <_InitIfNot>b__12_1() { }
	// RVA: 0x2cff664 VA: 0x7595317664
	private Void <_InitIfNot>b__12_2() { }
}
```