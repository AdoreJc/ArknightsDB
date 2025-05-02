# SandboxV2RacerTempInventoryTopView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _backRt`

- `Text _textName`

- `Text _textTempBagName`

- `Text _textTempRacerCount`

- `Text _textTempBagCapacity`

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
public class SandboxV2RacerTempInventoryTopView : DataBinder`1, IHotfixable
{
	private RectTransform _backRt; // 0x20
	private Text _textName; // 0x28
	private Text _textTempBagName; // 0x30
	private Text _textTempRacerCount; // 0x38
	private Text _textTempBagCapacity; // 0x40
	private Text _textBagName; // 0x48
	private Text _textRacerCount; // 0x50
	private Text _textBagCapacity; // 0x58
	private Boolean m_hasInited; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25f639c VA: 0x7594c0e39c
	public override Void OnValueChanged(SandboxV2RacerTempInventoryProperty property) { }
	// RVA: 0x25f6658 VA: 0x7594c0e658
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x25f6548 VA: 0x7594c0e548
	private Void _InitIfNot() { }
	// RVA: 0x25f66fc VA: 0x7594c0e6fc
	public Void .ctor() { }
}
```