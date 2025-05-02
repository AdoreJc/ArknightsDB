# ZoneRecordNoteDetailView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneRecordDetailState _state`

- `Image _pic`

- `Text _desc`

- `Text _normalContent`

- `ScrollRect _content`

- `ScrollRect _toughContent`


## Methods

- `Void Render(RecordRewardInfo)`

- `String _TryLoadTextAssets(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordNoteDetailView : DataBinder`1, IHotfixable
{
	private ZoneRecordDetailState _state; // 0x20
	private Image _pic; // 0x28
	private Text _desc; // 0x30
	private Text _normalContent; // 0x38
	private ScrollRect _content; // 0x40
	private ScrollRect _toughContent; // 0x48
	private const Single SCROLL_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__TryLoadTextAssets; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fc8050 VA: 0x75955e0050
	public override Void OnValueChanged(ZoneRecordDetailViewPropery property) { }
	// RVA: 0x2fc81b4 VA: 0x75955e01b4
	public Void Render(RecordRewardInfo info) { }
	// RVA: 0x2fc83b4 VA: 0x75955e03b4
	private String _TryLoadTextAssets(String path) { }
	// RVA: 0x2fc858c VA: 0x75955e058c
	public Void .ctor() { }
}
```