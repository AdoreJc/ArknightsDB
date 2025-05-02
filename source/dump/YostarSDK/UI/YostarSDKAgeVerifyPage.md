# YostarSDKAgeVerifyPage

**Namespace:** `YostarSDK.UI`


## Fields

- `CanvasGroup _contentPart`

- `Button _btnAgree`

- `Text _btnAgree_text`

- `Text _btnAgree_text_g`

- `Button _btnCancel`

- `Text _btnCancel_text`

- `Button _btnCheckBox`

- `Button _btnCheckBox_g`

- `Text _btnCheckBox_text`

- `Text _btnCheckBox_text_g`

- `Text _Notice_text`

- `SimpleLayoutContent _textContainer`

- `ContentAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnAgreeClicked()`

- `Void EventOnCancelClicked()`

- `Void EventOnBlankClicked()`

- `Void EventOnAcceptClicked()`

- `Void EventOnNagativeClicker()`

- `Void Open(UIManager)`

- `Void _ShowTheAgeAgreement()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class YostarSDKAgeVerifyPage : UIState
{
	private CanvasGroup _contentPart; // 0x50
	private Button _btnAgree; // 0x58
	private Text _btnAgree_text; // 0x60
	private Text _btnAgree_text_g; // 0x68
	private Button _btnCancel; // 0x70
	private Text _btnCancel_text; // 0x78
	private Button _btnCheckBox; // 0x80
	private Button _btnCheckBox_g; // 0x88
	private Text _btnCheckBox_text; // 0x90
	private Text _btnCheckBox_text_g; // 0x98
	private Text _Notice_text; // 0xa0
	private const Int32 MAX_TEXT_STRLEN; // 0x0
	private const Int32 MIN_TEXT_STRLEN; // 0x0
	private SimpleLayoutContent _textContainer; // 0xa8
	private List`1 m_content; // 0xb0
	private ContentAdapter m_adapter; // 0xb8
	private static String Underagreement; // 0x0
	private Boolean m_isInited; // 0xc0

	public override PayState myState { get; }

	// RVA: 0x1b4c9dc VA: 0x75941649dc
	private static Void _DealWithTitleStyle(Text text) { }
	// RVA: 0x1b4ca0c VA: 0x7594164a0c
	private static Void _DealWithContentStyle(Text text) { }
	// RVA: 0x1b4ca3c VA: 0x7594164a3c
	public static Void init(String underagreement) { }
	// RVA: 0x1b4caa4 VA: 0x7594164aa4
	public override PayState get_myState() { }
	// RVA: 0x1b4caac VA: 0x7594164aac
	private Void _InitIfNot() { }
	// RVA: 0x1b4cb48 VA: 0x7594164b48
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b4cd10 VA: 0x7594164d10
	public Void EventOnAgreeClicked() { }
	// RVA: 0x1b4cd74 VA: 0x7594164d74
	public Void EventOnCancelClicked() { }
	// RVA: 0x1b4ce7c VA: 0x7594164e7c
	public Void EventOnBlankClicked() { }
	// RVA: 0x1b4cf84 VA: 0x7594164f84
	public Void EventOnAcceptClicked() { }
	// RVA: 0x1b4cff4 VA: 0x7594164ff4
	public Void EventOnNagativeClicker() { }
	// RVA: 0x1b4d064 VA: 0x7594165064
	public Void Open(UIManager uiMgr) { }
	// RVA: 0x1b4cc84 VA: 0x7594164c84
	private Void _ShowTheAgeAgreement() { }
	// RVA: 0x1b4d068 VA: 0x7594165068
	private static String _ExtractAgreementContent(String ret) { }
	// RVA: 0x1b4d1e8 VA: 0x75941651e8
	public Void .ctor() { }
	// RVA: 0x1b4d1f0 VA: 0x75941651f0
	private static Void .cctor() { }
}
```