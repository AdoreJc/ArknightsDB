# Rl01OuterBuffListItem

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `CanvasGroup _alphaHandler`

- `Text _textBuffName`

- `Text _textBuffValue`

- `CanvasGroup _canvasBkgLight`

- `Int32 m_cachedDisplayValue`

- `Sequence m_sequence`


## Properties

- `CanvasGroup alphaHandler`


## Methods

- `CanvasGroup get_alphaHandler()`

- `Void Render(RoguelikeTopicOuterBuffListItemModel, Boolean)`

- `Void _ShowBuffUpgradeEffect()`

- `Void <_ShowBuffUpgradeEffect>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffListItem : MonoBehaviour, IHotfixable
{
	public const Single FADE_IN_DURATION; // 0x0
	public const Single WAIT_DURATION; // 0x0
	public const Single FADE_OUT_DURATION; // 0x0
	private CanvasGroup _alphaHandler; // 0x18
	private Text _textBuffName; // 0x20
	private Text _textBuffValue; // 0x28
	private CanvasGroup _canvasBkgLight; // 0x30
	private Int32 m_cachedDisplayValue; // 0x38
	private Sequence m_sequence; // 0x40
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__ShowBuffUpgradeEffect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public CanvasGroup alphaHandler { get; }

	// RVA: 0x26ca7c8 VA: 0x7594ce27c8
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x26cacf4 VA: 0x7594ce2cf4
	public Void Render(RoguelikeTopicOuterBuffListItemModel model, Boolean isInit) { }
	// RVA: 0x26cae08 VA: 0x7594ce2e08
	private Void _ShowBuffUpgradeEffect() { }
	// RVA: 0x26cb034 VA: 0x7594ce3034
	public Void .ctor() { }
	// RVA: 0x26cb0a4 VA: 0x7594ce30a4
	private Void <_ShowBuffUpgradeEffect>b__12_0() { }
}
```