# CarvingMainChallengeInfoStateBean

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainChallengeInfoProperty m_prop`

- `Boolean m_isInfoState`


## Properties

- `Boolean isInfoState`

- `CarvingMainChallengeInfoProperty prop`


## Methods

- `Boolean get_isInfoState()`

- `CarvingMainChallengeInfoProperty get_prop()`

- `Void LoadData(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeInfoStateBean : IStateBean, IHotfixable
{
	private CarvingMainChallengeInfoProperty m_prop; // 0x10
	private Boolean m_isInfoState; // 0x18
	private static DelegateBridge __Hotfix0_get_isInfoState; // 0x0
	private static DelegateBridge __Hotfix0_get_prop; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isInfoState { get; }
	public CarvingMainChallengeInfoProperty prop { get; }

	// RVA: 0x2dac574 VA: 0x75953c4574
	public Boolean get_isInfoState() { }
	// RVA: 0x2dac0d8 VA: 0x75953c40d8
	public CarvingMainChallengeInfoProperty get_prop() { }
	// RVA: 0x2dac008 VA: 0x75953c4008
	public Void LoadData(String actId, Boolean isAutoPop) { }
	// RVA: 0x2dac9d8 VA: 0x75953c49d8
	public Void .ctor() { }
}
```