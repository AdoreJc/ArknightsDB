# ActivityFirstMissionView

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `Transform _missionContainer`

- `ActivityFirstMissionItem _missionItem`

- `UIStringEvent _stringEvent`


## Methods

- `Void InitData(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMissionView : MonoBehaviour, IHotfixable
{
	private Transform _missionContainer; // 0x18
	private ActivityFirstMissionItem _missionItem; // 0x20
	private UIStringEvent _stringEvent; // 0x28
	private List`1 m_missionList; // 0x30
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x348e4e4 VA: 0x7595aa64e4
	public Void InitData(List`1 missionList) { }
	// RVA: 0x349216c VA: 0x7595aaa16c
	public Void .ctor() { }
}
```