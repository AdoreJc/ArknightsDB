# AVGTypeWriterText

**Namespace:** `Torappu.AVG`


## Fields

- `Single _typeWriterDelay`

- `Boolean _onMiddle`

- `Single _maxWidth`

- `Boolean _doNotParseSpecialChars`

- `Text m_text`

- `String m_message`

- `Action m_onTypeEnd`

- `Double m_typerTime`

- `Boolean m_typing`

- `Boolean m_onMiddle`

- `StringBuilder m_sb`

- `RectTransform m_rect`

- `ContentSizeFitter m_sizeFitter`

- `Single m_typeWriterDelay`

- `Int32 m_cachedMultilineTextLenth`

- `Boolean m_isMultiline`


## Properties

- `Boolean isTyping`

- `String message`

- `Int32 messageLength`

- `Text text`

- `Single typeWriterDelay`

- `Single originDelay`


## Methods

- `Boolean get_isTyping()`

- `String get_message()`

- `Int32 get_messageLength()`

- `Text get_text()`

- `Single get_typeWriterDelay()`

- `Void set_typeWriterDelay(Single)`

- `Single get_originDelay()`

- `Void OnReset()`

- `Void BeginText(String, Action)`

- `Void AppendText(String, Action)`

- `Void TryFinish()`

- `Void TryCutMessage(Int32)`

- `Void _FinishTyping()`

- `Void _ClearMessage()`

- `Void _UpdateMaxWidth()`

- `Void Awake()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTypeWriterText : MonoBehaviour, IHotfixable
{
	private Single _typeWriterDelay; // 0x18
	private Boolean _onMiddle; // 0x1c
	private Single _maxWidth; // 0x20
	private Boolean _doNotParseSpecialChars; // 0x24
	private Text m_text; // 0x28
	private String m_message; // 0x30
	private Action m_onTypeEnd; // 0x38
	private Double m_typerTime; // 0x40
	private Boolean m_typing; // 0x48
	private Boolean m_onMiddle; // 0x49
	private StringBuilder m_sb; // 0x50
	private RectTransform m_rect; // 0x58
	private ContentSizeFitter m_sizeFitter; // 0x60
	private Single m_typeWriterDelay; // 0x68
	private IEnumerator`1 m_textMessageIterator; // 0x70
	private Int32 m_cachedMultilineTextLenth; // 0x78
	private Boolean m_isMultiline; // 0x7c
	private static DelegateBridge __Hotfix0_get_isTyping; // 0x0
	private static DelegateBridge __Hotfix0_get_message; // 0x8
	private static DelegateBridge __Hotfix0_get_messageLength; // 0x10
	private static DelegateBridge __Hotfix0_get_text; // 0x18
	private static DelegateBridge __Hotfix0_get_typeWriterDelay; // 0x20
	private static DelegateBridge __Hotfix0_set_typeWriterDelay; // 0x28
	private static DelegateBridge __Hotfix0_get_originDelay; // 0x30
	private static DelegateBridge __Hotfix0_OnReset; // 0x38
	private static DelegateBridge __Hotfix0_BeginText; // 0x40
	private static DelegateBridge __Hotfix0_AppendText; // 0x48
	private static DelegateBridge __Hotfix0_TryFinish; // 0x50
	private static DelegateBridge __Hotfix0_TryCutMessage; // 0x58
	private static DelegateBridge __Hotfix0__FinishTyping; // 0x60
	private static DelegateBridge __Hotfix0__ClearMessage; // 0x68
	private static DelegateBridge __Hotfix0__GetTextMessageGenerator; // 0x70
	private static DelegateBridge __Hotfix0__GetMultilineTextMessageGenerator; // 0x78
	private static DelegateBridge __Hotfix0__UpdateMaxWidth; // 0x80
	private static DelegateBridge __Hotfix0__AppendHiddenString; // 0x88
	private static DelegateBridge __Hotfix0_Awake; // 0x90
	private static DelegateBridge __Hotfix0_Update; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public Boolean isTyping { get; }
	public String message { get; }
	public Int32 messageLength { get; }
	protected Text text { get; }
	public Single typeWriterDelay { get; set; }
	public Single originDelay { get; }

	// RVA: 0x3eab128 VA: 0x75964c3128
	public Boolean get_isTyping() { }
	// RVA: 0x3eae1b8 VA: 0x75964c61b8
	public String get_message() { }
	// RVA: 0x3eabd98 VA: 0x75964c3d98
	public Int32 get_messageLength() { }
	// RVA: 0x3eae220 VA: 0x75964c6220
	protected Text get_text() { }
	// RVA: 0x3eae2f8 VA: 0x75964c62f8
	public Single get_typeWriterDelay() { }
	// RVA: 0x3eab850 VA: 0x75964c3850
	public Void set_typeWriterDelay(Single value) { }
	// RVA: 0x3eab7e8 VA: 0x75964c37e8
	public Single get_originDelay() { }
	// RVA: 0x3eabe24 VA: 0x75964c3e24
	public Void OnReset() { }
	// RVA: 0x3eaba78 VA: 0x75964c3a78
	public Void BeginText(String message, Action onTypeEnd) { }
	// RVA: 0x3eab8cc VA: 0x75964c38cc
	public Void AppendText(String message, Action onTypeEnd) { }
	// RVA: 0x3eab280 VA: 0x75964c3280
	public Void TryFinish() { }
	// RVA: 0x3eae8d0 VA: 0x75964c68d0
	public Void TryCutMessage(Int32 length) { }
	// RVA: 0x3eae720 VA: 0x75964c6720
	private Void _FinishTyping() { }
	// RVA: 0x3eae360 VA: 0x75964c6360
	private Void _ClearMessage() { }
	// RVA: 0x3eae43c VA: 0x75964c643c
	private IEnumerable`1 _GetTextMessageGenerator() { }
	// RVA: 0x3eae664 VA: 0x75964c6664
	private IEnumerable`1 _GetMultilineTextMessageGenerator() { }
	// RVA: 0x3eae984 VA: 0x75964c6984
	private Void _UpdateMaxWidth() { }
	// RVA: 0x3eae4f8 VA: 0x75964c64f8
	private static Void _AppendHiddenString(StringBuilder sb, String hiddenString) { }
	// RVA: 0x3eaead8 VA: 0x75964c6ad8
	private Void Awake() { }
	// RVA: 0x3eaebac VA: 0x75964c6bac
	private Void Update() { }
	// RVA: 0x3eaedd4 VA: 0x75964c6dd4
	public Void .ctor() { }
}
```