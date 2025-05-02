# TuningHomeFragGroupView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `SimpleLayoutContent _content`

- `UICommonTrackPoint _productTrackPoint`

- `GameObject _panelArchiveBtn`

- `UICommonTrackPoint _archiveTrackPoint`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `TrackPointViewProperty m_productTrackPointProperty`

- `TrackPointViewProperty m_archiveTrackPointProperty`


## Methods

- `Void OnProductBtnClicked()`

- `Void OnArchiveBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeFragGroupView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private UICommonTrackPoint _productTrackPoint; // 0x28
	private GameObject _panelArchiveBtn; // 0x30
	private UICommonTrackPoint _archiveTrackPoint; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private Boolean m_hasInited; // 0x50
	private Adapter m_adapter; // 0x58
	private List`1 m_cacheFragList; // 0x60
	private TrackPointViewProperty m_productTrackPointProperty; // 0x68
	private TrackPointViewProperty m_archiveTrackPointProperty; // 0x70
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnProductBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnArchiveBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2325834 VA: 0x759493d834
	public override Void OnValueChanged(TuningHomeProperty property) { }
	// RVA: 0x2325a74 VA: 0x759493da74
	public Void OnProductBtnClicked() { }
	// RVA: 0x2325b18 VA: 0x759493db18
	public Void OnArchiveBtnClicked() { }
	// RVA: 0x2325964 VA: 0x759493d964
	private Void _InitIfNot() { }
	// RVA: 0x2325c50 VA: 0x759493dc50
	public Void .ctor() { }
}
```