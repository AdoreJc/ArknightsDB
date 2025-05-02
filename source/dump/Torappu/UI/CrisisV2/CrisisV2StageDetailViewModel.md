# CrisisV2StageDetailViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String seasonId`

- `String mapId`

- `String levelId`

- `String stageLogoId`

- `String stageCode`

- `String stageName`

- `String stageDesc`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2StageDetailViewModel : IHotfixable
{
	public String seasonId; // 0x10
	public String mapId; // 0x18
	public String levelId; // 0x20
	public String stageLogoId; // 0x28
	public String stageCode; // 0x30
	public String stageName; // 0x38
	public String stageDesc; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bf89ec VA: 0x75952109ec
	public Void LoadData(String mapId) { }
	// RVA: 0x2bf8b6c VA: 0x7595210b6c
	public Void .ctor() { }
}
```