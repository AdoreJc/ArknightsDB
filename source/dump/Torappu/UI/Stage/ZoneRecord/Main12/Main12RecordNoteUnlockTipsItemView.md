# Main12RecordNoteUnlockTipsItemView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `Text _unlockTips`

- `String _styleRecordNameCol`

- `String _styleTipsCol`

- `SimpleLayoutContent _missionContent`

- `Boolean m_isInited`

- `MissionAdapter m_adapter`


## Methods

- `Void Render(ZoneRecordViewModel)`

- `Void _UpdateDiffIcons(ZoneRecordDiffStatus, ListDict`2)`

- `Void _AddDiffStatusToList(RecordRewardStageDiff, ref)`

- `Void _RenderDiffIcons(List`1, ListDict`2)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12RecordNoteUnlockTipsItemView : MonoBehaviour, IHotfixable
{
	private Text _unlockTips; // 0x18
	private StageDiffImage[] _diffIconList; // 0x20
	private String _styleRecordNameCol; // 0x28
	private String _styleTipsCol; // 0x30
	private SimpleLayoutContent _missionContent; // 0x38
	private const String TIPS_STYLE; // 0x0
	private Boolean m_isInited; // 0x40
	private MissionAdapter m_adapter; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateDiffIcons; // 0x8
	private static DelegateBridge __Hotfix0__AddDiffStatusToList; // 0x10
	private static DelegateBridge __Hotfix0__RenderDiffIcons; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fcf500 VA: 0x75955e7500
	public Void Render(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd07b0 VA: 0x75955e87b0
	private Void _UpdateDiffIcons(ZoneRecordDiffStatus diffStatus, ListDict`2 diffMap) { }
	// RVA: 0x2fd08e4 VA: 0x75955e88e4
	private Void _AddDiffStatusToList(RecordRewardStageDiff status, ref List`1 diffList) { }
	// RVA: 0x2fd0a38 VA: 0x75955e8a38
	private Void _RenderDiffIcons(List`1 diffStatusList, ListDict`2 diffMap) { }
	// RVA: 0x2fd0694 VA: 0x75955e8694
	private Void _InitIfNot() { }
	// RVA: 0x2fd0ca4 VA: 0x75955e8ca4
	public Void .ctor() { }
}
```