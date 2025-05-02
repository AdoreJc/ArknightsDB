# RetroDB

**Namespace:** `Torappu`


## Methods

- `String GetRetroIdByZoneId(String)`

- `RetroActData GetActInfoNullable(String)`

- `String GetRetroIdByActId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RetroDB : ConstTable`2
{
	private Dictionary`2 m_actToRetroMap; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetRetroIdByZoneId; // 0x8
	private static DelegateBridge __Hotfix0_GetActInfoNullable; // 0x10
	private static DelegateBridge __Hotfix0_GetRetroIdByActId; // 0x18
	private static DelegateBridge __Hotfix0__FlushLevelsToDefault; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31f4710 VA: 0x759580c710
	protected override Void OnInit() { }
	// RVA: 0x31f4bd4 VA: 0x759580cbd4
	public String GetRetroIdByZoneId(String zoneId) { }
	// RVA: 0x31f4cc8 VA: 0x759580ccc8
	public RetroActData GetActInfoNullable(String retroId) { }
	// RVA: 0x31f4d98 VA: 0x759580cd98
	public String GetRetroIdByActId(String actId) { }
	// RVA: 0x31f4a58 VA: 0x759580ca58
	private static Void _FlushLevelsToDefault(RetroStageTable stageTable) { }
	// RVA: 0x31f4e34 VA: 0x759580ce34
	public Void .ctor() { }
}
```