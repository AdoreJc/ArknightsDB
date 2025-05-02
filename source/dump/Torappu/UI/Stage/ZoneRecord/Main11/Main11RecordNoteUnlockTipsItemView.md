# Main11RecordNoteUnlockTipsItemView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


## Fields

- `Text _unlockTips`

- `String _styleRecordNameCol`

- `String _styleTipsCol`


## Methods

- `Void Render(ZoneRecordViewModel)`

- `Void _UpdateDiffIcons(ZoneRecordDiffStatus)`

- `Void _AddDiffStatusToList(RecordRewardStageDiff, ref)`

- `Void _RenderDiffIcons(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11RecordNoteUnlockTipsItemView : MonoBehaviour, IHotfixable
{
	private Text _unlockTips; // 0x18
	private StageDiffImage[] _diffIconList; // 0x20
	private String _styleRecordNameCol; // 0x28
	private String _styleTipsCol; // 0x30
	private const String TIPS_STYLE; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateDiffIcons; // 0x8
	private static DelegateBridge __Hotfix0__AddDiffStatusToList; // 0x10
	private static DelegateBridge __Hotfix0__RenderDiffIcons; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2fd8d30 VA: 0x75955f0d30
	public Void Render(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd8e68 VA: 0x75955f0e68
	private Void _UpdateDiffIcons(ZoneRecordDiffStatus diffStatus) { }
	// RVA: 0x2fd8f88 VA: 0x75955f0f88
	private Void _AddDiffStatusToList(RecordRewardStageDiff status, ref List`1 diffList) { }
	// RVA: 0x2fd90dc VA: 0x75955f10dc
	private Void _RenderDiffIcons(List`1 diffStatusList) { }
	// RVA: 0x2fd9274 VA: 0x75955f1274
	public Void .ctor() { }
}
```