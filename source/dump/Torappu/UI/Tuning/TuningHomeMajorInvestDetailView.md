# TuningHomeMajorInvestDetailView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Text _textProgressCurr`

- `Text _textProgressTarget`

- `Text _textDesc1`

- `Text _textDesc2`

- `Text _textDesc3`

- `Text _textDesc4`

- `SimpleLayoutContent _content`

- `RectTransform _rectBack`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `Adapter m_adapter`


## Methods

- `Void EventOnCloseBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeMajorInvestDetailView : DataBinder`1, IHotfixable
{
	private Text _textProgressCurr; // 0x20
	private Text _textProgressTarget; // 0x28
	private Text _textDesc1; // 0x30
	private Text _textDesc2; // 0x38
	private Text _textDesc3; // 0x40
	private Text _textDesc4; // 0x48
	private SimpleLayoutContent _content; // 0x50
	private RectTransform _rectBack; // 0x58
	private Boolean m_hasInited; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private List`1 m_cachedModelList; // 0x78
	private Adapter m_adapter; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCloseBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x232d678 VA: 0x7594945678
	public override Void OnValueChanged(TuningHomeMajorInvestDetailProperty property) { }
	// RVA: 0x232d96c VA: 0x759494596c
	public Void EventOnCloseBtnClicked() { }
	// RVA: 0x232d80c VA: 0x759494580c
	private Void _InitIfNot() { }
	// RVA: 0x232daa4 VA: 0x7594945aa4
	public Void .ctor() { }
}
```