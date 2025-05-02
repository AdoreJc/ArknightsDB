# DIYMedalModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `String id`

- `String name`

- `MedalSize size`


## Methods

- `Void LoadData(MedalPerData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class DIYMedalModel : IHotfixable
{
	public String id; // 0x10
	public String name; // 0x18
	public MedalSize size; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x276251c VA: 0x7594d7a51c
	public Void LoadData(MedalPerData data) { }
	// RVA: 0x276260c VA: 0x7594d7a60c
	public Void .ctor() { }
}
```