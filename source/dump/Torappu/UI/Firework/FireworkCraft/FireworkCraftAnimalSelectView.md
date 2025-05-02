# FireworkCraftAnimalSelectView

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `Image _imgSelectedAnimal`

- `Text _textSelectedAnimalDesc`

- `GameObject _pnlEquip`

- `GameObject _pnlAlreadyEquiped`

- `UIAnimationLocation _animEnter`

- `Button _btnAnimal`

- `UISpineWrapper _spineWrapperLeft`

- `UISpineWrapper _spineWrapperRight`

- `String m_cachedSelectedAnimal`

- `Int32 m_cachedLoadSeqNum`

- `UIStateFinder m_stateFinder`

- `Tween m_showTween`


## Properties

- `Boolean isPlayingEnterAnim`


## Methods

- `Boolean get_isPlayingEnterAnim()`

- `Void RegisterTutorialGo()`

- `Void OnEquipBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftAnimalSelectView : DataBinder`1
{
	private const String LEFT_SPINE_ANIM_NAME; // 0x0
	private const String RIGHT_SPINE_ANIM_NAME; // 0x0
	private FireworkCraftAnimalSelectAnimalView[] _animalViews; // 0x20
	private Image _imgSelectedAnimal; // 0x28
	private Text _textSelectedAnimalDesc; // 0x30
	private GameObject _pnlEquip; // 0x38
	private GameObject _pnlAlreadyEquiped; // 0x40
	private UIAnimationLocation _animEnter; // 0x48
	private Button _btnAnimal; // 0x58
	private UISpineWrapper _spineWrapperLeft; // 0x60
	private UISpineWrapper _spineWrapperRight; // 0x68
	private String m_cachedSelectedAnimal; // 0x70
	private Int32 m_cachedLoadSeqNum; // 0x78
	private UIStateFinder m_stateFinder; // 0x80
	private Tween m_showTween; // 0x90
	private static DelegateBridge __Hotfix0_get_isPlayingEnterAnim; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0_OnEquipBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isPlayingEnterAnim { get; }

	// RVA: 0x2902828 VA: 0x7594f1a828
	public Boolean get_isPlayingEnterAnim() { }
	// RVA: 0x29029b8 VA: 0x7594f1a9b8
	public override Void OnValueChanged(FireworkCraftAnimalSelectProperty property) { }
	// RVA: 0x29028a4 VA: 0x7594f1a8a4
	public Void RegisterTutorialGo() { }
	// RVA: 0x2902d50 VA: 0x7594f1ad50
	public Void OnEquipBtnClicked() { }
	// RVA: 0x2902e14 VA: 0x7594f1ae14
	public Void .ctor() { }
}
```