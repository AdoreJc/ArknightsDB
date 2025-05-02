# DiceResultItemView

**Namespace:** ` `


## Fields

- `Text _textCount`

- `UIAtlasImage _resultImage`

- `RL02ReportDiceView m_closure`


## Methods

- `Void Init(RL02ReportDiceView)`

- `Void Render(DiceResultClass, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DiceResultItemView : IHotfixable
{
	private Text _textCount; // 0x10
	private UIAtlasImage _resultImage; // 0x18
	private RL02ReportDiceView m_closure; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b62f88 VA: 0x759517af88
	public Void Init(RL02ReportDiceView closure) { }
	// RVA: 0x2b63444 VA: 0x759517b444
	public Void Render(DiceResultClass resultClass, Int32 count) { }
	// RVA: 0x2b637a0 VA: 0x759517b7a0
	public Void .ctor() { }
}
```