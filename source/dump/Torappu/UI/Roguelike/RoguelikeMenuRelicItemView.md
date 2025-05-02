# RoguelikeMenuRelicItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _imageIcon`

- `CanvasGroup _pnlWhole`

- `CanvasGroup _pnlHalf`

- `CanvasGroup _canvasHandler`

- `Action onClickEvent`

- `UISwitchTween m_switchTween`

- `String m_cachedItemId`

- `Boolean m_hasInited`


## Properties

- `CanvasGroup alphaHandler`


## Methods

- `CanvasGroup get_alphaHandler()`

- `Void _InitIfNot()`

- `Void Render(IRoguelikeRelicViewModel, Boolean, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicItemView : MonoBehaviour, IHotfixable
{
	private const Single SWITCH_DURATION; // 0x0
	private Image _imageIcon; // 0x18
	private CanvasGroup _pnlWhole; // 0x20
	private CanvasGroup _pnlHalf; // 0x28
	private CanvasGroup _canvasHandler; // 0x30
	public Action onClickEvent; // 0x38
	private UISwitchTween m_switchTween; // 0x40
	private String m_cachedItemId; // 0x48
	private Boolean m_hasInited; // 0x50
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CanvasGroup alphaHandler { get; }

	// RVA: 0x2a41300 VA: 0x7595059300
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x2a41368 VA: 0x7595059368
	private Void _InitIfNot() { }
	// RVA: 0x2a414b8 VA: 0x75950594b8
	public Void Render(IRoguelikeRelicViewModel viewModel, Boolean showFullIcon, Boolean isInit) { }
	// RVA: 0x2a416f0 VA: 0x75950596f0
	public Void OnClick() { }
	// RVA: 0x2a41774 VA: 0x7595059774
	public Void .ctor() { }
}
```