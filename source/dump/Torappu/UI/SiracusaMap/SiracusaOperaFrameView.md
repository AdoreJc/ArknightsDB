# SiracusaOperaFrameView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIAnimationLocation _animationLocation`

- `Button _clickBtn`

- `Text _titleMain`

- `Text _titleSub`

- `Text _scoreText`

- `UIAtlasImage _numImg`

- `UIAtlasObject _atlasObj`

- `GameObject _activePart`

- `GameObject _passPart`

- `Text _passText`

- `Text _passTimeText`

- `GameObject _futurePart`

- `Text _futureTimeText`

- `Text _futureText`

- `Image _backSprite`

- `Text _addCount`

- `Text _admireCount`

- `GameObject _admirePart`

- `GameObject _unableMask`

- `GameObject _unopenText`

- `SimpleLayoutContent _headIconContent`

- `Transform _commentContainer`

- `UIIntEvent onClickFocus`

- `UIPage page`

- `Adapter m_adapter`

- `AnimationSwitchTween m_switchTween`

- `Boolean m_isInited`

- `SiracusaOperaFrameViewModel m_cacheViewModel`


## Methods

- `Void Render(SiracusaOperaFrameViewModel, Boolean, Boolean)`

- `Sprite LoadSiracusaAvatar(String)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaFrameView : MonoBehaviour, IHotfixable
{
	public const Single TWEEN_DURATION; // 0x0
	private const String NUM_SPRITE_ID; // 0x0
	private UIAnimationLocation _animationLocation; // 0x18
	private Button _clickBtn; // 0x28
	private Text _titleMain; // 0x30
	private Text _titleSub; // 0x38
	private Text _scoreText; // 0x40
	private UIAtlasImage _numImg; // 0x48
	private UIAtlasObject _atlasObj; // 0x50
	private GameObject _activePart; // 0x58
	private GameObject _passPart; // 0x60
	private Text _passText; // 0x68
	private Text _passTimeText; // 0x70
	private GameObject _futurePart; // 0x78
	private Text _futureTimeText; // 0x80
	private Text _futureText; // 0x88
	private Image _backSprite; // 0x90
	private Text _addCount; // 0x98
	private Text _admireCount; // 0xa0
	private GameObject _admirePart; // 0xa8
	private GameObject _unableMask; // 0xb0
	private GameObject _unopenText; // 0xb8
	private SimpleLayoutContent _headIconContent; // 0xc0
	private Transform _commentContainer; // 0xc8
	public UIIntEvent onClickFocus; // 0xd0
	public UIPage page; // 0xd8
	private Adapter m_adapter; // 0xe0
	private AnimationSwitchTween m_switchTween; // 0xe8
	private Boolean m_isInited; // 0xf0
	private SiracusaOperaFrameViewModel m_cacheViewModel; // 0xf8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_LoadSiracusaAvatar; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23fb0ec VA: 0x7594a130ec
	public Void Render(SiracusaOperaFrameViewModel viewModel, Boolean isSelected, Boolean needRefesh) { }
	// RVA: 0x23fb7f4 VA: 0x7594a137f4
	public Sprite LoadSiracusaAvatar(String operaId) { }
	// RVA: 0x23fb880 VA: 0x7594a13880
	public Void OnClick() { }
	// RVA: 0x23fb698 VA: 0x7594a13698
	private Void _InitIfNot() { }
	// RVA: 0x23fb91c VA: 0x7594a1391c
	public Void .ctor() { }
}
```