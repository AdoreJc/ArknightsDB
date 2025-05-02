# RoguelikeShopNpcView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasGroup`

- `Text _textDialog`

- `Single _alphaTweenDelay`

- `Single _alphaTweenDuration`

- `Single _textTweenDuration`

- `Tween m_alphaTweener`

- `Tween m_textTweener`


## Properties

- `Boolean isTweening`


## Methods

- `Boolean get_isTweening()`

- `Void Render(String, Boolean)`

- `Void _PlayTextTween(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopNpcView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasGroup; // 0x18
	private Text _textDialog; // 0x20
	private Single _alphaTweenDelay; // 0x28
	private Single _alphaTweenDuration; // 0x2c
	private Single _textTweenDuration; // 0x30
	private Tween m_alphaTweener; // 0x38
	private Tween m_textTweener; // 0x40
	private static DelegateBridge __Hotfix0_get_isTweening; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__PlayTextTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isTweening { get; }

	// RVA: 0x2aec378 VA: 0x7595104378
	public Boolean get_isTweening() { }
	// RVA: 0x2aec418 VA: 0x7595104418
	public Void Render(String dialog, Boolean tweenAlpha) { }
	// RVA: 0x2aec64c VA: 0x759510464c
	private Void _PlayTextTween(String dialog) { }
	// RVA: 0x2aec7b4 VA: 0x75951047b4
	public Void .ctor() { }
}
```