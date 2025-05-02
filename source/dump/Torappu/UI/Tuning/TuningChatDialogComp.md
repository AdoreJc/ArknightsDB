# TuningChatDialogComp

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Text _content`

- `AVGTypeWriterText _typeWriter`

- `Color _askColor`

- `Color _answerColor`

- `Color _defaultColor`

- `Single _padding`

- `String m_cachedContent`

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_textSettings`


## Methods

- `Void _Render(String)`

- `Single _GetPreferedHeight(Options)`

- `String _GetContent(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatDialogComp : TuningChatFadeCompBase
{
	private Text _content; // 0x30
	private AVGTypeWriterText _typeWriter; // 0x38
	private Color _askColor; // 0x40
	private Color _answerColor; // 0x50
	private Color _defaultColor; // 0x60
	private Single _padding; // 0x70
	private String m_cachedContent; // 0x78
	private TextGenerator m_textGenerator; // 0x80
	private TextGenerationSettings m_textSettings; // 0x88
	private static DelegateBridge __Hotfix0__Render; // 0x0
	private static DelegateBridge __Hotfix0__GetPreferedHeight; // 0x8
	private static DelegateBridge __Hotfix0__GetContent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2312128 VA: 0x759492a128
	private Void _Render(String style) { }
	// RVA: 0x231223c VA: 0x759492a23c
	private Single _GetPreferedHeight(Options options) { }
	// RVA: 0x2312588 VA: 0x759492a588
	private String _GetContent(String content, String style) { }
	// RVA: 0x23126d8 VA: 0x759492a6d8
	public Void .ctor() { }
}
```