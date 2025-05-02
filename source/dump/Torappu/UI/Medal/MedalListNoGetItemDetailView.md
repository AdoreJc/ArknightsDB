# MedalListNoGetItemDetailView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Text _name`

- `Text _getDesc`

- `Text _desc`

- `GameObject _preObj`

- `Image _icon`

- `SimpleLayoutContent _preObjList`

- `GameObject _haveRewardFlag`

- `AnimationWrapper _animationWrapper`

- `Single _scaler`

- `GameObject _rewardPart`

- `Transform _itemContainer`

- `Text _itemName`

- `MedalAdvanceCommonView _advancedView`

- `GameObject _advancedIcon`

- `UIStringEvent toTargetMedal`

- `MedalCommonViewModel m_viewModelCache`

- `MedalLittleAdapter m_adapter`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Properties

- `AnimationWrapper animationWrapper`


## Methods

- `AnimationWrapper get_animationWrapper()`

- `Void _InitIfNot()`

- `Void RenderView(MedalCommonViewModel)`

- `Void SetToLargeCommon()`

- `Void ApplyAnimation()`

- `Boolean IsPlaying()`

- `Void StopAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListNoGetItemDetailView : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _getDesc; // 0x20
	private Text _desc; // 0x28
	private GameObject _preObj; // 0x30
	private Image _icon; // 0x38
	private SimpleLayoutContent _preObjList; // 0x40
	private GameObject _haveRewardFlag; // 0x48
	private AnimationWrapper _animationWrapper; // 0x50
	private Single _scaler; // 0x58
	private GameObject _rewardPart; // 0x60
	private Transform _itemContainer; // 0x68
	private Text _itemName; // 0x70
	private MedalAdvanceCommonView _advancedView; // 0x78
	private GameObject _advancedIcon; // 0x80
	public UIStringEvent toTargetMedal; // 0x88
	private MedalCommonViewModel m_viewModelCache; // 0x90
	private MedalLittleAdapter m_adapter; // 0x98
	private UIItemCard m_itemCard; // 0xa0
	private Boolean m_isInited; // 0xa8
	private const String ANIMATION_PARAM_DOWN; // 0x0
	private const String ANIMATION_PARAM_UP; // 0x0
	private const String LARGE_COMMON; // 0x0
	private static DelegateBridge __Hotfix0_get_animationWrapper; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_SetToLargeCommon; // 0x18
	private static DelegateBridge __Hotfix0_ApplyAnimation; // 0x20
	private static DelegateBridge __Hotfix0_IsPlaying; // 0x28
	private static DelegateBridge __Hotfix0_StopAnimation; // 0x30
	private static DelegateBridge __Hotfix0__GenerateGetMethodDesc; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected AnimationWrapper animationWrapper { get; }

	// RVA: 0x27a1960 VA: 0x7594db9960
	protected AnimationWrapper get_animationWrapper() { }
	// RVA: 0x27a19c8 VA: 0x7594db99c8
	private Void _InitIfNot() { }
	// RVA: 0x27a1bb0 VA: 0x7594db9bb0
	public Void RenderView(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a27f8 VA: 0x7594dba7f8
	public Void SetToLargeCommon() { }
	// RVA: 0x27a2888 VA: 0x7594dba888
	public Void ApplyAnimation() { }
	// RVA: 0x27a2a44 VA: 0x7594dbaa44
	public Boolean IsPlaying() { }
	// RVA: 0x27a2b14 VA: 0x7594dbab14
	public Void StopAnimation() { }
	// RVA: 0x27a214c VA: 0x7594dba14c
	private static String _GenerateGetMethodDesc(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a2e14 VA: 0x7594dbae14
	public Void .ctor() { }
}
```