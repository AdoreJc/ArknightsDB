# RoguelikeNpcDialogView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasGroup`

- `Text _textDialog`

- `Single _alphaTweenDelay`

- `Single _alphaTweenDuration`

- `Single _textTweenDuration`

- `GameObject _npcPanel`

- `GameObject _npcGonePanel`

- `Boolean m_hasInited`

- `Tween m_alphaTweener`

- `Tween m_textTweener`


## Properties

- `Boolean isTweening`


## Methods

- `Boolean get_isTweening()`

- `Void _RenderNpc(Boolean)`

- `Void _PlayTextTween(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeNpcDialogView : DataBinder`1
{
	private CanvasGroup _canvasGroup; // 0x20
	private Text _textDialog; // 0x28
	private Single _alphaTweenDelay; // 0x30
	private Single _alphaTweenDuration; // 0x34
	private Single _textTweenDuration; // 0x38
	private GameObject _npcPanel; // 0x40
	private GameObject _npcGonePanel; // 0x48
	private Boolean m_hasInited; // 0x50
	private Tween m_alphaTweener; // 0x58
	private Tween m_textTweener; // 0x60
	private static DelegateBridge __Hotfix0_get_isTweening; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__RenderNpc; // 0x10
	private static DelegateBridge __Hotfix0__PlayTextTween; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isTweening { get; }

	// RVA: 0x2ad7de8 VA: 0x75950efde8
	public Boolean get_isTweening() { }
	// RVA: 0x2ae6300 VA: 0x75950fe300
	public override Void OnValueChanged(RoguelikeGameShopDialogProp property) { }
	// RVA: 0x2ae65b0 VA: 0x75950fe5b0
	private Void _RenderNpc(Boolean npcExist) { }
	// RVA: 0x2ae66bc VA: 0x75950fe6bc
	private Void _PlayTextTween(String dialog) { }
	// RVA: 0x2ae6824 VA: 0x75950fe824
	public Void .ctor() { }
}
```