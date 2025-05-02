# RelicPart

**Namespace:** ` `


## Fields

- `Image _imageIcon`

- `Text _textName`

- `Text _textUsage`

- `GameObject _iconUsed`

- `GameObject _layerPart`

- `Text _textLayer`

- `String m_cachedRelicId`

- `RoguelikeRelicViewModel m_cachedRelicModel`


## Methods

- `Void Render(RoguelikeRelicViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RelicPart : IHotfixable
{
	private Image _imageIcon; // 0x10
	private Text _textName; // 0x18
	private Text _textUsage; // 0x20
	private GameObject _iconUsed; // 0x28
	private GameObject _layerPart; // 0x30
	private Text _textLayer; // 0x38
	private String m_cachedRelicId; // 0x40
	private RoguelikeRelicViewModel m_cachedRelicModel; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2a7522c VA: 0x759508d22c
	public Void Render(RoguelikeRelicViewModel viewModel) { }
	// RVA: 0x2a74940 VA: 0x759508c940
	public Void EventOnClicked() { }
	// RVA: 0x2a756b4 VA: 0x759508d6b4
	public Void .ctor() { }
}
```