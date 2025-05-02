# Act9D0EntryMissionView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Text _missionText`

- `Image _progressBar`

- `Int32 m_missionNum`

- `Int32 m_missionSum`


## Methods

- `Void _LoadMissionData(Object)`

- `Void _TryLoadMissionData()`

- `Void _TryUpdateMission(Object)`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_BeforeUnload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0EntryMissionView : ActivityStageComponent, IHotfixable
{
	private Text _missionText; // 0x20
	private Image _progressBar; // 0x28
	private Int32 m_missionNum; // 0x30
	private Int32 m_missionSum; // 0x34
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_BeforeUnload; // 0x8
	private static DelegateBridge __Hotfix0__LoadMissionData; // 0x10
	private static DelegateBridge __Hotfix0__TryLoadMissionData; // 0x18
	private static DelegateBridge __Hotfix0__TryUpdateMission; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31a34ec VA: 0x75957bb4ec
	protected override Void OnLoaded() { }
	// RVA: 0x31a3778 VA: 0x75957bb778
	protected override Void BeforeUnload() { }
	// RVA: 0x31a367c VA: 0x75957bb67c
	public Void _LoadMissionData(Object _) { }
	// RVA: 0x31a3908 VA: 0x75957bb908
	private Void _TryLoadMissionData() { }
	// RVA: 0x31a3c58 VA: 0x75957bbc58
	private Void _TryUpdateMission(Object progress) { }
	// RVA: 0x31a3dd4 VA: 0x75957bbdd4
	public Void .ctor() { }
	// RVA: 0x31a3e4c VA: 0x75957bbe4c
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x31a3e54 VA: 0x75957bbe54
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```