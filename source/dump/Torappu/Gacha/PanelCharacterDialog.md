# PanelCharacterDialog

**Namespace:** `Torappu.Gacha`


## Fields

- `Single _fadeinTime`

- `AVGTypeWriterText _text`

- `RectTransform _messageRect`

- `Single _messageRectBottomPadding`

- `Boolean m_waitSignal`

- `CanvasGroup m_canvasGroup`

- `Single m_originYPos`


## Properties

- `CanvasGroup canvasGroup`


## Methods

- `CanvasGroup get_canvasGroup()`

- `Void Reset()`

- `String _InitDialog(CharacterConfig)`

- `Void SkipToEnd(CharacterConfig)`

- `Void _AdjustMessageRect()`

- `IEnumerator _TryFinishText()`

- `IEnumerator Begin(CharacterConfig)`

- `Void Awake()`

- `Void <SkipToEnd>b__12_0()`

- `Void <Begin>b__15_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class PanelCharacterDialog : MonoBehaviour, IHotfixable
{
	private Single _fadeinTime; // 0x18
	private AVGTypeWriterText _text; // 0x20
	private RectTransform _messageRect; // 0x28
	private Single _messageRectBottomPadding; // 0x30
	private const Single TRY_FINISH_TIME; // 0x0
	private Boolean m_waitSignal; // 0x34
	private CanvasGroup m_canvasGroup; // 0x38
	private Single m_originYPos; // 0x40
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0__InitDialog; // 0x10
	private static DelegateBridge __Hotfix0_SkipToEnd; // 0x18
	private static DelegateBridge __Hotfix0__AdjustMessageRect; // 0x20
	private static DelegateBridge __Hotfix0__TryFinishText; // 0x28
	private static DelegateBridge __Hotfix0_Begin; // 0x30
	private static DelegateBridge __Hotfix0_Awake; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private CanvasGroup canvasGroup { get; }

	// RVA: 0x35ca338 VA: 0x7595be2338
	private CanvasGroup get_canvasGroup() { }
	// RVA: 0x35ca410 VA: 0x7595be2410
	public Void Reset() { }
	// RVA: 0x35ca49c VA: 0x7595be249c
	private String _InitDialog(CharacterConfig config) { }
	// RVA: 0x35ca7ac VA: 0x7595be27ac
	public Void SkipToEnd(CharacterConfig config) { }
	// RVA: 0x35ca9f4 VA: 0x7595be29f4
	private Void _AdjustMessageRect() { }
	// RVA: 0x35ca948 VA: 0x7595be2948
	private IEnumerator _TryFinishText() { }
	// RVA: 0x35cab2c VA: 0x7595be2b2c
	public IEnumerator Begin(CharacterConfig charConfig) { }
	// RVA: 0x35cac50 VA: 0x7595be2c50
	private Void Awake() { }
	// RVA: 0x35cad08 VA: 0x7595be2d08
	public Void .ctor() { }
	// RVA: 0x35cad8c VA: 0x7595be2d8c
	private Void <SkipToEnd>b__12_0() { }
	// RVA: 0x35cad98 VA: 0x7595be2d98
	private Void <Begin>b__15_0() { }
}
```