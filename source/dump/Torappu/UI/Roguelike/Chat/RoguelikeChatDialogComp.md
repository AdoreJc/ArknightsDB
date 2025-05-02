# RoguelikeChatDialogComp

**Namespace:** `Torappu.UI.Roguelike.Chat`


## Fields

- `Image _imgAvater`

- `Text _dialog`

- `Single _textPadding`

- `Single _avatarHeight`

- `Single _fadeInPos`

- `CanvasGroup _fadeInAlpha`

- `RectTransform _fadeInTrans`

- `Single _fadeInDuration`

- `Single _postDelay`

- `PreferSizeCalculator m_sizeCalculator`

- `FadeTranslationSwitchTween m_switchTween`


## Methods

- `PreferSizeCalculator _GetSizeCalculator()`

- `Void _Render(String, String)`

- `Void _SetDisplay(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Chat
public class RoguelikeChatDialogComp : MonoBehaviour, IHotfixable
{
	private Image _imgAvater; // 0x18
	private Text _dialog; // 0x20
	private Single _textPadding; // 0x28
	private Single _avatarHeight; // 0x2c
	private Single _fadeInPos; // 0x30
	private CanvasGroup _fadeInAlpha; // 0x38
	private RectTransform _fadeInTrans; // 0x40
	private Single _fadeInDuration; // 0x48
	private Single _postDelay; // 0x4c
	private PreferSizeCalculator m_sizeCalculator; // 0x50
	private FadeTranslationSwitchTween m_switchTween; // 0x58
	private static DelegateBridge __Hotfix0__GetSizeCalculator; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__SetDisplay; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2bb7aa4 VA: 0x75951cfaa4
	private PreferSizeCalculator _GetSizeCalculator() { }
	// RVA: 0x2bb7bf8 VA: 0x75951cfbf8
	private Void _Render(String avatarId, String content) { }
	// RVA: 0x2bb7cdc VA: 0x75951cfcdc
	private Void _SetDisplay(Boolean isShow, Boolean useFastMode) { }
	// RVA: 0x2bb7e4c VA: 0x75951cfe4c
	public Void .ctor() { }
}
```