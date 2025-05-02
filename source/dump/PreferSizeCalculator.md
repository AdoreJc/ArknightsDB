# PreferSizeCalculator

**Namespace:** ` `


## Fields

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_textSettings`

- `Single m_textPadding`

- `Single m_avatarSize`

- `RoguelikeChatDialogComp m_view`


## Methods

- `Single CalcSize(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PreferSizeCalculator
{
	private TextGenerator m_textGenerator; // 0x10
	private TextGenerationSettings m_textSettings; // 0x18
	private Single m_textPadding; // 0x78
	private Single m_avatarSize; // 0x7c
	private RoguelikeChatDialogComp m_view; // 0x80


	// RVA: 0x2bb7bc8 VA: 0x75951cfbc8
	public Void .ctor(RoguelikeChatDialogComp view) { }
	// RVA: 0x2bb80a0 VA: 0x75951d00a0
	public Single CalcSize(String text) { }
}
```