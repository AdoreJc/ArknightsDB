# MedalListNotGetItemView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Text _name`

- `Image _icon`

- `GameObject _haveRewardFlag`

- `GameObject _panelGetPart`

- `Text _getDesc`

- `GameObject _panelDescPart`

- `Text _textDesc`

- `AnimationWrapper _animationWrapper`

- `UIStringEvent toTargetMedal`

- `MedalCommonViewModel m_viewModelCache`

- `DisplayInfoCache m_displayCache`


## Properties

- `AnimationWrapper animationWrapper`


## Methods

- `AnimationWrapper get_animationWrapper()`

- `Void OnClick()`

- `Void RenderView(MedalCommonViewModel)`

- `Void _HideAnimation()`

- `Void _ShowAnimation(String)`

- `Void _ResetAnimation()`

- `Void _UpdateGetPart(MedalCommonViewModel)`

- `Void _UpdateDescPart(MedalCommonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListNotGetItemView : MonoBehaviour, IHotfixable, IMedalListItem
{
	private Text _name; // 0x18
	private Image _icon; // 0x20
	private GameObject _haveRewardFlag; // 0x28
	private GameObject _panelGetPart; // 0x30
	private Text _getDesc; // 0x38
	private GameObject _panelDescPart; // 0x40
	private Text _textDesc; // 0x48
	private AnimationWrapper _animationWrapper; // 0x50
	public UIStringEvent toTargetMedal; // 0x58
	private MedalCommonViewModel m_viewModelCache; // 0x60
	private DisplayInfoCache m_displayCache; // 0x68
	public const String HIDE_PARAM; // 0x0
	public const String SHOW_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_get_animationWrapper; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0__HideAnimation; // 0x18
	private static DelegateBridge __Hotfix0__ShowAnimation; // 0x20
	private static DelegateBridge __Hotfix0__ResetAnimation; // 0x28
	private static DelegateBridge __Hotfix0__UpdateGetPart; // 0x30
	private static DelegateBridge __Hotfix0__UpdateDescPart; // 0x38
	private static DelegateBridge __Hotfix0__GenerateGetMethodDesc; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected AnimationWrapper animationWrapper { get; }

	// RVA: 0x27a2ec4 VA: 0x7594dbaec4
	protected AnimationWrapper get_animationWrapper() { }
	// RVA: 0x27a2f2c VA: 0x7594dbaf2c
	public Void OnClick() { }
	// RVA: 0x27a3120 VA: 0x7594dbb120
	public Void RenderView(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a307c VA: 0x7594dbb07c
	private Void _HideAnimation() { }
	// RVA: 0x27a3724 VA: 0x7594dbb724
	private Void _ShowAnimation(String targetMedal) { }
	// RVA: 0x27a3374 VA: 0x7594dbb374
	private Void _ResetAnimation() { }
	// RVA: 0x27a354c VA: 0x7594dbb54c
	private Void _UpdateGetPart(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a3648 VA: 0x7594dbb648
	private Void _UpdateDescPart(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a38b8 VA: 0x7594dbb8b8
	private static String _GenerateGetMethodDesc(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a3c10 VA: 0x7594dbbc10
	public Void .ctor() { }
}
```