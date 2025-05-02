# ActMultiV3ManualStateBean

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3ManualProperty property`

- `Input input`


## Methods

- `Void InitData(String)`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualStateBean : IStateBean, IHotfixable
{
	public ActMultiV3ManualProperty property; // 0x10
	public Input input; // 0x18
	public HashSet`1 tempIdSet; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30f8910 VA: 0x7595710910
	public Void InitData(String actId) { }
	// RVA: 0x30f8a9c VA: 0x7595710a9c
	public Void LoadData() { }
	// RVA: 0x30facf4 VA: 0x7595712cf4
	public Void .ctor() { }
}
```