# SandboxV2DungeonZoneViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String zoneId`

- `String zoneName`

- `SandboxV2MapZoneData mapZoneData`

- `Boolean isShow`

- `Boolean unlocked`

- `SandboxV2WeatherType zoneWeatherType`


## Methods

- `Void LoadData(LoadParam)`

- `Void UpdateData(UpdateParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonZoneViewModel : IHotfixable
{
	public String zoneId; // 0x10
	public String zoneName; // 0x18
	public SandboxV2MapZoneData mapZoneData; // 0x20
	public List`1 nodes; // 0x28
	public Boolean isShow; // 0x30
	public Boolean unlocked; // 0x31
	public SandboxV2WeatherType zoneWeatherType; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25c269c VA: 0x7594bda69c
	public Void LoadData(LoadParam loadParam) { }
	// RVA: 0x25c2814 VA: 0x7594bda814
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25c28bc VA: 0x7594bda8bc
	public Void .ctor() { }
}
```