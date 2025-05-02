# FifthAnnivExploreTargetInfoView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _stageNumText`

- `Text _stageNameText`

- `Text _apNumText`

- `Config _config`

- `SimpleLayoutContent _layoutContent`

- `GameObject _blankHotspotObj`

- `RectTransform _container`

- `CanvasGroup _canvasGroup`

- `Vector2 _hidePos`

- `Vector2 _showPos`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `FadeTranslationSwitchTween m_fadeTween`

- `Action <onBlankClick>k__BackingField`


## Properties

- `Action onBlankClick`


## Methods

- `Void set_onBlankClick(Action)`

- `Action get_onBlankClick()`

- `Void _InitIfNot()`

- `Void OnBlankClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreTargetInfoView : DataBinder`1, IHotfixable
{
	private Text _stageNumText; // 0x20
	private Text _stageNameText; // 0x28
	private Text _apNumText; // 0x30
	private Config _config; // 0x38
	private SimpleLayoutContent _layoutContent; // 0x78
	private GameObject _blankHotspotObj; // 0x80
	private RectTransform _container; // 0x88
	private CanvasGroup _canvasGroup; // 0x90
	private Vector2 _hidePos; // 0x98
	private Vector2 _showPos; // 0xa0
	private Boolean m_isInited; // 0xa8
	private Adapter m_adapter; // 0xb0
	private List`1 m_cachedItemViewModels; // 0xb8
	private FadeTranslationSwitchTween m_fadeTween; // 0xc0
	private Action <onBlankClick>k__BackingField; // 0xc8
	private static DelegateBridge __Hotfix0_set_onBlankClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onBlankClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnBlankClick; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action onBlankClick { get; set; }

	// RVA: 0x293032c VA: 0x7594f4832c
	public Void set_onBlankClick(Action value) { }
	// RVA: 0x29303b0 VA: 0x7594f483b0
	private Action get_onBlankClick() { }
	// RVA: 0x2930418 VA: 0x7594f48418
	private Void _InitIfNot() { }
	// RVA: 0x2930648 VA: 0x7594f48648
	public Void OnBlankClick() { }
	// RVA: 0x29306e4 VA: 0x7594f486e4
	public override Void OnValueChanged(FifthAnnivExploreTargetInfoProperty property) { }
	// RVA: 0x293082c VA: 0x7594f4882c
	public Void .ctor() { }
}
```