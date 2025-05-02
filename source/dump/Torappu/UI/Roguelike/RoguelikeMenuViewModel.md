# RoguelikeMenuViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Properties

- `Boolean isInit`


## Methods

- `Void set_isInit(Boolean)`

- `Void LoadData(String)`

- `Void AddCompViewModel(Type)`

- `RoguelikeMenuCompViewModel GetCompViewModel(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuViewModel : IHotfixable
{
	public Dictionary`2 data; // 0x10
	private static DelegateBridge __Hotfix0_set_isInit; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_AddCompViewModel; // 0x10
	private static DelegateBridge __Hotfix0_GetCompViewModel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isInit { set; }

	// RVA: 0x2a7f3dc VA: 0x75950973dc
	public Void set_isInit(Boolean value) { }
	// RVA: 0x2a7f560 VA: 0x7595097560
	public Void LoadData(String topicId) { }
	// RVA: 0x2a7f6f0 VA: 0x75950976f0
	public Void AddCompViewModel(Type type) { }
	// RVA: 0x2a7f820 VA: 0x7595097820
	public RoguelikeMenuCompViewModel GetCompViewModel(Type type) { }
	// RVA: 0x2a7f8bc VA: 0x75950978bc
	public Void .ctor() { }
}
```