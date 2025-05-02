# SandboxV2DungeonReadArchiveView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonReadArchiveCurDayItemView _curDayInfoItemView`

- `Text _txtReadArchiveTips`

- `TwoStateToggle _backExitToggle`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `String m_archiveTipsFormat`

- `SandboxV2DungeonReadArchiveItemListView _targetListView`

- `Boolean m_panelInited`


## Methods

- `Void _InitIfNot()`

- `Void OnBgClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonReadArchiveView : DataBinder`1
{
	private SandboxV2DungeonReadArchiveCurDayItemView _curDayInfoItemView; // 0x20
	private Text _txtReadArchiveTips; // 0x28
	private TwoStateToggle _backExitToggle; // 0x30
	private List`1 _archiveItemListViews; // 0x38
	private Boolean m_isInited; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private String m_archiveTipsFormat; // 0x58
	private SandboxV2DungeonReadArchiveItemListView _targetListView; // 0x60
	private Boolean m_panelInited; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnBgClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x252d620 VA: 0x7594b45620
	public override Void OnValueChanged(SandboxV2DungeonReadArchiveProp property) { }
	// RVA: 0x252d950 VA: 0x7594b45950
	private Void _InitIfNot() { }
	// RVA: 0x252d9c4 VA: 0x7594b459c4
	public Void OnBgClick() { }
	// RVA: 0x252da68 VA: 0x7594b45a68
	public Void .ctor() { }
}
```