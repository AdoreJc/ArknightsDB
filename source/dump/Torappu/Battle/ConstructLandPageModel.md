# ConstructLandPageModel

**Namespace:** `Torappu.Battle`


## Fields

- `String topicId`

- `String nodeId`

- `SandboxV2ConstructDetailModel detailModel`

- `JArray sceneOperations`


## Methods

- `Void AddOperation(JObject)`

- `Void Init(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ConstructLandPageModel
{
	public String topicId; // 0x10
	public String nodeId; // 0x18
	public SandboxV2ConstructDetailModel detailModel; // 0x20
	public JArray sceneOperations; // 0x28
	public Dictionary`2 catchedAnimals; // 0x30


	// RVA: 0x3fa6a74 VA: 0x75965bea74
	public Void AddOperation(JObject operationData) { }
	// RVA: 0x3fa6a90 VA: 0x75965bea90
	public Void Init(String topicId, String nodeId) { }
	// RVA: 0x3fa6974 VA: 0x75965be974
	public Void .ctor() { }
}
```