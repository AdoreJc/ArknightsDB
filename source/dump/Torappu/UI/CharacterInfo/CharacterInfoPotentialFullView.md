# CharacterInfoPotentialFullView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `RectTransform _illustContainer`

- `SimpleLayoutContent _textPotentialContent`

- `Text _textCharacter`

- `AnimationWrapper _animationWrapper`

- `UICharacterIllust m_illust`

- `Adapter m_adapter`

- `Boolean m_hasInited`

- `Boolean <canSkipAnim>k__BackingField`

- `Action <onClick>k__BackingField`

- `TweenWrapper <tweenWrapper>k__BackingField`


## Properties

- `Boolean canSkipAnim`

- `Action onClick`

- `TweenWrapper tweenWrapper`

- `AnimationWrapper animationWrapper`


## Methods

- `Boolean get_canSkipAnim()`

- `Void set_canSkipAnim(Boolean)`

- `Action get_onClick()`

- `Void set_onClick(Action)`

- `TweenWrapper get_tweenWrapper()`

- `Void set_tweenWrapper(TweenWrapper)`

- `AnimationWrapper get_animationWrapper()`

- `Void LoadData(PlayerCharacter, CharacterData, UIPage)`

- `IEnumerator ShowAnim()`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialFullView : MonoBehaviour, IHotfixable
{
	public const String ANIM_ENTER; // 0x0
	public const String ANIM_SHOW_KEY; // 0x0
	private RectTransform _illustContainer; // 0x18
	private SimpleLayoutContent _textPotentialContent; // 0x20
	private Text _textCharacter; // 0x28
	private AnimationWrapper _animationWrapper; // 0x30
	private UICharacterIllust m_illust; // 0x38
	private Adapter m_adapter; // 0x40
	private Boolean m_hasInited; // 0x48
	private Boolean <canSkipAnim>k__BackingField; // 0x49
	private Action <onClick>k__BackingField; // 0x50
	private TweenWrapper <tweenWrapper>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_canSkipAnim; // 0x0
	private static DelegateBridge __Hotfix0_set_canSkipAnim; // 0x8
	private static DelegateBridge __Hotfix0_get_onClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onClick; // 0x18
	private static DelegateBridge __Hotfix0_get_tweenWrapper; // 0x20
	private static DelegateBridge __Hotfix0_set_tweenWrapper; // 0x28
	private static DelegateBridge __Hotfix0_get_animationWrapper; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_ShowAnim; // 0x40
	private static DelegateBridge __Hotfix0_OnClick; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean canSkipAnim { get; set; }
	private Action onClick { get; set; }
	public TweenWrapper tweenWrapper { get; set; }
	public AnimationWrapper animationWrapper { get; }

	// RVA: 0x2d7ca00 VA: 0x7595394a00
	public Boolean get_canSkipAnim() { }
	// RVA: 0x2d7ca68 VA: 0x7595394a68
	private Void set_canSkipAnim(Boolean value) { }
	// RVA: 0x2d7cae8 VA: 0x7595394ae8
	private Action get_onClick() { }
	// RVA: 0x2d7cb50 VA: 0x7595394b50
	public Void set_onClick(Action value) { }
	// RVA: 0x2d7cbd4 VA: 0x7595394bd4
	public TweenWrapper get_tweenWrapper() { }
	// RVA: 0x2d7cc3c VA: 0x7595394c3c
	private Void set_tweenWrapper(TweenWrapper value) { }
	// RVA: 0x2d7ccc0 VA: 0x7595394cc0
	public AnimationWrapper get_animationWrapper() { }
	// RVA: 0x2d7cd28 VA: 0x7595394d28
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, UIPage page) { }
	// RVA: 0x2d7d17c VA: 0x759539517c
	public IEnumerator ShowAnim() { }
	// RVA: 0x2d7d250 VA: 0x7595395250
	public Void OnClick() { }
	// RVA: 0x2d7d02c VA: 0x759539502c
	private Void _InitIfNot() { }
	// RVA: 0x2d7d35c VA: 0x759539535c
	public Void .ctor() { }
}
```