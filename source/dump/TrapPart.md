# TrapPart

**Namespace:** ` `


## Fields

- `Image _imageIcon`

- `Text _textName`

- `Text _textUsage`

- `String m_cachedTrapId`

- `RoguelikeTrapViewModel m_cachedTrapModel`


## Methods

- `Void Render(RoguelikeTrapViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TrapPart : IHotfixable
{
	private Image _imageIcon; // 0x10
	private Text _textName; // 0x18
	private Text _textUsage; // 0x20
	private String m_cachedTrapId; // 0x28
	private RoguelikeTrapViewModel m_cachedTrapModel; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2a7506c VA: 0x759508d06c
	public Void Render(RoguelikeTrapViewModel viewModel) { }
	// RVA: 0x2a74b5c VA: 0x759508cb5c
	public Void EventOnClicked() { }
	// RVA: 0x2a75724 VA: 0x759508d724
	public Void .ctor() { }
}
```