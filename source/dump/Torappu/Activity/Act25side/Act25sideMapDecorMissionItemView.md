# Act25sideMapDecorMissionItemView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Text _areaName`

- `Text _missionContent`

- `Text _missionTotalProgress`

- `Text _missionCurrProgress`

- `GameObject _panelComplete`

- `Color _colorNormal`

- `Color _colorComplete`


## Methods

- `Void Render(Act25sideMapDecorMissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideMapDecorMissionItemView : MonoBehaviour, IHotfixable
{
	private const String MISSION_PROGRESS_FORMAT; // 0x0
	private Text _areaName; // 0x18
	private Text _missionContent; // 0x20
	private Text _missionTotalProgress; // 0x28
	private Text _missionCurrProgress; // 0x30
	private GameObject _panelComplete; // 0x38
	private Color _colorNormal; // 0x40
	private Color _colorComplete; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3270e68 VA: 0x7595888e68
	public Void Render(Act25sideMapDecorMissionViewModel missionViewModel) { }
	// RVA: 0x3271080 VA: 0x7595889080
	public Void .ctor() { }
}
```