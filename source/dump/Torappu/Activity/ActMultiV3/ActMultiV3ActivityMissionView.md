# ActMultiV3ActivityMissionView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3ActivityMissionAdapter _missionAdapter`

- `Text _completedTaskText`

- `Text _totalTaskText`

- `TwoStateToggle _claimAllToggle`

- `UIStateFinder m_finder`

- `Int32 m_cachedLoadSeqNum`


## Methods

- `Void OnClickClaimAllBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ActivityMissionView : ActMultiV3TabContentAbstractView
{
	private ActMultiV3ActivityMissionAdapter _missionAdapter; // 0x18
	private Text _completedTaskText; // 0x20
	private Text _totalTaskText; // 0x28
	private TwoStateToggle _claimAllToggle; // 0x30
	private UIStateFinder m_finder; // 0x38
	private Int32 m_cachedLoadSeqNum; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickClaimAllBtn; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x311aed8 VA: 0x7595732ed8
	public override Void Render(ActMultiV3ManualViewModel viewModel) { }
	// RVA: 0x311b038 VA: 0x7595733038
	public Void OnClickClaimAllBtn() { }
	// RVA: 0x311b0dc VA: 0x75957330dc
	public Void .ctor() { }
}
```