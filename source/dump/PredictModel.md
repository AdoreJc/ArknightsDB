# PredictModel

**Namespace:** ` `


## Fields

- `String topicId`

- `TotemModel predictTotemModel`

- `ChaosModel predictChaosModel`


## Methods

- `Void LoadData(String, String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PredictModel : IHotfixable
{
	public String topicId; // 0x10
	public TotemModel predictTotemModel; // 0x18
	public ChaosModel predictChaosModel; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb4770 VA: 0x75951cc770
	public Void LoadData(String topicId, String predictChaosId, String predictTotemId) { }
	// RVA: 0x2bb4700 VA: 0x75951cc700
	public Void .ctor() { }
}
```