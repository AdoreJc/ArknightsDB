# RoguelikeCharInventoryStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeSelectCharProperty property`


## Methods

- `Void AttachPluginContexts(List`1)`

- `Void InitInventoryProperty(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharInventoryStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public RoguelikeSelectCharProperty property; // 0x18
	private List`1 m_pluginContexts; // 0x20
	private static DelegateBridge __Hotfix0_AttachPluginContexts; // 0x0
	private static DelegateBridge __Hotfix0_InitInventoryProperty; // 0x8
	private static DelegateBridge __Hotfix0__GetAllCharList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ac55d0 VA: 0x75950dd5d0
	public Void AttachPluginContexts(List`1 pluginContexts) { }
	// RVA: 0x2ac5750 VA: 0x75950dd750
	public Void InitInventoryProperty(String topicId) { }
	// RVA: 0x2ad0e04 VA: 0x75950e8e04
	private List`1 _GetAllCharList() { }
	// RVA: 0x2ad1364 VA: 0x75950e9364
	public Void .ctor() { }
}
```