# MedalListAlreadyGetItemDetailView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Single _scaler`

- `GameObject _rewardPart`

- `Transform _itemContainer`

- `Text _itemName`

- `GameObject _preObj`

- `Text _getMethodText`

- `SimpleLayoutContent _content`

- `MedalAdvanceCommonView _advancedView`

- `GameObject _advancedIcon`

- `GameObject _hasAdvancedIcon`

- `Image _icon`

- `Text _getTime`

- `Text _name`

- `Text _description`

- `AnimationWrapper _animationWrapper`

- `UIStringEvent toTargetMedal`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `MedalLittleAdapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void ApplyAnimation()`

- `Boolean IsPlaying()`

- `Void SetToLargeCommon()`

- `Void StopAnimation()`

- `Void RenderDetailView(MedalCommonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListAlreadyGetItemDetailView : MonoBehaviour, IHotfixable
{
	private Single _scaler; // 0x18
	private GameObject _rewardPart; // 0x20
	private Transform _itemContainer; // 0x28
	private Text _itemName; // 0x30
	private GameObject _preObj; // 0x38
	private Text _getMethodText; // 0x40
	private SimpleLayoutContent _content; // 0x48
	private MedalAdvanceCommonView _advancedView; // 0x50
	private GameObject _advancedIcon; // 0x58
	private GameObject _hasAdvancedIcon; // 0x60
	private Image _icon; // 0x68
	private Text _getTime; // 0x70
	private Text _name; // 0x78
	private Text _description; // 0x80
	private AnimationWrapper _animationWrapper; // 0x88
	public UIStringEvent toTargetMedal; // 0x90
	private Boolean m_isInited; // 0x98
	private UIItemCard m_itemCard; // 0xa0
	private MedalLittleAdapter m_adapter; // 0xa8
	private const String ANIMATION_PARAM_DOWN; // 0x0
	private const String ANIMATION_PARAM_UP; // 0x0
	private const String LARGE_COMMON; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_ApplyAnimation; // 0x8
	private static DelegateBridge __Hotfix0_IsPlaying; // 0x10
	private static DelegateBridge __Hotfix0_SetToLargeCommon; // 0x18
	private static DelegateBridge __Hotfix0_StopAnimation; // 0x20
	private static DelegateBridge __Hotfix0_RenderDetailView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x27a0208 VA: 0x7594db8208
	private Void _InitIfNot() { }
	// RVA: 0x279fa70 VA: 0x7594db7a70
	public Void ApplyAnimation() { }
	// RVA: 0x279f9a8 VA: 0x7594db79a8
	public Boolean IsPlaying() { }
	// RVA: 0x279a560 VA: 0x7594db2560
	public Void SetToLargeCommon() { }
	// RVA: 0x2799cbc VA: 0x7594db1cbc
	public Void StopAnimation() { }
	// RVA: 0x2799d78 VA: 0x7594db1d78
	public Void RenderDetailView(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a0464 VA: 0x7594db8464
	public Void .ctor() { }
}
```