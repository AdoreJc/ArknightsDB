# AprilFoolStageData

**Namespace:** `Torappu`


## Fields

- `String stageId`

- `String levelId`

- `String code`

- `String name`

- `AppearanceStyle appearanceStyle`

- `String loadingPicId`

- `Difficulty difficulty`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class AprilFoolStageData
{
	public String stageId; // 0x10
	public String levelId; // 0x18
	public String code; // 0x20
	public String name; // 0x28
	public AppearanceStyle appearanceStyle; // 0x30
	public String loadingPicId; // 0x38
	public Difficulty difficulty; // 0x40
	public List`1 unlockCondition; // 0x48
	public List`1 stageDropInfo; // 0x50


	// RVA: 0x33befcc VA: 0x75959d6fcc
	public Void .ctor() { }
}
```