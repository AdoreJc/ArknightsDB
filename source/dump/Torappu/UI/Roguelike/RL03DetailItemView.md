# RL03DetailItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `SimpleLayoutContent _itemContent`

- `GameObject _panel`

- `Text _detailText`

- `SimpleLayoutContent _orContent`

- `CanvasGroup _itemViewCanvasGroup`

- `GameObject _morePart`

- `HorizontalLayoutGroup _layout`

- `Int32 _spacingWithOr`

- `Int32 _spacingWithoutOr`

- `FadeSwitchTween m_panelFade`

- `ConstAdapter m_constAdapter`

- `Adapter m_adapter`

- `String m_adapterCacheId`


## Methods

- `Void _InitAdapter(String, RoguelikeRewardStyle)`

- `Void OnRender(Options)`

- `Void HidePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RL03DetailItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemContent; // 0x18
	private GameObject _panel; // 0x20
	private Text _detailText; // 0x28
	private SimpleLayoutContent _orContent; // 0x30
	private CanvasGroup _itemViewCanvasGroup; // 0x38
	private GameObject _morePart; // 0x40
	private HorizontalLayoutGroup _layout; // 0x48
	private Int32 _spacingWithOr; // 0x50
	private Int32 _spacingWithoutOr; // 0x54
	private FadeSwitchTween m_panelFade; // 0x58
	private ConstAdapter m_constAdapter; // 0x60
	private Adapter m_adapter; // 0x68
	private String m_adapterCacheId; // 0x70
	private static DelegateBridge __Hotfix0__InitAdapter; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_HidePanel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a08228 VA: 0x7595020228
	private Void _InitAdapter(String topicId, RoguelikeRewardStyle style) { }
	// RVA: 0x2a0857c VA: 0x759502057c
	public Void OnRender(Options options) { }
	// RVA: 0x2a08750 VA: 0x7595020750
	public Void HidePanel() { }
	// RVA: 0x2a08824 VA: 0x7595020824
	public Void .ctor() { }
}
```