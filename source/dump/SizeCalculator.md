# SizeCalculator

**Namespace:** ` `


## Fields

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_nameSettings`

- `TextGenerationSettings m_msgSettings`

- `DialogPlaybackTextView m_prefab`


## Methods

- `Single CalcSize(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SizeCalculator : IHotfixable
{
	private TextGenerator m_textGenerator; // 0x10
	private TextGenerationSettings m_nameSettings; // 0x18
	private TextGenerationSettings m_msgSettings; // 0x78
	private DialogPlaybackTextView m_prefab; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CalcSize; // 0x8


	// RVA: 0x1c45f04 VA: 0x759425df04
	public Void .ctor(DialogPlaybackTextView prefab) { }
	// RVA: 0x1c4647c VA: 0x759425e47c
	public Single CalcSize(String name, String msg) { }
}
```