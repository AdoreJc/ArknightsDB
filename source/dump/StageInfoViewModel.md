# StageInfoViewModel

**Namespace:** ` `


## Fields

- `String zoneId`

- `String zoneName`

- `StringBuilder m_stageNameSb`


## Methods

- `String GetStageNamesStr()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StageInfoViewModel : IHotfixable
{
	public String zoneId; // 0x10
	public String zoneName; // 0x18
	public List`1 stageNames; // 0x20
	private StringBuilder m_stageNameSb; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetStageNamesStr; // 0x8


	// RVA: 0x2dc5e14 VA: 0x75953dde14
	public Void .ctor(String zoneId) { }
	// RVA: 0x2dc6054 VA: 0x75953de054
	public String GetStageNamesStr() { }
}
```