# Act13sideDecorMissionItemView

**Namespace:** `Torappu.Activity.Act13Side.UI`


## Fields

- `Text _textTitle`

- `Text _textProgress`

- `Text _textContent`

- `Image _imgChar`

- `GameObject _panelComplete`


## Methods

- `Void Render(String, DailyMissionData, String, DailyMissionProgress)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side.UI
public class Act13sideDecorMissionItemView : MonoBehaviour, IHotfixable
{
	private Text _textTitle; // 0x18
	private Text _textProgress; // 0x20
	private Text _textContent; // 0x28
	private Image _imgChar; // 0x30
	private GameObject _panelComplete; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3446954 VA: 0x7595a5e954
	public Void Render(String actId, DailyMissionData missionData, String principalChar, DailyMissionProgress progress) { }
	// RVA: 0x3446b0c VA: 0x7595a5eb0c
	public Void .ctor() { }
}
```