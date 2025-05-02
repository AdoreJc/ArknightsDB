# Activity3D5HelpView

**Namespace:** `Torappu.Activity.Act3D5`


## Fields

- `Text _dailyTaskTimeLabel`

- `Text _limitTaskTimeLabel`

- `Activity3D5HelpDailyItem _dailyItem`

- `Transform _limitContainer`

- `Activity3D5HelpLimitItem _limitItemPrefab`

- `String m_activityId`

- `Action m_close`


## Methods

- `Void Refresh(String, Action)`

- `Void _SynTime()`

- `Void OnClose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D5
internal class Activity3D5HelpView : MonoBehaviour, IHotfixable
{
	private Text _dailyTaskTimeLabel; // 0x18
	private Text _limitTaskTimeLabel; // 0x20
	private Activity3D5HelpDailyItem _dailyItem; // 0x28
	private Transform _limitContainer; // 0x30
	private Activity3D5HelpLimitItem _limitItemPrefab; // 0x38
	private List`1 m_limitItems; // 0x40
	private String m_activityId; // 0x48
	private Action m_close; // 0x50
	private static DelegateBridge __Hotfix0_Refresh; // 0x0
	private static DelegateBridge __Hotfix0__SynTime; // 0x8
	private static DelegateBridge __Hotfix0_OnClose; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32269dc VA: 0x759583e9dc
	public Void Refresh(String activityId, Action close) { }
	// RVA: 0x3226e38 VA: 0x759583ee38
	private Void _SynTime() { }
	// RVA: 0x32270bc VA: 0x759583f0bc
	public Void OnClose() { }
	// RVA: 0x3227184 VA: 0x759583f184
	public Void .ctor() { }
}
```