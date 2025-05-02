# HomeCheckInProgressGPDetailView

**Namespace:** `Torappu.UI.Home`


## Fields

- `SimpleLayoutContent _content`

- `Text _textTitle`

- `Text _textRemainTime`

- `ScrollRect _scrollRect`

- `UIFadeFloatPanel _floatPanel`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`

- `ProgressCheckInViewModel m_cachedModel`


## Methods

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInProgressGPDetailView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private Text _textTitle; // 0x28
	private Text _textRemainTime; // 0x30
	private ScrollRect _scrollRect; // 0x38
	private UIFadeFloatPanel _floatPanel; // 0x40
	private Boolean m_hasInited; // 0x48
	private Adapter m_adapter; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private ProgressCheckInViewModel m_cachedModel; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2830e38 VA: 0x7594e48e38
	public override Void OnValueChanged(HomeCheckInProperty property) { }
	// RVA: 0x28310f8 VA: 0x7594e490f8
	public Void OnClick() { }
	// RVA: 0x2830f94 VA: 0x7594e48f94
	private Void _InitIfNot() { }
	// RVA: 0x2831230 VA: 0x7594e49230
	public Void .ctor() { }
}
```