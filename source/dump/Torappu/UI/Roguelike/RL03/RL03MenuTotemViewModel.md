# RL03MenuTotemViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String topicId`

- `Boolean totemCanUse`

- `Boolean haveTotemDivination`

- `Boolean initProcessing`


## Methods

- `Boolean _CheckTotemsCanUse(String)`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MenuTotemViewModel : RoguelikeMenuCompViewModel
{
	public String topicId; // 0x18
	public Boolean totemCanUse; // 0x20
	public Boolean haveTotemDivination; // 0x21
	public Boolean initProcessing; // 0x22
	private List`1 m_totemViewModels; // 0x28
	private List`1 m_locationTotemViewModels; // 0x30
	private List`1 m_effectTotemViewModels; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__CheckTotemsCanUse; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ba10b8 VA: 0x75951b90b8
	public override Void LoadData(String topicId) { }
	// RVA: 0x2ba130c VA: 0x75951b930c
	private Boolean _CheckTotemsCanUse(String topicId) { }
	// RVA: 0x2ba1700 VA: 0x75951b9700
	public Void .ctor() { }
	// RVA: 0x2ba1770 VA: 0x75951b9770
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```