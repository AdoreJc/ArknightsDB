# Main11RecordNoteDotItemView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


## Fields

- `Text _stageId`

- `Color _txtCol`

- `CanvasGroup _canvasSelect`

- `String m_cachedRecordId`

- `Boolean m_isInited`

- `FadeSwitchTween m_selectTween`


## Methods

- `Void Render(ZoneRecordViewModel, Boolean)`

- `Void _InitIfNot(ZoneRecordViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11RecordNoteDotItemView : MonoBehaviour, IHotfixable
{
	private Text _stageId; // 0x18
	private Color _txtCol; // 0x20
	private CanvasGroup _canvasSelect; // 0x30
	private String m_cachedRecordId; // 0x38
	private Boolean m_isInited; // 0x40
	private FadeSwitchTween m_selectTween; // 0x48
	private const Single ALPHA_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2fd8a9c VA: 0x75955f0a9c
	public Void Render(ZoneRecordViewModel viewModel, Boolean selected) { }
	// RVA: 0x2fd8b70 VA: 0x75955f0b70
	private Void _InitIfNot(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd8cc0 VA: 0x75955f0cc0
	public Void .ctor() { }
}
```