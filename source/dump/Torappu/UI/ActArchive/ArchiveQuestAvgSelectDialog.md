# ArchiveQuestAvgSelectDialog

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `RectTransform _rectBack`

- `UIRenderTextureImage _bkgBlur`

- `Text _textQuestType`

- `Text _textQuestName`

- `Text _textAvgName1`

- `Text _textAvgName2`

- `TwoStateToggle _toggleIcon1`

- `TwoStateToggle _toggleIcon2`

- `Int32 m_index`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnClickStartIndex(Int32)`

- `Void OnBackClick()`

- `Void _OnSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestAvgSelectDialog : UICustomDialog`1
{
	public const Int32 NOT_SELECT_COUNT; // 0x0
	private RectTransform _rectBack; // 0x40
	private UIRenderTextureImage _bkgBlur; // 0x48
	private Text _textQuestType; // 0x50
	private Text _textQuestName; // 0x58
	private Text _textAvgName1; // 0x60
	private Text _textAvgName2; // 0x68
	private TwoStateToggle _toggleIcon1; // 0x70
	private TwoStateToggle _toggleIcon2; // 0x78
	private Action`1 m_onSelect; // 0x80
	private Int32 m_index; // 0x88
	private Boolean m_hasInited; // 0x8c
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClickStartIndex; // 0x18
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x20
	private static DelegateBridge __Hotfix0__OnSelect; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x306dc44 VA: 0x7595685c44
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x306dcac VA: 0x7595685cac
	protected override Void OnRender(Options input) { }
	// RVA: 0x306de50 VA: 0x7595685e50
	private Void _InitIfNot() { }
	// RVA: 0x306df58 VA: 0x7595685f58
	public Void EventOnClickStartIndex(Int32 index) { }
	// RVA: 0x306e05c VA: 0x759568605c
	public Void OnBackClick() { }
	// RVA: 0x306e0e0 VA: 0x75956860e0
	private Void _OnSelect() { }
	// RVA: 0x306e168 VA: 0x7595686168
	public Void .ctor() { }
}
```