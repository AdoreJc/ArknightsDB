# UniEquipUnlockInfoItemView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Text _titleText`

- `UICommentedText _descText`

- `UIAnimationLocation _animLocation`

- `Image _levelImage`

- `Color _iniLevelImageColor`

- `Color _maxLevelImageColor`

- `AnimationSwitchTween m_animSwitchTween`

- `Boolean m_isInited`


## Methods

- `Void Render(InfoData, Int32)`

- `Void ResetAnim(Boolean)`

- `Void AnimRender(Boolean)`

- `Void _AnimInitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockInfoItemView : MonoBehaviour, IHotfixable
{
	private Text _titleText; // 0x18
	private UICommentedText _descText; // 0x20
	private UIAnimationLocation _animLocation; // 0x28
	private Image _levelImage; // 0x38
	private List`1 _stageSprites; // 0x40
	private Color _iniLevelImageColor; // 0x48
	private Color _maxLevelImageColor; // 0x58
	private AnimationSwitchTween m_animSwitchTween; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetAnim; // 0x8
	private static DelegateBridge __Hotfix0_AnimRender; // 0x10
	private static DelegateBridge __Hotfix0__AnimInitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x230f234 VA: 0x7594927234
	public Void Render(InfoData infoData, Int32 level) { }
	// RVA: 0x230f3c4 VA: 0x75949273c4
	public Void ResetAnim(Boolean isShow) { }
	// RVA: 0x230f450 VA: 0x7594927450
	public Void AnimRender(Boolean isShow) { }
	// RVA: 0x230f4e4 VA: 0x75949274e4
	private Void _AnimInitIfNot() { }
	// RVA: 0x230f5d4 VA: 0x75949275d4
	public Void .ctor() { }
}
```