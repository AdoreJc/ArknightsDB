# Act25sideResearchConfirmViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String areaId`

- `String areaName`

- `Int32 dailyAddCount`

- `Int32 currentCount`

- `Int32 costCount`

- `Boolean isNotOpen`

- `Boolean isNotEnoughCount`


## Methods

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchConfirmViewModel : IHotfixable
{
	public String areaId; // 0x10
	public String areaName; // 0x18
	public Int32 dailyAddCount; // 0x20
	public Int32 currentCount; // 0x24
	public Int32 costCount; // 0x28
	public Boolean isNotOpen; // 0x2c
	public Boolean isNotEnoughCount; // 0x2d
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3279228 VA: 0x7595891228
	public Void LoadData(String actId, String areaId) { }
	// RVA: 0x3286dd8 VA: 0x759589edd8
	public Void .ctor() { }
}
```