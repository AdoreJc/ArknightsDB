# RetroTrailRewardView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Image _backImage`

- `SimpleLayoutContent _content`

- `Image _backImg`

- `Image _titleImg`

- `GameObject _portraitCont`

- `Transform _illustContainer`

- `Image _potentialImg`

- `Text _currentStar`

- `Text _maxStar`

- `UIStringEvent _onClickEvent`

- `Image _rarityImg`

- `Image _professionImg`

- `Text _charName`

- `TwoStateToggle _toggleCharFullPotential`

- `Adapter m_adatper`

- `Boolean m_isInited`

- `UICharacterIllust m_illust`


## Methods

- `Void _InitIfNot()`

- `Void Render(SideStoryViewModel, UICharacterIllustLoader)`

- `Void _LoadRetroBackImage(String, String, UICharacterIllustLoader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class RetroTrailRewardView : MonoBehaviour, IHotfixable
{
	private Image _backImage; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private Image _backImg; // 0x28
	private Image _titleImg; // 0x30
	private GameObject _portraitCont; // 0x38
	private Transform _illustContainer; // 0x40
	private Image _potentialImg; // 0x48
	private Text _currentStar; // 0x50
	private Text _maxStar; // 0x58
	private UIStringEvent _onClickEvent; // 0x60
	private Image _rarityImg; // 0x68
	private Image _professionImg; // 0x70
	private Text _charName; // 0x78
	private TwoStateToggle _toggleCharFullPotential; // 0x80
	private Adapter m_adatper; // 0x88
	private Boolean m_isInited; // 0x90
	private UICharacterIllust m_illust; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__LoadRetroBackImage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f149a0 VA: 0x759552c9a0
	private Void _InitIfNot() { }
	// RVA: 0x2f14b48 VA: 0x759552cb48
	public Void Render(SideStoryViewModel storyViewModel, UICharacterIllustLoader illustLoader) { }
	// RVA: 0x2f14e7c VA: 0x759552ce7c
	private Void _LoadRetroBackImage(String retroId, String charId, UICharacterIllustLoader illustLoader) { }
	// RVA: 0x2f15200 VA: 0x759552d200
	public Void .ctor() { }
}
```