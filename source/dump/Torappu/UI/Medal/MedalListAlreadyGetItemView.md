# MedalListAlreadyGetItemView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _icon`

- `Text _getTime`

- `Text _name`

- `Text _description`

- `AnimationWrapper _animationWrapper`

- `GameObject _advancedIcon`

- `UIStringEvent toTargetMedal`

- `MedalCommonViewModel m_viewModelCache`


## Properties

- `AnimationWrapper animationWrapper`


## Methods

- `AnimationWrapper get_animationWrapper()`

- `Void RenderView(MedalCommonViewModel)`

- `Void OnClick()`

- `Void _HideAnimation()`

- `Void _ShowAnimation(String)`

- `Void _ResetAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListAlreadyGetItemView : MonoBehaviour, IHotfixable, IMedalListItem
{
	private Image _icon; // 0x18
	private Text _getTime; // 0x20
	private Text _name; // 0x28
	private Text _description; // 0x30
	private AnimationWrapper _animationWrapper; // 0x38
	private GameObject _advancedIcon; // 0x40
	public UIStringEvent toTargetMedal; // 0x48
	private MedalCommonViewModel m_viewModelCache; // 0x50
	public const String HIDE_PARAM; // 0x0
	public const String SHOW_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_get_animationWrapper; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0__HideAnimation; // 0x18
	private static DelegateBridge __Hotfix0__ShowAnimation; // 0x20
	private static DelegateBridge __Hotfix0__ResetAnimation; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected AnimationWrapper animationWrapper { get; }

	// RVA: 0x27a07a0 VA: 0x7594db87a0
	protected AnimationWrapper get_animationWrapper() { }
	// RVA: 0x27a0808 VA: 0x7594db8808
	public Void RenderView(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a0b94 VA: 0x7594db8b94
	public Void OnClick() { }
	// RVA: 0x27a0cdc VA: 0x7594db8cdc
	private Void _HideAnimation() { }
	// RVA: 0x27a0d80 VA: 0x7594db8d80
	private Void _ShowAnimation(String targetMedal) { }
	// RVA: 0x27a0b08 VA: 0x7594db8b08
	private Void _ResetAnimation() { }
	// RVA: 0x27a0eac VA: 0x7594db8eac
	public Void .ctor() { }
}
```