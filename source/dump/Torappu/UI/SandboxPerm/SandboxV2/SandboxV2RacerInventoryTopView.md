# SandboxV2RacerInventoryTopView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _backRt`

- `Text _textName`

- `GameObject _panelTextBack`

- `GameObject _panelTitle`

- `Image _imgTokenIcon`

- `Text _textTokenCount`

- `Text _textBagName`

- `Text _textRacerCount`

- `Text _textBagCapacity`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnBackBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryTopView : DataBinder`1, IHotfixable
{
	private RectTransform _backRt; // 0x20
	private Text _textName; // 0x28
	private GameObject _panelTextBack; // 0x30
	private GameObject _panelTitle; // 0x38
	private Image _imgTokenIcon; // 0x40
	private Text _textTokenCount; // 0x48
	private Text _textBagName; // 0x50
	private Text _textRacerCount; // 0x58
	private Text _textBagCapacity; // 0x60
	private Boolean m_hasInited; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25e5b9c VA: 0x7594bfdb9c
	public override Void OnValueChanged(SandboxV2RacerInventoryProperty property) { }
	// RVA: 0x25e5f3c VA: 0x7594bfdf3c
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x25e5e2c VA: 0x7594bfde2c
	private Void _InitIfNot() { }
	// RVA: 0x25e5fe0 VA: 0x7594bfdfe0
	public Void .ctor() { }
}
```