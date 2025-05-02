# SiracusaChatDecisionComp

**Namespace:** `Torappu.UI.SiracusaMap.Chat`


## Fields

- `Single _textPadding`

- `Single _transTime`

- `VerticalLayoutGroup _innerLayout`

- `SiracusaChatDecisionItem _itemPrefab`

- `SimpleLayoutContent _content`

- `Text _decisionResult`

- `CanvasGroup _decisionGroup`

- `CanvasGroup _resultGroup`

- `Boolean m_isInited`

- `SiracusaDecisionAdapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void _RenderForDecisions(OptionRenderOptions[])`

- `Void _RenderForDecided(String)`

- `Void _MakeDecision(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap.Chat
public class SiracusaChatDecisionComp : SiracusaChatSwitchableComp
{
	private Single _textPadding; // 0x40
	private Single _transTime; // 0x44
	private VerticalLayoutGroup _innerLayout; // 0x48
	private SiracusaChatDecisionItem _itemPrefab; // 0x50
	private SimpleLayoutContent _content; // 0x58
	private Text _decisionResult; // 0x60
	private CanvasGroup _decisionGroup; // 0x68
	private CanvasGroup _resultGroup; // 0x70
	private Boolean m_isInited; // 0x78
	private SiracusaDecisionAdapter m_adapter; // 0x80
	private OptionRenderOptions[] m_cachedDecisions; // 0x88
	private Action`1 m_onDecisionMade; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RenderForDecisions; // 0x8
	private static DelegateBridge __Hotfix0__RenderForDecided; // 0x10
	private static DelegateBridge __Hotfix0__MakeDecision; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x241dcd0 VA: 0x7594a35cd0
	private Void _InitIfNot() { }
	// RVA: 0x241de20 VA: 0x7594a35e20
	private Void _RenderForDecisions(OptionRenderOptions[] options) { }
	// RVA: 0x241df30 VA: 0x7594a35f30
	private Void _RenderForDecided(String content) { }
	// RVA: 0x241dff4 VA: 0x7594a35ff4
	private Void _MakeDecision(Int32 index) { }
	// RVA: 0x241e094 VA: 0x7594a36094
	public Void .ctor() { }
}
```