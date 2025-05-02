# Main10ZoneRecordDetailView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main10`


## Fields

- `Image _pic`

- `Text _desc`

- `Text _normalContent`

- `ScrollRect _content`

- `ScrollRect _toughContent`

- `UIPage m_page`

- `Action eventOnClose`


## Methods

- `Void Init(UIPage)`

- `Void Render(RecordRewardInfo)`

- `String _TryLoadTextAssets(String)`

- `Void CloseView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main10
public class Main10ZoneRecordDetailView : DataBinder`1, IHotfixable
{
	private Image _pic; // 0x20
	private Text _desc; // 0x28
	private Text _normalContent; // 0x30
	private ScrollRect _content; // 0x38
	private ScrollRect _toughContent; // 0x40
	private const Single SCROLL_DURATION; // 0x0
	private UIPage m_page; // 0x48
	public Action eventOnClose; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__TryLoadTextAssets; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_CloseView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fdde28 VA: 0x75955f5e28
	public Void Init(UIPage page) { }
	// RVA: 0x2fdfbe4 VA: 0x75955f7be4
	public Void Render(RecordRewardInfo info) { }
	// RVA: 0x2fdfde4 VA: 0x75955f7de4
	private String _TryLoadTextAssets(String path) { }
	// RVA: 0x2fdffec VA: 0x75955f7fec
	public override Void OnValueChanged(Main10ZoneRecordViewProperty property) { }
	// RVA: 0x2fe0144 VA: 0x75955f8144
	public Void CloseView() { }
	// RVA: 0x2fe01c8 VA: 0x75955f81c8
	public Void .ctor() { }
}
```